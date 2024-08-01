## Tesla M3 Rear Drive Unit (RDU) - JTAG interface

####  RDU PCB showing JTAG Connector  (Dave Fiddes Github)
<br><br>
![PCB with JTAG connector installed](https://github.com/davefiddes/c2000-inverter/blob/portable-cpp/docs/DIY-Tesla-M3-inverter-JTAG-cable.jpg)
<br><br><br>
### Using Damiens Jtag module.

[Damien's Jtag module](https://www.evbmw.com/index.php/evbmw-webshop/tesla-boards/m3du-jtag)<BR>
[Dave Fiddes Jtag setup](https://github.com/davefiddes/c2000-inverter/blob/portable-cpp/docs/Tesla-M3-JTAG-cable.md)
Once assembled the FTDI FT2232H must be programmed with the correct USB identifiers and configuration so that it appears to the host PC as a TI XDS100v2 JTAG adapter. To do this use the Windows [FT_PROG](https://ftdichip.com/utilities/#ft_prog) to apply the [TI template](https://software-dl.ti.com/ccs/esd/documents/xdsdebugprobes/files/F28379D_LAUNCHXL.zip).

###  Connector details

-  PCB Connector:  Hirose DF20F-10DP-1V(55)

-  Cable Connector - Housing (Shell)  :  Hirose DF20A-10DS-1C
-  Cable Connector - Pins  :  Hirose DF20F-2830SCFA
<br><br><br>
### AliExpress Pre-made Cable
<br><br><br>
-  [AliExpress link to store for Jtag cable](https://www.aliexpress.com/item/1005005884037779.html?src=google&aff_fcid=6090ed7d06404f66911ba49f2591ba9c-1721802355984-03216-UneMJZVf&aff_fsk=UneMJZVf&aff_platform=aaf&sk=UneMJZVf&aff_trace_key=6090ed7d06404f66911ba49f2591ba9c-1721802355984-03216-UneMJZVf&terminal_id=c1eee989edee4ee6a4026f3b7d0bf982&afSmartRedirect=n)

<p float="left">
  <img src="https://github.com/mackelec/tesla_M3_rdu/blob/main/dev/AliExpress%20Jtag%20cable%201.PNG" alt="Description of image 1" width="300" />
  <img src="https://github.com/mackelec/tesla_M3_rdu/blob/main/dev/AliExpress%20Jtag%20cable%202.PNG" alt="Description of image 2" width="300" />
</p>


<br><br><br>
###  Pinout of RDU JTAG Connector
<br><br><br>
![Tesla RDU Jtag Pinout](https://github.com/mackelec/tesla_M3_rdu/blob/main/resource/Jtag%20assigned_circled.png)





