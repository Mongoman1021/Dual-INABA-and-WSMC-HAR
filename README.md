# Dual-INABA-and-WSMC-HAR
an enhenced network and a self-collected dataset of human activity recognition

about.txt for WSMC_HAR_data_sample


Associated tasks: classification

Number of attributes: 5
Missing attribute values: None
Class distribution: {
	Running ,
	Jogging ,
	Upstairs ,
	Downstairs ,
	Sitting ,
	 }

data_sample.txt follows this format:
[user-id],[time],[activity],[x-acceleration],[y-accel],[z-accel];

This line is a representative example:
6	14:51:30	Downstairs	0.5175016883844479	0.3816218604296867	0.14430627424699796

Sampling rate: 
20Hz (1 sample every 50ms)

Fields:
*user-id
	nominal, 6 and 7

*time
	numeric

*activity
	nominal, {
		Running
		Jogging
		Sitting
		Upstairs
		Downstairs }


*x-acceleration
	numeric, floating-point values between 0 .. 1
		The acceleration in the x direction as measured
		by the accelerometer. 

*y-accel
	numeric, see x-acceleration

*z-accel
        	numeric, see x-acceleration
