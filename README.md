# todo list in kotlin
todo list demo project created in kotlin using room database. and also added notification to notify user at specific date


# Modification that I made into the project:

- I integrated the MVVM architecture into the project to enhance its structure and maintainability.

- Comprehensive code comments were added for improved code readability and understanding.

- Analytics functionality was incorporated for key actions such as adding, editing, and deleting todos, handling todo errors, and monitoring overall app usage in a single session.

- Utilized the Work Manager to facilitate the seamless uploading of analytics data.

- Instead of relying on an actual server, I opted to store analytic data in the Room database due to the absence of a provided API endpoint.

- Updated the Gradle file to align with the latest Android Studio requirements and enhancements.

- Implemented Dagger Hilt for dependency injection, contributing to a more modular and maintainable codebase.

- Implemented Error handling mechanism in the worker class using try catch

Additionally, it is advisable to consider using the HTTPS protocol for secure data transmission and leverage the Retrofit library for streamlined communication.
