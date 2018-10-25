# MQTT-Controller

A linear potentiometer to control devices through MQTT.

To me, this is the most intuitive and easy way to physically dim lights or control volume, covers or other devices. This motorized fader will send it's state to a MQTT server and will also position itself from states received from that MQTT server.

A video example:


## How To:

Make sure you have everything from the parts list.
The case I use was 3D printed and the STL files are included.

### Step 1
Download [arduino IDE](https://www.arduino.cc/en/Main/Software) and the MQTT-Controler.ino file from this repo.

### Step 2
Open the MQTT-Controler.ino file in the Arduino IDE. Enter your WiFi, MQTT and other information in the designated fields.

## Step 3
Connect NodeMCU and upload the code to the board.

## Step 4
Connect the wires according to the following diagram:

## Step 5
Put all the parts in a case and give the controler a place.


## Step 6



Parts list:

| Part | Description | Price | Link |
|------|-------------|-------|------|
|NodeMCU V3| The brain. I used a V3 but I think any NodeMCU will work | €2,09 | [AliExpress](https://nl.aliexpress.com/item/5pcs-lot-New-Wireless-module-NodeMcu-Lua-WIFI-Internet-of-Things-development-board-based-ESP8266-with/32266751149.html?spm=a2g0s.9042311.0.0.27424c4dssTCIN)|
|L298N Motor driver|Controll MotorFader through the NodeMCU with this board| €1,43 | [AliExpress](https://nl.aliexpress.com/item/1-stks-L298N-driver-board-module-L298-stappenmotor-slimme-auto-robot-breadboard-peltier-High-Power/32857475920.html?spm=a2g0s.9042311.0.0.2a0e4c4d7K6xfZ)|
|ALPS Motorized linear Potentiometer| The Flying fader | €22 | [Conrad](https://www.conrad.nl/p/alps-rsaon11m9-motorfader-10-k-05-w-lineair-1-stuks-442081)|
|10V AC-DC Adapter| Adapter to power L982N board. This board will power the motor as well as the NodeMCU| €?| Find locally|
| Case | A case to put everyting together. I created a simple case thats 3D printable that is included in this repo. | €? | In repo|


You will also need some wires to connect everything. 
