

# getting-started-docs

## Hololens Applications: Basic

### SET UP CAMERA 

* Under Hierarchy Tab

  * Click Camera 
  
    * Look under Inspector Tab
    
      * Under Transform
      
        * Change Position to  X:0 Y:0 Z:0
        
      * Under Camera Component
      
        * Find Clear Flags
        
          * Change to Solid Color
          
            * Change Color to RGB: 0,0,0 or Black
            
              * Find Clipping Plains
              
                * Change Near to 0.85
    
### CREATE 3D IMAGE 

Right click in Hierarchy
    Create any basic 3D Object
        Under Transform
            Change Position: X:0 Y:0 Z:8

### CHANGE QUALITY/PERFORMANCE SETTINGS

Click Edit ->  Go to Project Settings -> Click Quality

     Click arrow under Universal Windows Platform, (Windows Logo)
        Set to “Very Low”
        
Clike on File -> Build Settings -> Player Settings -> Navigate to XR Settings -> Make sure the Virtual Reality Supported box and the Vuforia Augmented Reality box are checked

Click on Window ->  Go to Vuforia Configuration
    Find Digital Eyewear 
Change Device Type to “Digital Eyewear” 
        Change Device Config to Hololens

### SAVE PROJECT

Click File -> Save Scene As.
    Create New Folder named “Scenes” under the Assets Folder (Should be the default folder)
    Name this scene “Main”

Click File -> Save Project

### CHANGE BUILD/PLAYER SETTINGS

Click File -> Build Settings 

Click “Player Settings” in the bottom left corner
        Scroll down to “Other Settings” 
            Under “Configuration” Change “Scripting Backend” to “.NET”
Under “Publisher Settings” Scroll to “Capabilities” and check:
Internet Client
Webcam
Microphone
Bluetooth
SpatialPerception

    Hit “Add Open Scenes”
    Go to Universal Windows Platform
        Under the settings that have appeared:
            Change Target Device to HoloLens
            Change Build Type to D3D
            Change SDK to Latest Installed
            Change Visual Studio Version to VS 2017
            Change Build and Run on to Local Machine
        
        Check “Unity C# Projects” Box
    
    Under “XR Settings” 
        Check both 
Virtual Reality Supported
Under Virtual Reality SDKS
Add Vuforia using the Plus sign in the bottom right
Vuforia Augmented Reality

### BUILDING THE PROJECT

Go Back to Build Settings, and hit Build.

Create a new File named “App” for the project.

When build is finished, find the .sln file under the “App” folder.

### RUNNING PROJECT WITH VISUAL STUDIO

Open that file with visual studio
In the toolbar for Visual Studio
    Select Debug from dropdown menu
    Select x86 from drop down menu next to that
    Select Device from Drop Down menu next to that one. 
    Click on the Green Arrow with the word Device



    
    


    

