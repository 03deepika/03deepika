Firstly to run the project:
downloading:

You have to download and install the Arduino version from http://arduino.cc/. 
Instead, you may choose to download the Arduino version we provide on http://reprapworld.com/?software. 
This version includes the required components for Megatronics/Minitronics.
Extract the files file into a location of your choice.
On Windows you may need to install drivers for the electronics board before you can upload software.
The installation files are located under the /drivers subdir.
Linux and Mac should recognize the boards out-of-the-box.

You can simply run Arduino by executing the Arduino file.

secondly to upload the project:
uploading:
To upload a firmware, we must first open the files using File → Open.
Select the .ino file from the directory containing the firmware. 
Arduino will open several tabs with files.
Next step is to select the correct electronics board. 
From the Tools menu, locate the Board item. 
This item should include a few sub items, including Megatronics, Minitronics, Arduino mega 2560 (RAMPS with mega 2560) and Arduino Mega 1280
(RAMPS with mega1280).
Select the board that fits your electronics.
Also we need to select the serial port the electronics is connected to. 
In the Tools menu, locate the Serial port item. 
This should include at least one item if the board is connected and the drivers are installed properly. 
If there are multiple items here, you need to find out which is the correct one by unplugging the board and checking which port was removed.
Once you have set the board and serial port, you can upload the firmware by pressing File → Upload. 
Arduino will try to compile the firmware, if any errors occurthe process will stop and you will need to fix the errors before trying again.
Once compilation is complete, the actual upload will start. 
This may take a minute for a large sketch.
