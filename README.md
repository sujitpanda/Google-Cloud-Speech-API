# Google-Cloud-Speech-API
Google Cloud Speech API Android Project Demo

This is demo project on implementation of new Google Cloud Speech API in Android project. 
This will record user speech and convert to text. There is one demo text "Hello" is visible on the activity screen. 
So when user open the app and say "Hello" it will be matched with the "Hello" text on the screen and if it matches then
the result text color will be changed to green otherwise in case user speech is not matching with "Hello" text then 
the result text will be shown with red color.

* To test this demo code you have to create a google cloud project in https://console.cloud.google.com/ and then enable Speech API.

* You have to get your credential.json file from Cloud console (https://console.cloud.google.com/) and put it inside res/raw/credential.json to test.

* Follow the following path to get credential.json 
  API & Services -> credential -> Create credential -> Service account key then download your credential.json from there.

<img src="https://github.com/sujitpanda/Google-Cloud-Speech-API/blob/master/Screenshot.png" width="300" height="500"/>

Special thanks to Mr.Frank Natividad from Google for really nice work on Cloud Speech API demo for Android. I have taken help from his implementation.  ( https://github.com/GoogleCloudPlatform ) and also
Mr. Yang Hui for custom VoiceView (https://github.com/kyze8439690/AndroidVoiceAnimation)
