# DevConnector 2.0

**Social network for developers**

This project is a MERN stack application developed as part of the "MERN Stack Front To Back" course on Udemy. It serves as a small social network app tailored for developers, featuring authentication, user profiles, and forum posts.

The application has undergone updates and improvements since the course was published. These changes include:

- Updated GitHub API authentication method due to deprecation of authentication via URL query parameters.
- Replacement of the deprecated `request` package with `axios` for making HTTP requests.
- Addition of the `normalize-url` package to handle user-entered URLs and ensure they are valid.
- Fixing broken links in Gravatar by using `normalize-url`.
- Implementation of Redux subscription to manage local storage for the authentication token.
- Refactoring of components for improved reusability, such as merging `EditProfile` and `CreateProfile` into a single `ProfileForm` component.
- Handling token expiration by logging the user out and ending their session.
- Migration from Moment.js to the browser's built-in `Intl` API for date formatting.

The project is structured to follow best practices, with the backend built using Node.js, Express.js, and MongoDB for the database. The frontend is built using React and Redux for state management. The application provides a comprehensive example of building a full-stack web application using modern technologies and practices.
