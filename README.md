# GSM-Based-DC-Motor-Controller

Mobile App that uses sms messages to control the speed and direction of a remote DC Motor (source code)

Brief schematic of the application:

Mobile Phone => GSM Module => Arduino (ATMega Micro-controller) => L293D Motor Drive => Electric Motor

An sms, with the control message, is sent to the motor. The text sms is received by the GSM module and serialised to the Arduino.
The Arduino decodes and transmits the message to the Motor Drive as a digital signal. In turn, the drive, controls the motor and
has it running as per the text sms sent.

