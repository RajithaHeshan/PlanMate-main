Authentication
•	Sign in via Email/Password or Google
•	Face ID / Touch ID for secure and fast access
👥 Group Management
•	Create, join (via code or QR), edit, and leave groups
•	Customizable group name, image, and description
•	Images stored in Firebase Storage
📌 Activity Planning
•	Propose group activities with multiple venue suggestions
•	Members vote on available times and preferred locations
🗓️ Event Scheduling
•	Create events based on group availability
•	Add title, date, time, location, notes, links, and reminders
•	Assign tasks to members
•	Sync events with the device’s calendar using EventKit
💬 In-App Messaging
•	Each event has its own chat thread for group discussions
🧑‍💼 Profile Management
•	Edit name and profile picture
•	Delete account if needed
🔔 Notifications
•	Local push notifications for event updates, proposals, and reminders
•	Notification settings managed in-app
📶 Offline Support
•	Core Data used for offline access to essential data
•	Syncs with Firebase when online
________________________________________
🧰 Tech Stack
•	Language & UI: Swift + SwiftUI (MVVM architecture)
•	Authentication: FirebaseAuth + Google Sign-In + Face ID/Touch ID
•	Backend Database: Firebase Firestore (NoSQL)
•	Storage: Firebase Storage for user and group images
•	Local Storage: Core Data for offline support
•	Calendar Integration: EventKit for syncing events with device calendar
•	Maps & Location: MapKit for selecting venues, nearby searches, and navigation
•	Notifications: Apple Local Push Notifications

