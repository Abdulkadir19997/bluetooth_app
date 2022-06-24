## Features

The goal of this project, is to control a servo motor using HC06 bluetooth detector connected to arduino.

+ Adapter status monitoring,

+ Turning adapter on and off,

+ Opening settings,

+ Discovering devices (and requesting discoverability),

+ Listing bonded devices and pairing new ones,

+ Connecting to multiple devices at the same time,

+ Sending and receiving data (multiple connections).

The plugin (for now) uses Serial Port profile for moving data over RFCOMM, so make sure there is running Service Discovery Protocol that points to SP/RFCOMM channel of the device. There could be [max up to 7 Bluetooth connections](https://stackoverflow.com/a/32149519/4880243).

For now there is only Android support.


![WhatsApp Image 2022-05-05 at 7 38 07 PM](https://user-images.githubusercontent.com/91943064/175530046-59a84e85-a10d-4d24-a46d-bf9b9ba2a8ca.jpeg)
![WhatsApp Image 2022-05-06 at 1 18 38 PM](https://user-images.githubusercontent.com/91943064/175530051-8ba1fdb5-6bbb-476a-84d0-8ba934e1b714.jpeg)
![WhatsApp Image 2022-05-06 at 4 44 05 PM](https://user-images.githubusercontent.com/91943064/175530062-4357ee32-0bad-4637-882e-cb0bb05072fb.jpeg)
![image](https://user-images.githubusercontent.com/91943064/175530244-fbff05ee-3bec-430b-b976-9e82f0a95181.png)




