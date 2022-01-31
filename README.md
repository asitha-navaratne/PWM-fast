# PWM-fast

<p align="justify">PWM or Pulse Width Modulation is the controlling of the average power delivered by an electrical signal to a load by transmitting the signal as a series of 
square-wave pulses as opposed to a signal of fixed voltage value. Through this method a digital power source, such as the pins of a microcontroller, which can usually only output 
either 0 or 5 V can be used to generate any analog voltage values between 0 and VCC. PWM is most commonly used to control the speed of motors and can be used for other 
applications where analog voltages are required, such as controlling the brightness of an LED.</p>

<p align="justify">A PWM signal generated by the microcontroller is a square-wave signal with a peak voltage of VCC. For one cycle, the time period where the signal is at VCC or 
HIGH is called the "On" time while the time period the signal is at 0 V is called the "Off" time. The ratio of the "On" time to the total time of the PWM signal (the total time 
being the sum of the On time and Off time) is called the Duty Cycle of the PWM signal. By controlling the duty cycle of the signal the average voltage of the PWM signal can be 
controlled thus providing an analog output from a digital source.</p>