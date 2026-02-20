# 🎂 AutoWish

A lightweight Android utility that reminds you of birthdays and anniversaries from a simple CSV file and helps you send wishes via WhatsApp with a single tap.

---

## 📲 1. How to Install
Since this app is distributed directly (Sideloaded), follow these steps:

1. **Download the APK** to your phone.
2. **Tap the file** to install. 
3. If your phone says *"Blocked by Play Protect"*, tap **More Details** and then **"Install Anyway."**
4. **Grant Permissions:** Allow the app to send **Notifications** when prompted.

> [!IMPORTANT]
> **Battery Optimization:** The app will ask to **Ignore Battery Optimizations**. Please select **"Allow"** or **"Unrestricted."** This ensures the app wakes up every hour to check for events even if the phone is idle.
> 
---

## 📄 2. Preparing Your Data (CSV Format)
The app reads a simple **Comma-Separated** text file. 

**The file must follow this structure (Date, Name, Event):**
```csv
20-02, Bumrah, Birthday
20-02, Rohit, Wedding Anniversary
21-02, Virat, Birthday

---

## 📄 2. Preparing Your Data (CSV Format)
The app reads a simple **Comma-Separated** text file. 

**The file must follow this structure (Date, Name, Event):**
```csv
20-02, Bumrah, Birthday
20-02, Rohit, Wedding Anniversary
21-02, Virat, Birthday

## ❓ Troubleshooting

* **No Alerts?**
  Android's "Battery Saver" often kills background tasks. Go to **Settings > Apps > Celebration Notifier > Battery** and ensure it is set to **"Unrestricted"**.

* **Not Notifying Multiple Times?**
  The app is designed to be smart. Once it notifies you about a specific person, it marks them as "Notified" for that day. It will not buzz you again for the same person until the next day.

* **WhatsApp doesn't open?**
  Ensure WhatsApp is installed on your device. The app uses a standard "Send" link; if WhatsApp is missing, the link will not have an app to open.

* **Formatting Errors?**
  Ensure your CSV file uses commas (`,`) and not semicolons (`;`). Also, ensure the date format is exactly `DD-MM` (e.g., 20-02).

### 📄 Template File
You can download a sample [Data.csv](./Data.csv) to use as a starting point.
