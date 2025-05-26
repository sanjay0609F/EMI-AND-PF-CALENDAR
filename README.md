?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:orientation="vertical"
    android:padding="16dp"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <EditText android:id="@+id/editPrincipal"
        android:hint="Principal Amount"
        android:inputType="numberDecimal"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"/>

    <EditText android:id="@+id/editRate"
        android:hint="Annual Interest Rate (%)"
        android:inputType="numberDecimal"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"/>

    <EditText android:id="@+id/editMonths"
        android:hint="Loan Duration (Months)"
        android:inputType="number"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"/>

    <EditText android:id="@+id/editSalary"
        android:hint="Basic Salary"
        android:inputType="numberDecimal"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"/>

    <Button android:id="@+id/calculateButton"
        android:text="Calculate"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"/>

    <TextView android:id="@+id/textResult"
        android:text=""
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:paddingTop="16dp"/>

</LinearLayout>
