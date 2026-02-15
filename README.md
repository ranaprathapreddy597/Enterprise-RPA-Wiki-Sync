# 🤖 Enterprise Web-Scraper Bot (RPA)
**Built with Automation Anywhere (A360)**

This Robotic Process Automation (RPA) solution automates the extraction of dynamic data from web sources (like Wikipedia) and synchronizes it with Google Sheets for real-time tracking.

### 🎥 Execution Demo
> **https://drive.google.com/file/d/1shtBLHj8Z7qhBPIc0JcZzu4f_mGZiLGQ/view?usp=drivesdk**
> *Due to file size and A360 Community Edition export constraints, please view the video above for the full end-to-end execution.*

### 🛠️ Bot Logic & Architecture
* **Step 1: Environment Setup** – Initializes the browser and navigates to the target URL.
* **Step 2: Data Extraction** – Utilizes the `Recorder: Capture` package to pull specific table data and attributes.
* **Step 3: Data Transformation** – Formats the extracted text to ensure clean data entry.
* **Step 4: Integration** – Uses the `Google Sheets Package` to authenticate and seamlessly append rows to the live sheet.

---
**Developer:** Rana Prathap Reddy | **CSE Student**
