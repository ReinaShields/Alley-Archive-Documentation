# Alley Archive

Alley Archive is a community-driven Android app that lets users discover, upload, and interact with street art in their area. Street art is temporary, it often gets painted over or removed, so this app creates a digital archive to preserve it. Users can browse a live map of nearby art, upload their own finds, and engage with the community through likes, comments, and favorites.

## Environment Setup

1. Install the latest version of Android Studio

2. Clone the repository
```bash
git clone https://github.com/your-username/alley-archive.git
```

3. Add the provided `google-services.json` to the `app/` directory

4. Add the provided Google Maps API key to `app/src/main/res/values/strings.xml`

## Running Program

1. Open the project in Android Studio
2. Switch to the `main` branch
3. Connect an Android device or start an emulator
4. Click Run

## Tools

- Android Studio (compileSdk 36, minSdk 24)
- Java 11

## Libraries

- AndroidX AppCompat
- Material Design
- ConstraintLayout
- Google Play Services Maps
- Google Play Services Location
- Firebase BOM 34.8.0
- Firebase Auth
- Firebase Firestore
- Firebase Storage

## Key Features

- **Photo Uploads** - Take or select a photo; GPS location is attached automatically
- **Interactive Map** - Browse street art near you using a Google Maps view with markers
- **Main Feed** - Scroll through recent posts from the community
- **Search & Filter** - Find art by city or tags
- **Likes, Comments & Favorites** - Engage with posts and save ones you love
- **User Authentication** - Secure login/signup via Firebase (required to upload or interact)
