# Vechlies-Hub-User For (BoldBrand Co.)
Application for BoldBrand Renter Cars
# Vehicles Hub - Car Rental Application

**Description**: Vehicles Hub is a car rental application designed for users to easily book vehicles and for car owners to manage their listings. It provides an efficient and user-friendly platform where users can browse, rent, and pay for cars directly from their mobile devices. The app utilizes **OTP SMS** (powered by **Masr**) for secure login and **FCM Push Notifications** to keep users updated with real-time information.

**Technologies Used**:
- **Flutter**: Cross-platform mobile app development.
- **Cubit (Bloc)**: State management solution for efficient UI updates and logic separation.
- **Firebase Cloud Messaging (FCM)**: For sending real-time push notifications.
- **OTP SMS Masr**: For secure authentication using OTP via SMS.
- **Laravel**: Backend API using **RESTful services** for data management and communication.
- **Google Play & Apple Store Integration**: Fully integrated and deployed on both Android and iOS platforms.

**Architecture**: 
The project follows **Clean Architecture** principles to ensure separation of concerns and maintainability:
- **Presentation Layer**: Contains the UI components built using Flutter and managed with Cubit for state management. It is responsible for rendering the app's views and handling user input.
- **Domain Layer**: Contains business logic and use cases, ensuring that the core functionality is decoupled from external frameworks and libraries.
- **Data Layer**: Handles API calls using REST and manages data storage using local storage for offline capabilities.
- **Backend**: The backend is built with **Laravel**, which serves the RESTful API, handling user authentication, car listings, and booking transactions.

**Key Features**:
- **User Registration & Login**: Secure login using OTP verification via SMS (Masr OTP).
- **Browse & Book Cars**: Users can browse available cars, view details, and book directly through the app.
- **Owner Dashboard**: Car owners can manage their vehicles, view bookings, and track income.
- **Real-time Notifications**: Using Firebase Cloud Messaging (FCM), users and owners are notified instantly about booking confirmations, cancellations, and other important events.
- **Responsive UI**: The app is fully responsive and optimized for different screen sizes, ensuring a smooth user experience across all devices.
- **Multi-language Support**: The app supports both English and Arabic.

**Challenges**:
- Implementing secure **OTP authentication** with **SMS Masr** for a seamless login experience.
- Managing complex **state transitions** using **Cubit** for clean and scalable state management.
- Integrating **FCM** to handle real-time notifications efficiently.
- Ensuring smooth payment and booking flows using secure backend API calls with **Laravel**.

**App Links**:
- [Google Play Store](https://play.google.com/store/apps/details?id=co.boldbrand.vehicles)
- [Apple App Store](https://apps.apple.com/us/app/vehicles-hub/id1664096596)

**Live Demo**:
Due to confidentiality, the source code is not available. However, I would be happy to demonstrate the application in a meeting using an emulator or live demo, showcasing the full user and owner flows. You can explore the app on [Google Play](https://play.google.com/store/apps/details?id=co.boldbrand.vehicles) or [Apple App Store](https://apps.apple.com/us/app/vehicles-hub/id1664096596).

**Contact for Demo**:
Please reach out to schedule a live demo or request further details about the project. I would be happy to walk you through the app's features and architecture.
