# INTRODUCTION
Windscreen wiper is a device that cleans water,snow or mud from the windscreen of vechile.Thus it ensures proper visibility of the road ahed.
This system finds application on a large variety of locomotives from vehicles, railways to aero-planes Generally, the term Windscreen wiper
refers to the wipers installed on the front windshield of a vehicle However, nowadays, rear wipers are also getting popular. Almost all the 
modern wiper mechanisms employ an electric motor for their operation. However, in some cases, pneumatic drives are also used to drive wide
arm. Some of the primitive designs of the wiper mechanism were hand operated Wiper motor drives the linkages of wiper mechanisms which
ultimately makes the wiper blade to move on the windscreen.

In this project we show the output in led form where according to the speed blue red orange green leds can be shown as the output of this
operation
## WORKING

Linkage Linkage performs two major functions Firstly, it holds the wiper arm and blade in position and maintains proper contact between
the blade and the windscreen. Secondly, it converts the rotary motion obtained from the motor into suitable form And to do this, it employs a
worm gear, Worm gear reduces the speed of output shaft of motor and converts it into suitable to que required to operate wiper arm

Wipelarm: Wiper arm is the connecting link between wiper linkage and wiper blade
When the wiper switch is in the off position, the wiper will not function. When the wiper switch is in low-speed mode, the wiper will work at low 
speed. Accordingly, when the wiper switch is in high-speed mode, the wiper will work at a fairly high speed.
Now that you hopefully understand how the car wiper works, along with its components and detail functions, you should take care of it as well
as possible and be diligent in cleaning it!
Wiper blade Blade is a rubber part that comes in contact with glass It also has a metal clamping attached to it which aids in maintaining
uniform pressure on the blade. Here we are going to show the wiper control system in microcontroller.
### WORKING PROCESS
- When the button is pressed ONCE, the car will be on ACC mode.

- When the button is pressed TWICE, the car will be on Ignition mode.

- When the button is pressed THREE times, wiper turn on.

- When the button is pressed FOUR times, wiper turn off.
## IMPORTANT OF WIPER SYSTEM IN CAR
1)For saftey on the road windshiled glass is the most critical part
2)But when it comes to the varying weather conditions,windshiled wipers are considerd to be the saviour.
3)In cities like Delhi and Chennai,which witnesses heavy rainfalls,windshiled wipers are highly essential.
4)Almost all motor vehicles,including cars,trucks,etc.are equipped with wipers and are very important for clear vision.
5)During the rainy season,water droplets on the windshiled continuously distrub the visiblity of the the drive that can lead to major accidents.
# REQUIREMENTS FOR THE PROJECTS ARE :
### STM32Cube IDE :
- STM32Cube software ecosystem. STM32CubeIDE is an advanced C/C++ development platform with peripheral configuration, code generation, code compilation, and debug features for STM32 microcontrollers and microprocessors. It is based on the Eclipse®/CDT™ framework and GCC toolchain for the development, and GDB for the debugging. It allows the integration of the hundreds of existing plugins that complete the features of the Eclipse® IDE.
## Xpack Packages :
### Windows Build Tools:
The xPack Windows Build Tools is a standalone Windows binary distribution of GNU make and a few of other tools required by the Eclipse Embedded CDT (formerly GNU MCU/ARM Eclipse) project, but the binaries can also be used in generic build environments.
### OpenOCD :
Open On-Chip Debugger (OpenOCD) is a free, open-source project that aims to provide debugging, in-system programming, and boundary scan using a debug adapter. The adapter is a hardware module that provides the right signals for the target to understand.
### QEMU :
The xPack QEMU Arm is a standalone cross-platform binary distribution of QEMU, with several extensions for Arm Cortex-M devices.
## COMPONENTS USED IN PROJECT:
### STM32F407G-DISC1
STM32F407 series of microcontrollers are high-performance MCUs designed for medical, industrial and consumer applications. It is based on ARM Cortex-M4 and offers up to 168MHz. The STM32F407VGT6 is the onboard chip which comes in a 100-pin LQFP package.

The STM32F407G-DISC1 is a Discovery Kit allows users to easily develop applications with the STM32F407 high performance microcontrollers with ARM cortex-M4 32-bit core. It includes everything required either for beginners or for experienced users to get quickly started. Based on the STM32F407VGT6, it includes an ST-LINK/V2 or ST-LINK/V2-A embedded debug tool, two ST MEMS digital accelerometers, a digital microphone, one audio DAC with integrated class D speaker driver, LEDs and push buttons and an USB OTG micro-AB connector.

### Features Of STM32F407G
- Flash memory of up to 1 megabyte.
- OTP memory of 512 bytes.
- Compact Flash, SRAM, PSRAM, NOR, and NAND memories are supported by this flexible static memory controller.
- Sleep, Stop, and Standby modes are low-power modes.
- 16-stream DMA controller with FIFOs and burst support for general-purpose DMA.
- Up to 54 Mbytes/s 8- to 14-bit parallel camera interface.
- Generator of true random numbers.
- Hardware calendar, CRC calculating unit, 96-bit unique ID RTC, subsecond accuracy.
# REQUIREMENTS 
## High level requirements
|ID|	Discription	|status|
|--|--------------|------|
|HR_01|	Car is in ACC mode	|Implemented|
|HR_02	|Car is in Ignition mode|	Implemented|
|HR_03|	Wiper turned on|	Implemented|
|HR_04	|Wiper turned off	|Implemented|
## Low level requirements
|ID	|Discription|	status|
|---|-----------|-------|
|LR_01	|Button pressed ONCE for two seconds - ON LED RED	|Implemented|
|LR_02	|Button pressed once again times - OFF LED RED|	Implemented|
|LR_03	|Button pressed two time - ON BLUE,GREEN,ORANGE|	Implemented|
|LR_04	|Button pressed again for two seconds - OFF ORANGE,GREEN,BLUE	|Implemented|

## SWOT ANALYSIS
### Strengths
- Simple device for cleaning car front windshield
- Cost effective 
- Maintenance is easy
- Decreasing operator's distraction and improves the saftey
### Weakness 
- if wiper arms are loose it is likely that the pivot nuts are loose
- if windowshiled wipers are not touching glass
### Opportunities 
- Windowshiled wiper will boost the wiper system market.Additionally,the rising demand from SMEs and various industry verticals gives
 enough cushion to market groeth
### Threats
- When car is at speed of more than 150km/hr then the wiper may cause breakage.
- Heavy wind and rains may cause wiper chattering.

## ADVANTAGES
They offer a clear vision which helps in making the most important driving decisions.

## DISADVANTAGES

Most car owners devote all their attention to the motor, vehicle transmission, forgetting about such, seemingly, minor element, like windshield 
wipers. But such carelessness can lead to, that the wipers are worn down quickly and respectively significantly deteriorate the quality of 
cleaning of the windshield, which ultimately may contribute to getting into an accident. Just like any other equipment, wiper blades can chip,
crack and no longer have the efficiency to clean the windshield properly. 

## 4W 1H
### WHO
In car it's the wiper system which plays a major role in safety when the rainfall happens It makes the driver to see the inad properly without any difficulty even during the rainfall and fog It plays a major role in avoiding accidents
### WHERE
It is located near the steering where we can rotate to change the speed of the wiper infront of the car Duning the rainy season, water droplets on the windshield continuously disturb the visibility of the driver that can lead to major accidents to avoid that this wiper system can be t
## WHAT
According to the amount of rainfall the wiper system maintains certain speeds to remove the water from the glass to make the travel to hea clear vision
### WHEN
When the rainfall happens we can allow the wiper system to work During the rainy season, water droplets on the windshield continuously disturb the visibility of the driver that can lead to major accidents To avoid that this wper system can be used
### HOW
To operate your front wipers use the wiper stalk on the right hand side of your steering column Fush the stalk down ONE position to turn on intermittent wiper speed and adjust the speed using the collai Push the stalk down to the SECOND position for a low wiper speed and proh down to the THIRD position for the highest speed
### USING STM32 IN WIPER SYSTEM
The STM32 family of 32 bit microcontrollers based on the Arm Cortex M processor is designed to offer new degrees of freedom to MCU users. It offers products combining very high performance, real-time capabilities digital signal processing, low-power/low voltage operation and connectivity, while maintaining full integration and ease of development

The unparalleled range of STM32 microcontroliers, based on an industry standard core, comes with a vast choice of tools and software to support project development, making this family of products ideal for both small projects and end to end platforms

1. Ignition Key Position at ACC: The Red LED is ON, if the user button is pressed and held for 2 secs
2. Wiper ON: Wiper is OFF: On press of the user input, Blue Green and Orange LEDs come ON one at a time with the set frequency, The
frequency changes on every alternate key press 3 frequency levels with 1,4 and 8 Hz
3 Wiper OFF Wiper is ON! The LED glow pattern stops on the 4th press the wiper action starts next press onwards as mentioned in step 2 4 Ignition Key Position at Lock The Red LED is CFF if the user button is pressed and held for 2 secs

## FUTURE SCOPE
1)Wipers can be designed with sensors as whenover the rainfall happens it can sense the water and the wipe can be switched on automatically so that the driver dont loose his concentration while searching and switching it on as sometimes this moment can make the accident happen, To avoid that we can go for it
2)Wipers can be designed such a way that a double wiper can act both inside and outside as sometimes the glass inside the car may be filled with the fog which makes the driver's usion low So even this can be designed to avoid accidents
3)We can make improvements in manufacturing the wiper blades to last ong So that we dont get the need to change it very often

## CONCLUSION
Hence Wipers do have a very important role in the safety of the riders because wiper performance is closely related to the safety of driving if it 
rains a lot and the car doesn't use wipers, the windshield will be dewy. Visible dew on the glass will block the view of the driver Hence it has an
important role to be played





