i2c-TMP102
==========

Reading temperature with the TMP102 i2c sensor and the Beaglebone

compile with:

	gcc tmp102.c -o tmp102
	

hints:

	i2c pullup resitor are required for i2c-2 (pin 17 and 18)

	
	address pin of the tmp102 device must be connected to ground or to vcc  