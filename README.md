## SDR-Based Multi-Hop Relay Network Testbed

We have implemented a robust multi-hop relay testbed using NI-USRP2921 and 2932 in LabVIEW NXG 5.0. 

Our design focuses on a relay node selection method, which utilizes amplify-and-forward (AF) relay techniques based on multiple measurements. 

These measurements include Signal-to-Noise Ratio (SNR), Received Signal Strength Indicator (RSSI), packet delay, used packet slot, and packet reception probability, all within a Time Division Duplex/Time Division Multiple Access (TDD/TDMA) protocol.

However, due to this project's association with KIOST, core schemes have not been included in the published codes. This is to maintain the confidentiality of the project details.

For a practical demonstration, a real-time testbed video has been uploaded to the YouTube channel, titled "[Multi-hop relay network based on Time Division Multiple Access (testbed based on NI)](https://www.youtube.com/watch?v=voAzFFCemsc)." 

The demonstration of data transmission based on the designed multi-hop relay network has been verified and evaluated through the list provided below:

1) [USRP-based Excel data transmission & reception](https://www.youtube.com/watch?v=z4IRT-KZuoY).
2) [End to end digital link testbed with NI-USRP 2921, 2932](https://www.youtube.com/watch?v=cBroDlvoG50).
3) [Single TX-RX based testbed](https://www.youtube.com/watch?v=zD9oPqSnpN4).

## Requirements
- (HW) NI-USRP2921, 2932
- (HW) NETGEAR switch hub
- (HW) Ethernet cat5 cable
- (SW) Labview 2021 or 2022
- (SW) Labview NXG 4.0 or 5.0
