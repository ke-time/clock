# Ke Time - A New Way to Track Time

### What is Ke Time?
Ke Time is an alternative timekeeping system that divides the day into **100 equal parts**, called **Ke**.  
Each **Ke** consists of **16 short minutes (shm)**, and each short minute contains **54 seconds**.  

This system allows for a **percentage-based** approach to tracking time, making it intuitive for scheduling, productivity, and personal time management.

- **Midday = 35 Ke** (meaning the Ke day starts at **03:36:00 AM**).
- The system is **anchored to local time zones**, so it aligns naturally with your daily routine.

---

### Features of This Implementation
- 📊 **Live Ke Time Display** – Shows both **percentage format** (`XX.XX% Ke`) and full time (`Ke, shm, sec`).
- 🎨 **Visual Pie Chart** – Displays the **elapsed vs. remaining Ke day**.
- 🏷 **Key Markers on the Chart** – Labels for **Midday, Midnight, Sunrise, Sunset**, as well as **00%, 25%, 50%, 75%**.
- 🌍 **Sunrise & Sunset Calculation** – Uses **geolocation** (with permission) to display **local sunrise & sunset** in Ke Time.
- 🔗 **Fully Web-Based** – Works in modern browsers with **JavaScript & HTML5 Canvas**.

---

### How It Works
- **JavaScript** calculates Ke Time based on your local system clock.
- **Canvas API** dynamically updates the pie chart with real-time progress.
- **Geolocation API** fetches the user's location (if allowed) to retrieve **sunrise & sunset** data.
- **Sunrise-Sunset API** provides local sunrise/sunset times, converted into Ke Time.

---

### Why Use Ke Time?
- **Easier Daily Progress Tracking** – Time is a percentage of your day.
- **No Need to Convert Hours & Minutes** – It’s all proportional.
- **Aligns with Human Perception of Time Flow** – More intuitive than AM/PM or 24-hour clocks.
- **Great for Productivity & Scheduling** – Quickly see how much of your day is left.

---

### How to Use
1. **Visit the live page:** [https://ke-time.github.io/clock/](https://ke-time.github.io/clock/)
2. **Allow location access** (for sunrise & sunset calculations).
3. **Check your Ke Time** in both percentage and full Ke format.
4. **View the Pie Chart** to see elapsed & remaining time.
5. **Use Ke Time for planning & tracking your day!

---

### Future Enhancements
🚀 Potential features for future versions:
- **Custom alarms & reminders** based on Ke Time.
- **User-selectable time zones** for checking Ke Time in other locations.
- **Mobile-friendly enhancements** & offline support.

---

### Contributing
If you'd like to contribute, feel free to **fork the repo** and submit pull requests!  
For discussions or feedback, reach out via GitHub.

---

### License: The Unlicense
This project is released under **The Unlicense**.  
You are **free to use, modify, and distribute this project without attribution**.  
No restrictions—do whatever you like with it! 🚀

For more details, see [https://unlicense.org/](https://unlicense.org/).

---
