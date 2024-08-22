App Outline

1.	Description
  a.	Name: Stay Hydrated
  b.	Purpose: To assist users track daily fluid intake using goals and alerts.
  c.	Target Audience: Users who are concerned with proper hydration

2.	Problem Addressing
  a.	Identified Problem
    i.	Many individuals struggle to maintain adequate hydration due to busy schedules, lack of awareness, or simply forgetting to drink water throughout the day.
    ii.	Poor hydration can lead to fatigue, reduced cognitive function, and other health issues, affecting overall well-being and productivity.
  b.	Proposed Solution
    i.	HydroTrack provides automated water consumption tracking via a smart water bottle and sends reminders to the user's mobile app to ensure they stay hydrated. 

3.	Platform
   a.	Platforms: Android and iOS
  b.	Firebase Realtime Database for storing user data.
  c.	Cloud Integration
    i.	AWS or Google Cloud for scalable storage and analytics
    ii.	Cloud messaging for notifications. 
  d.	Security & Privacy
    i.	 Data Encryption 
  e.	Privacy Policies
    i.	Personalization for goals, weight, age, etc.
    ii.	Optional sync to other apps.
  f.	User Profile Screen
    i.	Goals
    ii.	Personal data (update weight, activity level, etc.).
    iii.	Calendar view of past water intake.

4.	 Front/Back End Support
  a.	(Front) UI Design - The user interface is designed with simplicity and ease of use in mind, utilizing Material Design principles to ensure a consistent and intuitive experience. 
  b.	Technologies - The UI is built using XML for layout, with Java/Kotlin handling the logic behind user interactions.
  c.	(Back) Firebase - is used for real-time database management and user authentication, ensuring secure storage and quick access to user data.
  d.	Technologies - Firebase Realtime Database Managers handle server-side logic, and database, allowing for scalable and flexible data handling

5.	Functionality
  a.	Hydration Tracking
    i.	Manual input of fluid tracking
    ii.	Integrated synching with smart bottles for optional automatic fluid tracking
    iii.	Daily water tracking with auto-reset for next day
    iv.	User defined reminders and notifications
    v.	Integration with Wearables & Smart Devices 
    vi.	Water tracking button
    vii.	Total progress for each day

6.	Design (Wireframes)
  a.	The wireframes were created to visualize the app’s layout and user flow before development began.
  b.	Initial hand-drawn sketches were refined into digital wireframes using Justinmind, ensuring all user interactions were mapped out clearly. 
  c.	Screen Layouts
    i.	Home Screen displays the user's current water intake, progress toward daily goals, and quick access to other features.
    ii.	Settings Screen allows users to adjust their hydration goals, connect/disconnect the smart bottle, and manage notifications.
