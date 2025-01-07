# Internet-of-Things-and-Communication-Interfaces

- Involves connecting physical devices, sensors, and systems to the internet for the collection, exchange, and analysation of data. Examples include: Smart home devices, industrial Iot Systems, wearable health monitors, an connected devices

Key Coms. Interfaces of IoT

* **Short Range**  
- Wifi   
- High speed, suitable or home automation an industrial IoT setups  
- Bluetooth  
- Low power and short range devices, variants like BLE optimize energy usage

* **Wide Range**  
- Cellular Networks (4G, 5G)  
- Essential for IoT applications requiring mobility , 5G provides higher bandwidth and lower latency, enabling real time.  
- Satellite Communication  
- Used in remote areas like environmental monitoring systems and rural areas  
* **Wired Coms.**  
- Ethernet   
- Reliable and high-speed  communication for industrial or data-heavy applications  
- Powerline Connections  
- Transfer data over already existing electrical wiring, useful in smart homes and buildings.

IoT and Communications Protocols

1. **IPv6 in IoT:**  
- Gives every IoT device a unique address for direct communication    
- solve s he shortage of IPv4 addresses and enables efficient routing  
- Supports low power networks (Like 6LoWPAN) for IoT devices.  
2. **HTTP/HTTPS:**  
- Used for sending data between devices and servers (e.g Rest APIs)  
- HTTPS encrypts the data for security, making it safer from hacking  
- Follows a request- response model (eg. devices send data, get commands back)  
3. **Combo of both:**  
- IPv6 handles addressing; HTTP/HTTPS handles secure data exchange.  
- Example: A smart bulb with an IPv6 address sends data to a cloud server over HTTPS to check if it should turn on/off.  
4.  **How do IoT devices use protocols like IPv6 or HTTP/HTTPS to communicate?:**  
- IoT devices use IPv6 to securely connect and communicate and HTTP/HTTPS to exchange information securely on the internet.  
- IoT devices are the same as any other internet-connected device, the only thing that changes it is the bandwidth, power and transmission distance from the connectivity.   

*How IoT Interfaces work with Web Servers*

Wifi connects IoT devices to Web servers while Bluetooth needs gateway devices (smart/tablet, smart hubs, or industrial gateways) for internet access but serve different purposes in IoT systems.

IoT devices use Bluetooth to send data to nearby gateways, like phones, with Wi-Fi devices that connect to the internet and also communicate with servers for data sharing and also remote control.

*How IoT devices impact the speed and performance of the internet*

Negative Impacts: can increase network congestion (too many devices in the Wi-fi), consuming bandwidth, and cause latency issues (delay in responsiveness of internet).  
It can strain the internet by generating a lot of data, making it slower for it to load pages.   
Positive Impacts: Drives innovation in network technologies (like 5G and edge computing) to handle traffic more efficiently.  
It can improve efficiency by improving internet performance by optimizing progress.

*How do browsers help show or manage IoT data*

- Browsers provide a visual interface for displaying IoT data and controlling devices.  
- They enable secure access to real-time updates, and remote management via cloud-hosted applications or local interface.  
- Technologies like Websockets, REST API, and encryption make browsers a powerful tool for interacting with IoT ecosystems.  
- Browsers allow IoT data to be displayed in interactive dashboards, helping other students in real-time.  
- Browsers enable users to send commands to IoT devices allowing for remote control and updates.  
- IoT Gateways secure communication between IoT devices and servers by managing data encryption and ensuring authorized access.  
