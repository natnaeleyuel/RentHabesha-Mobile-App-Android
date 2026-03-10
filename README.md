# RentHabesha Traditional Clothing Renting Mobile App

RentHabesha is a mobile application designed to simplify the rental process for traditional Ethiopian clothing. The project combines an **Android frontend built with Kotlin** and a **backend powered by JavaScript and Express**, allowing clothing owners, boutiques, and renters to interact through a practical digital rental platform while promoting Ethiopian cultural heritage.

## Project Overview

The application serves as a marketplace for traditional Ethiopian clothing rentals. It supports listing management, user account operations, and administrative controls, making it a complete mobile-and-backend project rather than a small standalone app.

## Team Information

- **Section:** 2
- **Group Members:**
  - **Feven Muluken** - `UGR/8442/15`
  - **Mekdelawit Gebre** - `UGR/1386/15`
  - **Natnael Eyuel** - `UGR/4424/15`
  - **Sifen Biyadgelgn** - `UGR/4937/15`
  - **Yeabsera Tilahun** - `UGR/1418/12`

## Contents

- **`app/`**: Android application module containing Kotlin source code, screens, resources, and app configuration.
- **`rent-habesha-backend/`**: Backend project directory for server-side logic and API functionality.
- **`gradle/`**: Gradle wrapper and Android build support files.
- **`build.gradle.kts`**: Project-level Gradle configuration.
- **`settings.gradle.kts`**: Module registration and project setup.
- **`README.md`**: Project overview and documentation.

## Key Features

- **Clothing Listings (CRUD)**
  - Create listings with outfit details such as photos, size, type, price, and location.
  - Browse and filter available traditional clothing.
  - Update listing information when availability or details change.
  - Delete listings that are no longer available.

- **User Profiles (CRUD)**
  - Create renter, boutique, or clothing-owner profiles.
  - View and manage account information.
  - Update personal details and preferences.
  - Delete user profiles when necessary.

- **Admin Dashboard (CRUD)**
  - Manage users, listings, and platform activity.
  - Update user records, clothing information, and app settings.
  - Remove listings or accounts that violate platform rules.

## Technology Stack

- **Android Frontend:** Kotlin
- **Mobile UI:** Android native app structure
- **Backend:** JavaScript with Express
- **Build System:** Gradle with Kotlin DSL

## Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/natnaeleyuel/RentHabesha-Mobile-App-Android.git
   ```
2. Open the Android app in **Android Studio**.
3. Sync Gradle dependencies for the mobile project.
4. Open the backend project inside `rent-habesha-backend/` to configure and run the Express server as needed.
5. Run the Android app on an emulator or physical device.

---

*Created collaboratively by the RentHabesha team, including [natnaeleyuel](https://github.com/natnaeleyuel)*
