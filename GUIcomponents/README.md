# Ex.No: 2 To develop an application that uses GUI Components with Fonts and Colors. 
Note: Create button for colors and fonts while clicking color or font button should change 


## AIM:

To create an application that uses GUI Components with Fonts and Colors using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Studio and click on "File" -> "New" -> "New Project".

Step 2 Design the layout by adding GUI components like buttons, text views, etc., and assign appropriate IDs to them.

Step 3: Add a button for colors and a button for fonts, and set their respective click listeners.

Step 4: In the click listener for the color button, prompt the user to select a color and change the background color of a specific view or the entire layout based on the user's selection.

Step 5: In the click listener for the font button, prompt the user to select a font and change the font of a specific view or the entire layout based on the user's selection.

Step 6: In the MainActivity.java file, implement the logic to display a message when the application starts.

Step 7: Save the changes and run the application on an Android device or emulator.

Step 8: Verify that the application launches successfully and displays the message.

## PROGRAM:
```
/*
Program to print the text “GUIcomponent”.
Developed by: NAADIRA SAHAR N
Registeration Number : 212221220034
*/
```
##activity_main.xml:

    <?xml version="1.0" encoding="utf-8"?>
    <LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity">
    <TextView
        android:id="@+id/textView"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="30dp"
        android:gravity="center"
        android:text="Student Details"
        android:textSize="25sp"
        android:textStyle="bold" />
    <TextView
        android:id="@+id/textView2"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="30dp"
        android:gravity="left"
        android:text="Name:NAADIRA SAHAR N"
        android:textSize="25sp"
        android:textStyle="bold" />
    <TextView
        android:id="@+id/textView3"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="30dp"
        android:gravity="left"
        android:text="Reg_no:212221220034"
        android:textSize="25sp"
        android:textStyle="bold" />
    <TextView
        android:id="@+id/textView4"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="30dp"
        android:gravity="left"
        android:text="Department:IT"
        android:textSize="25sp"
        android:textStyle="bold" />
    <TextView
        android:id="@+id/textView5"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="30dp"
        android:gravity="left"
        android:text="Year:3rd Year"
        android:textSize="25sp"
        android:textStyle="bold" />
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="horizontal">
        <Button
            android:id="@+id/button1"
            android:layout_width="108dp"
            android:layout_height="wrap_content"
            android:layout_margin="18dp"
            android:text="size"
            android:textSize="14sp" />

        <Button
            android:id="@+id/button2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_margin="18dp"
            android:text="color"
            android:textSize="14sp" />

        <Button
            android:id="@+id/button3"
            android:layout_width="108dp"
            android:layout_height="wrap_content"
            android:layout_margin="18dp"
            android:text="style"
            android:textSize="14sp" />
    </LinearLayout>
</LinearLayout>


## OUTPUT:

![Screenshot (154)](https://github.com/Naadira/Mobile-Application-Development/assets/128135126/7de32b9e-8311-4ee0-bc49-d3d50d751c57)

![Screenshot (156)](https://github.com/Naadira/Mobile-Application-Development/assets/128135126/320a92f5-673d-40fc-b5c4-4b58934c9733)

![Screenshot (157)](https://github.com/Naadira/Mobile-Application-Development/assets/128135126/c647eb15-b8a4-4cff-9f67-7625c833bf8f)


## RESULT
Thus a Simple Android Application that uses GUI Components with Fonts and Colors using Android Studio is developed and executed successfully.


