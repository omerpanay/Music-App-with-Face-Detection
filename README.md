# Emotion-Based Music Player

An innovative Android application that recommends music based on your emotional state using facial recognition technology.

## Features

- 😊 Emotion Detection: Uses ML Kit Face Detection to analyze user emotions
- 🎵 Dynamic Playlist Generation: Creates personalized playlists based on detected mood
- 🔐 Secure Authentication: Firebase authentication for user management
- 🎸 Music Integration: Deezer API integration for rich music content
- 📱 Modern UI: Material Design components and intuitive interface
- ▶️ Real-time Playback: Full music playback controls

## Technologies Used

- Android SDK
- Firebase (Authentication, Firestore, Storage)
- ML Kit Face Detection
- Retrofit for API Integration
- ViewBinding
- Navigation Component
- MediaPlayer for audio playback

## Project Structure

The project follows a modular architecture with the following main components:

- `activities`: Main application activities
- `adapters`: RecyclerView adapters for music lists
- `models`: Data models
- `ui`: UI fragments and components
- `fromAPI`: API integration models and interfaces

## Setup

1. Clone the repository
2. Open the project in Android Studio
3. Configure Firebase:
   - Add your `google-services.json`
   - Enable Authentication and Firestore
4. Configure Deezer API:
   - Add your API key in ApiInterface.java
