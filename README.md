<!-- File: res/layout/activity_main.xml -->
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp"
    android:background="#FFFFFF">

    <!-- WoodTrendExterior logotips -->
    <ImageView
        android:id="@+id/logoImageView"
        android:layout_width="wrap_content"
        android:layout_height="100dp"
        android:src="@drawable/woodtrend_logo"
        android:contentDescription="WoodTrendExterior logotips"
        android:adjustViewBounds="true"
        android:scaleType="centerInside" />

    <!-- Lietotnes virsraksts -->
    <TextView
        android:id="@+id/titleTextView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="WoodTrendExterior Budžeta Pārskats"
        android:textSize="24sp"
        android:textStyle="bold"
        android:textColor="#000000"
        android:layout_marginTop="16dp" />

    <!-- Budžeta pārskata dati -->
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        android:layout_marginTop="16dp">

        <!-- Ienākumu sadaļa -->
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Ienākumi"
            android:textStyle="bold" />
        <TextView
            android:id="@+id/incomeTextView"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="0.00"
            android:textSize="18sp"
            android:textColor="#333333" />

        <!-- Izdevumu sadaļa -->
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Izdevumi"
            android:textStyle="bold"
            android:layout_marginTop="8dp" />
        <TextView
            android:id="@+id/expensesTextView"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="0.00"
            android:textSize="18sp"
            android:textColor="#333333" />

        <!-- Bilances sadaļa -->
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Bilance"
            android:textStyle="bold"
            android:layout_marginTop="8dp" />
        <TextView
            android:id="@+id/balanceTextView"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="0.00"
            android:textSize="18sp"
            android:textColor="#333333" />
    </LinearLayout>

    <!-- Poga, lai atjaunotu pārskatu -->
    <Button
        android:id="@+id/updateButton"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Atjaunot pārskatu"
        android:layout_marginTop="16dp" />

</LinearLayout>
