# OpenBatt_6s2p

**DIY 6s2p Li-Ion Batterypack integrated on a PCB with BMS and BLE**.
<br />
<br />
**Specs**: U=21.6V, I=30A, P=648W, C=108Wh, Dimensions=315x95x30mm [L,W,H]
<br />
<br />
You can find further technical information in the **Hardware System Architecture** below.

# Table of Contents
1. [ Project Status. ](#ProjectStatus)
2. [ 3D Top View. ](#3DTopView)
3. [ 3D Bottom View. ](#3DBottomView)
4. [ Example usage DIY Electric Longboard. ](#ExampleusageDIYElectricLongboard)
5. [ Hardware System Architecture. ](#HardwareSystemArchitecture)

<a name="ProjectStatus"></a>
# Project Status

Currently the PCB is untested! I'm waiting for some parts to be available... 

<a name="3DTopView"></a>
# 3D Top View

![OpenBatt_6s2p_3D_TopView](https://user-images.githubusercontent.com/108613519/177038933-394bf812-14e5-416e-8f4e-e9a5df584d60.png)

<a name="3DBottomView"></a>
# 3D Bottom View

![OpenBatt_6s2p_3D_BottomView](https://user-images.githubusercontent.com/108613519/177038978-36c688a1-d463-4b06-bcc9-7e361f0db8e3.png)

<a name="ExampleusageDIYElectricLongboard"></a>
# Example usage "DIY Electric Longboard"

![OpenBatt_6s2p_3D_ElectricLongboard](https://user-images.githubusercontent.com/108613519/177039099-7dec32df-2ebe-4c31-8aa8-50affc784a54.PNG)

<a name="HardwareSystemArchitecture"></a>
# Hardware System Architecture

![System_Architecture_Overview_V1_0](https://user-images.githubusercontent.com/108613519/180645766-bccaa4cf-a095-4783-bde8-66f1c8bca6b8.png)

![System_Architecture_Slave-BMS_V1_0](https://user-images.githubusercontent.com/108613519/180645775-f840c8e0-802b-446c-bbea-c92667edcf96.png)
For the Slave BMS i used the OpenSourceProject "diyBMSv4" from stuartpittaway. 
<br />
Link: https://github.com/stuartpittaway/diyBMSv4.
<br />
The diyBMSv4 is very minimalistic and very versatile!
Basic software from Stuart should also work for my project.
The fuses are not part of Stuarts BMS.

![System_Architecture_Main-BMS_V1_0](https://user-images.githubusercontent.com/108613519/180645788-24095e9f-82e8-4e1d-984c-1f77652f2dbd.png)


