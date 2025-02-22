# easy-language-app
easy language

<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp"
    android:gravity="center">

    <TextView
        android:id="@+id/wordTextView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Word"
        android:textSize="24sp"
        android:padding="16dp"/>

    <Button
        android:id="@+id/showTranslationButton"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Show Translation"
        android:layout_marginTop="16dp"/>

    <TextView
        android:id="@+id/translationTextView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Translation"
        android:textSize="18sp"
        android:layout_marginTop="16dp"
        android:visibility="gone"/>

    <Button
        android:id="@+id/nextWordButton"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Next Word"
        android:layout_marginTop="16dp"/>
</LinearLayout>
