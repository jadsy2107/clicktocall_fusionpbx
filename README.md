# ClickToCall_FusionPBX
Real click to call functionality forked from https://github.com/blackc2004/fusionpbx-clicktocall

Firstly copy ClickToCall into anywhere on your local disk, C:\ClickToCall is where i keep it for now, 

Secondly to add this portable program as a Default App in Windows 7/10/11 - copy the PortableRegistrator into C: also. 

Run the PortableRegistrator.exe, register the ClickToCall.exe (whereever you saved it), Choose Telephone-App and click register.

Now go to Windows Settings, Default Apps, change tel and callto URL to use ClickToCall as default.


Voila - any tel: or callto: links will now open in your new ClickToCall.exe - make your you run ClickToCall.exe before making any calls
and setup Extension, Domain, API Key (all from FusionPBX) 

In the URL feild just put domain.com not https://domain.com - it will automatically and ONLY support https installations.

Finally if you don't like Google Chrome adding an extra click, confirming to use the app to call, install the Registry Key ClickToCall.reg




