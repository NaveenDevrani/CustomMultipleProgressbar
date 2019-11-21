## CustomMultipleProgressbar  

# Step 1. Add the JitPack repository to your build file   
```
allprojects {  
	  	repositories {  
			...  
		  	maven { url 'https://jitpack.io' }  
	 	}  
	 }
```
   
 # Step 2. Add the dependency  
 ```
 	dependencies {
		implementation 'com.github.NaveenDevrani:customMultipleProgressbar:1.0'
	}  
  ```
## step 3 add in Xml 
```
<com.naveen.custommultpleprogressbars.CustomProgressbar  
        android:id="@+id/timer1"  
        android:layout_width="200dp"  
        android:layout_height="200dp"  
        android:padding="20dp"  
        app:backgroundColor="@color/colorGrey"  
        app:layout_constraintBottom_toBottomOf="parent"  
        app:layout_constraintEnd_toEndOf="parent"  
        app:layout_constraintStart_toStartOf="parent"  
        app:layout_constraintTop_toTopOf="parent"  
        app:primaryCapSize="30"  
        app:primaryCapVisibility="true"  
        app:progress="30"  
        app:progressColor="@color/colorStart"  
        app:secodaryCapSize="40"  
        app:secodaryCapVisibility="true"  
        app:secondaryProgress="70"  
        app:secondaryProgressColor="@color/colorCenter"  
        app:strokeWidth="10dp" />  
  ```
  ![Optional Text](../master/demo.png)
  
  Copyright 2018 Dev

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

