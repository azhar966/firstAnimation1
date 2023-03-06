Android animation

Import animation 
Lottie FIles -> download in json -> follow steps 
To implement all things
Implement files in build gradle
Add version of file

3. Paste json file into -> res -> new android resource directory with, select raw type -> paste
4. Paste XML resource code

//XML code
<com.airbnb.lottie.LottieAnimationView
        android:id="@+id/animationView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_margin="50dp"
        app:lottie_rawRes="@raw/animation"
        app:lottie_autoPlay="true"
        app:lottie_loop="true"/>


//gradleCode
dependencies {

      implementation "com.airbnb.android:lottie:3.4.0"
}


// jsonFile 
https://lottiefiles.com/9589-wood-like-button-loading

