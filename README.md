# BLCD-Controller
BLCD Controller developed as the final project of the course **_Electrónica de Potencia_** at **_UTN FRBA_**.
<p>
</p>
Watch it working 

[![BLCD](https://img.youtube.com/vi/RzlKXHOah-g/0.jpg)](https://www.youtube.com/watch?v=RzlKXHOah-g)


## Tools 🛠️
This project was implemented with
- IDE : S32DS
- No SDK used, every code was written baremetal
- PCB on Altium Designer

## Features 🚀
- Trapezoidal control
- Unipolar PWM control
- Complementary PWM switching
- UI for reading engine's RPM
- RPM's value settable with potentiometer 

## Measurement 📐

Every images from oscilloscope follow the same color logic associated to phase or hall input.
<p>
</p>

$${\color{yellow}Phase/Hall A} 
{\color{cyan}Phase/Hall B}
{\color{orange}Phase/Hall C}
{\color{green}Internal signal generated after a hall sequence}$$


Internal signal should be used as debugging because of engine had 31 poles, so with that signal was easier to understand the sequence.

### eRPM
![eRPM](https://github.com/TobiasBp99/BLCD-Controller/blob/master/images/eRpm.png)
<p>
</p>
This image shows the hall sequence.

### Trapezoidal shape
![shape](https://github.com/TobiasBp99/BLCD-Controller/blob/master/images/trapezoidal.png)
This image voltage seen in each engine's phase.

## Assembly 💡
![top](https://github.com/TobiasBp99/BLCD-Controller/blob/master/images/topLayer.png)
![bottom](https://github.com/TobiasBp99/BLCD-Controller/blob/master/images/bottomLayer.png)

PCB assembly was made by myself too.

## UI 💡
![ui](https://github.com/TobiasBp99/BLCD-Controller/blob/master/images/ui.png)