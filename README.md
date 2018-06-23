# Radiofaro
Use [radiofaro.de](http://radiofaro.de) for more information.
<br>
This repository is just my private bugtracker. 
<br><br><br>
### PWM channel
- Rasenroboter (RadioFaro+MotorShieldR3) = 3,7->11(wire jumper at connector)
- Rasenroboter (RadioFaro+VNH5019MotorShield) = 9,3->10(wire jumper at connector)
- GartenbahnLok1K (RadioFaro+MotorShieldR3) = 3(PIN_PWMA)
- Used Boards
   - Radiofaro = 2, 3, 7, 8, 9
      - 2 @ TIMER3B
      - 3 @ TIMER3C
      - 7 @ TIMER3A
      - 8 @ TIMER2A
      - 9 @ TIMER1A
      - %USER%\AppData\Local\Arduino15\packages\uracoli\hardware\avr\0.5.2\variants\radiofaro\pins_arduino.h
   - Arduino Motor Shield R3 = 3(PWMA), 11(PWMB)
   - Pololu Dual VNH5019 Motor Driver Shield = 9(M1PWM), 10(M2PWM)
   - Arduino Uno = 3,5,6,9,10,11

### millis() & micros()
- TIMER0_OVF_vect interrupt of TIMER0
- %USER%\AppData\Local\Arduino15\packages\uracoli\hardware\avr\0.5.2\cores\uracoli\wiring.c
