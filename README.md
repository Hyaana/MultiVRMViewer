#-- Hyaana's MultiVRM Viewer --
Hyaana Discord :: HyaanaMoon#9640

If something breaks or a red error shows up:
	- Go to AppData\LocalLow\Hyaana\VRMTestImport1 and get "Player.log"
	- Tell Hyaana what broke and the steps to break it
	- Send Hyaana the log 

###Loading VRM :
 - Click button labelled "Select VRM Model"
 - Select your .vrm file from file explorer
 - Click button labelled "Upload VRM" to upload file to server
 	- Only need to do this once, if you have already uploaded your model you can skip this step!
 - If a room does not exist yet, click button labelled "Create Room"
 - If a room does exist and you wish to join that room click button labelled "Join Room"
	- (Plan to add a room finder in the future)

###After Create/Join:
 - Wait for your model to load in
 - Wait for everyone elses model to load in
 	- This might freeze while it downloads other models / loads your own model

###Controls:
	####VRM Movement:
	- A/D for left/right movement
	- W/S for up/down movement
	- Q/E for height adjustment
	
	####Misc Controls:
	- TAB for UI enable/disable
	- M for microphone selector

	####Edit Model:
	- Click checkboxes to toggle clothing on model
	- This will only work on certain VRM models
		- Spefically models created where they were seperated by material before export

###Body Tracking:		[NOT ENABLED ON CURRENT BUILD]
###NOTE : 	Tracking is very primitive and doesn't work really well.
	All face tracking API cost > $50 with added costs for IK for smooth VRM motion, and I don't want to spend that on a pet project.

- Click button labelled "Calibrate Tracking" to enter calibration
- Hover over middle of your face and press R to calibrate
	- Forehead or cheek works best
	- Decent lighting (but not too much) needed
- Click button labelled "Calibrate Tracking" to exit calibration
	
	####Debug Mode:
	WARNING :: This modewill slow down the program significantly.
	- Toggle "Tracking Debug"
	- Click button labelled "Calibrate Tracking" to enter calibration
		- Webcam image will be white/black
	- Press R to calibrate in a black area
	- Tracked center will be represented by red/green lines
