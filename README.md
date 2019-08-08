# AndroidFlask

## Image Upload from Android to a Python-Based Flask Server
The repository consists of 2 main folders:
1. **AndroidClient**: Represents the Android Studio project which builds an Android app working as a client.
2. **FlaskServer**: The Python-Based server using Flask.

To use this project, do the following:
* Open the **Android Studio** project and run it to create the APK and run the app.
* After that, run the **Flask** app Python file. It is enough to run it in the console.
* After the server is up and running, then go back to the Android app. Edit the EditText boxe of the **IPv4 address** to reflect the current IPv4 address of the server.
* If the **port number** used in the project which is **5000** is used by another app in your machine, you need to change the port number in both the client and server.
* Select an image file to be uploaded to the server by clikcing on the **Select Image** button.
* Click on the **Connect to Server** button to establish a connection with the server and upload the selected image.
