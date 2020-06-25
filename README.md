# Android-Application-via-BCI
Try to think about controlling lights, airconditionner or TV. The application will classify your command in minds and show it in the android application. 


"Algo_SDK_Sample" is a project to demonstrate how to classify your thoughts(open the lights TV and air-conditioner) through Mobile Headset (realtime mode) or canned data (offline mode).


In the app,
	1. connect the headset to the app by tapping "Headset” button
	2. start the app until the signal status is good.
	3. tap "Start“ to start process any incoming headset data (by invoking "NskAlgoStart()" method)
	4. tap "Pause" to pause EEG Algo SDK (by invoking “NskAlgoPause()” method)
	5. tap "Stop" to stop EEG Algo SDK (by invoking "NskAlgoStop()" method)
	6. blink to invoke message and the corresponding items will be changed

