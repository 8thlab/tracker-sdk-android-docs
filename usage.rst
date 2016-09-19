Usage
========

.. role:: java(code)
   :language: java

.. code-block:: java

	import android.support.v7.app.AppCompatActivity;
	import android.os.Bundle;

	import com.a8thlab.trackersdk.A8thLABSDK;

	public class TrackerSDKTest extends AppCompatActivity {

	    @Override
	    protected void onCreate(Bundle savedInstanceState) {
	        super.onCreate(savedInstanceState);
	        setContentView(R.layout.activity_tracker_sdktest);
	        String appId="APP_ID";
	        String appToken="APP_TOKEN";
	        A8thLABSDK.initializeSDK(getApplicationContext(), appId, appToken);
	    }
	}

In order to use library, execute static method :java:`initializeSDK` that is present in :java:`A8thLABSDK` class . Method accepts three parameters: application context, your unique application id provided by us, your unique application token provided by us. 

After that method execution apropriate threads and listeners are created, depending on android version and suported features. 