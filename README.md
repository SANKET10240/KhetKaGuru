# KhetKaGuru
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/layout1"
    android:orientation="vertical"
    tools:context=".ExploreActivity">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical">

        <TextView
            android:id="@+id/textView2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:paddingLeft="20dp"
            android:paddingTop="40dp"
            android:text="Explore"
            android:textSize="20sp"
            android:textStyle="bold"
            tools:layout_editor_absoluteX="35dp"
            tools:layout_editor_absoluteY="37dp" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="16dp"
            android:paddingLeft="20dp"
            android:paddingTop="20dp"
            android:text="Select a State:"
            android:textColor="#000000"
            android:textSize="18sp" />

        <Spinner
            android:id="@+id/spinner_indian_states"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="20dp"
            android:paddingLeft="10dp"
            android:spinnerMode="dropdown" />

        <Spinner
            android:id="@+id/spinner_indian_cities"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="20dp"
            android:paddingLeft="10dp"
            android:spinnerMode="dropdown" />

        <Button
            android:id="@+id/btnCheck"
            android:layout_width="107dp"
            android:layout_height="wrap_content"
            android:background="@null"
            android:text="Check" />
    </LinearLayout>

    <LinearLayout
        android:id="@+id/load"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="vertical">

        <TextView
            android:id="@+id/textViewWeather"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:textSize="18sp"
            android:paddingTop="16dp"
            android:paddingLeft="10dp"/>

        <TextView
            android:id="@+id/textViewBestPractices"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:textSize="16sp"
            android:paddingTop="16dp"
            android:paddingLeft="10dp"/>
    </LinearLayout>
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:padding="10dp"
    android:layout_marginBottom="5dp"
    android:orientation="vertical">

    <LinearLayout
        android:id="@+id/userMessageContainer"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:visibility="gone"
        android:padding="10dp"
        android:gravity="start">

    <TextView
        android:id="@+id/userMessageTextView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textSize="16sp"
        android:textColor="@android:color/white" />
    </LinearLayout>

    <LinearLayout
        android:id="@+id/botMessageContainer"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:visibility="gone"
        android:padding="10dp"
        android:gravity="start">

        <TextView
        android:id="@+id/botMessageTextView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textSize="16sp"
        android:textColor="@android:color/white" />
    </LinearLayout>

</LinearLayout>
</LinearLayout>




