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

- ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) `#f03c15`
- ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) `#c5f015`
- ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) `#1589F0`

$${\color{yellow}Phase/Hall A} \break
{\color{cyan}Phase/Hall B} \enter
{\color{orange}Phase/Hall C} \enter
{\color{green}Internal \space signal \space generated \space after \space a \space hall \space sequence}$$


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