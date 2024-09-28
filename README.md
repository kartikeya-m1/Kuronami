**Model and Website Setup Instructions**
This repository contains three models packaged in zip files, along with instructions for running them individually and deploying the website locally. Please follow the steps below:

**Models Included:**
1. Fire_Smoke_detection_Implemented_with_Alert_Messaging.zip
2. Road_accident_with_alert_final.py
3. Violence_demo(2).py (Updated Version)


**Running Models Individually**
To run each model, follow these steps:

1. Extract the Models: Unzip the model files.
2. Edit Model Paths:
Update the path for the best.pt model file to point to your local file location.
Adjust the path for the sample video files included in the zip to your own video files.


**Running the Final Deployed Website Locally**
To set up and run the final deployed website, do the following:

1. Extract the Website Files: Unzip the Web_implementation_models.zip.
2. Refer to the README: Check the README file in the extracted folder for detailed setup instructions.
3. Download and Extract Models:
   -> Extract all the models mentioned above into the Web_implementation_models folder.
   ->Due to size constraints, everything couldn't be in a single folder.
   
4. Combine Folders: Ensure all model folders and the web implementation folder are located in the same directory.
5. Update Model Paths: Open pyserv.py and change the model paths to reflect your local file paths.
6. Consult the README: For additional setup details, refer to the README inside the Web_implementation_models.zip.

   
**Output Results**
After successfully executing the processes for both the models and the website, refer to OUTPUT.ZIP for the results.

**Important Note**
Alert Implementation: The alert system is implemented using Twilio. To use it, you need to create a Twilio account.
Replace the provided credentials with your own Twilio account details; otherwise, the code may run into errors.
