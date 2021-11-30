# android-dependencies
--------------------------------------------------------------------
//Retrofit


        Build.gradle- Module    
        
        1. id 'kotlin-kapt'

        2.  implementation 'com.squareup.retrofit2:retrofit:2.9.0'
            //GSON converter
            implementation 'com.squareup.retrofit2:converter-gson:2.9.0'
            
        
// Dagger-Hilt
         Build.gradle- Module Level
         
         id 'kotlin-kapt'
         id 'dagger.hilt.android.plugin'
         
          //dagger hilt
          implementation("com.google.dagger:hilt-android:2.38.1")
          kapt("com.google.dagger:hilt-android-compiler:2.38.1")
          
          Build.gradle- Project Level
          
          //dagger hilt class path
          classpath("com.google.dagger:hilt-android-gradle-plugin:2.38.1")
        
      
        
       
