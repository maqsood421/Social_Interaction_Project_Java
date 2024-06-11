# MHZ Socio: Social Interaction Console-Based Application

## Table of Contents
1. [Abstract](#abstract)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [Contributing](#contributing)
7. [License](#license)

## Abstract
MHZ Socio is a console-based social interaction application that simulates the core functionalities of a social media platform. It allows users to create profiles, manage friendships, send and receive messages, and create and view posts. This project aims to provide a fundamental understanding of the mechanisms involved in social media platforms.

## Features
- User registration and login
- Profile management
- Friend management (add, view, and manage friends)
- Messaging system (send and receive messages)
- Post creation and viewing (home feed)
- User-friendly console-based interface

## Installation
To run the MHZ Socio application on your local machine, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/mhz-socio.git
   cd mhz-socio
   ```

2. **Compile the project:**
   ```bash
   javac Application.java
   ```

3. **Run the application:**
   ```bash
   java Application
   ```

## Usage
1. **Start the application:**
   ```bash
   java Application
   ```

2. **Register or login:**
   - Follow the prompts to register a new user or login with an existing username and password.

3. **Navigate the menus:**
   - Use the provided menu options to navigate through the application. Options include viewing and editing your profile, managing friends, sending and viewing messages, and creating and viewing posts.

## Project Structure
The project is structured into several classes, each responsible for different functionalities:

- **User**: Manages user details, friends, posts, and messages.
- **Post**: Represents a user post with content and timestamp.
- **Message**: Represents a message with content, sender, recipient, and timestamp.
- **Menu**: Handles the display and navigation of various menus.
- **Application**: The main class that initiates and runs the application.

Example directory structure:
```
mhz-socio/
├── Application.java
├── Menu.java
├── User.java
├── Post.java
├── Message.java
└── README.md
```

## Contributing
Contributions are welcome! If you have suggestions or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push the branch to your fork.
5. Submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

---

Feel free to modify the content of this README file to fit the specifics of your project. This file serves as a basic template to guide you in documenting your project effectively.
