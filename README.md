🚖 Uber Clone
A full-stack Uber Clone mobile application built using React Native, designed to showcase seamless real-time interactions and user-friendly interfaces for both Android and iOS devices. This app combines powerful tools and services to provide live location tracking, map-based ride selection, secure authentication, and a responsive UI. This project is a perfect way to demonstrate proficiency in building full-stack mobile applications that make a lasting impact.

🛠️ Tech Stack
Frontend: React Native, Expo
Map and Directions: Google Maps with Geoapify for directions and autocomplete
Backend: Serverless PostgreSQL database
State Management: Zustand
Authentication: Clerk for secure email and Google-based login
Payments: Stripe for mock payment functionality
Styling: Tailwind CSS for efficient and responsive UI styling
🚀 Features
📝 Onboarding Flow
👤 Seamless User Registration: Streamlined onboarding for quick and smooth setup.
🔒 Email and Password Authentication with Verification: Secure login with email verification to ensure account security.
🔑 OAuth with Google: Allows users to log in with Google credentials for faster access.
🔐 Authorization and Role-Based Access Control
🛡️ User Role Management: Secure access control, allowing different users to have role-based permissions.
🏠 Home Screen
📍 Live Location Tracking: Real-time location tracking with Google Maps integration, showing the user's live location.
🚗 Nearby Cars on Map: Real-time markers on the map representing nearby available cars.
📋 Recent Rides
📅 Ride History at a Glance: View a list of recent rides directly from the home screen.
🔍 Geoapify Autocomplete
🌍 Place Search: Search any place globally with autocomplete suggestions, powered by Geoapify.
🚕 Ride Management
📌 Find Rides: Search for rides by specifying 'From' and 'To' locations with accurate routes.
🗺️ Select Rides on Map: Choose available cars in the vicinity from the map interface.
✔️ Confirm Ride: Detailed ride information displayed upon selection, including estimated time and fare price.
👤 Profile Management
🧑 User Profile: Manage personal account details from the profile screen.
🕒 Ride History
📜 View Past Rides: Review all booked rides in the history section.
📱 Cross-Platform Responsiveness
📲 Android and iOS Compatibility: Optimized layout and responsiveness for both Android and iOS platforms.
🧩 Project Architecture and Code Reusability
📂 Modular Architecture: The project is structured with a modular approach for easy navigation and code reusability.
🎛️ Efficient State Management: Zustand provides a lightweight, predictable store for managing app-wide state.
💅 Responsive Styling: Tailwind CSS keeps the UI adaptable across various screen sizes and orientations.
🏁 Getting Started
✅ Prerequisites
Ensure you have Node.js, Expo CLI, and a compatible code editor installed.
📥 Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/uber-clone.git
cd uber-clone
Install dependencies:

bash
Copy code
npm install
Set up environment variables:

Configure your API keys for Google Maps, Geoapify, Stripe, and Clerk in an .env file.
Run the app:

bash
Copy code
expo start
⚙️ Additional Setup
Set up PostgreSQL database for handling data storage and retrieval.
Configure Stripe for handling mock payments.
📖 Usage
🆕 Sign Up / Log In: Begin by creating an account or logging in via email or Google OAuth.
🗺️ Search and Select Rides: Use the map to locate nearby cars, search for destinations, and confirm rides.
👤 Profile and History: Manage your account details and view your booking history.
💳 Test Payments: Use the Stripe integration to simulate payments in the app.
🔮 Future Enhancements
💳 Real Payment Integration: Integrate live payments with Stripe.
💬 Driver and Passenger Chat: Add in-app chat for real-time communication.
🔔 Push Notifications: Enable push notifications for ride updates.
🤝 Contributing
Contributions are welcome! If you'd like to improve the project or add new features, feel free to fork the repository and submit a pull request.

