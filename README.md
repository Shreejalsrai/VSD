# A 4-week Research Internship on VSDSquadron Mini RISC-V Dev Board

BOARD SPECIFICATIONS:

| Tech specs   |   |    |
|------------|------------|------------|
| *Board* | Name     | VSDSquadron Mini    |
|      | SKU    | VSDSQM    |
| *Microcontroller*    | CH32V003F4U6 chip with 32-bit RISC-V core based on RV32EC instruction set    |     |
| *USB connector* | USB 2.0 Type-C    |     |
| *Pins*     | Built-in LED Pin     | 1X onboard user led (PD6)     |
|      | Digital I/O pins     | 15     |
|      | Analog I/O pins     | 10-bit ADC, PD0-PD7, PA1, PA2, PC4     |
|      | PWM pins     | 14X     |
|      | External interrupts     | 	8 external interrupt edge detectors, but it only maps one external interrupt to 18 I/O ports     |
| *Communication*     | USART     | 	1x, PD6(RX), PD5(TX)     |
|      | I2C     | 1x, PC1(SDA), PC2(SCL)    |
|      | SPI     | 1x, PC5(SCK), PC1(NSS), PC6(MOSI), PC7(MISO)     |
|      | Programmer/debugger     | Onboard RISC-V programmer/debugger, USB to TTL serial port support     |
| *Power*     | I/O voltage     | 3.3 V    |
|      | Input voltage (nominal)     | 5 V    |
|      | Source Current per I/O Pin    | 8 mA     |
|      | Sink Current per I/O Pin     | 8 mA     |
| *Clock speed*     | Processor    | 24 MHz     |
| *Memory*     | SRAM     | 2kb onchip volatile sram,16kb external program memory     |
   

This repo is intended to document the weekly progress.

### The first online meet was held on 16th of Feb 2024 @6PM

<details>
    <summary> TASK 1 </summary>
 
1) install Yosys 

2) install iverilog 

3) install gtkwave

### CLONING RISC-V GNU TOOLCHAIN

# To install git 
sudo apt install git-all   

 make sure to install the dependencies
![86a76990-1015-43d1-b726-e30082617551](https://github.com/Shreejalsrai/VSD/assets/160627157/16f1c365-93a4-4da3-ab45-5bba0d62154c)




### INSTALLING YOSYS, IVERILOG & GTKWAVE.

### 1.YOSYS


git clone https://github.com/YosysHQ/yosys.git
![a98614a6-670a-4369-ab78-a9e2b9495517](https://github.com/Shreejalsrai/VSD/assets/160627157/ddf1f966-c0b6-42d5-b64b-9d1f60f2cf0f)

cd yosys 

sudo apt install make
![2c70b827-d3c1-4155-b023-7b4bedfbcd05](https://github.com/Shreejalsrai/VSD/assets/160627157/6a734fc9-3c61-418e-a866-f2a5ddfd2aed)

sudo apt-get install build-essential clang bison flex \libreadline-dev gawk tcl-dev libffi-dev git \ graphviz xdot pkg-config python3 libboost-system-dev\libboost-python-dev libboost-filesystem-dev zlib1g-dev

make config-gcc

make 

sudo make install
![4fe9c91f-eb81-4e21-9e7c-51edd4b60b8b](https://github.com/Shreejalsrai/VSD/assets/160627157/88f28fd1-48ba-4aba-9b52-5299501fb8a3)




### 2.iVerilog
installing iVerilog

sudo apt update

sudo apt-get install iverilog

![4fe9c91f-eb81-4e21-9e7c-51edd4b60b8b](https://github.com/Shreejalsrai/VSD/assets/160627157/58951e74-3dfb-44d9-bc1d-a5dad896edd5)

### 3.GTkWave
installing GTkWave

 sudo apt-get install gtkwave
 
![2f34fdac-740a-46bb-a87f-0fbbe34235e0](https://github.com/Shreejalsrai/VSD/assets/160627157/f384911e-d38d-4590-8cba-73725d922463)


</details>

### The second online meet was held on 20th of Feb 2024 @6PM
<details>
    <summary> TASK 2 </summary>


## Universal Asynchronous Receiver Transmitter protocol based on hardware transmitter

### Introduction:


UART means Universal Asynchronous Receiver Transmitter Protocol. UART is used for serial communication from the name itself we can understand the functions of UART, where U stands for Universal which means this protocol can be applied to any transmitter and receiver, and A is for Asynchronous which means one cannot use clock signal for communication of data and R and T refers to Receiver and Transmitter hence UART refers to a protocol in which serial data communication will happen without clock signal. 

![image](https://github.com/Shreejalsrai/VSD/assets/160627157/f1eb44bd-5242-49a2-9b11-3116374e588c)
</details>
