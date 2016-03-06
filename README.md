# Android-WheelProgress
A progress bar for my ongoing project.

![Check Diagram](art/pic-1.png)

## Download

via Gradle:

    dependencies {
      compile 'com.zekapp.library:progreswheelview:1.1.0'
    }
    
## Usage

       <com.app.progresviews.ProgressWheel
            android:id="@+id/wheelprogress"
            android:layout_width="150dp"
            android:layout_height="150dp"
            app:barWidth="17dp"
            app:marginBtwText= "15dp"
            app:countText="931,199"
            app:definitionText="Steps"
            app:countTextColor="@android:color/black"
            app:defTextColor="@android:color/black"
            app:progressColor="#64b324"
            app:defTextSize="10sp"
            app:countTextSize="20sp"
            app:percentage="90"/>

## License

        Copyright (C) 2015 Zeki Guler
        Copyright (C) 2011 The Android Open Source Project
        
        Licensed under the Apache License, Version 2.0 (the "License");
        you may not use this file except in compliance with the License.
        You may obtain a copy of the License at
        
           http://www.apache.org/licenses/LICENSE-2.0
        
        Unless required by applicable law or agreed to in writing, software
        distributed under the License is distributed on an "AS IS" BASIS,
        WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
        See the License for the specific language governing permissions and
        limitations under the License.