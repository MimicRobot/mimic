# Change Log
latest changes for the [mimic app](mimicrobot.tk)
## v1.0.22
3/2/18
- [x] added "pick and place" recording type
- [x] can convert from one recording type to another
- [x] can replace a real time recording
- [x] update scrub UI when turning knob
- [x] improved "recorded servo" button
- [x] made trace line transparent and avoid hit detection
- [x] maintain lighting direction when rotating camera
- [x] bug fix: updating movements analysis should not stop playback
- [x] bug fix: safety doesn't respect jaw movement in scrub and target
- [x] bug fix: remove keyframes not working right
- [x] bug fix: firmware update 1.0.3: delay sometimes on synchronized movements
- [x] drag drop recordings order is maintained and folders sort to the top
- [x] scratch - can playback partial recordings
- [x] scratch - can to text-to-speech
- [x] scratch - can do voice recognition
- [x] Extend motors being on while parts are being moved through the computer
- [x] Knob moves to keyframes - not shuttling, like before

## v1.0.21
2/14/18
- [x] improved scrubbing support
- [x] Added Record & Playback module - for kids to play
- [x] ability to adjust real time recordings
- [x] more hot keys
- [x] live speed adjustments while playing

## v1.0.20
2/9/18
- [x] full touch screen support
- [x] backup and restore arm settings
- [x] easier rename of recordings - double-click
- [x] named keyframes
- [x] insert & copy key frames
- [x] remove keyframes for spesific servos
- [x] drag and drop keyframes between recordings
- [x] save and revert recording properly
- [x] bug fix: scrub to end, then press play was playing last .1 sec of recording
- [x] slice tool
- [x] add realistic simulator speed
- [x] bug fix: when 1 keyframe total complete is 1 (no slice tool)
- [x] bug fix: when normalizing recording time and play is pressed - exception
- [x] change position in sim while servos on
- [x] make update position more accurate
- [x] added reset arm button to connection panel
- [x] use knob to control recording a little more
- [x] code "automatic positioning" recording type
- [x] Added ability to use IK in recordings
- [x] real time recording while servos are on - watched a kid try this
- [x] improved trail rendering
- [x] hot-keys [delete, space, wasd]

## v1.0.19
1/26/18
- [x] start of the drawing module
- [x] edit tools for motion studio
- [x] scratch integration improvement

## v1.0.18
1/16/18
- [x] various caliberation bug fixes
- [x] recognize caliberation where caliberation finishes + caliberation still flashes
- [x] reset robot settings when robot settings module is used
- [x] 3D simulator doesn't show after launch when connected to real arm
- [x] bug fix [(issue)](../../issues/15)
- [x] bug fix [(issue)](../../issues/14)
- [x] bug fix [(issue)](../../issues/11)
- [x] bug fix [(issue)](../../issues/7)

## v1.0.17
11/3/17
- [x] bug fix [(issue)](../../issues/12)
- [x] added a simulator (click connection link from menu bar and press Launch Simulator button)
- [x] bug fix [(issue)](../../issues/1)
- [x] added scratch sample game in My Documents\Mimic\Scratch folder

## v1.0.16
10/27/17
- [x] added change log [(issue)](../../issues/8)
- [x] made version number easier to see **its in the upper right corner** [(issue)](../../issues/8)
- [x] calibration saves state and let you pickup where you left off - if you exit [(issue)](../../issues/5)
- [x] Handfull of caliberation bug fixes
- [ ] there are still some more caliration bugs I'll get to for next release

## v1.0.15
10/20/17
- [x] finished the testing & troubleshooting module [(issue)](../../issues/10)
- [x] fixed various bugs in firmware
- [x] saved state in hardware verification - so it picks up where you left off again
- [ ] still known work to be done to get caliberation working smoothly but should be better
* requires firmware v1.0.1
