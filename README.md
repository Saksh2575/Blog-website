# Blog-website
Blog website using HTML,CSS,Node.js and MongoDB for data storage

This blog website is built using HTML, CSS, Node.js, and MongoDB for data storage, offering a platform where users can create, read, update, and delete blog posts. The website features user authentication, enabling users to sign up, log in, and manage their posts securely. It utilizes Passport.js for authentication, bcrypt for password hashing, and express-session for session management. The application is designed with a responsive user interface and uses EJS as the templating engine to render dynamic content.

To get started, clone the repository and install the necessary dependencies using `npm install`. You’ll need to set up environment variables by creating a `.env` file in the root directory with the required configuration for the port, MongoDB URI, and session secret. Once set up, run the application using `npm start`, and it will be accessible at `http://localhost:3000`.

The project is organized with a clear folder structure, including `public` for static files like CSS, `views` for EJS templates, `routes` for defining routes, and `models` for Mongoose schemas. The homepage displays all blog posts, with options for authenticated users to create new posts, edit existing ones, or delete them.

OUTPUT:
![Screenshot (10)](https://github.com/user-attachments/assets/6bf86931-d61b-4087-aeda-c1f7c292d4d3)
![Screenshot (11)](https://github.com/user-attachments/assets/6b87cb67-0f3a-463f-8ea3-1454c03732eb)
![Screenshot (7)](https://github.com/user-attachments/assets/399e5906-4b20-40a0-8d77-432caafdb0a7)


