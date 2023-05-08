#### What is it?

USB232R02 is a USB-UART adapter based on the FTDI chip [FT231XQ](https://ftdichip.com/products/ft231xq/).
The converter is characterized by its mechanical arrangement, which is compatible with the MLAB construction kit,
ensuring the robustness of manufactured devices and a unified approach to connecting individual components
using pin-headers. The converter is equipped with a USB-B connector for connection to a computer, for example.
This ensures a high-quality USB connection without communication dropout. The converter supports
USB Full speed with a transfer rate of up to 12 Mbps.

![USB232R02A_wide_small](https://user-images.githubusercontent.com/5196729/236865492-09f37ae5-6997-42ab-aa2f-36fa9e03e0bd.jpg)

The module contains a pair of output power connectors/pin headers with voltages of 5V and 3.3V.
The 5V supply is protected by a 750 mA fuse and is obtained from USB voltage. The 3.3V comes from an internal 
LDO with a maximum load of 50mA. The module is equipped with a pair of LEDs indicating RX/TX communication over USB.

The FTDI chip has a CMOS output (3.3V levels), and the pins are 5V compatible.
As a result, the module can be connected to both 3.3V and 5V constructions without configuration
changes and without the risk of damaging them.

The module includes all control pins (Handshake). 
Output signals are routed to pin headers with a standard 2.54mm pitch
, and all pins are doubled. This way, you can easily create extensive
constructions without dealing with complex connections or split connection cables.

The module has a wide range of uses. It can be used to connect various microcontrollers
to a computer for data capturing or for controling them. It can also be used for configuring
or powering many existing devices that are often equipped with a serial interface at UART levels.
With the right cable, this converter can be used as a configuration interface for some networking devices,
for example.

You can find additional device parameters in the [README of the converter](https://github.com/mlab-modules/USB232R02#readme).
