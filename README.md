Login App :
This is a Flutter-based login application where users can log in using their Staff ID and password. The app connects to an API for authentication and handles basic login logic. This project is designed to be lightweight and easily customizable.

Features:
Staff ID and Password Authentication: Users input their Staff ID and password to authenticate.
API Integration: The app uses an HTTP POST request to send login data to the server.
Loading Indicator: Shows a loading spinner while waiting for the server response.
Error Handling: Displays an error message if login fails or fields are empty.
Navigation: Once authenticated, users are redirected to a home screen.
Project Structure:
main.dart: The entry point of the app, sets up the LoginScreen as the default page.
login.dart: Contains the LoginScreen UI and logic to collect and process user inputs.
service.dart: Handles the API call for login authentication.

How to Run the Project
Clone the Repository:

bash
Copy code
git clone https://github.com/your-repository/login_app.git
cd login_app
Install Dependencies: Make sure you have Flutter installed. Run the following command to get the necessary packages:

bash
Copy code
flutter pub get
Run the Application: To run the app on a connected device or emulator, use:

bash
Copy code
flutter run
API Details
