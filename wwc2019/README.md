# Mobile Serverless with Firestore and Google Cloud Functions

This project is about a workshop showing how to use Google Cloud Functions and Google Firebase Firestore to build a serverless backend for a mobile application. This uses Google's provided sample application and codelab, Friendly Eats, and is available on either iOS or Android.

# The Story

You've built a Friendly Eats restaurant reviewing app in your area to share restaurants and let the community review and share their opinions. Your app has become so popular, restuarants are emailing you to ask if they can be sent an email with any new reviews on their restaurants. As you build this feature, you start thinking about other things you can do too:
* Restaurant owners getting a list of all their reviews
* Restaurant owners subscribing and unsubscribing from new reviews
* Restaurant owners commenting on reviews

Let's build a serverless solution for these features.

# Setup

For this workshop, you will need to do the following setup:
1. Create a Google Cloud Platform account to access the Firebase
2. Install either XCode or Android Studio to run the app
3. Pull down the github sample repo for your platform and languages

## Do I need to run a mobile app for this workshop?

You can build the serverless solution and test it without running an app. You will still need to set up Firebase to create the Firestore triggers.

## Set up a (free) GCP Account

## Install Android Studio

## Install XCode

## Clone the github repo 5 min

## Run the app 10 min

## Create a review 2 min

## See in Firestore

## Create a cloud function trigger set to Firestore create to the review collection 10 min

## Cloud function prints review to logs

## Cloud function sends a message 5 min

## Second cloud function to get list of all reviews for a restaurant/average rating

## What is Firebase/Firestore/Cloud Functions 10 min

## QA - 10 min
Current total: 50 min

https://firebase.google.com/docs/firestore/

https://firebaseopensource.com/projects/firebase/friendlyeats-android/

https://codelabs.developers.google.com/codelabs/firestore-android/#0

https://codelabs.developers.google.com/codelabs/firestore-ios/#0

https://cloud.google.com/functions/docs/calling/cloud-firestore

https://cloud.google.com/functions/docs/calling/firebase-auth

https://cloud.google.com/functions/docs/calling/firebase-remote-config

https://cloud.google.com/functions/docs/calling/google-analytics-firebase

# Devops
- Deploying from command line source control
- Logging and Stackdrivers
- Retries and limiting executions
- environment variables