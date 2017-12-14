# GPV-Wheel
This is a display for use at https://gamepadviewer.com/ Inside, you'll find a small group of displays for PC wheels and accesories. Due to the varied complexity and multiple axis' of some of these devices, they may be split into several displays to be reassembled into a program such as OBS. In each section you will find the settings that should be applied, what needs to be remapped for the display to appear correctly, and the url of the custom css for quick access.

# Quick How-to
For any of the following displays: Remap the device's input to the coresponding controller input, apply any settings, and apply the custom css. Take the resulting url and past it into a browser source in OBS or another program of choice. If the inputs are not acting appropriately, you must ensure that in OBS all designated to the same player by scrolling to the beginning of the address and finding `?p=1`

# Wheel.css
This is for the wheel axis and either paddle.  

Settings:  
  Strength Meter: Enabled  
  
Remapping:  
  Wheel left: Left trigger  
  Wheel right: Right trigger  
  Paddle left: Select  
  Paddle right: Start  
  
Custom CSS URL:  
  https://raw.githubusercontent.com/ElderCub/GPV-Wheel/master/wheel.css
  
# ThrottleBrake.css
This is just for the throttle and brake pedal.

Settings:   
  Strength Meter: Enabled  
  
Remapping:  
  Brake pedal: Left trigger  
  Accelerator: Right trigger  
  
Custom CSS URL:  
  https://raw.githubusercontent.com/ElderCub/GPV-Wheel/master/throttlebrake.css
  
# Clutch.css
If you don't have a third petal this is unneccesary.  

Settings:   
  Strength Meter: Enabled  
  
Remapping:  
  Clutch pedal: Left trigger  
  
Custom CSS URL:  
  https://raw.githubusercontent.com/ElderCub/GPV-Wheel/master/clutch.css
  
These three entries above are all for the same device, ensure that in OBS all designated to the same player by scrolling to the beginning of the address and finding `?p=1`
  
# eBrake.css
This is the only meter that fills from the top down. This offers the appearance of "pulling" rather than pushing a pedal, if requested I can make a version going from the bottom up.

Settings:   
  Strength Meter: Enabled  
  
Remapping:  
  eBrake axis: Right trigger
  
Custom CSS URL:  
  https://raw.githubusercontent.com/ElderCub/GPV-Wheel/master/ebrake.css
  
# Shifter.css
This is a host of buttons for shifters 1-6 + R. 

Remapping:  
  1st Gear: Select  
  2nd Gear: Start  
  3rd Gear: X / Square  
  4th Gear: Y / Triangle  
  5th Gear: A / Cross  
  6th Gear: B / Circle  
  Reverse:  Right stick click / R3  
  
Custom CSS URL:  
  https://raw.githubusercontent.com/ElderCub/GPV-Wheel/master/shifter.css
  
# TODO
In the future I intend to combine wheel.css, throttlebrake.css, and clutch.css. It was built this way, currently, due to my lack of knowledge on the css language.  

I will also be adding a graphic for the additional buttons of the G29 as well as any other wheels that may be requested. Requests for shifters with a 7th gear, or additional buttons such as the G25 or G27 will also be welcome.  

I intend to build these graphics in a modular fashion so any configuration of devices would fit together.
