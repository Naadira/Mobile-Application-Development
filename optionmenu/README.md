# Ex.No:10 To create a option menu to display menu items.


## AIM:

To create a option menu to display menu items using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:
Step 1: Open Android Studio and then click on File -> New -> New project.

Step 2: Then type the Application name as OptionMenu and click Next.

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Create a option.xml file to create options in your menu.

Step 7: Display options in MainActivity file.

Step 8: Save and run the application.

## PROGRAM:
```
/*
Program to print the text “optionmenu”.
Developed by: NAADIRA SAHAR N
Registeration Number : 212221220034
*/
```
**activity_xml:**

    <?xml version="1.0" encoding="utf-8"?>
    <androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:src="@drawable/amgus"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        tools:srcCompat="@tools:sample/avatars" />
    </androidx.constraintlayout.widget.ConstraintLayout>
    
**option.xml:**

    <?xml version="1.0" encoding="utf-8"?>
    <menu xmlns:android="http://schemas.android.com/apk/res/android">
    <item android:title="PRIME 1" />
    <item android:title="PRIME 2" />
    <item android:title="PRIME 3" />
    </menu>
**MainActivity.java:**

    package com.example.menuapp;

    import androidx.appcompat.app.AppCompatActivity;

    import android.os.Bundle;
    import android.view.Menu;
    import android.view.MenuInflater;

    public class MainActivity extends AppCompatActivity {
     @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }
    @Override
    public boolean onCreateOptionsMenu(Menu menu) {
        MenuInflater m = getMenuInflater();
        m.inflate(R.menu.option,menu);
        return true;
    }
    }


## OUTPUT:
![Xml](https://github.com/HariHaranLK/Mobile-Application-Development/assets/132996089/b7cc1ff6-2b96-469d-aa49-e1d5a95295ca) <br>
![Main](https://github.com/HariHaranLK/Mobile-Application-Development/assets/132996089/25badaf2-006c-4716-a599-cb60479fedf8) <br>
<img src="https://github.com/HariHaranLK/Mobile-Application-Development/assets/132996089/22986e9f-d347-47d1-84f9-f18af2edf0f7" alt="hi width="95%" height="75%"> <br>
<img src="https://github.com/HariHaranLK/Mobile-Application-Development/assets/132996089/bfa5a2cf-ab10-4fa3-baf9-209bb4399137" alt="hii width="95%" height="75%"> <br>



## RESULT:
Thus a Simple Android Application to create a option menu to display menu items using Android Studio is developed and executed successfully.


