# CMOS_VLP_2Transmitters
With an increase in popularity of location-based services and mobile autonomous systems, indoors positioning systems
have become more important in recent years. Among these, po-sitioning based on visible light offers several advantages.
With the increased use of LEDs for lighting purposes, visible light positioning (VLP) can be implemented using existing
infrastruc-ture. In addition to being easy to implement, VLP offers greater positioning accuracy than indoors positioning
based on radio-frequency and wireless communication technology. With modulated LEDs serving as transmitters, VLP relies
on either photodiodes or camera image sensors to receive light signals and perform positioning for the mobile receiver
system. In this paper, a VLP implementation is presented utilizing a camera as receiver and deploying a posi-tioning
algorithm capable of determining the receiver position from signals received from two transmitters. Transmitters are
distinguished through frequency division multiplexing: each transmitting LED is modulated with a symmetric square-wave
at a unique frequency serving as identifier (ID). LEDs modulated with On-Off-Keying at kHz frequencies produce blinking
patterns imperceptible to human eyes. The receiver exploits the rolling shutter of the image sensor to capture these light
signals as stripe patterns whose thickness is proportional to the signal frequency. The positioning algorithm uses a lookup
table to link image coordinates of identified transmitters with predetermined real-world coordinates, and determines the
receiver position through a back transformation from image coordinates of the camera’s optical cen-tre. During tests
performed with transmitters spaced 1.6m x 1.78m at a height of 1.49m, a median positioning error of 2cm was obtained.
