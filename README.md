
# Simple Calculator

## Introduction
The **Simple Calculator** is an Android application designed to perform basic arithmetic operations including addition, subtraction, multiplication, and division. This lightweight app offers a user-friendly interface and demonstrates the fundamentals of Android app development using Java.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [Examples](#examples)
- [Troubleshooting](#troubleshooting)
- [Contributors](#contributors)
- [License](#license)

## Features
- Basic arithmetic operations (Addition, Subtraction, Multiplication, Division)
- Simple and intuitive user interface
- Landscape and portrait layout support
- Basic error handling for invalid inputs

## Installation
To set up the project locally:

1. Clone or download the repository.
2. Open the project in **Android Studio**.
3. Sync the Gradle files.
4. Build and run the application on an emulator or physical device.

```sh
git clone <repository-url>
```

## Usage
- Launch the app.
- Use the numeric keypad to enter numbers.
- Tap the operation buttons (+, -, ×, ÷) to perform calculations.
- View the results instantly on screen.

## Project Structure
```
simple-calculator-master/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   ├── id/marfinabumalikah/calculator/
│   │   │   │   │   ├── MainActivity.java
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   ├── activity_main.xml
│   │   │   │   ├── values/
│   │   │   │   │   ├── strings.xml
│   │   │   │   │   ├── colors.xml
│   │   │   │   │   ├── styles.xml
│   ├── build.gradle
├── build.gradle
├── settings.gradle
└── gradle/
```

## Dependencies
The project uses the following dependencies (from `build.gradle`):

```gradle
dependencies {
    implementation 'com.android.support:appcompat-v7:28.0.0'
    testImplementation 'junit:junit:4.13.2'
    androidTestImplementation 'androidx.test.ext:junit:1.1.5'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.5.1'
}
```

## Configuration
### Minimum Requirements
- **Android Studio:** Arctic Fox or later
- **Gradle Version:** 7.x
- **Minimum SDK:** 21 (Lollipop)
- **Target SDK:** 33

### Gradle Wrapper
The project includes Gradle wrapper scripts for simplified builds:

- `gradlew` (Linux/macOS)
- `gradlew.bat` (Windows)

## Examples
The main calculator screen contains:
- Number buttons (0-9)
- Operation buttons (+, -, ×, ÷)
- Clear and Equals buttons
- TextView to display the calculation and result

## Troubleshooting
- **Gradle Sync Issues:** Ensure you have the correct Gradle version installed (check `gradle-wrapper.properties`).
- **Missing Dependencies:** Click on "Sync Project with Gradle Files" in Android Studio.
- **Emulator Issues:** Ensure your emulator has Google Play services installed if required.

## Contributors
- **Marfin**

## License
This project is licensed under the MIT License.
