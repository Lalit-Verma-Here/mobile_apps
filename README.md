# Mobile Computing Lab Applications

This repository contains the mobile applications developed during the Mobile Computing Lab exercises. Each folder represents a distinct exercise demonstrating different Android development concepts.

## Projects Overview

### 1. [HelloWorld](./HelloWorld/) (Exercise 1)
A simple "Hello World" Android application built using Kotlin. It introduces the basic structure of an Android project and demonstrates how to display a simple user interface containing a text message using `ConstraintLayout`.

### 2. [Canvas App](./Canvas/) (Exercise 2)
An Android application written in Java that demonstrates how to use the Android `Canvas` and `Paint` classes to procedurally draw 2D shapes (lines, rectangles, circles, ovals, and text) on a custom Android `View`. 

### 3. [Pictures Slideshow](./Pictures/) (Exercise 3)
An automated image slideshow application written in Java. It cycles through a predefined set of images using `android.os.Handler` and `android.os.Looper` to schedule and execute image updates seamlessly on the main UI thread.

### 4. [Sum Calculator](./SumCalculator/) (Exercise 4)
A basic calculator Android application that allows users to perform simple arithmetic operations (Addition, Subtraction, Multiplication, Division) on two input numbers. Features include input validation, reset functionality, and error handling.

### 5. [Toggle Button](./ToggleButton/) (Exercise 5)
An Android application written in Java that demonstrates the use of a `ToggleButton`. It uses an `OnCheckedChangeListener` to detect state changes and displays a `Toast` message indicating whether the button is toggled ON or OFF.

### 6. [Android Layouts](./Layouts/) (Exercise 6)
An Android application that demonstrates the use of different fundamental Android layouts, including `LinearLayout`, `RelativeLayout`, and `TableLayout`. It includes a main activity acting as a navigation hub to explore specialized activities for each layout type.

### 7. [Android Widget](./Widget/) (Exercise 7)
An Android application that demonstrates how to create a home screen widget. It covers the basics of `AppWidgetProvider`, updating the widget via `RemoteViews`, and configuring widget metadata in XML.

### 8. [Temperature Converter](./Temperature/) (Exercise 8)
A simple temperature conversion application. It demonstrates handling user inputs, performing calculations (like Celsius to Fahrenheit), and updating the UI dynamically based on the input.

### 9. [Gender Selection](./Gender/) (Exercise 9)
An Android application demonstrating the use of selection controls, such as `RadioButton` and `RadioGroup`, to choose an option like gender. It processes user interaction and responds to selection changes.

### 10. [Bottom Navigation Menu](./Menu/) (Exercise 10)
An Android application written in Kotlin that demonstrates a Bottom Navigation Menu. It uses the Android Navigation Architecture Component to switch between multiple fragments (Home, Dashboard, Notifications) seamlessly.

## Getting Started

To run any of the applications:
1. Open the specific project folder (e.g., `HelloWorld`, `Canvas`) in Android Studio.
2. Sync the project with Gradle files.
3. Build and run the project on an Android emulator or a physical Android device.
