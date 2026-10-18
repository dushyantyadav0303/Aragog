---
title: "Aragog"
description: "Aragog is scary spider robot that will chase. Aspire from Harry Potter movie "
created_at: "2026-09-29"
---

<img width="1015" height="680" alt="image" src="https://github.com/user-attachments/assets/13d99956-3f43-47f4-8b7b-ed0ef74374d1" />


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

---

# 2026-10-07          making Schematic
## lapse: https://lapse.hackclub.com/timelapse/IrNZ7qAwwCne
#### so i am start designing Schematic and i first selected the MCU and I'm using Espressif ESP-WROOM-32 and added the Programming circuit to programme it and 
#### next i added servo driver and other things
#### And was everything is done i polish it By adding labels.
#### here you see the Schematic
<img width="1061" height="551" alt="image" src="https://github.com/user-attachments/assets/59f0b04f-df51-4698-a37d-c1b4078b3b02" />


---

# 2026-10-10          Routing PCB
## lapse: https://lapse.hackclub.com/timelapse/8rM_ZCm9HDkg
#### Yooo today, i Start Routing the PCB but wait before then i Assign the footprint to all the component.
<img width="921" height="606" alt="image" src="https://github.com/user-attachments/assets/4eb4373c-08cf-46e6-aba3-6ca569382cbb" /> <br>
#### Layout the component: means arrange all the Component on PCB and it good placement really matter cause.
#### Then i start  Routing the PCB and Split the Copper pour into 2 net: 3v3 and 5v 
<img width="606" height="544" alt="image" src="https://github.com/user-attachments/assets/92b742a0-443a-4a21-92b2-9840e572b81c" /> <br>
#### here are the final routing 

| TOP | Bottom |
| :---: | :---: |
| ![Image 1](https://github.com/user-attachments/assets/1c150960-e173-4809-a108-28410e300bd7) | ![Image 2](https://github.com/user-attachments/assets/73616033-38e0-4415-8ee0-fa9541a6b6bb) |

#### at last i added the Halloween theame Silkscreen on top and spider logo expose copper (solder mask).
#### which really looks so sick!!!!!!!!!!!!


| TOP | Bottom |
| :---: | :---: |
| ![Image 1](https://github.com/user-attachments/assets/acdcddf8-3f5d-47ed-957c-84b2bd8a7eaf) | ![Image 2](https://github.com/user-attachments/assets/a20d4083-8f29-4fad-83f8-92aaa305bfe5) |


#### ahhh!!! at the last min I remember to add mount holes.
#### so i added 2x **M3** for mount the PCB on 3D printed spider model 
<img width="657" height="514" alt="image" src="https://github.com/user-attachments/assets/12a25d5e-4c78-4a1f-953d-34716012bdc0" /> <br>




# 2026-10-18      Cad model 
## lapse: https://lapse.hackclub.com/timelapse/leC36OzeO9i9
### So today, I completed the Aragog cad model in fusion 360 and here you see the Final Cad model.
<img width="1280" height="1024" alt="Aragog" src="https://github.com/user-attachments/assets/cd3d8c6c-ddb8-49c2-ae04-1375fbfb77d1" /> <br>
<img width="1202" height="620" alt="image" src="https://github.com/user-attachments/assets/cd4d90e0-dcd6-422b-9f37-b45d840b79cb" /> 
