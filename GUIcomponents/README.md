# Ex.No: 2 To develop an application that uses GUI Components with Fonts and Colors. 
Note: Create button for colors and fonts while clicking color or font button should change 


## AIM:

To create an application that uses GUI Components with Fonts and Colors using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

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



## PROGRAM:
```
/*
Program to print the text “GUIcomponent”.
Developed by: NAADIRA SAHAR N
Registeration Number : 212221220034
*/
```

## OUTPUT




## RESULT
Thus a Simple Android Application that uses GUI Components with Fonts and Colors using Android Studio is developed and executed successfully.


