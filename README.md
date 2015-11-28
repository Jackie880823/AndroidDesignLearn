# AndroidDesignLearn
一个对[Material design](http://www.google.com/design/spec/material-design/introduction.html)支持的Android Design Support Library的Demo.

<image name="navigation_view" src="./images/navigation-view.png"  width="300px"/>

布局如下：
	

    <android.support.v4.widget.DrawerLayout 
        xmlns:android="http://schemas.android.com/apk/res/android"
        xmlns:app="http://schemas.android.com/apk/res-auto"
    	android:id="@+id/drawer_layout"
    	android:layout_width="match_parent"
    	android:layout_height="match_parent"
    	android:fitsSystemWindows="true">
    	
    		<android.support.design.widget.NavigationView
        		android:id="@+id/navigation"
        		android:layout_width="wrap_content"
        		android:layout_height="match_parent"
        		android:layout_gravity="start"
        		app:headerLayout="@layout/nv_header_layout"
        		app:menu="@menu/nv_menu" />
        		
	</android.support.v4.widget.DrawerLayout>	
	
