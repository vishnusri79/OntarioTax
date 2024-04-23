Ontario Tax Calculator App
The Ontario Tax Calculator App is a user-friendly Android application designed to calculate income tax based on the tax brackets and rates provided by the Ontario government. Additionally, the app allows users to account for RRSP (Registered Retirement Savings Plan) contributions, deducting them from income when calculating tax. The RRSP contribution limit for the next year is also displayed. App data is stored in Shared Preferences for persistence, and users can perform what-if analysis by adjusting the RRSP deduction limit using a Slider component.

Features
Tax Calculation: Implements a tax calculation class that handles tax calculation based on Ontario tax rules.
RRSP Contribution Deduction: Deducts RRSP contributions from income before tax calculation.
RRSP Contribution Limit Display: Retrieves and displays RRSP contribution limits for the next year from an external data source.
Slider Component: Utilizes a Slider component to allow users to adjust the RRSP deduction limit and instantly calculate tax based on the chosen multiplier.
Shared Preferences: Stores app data, including user preferences and RRSP deduction limit, in Shared Preferences for persistent storage.
Refresh Button: Provides a refresh button to reload data stored in Shared Preferences, allowing users to update information whenever needed.
Installation
Clone the repository to your local machine.
Open the project in Android Studio.
Build and run the app on an Android device or emulator.
Usage
Tax Calculation Activity: Launches the main activity of the app, where users can interact with the UI to adjust RRSP deduction limits and view calculated taxes.
Slider Interaction: Users can slide the Slider component to choose a multiplier for the RRSP deduction limit, triggering real-time tax calculation updates.
Refresh Button: Allows users to reload data stored in Shared Preferences, ensuring the latest information is displayed.
Contributing
Contributions are welcome! Please fork the repository and submit pull requests for any enhancements or bug fixes.

License
This project is licensed under the MIT License.
Screenshots :
![image](https://github.com/vishnusri79/OntarioTax/assets/92097289/305b9171-978a-496d-8cc1-8d9315c58106)
![image](https://github.com/vishnusri79/OntarioTax/assets/92097289/3e90e536-845a-4d05-808a-10f547431935)
![image](https://github.com/vishnusri79/OntarioTax/assets/92097289/7c8558f7-f0d4-45f0-bdfe-dad2ac4c1059)
![image](https://github.com/vishnusri79/OntarioTax/assets/92097289/5c81b58d-728f-4805-a76e-6da8f8aab980)
![image](https://github.com/vishnusri79/OntarioTax/assets/92097289/9a50e448-5743-4917-8f9d-4275bbb61c6c)




