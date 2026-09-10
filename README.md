# 🌐 Bagging Verification Frontend (GitHub Pages / Workstation)

A high-performance web interface designed for warehouse bagging workstations. It captures live video from an external USB camera, responds to barcode scanners, records in lightweight WebM VP9 (~300 kbps), and transmits footages directly to the Google Apps Script backend using a 100% CORS-free iframe postMessage bridge.

---

## 🚀 How to Host on GitHub Pages

1. Create a new GitHub repository (e.g. `bagging-camera-bridge`).
2. Push the files in this folder (`index.html`) to the `main` branch.
3. In your GitHub repository:
   - Go to **Settings** ➔ **Pages**.
   - Under **Build and deployment** ➔ Select **Deploy from a branch** (Branch: `main`, folder: `/root`).
   - Click **Save**.
4. Open your live GitHub Pages link (e.g. `https://your-username.github.io/bagging-camera-bridge/`).
5. On the first launch:
   - Click the **⚙️ Settings** icon in the top right.
   - Paste your deployed **Google Apps Script Web App URL** (`https://script.google.com/macros/s/.../exec`).
   - Click **Save URL**.

---

## 💻 How to Run Locally on Workstation

You can also run this locally on your station without hosting:
1. Open this folder in terminal / command prompt.
2. Run `npx serve .` or `python -m http.server 8080`.
3. Open `http://localhost:8080` in Chrome!
