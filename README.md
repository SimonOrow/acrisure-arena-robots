
This project consists of robots that were created to automate data retrieval from the Acrisure Arena website (https://acrisurearena.com/). This was done through the Kofax RPA Designer Studio.

The event robots simply loop through all available events and saves the event name and subheading.


Command to run the roboserver:
After obtaining a free trial, the roboserver must be started with the following command:

    roboserver -MC -mcUrl "http://localhost:50080"
From there, navigate to http://localhost:50080 for the initial setup and enter the correct license key and company found in the free trial email.
