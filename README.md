
# Driver-Ver1

<div align="center"; display="flex">
  <img src="https://github.com/Ngoc411/Driver-Ver1/blob/d39fc4d63df6450d3fb0aa3cb330c1f0cb55421f/Screenshot%202025-02-21%20080400.png" height="280">
  <img src="https://github.com/Ngoc411/Driver-Ver1/blob/d39fc4d63df6450d3fb0aa3cb330c1f0cb55421f/Screenshot%202025-02-21%20080443.png" height="280">
</div>

<div align="center" style="display: flex; margin-bottom: 16px;">
  <img src="https://github.com/Ngoc411/Driver-Ver1/blob/d39fc4d63df6450d3fb0aa3cb330c1f0cb55421f/Screenshot%202025-02-21%20080626.png" height="280">
  <img src="https://github.com/Ngoc411/Driver-Ver1/blob/d39fc4d63df6450d3fb0aa3cb330c1f0cb55421f/Screenshot%202025-02-21%20080639.png" height="280">
</div>

<p>
  Each PCB contain a magnetic driver to track the step of the step motors, each driver will be in charge of 1 motor. And in each PCB contains a STM32F103CBT6, this MCU has the role to receive command from the main board through UART and control the motors.
</p>

<div align="center" style="display: flex; margin-top: 16px;">
  <img src="https://github.com/Ngoc411/Driver-Ver1/blob/e4cdcee852b8e8da6571943189ff37abebfbcab2/Screenshot%202025-02-21%20080745.png" height="300">
  <img src="https://github.com/Ngoc411/Driver-Ver1/blob/e4cdcee852b8e8da6571943189ff37abebfbcab2/Screenshot%202025-02-21%20080313.png" height="300">
</div>

This the main board, including a STM32F407VGT6 to process entire trajectory of motors and send it to subborad through UART. There is also a ESP32 PICO responsible for peripheral connections includes wireless connection.
