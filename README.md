# Sandwich Club Project Starter Code

This is the introductory project for the "Grow With Google" scholarship Udacity/Google Android Developer Nanodegree 
program, where you complete the "Sandwich Club" app's starter code and submit it for review, just to ensure that as 
everyone starts the Nanodegree program they are on the same page as far as understanding the process of completing 
projects according to requirements, and correctly submitting them for review and making any requested changes 
afterward. #GoogleUdacityScholars #GrowWithGoogle

## Screenshots
![MainActivity](https://github.com/tachyonlabs/Grow-With-Google-Udacity-Android-Developer-Nanodegree-Sandwich-Club/blob/master/MainActivity.png "MainActivity") &nbsp; &nbsp; ![DetailActivity](https://github.com/tachyonlabs/Grow-With-Google-Udacity-Android-Developer-Nanodegree-Sandwich-Club/blob/master/DetailActivity.png "DetailActivity")

## Project Overview
In this project, you will complete the **Sandwich Club** app to
show the details of each sandwich once it is selected.

## Why this Project

Building a layout and populating its fields from data received as JSON
is a common task for Android Developers. Although JSON parsing is usually
done using libraries, writing the JSON parsing for this project will
help you to better understand how it is processed.

## What Will I Learn?
Through this project, you will:

* [x] Learn how to submit projects for review
* [x] Practice JSON parsing to a model object
* [x] Design an activity layout
* [x] Populate all fields in the layout accordingly

## How Do I Complete this Project?

* [x] Download the [Sandwich Club app starter code.](https://github.com/udacity/sandwich-club-starter-code)
* [x] Design the layout for the detail activity so the different elements display in a sensible way. 
* [x] Implement the JSON parsing in JsonUtils so it produces a Sandwich Object that can be used to populate the UI that you designed.

## Common Project Requirements

* [x] App is written solely in the Java Programming Language
* [x] App conforms to common standards found in the Android Nanodegree General Project Guidelines NOTE: It is okay if the app does not handle rotation properly or does not restore the data using onSaveInstanceState/onRestoreInstanceState)

## Core Functionality

* [x] JSON data is parsed correctly to a Sandwich object in JsonUtils
* [x] JSON is parsed without using 3rd party libraries
* [x] DetailActivity shows all Sandwich details correctly
* [x] Detail layout includes a ScrollView so all the details are visible in small screen devices
* [x] Sandwich details are shown in a sensible layout. For example, ingredients appear next to the ingredients label

## Udacity Android Developer Nanodegree - Core App Quality Guidelines
### Visual Design and User Interaction
#### Standard Design

* [x] App does not redefine the expected function of a system icon (such as the Back button).
* [x] App does not redefine or misuse Android UI patterns, such that icons or behaviors could be misleading or confusing to users.

#### Navigation

* [x] App supports standard system Back button navigation and does not make use of any custom, on-screen "Back button" prompts.
* [x] All dialogs are dismissible using the Back button.
* [x] Pressing the Home button at any point navigates to the Home screen of the device.

### Functionality
#### Permissions

* [x] App does not redefine or misuse Android UI patterns, such that icons or behaviors could be misleading or confusing to users.
* [x] App does not request permissions to access sensitive data or services that can cost the user money, unless related to a core capability of the app.

#### User/App State

* [ ] (N/A) App correctly preserves and restores user or app state, that is, student uses a bundle to save app state and restores it via onSaveInstanceState/onRestoreInstanceState. For example,

- When a list item is selected, it remains selected on rotation.
- When an activity is displayed, the same activity appears on rotation.
- User text input is preserved on rotation.
- Maintains list items positions on device rotation.
    
* [x] When the app is resumed after the device wakes from sleep (locked) state, the app returns the user to the exact state in which it was last used.
* [x] When the app is relaunched from Home or All Apps, the app restores the app state as closely as possible to the previous state.

### Performance and Stability
#### Stability

* [x] App does not crash, force close, freeze, or otherwise function abnormally on any targeted device.

### Google Play
#### Content Policies

* [x] All content is safe for work content.
* [ ] (N/A) App adheres to the Google Play Store App policies.
* [x] App’s code follows standard Java/Android Style Guidelines.
