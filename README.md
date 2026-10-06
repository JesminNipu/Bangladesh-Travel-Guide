# Bangladesh Travel Guide (BTG) / Tourist Guide

[![Platform: Android](https://img.shields.io/badge/Platform-Android-green.svg)](https://developer.android.com/)
[![Language: Java](https://img.shields.io/badge/Language-Java-orange.svg)](https://www.java.com/)
[![Backend: PHP & MySQL](https://img.shields.io/badge/Backend-PHP%20%26%20MySQL-blue.svg)](https://www.php.net/)
[![Report: B.Sc. Thesis](https://img.shields.io/badge/Documentation-B.Sc.%20Report%20(PDF)-red.svg)](./Bsc%20Report%20of%20Jesmin%20Akther.pdf)
[![Journal: JARMC 2021](https://img.shields.io/badge/Publication-JARMC%202021-purple.svg)](https://jesminnipu.github.io/Portfolio/#publications)

An end-to-end native Android mobile application designed to provide real-time tourism navigation, localized city guidance, dynamic weather forecasting, and emergency facility lookups across the administrative divisions of Bangladesh.

---

## 📄 Academic Project Report

This repository contains the official undergraduate Bachelor of Science (B.Sc.) project and thesis report:

* **Document:** [**B.Sc. Report of Jesmin Akther.pdf**](./Bsc%20Report%20of%20Jesmin%20Akther.pdf)
* **Author:** **Jesmin Akther**
* **Institution:** Department of Information and Communication Engineering (ICE), **Noakhali Science and Technology University (NSTU)**, Bangladesh

### 📑 Associated Publication

> **Akther J.**, Harun-or-roshid M., Mahbub-or-rashid M., Soheli S.J.  
> *"Bangladesh travel guide (BTG) an android mobile application to utilize free time in a better way."*  
> **Journal of Advance Research in Mobile Computing**, 2021; 3(1): 1–10.

---

## 🌟 Overview & Objectives

The **Bangladesh Travel Guide (BTG)** application was developed to empower tourists and travelers with localized, reliable, and real-time information when exploring Bangladesh. By consolidating fragmented travel data into an intuitive mobile interface, the system eliminates the dependency on traditional physical guidebooks and unreliable travel sources.

### Key Objectives:
- Provide GPS-assisted location tracking and interactive map navigation to tourist attractions.
- Deliver localized weather forecasts to assist tourists in itinerary planning.
- Offer dynamic access to facilities, including hotels, restaurants, transportation services, and emergency amenities.
- Minimize mobile bandwidth consumption and server latency through lightweight RESTful API endpoints.

---

## 🚀 Key Features

* **🗺️ Interactive Map Navigation:** Integrated with the **Google Maps API** and GPS location services to offer turn-by-turn guidance and pinpoint tourist spots across divisions and districts.
* **🌦️ 16-Day Weather Forecasting:** Connected to the **OpenWeatherMap API** to retrieve dynamic weather conditions, temperature, humidity, and forecast data.
* **🏛️ Comprehensive Tourist Spot Directory:** Categorized listings of cultural, historical, archaeological, and natural destinations throughout Bangladesh.
* **🏨 Accommodations & Dining:** Detailed directory of nearby hotels, resorts, and restaurants with contact details and location markers.
* **🚨 Emergency Amenities:** Quick-access emergency contacts, police stations, hospitals, and local administrative offices.
* **⚡ Optimized API & Network Layer:** Asynchronous HTTP request processing with cached JSON data parsing for smooth operation even in low-bandwidth rural environments.

---

## 🛠️ System Architecture & Technologies

| Layer | Technologies & Tools |
| :--- | :--- |
| **Mobile Client** | Native Android SDK, Java, XML Layouts |
| **APIs & Services** | Google Maps API, Google Play Services Location, OpenWeatherMap API |
| **Backend Server** | PHP RESTful APIs, Apache (WampServer) |
| **Database** | MySQL |
| **Data Format** | JSON |
| **IDE & Build** | Android Studio, Gradle |

---

## 📂 Repository Structure

```text
Touristguide/
├── Bsc Report of Jesmin Akther.pdf   # Official B.Sc. project/thesis documentation
├── README.md                          # Repository documentation and project guide
├── app/
│   ├── src/main/
│   │   ├── java/com/example/nipu/touristguide/
│   │   │   ├── activity/             # Android Activity screens (Home, Detail, Maps, etc.)
│   │   │   ├── adapters/             # Custom List and RecyclerView adapters
│   │   │   ├── firstablayout/        # Tab navigation layout managers
│   │   │   ├── modelclass/           # Data models (Spot, Hotel, Weather, Location)
│   │   │   ├── network/              # REST API request handlers & JSON parsers
│   │   │   ├── otherclass/           # Helper utilities and background tasks
│   │   │   └── service/              # Background location & network services
│   │   ├── res/                      # Layout XMLs, drawables, menus, and string resources
│   │   └── AndroidManifest.xml       # App configuration and permissions
├── build.gradle                       # Project-level Gradle build script
└── settings.gradle                    # Gradle project settings
```

---

## 💻 Getting Started

### Prerequisites
1. **Android Studio** (Electric Eel or newer recommended)
2. **Java Development Kit (JDK 8 or JDK 11)**
3. Android Virtual Device (AVD) or physical Android device running Android 5.0+ (API level 21+)
4. Active **Google Maps API Key**

### Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/JesminNipu/Touristguide.git
   ```
2. **Open in Android Studio:**
   - Launch Android Studio, select **Open**, and navigate to the cloned directory.
3. **Configure API Keys:**
   - In `app/src/main/res/values/strings.xml` or `AndroidManifest.xml`, replace the placeholder with your valid Google Maps API Key:
     ```xml
     <string name="google_maps_key">YOUR_GOOGLE_MAPS_API_KEY</string>
     ```
4. **Sync Gradle & Run:**
   - Allow Gradle to sync dependencies, then click **Run** (`Shift + F10`) to build and deploy to your connected device or emulator.

---

## 👩‍💻 Author & Contact

**Jesmin Akther**  
Mobile Application Developer & Computer Science Researcher  
* Department of Information and Communication Engineering, NSTU  
* **Email:** [jesminnipu1@gmail.com](mailto:jesminnipu1@gmail.com)  
* **GitHub:** [@JesminNipu](https://github.com/JesminNipu)  
* **Portfolio:** [https://jesminnipu.github.io/Portfolio/](https://jesminnipu.github.io/Portfolio/)
