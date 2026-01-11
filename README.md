
---

## 🚗 Vehicle Intelligence Tool

**Vehicle Intelligence Tool** is a lightweight OSINT utility that allows users to look up vehicle registration (RC) details using a public API and view the results in a clean, SOC-style interface. It is built for **cybersecurity students, OSINT researchers, and digital investigators** to practice real-world data collection, logging, and analysis in a safe and ethical way.

---

## 🐉 Kali Linux — Setup Guide (From Zero)

### 1️⃣ Update Kali

```bash
sudo apt update
```

---

### 2️⃣ Install required packages

```bash
sudo apt install python3 python3-pip python3-rich python3-requests git -y
```

---

### 3️⃣ Download the project from GitHub

```bash
git clone https://github.com/bhatt-saahab/PROJECT-vehicle-intelligence.git
cd PROJECT-vehicle-intelligence
```

---

### 4️⃣ Run the tool

```bash
python3 vehicleintel.py
```

or

```bash
./vehicleintel.py
```

---

### 5️⃣ Enter RC number

Example:

```
GJ01AB1234
```

---

### 📁 Output folders

All data will be automatically saved in:

```
results/   → Vehicle lookup results (JSON)
logs/      → Search activity logs
cache/     → Cached API responses
```

---

