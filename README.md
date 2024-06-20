# CS-360

The app I developed is a weight tracking application designed to help users monitor their weight loss or gain progress. The primary user need is to easily log their weight, set a goal weight, and view their progress over a period of time.

**User-Centered UI**
To address user needs, the app features the following screens:

  Login/Signup Screen: Provides secure access to personalized weight data.
  
  Permission Request Screen: Clearly explains the need for SMS permission and allows users to grant it.
  
  Weight Logging Screen: Allows users to input their current weight and goal weight. Provides immediate feedback on their progress towards their goal (if SMS permission is granted).

  Weight History Screen: Displays a chronological list of past weight entries, including the difference from the goal weight. Offers a "Delete Entry" button for managing past entries.
  
The UI design prioritizes simplicity and clarity. Input fields are clearly labeled, buttons have descriptive text, and the weight history is presented in an easy-to-read format. The use of Snackbars for feedback and dialogs for confirmation ensures a user-friendly experience.

**Coding Approach**
I adopted a structured approach to coding, utilizing:
  Background Threads: Database operations and potentially time-consuming tasks were performed in background threads to avoid blocking the main UI thread and ensure a smooth user experience.
  
  SharedPreferences: Used to store the SMS permission status, allowing the app to remember the user's choice across sessions.
  
  Input Validation: Implemented checks to prevent crashes due to empty input fields, providing informative error messages to the user.
  
  Modular Design: Organized code into separate classes and methods for better maintainability and reusability.
  
These techniques are fundamental to Android development and can be applied to any future app development projects.

Testing and Quality Assurance

Thorough testing was conducted throughout the development process. This included:
  Unit Testing: Testing individual components (like input validation and data calculations) in isolation.
  
  Integration Testing: Testing the interaction between different components (like data storage and retrieval).
  
  User Interface Testing: Manually interacting with the app to ensure a smooth and intuitive user experience.
Testing is crucial to identify and fix bugs, ensure functionality, and improve the overall quality of the app.
Innovation and Challenges

One challenge was handling the SMS permission in a way that respects user choice while still providing the desired functionality. 
**The solution involved:**
  Persistent Permission Prompt: Ensuring the permission request screen is shown on every app run if the permission is not granted.
  
  Graceful Handling of Denial: Skipping the permission screen and providing a message if the user permanently denies the permission.
  
**Demonstrated Skills**
Throughout the development process, I demonstrated proficiency in:

  Android SDK and Jetpack Libraries: Utilized core Android components and modern Jetpack libraries for efficient and robust app development.
  
  UI Design and User Experience: Created a user-centered interface that is intuitive and easy to navigate.
  
  Data Persistence: Implemented a database to store and retrieve user data.
  
  Background Processing: Ensured a smooth user experience by performing time-consuming tasks in background threads.
  
  Problem-Solving and Debugging: Effectively identified and resolved issues throughout the development process.

  
Overall, this project showcases my ability to design, develop, and test a functional and user-friendly Android application.
