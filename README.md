### RATEFLIX School Project README

#### Project Overview
The project is divided into three distinct parts. With my team, we developed a platform similar to Allociné:

1. **Infrastructure Project**: Creation of a virtual machine to host a platform similar to Allociné.
2. **Web Application Project (PHP)**: Development of a web application in PHP using a relational database.
3. **Java Application Project**: Practical application of object-oriented programming concepts in Java.

I was responsible for the Web part.

#### Project Description
The web application allows users to rate movies and obtain a personalized ranking, keeping track of viewed films while expressing their opinions.

#### Web Application Structure
The web application is composed of 7 pages:

- **Register**: User account creation.
- **Login**: User login.
- **Password Forgot**: Password recovery.
- **SearchPage**: Homepage with movie search functionality.
- **MoviePage**: Movie profile with associated comments.
- **HomeProfile**: User profile overview with left comments.
- **EditProfile**: Edit user information.

#### User Account Management
- **Register**:
  - Users input their username, email, password (masked), and confirm their password.
  - Date of birth can also be provided, visible on the user's profile.
  - Error messages are displayed in case of malfunction.

- **Login**:
  - Users input their username and password (masked).
  - Links are provided for password recovery and account creation.

- **PasswordForgot**:
  - Users can change their forgotten password by inputting their email and a new password.
  - Error messages are displayed in case of mismatching passwords.

#### User Interface
- Each page features a header with the site's name and a "Logout" button.
- Clicking on the user's avatar and username redirects to the profile page.

#### Pages Description
- **SearchPage**:
  - Displays all movies on the site and includes a search bar.
  - Displays movie names as users type in the search bar.

- **MoviePage**:
  - Divided into three parts: movie information, comment addition, and user comments.
  - Users can rate movies and leave comments.

- **HomeProfile**:
  - Divided into two sections: navigation bar and user profile.
  - Displays user profile information and all comments left by the user.

- **EditProfile**:
  - Allows users to modify their personal information, including username, email, and password.
  - Users can also upload a profile picture.

This README provides an overview of the web application developed.
