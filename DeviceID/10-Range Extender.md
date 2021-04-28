# 第十章 Range Extender

## 1、描述

​	Range Extender是一个简单的设备，可以充当其他设备的路由器。 Range Extender设备不应是ZigBee终端设备。 实现Range Extender设备的产品不应实现此配置文件中定义的任何其他设备。 仅当产品不打算用于任何其他应用程序，或者实施了本配置文件未解决的专用应用程序时，才应使用该设备。

## 2、Supported Cluster
<table>
   <tr align="center">
   	<td style="width:50%;">Server Side</td>
    <td style="width:50%;">Client Side</td>
   </tr>
   <tr align="center">
   	<td colspan="2">Mandatory</td>
   </tr>
   <tr align="center">
    <td>Basic</td>
    <td></td>
   </tr>
   <tr align="center">
    <td>Identify</td>
    <td></td>
   </tr>
   <tr align="center">
   	<td colspan="2">Optional</td>
   </tr>
   <tr align="center"> 
       <td>Clusters with reporting capability(see sub-clause 7.1.1 for details)</td>
       <td>Clusters with reporting capability(see sub-clause 7.1.1 for details)</td>
   </tr>
   <tr align="center"> 
       <td>Power Configuration</td>
       <td>Time</td>
   </tr>  
   <tr align="center"> 
       <td>Device Temperature Configuration</td>
       <td>OTA Bootload</td>
   </tr>  
   <tr align="center"> 
       <td>Alarms</td>
       <td></td>
   </tr>
   <tr align="center"> 
       <td>Electrical Measurement</td>
       <td></td>
   </tr>
   <tr align="center"> 
       <td>Poll Control</td>
       <td></td>
   </tr>
   <tr align="center"> 
       <td>Partition</td>
       <td>Partition</td>
   </tr>
   <tr align="center"> 
       <td>Manufacturer-specific(see sub-clause 7.1.6 for details)</td>
       <td>Manufacturer-specific(see sub-clause 7.1.6 for details)</td>
   </tr>
</table>

