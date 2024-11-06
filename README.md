[![](https://jitpack.io/v/sakacyber/html-textview.svg)](https://jitpack.io/#sakacyber/html-textview)

## Quick Start

**ComplexView** is available on jitpack.

Add dependency:

```groovy
implementation "com.github.ngoconglinh:aComplexView:1.0.0"
```

## Usage

to use **ComplexView**:

```xml
    <com.lutech.ComplexView.ComplexView
        android:id="@+id/complexView"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_gravity="center"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:radius="@dimen/_20sdp"
        app:shadow="true"
        app:shadowAlpha="80"
        app:shadowColor="#07ADFB"
        app:shadowSpread="4">
    
        <ViewGroup
            android:layout_width="match_parent"
            android:layout_height="match_parent" />
    </com.lutech.ComplexView.ComplexView>
```
