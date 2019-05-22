# FaceDetector
An application that runs on Android things toolkit. Does basic facial recognition and object recognition thanks to the Firebase Machine Learning API and cloud vision.It takes a picture of a person and analyses the persons facial features. It can determine if the person is smiling , Sad e.t.c.

## Installation
This project is on android so you'll definitely need Android Studio.
Also you'll need your own google-services.json file . Add this to the app directory
For the interaction with the rainbowhat .

```gradle
 implementation 'com.google.android.things.contrib:driver-button:1.0'
 implementation 'com.google.android.things.contrib:driver-rainbowhat:1.0'
```

## Usage

```text
The application will take a picture when you press the 'A' Button. It will then save the image to a cloud storage bucket. From there it will upload the image to firebase where it will user the machine Learning api where it will run facial recognition. From this it will determine various things based on the landmarks on your face. From there it will also send the image the Cloud Vision API where it will do object detection and return a list of objects .
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
