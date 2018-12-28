# Phils-Li-Ion-Battery-Board

I created this PCB for my personal project of a very big custom Li-Ion Battery which i use to charge my FPV Racing Drones Batteries on the flying field. With this PCB, you can build your own LiIon/LiPo Battery with up to 6 cells. You dont need to worry about the balancing wires, they are intregated in the PCB.

<img src="https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/phils_liion_battery_board%20(1).jpg" width="800">

An ISDT BC-8S monitors all your cells and alerts you if there is any problem.

In adition, i also added 3 USB QC3.O USB Charging Ports, which can be seperatly turned on/off via a pin header jumper.

[<img src="https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/battery_board_V1.0_top.PNG" width="800">](https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/battery_board_V1.0_top.PNG)

[<img src="https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/diy_lithium_ion_battery_18650_cells-8.jpg" width="800">](https://blog.seidel-philipp.de/xxl-powerhouse-diy-feldakku-aus-18650-zellen/)

# Features
* connect up to 6 1S cells via XT60
* XT60 Plugs (direct or via cable)
* 3X 24W USB QC3.O USB Stepdown
* Balancer Port
* Port for ISDT BC-8S
* open copper trace on back - fill with solder tin to increase trace height
* 99mm x 80mm Board (all dimensions [here](https://raw.githubusercontent.com/ps915/Phils-Li-Ion-Battery-Board/master/photos/battery_board_V1.0_dimensions.PNG))

# Video
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/qvAzB0jTuBU/0.jpg)](https://www.youtube.com/watch?v=qvAzB0jTuBU)

https://www.youtube.com/watch?v=qvAzB0jTuBU

# Changelog
### [ALL RELEASES](https://github.com/ps915/Phils-Li-Ion-Battery-Board/releases) 
### 14.12.2018 - v1.1 released [DOWNLOAD](https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/battery_board_v1.1.zip)
* inital release

# What do you need
[<img src="https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/battery_board_v1.jpg" width="800">](https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/battery_board_v1.jpg)

* 1x PCB (how to order, see below)
* 1x [ISDT BC-8S](https://www.banggood.com/de/ISDT-BC-8S-Battery-Checker-with-Two-85dB-Buzzer-for-LiPo-LiHv-LiFe-LiIon-Batteries-p-1128253.html?p=3R26141006882201412N)
* 6x XT60 Male [without cable](https://www.banggood.com/10X-XT60-Male-Female-Bullet-Connectors-Plugs-For-RC-Battery-p-958017.html?p=3R26141006882201412N) / [with cable](https://www.banggood.com/AMASS-XT60-Plug-Connector-14AWG-10cm-Power-Cable-Wire-p-1060098.html?p=3R26141006882201412N)
* 2X XT60 Female [without cable](https://www.banggood.com/10X-XT60-Male-Female-Bullet-Connectors-Plugs-For-RC-Battery-p-958017.html?p=3R26141006882201412N) / [with cable](https://www.banggood.com/AMASS-XT60-Plug-Connector-14AWG-10cm-Power-Cable-Wire-p-1060098.html?p=3R26141006882201412N)
* 1x [9 Pin Header Female 90° Angled ](http://s.click.aliexpress.com/e/bd0gOtSg)
* 1x [7 Pin JST-XH 2.5mm Angled Connector](https://www.banggood.com/25-Sets-6-7-8-9-10-pin-Right-Angle-JST-XH-2_5mm-Male-Female-Lipo-Balance-Connector-p-1160584.html?p=3R26141006882201412N)
* 3x [USB Module](https://www.banggood.com/3pcs-DC-Buck-Module-12V24V-to-QC3_0-Single-USB-Mobile-Charging-Board-p-1338057.html?p=3R26141006882201412N)
* 3x [2 Pin RM2.54 Pin Header](https://www.banggood.com/10-Pcs-40-Pin-2_54mm-Single-Row-Male-Pin-Header-Strip-For-Arduino-p-918427.htm?p=3R26141006882201412Nl)
* 3x [Jumper](https://www.banggood.com/100pcs-2_54mm-Jumper-Cap-Short-Circuit-Cap-Pin-Connection-Block-p-1212414.html?p=3R26141006882201412N)

(some links above are affiliate links / Werbung)

# Important Notice
I removed the solder mask in order to apply solder to the traces on the back. I highly recommend to add a good amount of solder to all traces on the back to increase the trace height. With this method, the Traces can withand high amp flow. 
[<img src="https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/battery_board_V1.0_back.PNG" width="800">](https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/battery_board_V1.0_back.PNG)

I highly suggest to charge big parallel packs with individual 1S Chargers. Charging big batteries via the Balancer Port may take a while. 

If you want to use less than 6 cells, just bride the unused XT60 ports.

# Shematics
[<img src="https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/battery_board_V1.0_shematics.PNG" width="800">](https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/battery_board_V1.0_shematics.PNG)


# Blog post about the project
* english (soon)
* [deutsch](https://blog.seidel-philipp.de/xxl-powerhouse-diy-feldakku-aus-18650-zellen/)

# Ordering the PCB from shared project
here you can order my shared project (v1.1): [https://www.pcbway.com/project/shareproject/Phils_LiIon_Battery_Board_v1_1.html](https://www.pcbway.com/project/shareproject/Phils_LiIon_Battery_Board_v1_1.html)

1. Click on "Add to Cart"
2. Set Quantity to "10"
3. Solder Mask: select you favourite color
4. Finished Copper: 1oz
5. Silkscreen: select you favourite color

# Ordering the PCB via gerber file download

you can order the latest PCB (v1.2) from china when you downloaded my gerber file from GitHub:
1. Go to "PCB Instant Quote" [www.pcbway.com](https://www.pcbway.com/setinvite.aspx?inviteid=108086)
2. Upload gerber file 
3. verify "PCB Specification Selection"
* Board type: Single pieces
* Different Design in Panel: 1
* Size :	99 x 80 mm
* Quantity :	10	
* Layers :	2 layers
* Material :	FR-4 TG130	
* Thickness :	1.6 mm	
* Min Track/Spacing :	6/6mil
* Min Hole Size :	0.3	
* Solder Mask :	red	
* Silkscreen :	White
* Gold fingers :	No	
* Surface Finish :	HASL with lead	
* Tick "Yes" means you accept we might change "HASL" to "ENIG" at our discretion without extra charge.Thanks!
* Via Process :	Tenting vias
* Finished Copper:	1 oz Cu	
4. choose shipping
5. add to cart
6. Upload Gerber File (battery_board_v1.2.zip) by clicking  "+Add Gerber File"
7. click "Submit Order" and pay!
8. share unused PCBs with the community! =)

Photos V1.1:

<img src="https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/phils_liion_battery_board%20(1).jpg" width="300"> <img src="https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/phils_liion_battery_board%20(2).jpg" width="300"> <img src="https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/phils_liion_battery_board%20(3).jpg" width="300"> <img src="https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/phils_liion_battery_board%20(4).jpg" width="300"> <img src="https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/phils_liion_battery_board%20(5).jpg" width="300"> <img src="https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/phils_liion_battery_board%20(6).jpg" width="300"> <img src="https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/phils_liion_battery_board%20(7).jpg" width="300"> <img src="https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/phils_liion_battery_board%20(8).jpg" width="300"> <img src="https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/phils_liion_battery_board%20(9).jpg" width="300"> <img src="https://github.com/ps915/Phils-Li-Ion-Battery-Board/blob/master/photos/phils_liion_battery_board%20(10).jpg" width="300">

Photos Prototype:

<a href="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-2.jpg"><img class="alignnone size-medium wp-image-9172" src="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-2-300x225.jpg" alt="" width="300" height="225" /></a> <a href="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-1.jpg"><img class="alignnone size-medium wp-image-9171" src="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-1-300x225.jpg" alt="" width="300" height="225" /></a> <a href="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-3.jpg"><img class="alignnone size-medium wp-image-9173" src="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-3-300x225.jpg" alt="" width="300" height="225" /></a> <a href="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-4.jpg"><img class="alignnone size-medium wp-image-9174" src="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-4-300x225.jpg" alt="" width="300" height="225" /></a> <a href="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-5.jpg"><img class="alignnone size-medium wp-image-9175" src="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-5-300x225.jpg" alt="" width="300" height="225" /></a> <a href="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-6.jpg"><img class="alignnone size-medium wp-image-9176" src="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-6-300x225.jpg" alt="" width="300" height="225" /></a> <a href="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-7.jpg"><img class="alignnone size-medium wp-image-9177" src="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-7-300x225.jpg" alt="" width="300" height="225" /></a> <a href="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-8.jpg"><img class="alignnone size-medium wp-image-9178" src="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-8-300x225.jpg" alt="" width="300" height="225" /></a> <a href="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-9.jpg"><img class="alignnone size-medium wp-image-9179" src="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-9-300x225.jpg" alt="" width="300" height="225" /></a> <a href="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-10.jpg"><img class="alignnone size-medium wp-image-9180" src="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-10-300x225.jpg" alt="" width="300" height="225" /></a> <a href="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-11.jpg"><img class="alignnone size-medium wp-image-9181" src="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-11-300x225.jpg" alt="" width="300" height="225" /></a> <a href="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-12.jpg"><img class="alignnone size-medium wp-image-9182" src="https://blog.seidel-philipp.de/wp-content/uploads/2017/09/pcbway_prototype_liion_board-12-300x225.jpg" alt="" width="300" height="225" /></a>
