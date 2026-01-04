⏱️ Time Tracker & Productivity Analytics – Chrome Extension
📌 Project Overview
This project is a Chrome Extension developed to track time spent on websites and analyze user productivity.
The extension automatically monitors the active browser tab, records the duration spent on each website, classifies them as Productive or Unproductive, and displays analytics through a popup and dashboard.
This project helps users understand their browsing habits and improve productivity.
🎯 Objectives
Track time spent on different websites
Categorize websites as productive or unproductive
Store browsing data locally
Display real-time productivity statistics
Provide a detailed analytics dashboard
Improve time management and focus
🛠️ Technologies Used
HTML5
CSS3
JavaScript
Chrome Extension API (Manifest V3)
Chrome Storage API
🔍 Features
✅ Automatic Time Tracking
Tracks time spent on each active website
Saves data automatically at regular intervals
✅ Website Classification
Productive websites: GitHub, LeetCode, StackOverflow
Unproductive websites: YouTube, Instagram, Facebook
Neutral category for other websites
✅ Popup View
Displays total productive time
Displays total unproductive time
Accessible via extension icon
✅ Dashboard Analytics
Detailed table of websites visited
Time spent on each website
Productivity classification
✅ Local Data Storage
Uses chrome.storage.local
No backend required
⚙️ How the Extension Works
Detects the currently active tab
Starts counting time
Saves time periodically (every few seconds)
Classifies website type
Stores data locally
Displays results in popup & dashboard
