# CS360
Mobile Architecture and Programming 

Project Overview
The goal of this project was to design and develop an event-tracking mobile application that allows users to securely log in, manage upcoming events, and receive optional SMS notifications. The app was designed to address the need for a simple and reliable way to organize events such as appointments, deadlines, or personal reminders without overwhelming users with unnecessary features. The focus was on usability, data persistence, and clear user feedback throughout the app.

User Interface and Features
To support user needs, the app includes a login screen for account creation and authentication, an events screen that displays stored events in a grid-style list, and a settings screen for managing SMS notifications. These screens were designed with a clear visual hierarchy, consistent layouts, and straightforward navigation. Input fields, buttons, and labels were kept simple and clearly named to reduce confusion. The UI design kept users in mind by guiding them through common tasks such as logging in, adding an event, editing existing data, and deleting events with minimal steps. These design choices were successful because they aligned with Android design guidelines and made the app intuitive even for first-time users.

Development Approach
I approached the coding process incrementally, building and testing one feature at a time. I focused on establishing a strong foundation first by setting up the database and login functionality before adding more advanced features like event management and SMS notifications. Breaking the app into smaller components made debugging easier and helped ensure each feature worked correctly before moving on. This approach can be applied to future projects by reducing complexity and making large development tasks more manageable.

Testing and Validation
Testing was performed frequently using the Android Emulator. Each feature was tested as it was implemented, including login validation, database operations, and permission handling. Testing revealed issues such as missing input validation and permission-related edge cases, which were resolved early in development. This process is important because it ensures the app behaves correctly in real-world scenarios and prevents small issues from becoming larger problems later.

Innovation and Problem Solving
One of the main challenges was integrating SMS permissions while ensuring the app still functioned properly if permission was denied. I addressed this by designing the app to gracefully handle both outcomes, allowing core features to continue working without interruption. This required careful planning around permission checks and user feedback.

Demonstrated Skills
The component where I was most successful in demonstrating my skills was the integration of SQLite with the user interface. Implementing full CRUD functionality and connecting database operations to the UI showed my understanding of data persistence, user interaction, and Android application structure. This project reflects my growth in mobile app design and development and demonstrates my ability to build a complete, functional application from initial planning to final implementation.
