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
