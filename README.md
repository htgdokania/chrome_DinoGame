# chrome_DinoGame T-Rex Run
This code is used to automate the game  which pops up when you have no internet in chrome, using an arduino and python
![image](https://user-images.githubusercontent.com/34301506/78688469-ed8c7980-7912-11ea-8259-b909b7de605e.png)

# 1. Arduino_code
First connect a LDR along with a resister(10K) in series across  +5v and Gnd
Next take a jumper from the junction of ldr and resister  and read it thorugh an analog pin
This value differs depending on the light conditions (We just need to differentiate between black and white).
Set the Range Accordingly.

# 2. Python Part
Once the arduino code decides when to jump it send a '1' to python via serial Communication.
Using pyautogui Library we simulate the spacebar key of the keyboard to make the dino jump .

In this way this code automates the game And makes it all look interesting .
