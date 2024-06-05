
# React WebRTC Application

Welcome to the React WebRTC project! This application demonstrates how to implement real-time video and audio communication using WebRTC (Web Real-Time Communication) in a React.js application. The backend server is powered by Node.js and Socket.io to manage signaling for peer-to-peer connections.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features
- Real-time video and audio communication
- User authentication and room joining
- Peer-to-peer connections using WebRTC
- Signaling server using Socket.io
- Responsive design for various devices

## Technologies Used
- **Frontend:**
  - React.js
  - WebRTC API

- **Backend:**
  - Node.js
  - Express.js
  - Socket.io

## Installation
To get this application up and running on your local machine, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/piyushgarg-dev/React-webRTC
    cd React-webRTC
    ```

2. **Install server dependencies:**
    ```sh
    cd server
    npm install
    ```

3. **Install client dependencies:**
    ```sh
    cd ../client
    npm install
    ```

4. **Run the application:**
    - Start the backend server:
      ```sh
      cd server
      npm start
      ```

    - Start the frontend development server:
      ```sh
      cd ../client
      npm start
      ```

## Usage
1. Visit `http://localhost:3000` to access the application.
2. Join a room by entering your email and the room name.
3. Start a video call by clicking the appropriate buttons.


## Project Structure
The project is divided into two main parts: the client and the server.

- **Client:** Contains the React.js application for the frontend.
- **Server:** Contains the Node.js application for the backend.



## Contributing
We welcome contributions to improve this project! To contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for checking out the React WebRTC project! If you have any questions or feedback, please feel free to open an issue or contact us.
