# ZoomTextView
A custom TextView, when pinch in out gesture used, then it reizes text size. 

How to use ?
```
 <noman.zoomtextview.ZoomTextView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:gravity="center"
        android:text="@string/sample_string"/>
```

Can also set the zoom in threshold using this method

```
 textView.setZoomLimit(float value);
```
Initial value of threshold is 3.0, so text will be zoomed 3 times its original size.

Demo 
