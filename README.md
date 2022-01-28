# 4-bit Ripple Carry Adder
The design is implemented using 500nm technology.

## 1-bit Full Adder
<ul>
  <li>Full adder was implemented using Transmission Gate Logic for low power design.</li>
  <li>Less number of transistors are used for less chip area and less power dissipation.</li>
</ul>

### 1-bit full adder using simple cmos design
![image](https://user-images.githubusercontent.com/67308779/151490480-d9fcf09d-2750-4fa6-a010-8a4e806864c4.png)

### 1-bit full adder using transmission gate logic
![image](https://user-images.githubusercontent.com/67308779/151490544-bb3520d6-ad7f-4821-854b-24ad198e0022.png)

### Waveform for 1-bit full adder circuit
![image](https://user-images.githubusercontent.com/67308779/151490584-c21426f4-14d6-4cf1-9b48-64443e391eb4.png)

<p>
  <ul>
    <li>Power dissipation in simple cmos design = <b>772.09 uW.</b></li>
    <li>Power dissipation in transmission gate logic = <b>80.394 uW.</b></li>
  </ul>
</p>

## 4-bit Ripple Carry Adder
<ul>
  <li>The circuitry was extended from the full adder circuitry.</li>
  <li>In the worst case the power dissipation is <b>111.50 micro Watts</b> and propagation delay is <b>2.6 ns.</b></li>
</ul>

<br>

![image](https://user-images.githubusercontent.com/67308779/151491098-d49fca1b-7cc2-4bd8-9c76-7eee3f5bec25.png)
