# PocketVJ Exhibition / Control Panel 3.x.x

## CP 3.1.2 27.September 2020<br />
- fixed scaling of mapper logo  <p/>
- added play dmxshow01 with audio01 (show01 to show05)  <p/>
- added a delay window to be able to sync manually dmxshow to video&audio  <p/>
- updated the dmxvideo scripts to the new style with delay syncing <p/>
- added USB output to dmxaudio/dmxvideo  <p/>
- added dmx to autostart <p/>
- added blackout dmx to stop button, so all lamps go to black when hitting stop <p/>
- added dmxaudio/dmxvideo to OSC commands  <p/>
- added dmxaudio/dmxvideo to UDP commands  <p/>
- fixed a wrong .js linke which caused CP to be unselectable <p/>

## CP 3.1.1 20.August 2020<br />
- removed softedge button under mapper, since there is already an "Edge Blend" button  <p/>
- added to Renthal Reset: disable scheduler, recreate full folder structure  <p/>

## CP 3.1.0 14.August 2020<br />
- added new mapper with more performance  <p/>
- added fullscreen function for mapper  <p/>
- added edgeblend function for mapper  <p/>
- added renthal reset (older versions than 4.0.6 need to copy 01_Testfile_HD.mp4 to /home/pvj/content/)  <p/>

## Image 4.0.6 14.August 2020 <br />
- copied standard files to /home/pvj/content/ for renthal preset function  <p/>

## CP 3.0.9 18.July 2020 <br />
- added UDP listener (users before Image 4.0.5 need to install socat) <p/>

## CP 3.0.8a 18.July 2020 <br />
- fixed an issue whit a .js script which was linked to an online version, caused that "tabs" on CP where not working <p/>

## Image 4.0.5 18. July 2020 <br />
- added socat for UDP listener (previous clients can install this manually with: apt-get install socat) <p/>

## CP 3.0.8 30.March 2020 <br />
- added artnet/dmx remote control <p/>

## CP 3.0.7 19.March 2020 <br />
- added maperremote button<p/>
- added kenburns slideshow (beta)<p/>

## Image 4.0.4 19.March 2020 <br />
- added pi3d library for kenburns slideshow<p/>
- added python-pil which is needed by pi3d<p/>

## CP 3.0.6 10.March 2020 <br />
- fixed "Scheduler Off", did not clean out scheduler before<p/>
- fixed user rights of videos triggered from scheduler<p/>

## CP 3.0.5 08.March 2020 <br />
- fixed function to test to conenct to a wifi network<p/>
- after updating make, click "Factory Rreset" in the red tab to apply changes systemwide!<p/>
- when no clicking on "Connect/Test" it will automatically set remote access on and protects CP with a login <p/>
- added function to look which wifi networks are available<p/>
- added function to check to which wifi you are connected<p/>

## Image 4.0.3 08.March 2020 <br />
- implemented RTC fix and remote wifi fix<p/>

## CP 3.0.4 05.March 2020 <br />
- fixed formatting of timer.txt file (browser writes hidden ^M$
 instead of $ only)<p/>
- added function to ask if projector is on or off<p/>
- added button to set audio volume of USB soundcard to 100% and store this value<p/>

## Image 4.0.2 04.March 2020 <br />
- added library for DHT11 sensor (Adafruit_Python_DHT)<p/>
- fixe audio volume for USB soundcard to standard 100% <p/>

## CP 3.0.3 04.March 2020 <br />
- fixed the pause function in headers shortcuts<p/>
- fixed hwclock issue (time was not saved), [see here](https://github.com/magdesign/PocketVJ-CP-exh/issues/1)<p/>
- added setting for an external temperature sensor<p/>

## CP 3.0.2 02.March 2020 <br />
- added dmx commands to scheduler<p/>
- added force resolution to 1920x1200<p/>
- added remotemapper (beta)<p/>
- fixed a typo in "update everything" function, users with CP 3.0.1 or older must update with [this](https://vimeo.com/308801484) method<p/>

## Image 4.0.1 March 2020 <br />
- added ofxJSON<p/>
- added remote mapper (also containng in CP update)<p/>

## CP 3.0.1 16.December 2019 <br />
- Updated midicontrol.cfg with commands to start/record dmx show 01-40<p/>
- Added scripts to play/record dmx show 01-40<p/>
- Added OSC control commands for dmx 01-05 play/record/play with video and enable/disable midi control<p/>

## CP 3.0.0 19.October 2019 <br />
- Main release<br />
- PVJ Exhibition Image 4.0 <br />


