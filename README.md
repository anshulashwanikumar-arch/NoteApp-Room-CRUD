### Notes App

# NoteApp - Room Database CRUD

A simple Notes application built using Kotlin, Jetpack Compose, Room Database, ViewModel and Coroutines.

## Features

- Add new notes
- View saved notes
- Edit existing notes
- Delete notes
- Persistent local storage using Room Database
- Jetpack Compose UI
- ViewModel architecture
- Coroutines for database operations

## Technologies Used

- Kotlin
- Jetpack Compose
- Room Database
- Android ViewModel
- Kotlin Coroutines
- Android Studio

## CRUD Operations

### Create

Users can create a new note by entering a title and content.

### Read

All saved notes are displayed in the application.

### Update

Users can edit the title and content of an existing note.

### Delete

Users can delete an existing note.

## Database

The application uses Room Database for local persistent storage.

The database contains a `notes` table with:

- `id`
- `title`
- `content`

## Project Structure

com.example.notesapp

├── MainActivity.kt
├── Note.kt
├── NoteDao.kt
├── NotesDatabase.kt
└── NotesViewModel.kt

## Architecture

Jetpack Compose UI
        ↓
NotesViewModel
        ↓
NoteDao
        ↓
Room Database
        ↓
Notes Table

## How to Run

1. Clone the repository.
2. Open the project in Android Studio.
3. Wait for Gradle synchronization to finish.
4. Connect an Android device or start an emulator.
5. Click the Run button.

## APK

The debug APK can be generated from:

Build → Generate App Bundles or APKs → Generate APKs

The generated APK can be found in:

app/build/outputs/apk/debug/

## Screenshots

### Notes App

<img width="1767" height="902" alt="image" src="https://github.com/user-attachments/assets/b777c8a2-d5d4-4b91-917d-aefc838b6c4a" />


### Edit Note

<img width="475" height="787" alt="image" src="https://github.com/user-attachments/assets/1074afef-043f-40f3-bc47-8021db86bdbd" />


### CRUD Operations

<img width="352" height="727" alt="image" src="https://github.com/user-attachments/assets/dcbb025a-0087-4f3c-9dab-0415f934aed5" />




