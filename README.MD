
# Outfit Suggestion | UiPath Robot

This UiPath robot is designed to suggest outfits based on the weather in a given city. It interacts with the user, asking for the name of the city, and then retrieves the weather information for that city. Based on the weather conditions, it provides suitable outfit recommendations.

# Prerequisites

To run this robot, you will need the following:

- UiPath - Version 21.10.6    
- UiPath Account
- Chrome
- An internet connection to access weather data

# Setup
1. Download UiPath.
    
    https://www.uipath.com/product/studio

2. Create an account.

3. Click download to get uiPath

4. Clone the repository to your local machine.

    git clone https://github.com/Nisarg-1998/ROBOT2_Outfit_Suggestion.git

5. Navigate to the cloned repository directory and select the project file (.xaml file).

# Usage

1. Execute the robot in UiPath Studio or publish it to Orchestrator.

2. The robot will prompt you to enter the name of a city. Type the name of the city and press Enter.

3. The robot will retrieve the weather information for the specified city using the configured API.

4. Based on the weather conditions, the robot will suggest appropriate outfit recommendations.

5. If desired, you can customize the outfit suggestions by modifying the logic in the workflow. For example, you can add more weather conditions or adjust the suggested outfits based on temperature ranges.

6. Optionally, you can add functionality to send the outfit suggestions via email. Modify the workflow to include the necessary email activities and configure the email settings.

# Trubleshooting

- If the robot fails to retrieve the weather information, verify that the API key is correctly configured and that you have an active internet connection.

- If the outfit suggestions do not match the expected weather conditions, review the logic in the workflow that determines the appropriate outfits. Adjust the conditions or add additional rules as necessary.
