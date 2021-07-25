# v3-storytellingApp-85



https://docs.expo.io/versions/latest/sdk/google/#using-it-inside-of-the-expo-app



Create an iOS OAuth Client ID
Select "iOS Application" as the Application Type. Give it a name if you want (e.g. "iOS Development").
Use host.exp.exponent as the bundle identifier.
Click "Create"
You will now see a modal with the client ID.
The client ID is used in the iosClientId option for Google.loginAsync (see code example below).




Create an Android OAuth Client ID
Select "Android Application" as the Application Type. Give it a name if you want (maybe "Android Development").
Run openssl rand -base64 32 | openssl sha1 -c in your terminal, it will output a string that looks like A1:B2:C3 but longer. Copy the output to your clipboard.
Paste the output from the previous step into the "Signing-certificate fingerprint" text field.
Use host.exp.exponent as the "Package name".
Click "Create"
You will now see a modal with the Client ID.
The client ID is used in the androidClientId option for Google.loginAsync (see code example below).

