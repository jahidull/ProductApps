# ProductApps

A modern Android application built using Kotlin, Jetpack Compose, and Clean Architecture principles. The project is structured with a multi-module approach to ensure scalability, maintainability, and testability.

## 🚀 Key Features
* **Modern UI:** Built entirely using Jetpack Compose for a fully declarative and responsive user interface.
* **Multi-Module Structure:** Separated into `core`, `features`, and `app` modules to enforce strict separation of concerns.
* **Centralized Dependency Management:** Utilizes Kotlin DSL and `buildSrc` for managing project-wide dependencies efficiently.
* **Offline First / Local Data:** Robust data handling and state management for a seamless user experience.

## 🛠️ Tech Stack & Libraries
* **Language:** Kotlin (100%)
* **UI Framework:** Jetpack Compose
* **Architecture:** Clean Architecture + MVVM (Model-View-ViewModel)
* **Dependency Injection:** Hilt / Dagger (or your preferred DI)
* **Build System:** Gradle Kotlin DSL (`.gradle.kts`)

## 📐 Architecture Overview
The project follows **Clean Architecture** guidelines to separate the business logic from UI components:
1. **Presentation Layer (Features):** Handles the UI states and user interactions using Jetpack Compose and ViewModels.
2. **Domain Layer:** Contains the core business logic, use cases, and repository interfaces.
3. **Data Layer:** Implements data sources, network requests, and local databases.
