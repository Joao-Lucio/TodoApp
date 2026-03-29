# TodoApp

## Description

TodoApp is a simple Android application for task management (todos). It allows users to add, mark as completed, and delete tasks in an intuitive way.

## Features

- Add new tasks
- Mark tasks as completed or pending
- Delete tasks
- Simple and responsive interface

## Technologies Used

- **Language**: Kotlin
- **Framework**: Android SDK
- **Architecture**: MVVM (Model-View-ViewModel)
- **Database**: Room
- **UI**: RecyclerView, Data Binding, Material Design
- **Others**: ViewModel, LiveData, Coroutines

## Prerequisites

- Android Studio (recommended version: Arctic Fox or higher)
- JDK 11 or higher
- Android device or emulator with API 24 or higher

## How to Run

1. Clone the repository:

   ```
   git clone https://github.com/Joao-Lucio/TodoApp.git
   ```

2. Open the project in Android Studio.

3. Wait for Gradle synchronization.

4. Run the application on a device or emulator.

## Project Structure

- `app/src/main/java/com/example/todoapp/`: Main source code
  - `data/`: Data layer (Room entities, DAO, Database)
  - `ui/`: UI components (Adapter, etc.)
  - `viewmodel/`: ViewModels
- `app/src/main/res/`: Resources (layouts, strings, etc.)
- `app/build.gradle.kts`: Gradle configurations for the app module
