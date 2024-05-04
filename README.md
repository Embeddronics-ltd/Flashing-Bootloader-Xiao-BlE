# Flash Bootloader in seeduino xiao Ble 

Hardware Required

1. Seeed Studio XIAO nRF52840
2. Jlink

Software Required

It is required to download the <a href="https://www.segger.com/downloads/jlink/" target="_blank" rel="noopener noreferrer">Segger</a> software from the website.
![image](https://github.com/Embeddronics-ltd/Flashing-Bootloader-Xiao-BlE/blob/main/Screenshot%202024-04-16%20131451.png)
Step 1. Use Jlink to connect pins below:
![image](https://github.com/Embeddronics-ltd/xiaoblebootloader/assets/46509741/e503822b-7fe8-4379-86ed-82a7f034a2d2)
![image](https://github.com/Embeddronics-ltd/Flashing-Bootloader-Xiao-BlE/assets/46509741/d9331cde-11f3-478e-85b4-8a33ca1b2a0b)
![image](https://github.com/Embeddronics-ltd/Flashing-Bootloader-Xiao-BlE/assets/46509741/ca779767-a386-4198-a1a4-db977ce1bde2)
![image](https://github.com/Embeddronics-ltd/Flashing-Bootloader-Xiao-BlE/assets/46509741/9997144f-b4b0-49f8-882a-7e3868d3ff5f)
<div>
<pre>
Nrf52840 Pin          SWD PIn
(TP5) Reset Pin   --------- Reset PIn 
(TP8) SWDIO Pin --------  TDO Pin
(TP7) SWDCLK Pin -------  RTCK Pin 
(TP11) 3.3v ------------------ VREF 
(TP 10) GND  ----------------- GND 
</pre>
</div>



Step 2. Start the J-Flash and search nRF52840, creating a new project:
![image](https://github.com/Embeddronics-ltd/Flashing-Bootloader-Xiao-BlE/assets/46509741/affd0f12-77d9-43f0-8f81-b7111e4b45f6)
![image](https://github.com/Embeddronics-ltd/Flashing-Bootloader-Xiao-BlE/assets/46509741/6d874d10-e791-4111-9e7a-0edc1129ea55)
![image](https://github.com/Embeddronics-ltd/Flashing-Bootloader-Xiao-BlE/assets/46509741/0809b48d-7646-4906-bfcd-97dbd2147437)


Step 3. Click "Target" and then select "Connect".
![image](https://github.com/Embeddronics-ltd/xiaoblebootloader/assets/46509741/0ee9d755-9b52-4668-b27e-4ee7660cdd94)

Step 4. Draw the bin or <a href="https://github.com/Embeddronics-ltd/xiaoblebootloader/blob/main/Seeed_XIAO_nRF52840_Sense_bootloader-0.6.1_s140_7.3.0.hex" target="_blank" rel="noopener noreferrer">hex file </a> to software. 
![image](https://github.com/Embeddronics-ltd/Flashing-Bootloader-Xiao-BlE/assets/46509741/feec2cff-8ed9-4cf8-9787-a429d3ad1619)
![image](https://github.com/Embeddronics-ltd/Flashing-Bootloader-Xiao-BlE/assets/46509741/122f060a-36f7-42fa-842e-6aa6673a5e1a)
![image](https://github.com/Embeddronics-ltd/Flashing-Bootloader-Xiao-BlE/assets/46509741/dc872e5c-1d6d-4c69-b43a-7e5efa612edb)




Then press F4 and F5 in that order. The reflashing is done.
![image](https://github.com/Embeddronics-ltd/Flashing-Bootloader-Xiao-BlE/assets/46509741/b7a91537-a968-4b94-93de-bd2836067a66)
![image](https://github.com/Embeddronics-ltd/Flashing-Bootloader-Xiao-BlE/assets/46509741/8657fe18-a2c7-4323-b70a-e26f318ceeef)

Flash success now you can disconnect jtag pins and arduino will pick it up 

@copy [Embeddronics](https://www.embeddronics.com/)
