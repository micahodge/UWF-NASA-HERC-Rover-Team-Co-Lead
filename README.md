<h1>Team Co-Lead of UWF NASA HERC Rover Team</h1>

<h2>Description</h2>
Currently co-lead a team of 13 students at the University of West Florida's Rover team. The team's goal is to compete in the NASA HERC Rover Challenge in April 2027. We have been accepted into the RC-division, and we submitted our Design Review Paper on November 24, 2026. We have completed roughly 80% of the rover's design, including mechanical/hardware subsystems design, the power subsystem, and most of the electrical/electronic subsystems design. The team is currently completing final revisions to the rover's design to ensure maximum points are earned at the competition. I will co-lead this team until I start my Capstone project in Fall 2027. <br />
<br />
Currently, I am the lead engineer on the team, performing final component and design selection for most subsystems on the hardware, software, and electrical components on the rover. This includes co-creating and finalizing designs for the chassis components layout, the 4-wheel rocker suspension system, the wheel design, the drivetrain design, etc. For the design review, I provided design alternatives for each subsystem and performed analysis on certain subsystem, such as a power consumption analysis for the rover and the rover's electronic architecture. The team plans to attempt and complete every obstacle (including the task) on the course, which is not common amongst most competing teams. 
<br />


<h2>Tools Used</h2>

- <b>SolidWorks</b> 
- <b>Bambu Studio with Bambu Lab P2S</b>
- <b>5303 Series Saturn Planetary Gear Motor (260RPM)</b>
- <b>Raspberry Pi 5</b>
- <b>ESP32 (2x)</b>
- <b>Servo Motors (20kgcm)</b>
- <b>SolidWorks</b>
- <b>Carbon Fiber plates/tubes, PLA, PETG-CF, TPU-95A, turntable bearings </b> 

<h2>Environments Used </h2>

- <b>Ubuntu 24.04 LTS (hosted on Raspberry Pi 5)</b>
- <b>ROS2 Jazzy</b>

<h2>Challenged and Solutions</h2>

During the design review process, the team and I ran into some initial design issues, although some have been resolved. Firstly, per the competition rules, the rover will receive maximum points for one requirement if the entire rover weighs < 20 pounds. Currently, after full design of the rover, the estimated weight is around 20 pounds. The biggest contributors to this weight are the battery and all of the drivetrain motors, which weight 3.16 pounds and 4.77 pounds respectively. The main component that will change first will be the wheels. The wheels are large for this size of rover, but tall wheels are necessary do to needed clearance during some obstacles at the competition. If the wheels are able to shrink slightly, then drivetrain motors will smaller planetary gearboxes could be used instead of the current ones, which would bring the weight down a 1-2 pounds. <br />

Another component that can be shrunk if needed is the battery. Currently the battery holds a capacity of 10000mAh, and the rover only needs ≈ 6650mAh of capacity. This leaves a FoS of ≈ 1.51. While this excess was predicted to be used during frequent peak current spurts on the obstacles, we might shrink the battery to ≈8000-9000mAh to save roughly .5 pounds. 

Other adjustments are planned to be made to the design throughout December 2026-January 2027 as the team starts to prototype and fabricate the rover.

<h2>Photos:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
