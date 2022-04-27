
## source code

### main activity.java
```java
package com.example.myapplication;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;

public class MainActivity extends AppCompatActivity{
    @Override
    protected void onCreate(Bundle savedInstanceState){
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }
}
```
### activity_main.xml
```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="welcome"
        android:textAlignment="center"
        android:textColor="#87CEEB"
        android:textSize="48sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"></TextView>



</androidx.constraintlayout.widget.ConstraintLayout>
```
### Output
![Screenshot (3)](https://user-images.githubusercontent.com/75234946/165219935-18d74d58-5d98-480d-8d15-5eb78e13a39c.png)

###Result
```
Thus a Simple Android Application Welcome should be in Center Alignment, Font Color: blue,using Android Studio is developed and executed successfully.
```
