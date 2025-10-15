# 🚶‍♀️ SafeWalk: Night Safety Companion

**SafeWalk** is a web-based night safety tool built using **HTML**, **CSS**, and **JavaScript**. It allows users—especially solo night travelers—to access essential tools like live location tracking, emergency alerts, and a flashlight/alarm system in just one click.

>  **Live Preview:** [https://safewalk.netlify.app/](https://safewalk.netlify.app/)

---

##  Tools Used

- **HTML** – for the page structure  
- **CSS** – for responsive and modern UI  
- **JavaScript** – for geolocation, alarm, and flashlight logic  

---

##  Key Features with Screenshots

###  1. Nearest Police Station Detection

This section uses the **Geolocation API** to detect your live coordinates and calculate the nearest police station using the **Haversine Formula**. After detection, it shows:
- Your current latitude and longitude
- The name, address, and coordinates of the closest police station
- A button to get **Google Maps directions**

📸 **Screenshot:**

![Nearest Police Station Detection](Image%201.jpg)

---

### 🔧 2. Built-in Safety Tools: Flashlight, Alarm, Emergency SMS

This section offers three one-click safety tools:
- **Flashlight**: Turns the screen white to provide visibility in dark areas
- **Alarm**: Plays a loud siren to draw attention
- **Send SMS**: Launches the default SMS app pre-filled with a distress message to police

📸 **Screenshot:**

![Flashlight, Alarm, Emergency SMS](Image%202.jpg)

---

### ❓ 3. What to Do If… (Emergency Tips Section)

This section gives quick actionable safety advice for real-world scenarios:
- **If followed** – go to a crowded area, use the alarm, call police
- **If harassed** – shout for help, call the police
- **If lost** – stay calm, find a landmark, and contact security

📸 **Screenshot:**

![What to Do If](Image%203.jpg)

---

### ☎️ 4. Emergency Numbers List

A quick-access section to the most essential national emergency contact numbers:
- Police: `100`
- Women Helpline: `1091`
- Ambulance: `102`

📸 **Screenshot:**

![Emergency Numbers](Image%204.jpg)


---

##  How It Works

1. On clicking **"Detect My Location"**, the app:
   - Uses Geolocation API to get latitude and longitude
   - Matches the nearest police station using Haversine formula
   - Displays name, address, and Google Maps link

2. The **Flashlight** button toggles a bright screen overlay.
3. The **Alarm** plays a looping siren from `alarm.mp3`.
4. The **SMS** button opens the default messaging app with an SOS message ready to send to the police.

---

##  Improvements for Future

- Replace static police station data with **real-time API integration**
- Add **voice command** support for hands-free emergency activation
- Include **user login** and **tracking logs** for personal safety history
- Integrate **weather and area alerts** for smarter navigation

---

##  Developed By

**Prashant Kumar**  

- 💼 LinkedIn :  [LinkedIn](https://www.linkedin.com/in/prashant-kumar-268484329)  
- 🛠️ Github :  [GitHub](https://github.com/PrashantKumar026)  
- 📧 Email: [prashantkumar02026@gmail.com](mailto:prashantkumar02026@gmail.com)

---

## Note :

This project is free to use for educational and real-time results an API like Google Places API should be integrated.


