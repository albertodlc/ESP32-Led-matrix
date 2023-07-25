# ESP32-Led-matrix
![Header](/images/header.jfif "Header")
## *BASIC ARDUINO STEPS*
### Detect DEV board on the PC (Windows)
We need to install specific drivers to connect the ESP32 board to a Windows PC. The drivers are available on the following link:
- [W10 Drivers - CP210x Windows Drivers](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers?tab=downloads)

### Start developing on an IDE (Arduino IDE)
The next step is to install the Arduion IDE [Arduino IDE](https://www.arduino.cc/en/software) and configure the ESP32 board on it.

For that, we need to install an Addon on the IDE. We can follow [this](https://www.youtube.com/watch?time_continue=24&v=mBaS3YnqDaU&feature=emb_title) video to complete this step.

### Upload a program TO the ESP32 board
After writing the code, we need to test it on the board. For that, we need to press the `check button` (to compile the program) and the `right arrrow button` to upload the program to the board

## *PROJECT DIAGRAM*
The project diragram is as follows:
![Project Diagram](/images/diagrama.png "Project Diagram")

We have 3 basic elements:
- The 16x16 LED Matrix: bought on Aliexpress (~10€)[LINK](https://es.aliexpress.com/item/1005002294644787.html?spm=a2g0o.order_list.0.0.21ef194dk2ampm&gatewayAdapt=glo2esp)
- The ESP32 Board: bought on Aliexpress (~3-4€) [LINK](https://es.aliexpress.com/item/1005001929935550.html?spm=a2g0o.order_list.0.0.21ef194dk2ampm&gatewayAdapt=glo2esp)
- A power supply: in my case is a regulable power supply, but for the final project we can use a simple one of 5V - 15A (we can reduce this number using multiplexation and other [tecniques](https://arduino.stackexchange.com/questions/83351/how-to-work-with-ws2812b-16x16-matrix-panel-from-aliexpress).
    - Power supply adapter [5V and 3A] (5.5x2.1-2.5mm): [LINK](https://es.aliexpress.com/item/1005004497000966.html?spm=a2g0o.productlist.main.33.5b541b7aCXpeyb&algo_pvid=0a3709f1-1753-4ad5-9763-c46b8535222a&algo_exp_id=0a3709f1-1753-4ad5-9763-c46b8535222a-16&pdp_ext_f=%7B%22sku_id%22%3A%2212000029365239060%22%7D&pdp_npi=2%40dis%21EUR%2117.85%218.75%21%21%21%21%21%402145288516655943207442304d0758%2112000029365239060%21sea&curPageLogUid=QbU5zFHdz7vJ)
    - Female DC Jack connector (5.5x2.1mm): [LINK](https://es.aliexpress.com/item/32805447244.html?spm=a2g0o.productlist.main.1.63b74b3awknaht&algo_pvid=fa0a3c44-a2f8-4060-a766-4880b73d6c54&algo_exp_id=fa0a3c44-a2f8-4060-a766-4880b73d6c54-0&pdp_ext_f=%7B%22sku_id%22%3A%2264304028955%22%7D&pdp_npi=2%40dis%21EUR%211.53%211.23%21%21%21%21%21%40214527fd16655944634894935d076c%2164304028955%21sea&curPageLogUid=yiHmGT6pchGC)

As optionals elements, if we have a 3D printer we can build a case and a Frame to built the diagram on it. 

[LINK](https://www.thingiverse.com/thing:4127683/files)

## *CODE DESCRIPTION*


https://www.youtube.com/watch?v=6XGeM2__Zx4