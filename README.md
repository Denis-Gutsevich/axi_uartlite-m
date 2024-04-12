# axi_uartlite
Modified ip-core "axi_uartlite" from rs485_betta branch.
Added: 
	Choose baudrate by BAUD_REG. Address offset is 0x10. 
	Default rate is 115200 bod/s.
		
		BAUD_REG[0:4]	baud_rate [bod/s]
		"00000"			110    
		"00001"			300    
		"00010"			1200   
		"00011"			2400   
		"00100"			4800   
		"00101"			9600   
		"00110"			19200  
		"00111"			38400  
		"01000"			57600  
		"01001"			115200 
		"01010"			128000 
		"01011"			230400 
		"01100"			460800 
		"01101"			921600 
		
