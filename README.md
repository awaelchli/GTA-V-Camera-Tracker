# Camera Tracker for Grand Theft Auto V
## Installation
  1. Download and install the modding tool [ScriptHookV](http://www.dev-c.com/gtav/scripthookv/) as described their the readme file.
  2. Open the file `src/CamTracker.sln` in Visual Studio 2013 and build the project.
  3. Copy the file `CamTracker.asi` from the folder `bin/Release` to the installation folder of Grand Theft Auto V. 
  
## Usage
The mod only works in story mode.

Key | Description
--- | ----------- |
__F5__ | Open/Close the plugin
__F9__ | Start/Stop recording of camera motion
__NUM 2/8/4/6__	| Navigate through the menus and lists (Num-Lock must be on)
__NUM5__ | Select
__NUM0/BACKSPACE/F5__ | Back

With each recording, the program creates a text file in the installation folder of GTA V.
Each row contains the following information:

Index | Time | X Y Z | Pitch Roll Yaw |
----- | ---- | ----- | -------------- |
Row number | Timestamp of the recording in milliseconds since the beginning of the clip | Location of the camera in world coordinate frame | Pitch, roll and yaw angles in degrees |
