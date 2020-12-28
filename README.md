# Kobiton ADB Tunnel - VS for Mac Plugin

# Prerequisites:
- Make sure that the ‘adb’ on home’s machine is on version 1.0.41 or higher
- Setup Android SDK
- Make sure Visual Studio is on version 8.7.8 or higher 

# How to use
Step 1: Download the plugin mpack file.

Step 2: Open Visual Studio, click on Visual Studio > Extensions, click Install from file to upload the plugin.

Step 3: Restart Visual Studio

Step 4: Open Kobiton ADB Tunnel plugin in Tools/Kobiton ADB Tunnel.

Step 5: Input Server Address, Email, APIKey then select “Connect” button to verify account. This is one time input if you do not sign out.
- Server Address: api server
- Email: your login email
- ApiKey: in Settings/API Keys on the Kobiton portal 

Step 6: Launch a device in the device list via iframe (only devices in ‘Private’ tab supports ADB tunnel)

Step 7: Input the Session ID to Kobiton ADB Tunnel dialog on IDE, then click the “Connect” button to connect to the device 

Step 8: Start debugging
Note: The global path environment for ADB command is set by default in Mac but you can change it by go to Preference > Projects > SDK Locations > Android
