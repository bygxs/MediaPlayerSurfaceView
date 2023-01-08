# MediaPlayerSurfaceView

Tutorial Exerciese
Medial Player SurfaceView
The app runs but didn't work due to non existen webpage resource
 "http://mic.duytan.edu.vn:83/FINAL.mp4"
 
 Greate for learning
 
 1. android manifist 
   <uses-permission android:name="android.permission.INTERNET"/>
   
 2. style editing in themes
  ....
           <item name="android:statusBarColor">?attr/colorPrimaryVariant</item>
        <!-- Customize your theme here. -->
<!--        <item name="windowNoTitle">true</item>-->
<!--        <item name="windowActionBar">false</item>-->
<!--        <item name="android:windowFullscreen">true</item>-->
<!--        <item name="android:windowContentOverlay">@null</item>-->

    </style>
</resources>

3. Generally implementing 
... AppCompatActivity implements SurfaceHolder.Callback, MediaPlayer.OnPreparedListener {...

   
