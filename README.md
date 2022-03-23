# SC126_i2c_bus_routines
## SC126 I2C bus routines

#### 1000 - PORT_INIT:		    Configures the 8 bit control register IC – U6.
#### 1017 - I2C_RESET:		    Reset the I2C bus ready for communication.
#### 1025 – I2C_START:		    Send a start bit.
#### 1032 – I2C_STOP:		    Send a stop bit.
#### 1045 – I2C_TX:		      Transmit a single byte to the bus, read the ACK bit.
#### 1052 – I2C_RX:		      Receive a single byte from the bus, Send a NACK bit.
#### 1155 - ACK_POLLING:	    Wait for the device to send an acknowledge bit then issue a stop bit.
#### 10DE – I2C_WR:		      Sequence to send a byte to a specified devices memory address.
#### 1111 – I2C_RD	:		      Sequence to read a byte from a specified devices memory address.
#### 116F – I2C_BLOCK_WR:	  Transfer a block of data from memory to EEPROM.
#### 11CF – I2C_BLOCK_RD:	  Transfer a block of data from EEPROM to memory.
#### 117A - 	ALT_BLOCK_WR:	  Set EEPROM address then transfer block of data from memory to EEPROM.
#### 11DA – ALT_BLOCK_RD:	  Set EEPROM address then transfer block of data from EEPROM to memory.
#### 11F8 - I2C_RX2:		      Receive a byte of data from the device.
#### 120B - SEND_ACK:		    Send an ACK bit.
#### 1215 - SEND_NACK:		    Send a NACK bit.
#### 121C – RESTART:		      Perform a restart to continue using the bus.
#### 1226 – RTC_BLOCK_WR:	  Sequence to send 8 bytes from a config table to 	the DS1307 RTC.
#### 124D – RTC_BLOCK_RD:	  Sequence to receive 8 bytes from the DS1307 RTC to a config table.	
