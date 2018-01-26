# BaskeballApp
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/baskeball">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="horizontal">

        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:orientation="vertical"
            tools:context="com.example.android.courtcounter.MainActivity">


            <TextView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginTop="16dp"
                android:gravity="center_horizontal"
                android:padding="4dp"
                android:text="Team A"
                android:textColor="#000000"
                android:textSize="30dp" />


            <TextView
                android:id="@+id/team_a_score"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="24dp"
                android:layout_marginTop="16dp"
                android:gravity="center_horizontal"
                android:padding="4dp"
                android:text="0"
                android:textColor="#FF1744"
                android:textSize="50dp" />


            <Button
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="8dp"
                android:layout_marginLeft="24dp"
                android:layout_marginRight="24dp"
                android:onClick="submitThreePoints"
                android:text="+3 points" />

            <Button
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="8dp"
                android:layout_marginLeft="24dp"
                android:layout_marginRight="24dp"
                android:onClick="submitTwoPoints"
                android:text="+2 points" />

            <Button
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginLeft="24dp"
                android:layout_marginRight="24dp"
                android:onClick="submitFreeThrow"
                android:text="free throw" />

        </LinearLayout>

        <View
            android:layout_width="3dp"
            android:layout_height="match_parent"
            android:layout_marginBottom="80dp"
            android:layout_marginTop="5dp"
            android:background="#000000" />

        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:orientation="vertical"
            tools:context="com.example.android.courtcounter.MainActivity">


            <TextView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginTop="16dp"
                android:gravity="center_horizontal"
                android:padding="4dp"
                android:text="Team B"
                android:textColor="#000000"
                android:textSize="30dp" />

            <TextView
                android:id="@+id/team_b_score"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="24dp"
                android:layout_marginTop="16dp"
                android:gravity="center_horizontal"
                android:padding="4dp"
                android:text="0"
                android:textColor="#FF1744"
                android:textSize="50dp" />


            <Button
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="8dp"
                android:layout_marginLeft="24dp"
                android:layout_marginRight="24dp"
                android:onClick="submitThreePointsB"
                android:text="+3 points" />

            <Button
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="8dp"
                android:layout_marginLeft="24dp"
                android:layout_marginRight="24dp"
                android:onClick="submitTwoPointsB"
                android:text="+2 points" />

            <Button
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginLeft="24dp"
                android:layout_marginRight="24dp"

                android:onClick="submitFreeThrowB"
                android:text="free throw" />

        </LinearLayout>

    </LinearLayout>

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_marginBottom="32dp"
        android:onClick="resetButton"
        android:text="RESET"

        />


</RelativeLayout>
