# System for Noncontact Measurement of Biopotential with Capacitive Driven Right Leg

<div style="text-align: justify"> 
Inherent noninvasive nature and minimal or almost nonexistent measurement preparation makes noncontact biopotential measurement systems exceptionally attractive for clinical use, rehabilitation and neonatal health monitoring. Even though noncontact biopotential measurement systems eliminate some of the key shortcomings which are related to the classical, contact measurement systems, they simultaneously bring a wide variety of engineering challenges, the analysis and solution of which is the main topic of this master thesis. 

Noncontact measurement of electrophysiological signals from the human body is achieved with designed active capacitive electrodes. Analog measurement system of active electrode consists of low – noise preamplifier LMP7721, cascade of high – pass, low – pass and bandstop filters. Amplitude – frequency characteristic is tuned for ECG signal measurement, where the role of bandstop filter is to eliminate the 50 Hz power line interference. 

In order to additionally decrease sensitivity to external interference, a capacitive driven right leg circuit is designed on a dedicated printed circuit board. Input to the system is a common mode interference component present on the measurement electrodes. The supplied signal is inverted and amplified and is capacitively sent back to the body. For the simultaneous acquisition of signals from two electrodes, analog – to – digital conversion and signal transmission, a dedicated, low – power system on a printed circuit board was designed. 

Designed system is based on the nRF52832 microcontroller and ADS1192 integrated circuit. Signal transmission for the further processing and visualization can be achieved with UART interface or wirelessly with Bluetooth Low Energy (BLE) technology. For powering the designed system, usage of Li – Ion battery is intended. Battery status monitoring and its charging control is also part of the system.

The performed measurements showed the success of ECG signal acquisition and R – wave detection in the QRS complex. The distance of the electrodes from the body and the influence of external factors proved to be the biggest challenges for obtaining high – quality and repeatable results.


 </div>
