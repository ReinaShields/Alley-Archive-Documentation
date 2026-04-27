# Alley Archive

Alley Archive is a community-driven Android app that lets users discover, upload, and interact with street art in their area. Street art is temporary, it often gets painted over or removed, so this app creates a digital archive to preserve it. Users can browse a live map of nearby art, upload their own finds, and engage with the community through likes, comments, and favorites.

## Environment Setup

1. Install the latest version of Android Studio

2. Clone the repository
```bash
git clone https://github.com/your-username/alley-archive.git
```

3. Add the provided `google-services.json` to the `app/` directory
```json
{
  "project_info": {
    "project_number": "576335311666",
    "project_id": "capstone-app-21baa",
    "storage_bucket": "capstone-app-21baa.firebasestorage.app"
  },
  "client": [
    {
      "client_info": {
        "mobilesdk_app_id": "1:576335311666:android:100a3c11f3db302b509d2b",
        "android_client_info": {
          "package_name": "com.example.capstone10"
        }
      },
      "oauth_client": [],
      "api_key": [
        {
          "current_key": "AIzaSyCZmyn-pZwK3jxKraKsW7jj6AMxr8dh1LY"
        }
      ],
      "services": {
        "appinvite_service": {
          "other_platform_oauth_client": []
        }
      }
    }
  ],
  "configuration_version": "1"
}
```

4. Add the provided Google Maps API key to `app/src/main/res/values/strings.xml`
```xml
<resources>
    <string name="app_name">Alley Archive</string>
    <string name="google_maps_key">AIzaSyD9TVl7eBS45oomUI6a5qJ7u2nD7WUm6eI</string>
    <string name="empty_posts_message">No posts yet</string>
    <string name="posts_load_failed">Could not load posts</string>
</resources>
```

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

## Test Account Information

Email: user@gmail.com  
Password: Hello123!

## Other Accounts

Email: misty64@gmail.com  
Password: OhSoBlu!

Email: MaryAnna@gmail.com  
Password: MaryAnna1

Email: khaliph.page@gmail.com  
Password: Testing123!

## Key Features

- **Photo Uploads** - Take or select a photo; GPS location is attached automatically
- **Interactive Map** - Browse street art near you using a Google Maps view with markers
- **Main Feed** - Scroll through recent posts from the community
- **Search & Filter** - Find art by city or tags
- **Likes, Comments & Favorites** - Engage with posts and save ones you love
- **User Authentication** - Secure login/signup via Firebase (required to upload or interact)
