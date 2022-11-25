## Stepper-Motor-Driver-using-RL78
---

This application note shows how to implement a controller for a stepper motor using the RL78 Hardware 16-Bit Single-Chip Microcontrollers (MCUs) along with a simple analog Drive circuit. Nowadays, stepper motors are used in a wide variety of applications. They are prevalent in consumer office equipment such as printers, scanners, copiers and plotters. They also play an important role in the industry, use in robotics or dashboard indicators, climate control systems in the automotive industry.

Purpose of this application note is to show how a stepper motor control is realised on the RL78/G13
with as few external parts as possible. The software and hardware configuration published here is
just a academic project (EL9630/NEA630 - Microprocessors) and are not intend for mass production.

### Stepper Motor Basics
---

A step motor is an electromagnetic, rotary actuator, which mechanically converts digital pulse inputs to
incremental shaft rotation. The rotation has not only a direct relation to the number of input pulses, but
its speed is related to the frequency of the pulses. 

#### Hybrid Stepper Motor
---

![Hybrid Stepper Motor.png](attachment:844c8fd3-502c-4a65-8eba-cd00f272740f.png)

The drive topology of stepper motors is also an important criterion for choosing a motor.
Here are two main topologies to mention, unipolar and bipolar driving. Unipolar stepping motors are composed of two windings, each with a center tap. The center taps are either brought outside the motor as two separate wires or connected to each other internally and brought outside the motor as one wire. As a result, unipolar motors have 5 or 6 wires. Regardless of the
number of wires, unipolar motors are driven in the same way. The center tap wire(s) is tied to a power supply and the ends of the coils are alternately grounded.


```python

```
