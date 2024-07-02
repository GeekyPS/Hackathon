# Price Precictor ML Model💬

</br>

<p align="center">
  <img src="https://github.com/GeekyPS/Tagify/assets/97830682/c456cbbf-2cf9-4f9d-8c4c-7f9f2c18ca57"/>
</p>


<p align="center">
  <img src="https://github.com/GeekyPS/Hackathon/assets/97830682/155f70a9-b4fe-4dcb-8f6a-42679a8a97f6)"/>
</p>


<p  align="center">
<a  href="https://flutter.dev"  target="_blank"><img  height="39"  src="[https://user-images.githubusercontent.com/37345795/205487266-9604e883-3bd3-45a5-b172-f4617d911ee3.png](https://github.com/GeekyPS/Tagify/assets/97830682/dd6d8a81-922a-4a5f-841c-715ce24739ff)"  alt="Flutter Logo"></a> <a>&nbsp;&nbsp;&nbsp;</a>

</p>

This repository contains a machine learning model designed to predict car parts based on various input features. The model leverages advanced algorithms to provide accurate predictions, aiding in inventory management, maintenance, and repair services.
## Setting up the project in your local environment💻

<p align="center">
    <img src="https://user-images.githubusercontent.com/74055102/141175363-4c00515a-2658-475e-b510-394110d43ec5.png" height=400/>
</p>

1. [Fork](https://github.com/letsintegreat/Tagify/fork) this repository.
2. Clone the **forked** repository:
```
git clone https://github.com/<your username>/Tagify
cd Tagify
```
3. Add a remote to the upstream repository:
```
# Typing the command below should show you only 1 remote named origin with the URL of your forked repository
git remote -v
# Adding a remote for the upstream repository
git remote add upstream https://github.com/letsintegreat/Tagify
```
4. Get [Flutter](https://docs.flutter.dev/get-started/install) and [Firebase CLI](https://firebase.google.com/docs/cli?authuser=0&hl=en#install_the_firebase_cli) if you don't already have them.
5. Run `flutter pub get` to get the dependencies.
6. If you have not yet logged into `Firebase CLI` and activate `FlutterFire CLI` globally:
```
firebase login
dart pub global activate flutterfire_cli
```
7. Create a new project on [Firebase Console](https://console.firebase.google.com/), activate Google Sign In, and activate Firebase Firestore in **test mode**.
8. Configure your flutter app with the newly created project on firebase console:
```
flutterfire configure
```

This automatically registers your per-platform apps with Firebase and adds a `lib/firebase_options.dart` configuration file to your Flutter project.

9. Finally, run the app:
```
flutter run
```

## Contributing to the project 🛠

<p align="center">
    <img src="https://user-images.githubusercontent.com/74055102/141175911-fbefae23-d381-44b3-bcfb-d369cfb66659.png" height=400/>
</p>

Now that you have the project set up in your local environment, follow the steps below to contribute!

1. Take up an already existing issue or create a new (but a valid) one via [issue tracker](https://github.com/letsintegreat/Tagify/issues).
2. Pull the latest code in.
```
# Make sure you are on the main branch
git pull upstream main
```
3. Create a new branch.
```
# Replace xx with the issue number you are working on and give your branch a good name
git checkout -b issue-xx-a-good-name
```
4. Make your changes!
5. Once done with a particular feature, bug fix, or a documentation part, add your changes to the staging area. *Please don't add `lib/firebase_options.dart` file to your commit, it is meant to be kept as a secret.*
```
git add .
```
6. Review and commit your changes.
```
# The message should be in present tense, for ex - "Added feature x" is not ideal but "Add feature X" is
git commit -m "a meaningful message"
```
7. Push your changes!
```
git push --set-upstream origin <your-branch-name>
```
8. Create a pull request from GitHub and wait for the review!

**Contributions of any kind welcome!**

# Authors

This project was developed under a hackathon by

- Akshat Kumar
- Priyanshu Srivastava
- Samarth Trivedi
- Vasu Sain

<p align="center">
  
</p>
