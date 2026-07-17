<div align="center">

# 𝗢𝗜𝗢𝗜𝗢𝗜𝗚𝗥𝗔𝗠

### 🔍 Instagram OSINT (Open Source Intelligence) Tool

A powerful command-line tool for gathering and analyzing publicly available Instagram information for **OSINT**, **cybersecurity research**, and **educational purposes**.

**Language:** Python 3.x  
**Platform:** Linux (Ubuntu, Kali Linux, Debian)  
**License:** MIT

</div>

---

# 📖 Overview

**OIOIOIGRAM** is an Instagram OSINT tool designed to collect publicly available information from Instagram profiles. It provides detailed profile information, post metadata, hashtags, and other useful data for security researchers, investigators, and OSINT enthusiasts.

---

# ✨ Features

## 👤 Profile Information

The tool can collect:

- Username
- Profile Name
- Profile URL
- Followers Count
- Following Count
- Number of Posts
- Biography
- Profile Picture URL
- Business Account Status
- Connected to Facebook Account
- External Website URL
- Recently Joined Status
- Business Category
- Private Account Status
- Verified Status

---

## 🏷️ Hashtag Analysis

- Most Used Hashtags
- All Used Hashtags (`-t`)

---

## 📷 Post Information

For every public post, the tool can retrieve:

- Accessibility Caption
- Caption
- Upload Timestamp
- Location
- Comments Disabled Status
- Image URL

---

# ⚙️ Prerequisites

- Python 3 or higher
- Linux Operating System
  - Ubuntu
  - Kali Linux
  - Debian

---

# 🚀 Getting Started

## Clone the Repository

```bash
git clone https://github.com/SakshamSinghSachan/oioioigram.git
cd oioioigram
```

## Create a Virtual Environment

```bash
python3 -m venv venv
```

Activate it:

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Tool

```bash
python3 main.py --username targetusername
```

---

# 💻 Usage

```bash
python3 main.py [OPTIONS]
```

| Option | Description |
|---------|-------------|
| `-h`, `--help` | Show help message |
| `-u`, `--username USERNAME` | Username of the Instagram account to scan |
| `-p`, `--postscrap` | Scrape information from uploaded posts |
| `-s`, `--savedata` | Save profile information, profile picture, and post information |

---

# 📂 Output

The tool can save:

- Profile Information
- Profile Picture
- Post Information
- Image URLs
- Hashtag Analysis

---


---

# ⚠️ Disclaimer

This project is intended **strictly for educational purposes, authorized security testing, and Open Source Intelligence (OSINT) research**.

Only collect information from accounts where you have permission or where the information is publicly available. Users are responsible for complying with applicable laws, platform terms of service, and ethical guidelines.

The author is **not responsible** for any misuse of this software.

---

# 📜 License

This project is licensed under the **MIT License**.

See the `LICENSE` file for more information.

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a Star!

Developed by **Saksham Singh Sachan** ❤️

GitHub Repository: https://github.com/SakshamSinghSachan/oioioigram

</div>
