# Event Planner Web App

**Overview:**
This web application serves as an Event Planner, allowing users to create, manage, and RSVP to events. It provides a simple and intuitive interface for users to schedule events, view upcoming activities, and manage their attendance status.

**Key Features:**
- **Event Creation:** Users can easily create events by providing details such as event name and date.
- **Event Management:** The application offers the ability to view, edit, and delete events.
- **RSVP Functionality:** Users can respond to event invitations with RSVP status (Going, Not Going, Not Responded).
- **Calendar View:** A visual calendar displays events with optional RSVP status indicators.

**Technologies Used:**
- **React:** The frontend is built using React for a dynamic and responsive user interface.
- **Firebase:** Firebase Firestore is used as the backend database to store event data.
- **React Router:** Navigation is handled using React Router to create a seamless single-page application.

**Project Structure:**
- **src/components:** Contains React components for SignIn, SignUp, EventForm, RSVP, CalendarView, etc.
- **src/firebase:** Firebase configuration and initialization.
- **src/App.js:** Main entry point, routing configuration using React Router.
- **src/index.js:** Renders the React application into the root HTML element.

**How to Use:**
1. Clone the repository to your local machine.
2. Run `npm install` to install dependencies.
3. Set up Firebase Firestore and update the configuration in `firebase.js`.
4. Run the app using `npm start`.
5. Access the application at [http://localhost:3000](http://localhost:3000).

**Contributions:**
Contributions and feature requests are welcome! Feel free to open issues or create pull requests.

**Author:**
VishaL Yadav

---
Feel free to customize this description based on your specific preferences and additional details about the project.
