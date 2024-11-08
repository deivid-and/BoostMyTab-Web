
# 🚀 BoostMyTab

BoostMyTab is a tool designed to optimize and enhance Android tablet performance. With a simple interface, it lets you run optimization scripts, manage system processes, and control the tablet remotely using `scrcpy`.

---

## ⚡ Quick Start for End Users

### 1. **Download and Run**:
   - 🔽 **Download** the `BoostMyTab.exe` file.
   - 📂 **Run** the Application by double-clicking `BoostMyTab.exe`.

### 2. **Access the Application**:
   - 🌐 Open your web browser and go to **[http://127.0.0.1:5000]**.

### 3. **Ensure Device Access**:
   - 🔧 Enable **USB debugging** on your tablet and confirm authorization for BoostMyTab.

---

## ✨ Features

- 🛠️ **Manage Processes**: Enable/disable Google, Samsung, and miscellaneous bloatware.
- 🚀 **Optimize Performance**: Adjust power settings, brightness, CPU mode, animations, and network settings.
- 🖥️ **System Management**: Reboot, enter recovery mode, list connected devices, and access the tablet remotely.

---

## 🛠️ Developer Setup (GitHub Version)

### 1. **Clone the Repository**:
   ```bash
   git clone https://github.com/deivid-and/BoostMyTab.git
   cd BoostMyTab
   ```

### 2. **Set Up Environment**:
   #### On Windows:
   ```bash
   python -m venv venv
   venv\Scripts\activate
   pip install -r requirements.txt
   ```
   #### On Linux/Mac:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

### 3. **Run the App**:
   ```bash
   flask run
   ```

### 4. **Access the Application**:
   - 🌐 Go to [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.
