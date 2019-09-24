## CustomMultipleProgressbar  

# Step 1. Add the JitPack repository to your build file   

allprojects {  
	  	repositories {  
			...  
		  	maven { url 'https://jitpack.io' }  
	 	}  
	 }    
   
 # Step 2. Add the dependency  
 	dependencies {
		implementation 'com.github.NaveenDevrani:customMultipleProgressbar:1.0'
	}  
  
## step 3 add in Xml 

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
  
  
  
  

