# CoreModules2SPAD.neXtConnector
Core Flight Tech. modules communicate via SPAD.neXt Serialv2 directly.

    -Close all applications on PC and be sure SPAD.neXt is not running at the background. 
    -Connect the via USB. 
    -Run Xloader.exe
    -Click file selection button. 
    -Find correct hex file.
    -Select device; Mega2560 for the MCP, Duemilanove/Nano(ATmega328) for other Modules. 
    -Select the correct Com port which the device connected. 
    -Set baud rate to 115200 for MCP, 57600 for other devices.
    -Upload the hex file. 
    
Important Note: While uploading, never interrupt the communication of the Module. Otherwise, there is no way to recovery if damaged.

https://coreflighttech.com/

Any feedback, please leave an e-mail to info@coreflighttech.com
