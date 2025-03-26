# University Event Sync

![University Event Sync Banner](https://via.placeholder.com/800x200?text=University+Event+Sync) <!-- Replace with actual banner -->

A web application for managing university events, including registration, notifications, and QR code check-ins.

## Features

### 1. User Authentication
- Secure registration with email/password
- Role-based access (Student/Organizer)
- Profile management

### 2. Event Management
- Browse upcoming events
- Filter by category/date
- Search functionality
- Detailed event views
- Registration management

### 3. Organizer Tools
- Create/edit/delete events
- View attendee lists
- Generate QR codes for check-in

### 4. Notifications
- Event reminders (24h and 1h before)
- Updates and cancellations
- Browser and email notifications

### 5. QR Code Check-In
- Unique QR codes per registration
- Scanner interface for organizers
- Attendance tracking

## Technology Stack

### Frontend
- Angular 15+
- Angular Material UI
- RxJS for state management
- AngularFire for Firebase integration

### Backend
- Firebase 
  - Firestore Database
  - Firebase Authentication
  - Cloud Functions
  - Firebase Cloud Messaging


### Additional Libraries
- angularx-qrcode for QR generation
- @zxing/ngx-scanner for QR scanning
- date-fns for date handling

## Project Structure
src/
├── app/
│ ├── auth/ # Authentication components
│ ├── events/ # Event-related components
│ ├── shared/ # Shared modules
│ │ ├── components/ # Reusable components
│ │ ├── models/ # Data models/interfaces
│ │ └── services/ # Shared services
│ ├── notifications/ # Notification components
│ ├── qr-code/ # QR code features
│ ├── core/ # Core singleton services
│ └── app.* # Root component