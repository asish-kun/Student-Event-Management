# Student Event Management (SEM) App

## Project Overview 🚀

The Student Event Management (SEM) App is a comprehensive platform designed to streamline event communication and organization within school communities. Built for Android using Kotlin and Firebase, this application bridges the communication gap between students, teachers, and staff by providing a centralized hub for all school events.

![Login Screen](login_screen.png)

Our mission is to enhance school functioning by ensuring event announcements reach their target audiences, centralizing schedules, and making student engagement visible and trackable.

## Key Features ✨

- **Role-Based Access Control**: Different interfaces for students (view-only) and administrators (full management)
- **Event Discovery**: Browse and filter events by category (Academics, Athletics, Clubs, Service)
- **Personalized Event Lists**: "Attending" and "Following" options to track personal interests
- **Interactive Maps**: View event locations with neighborhood filtering and directions
- **Swipe Gestures**: Intuitive interactions to manage event attendance status
- **Real-Time Synchronization**: Immediate updates across all user devices via Firebase

![Dashboard Views](dashboard_views.png)

## User Roles 👥

- **Students**: View events, mark attendance, follow events for updates
- **Teachers/Administrators**: Create, edit, and delete events, plus all student capabilities
- **Coaches/Club Sponsors**: Manage extracurricular activities and gauge student interest
- **Administrative Staff**: Push critical updates and facilities information

## Technical Architecture 🏗️

- **Frontend**: Built with Kotlin for Android
- **Backend**: Firebase for real-time database, authentication, and cloud services
- **Maps Integration**: Google Maps API for location services and directions
- **UI/UX**: Designed with Material Design principles for intuitive navigation

![Event Details](event_details.png)

## App Navigation 🧭

1. **Home/Dashboard**: Entry point with scrollable event list and category filters
2. **Events List**: View all events with swipe interactions for attendance management
3. **Event Details**: Comprehensive information including location, time, and contact details
4. **Maps**: Interactive map showing all event locations with filtering options
5. **User Profile**: Account management and logout functionality

![Maps View](maps_view.png)

## Implementation Highlights 💡

- **Firebase Integration**: Real-time database updates and user authentication
- **Intuitive UI**: Color-coded event categories and consistent design language
- **Geospatial Features**: Neighborhood filtering and turn-by-turn directions
- **Responsive Design**: Adapts to various Android device sizes and orientations

## Getting Started 🚀

### Prerequisites
- Android Studio (latest version)
- Kotlin plugin
- Firebase account
- Google Maps API key

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/dkumankumah/SEM.git
   ```
2. Open in Android Studio
3. Configure Firebase:
   - Connect to your Firebase project
   - Download and add google-services.json
4. Run the app on an emulator or physical device

### Test Credentials
- Admin access: sweng888@test.com / password: sweng888

![Add Event](add_event.png)

## Future Enhancements 🔮

- iOS compatibility
- Push notifications for event reminders
- Calendar integration
- Event attendance tracking and analytics
- Dark mode support

## Contributors 👨‍💻👩‍💻

- Tara Can
- Daniel Kumankumah
- Asish Nelapati

## License 📄

This project is created for Pennsylvania State University's SWENG 888 course under Professor Guimaraes, Fall 2024.

---

**Note on Images**: The PDF contains wireframes and screenshots that should be placed as follows:
- Login screen image after the Project Overview section
- Dashboard views (student vs admin) after Key Features
- Event Details view after Technical Architecture
- Maps view after App Navigation
- Add Event screen after Getting Started

The repository would benefit from organizing these images in an `/images` directory and referencing them accordingly in the README.
