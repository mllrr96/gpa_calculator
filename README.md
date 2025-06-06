# GPA Calculator 📊

[![Try It Online](https://img.shields.io/badge/Live%20Demo-Web%20App-blue?logo=flutter&logoColor=white)](https://mllrr96.github.io/Gpa-Calculator/)

A simple Flutter app that helps AUIS students calculate their GPA based on letter grades and credit hours.

> 🎓 **Note:** This app is specifically designed for students of [The American University of Iraq, Sulaimani (AUIS)](https://auis.edu.krd/), and follows the official GPA calculation policy described in [How to Calculate Your GPA](https://auis.edu.krd/how-calculate-your-gpa).

## 🚀 Features

- Dynamic course entry
- Grade-to-point calculation
- Support for both Undergraduate (UG) and MBA grading rules
- Responsive design
- Light/Dark mode support

## 🎓 UG vs MBA GPA Rules

- ✅ **UG**: Allows grades from A to F (including C-, D+, D)
- ✅ **MBA**: Only allows grades from A to C and F. Fixed 2-credit hours per course.
- ⚠️ Disallowed grades in MBA mode are automatically removed from selection

## 🖼️ Screenshots

<table>
  <tr>
    <th>Home Screen</th>
    <th>Grade Entry</th>
    <th>GPA Result</th>
  </tr>
  <tr>
    <td><img src="https://github.com/mllrr96/gpa_calculator/blob/main/screenshots/Home-Empty.png" width="400"/></td>
    <td><img src="https://github.com/mllrr96/gpa_calculator/blob/main/screenshots/Home.png" width="400"/></td>
    <td><img src="https://github.com/mllrr96/gpa_calculator/blob/main/screenshots/Result.png" width="400"/></td>
  </tr>
</table>

## 🌐 Try It Online

Want to test the GPA Calculator without installing anything?

**[Launch the Web App](https://mllrr96.github.io/Gpa-Calculator/)**  
Runs entirely in your browser — no setup needed.

## 📥 Download APK for Android devices

You can download the APK file for Android devices from the [Releases Page](https://github.com/mllrr96/gpa_calculator/releases/)

## 📦 Build from Source

### Clone the repository to your local machine
```bash
git clone https://github.com/mllrr96/gpa_calculator.git
```

### Move into the project directory
```bash
cd gpa-calculator
```

### Install all the required Flutter packages
```bash
flutter pub get
```

### Run the app on your connected device or emulator
```bash
flutter run
```
