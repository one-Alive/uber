
# 🚖 Uber Clone

A full-stack **Uber Clone** mobile application built using React Native, designed to showcase seamless real-time interactions and user-friendly interfaces for both Android and iOS devices. This app combines powerful tools and services to provide live location tracking, map-based ride selection, secure authentication, and a responsive UI. This project is a perfect way to demonstrate proficiency in building full-stack mobile applications that make a lasting impact.

## 🛠️ Tech Stack

- **Frontend**: [React Native](https://reactnative.dev/), [Expo](https://expo.dev/)
- **Map and Directions**: [Google Maps](https://developers.google.com/maps) with [Geoapify](https://www.geoapify.com/) for directions and autocomplete
- **Backend**: Serverless [PostgreSQL](https://www.postgresql.org/) database
- **State Management**: [Zustand](https://github.com/pmndrs/zustand)
- **Authentication**: [Clerk](https://clerk.dev/) for secure email and Google-based login
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) for efficient and responsive UI styling

## 🚀 Features

### 📝 Onboarding Flow
- **👤 Seamless User Registration**: Streamlined onboarding for quick and smooth setup.
- **🔒 Email and Password Authentication with Verification**: Secure login with email verification to ensure account security.
- **🔑 OAuth with Google**: Allows users to log in with Google credentials for faster access.

### 🔐 Authorization and Role-Based Access Control
- **🛡️ User Role Management**: Secure access control, allowing different users to have role-based permissions.

### 🏠 Home Screen
- **📍 Live Location Tracking**: Real-time location tracking with Google Maps integration, showing the user's live location.
- **🚗 Nearby Cars on Map**: Real-time markers on the map representing nearby available cars.
  
### 📋 Recent Rides
- **📅 Ride History at a Glance**: View a list of recent rides directly from the home screen.

### 🔍 Geoapify Autocomplete
- **🌍 Place Search**: Search any place globally with autocomplete suggestions, powered by Geoapify.

### 🚕 Ride Management
- **📌 Find Rides**: Search for rides by specifying 'From' and 'To' locations with accurate routes.
- **🗺️ Select Rides on Map**: Choose available cars in the vicinity from the map interface.
- **✔️ Confirm Ride**: Detailed ride information displayed upon selection, including estimated time and fare price.

### 👤 Profile Management
- **🧑 User Profile**: Manage personal account details from the profile screen.
  
### 🕒 Ride History
- **📜 View Past Rides**: Review all booked rides in the history section.

### 📱 Cross-Platform Responsiveness
- **📲 Android and iOS Compatibility**: Optimized layout and responsiveness for both Android and iOS platforms.

## 🧩 Project Architecture and Code Reusability

- 📂 **Modular Architecture**: The project is structured with a modular approach for easy navigation and code reusability.
- 🎛️ **Efficient State Management**: Zustand provides a lightweight, predictable store for managing app-wide state.
- 💅 **Responsive Styling**: Tailwind CSS keeps the UI adaptable across various screen sizes and orientations.

## 🏁 Getting Started

### ✅ Prerequisites
- Ensure you have Node.js, Expo CLI, and a compatible code editor installed.

### 📥 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/one-Alive/uber.git
   cd uber-clone
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Configure your API keys for Google Maps, Geoapify, and Clerk in an `.env` file.

4. Run the app:
   ```bash
   expo start
   ```

### ⚙️ Additional Setup

- Set up PostgreSQL database for handling data storage and retrieval.

## 📖 Usage

1. **🆕 Sign Up / Log In**: Begin by creating an account or logging in via email or Google OAuth.
2. **🗺️ Search and Select Rides**: Use the map to locate nearby cars, search for destinations, and confirm rides.
3. **👤 Profile and History**: Manage your account details and view your booking history.
4. **💳 Test Payments**: Using mock data

## 🔮 Future Enhancements

- **💳 Real Payment Integration**: Integrate live payments with Stripe.
- **💬 Driver and Passenger Chat**: Add in-app chat for real-time communication.
- **🔔 Push Notifications**: Enable push notifications for ride updates.

## 🤝 Contributing

Contributions are welcome! If you'd like to improve the project or add new features, feel free to fork the repository and submit a pull request.

---
