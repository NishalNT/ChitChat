# ChitChat

ChitChat is a real-time chat application that allows users to connect and communicate with each other instantly. Built with PHP, HTML, CSS, JavaScript, and MySQL, this app provides a seamless chatting experience with user authentication and online status features.

## Live Demo

Experience ChitChat in action: [ChitChat Live Demo](https://teamchatapp.000webhostapp.com/)

## Features

- User Authentication (Signup and Login)
- Real-time messaging
- User search functionality
- Online/Offline status indicators
- Responsive design for various devices

## Technologies Used

- PHP
- HTML
- CSS
- JavaScript
- MySQL

## Installation

To set up ChitChat locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/NishalNT/ChitChat.git
   ```
2. **Go to the folder**
   ```bash 
   cd ChitChat
   ```

3. **Download and Install XAMPP**:
   - Download XAMPP from [Apache Friends](https://www.apachefriends.org/index.html).
   - Install XAMPP on your local machine.

4. **Copy Folder to XAMPP Directory**:
   - Copy the application folder to the `htdocs` directory inside your XAMPP installation folder (e.g., `C:\xampp\htdocs\`).

5. **Start XAMPP**:
   - Open the XAMPP Control Panel.
   - Start the Apache and MySQL modules.

6. **Create Database**:
   - Open your web browser and go to `http://localhost/phpmyadmin`.
   - Create a new database named `chitchat`.
   - Import the sql file named `chitchat.sql`

7. **Configure Database Connection**:
   - Open the `php/config.php` file in the project directory.
   - Update the database credentials (hostname, username, password, database name) to match your local setup

8. Open your web browser and navigate to `http://localhost/ChitChat/index.php` to start using ChatApp.

## Usage

1. Register for a new account or log in with existing credentials.
2. Use the search feature to find other users.
3. Click on a user to start a chat.
4. Send and receive messages in real-time.
5. Observe the online/offline status of your contacts.


## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

For any queries or suggestions, please open an issue on the GitHub repository.
