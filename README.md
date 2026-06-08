# GymBuddy

GymBuddy is a modern fitness tracking application built to help users maintain consistency, monitor progress, and organize their fitness journey efficiently. The app provides workout tracking, streak management, expense tracking, and cloud synchronization in a clean and user-friendly interface.

---

# Overview

GymBuddy is designed for gym enthusiasts, fitness beginners, and anyone who wants a structured way to track workouts and maintain discipline. The application focuses on simplicity, performance, and reliability while providing essential fitness management tools.

---

# Features

## Authentication

* Email and Password Sign In
* Google Sign In
* Secure Firebase Authentication
* User Profile Management

## Workout Tracking

* Log daily workouts
* View workout history by date
* Track completed exercises
* Maintain organized workout records
* Easy navigation between previous and upcoming dates

## Streak System

* Daily workout streak tracking
* Consistency monitoring
* Motivation through progress tracking

## Expense Tracker

* Record fitness-related expenses
* Daily expense management
* Monthly expense summaries
* Yearly expense summaries
* Spending analysis and insights
* Track highest spending categories

## User Profile

* Custom profile information
* Profile photo support
* Account management
* Fitness activity overview

## Cloud Synchronization

* Secure Firebase Firestore database
* Real-time data synchronization
* Reliable cloud storage
* Data backup and recovery

## Responsive Design

* Clean and modern user interface
* Optimized for Android devices
* Smooth navigation and performance

---

# Tech Stack

## Frontend

* Flutter
* Dart

## Backend Services

* Firebase Authentication
* Cloud Firestore
* Firebase Core

## State Management

* Flutter Riverpod

## Additional Services

* Google Sign In
* Local Notifications

---

# Screenshots

Add application screenshots inside the `/screenshots` folder and reference them here.

```text
screenshots/
├── home.png
├── workout_history.png
├── profile.png
├── expense_tracker.png
└── settings.png
```

---

# Installation

## Prerequisites

Before starting, ensure you have:

* Flutter SDK
* Dart SDK
* Android Studio or VS Code
* Firebase Project
* Android Device or Emulator

## Clone Repository

```bash
git clone https://github.com/yourusername/gymbuddy.git

cd gymbuddy
```

## Install Dependencies

```bash
flutter pub get
```

## Configure Firebase

1. Create a Firebase project.
2. Enable Authentication.
3. Enable Google Sign-In.
4. Create a Firestore Database.
5. Download `google-services.json`.
6. Place it inside:

```text
android/app/google-services.json
```

## Run Application

```bash
flutter run
```

---

# Project Structure

```text
lib/
├── app/
├── features/
│   ├── authentication/
│   ├── home/
│   ├── workout/
│   ├── profile/
│   ├── expenses/
│   └── settings/
├── services/
├── models/
├── providers/
├── widgets/
├── firebase_options.dart
└── main.dart
```

---

# Database Structure

## Users Collection

```json
users
{
  "uid": "user_id",
  "name": "John Doe",
  "email": "john@example.com",
  "profilePhoto": "url"
}
```

## Workouts Collection

```json
workouts
{
  "date": "2026-01-01",
  "workoutName": "Push Day",
  "exercises": []
}
```

## Expenses Collection

```json
expenses
{
  "amount": 250,
  "category": "Supplements",
  "date": "2026-01-01"
}
```

---

# Security

GymBuddy uses Firebase Authentication and Firestore Security Rules to ensure secure access to user data. Users can only access and modify their own information.

---

# Future Roadmap

* Weight Tracking
* BMI Calculator
* Body Measurements Tracking
* Progress Photos
* Nutrition Tracking
* Water Intake Tracker
* Exercise Library
* Workout Templates
* Data Export
* Dark Mode Improvements
* Multi-Device Synchronization Enhancements

---

# Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Add feature"
```

4. Push the branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

# License

This project is licensed under the MIT License.

---

# Developer

**Mayank Dhakad**
**Vyapariworks**
GymBuddy is developed to provide a simple, reliable, and professional fitness tracking experience for users who want to stay consistent and achieve their fitness goals.
