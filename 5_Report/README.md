# WIPER CONTROL SYSTEM
## ABSTRACT:
A wiper speed control system for an automotive wiper controls the operational speed of a wiper in accordance with rain conditions. The control system includes a rain sensor detecting rain conditions to produce . an analog signal having an amplitude depending upon the detected rain conditions. The analog sensor signal is converted into a digital pulse signal by a converter for application to a digital circuit system. A control signal is produced by digitally processing the pulse signal. The control signal is applied to a wiper driver circuit to adjust the operational speed or timing in accordance with the control signal.

A wiper is a crucial part that eliminates precipitation or some other fluid from the windscreen of a vehicle. The past technique required manual wiper initiation, and raising the wiper was an extreme errand. Therefore, this framework is being introduced as an answer for these issues. The's task will likely stockpile cleaning frameworks for more established vehicles, work on the framework by utilizing actuators and pull switches (involving similar switch for different capacities by stepwise exchanging), and oversee motor and wiper speed with a solitary switch. This System manages the wiper's activity speed in light of how much downpour. This Wiper Speed Control System is used in a wide range of cars, and its essential capacity is to eliminate downpour air drops from the vehicle's front screen.
## INTRODUCTION:
These days, even non-luxury compact and family cars are available with rain-sensing wipers. These systems utilize an LED sensor, fitted between the windshield and rearview mirror, to detect the amount of rain or snow falling on the windshield.There are a number of infrared light-emitting diodes (LEDs) and a central photodiode which make up the “rain sense” portion of the system.The invisible light emitted by the LEDs is reflected by the windshield onto the photo sensor. Therefore the more moisture there is on the windshield, the less light the sensor receives. This information is subsequently relayed to a computer control unit, which then adjusts the intermittent wiper delay intervals of the accordingly.The wetter it gets, the faster the rain sensing wipers work to help give you a clear view of what's in front of you. When the system senses drier conditions, such as when the vehicle is stopped at a red light and the rain is falling less intensely, the wipers will gradually slow down before switching themselves off when no longer needed.

## Objectives:
The automated rain wiper system is used to detect rainfall and activate automobile rain wiper automatically without driver interaction. The system is developed to mitigate driving distractions and allow drivers to focus on their primary task of driving. The distraction eliminated with the development of this product is the manual adjustment of windshield wipers when driving in precipitation. The few seconds that a driver takes their attention off the road to adjust a knob while driving in poor weather conditions could potentially lead to car accidents.The system uses a combination of impedance and rain sensor to detect rain and its intensity. The system contains a controller that takes in the input signals from the sensors and controls the operation of the windshield wipers based on those input signals The aim of this project is to help reduce accidents that happen as a result of the driver intending to clean the windscreen when rain is falling thereby taking the attention of the driver off the road when he or she is switching on and off the wiper. In rainy days we suffer from the act of sprinkling of water on the front glass of our wheeler. While driving, when drivers cannot see visibly on-road vehicles they try operating the wiper on glass manually, at times switching on and off intermittently and this distraction might cause vehicle accident. If we apply any kind of sensor on glass which senses the act of sprinkling water, by automation, the wiper will be operating automatically. When the water hit the sensor, it will send a signal to the system thus triggering the wiper motor. Once the sensor does not detect any water, the wiper will stop. This will reduce the human interface that has been stated earlier. An addition to this invention is that the wiper automatically push up from the windscreen when the engine is shut off.

## DESCRIPTION:
Windshield wipers keep the windshield of a vehicle clear from rain water, snow, dust and road spray. The first windshield wipers were operated manually by moving a lever inside the car. Later wiper designs were powered by the engine's manifold vacuum. Virtually all wipers today employ an electric motor coupled with a linkage mechanism and are actuated by a knob beside the steering wheel. The wiper blade speed can be adjusted by the driver.

Modern windshield wipers may also be run intermittently. The intermittent wiper option cycles the wipers on and off every few seconds rather than running constantly. Intermittent control first appeared in automobiles in the 1970's. The original intermittent wipers were controlled by a constant power source that was routed through a series of switches. Now, virtually all automotive wipers are controlled by a microprocessor.

## STM32F407VG:
The STM32F407 Kit takes advantage of the high-performance STM32F407 microcontrollers' capabilities to make it simple for users to create audio-based applications. It comes with an ST-LINK embedded debug tool, an ST-MEMS digital accelerometer, a digital microphone, an audio DAC with integrated class D speaker driver, LEDs, pushbuttons, and a USB OTG micro-AB connector.Ethernet connectivity, an LCD display, and other features have been added to the STM32F4 DISCOVERY kit. The STM32F405xx and STM32F407xx families are built around the high-performance Arm® Cortex®-M4 32-bit RISC core, which runs at up to 168 MHz.

# WORKING PRINCIPLE:
Accept that the car is the microcontroller. Assuming the button is hit, the principal drove (red) will turn on, Clicking again the wiper will begin, and the subsequent drove (blue) will turn on for an ideal rate. Assuming the button is squeezed once more, the third driven (green) will turn on, and the wiper's speed will be expanded in contrast with the past one. The fourth press will turn on the fourth driven (orange), and the wiper speed will be expanded as per the past one. The microcontroller (vehicle) is switched off after the fifth snap.

## FEATURES OF STM32F407VG:
▪In a LQFP100 package, the STM32F407VGT6 microcontroller has a 32-bit ARM Cortex-M4 with FPU core, 1-Mbyte Flash memory, and 192-Kbyte RAM.

▪On-board ST-LINK/V2 or ST-LINK/V2-A on STM32F4 DISCOVERY (old reference) or STM32F407G-DISC1 (new order code)

▪USB ST-LINK with three separate interfaces and re-enumeration capability.

▪Virtual Com port Debug port (with new order code only)

▪Large-scale storage (with new order code only)

▪Board power is supplied through USB or an external 5 V supply source.

▪3 V and 5 V external application power supply

## SWOT ANALYSIS:
![168055063-47ab88cc-ac8f-4dbf-9985-a2b097a59848](https://user-images.githubusercontent.com/101501471/168239886-68d849b8-8fd7-4377-8a09-e9b989a5f89b.jpg)

## 5W's & 1H:
<img width="761" alt="5W   1H" src="https://user-images.githubusercontent.com/101501471/168241542-5f03bf50-3313-4637-a9b7-4593aa34e9f0.png">

## WHAT:
Controlling the car wipers

## WHY:
Easy switching of the controlling wipers and speed of wipers

## WHERE:
Wiper system on the car

## WHEN:
In tough environment conditions like rainy season and mansoon season

## WHO:
Easy for the driver to control the ON and OFF the motor and control wiper system by using one switch

## HOW:
When we on the wiper switch it gets activated

## HIGH LEVEL REQUIREMENTS:
| ID    | Discription                       | status      |
|-------|-----------------------------------|-------------|
| HR_01 | It Shall LOCK the car             | Implemented |
| HR_02 | It Shall UNLOCK the car           | Implemented |
| HR_03 | It Shall Activate Wiper System    | Implemented |
| HR_04 | It Shall Deactivate Wiper System. | Implemented |

## LOW LEVEL REQUIREMENTS:
| Test ID | Description                | Exp i/P                    | Exp O/P                    | Actual o/p                                                | Pass/Fail |
|---------|----------------------------|----------------------------|----------------------------|-----------------------------------------------------------|-----------|
| LL_01   | ON Engine Check Condition  | Pressed BUTTON ONCE        | ON All LED                 | ON All LED As Per ENCRYPTION                              | PASS      |
| LL_02   | OFF Engine Check Condition | Pressed BUTTON TWICE       | OFF All LED                | OFF All LED As Per ENCRYPTION                             | PASS      |
| LL_03   | ON Wiper Check Condition   | Pressed BUTTON THREE Times | ON LED Once ClockWise      | ON LED Once In ClockWise Direction As Per ENCRYPTION      | PASS      |
| LL_04   | OFF Wiper Check Condition  | Pressed BUTTON FOUR Times  | ON LED Once Anti ClockWise | ON LED Once In Anti ClockWise Direction As Per ENCRYPTION | PASS      |
# Exploring STM32F407 Discovery Board
The main purpose of this project is to get an insight into the STM32F407 Discovery Board, which is an ARM Cortex M4 based Microcontroller. As I started working on STM32F07 Discovery Board, initially it was difficult and confusing to understand and program this microcontroller because understanding internal structures and working of the microcontroller using datasheet of STM32F407VGT MCU is difficult especially if one is a beginner.

# Figure 1 : STM32F407 Discovery Board
![167889559-56e8ccad-7419-470f-80b9-ab31101be18c](https://user-images.githubusercontent.com/101501471/168267316-91665ecd-2c75-4768-9b0c-4c7e6d67547a.png)

# NVIC(Nested vectored interrupt controller)
Interrupts are a common feature supported by almost all microcontrollers. They are typically generated by hardware, for example peripherals or external input pins. When a peripheral or hardware needs service from the processor, this will lead to changes in program flow control outside the normal programmed sequence. Typically, the following sequences would occur:

1.The peripheral asserts an interrupt request to the processor.

2.The currently running task is suspended by the processor.

3.The processor executes an Interrupt Service Routine (ISR) to service the peripheral, and optionally the interrupt request is cleared by software if needed.

4.The processor resumes the previously suspended task. For every interrupt there must be a program associated with it. When an interrupt occurs, this program is executed to perform certain service for the interrupt. This program is usually named as Interrupt Service Routine (ISR) or interrupt handler.

![167892509-aed11f6b-5d49-48d7-8152-0cc503bbc96d](https://user-images.githubusercontent.com/101501471/168267283-7b1e8d7f-ac62-47e7-8b2a-e16430cc5e5e.png)

NVIC As the above figure shows every Cortex-M4 processor provides a Nested Vectored Interrupt Controller (NVIC) for interrupt handling. NVIC facilitates low-latency exception and interrupts handling, controls power management and implements System Control Registers. The NVIC and the processor core interface are closely coupled, which enables low latency to interrupt processing and efficient processing of late arriving interrupts.

For this microcontroller, the NVIC receives interrupt requests from various sources. In addition to interrupt requests, ther are some other events which need servicing. They are called “exceptions” (which are MCU internally generated). For Cortex-M4 processor, exceptions include resets, software interrupts and hardware interrupts. Each exception has an associated 32-bit vector that stores the memory location where the ISR that handles the exception is located. These vectors are stored in ROM at the beginning of memory. As explained earlier Vector table holds the location of ISR. The Cortex-M4 NVIC supports up to 240 interrupt requests (IRQs), a non-maskable interrupt (NMI), a SysTick timer interrupt and a number of system exceptions. Most of these IRQs are generated by peripherals such as timers, GPIO ports and communication interfaces such as UARTs.

# OUTPUT:
## ENGINE ON STATE:
![168270659-510526cf-8bf6-4916-afe9-c947d4dfa916](https://user-images.githubusercontent.com/101501471/168411853-885ccce3-7aad-48cc-914a-6dfd35d09729.png)

## ENGINE OFF STATE:
![168271807-83ca6e24-7ec2-4a6d-917b-81b59797b88d](https://user-images.githubusercontent.com/101501471/168411874-b8da3721-d3db-4454-9ba5-59281d2aabe4.png)

## WIPER SPEED IS LOW:
![168272110-ba6bdba7-3601-4577-b324-2eb865077862](https://user-images.githubusercontent.com/101501471/168411883-26a1906b-0f22-4afd-93c3-e77fb314b00f.png)

## WIPER SPEED ID MODERATE:
![168272380-5c7a8fdb-6ac8-4f0e-b39d-12fd36c119da](https://user-images.githubusercontent.com/101501471/168411898-d5adcca3-3503-460a-ba36-4b2d49f7fea6.png)

## WIPER SPEED IS HIGH:
![168272740-47d01034-eca2-412c-bf74-62f5edad61d9](https://user-images.githubusercontent.com/101501471/168411908-082d0a76-3106-4062-af74-884c0713ec26.png)

