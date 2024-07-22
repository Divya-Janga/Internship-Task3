Objective:
The primary objective of this e-learning platform is to provide a comprehensive and user-friendly environment for users to log in, browse available courses, view course details, and enroll in courses. The platform aims to facilitate easy access to educational content and track user progress in enrolled courses.

Technologies Used:
Java Swing: For creating the graphical user interface (GUI) components.
Java AWT: For handling user input and action events.
CardLayout: For managing different screens (panels) within the main application window.
JFrame, JPanel, JLabel, JTextField, JButton, JTextArea, JScrollPane: For building the application window and its components.
GridLayout, BorderLayout: For organizing the layout of components within panels.
Features and Components:
User Interface (UI):

Main Frame: The main window of the application that holds all panels.
Panels: Separate panels for logging in, viewing the user profile, browsing courses, and viewing course details.
Buttons: For interacting with the application (e.g., logging in, viewing courses, enrolling in courses, and navigating between screens).
Backend Logic:

Users Map: A map to store user information.
Courses Map: A map to store available courses and their details.
Current User: Keeps track of the currently logged-in user.
Action Listeners: For handling button click events and updating user and course details.
Working of the Application:
Login Panel:

Users enter their username and click the "Login" button.
If the username is new, a new user is created and added to the users map.
The current user is set to the logged-in user, and the profile panel is displayed.
Profile Panel:

Displays a welcome message with the username.
A "View Courses" button allows users to navigate to the courses panel.
Courses Panel:

Displays a list of available courses as buttons.
Clicking a course button displays the course details in the course details panel.
A "Back to Profile" button allows users to navigate back to the profile panel.
Course Details Panel:

Displays the title and description of the selected course.
An "Enroll" button allows the current user to enroll in the course.
A "Back to Courses" button allows users to navigate back to the courses panel.
Example Code Analysis:
The provided code implements the e-learning platform with the following key components:

Main Frame Setup:

The JFrame is initialized with a title and size.
A CardLayout is used to manage different panels (screens) within the main frame.
Four main panels are added to the card layout: LoginPanel, ProfilePanel, CoursesPanel, and CourseDetailsPanel.
LoginPanel:

Displays a login form with a text field for the username and a "Login" button.
Upon login, the current user is set, and the profile panel is displayed.
ProfilePanel:

Displays a welcome message with the username.
A "View Courses" button allows users to navigate to the courses panel.
CoursesPanel:

Displays a list of available courses as buttons.
Clicking a course button displays the course details in the course details panel.
A "Back to Profile" button allows users to navigate back to the profile panel.
CourseDetailsPanel:

Displays the title and description of the selected course.
An "Enroll" button allows the current user to enroll in the course.
A "Back to Courses" button allows users to navigate back to the courses panel.
User Class:

Represents a user with a username and a map of enrolled courses.
Course Class:

Represents a course with a title and description.
CourseProgress Class:

Tracks the progress of a user in a course.
Conclusion:
This e-learning platform provides a basic yet functional environment for users to log in, browse courses, view course details, and enroll in courses. Enhancements could include user authentication, persistent storage for users and courses, tracking of course progress, and more interactive course content. Integration with a backend service could also be added to handle real-time data and user interactions.
