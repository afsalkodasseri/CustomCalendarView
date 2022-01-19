# CustomCalendarView
Android calenderview sometimes doesn't meet the user needs.So you can use this for your calendarview and also can be customisable.

-Paste java files in your main directory of your project

-Paste the back.xml,front.xml,select_date.xml,today.xml to your drawable directory

-Paste the other xml files in your layout directory

change the package names in your java files.

-And create the component in your activity layout
 
    <com.your_app_package.CustomCalenderView
        android:id="@+id/mycal"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="64dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.496"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
          
You can customize as you wish.

