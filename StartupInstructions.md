

# Setup Instructions

1. Navigate to portal.azure.com and sign in with your portal credentials
1. Click on the Create a resource button as shown in the image  

   ![Calabash Logo](/images/startup-1.png)

1. Type calabash into the search window and hit enter
	
	![Calabash Logo](images/startup-2.png)

1. You should see calabash presented.  Click ```create``` and select ```developer```	
	
	![Calabash Logo](images/startup-4.png)

1. Next enter the setting for the Calanash VM.  You should specify the network, storage, and vm size you want.  __NOTE__:  _There will be some things that you normally configure that you cant when using Calabash so dont be alarmed_. __Do not change the VM image__ 

	![Calabash Logo](images/startup-5.png)

1. Once you have everything setup the way you want, click create to deploy Calabash!

1. Once the deployment has completed click ```Go to resource``` to start using your image.

	![Calabash Logo](images/startup-7.png)

1. A Calabash setup looks like any other VM on the surface, but the software configured on it is what matters.  You can access it using RDP if you configured it with a public IP or use a bastion host to connect.
1. Once you sign in, go through the standard windows server setup steps.  Windows should land you on the windows server manager page.
1. Open edge and navigate to localhost.  You should now see the Calabsh setup page where you can create a root profile.  Enter the information for the root profile and hit ```Create Profile```

	![Calabash Logo](images/startup-9.png)

1. This should take you to the Calabash landing page. Enter the credentials you created here to sign in.
That's it!  Your in and ready to start using Calabash.
	
	![Calabash Logo](images/startup-11.png)
