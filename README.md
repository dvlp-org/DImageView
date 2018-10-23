# DImageView

[![](https://jitpack.io/v/dvlp-org/DImageView.svg)](https://jitpack.io/#dvlp-org/DImageView)

Configuration

 Step 1.Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  Step 2. Add the dependency
  
  	dependencies {
	        implementation 'com.github.dvlp-org:DImageView:Tag'
	}
  
   Step 3. Add layout xml
   
    <news.dvlp.dview.CircleImageView
        android:layout_margin="5dp"
        android:layout_width="150dp"
        android:layout_height="150dp"
        app:border_color="#000000"
        app:border_width="2dp"
        android:src="@color/###"/>

    <news.dvlp.dview.RoundImageView
        android:layout_margin="5dp"

        android:layout_width="150dp"
        android:layout_height="150dp"
        app:type="circle"
        android:src="@color/###"/>

--------------------------------------------attrs------------------------------------------------------------

     <declare-styleable name="RoundImageView">
        <attr name="type" format="enum">
            <enum name="circle" value="1"/>
            <enum name="round" value="2"/>
        </attr>
        <attr name="radius" format="dimension"/>
    </declare-styleable>

    <declare-styleable name="CircleImageView">
        <attr name="border_width" format="dimension" />
        <attr name="border_color" format="color" />
    </declare-styleable>
--------------------------------------------attrs------------------------------------------------------------        
        
