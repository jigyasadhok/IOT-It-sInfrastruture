Network protocols:
1. Zigbee 

Type: Low-power, short-range wireless communication protocol.
Standard: IEEE 802.15.4.

Features: Low Power: Designed for devices that operate on small batteries for months or even years. Short Range: Typically 10–100 meters, depending on the environment and obstacles. Mesh Networking: Zigbee devices form a mesh network, where data can hop between devices to extend coverage. Low Data Rate: ~250 kbps, suitable for small packets like sensor data. Security: AES-128 encryption for secure communication. Applications: Smart home devices (e.g., smart lights, thermostats). Industrial automation. Healthcare monitoring systems. Agriculture (e.g., soil sensors). 2. BLE (Bluetooth Low Energy) 

Type: Short-range wireless communication protocol for low-power applications.
Standard: Part of the Bluetooth 4.0+ specifications.

Features: Energy Efficient: Designed for devices that need minimal power, allowing years of operation on small batteries. Short Range: ~10–50 meters (depending on power levels and environment). Fast Connection Time: Connects to devices quickly to conserve energy. Data Rate: Up to 2 Mbps (faster than Zigbee). Security: 128-bit AES encryption. Interoperability: Widely supported by smartphones, tablets, and IoT devices. Applications: Fitness trackers (e.g., Fitbit). Smartwatches. Wireless medical devices (e.g., heart rate monitors). Smart home systems (e.g., door locks). 

3. LTE (Long-Term Evolution) 

Type: High-speed cellular communication protocol.
Standard: Part of the 4G technology family.

Features: High Speed: Download speeds of up to 300 Mbps and upload speeds of up to 75 Mbps. Low Latency: Ideal for real-time applications like video calls and gaming. Wide Coverage: Operates on licensed spectrum bands, ensuring reliable connectivity over large areas. QoS (Quality of Service): Prioritizes different types of traffic (e.g., voice over data). Security: Encrypted communication using robust protocols. Applications: Mobile internet for smartphones, tablets, and laptops. IoT devices (e.g., connected cars, smart meters). Video streaming and VoLTE (Voice over LTE). 

4. RFID (Radio-Frequency Identification) 

Type: Wireless technology for tracking and identification.

Features: Tag-Based Communication: Uses RFID tags (passive, semi-passive, or active) and readers for data exchange. Passive Tags: Do not require a power source; powered by the reader's signal. Short Range: A few centimeters for passive tags; up to 100 meters for active tags. Low Data Rate: Suitable for basic identification data. Applications: Inventory management and supply chain tracking. Contactless payment systems (e.g., RFID-enabled credit cards). Access control (e.g., employee badges). Animal tracking (e.g., pet microchips). 

5. GSF WiFi (Google Services Framework WiFi) 

WiFi is based on the IEEE 802.11 standards and is widely used for wireless local area networks (WLANs).

Key Features of Modern WiFi: 
WiFi 4 (802.11n): Moderate speed (~150 Mbps); works on 2.4 GHz and 5 GHz.

WiFi 5 (802.11ac): High speed (~1.3 Gbps); optimized for 5 GHz. 

WiFi 6 (802.11ax): Enhanced speed (~9.6 Gbps), supports more devices, and offers low latency. Range: Up to 50 meters indoors, 100 meters outdoors. 

Applications: Internet access in homes, offices, and public areas. IoT device connectivity. High-speed streaming and gaming.

Infrastructure Protocols:
1. LTE-A
LTE-Advanced (LTE-A) is an improved version of LTE technology designed for cellular communication, especially for IoT and smart city applications. It is ideal for these scenarios because it offers low costs, scalability, and long-term infrastructure durability.

At its core, LTE-A works using a technology called OFDMA (Orthogonal Frequency Division Multiple Access), which splits the network bandwidth into smaller chunks called Physical Resource Blocks (PRBs) to efficiently handle multiple devices. It also uses carrier aggregation, allowing up to five 20 MHz channels to combine, increasing data capacity.  

2. EPCglobal
EPCglobal: The Electronic Product Code (EPC) is a
unique identification number which is stored on an RFID tag
and is used basically in the supply chain management to identify items.
EPCglobal is the organization that developed and manages this technology and its standards.

EPC Types
  96-bit EPC: Supports 268 million companies, 16 million product categories, and 68 billion serial numbers per category.

  64-bit EPCs (Types I, II, III): Support 16,000 companies, up to 9 million product types, and 33 million serial numbers per type.


3. 6LoWPAN
6LoWPAN stands for "IPv6 over Low-power Wireless Personal Area Networks". It is a protocol designed to enable low-power devices (like sensors) to communicate using IPv6 over wireless networks like IEEE 802.15.4, which have limited bandwidth, small packet sizes (127 bytes), and low power consumption.

Why Do We Need 6LoWPAN?
IPv6 packets are much larger than what low-power networks like IEEE 802.15.4 can handle. To solve this, 6LoWPAN acts as an adaptation layer to make IPv6 work efficiently over these constrained networks by:
1. Compressing IPv6 headers: Reduces overhead to save bandwidth and power.
2. Fragmenting packets: Splits large IPv6 packets into smaller ones that fit the limited frame size.
3. Supporting multi-hop communication: Ensures packets can pass through multiple devices to reach their destination.
