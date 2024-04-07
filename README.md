# axi_uartlite
Modified ip-core "axi_uartlite"
Added: 
	Controlling nRE/DE line for RS-485;
	Choose baudrate by CTRL_REG. Default rate is 115200 bod/s.
		CTRL_REG[2] := baud_sel[0];
		CTRL_REG[3] := baud_sel[1];
		CTRL_REG[5] := baud_sel[2];
		CTRL_REG[6] := baud_sel[3];
		CTRL_REG[7] := baud_sel[4];
		
		baud_sel	baud_rate [bod/s]
		"00000"		110    
		"00001"		300    
		"00010"		1200   
		"00011"		2400   
		"00100"		4800   
		"00101"		9600   
		"00110"		19200  
		"00111"		38400  
		"01000"		57600  
		"01001"		115200 
		"01010"		128000 
		"01011"		230400 
		"01100"		460800 
		"01101"		921600 
		
