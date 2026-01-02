# Birthday Age Calculator

A Kotlin Compose Desktop application that calculates your age based on your birthday.

## Features

- **Birthday Input**: Select your birth date using three dropdown menus for Month, Day, and Year
- **Smart Date Handling**: Days automatically adjust based on the selected month and year (including leap years)
- **Precise Age Calculation**: Displays age in years, months, and days
- **Age Categories**: Shows a fun category based on your age:
  - 0-12: Youngster
  - 13-19: Teenager
  - 20-40: Adult
  - 41-61: Middle-Aged Adult
  - 62-74: Senior Citizen
  - 75-84: Very Senior Citizen
  - 85+: Really Old

## Requirements

- JDK 11 or higher
- Gradle 8.x

## Running the Application

### Windows
```shell
.\gradlew.bat :composeApp:run
```

### macOS/Linux
```shell
./gradlew :composeApp:run
```

## Tech Stack

- Kotlin
- Compose Multiplatform (Desktop/JVM)
- Material 3
