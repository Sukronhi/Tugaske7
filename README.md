# Tugaske7
Background 
<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android"
    android:shape="rectangle">
    <corners android:radius="1000dp" />
    <solid android:color="#5EAE9E" />
    <stroke
        android:width="5dip"
        android:color="#5EAE9E" />
    <padding
        android:bottom="4dp"
        android:left="4dp"
        android:right="4dp"
        android:top="4dp" />
</shape>

Layout

<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#4A9586"
    android:orientation="vertical"
    android:scrollbarAlwaysDrawVerticalTrack="true">

</RelativeLayout>


<RelativeLayout
    android:layout_width="fill_parent"
    android:layout_height="wrap_content"
    android:layout_below="@+id/login_title"
    android:layout_marginLeft="30dp"
    android:layout_marginRight="30dp"
    android:layout_marginTop="70dp"
    android:background="#fff"
    android:elevation="4dp"
    android:orientation="vertical"
    android:padding="20dp"
    android:id="@+id/relativeLayout">

</RelativeLayout>

Icon
<LinearLayout
    android:layout_width="fill_parent"
    android:layout_height="wrap_content"
    android:orientation="vertical"
    android:paddingTop="30dp">

</Linear Layout>


Penambahan widget

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#4A9586"
    android:orientation="vertical"
    android:scrollbarAlwaysDrawVerticalTrack="true">

    <RelativeLayout
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        android:layout_below="@+id/login_title"
        android:layout_marginLeft="30dp"
        android:layout_marginRight="30dp"
        android:layout_marginTop="70dp"
        android:background="#fff"
        android:elevation="4dp"
        android:orientation="vertical"
        android:padding="20dp"
        android:id="@+id/relativeLayout">

        <LinearLayout
            android:layout_width="fill_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            android:paddingTop="30dp">

            <android.support.design.widget.TextInputLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content">

                <EditText
                    android:layout_width="fill_parent"
                    android:layout_height="wrap_content"
                    android:drawableLeft="@drawable/username"
                    android:hint="User Name"
                    android:inputType="textEmailAddress" />
            </android.support.design.widget.TextInputLayout>

            <android.support.design.widget.TextInputLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content">

                <EditText
                    android:layout_width="fill_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginTop="16dp"
                    android:drawableLeft="@drawable/password"
                    android:hint="Password"
                    android:inputType="numberPassword" />
            </android.support.design.widget.TextInputLayout>

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_gravity="right"
                android:paddingTop="5dp"
                android:text="Forgot Password?" />


            <Button
                android:layout_width="fill_parent"
                android:layout_height="wrap_content"
                android:layout_margin="22dp"
                android:background="#d67601"
                android:text="Sign in"
                android:textAllCaps="false"
                android:textColor="#fff"
                android:textSize="18sp" />
        </LinearLayout>
    </RelativeLayout>

    <ImageButton
        android:id="@+id/user_profile_photo"
        android:layout_width="100dp"
        android:layout_height="100dp"
        android:layout_below="@+id/login_title"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="16dp"
        android:background="@drawable/background_profile"
        android:elevation="4dp"
        android:src="@drawable/user_icon" />

    <TextView
        android:id="@+id/login_title"
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        android:layout_marginTop="26dp"
        android:gravity="center_horizontal"
        android:text="Login "
        android:textColor="#fff"
        android:textSize="26sp"
        android:textStyle="bold"
        android:layout_alignParentTop="true"
        android:layout_alignParentStart="true" />
</RelativeLayout>
