# My Assessment Application

Android application for NIT3213 Final Assignment demonstrating API integration and Android development.

## Features

- Login screen with authentication
- Dashboard with entity list (RecyclerView)
- Details screen with complete entity information
- API integration with Retrofit
- Proper navigation between screens

## Setup

1. Open project in Android Studio
2. Sync Project with Gradle Files
3. Build → Clean Project
4. Build → Rebuild Project
5. Run the application

## Usage

- **Login**: Use first name as username and student ID (without 's') as password
- **Dashboard**: View list of entities from API
- **Details**: Click any item to view detailed information
- **Navigation**: Use back buttons to navigate between screens

## API Details

- **Base URL**: `https://nit3213api.onrender.com/`
- **Login**: POST `/sydney/auth`
- **Dashboard**: GET `/dashboard/{keypass}`

## Technical Stack

- Kotlin
- Retrofit for API calls
- RecyclerView for lists
- ViewModel and LiveData
- ViewBinding

## Project Structure

- `MainActivity.kt` - Login screen
- `DashboardActivity.kt` - Entity list
- `DetailsActivity.kt` - Entity details
- `DashboardViewModel.kt` - Business logic
- `EntityAdapter.kt` - RecyclerView adapter

## Dependencies

- Retrofit 2.9.0
- Gson Converter 2.9.0
- AndroidX Lifecycle components
- RecyclerView 1.3.2
- Coroutines 1.7.3
- ✅ Proper navigation and error handling
- ✅ Clean code structure
- ✅ Unit tests included

# My Assessment Application

Android application for NIT3213 Final Assignment demonstrating API integration and Android development.

## Features

- Login screen with authentication
- Dashboard with entity list (RecyclerView)
- Details screen with complete entity information
- API integration with Retrofit
- Proper navigation between screens

## Prerequisites

- **Android Studio** (2022.3.1 or later recommended)
- **JDK** 11 or higher
- **Android SDK** API 24 to 34
- **Internet connection** (for API calls)

## Build Instructions
Using Android Studio (Recommended)

1. Open the Project
   - Launch Android Studio
   - Select "Open an Existing Project"
   - Navigate to the project folder and click "OK"

2. Sync Project with Gradle
   - Click "Sync Project with Gradle Files" (elephant icon)
   - Or go to: File → Sync Project with Gradle Files

3. Clean the Project
   - Build → Clean Project

4. Rebuild the Project
   - Build → Rebuild Project

5. Resolve Dependencies (if needed)
   - If you see dependency errors, go to: File → Invalidate Caches / Restart
   - Select "Invalidate and Restart"

##Run Instructions
Using Android Studio (Recommended)
Connect Device or Emulator

Tools → Device Manager → Create Device

Select device (e.g., Pixel 4)

Select API level 24 or higher

Finish setup

###Run the Application

Click "Run" button (green play icon)

Or go to: Run → Run 'app'

Select target device (connected device or emulator)
