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


</details>

### The third online meet was held on 22nd of Feb 2024 @6PM
<details>
    <summary> TASK 3 </summary>

![WhatsApp Image 2024-02-26 at 4 56 39 PM](https://github.com/Shreejalsrai/VSD/assets/160627157/441558c6-8142-4591-b562-63f73691c740)

![WhatsApp Image 2024-02-26 at 4 56 27 PM](https://github.com/Shreejalsrai/VSD/assets/160627157/8b2e7d98-1aa4-41f5-98c8-fc2d2c65db54)
![WhatsApp Image 2024-02-26 at 4 56 18 PM](https://github.com/Shreejalsrai/VSD/assets/160627157/d56c25dc-b585-482f-896f-fa09210c66d3)
![WhatsApp Image 2024-02-26 at 4 56 48 PM](https://github.com/Shreejalsrai/VSD/assets/160627157/17f41e2d-6969-4b16-95f1-9f4406679297)

</details>

### The fourth online meet was held on 27th of Feb 2024 @6PM
<details>
    <summary> TASK 4 </summary>
   
![WhatsApp Image 2024-02-29 at 12 16 15 PM (2)](https://github.com/Shreejalsrai/VSD/assets/160627157/7a3a419f-c330-4d3f-b57d-c3926907e69a)
![WhatsApp Image 2024-02-29 at 12 16 15 PM (1)](https://github.com/Shreejalsrai/VSD/assets/160627157/3b82c49f-becd-47d8-bfaa-d866bd8c4138)
![WhatsApp Image 2024-02-29 at 12 16 14 PM (1)](https://github.com/Shreejalsrai/VSD/assets/160627157/700db014-6cda-4abf-aa7f-e13a292ee219)
![WhatsApp Image 2024-03-05 at 2 46 12 PM (2)](https://github.com/Shreejalsrai/VSD/assets/160627157/d0d3672f-bc75-4e0f-abd5-5afdb26d295d)
![WhatsApp Image 2024-03-05 at 2 46 12 PM (3)](https://github.com/Shreejalsrai/VSD/assets/160627157/530f595d-776e-4d78-99f4-6b72341907f1)
![WhatsApp Image 2024-03-05 at 2 46 13 PM](https://github.com/Shreejalsrai/VSD/assets/160627157/715cf90b-1b15-41d4-b387-5c1a772f3438)
![WhatsApp Image 2024-03-05 at 2 46 13 PM (1)](https://github.com/Shreejalsrai/VSD/assets/160627157/fcf5dace-07f4-421f-ab64-6d103f952e52)
![WhatsApp Image 2024-03-05 at 2 46 13 PM (6)](https://github.com/Shreejalsrai/VSD/assets/160627157/6d9c3417-7dec-4a97-b191-54732d284479)
![WhatsApp Image 2024-03-05 at 2 46 14 PM](https://github.com/Shreejalsrai/VSD/assets/160627157/a4f67a2b-56ba-440e-8173-726e0208b16c)
![WhatsApp Image 2024-03-05 at 2 46 14 PM (1)](https://github.com/Shreejalsrai/VSD/assets/160627157/298fd494-6b75-4f25-9971-9812f98bbf3b)
![WhatsApp Image 2024-03-05 at 2 46 12 PM (1)](https://github.com/Shreejalsrai/VSD/assets/160627157/b83e50a2-d163-41a0-84af-c92f09f00e8c)
![WhatsApp Image 2024-03-05 at 2 46 12 PM](https://github.com/Shreejalsrai/VSD/assets/160627157/a4200067-aebc-4a1e-9bf8-2b138e499f64)


</details>

### The fifth online meet was held on 1st of March 2024 @6PM
<details>
    <summary> TASK 5 </summary>

![WhatsApp Image 2024-03-05 at 3 05 54 PM (7)](https://github.com/Shreejalsrai/VSD/assets/160627157/3f1daa1f-beef-4e53-ad77-ba72b2fabe48)
![WhatsApp Image 2024-03-05 at 3 05 54 PM (8)](https://github.com/Shreejalsrai/VSD/assets/160627157/22462401-52c3-4855-8ff4-54618e040087)
![WhatsApp Image 2024-03-05 at 3 05 54 PM (9)](https://github.com/Shreejalsrai/VSD/assets/160627157/eb665edb-3f0d-446a-9dc0-8817e57b30f2)
![WhatsApp Image 2024-03-05 at 3 05 54 PM (2)](https://github.com/Shreejalsrai/VSD/assets/160627157/76583664-8e0f-4279-996b-909f0fbae312)
![WhatsApp Image 2024-03-05 at 3 05 54 PM (3)](https://github.com/Shreejalsrai/VSD/assets/160627157/5a497699-9c7a-424a-a126-5d43f16bf89f)
![WhatsApp Image 2024-03-05 at 3 05 54 PM (4)](https://github.com/Shreejalsrai/VSD/assets/160627157/30b4544b-228f-4094-a59b-5d4c09dbe242)
![WhatsApp Image 2024-03-05 at 3 05 54 PM (5)](https://github.com/Shreejalsrai/VSD/assets/160627157/70b5fd13-f041-4e42-9ef9-89151a8c12aa)
![WhatsApp Image 2024-03-05 at 3 05 54 PM (6)](https://github.com/Shreejalsrai/VSD/assets/160627157/a8345919-217b-4739-8516-af22acfd263d)
![WhatsApp Image 2024-03-05 at 3 05 54 PM (10)](https://github.com/Shreejalsrai/VSD/assets/160627157/3f392a52-c714-46ba-9227-a0c9800cfbc9)
![WhatsApp Image 2024-03-05 at 3 05 54 PM (11)](https://github.com/Shreejalsrai/VSD/assets/160627157/32f9a681-0ecb-485c-9ea6-51c65b47dcbb)
![WhatsApp Image 2024-03-05 at 3 05 55 PM](https://github.com/Shreejalsrai/VSD/assets/160627157/8041c571-71f8-4d97-944e-ba3f73072201)
![WhatsApp Image 2024-03-05 at 3 05 56 PM (2)](https://github.com/Shreejalsrai/VSD/assets/160627157/b1dc9d58-ee17-4506-8245-3f1e4753558f)
![WhatsApp Image 2024-03-05 at 3 05 56 PM (3)](https://github.com/Shreejalsrai/VSD/assets/160627157/eb89de13-8534-4e38-bc2a-3f7aa949d5d8)
![WhatsApp Image 2024-03-05 at 3 05 56 PM (4)](https://github.com/Shreejalsrai/VSD/assets/160627157/f18cf519-4daf-4d64-aef7-510b493aaa39)
![WhatsApp Image 2024-03-05 at 3 05 56 PM (6)](https://github.com/Shreejalsrai/VSD/assets/160627157/d58af89d-7cc9-4047-b232-20a1d045a026)
![WhatsApp Image 2024-03-05 at 3 05 56 PM (5)](https://github.com/Shreejalsrai/VSD/assets/160627157/4ce8c124-6212-4a23-bc5f-6d0b248a422c)
![WhatsApp Image 2024-03-05 at 3 05 54 PM (1)](https://github.com/Shreejalsrai/VSD/assets/160627157/6fe9ccab-8501-4b33-84c4-6c082ceab12a)
![WhatsApp Image 2024-03-05 at 3 05 54 PM](https://github.com/Shreejalsrai/VSD/assets/160627157/cc29aa1f-876e-4d16-913f-2a91734a4426)


</details>



    


