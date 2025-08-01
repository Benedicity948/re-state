# Awesome Homes - Real Estate Mobile App

![Awesome Homes Logo](./assets/images/icon.png)  
*Your dream home, one tap away.*

---

## 🏡 About Awesome Homes

**Awesome Homes** is a sleek, user-friendly mobile application built with **React Native** that helps users discover, explore, and connect with their ideal properties. Whether you're searching for a cozy apartment, a modern condo, or a spacious family home, Awesome Homes delivers a seamless real estate experience right from your smartphone.

With advanced search filters, interactive maps, high-resolution photo galleries, and instant contact options, Awesome Homes makes property hunting faster, smarter, and more enjoyable.

---

## 🚀 Features

- **Property Listings**: Browse thousands of homes for sale or rent with detailed descriptions, pricing, and amenities.
- **Advanced Search & Filters**: Filter by price range, bedrooms, bathrooms, property type, location, and more.
- **Interactive Map View**: Explore listings on an integrated map with real-time location pins.
- **Favorites & Saved Searches**: Save your favorite homes and set up alerts for new matches.
- **Photo Galleries**: High-quality image carousels for immersive property previews.
- **In-App Messaging**: Contact agents directly from the app.
- **Offline Mode**: View recently browsed listings without internet.
- **Dark Mode Support**: Eye-friendly interface for all lighting conditions.
- **Push Notifications**: Get alerts for price drops, open houses, and new listings.

---

## 🛠️ Tech Stack

- **Frontend**: React Native (iOS & Android)
- **State Management**: Redux Toolkit
- **Navigation**: React Navigation (Stack, Tab, Drawer)
- **Styling**: Styled Components & React Native Paper
- **Backend Integration**: RESTful API / GraphQL (with Axios or Apollo Client)
- **Authentication**: Firebase Auth / JWT
- **Maps**: React Native Maps (Google Maps or Mapbox)
- **Image Caching**: React Native Fast Image
- **Testing**: Jest, React Native Testing Library
- **CI/CD**: GitHub Actions / Fastlane

---

## 📱 Screenshots

| Home Screen | Search Filters | Property Detail |
|-----------|----------------|------------------|
| ![Home]() | ![Filters]()) | ![Detail]() |



---

## 📦 Installation

### Prerequisites
- Node.js (v16 or higher)
- React Native CLI or Expo CLI
- Xcode (for iOS) or Android Studio (for Android)
- Your mobile phone if you don't use any of the above

### Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/Benedicity948/re-state.git
   cd awesome-homes```

2. Install dependencies:
   ```bash
   npm install
       #or
   yarn install```
   
3. Configure Envireonment Variables:
   Create a .env file in the root directory;
   ```bash
   API_BASE_URL=https://your_api_here
   GOOGLE_MAPS_API_KEY=your_google_maps_key
   FIREBASE_CONFIG={"apiKey":"..."```

4. Run the app:
   ```bash
   npm start #for Expo Users or scan the QR code with the Expo App  
      #or
   npx react-native run-android
      #or
   npx react-native run-ios```