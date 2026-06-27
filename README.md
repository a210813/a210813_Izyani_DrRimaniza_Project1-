# JobQuest - Mobile Programming Project 1

## 📱 App Name
**JobQuest**

## 🎯 SDG Theme
**SDG 1: No Poverty**

> "End poverty in all its forms everywhere."  
> JobQuest helps users find job opportunities, supporting economic growth and decent work. The app provides a platform for job seekers to discover employment opportunities and apply for positions.

## 📋 Features

### Core Features
- 🔐 **User Authentication** - Login and Sign Up with local database storage
- 🏠 **Home Screen** - Overview of available jobs with personalized greeting
- 🔍 **Search Jobs** - Search by title, company, or location
- 📨 **Apply to Jobs** - Application form with resume and cover letter
- 📅 **Job Fair Event** - RSVP and event details
- 🎨 **Dark/Light Theme** - Toggle between dark and light mode

### Technical Features
- **Multiple Screens** - Login, Sign Up, Home, Search, Profile, Details, All Jobs, Applied Jobs, Messages
- **Navigation** - Jetpack Navigation Compose
- **State Management** - SharedViewModel with StateFlow

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Kotlin** | Programming language |
| **Jetpack Compose** | UI framework |
| **Jetpack Navigation** | Screen navigation |
| **Room Database** | Local data persistence |
| **Coroutines & Flow** | Asynchronous operations |

## 📸 Screenshots

*(Screenshots will be added soon)*

## 📂 Project Structure

app/src/main/java/com/example/a210813_izyani_drrimaniza_project1/
├── MainActivity.kt # Main entry point
├── data/
│ ├── AppliedJob.kt # Applied job data model
│ ├── ChatModels.kt # Chat message models
│ └── UserProfile.kt # User profile data model
├── screens/ # All Compose Screens
│ ├── AllJobsScreen.kt
│ ├── AppliedJobsScreen.kt
│ ├── AppliedPlaceholder.kt
│ ├── DetailsScreen.kt
│ ├── HomeScreen.kt
│ ├── MessagesPlaceholder.kt
│ ├── ProfileScreen.kt
│ ├── SearchScreen.kt
│ └── SharedViewModel.kt # Shared ViewModel with StateFlow
├── ui/theme/ # Theme Configuration
│ ├── Color.kt
│ ├── Theme.kt
│ └── Type.kt
└── utils/
└── (Helper classes)


## 🔧 Setup Instructions

### Prerequisites
- Android Studio Ladybug or later
- JDK 17+
- Android SDK 35

### Steps to Run

1. **Clone the repository**
```bash
git clone https://github.com/a210813/a210813_Izyani_Project1.git
