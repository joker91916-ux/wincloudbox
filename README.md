# ☁️ Cloud Computer (Windows 2025 + AnyViewer)

Spin up your own **Windows 2025 Cloud Computer** inside GitHub Actions!  
This workflow installs **AnyViewer** with a fixed password and keeps the session alive for **6 hours**.  
You can connect remotely just like a personal cloud PC. 🚀

---

## 🔑 Features
- Runs on **Windows Server 2025 GitHub runner**
- Installs & configures **AnyViewer**
- Fixed password: `bear`
- Prints your **Device ID** + **Password** in the logs
- Keeps session alive for **6 hours**

---

## 🖥️ How to Use
1. Go to the **Actions** tab in this repo.
2. Run the workflow **Cloud Computer** manually.
3. Wait until the `Show AnyViewer Info` step — copy the **Device ID**.
4. Download the [AnyViewer desktop app](https://www.anyviewer.com/download.html).
5. Connect with:
   - **Device ID:** from workflow logs
   - **Password:** `bear`
   - **Port:** default (handled automatically)

---

## ⏳ Session Time
- Each run lasts **6 hours** (GitHub runner limit).
- You can restart the workflow anytime for a fresh session.

---

## ⚠️ Notes
- This is for **personal / educational use only**.
- Files and settings are reset after each run (ephemeral runner).
- Do not store sensitive data here — treat it like a disposable VM.

---

## 🚀 Example Use Cases
- Try Windows Server 2025 in the cloud
- Run apps without installing locally
- Quick development / testing sandbox
- Remote demo environments

---
