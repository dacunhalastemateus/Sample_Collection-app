# Sample Collection App

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23077056.svg)](https://doi.org/10.5281/zenodo.23077056)
[![Platform: AppSheet](https://img.shields.io/badge/Platform-AppSheet-blue.svg)](https://www.appsheet.com)

> An AppSheet mobile and web application designed to support field sample collection for passive eDNA and plankton net sampling.

[🚀 **Open the App in Browser**](https://www.appsheet.com/start/46dc33df-247e-4086-80cc-35d65848b817) &nbsp;|&nbsp; [💾 **Copy the App Template**](https://www.appsheet.com/Template/AppDef?appName=Sample_Collection-680552420-26-09-14&utm_source=share_app_link)

---

## 📌 Overview

This app supports field sample collection for passive eDNA and plankton net samples conducted by researchers in our lab, designed to accommodate their pre-existing horizontal data structure.

## 🎯 Objectives

* **Streamline Fieldwork:** Facilitate and standardize the sample collection process.
* **Reduce Errors:** Minimize human entry mistakes and reduce time consumption in the field.
* **Enable Collaboration:** Allow multiple teams to collect and process sample data simultaneously.

## ✨ Key Features

* **Multilingual Support:** Built-in multi-language translation method managed through the `'Translations'` table.
* **Full Access Management:** Security filters managed through the `'Access Management'` table.
* **Proximity-Based Pre-Filling:** Auto-fills variables based on GPS proximity to pre-existing location data.
* **Automated Batch Processing:** Automatic sample copying and bulk editing managed by AppSheet Bots based on researcher protocols.
* **Sequential Sample Naming:** Standardized naming logic and sequences paired with independent `UNIQUEID("UUID")` keys.
* **Precise Location:** Automatic, GPS-based pre-filling of `Geographic_Origin` and `Collection_Location` variables by filtering existing data in the `UIMS` datasheet.

---

## ⚙️ Setup & Customization

Follow these three steps to deploy and adapt the app to your needs:

1. **Upload Data Source:** Copy and upload the `HOME.xlsx` file to the Google Drive folder where you want your app data to reside.
2. **Copy the App:** Click the **[Copy the App Template](https://www.appsheet.com/Template/AppDef?appName=Sample_Collection-680552420-26-09-14&utm_source=share_app_link)** link above to clone the application into your AppSheet account.
3. **Connect Data Source:** In the AppSheet editor, change the data source location to point to your copy of `HOME.xlsx` in Google Drive.

---

## 📖 Citation

If you use this application or adapt its structure for your research, please cite it as follows:

**DOI:** [10.5281/zenodo.23077056](https://doi.org/10.5281/zenodo.23077056)

```text
Sample Collection App [Computer software]. Zenodo. [https://doi.org/10.5281/zenodo.23077056](https://doi.org/10.5281/zenodo.23077056)


