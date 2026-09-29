---
title: "Aragog"
description: "Aragog is scary spider robot that will chase. Aspire from Harry Potter movie "
created_at: "2026-09-29"
---


## Hackatime link: https://hackatime.hackclub.com/@dushyantYadav0303/project/Aragog

--- 

# 2026-09-29          Planning 
## lapse Link:  https://lapse.hackclub.com/timelapse/i23Tx4Z6MR1Q
### Hi folks!!!!,
### if You are reading this then Definitely you're interested to see How I built this project. + I link all the Time lapse with link while working on this project. So you can see how i build this project. 
### let's get started!!!,
#### So I'm making a Scary hexapod Robot for Halloween which will chase you. when you get near by. 
#### And the name of the project "[Aragog](https://harrypotter.fandom.com/wiki/Aragog)" was inspired from [Harry Potter movie](https://en.wikipedia.org/wiki/Harry_Potter_and_the_Chamber_of_Secrets_(film)).
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/eeefd59e-bba7-460c-939d-b1a4a5f874fb" /> <br/>
<sub>*Source: [Monster Legacy](https://monsterlegacy.net/2017/02/11/aragog/)*</sub>
### So I created A short animation to show my idea And this is my first time making such an animation. 
<img width="470" height="470" alt="flipanim" src="https://github.com/user-attachments/assets/b90e20cc-89a9-4141-8388-be5491f6bb88" /> <br/>


## hexapod Hardware selection
### it is going to be the 6 legs hexapod as the name says "hexa".
<img width="202" height="234" alt="image" src="https://github.com/user-attachments/assets/b765a344-1ab6-47dc-9af5-d503303fa406" /> <br/>
<sub>*Source: [facebook](https://www.facebook.com/groups/entomemeology/posts/2128501734668433/)*</sub>

### every leg have 3 degree of freedom 
<img width="688" height="558" alt="image" src="https://github.com/user-attachments/assets/75d3d00c-d313-436e-81f2-9c84989a1546" /> <br/>
<sub>*Source: [researchgate](https://www.researchgate.net/figure/Conventional-leg-of-a-hexapod-robot-equipped-with-3-degrees-of-freedom-inspired-by-the_fig3_365654058)*</sub>
#### In total we need 3(dof) * 6(legs)  = 18 Actuator 
### Hardware selection
- we are using [TowerPro MG996R](https://robu.in/product/towerpro-mg996r-digital-high-torque-servo-motor/) It is Affordable and Good Torque.
- Esp32 S3 as a MCU 
- For connecting 18 servo to the ESP32 I'm going to use [16-Channel 12-bit PWM/Servo Driver](https://robu.in/product/16-channel-12-bit-pwmservo-driver-i2c-interface-pca9685-arduino-raspberry-pi/).
- 11.1v [LiPo batter](https://robu.in/product/orange-11-1v-1800mah-3s-30c-lipo-battery-pack-xt60-connector/) for power.
### For this project I'm building a custom PCB With all this component. 
  ### Alright so that's it for now. next we will proceed with Making Sch of PCB.
