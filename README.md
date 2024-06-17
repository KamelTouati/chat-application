# Chat Application

This project is a chat application consisting of a server-side component built with Node.js and Express, and a client-side component built with React. The application allows users to communicate in real-time via web sockets using Socket.IO.

## Features

- **Real-time Messaging:** Users can send and receive messages instantly without refreshing the page.
- **User Interface:** Built with React, providing a modern and responsive user interface.
- **Routing:** Utilizes React Router for client-side routing, enabling a seamless single-page application experience.
- **Scroll to Bottom:** Integrates `react-scroll-to-bottom` for automatically scrolling to the bottom when new messages are received.
- **Emoji Support:** Includes `react-emoji` for rendering emojis in messages.
- **Cross-Origin Resource Sharing (CORS):** Implemented using `cors` to allow the server to accept requests from the client's origin.
- **Development Experience:** Uses `nodemon` for automatic server restarts during development.

## Installation

1. **Clone Repository:**
   ```bash
   git clone https://github.com/your/repository.git
   cd repository
   ```

2. **Install Dependencies:**
   - Server:
     ```bash
     cd server
     npm install
     ```
   - Client:
     ```bash
     cd client
     npm install
     ```

3. **Run the Application:**
   - Start Server (from `server/`):
     ```bash
     npm start
     ```
   - Start Client (from `client/`):
     ```bash
     npm start
     ```

4. **Open in Browser:**
   Open [http://localhost:3000](http://localhost:3000) to view the client-side application in your browser.

## Dependencies

### Server-Side

- **Express:** Fast, unopinionated, minimalist web framework for Node.js.
- **Socket.IO:** Enables real-time bidirectional event-based communication.
- **Cors:** Middleware for enabling CORS with various options.

### Client-Side

- **React:** JavaScript library for building user interfaces.
- **React Router DOM:** Declarative routing for React applications.
- **Socket.IO Client:** Client-side implementation of Socket.IO for real-time communication.
- **React Emoji:** Lightweight emoji parser for React components.
- **React Scroll to Bottom:** Auto-scrolling React component for chat interfaces.

## Development Setup

- **Linting:** Configured with ESLint and follows the Airbnb JavaScript style guide.
- **Browserslist:** Specifies supported browsers for production and development.

## Contributing

1. Fork the repository and create your branch from `main`.
2. If you've added new functionality, make sure to include tests.
3. Ensure your code lints without any errors.
4. Issue a pull request. We welcome contributions!

## License

This project is licensed under the ISC License - see the LICENSE.md file for details.

## Acknowledgments

- **React:** Created and maintained by Facebook.
- **Express:** Created and maintained by the Node.js Foundation.
- **Socket.IO:** Created and maintained by Guillermo Rauch and contributors.
- **cors:** Created and maintained by Troy Goode.

## Contact

For any questions or feedback regarding this project, please feel free to [contact us](mailto:your-email@example.com).

---

Feel free to customize this README file further based on specific details of your project or additional features you may have implemented. Adjust the contact information, acknowledgments, and contribution guidelines to fit your project's needs.