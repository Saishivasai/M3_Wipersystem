## FEATURES
* Wiper is powered on when button long pressed once.
* Wiper starts moving slowly when button pressed once.
* Wiper starts moving with medium speed when button pressed twice.
* Wiper starts moving with high speed when button pressed thrice.
* Wiper stops moving when button pressed for fourth time.
* The pattern continues from next press.
* Wiper is powered off when button long pressed again.
## 5W's 1H
|WHY|WHEN|WHAT|WHERE|WHO|HOW|
|:--:|:--:|:--:|:--:|:--:|:--:|
|To make wiper system more efficient and avoid disadvantage of old wiper system.|At times of Rain.|Mechanism to enhance wiper system.|Car.|Whoever drives car.|With MCU and push buttons.
## SWOT
|STRENGTH|WEAKNESS|OPPERTUNITY|THREATS|
|:--:|:--:|:--:|:--:|
|Avoid disadvantage od old wiper system.|It doesnt work automatically.|Can be automated with sensor data.|Might malfunction due to rain water and take more time to respond

## High Level Requirements
| ID | High Level Requirements |
| -------- | -------------- |
| HLR1 | It Powers ON Wiper control system|
| HLR2 | It Powers OFF Wiper control system |
| HLR3 | It moves wiper arm at different speed|
| HLR4 | It Brings wiper arm to 0 degree angle when wiper is powered OFF|

## Low Level Requirements
| ID | Low Level Requirements for HLR1|
|:--:|:--:|
| LLR 1.1 | If button is pressed and held it Power ON Red LED|

| ID | Low Level Requirements for HLR2|
|:--:|:--:|
| LLR 2.1 | If button is pressed and held it when Wiper is already powered Power OFF Red LED|

| ID | Low Level Requirements for HLR3|
|:--:|:--:|
| LLR 3.1 | Glows Blue, Green and Orange LED alternatively with slow speed in clockwise manner when  pressed Once|
| LLR 3.2 | Glows Blue, Green and Orange LED alternatively with medium speed in clockwise manner when  pressed twice|
| LLR 3.2 | Glows Blue, Green and Orange LED alternatively with high speed in clockwise manner when  pressed thrice|
| LLR 3.2 | LED glow pattern stops on the 4th press and the wiper action starts on next press from slow speed|

| ID | Low Level Requirements for HLR4|
|:--:|:--:|
| LLR 4.1 | When it is powered OFF Blue LED must Glow Finally |
