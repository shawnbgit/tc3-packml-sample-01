# tc3-packml-sample-01
PackML sample utilizing Tc3_PackML_V2 lib &amp; OMAC implementation guide

Developed in Tc3 Build 4024.32


Production Line = Master (no PackML Modes or States, only giving PackTag commands to the Units)

Unit 1 is a Robotic Delta Cell = (PackML Modes, States & PackTags) 
•	SubUnit 1 is the infeed conveyor (PackML States)
•	SubUnit 2 is the delta robot (PackML States)
•	SubUnit 3 is the discharge conveyor (PackML States)

Unit 2 is a Robotic SCARA Cell = (PackML Modes, States & PackTags)
•	SubUnit 1 is the infeed conveyor (PackML States)
•	SubUnit 2 is the scara robot (PackML States)
•	SubUnit 3 is the discharge conveyor (PackML States)

There’s a simple visu to walk through the modes & states of the main units/sub-units. 
