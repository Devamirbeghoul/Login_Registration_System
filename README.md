﻿# Simple Login and Registration System in C++

This project provides a basic implementation of a login and registration system using C++. It allows users to register with a (username or email) and password, and then log in using those credentials.

## Features
- **User Registration**: Users can create a new account by providing a unique username and email.
- **User Login**: Registered users can log in with their (username or email) and password.
- **Data Storage**: User credentials are stored in a text file.

## Getting Started

### Prerequisites
- A C++ compiler (e.g., GCC, Clang).
- Basic knowledge of C++ and standard libraries.

### Project Structure
- `main.c++`: The main application file containing the logic for registration and login.
- `UserInformation`: A text file used to store registered user data.

### Usage
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/CidKagenou007/sLogin_Registration_System.git
   cd simple-login-registration
   ```

2. **Compile the Program:**
   ```bash
   g++ main.cpp -o login_registration
   ```

3. **Run the Program:**
   ```bash
   ./login_registration
   ```

## Example UI Interaction

```plaintext
1 - Login
2 - Sign-Up
3 - Forget Password
4 - Exit

Enter your choice: 1
Enter username: user1
Enter password: pass1
Login successful!
```

## Notes
- **Data Security**: The current implementation stores user data in plain text. For production use, consider implementing encryption.

## License

Anyone can use this.

## Acknowledgments
This project was inspired by basic C++ tutorials on login and registration systems.
