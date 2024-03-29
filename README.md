#Flash Bootloader in seeduino xiao Ble 

Hardware Required

1. Seeed Studio XIAO nRF52840
2. Jlink

Software Required

It is required to download the <a href="https://www.segger.com/downloads/jlink/" target="_blank" rel="noopener noreferrer">Segger</a> software from the website.

Step 1. Use Jlink to connect pins below:
![image](https://github.com/Embeddronics-ltd/xiaoblebootloader/assets/46509741/e503822b-7fe8-4379-86ed-82a7f034a2d2)

Step 2. Start the J-Flash and search nRF52840, creating a new project:
![image](https://github.com/Embeddronics-ltd/xiaoblebootloader/assets/46509741/6fd469e9-493c-49b6-b5ef-d69dac7c9f18)
![image](https://github.com/Embeddronics-ltd/xiaoblebootloader/assets/46509741/7ad8a11b-45b6-4cdf-8e2f-81ba4685f151)

Step 3. Click "Target" and then select "Connect".
![image](https://github.com/Embeddronics-ltd/xiaoblebootloader/assets/46509741/0ee9d755-9b52-4668-b27e-4ee7660cdd94)

Step 4. Draw the bin or <a href="https://github.com/Embeddronics-ltd/xiaoblebootloader/blob/main/Seeed_XIAO_nRF52840_Sense_bootloader-0.6.1_s140_7.3.0.hex" target="_blank" rel="noopener noreferrer">hex file </a> to software. 
![image](https://github.com/Embeddronics-ltd/xiaoblebootloader/assets/46509741/44440834-0623-44d7-9389-f05352168e9d)

Then press F4 and F5 in that order. The reflashing is done.
