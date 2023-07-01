# Sun-Tracking-Solar-Panel
![](vertopal_0e66308ed1a04b40b52a4c30af20b8f7/media/image1.png){width="3.3333333333333335in"
height="3.361111111111111in"}![](vertopal_0e66308ed1a04b40b52a4c30af20b8f7/media/image2.png){width="6.311111111111111in"
height="7.4936668853893265in"}![](vertopal_0e66308ed1a04b40b52a4c30af20b8f7/media/image3.png){width="4.1666666666666664e-2in"
height="5.555555555555555e-2in"}![](vertopal_0e66308ed1a04b40b52a4c30af20b8f7/media/image4.png){width="4.1666666666666664e-2in"
height="4.1666666666666664e-2in"}![](vertopal_0e66308ed1a04b40b52a4c30af20b8f7/media/image5.png){width="0.1111111111111111in"
height="6.944444444444445e-2in"}![](vertopal_0e66308ed1a04b40b52a4c30af20b8f7/media/image6.png){width="4.1666666666666664e-2in"
height="4.1666666666666664e-2in"}![](vertopal_0e66308ed1a04b40b52a4c30af20b8f7/media/image7.png){width="4.1666666666666664e-2in"
height="4.1666666666666664e-2in"}![](vertopal_0e66308ed1a04b40b52a4c30af20b8f7/media/image8.png){width="2.7777777777777776e-2in"
height="4.1666666666666664e-2in"}

**Dual-Axis** **Sun**\
**Tracking**\
**Solar Panel**

> **View more ECN Course Project**

**Vaishnavi Virat Dave**

**21116034**

+-----------------------------------+-----------------------------------+
| > **Benefits of** **my project**  | > ![](vertopal_0e66308ed1a0       |
| > With the increasing need of     | 4b40b52a4c30af20b8f7/media/image9 |
| > green energy , increasing the   | .png){width="7.127777777777778in" |
| > efficiency of our green         | > height="6.686111111111111in"}   |
| > technology is the need of the   |                                   |
| > hour and has been the biggest   |                                   |
| > challenge of technocrats . My   |                                   |
| > course project is SUN\          |                                   |
| > TRACKING SOLAR PANEL . It is a  |                                   |
| > device that tracks the sun      |                                   |
| > through its circuitry and       |                                   |
| > rotates in the sun's direction  |                                   |
| > along its 2 axis , one          |                                   |
| > horizontal and one vertical .   |                                   |
| > This movement ensures nearly    |                                   |
| > 50% more power than the         |                                   |
| > conventional solar panels .     |                                   |
| > Through this course project ,   |                                   |
| > in addition to learning about   |                                   |
| > the basics of\                  |                                   |
| > electronics , I also got to     |                                   |
| > learn about the basis of green  |                                   |
| > technology .                    |                                   |
| >                                 |                                   |
| > Basics of Arduino Coding ,      |                                   |
| > working of Solar Cell , how to  |                                   |
| > make electronic connections ,   |                                   |
| > soldering and also the working  |                                   |
| > of the servo motors is what I   |                                   |
| > have learned through this       |                                   |
| > process of making this working  |                                   |
| > model .                         |                                   |
+===================================+===================================+
+-----------------------------------+-----------------------------------+

> **Components
> used**![](vertopal_0e66308ed1a04b40b52a4c30af20b8f7/media/image14.png){width="7.143054461942257in"
> height="2.9537117235345582in"}

+-----------------------------------+-----------------------------------+
| > ![](vertopal_0e66308ed1a04b     |                                   |
| 40b52a4c30af20b8f7/media/image10. |                                   |
| png){width="3.3833333333333333in" |                                   |
| > height="2.3583333333333334in"}  |                                   |
| > ![](vertopal_0e66308ed1a04      |                                   |
| b40b52a4c30af20b8f7/media/image11 |                                   |
| .png){width="9.238888888888889in" |                                   |
| > height="2.6027766841644793in"}  |                                   |
| >                                 |                                   |
| > Arduino Uno 3 Solar Panels 4    |                                   |
| > LDRs On-off Switch 4 10K        |                                   |
| > Resistors                       |                                   |
+===================================+===================================+
| > ![](vertopal_0e66308ed1a04      | > ![](vertopal_0e66308ed1a04      |
| b40b52a4c30af20b8f7/media/image12 | b40b52a4c30af20b8f7/media/image13 |
| .png){width="2.386111111111111in" | .png){width="2.959721128608924in" |
| > height="2.2916666666666665in"}  | > height="2.3305555555555557in"}  |
+-----------------------------------+-----------------------------------+

> 2 Servo Motors Jumper Wires Connecting Wires 9V Battery Voltage
> Display

**Working Logic**

+-----------------------------------+-----------------------------------+
| ![](vertopal_0e66308ed1a04b       | > The working logic of my project |
| 40b52a4c30af20b8f7/media/image15. | > is based on LDR and the servo   |
| png){width="3.3694444444444445in" | > motor. Here, the servo motor    |
| height="2.3805544619422574in"}    | > with its axis horizontal is     |
|                                   | > measuring the altitude angle    |
|                                   | > and the servo motor with its    |
|                                   | > axis vertical is measuring the  |
|                                   | > azimuth angle of the sun. The   |
|                                   | > code uploaded in the Arduino    |
|                                   | > controls the positions of these |
|                                   | > servo motors through their      |
|                                   | > angle on the basis of light     |
|                                   | > incident on the 4 LDRs. If the  |
|                                   | > relative amount of light on any |
|                                   | > LDR is more than that on        |
|                                   | > others, the code commands the   |
|                                   | > servo motors to orient in such  |
|                                   | > a way that all the LDRs are     |
|                                   | > exposed to the same amount of   |
|                                   | > light. If this is not the       |
|                                   | > condition, by rotating the      |
|                                   | > panel about the required axis,  |
|                                   | > this condition is established.  |
|                                   | > Therefore, this arrangement     |
|                                   | > enables us to extract a very    |
|                                   | > good amount of power as         |
|                                   | > compared to conventional solar  |
|                                   | > panels.                         |
+===================================+===================================+
+-----------------------------------+-----------------------------------+

**Circuit Diagram**

+-----------------------------------+-----------------------------------+
| > The circuit design is very      | > ![](vertopal_0e66308ed1a04      |
| > simple. There are total 10 pins | b40b52a4c30af20b8f7/media/image16 |
| > that go into the Arduino Board  | .png){width="6.058333333333334in" |
| > . The wires in the 8 and 9      | > height="5.166666666666667in"}   |
| > ports are the signal wires of   |                                   |
| > the 2 servo motors. The         |                                   |
| > positive wires of the servo     |                                   |
| > motors are connected with all   |                                   |
| > the 4 LDRs and together, they   |                                   |
| > go into the 5V slot of the      |                                   |
| > board. The negative wires of    |                                   |
| > the 2 servo motors are          |                                   |
| > connected to all 4 resistors    |                                   |
| > and together, they go into the  |                                   |
| > GND slot of the board. The 2    |                                   |
| > ends of the battery are         |                                   |
| > connected to GND and Vin slots  |                                   |
| > of the board with an on-off     |                                   |
| > switch in between. The other 4  |                                   |
| > wires are from all the 4        |                                   |
| > individual resistors that go    |                                   |
| > into the A0, A1, A2, and A3     |                                   |
| > analog slots of the board. This |                                   |
| > enables the moving of the solar |                                   |
| > panel. The positive and         |                                   |
| > negative wires of the solar     |                                   |
| > panel are connected to the      |                                   |
| > voltage displayer that shows    |                                   |
| > the amount of power generated   |                                   |
| > by the solar panel.             |                                   |
+===================================+===================================+
+-----------------------------------+-----------------------------------+

![](vertopal_0e66308ed1a04b40b52a4c30af20b8f7/media/image22.png){width="2.5430555555555556in"
height="3.3139818460192476in"}![](vertopal_0e66308ed1a04b40b52a4c30af20b8f7/media/image23.png){width="3.7777777777777777in"
height="3.3194444444444446in"}

+-----------------------+-----------------------+-----------------------+
| > ![](verto           |                       | ![](vert              |
| pal_0e66308ed1a04b40b |                       | opal_0e66308ed1a04b40 |
| 52a4c30af20b8f7/media |                       | b52a4c30af20b8f7/medi |
| /image17.png){width=" |                       | a/image18.png){width= |
| 3.1999989063867016in" |                       | "4.156944444444444in" |
| > height="2           |                       | height="              |
| .6805555555555554in"} |                       | 5.923611111111111in"} |
+=======================+=======================+=======================+
| > ![](vert            | > ![](verto           |                       |
| opal_0e66308ed1a04b40 | pal_0e66308ed1a04b40b |                       |
| b52a4c30af20b8f7/medi | 52a4c30af20b8f7/media |                       |
| a/image19.png){width= | /image20.png){width=" |                       |
| "2.361111111111111in" | 0.9305555555555556in" |                       |
| > height="2           | > height="0           |                       |
| .7152777777777777in"} | .5555555555555556in"} |                       |
+-----------------------+-----------------------+-----------------------+

> Structuring phase Circuit Making Phase Final Working Model that can
> generate a maximum

![](vertopal_0e66308ed1a04b40b52a4c30af20b8f7/media/image21.png){width="8.333333333333333e-2in"
height="6.944444444444445e-2in"}
