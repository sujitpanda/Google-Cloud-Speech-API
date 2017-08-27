# Google-Cloud-Speech-API
Google Cloud Speech API Android Project Demo

This is demo project on implementation of new Google Cloud Speech API in Android project. 
This will record user speech and convert to text. There is one demo text "Hello" is visible on the activity screen. 
So when user open the app and say "Hello" it will be matched with the "Hello" test on the screen 
and text color will be changed to Red otherwise in case user speech is not matching with "Hello" test then 
the speech will be shown with Red color.

First create a google cloud project in https://console.cloud.google.com/ and then enable Speech API.

You have to get your credential.json file from Cloud console (https://console.cloud.google.com/) and put it inside res/raw/credential.json to work.
API & Services -> credential -> Create credential -> Service account key then download your credential.json from there.

Special thanks to Mr. Yuichi Araki from Google for really nice work on Cloud Speech API demo for Android. I have taken help from his implementation.  ( https://github.com/GoogleCloudPlatform ) and also
Mr. Yang Hui for custom VoiceView (https://github.com/kyze8439690/AndroidVoiceAnimation)
