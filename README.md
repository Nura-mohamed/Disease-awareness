# HealthConnect USSD Menu System

The HealthConnect USSD Menu System is a web application that provides users with information about various diseases. It allows users to access disease-specific information, including common symptoms, treatment options, self-care tips, and hotline numbers for support. The application is built using the Africa's Talking API to handle USSD communication over a GSM network.

## Features

- Main Menu: Users are presented with a language selection menu (English or Swahili) to choose their preferred language for disease information.
- Disease Selection: Users can select a specific disease from the menu options to get information about that disease.
- Disease Information: The application provides detailed information about each disease, including symptoms, treatment options, self-care tips, and hotline numbers for support.
- Navigation: Users can navigate back to the main menu or exit the system at any point during the interaction.
- Error Handling: The application handles invalid inputs and displays appropriate error messages to guide the user.

## Technologies Used

- Python: Programming language used for developing the application.
- Flask: Web framework used for building the web application.
- Africa's Talking API: API used for handling USSD communication and integrating with the GSM network.

## Installation and Setup

1. Clone the repository:
git clone <repository-url>

2. Install the required dependencies:


3. Set up your Africa's Talking account and obtain the necessary API credentials.

4. Configure the application with your Africa's Talking API credentials. Update the configuration variables in the `config.py` file:

```python
USERNAME = 'your-africas-talking-username'
API_KEY = 'your-africas-talking-api-key'
USSD_CODE = 'your-ussd-shortcode'

Contributing
Contributions to the HealthConnect USSD Menu System are welcome. Here are some ways you can contribute:

Report bugs and suggest improvements by opening an issue.
Implement new features or enhance existing functionality by creating a pull request.
Improve documentation by fixing errors or adding missing information.
