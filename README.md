# BlogMaster

BlogMaster is a full-stack blogging application built using the MERN stack (MongoDB, Express, React, Node.js). It allows users to create, publish, and manage their blogs seamlessly.

## Technologies Used

- **Backend:**
  - Express.js
  - Mongoose (for MongoDB object modeling)
  - MongoDB (database)
  - Bcrypt (for password hashing)
  - Concurrently (to run Node.js server and React server simultaneously)

- **Frontend:**
  - React.js
  - Redux Toolkit (for state management)
  - React Router (for client-side routing)
  - Material UI (for UI components)

## Strategy

### Backend:
1. **Setup:**
   - Initialized the project folder and installed necessary dependencies.
   - Created `server.js` as the entry point.
   - Utilized `.env` file to store MongoDB connection string.
   - Implemented `db.js` for establishing connection between the app and MongoDB.

2. **User Authentication:**
   - Integrated user authentication using routes for login, signup, etc.
   - Implemented user model and controllers to handle login, signup, and password hashing.
   - Used bcrypt for password hashing and encryption.
   - Tested APIs using tools like Thunderclient.

3. **Blog Management:**
   - Developed blogRouter to handle CRUD operations for blogs.
   - Implemented logic for fetching, posting, updating, and deleting blogs.

### Frontend:
1. **Setup:**
   - Designed the header using Material UI components like AppBar, Toolbar, and Button.
   - Implemented routing logic for different pages.

2. **User Authentication:**
   - Created login and register pages.
   - Managed global state using Redux Toolkit.
   - Styled login and register pages using Material UI.
   - Utilized Axios for sending network requests to APIs.

3. **Blog Display and Management:**
   - Fetched blogs from the database using useEffect hook.
   - Used Material UI Card component for displaying blogs.
   - Implemented logic to manage user-specific blogs and rendering them on the UI.
   - Created functionality for creating, updating, and deleting blogs.

## Getting Started

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Start the server and client concurrently using `npm run dev`.

## Author

[Shantanu Tiwari]

## License

This project is licensed under the [License Name] License - see the LICENSE.md file for details.

## Acknowledgments

- Special thanks to the creators of Express, React, and MongoDB for providing amazing tools for building web applications.
- Gratitude to the developers of Material UI for their beautiful and customizable UI components.
- Thanks to the Redux Toolkit team for simplifying state management in React applications.
- Appreciation to the authors of Axios for creating a user-friendly HTTP client for JavaScript.
- Shoutout to the contributors of Concurrently for enabling seamless integration between Node.js and React development environments.

