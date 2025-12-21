# sniffRF
![PCB 3D Render](./Media/SniffRF_PCB_3D_Render.png)<br><br>

## Preface
This is a personal project and my very first STM32 PCB!!! Spent a couple of weekends working on this project. The STM32L053R8 is being used for this project as I already have the development board for this chip. A working prototype of this circuit was partially breadboarded and tested before the PCB was made. <br>

## About
SniffRF is an RSSI detector aka a signal strength detector for the 902MHz to 928MHz band based off an AD8318 chip and built around an STM32L053R8 MCU. <br>

## Application
Many IoT devices utilizing FHSS are often deployed in the ISM bandwidth surrounding 915MHz. If a transceiver is to be tested or deployed at a location, the noise floor in that location should be found and then the noise margin should be calculated to verify that it is above the minimum level required by this transceiver. SniffRF could potentially be used to gauge the background noise level at any location before deploying a device on the 900MHz band. <br><br>

Another interesting use case would be to use SniFFRF to find RC models and more importantly high power rockets with telemetry transceivers operating on the 900MHz band. Infact, the driving factor behind making this SniffRF module was to find rockets. An very low gain omnidirectional antenna could be used until the user is roughly in the neighbourhood surrounding the rocket. Then switch to a more directional antenna to pinpoint the exact location of the rocket. This will come in very handy in finding rockets in a ditch or inside a shrub on the desert floor. <br>

## TBC...
TBC... <br>

## Conclusion
TBC... <br>