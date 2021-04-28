# 第十九章 Meter Interface

## 1、描述

​	  仪表接口设备代表能够将仪表信息发送到家庭自动化网络的计量设备（例如，电，气，水，热等）的接口。 取决于所测量的内容，该设备可能能够立即（通过轮询请求）读数或自主的周期性读数（通过推送机制发送）。 计量接口设备也可能能够传送某些状态指示器（例如，电池电量不足，检测到篡改）。如果计量接口无法提供价格信息，则可能会限制使用智能能源规范中定义的价格集群 通过使用“获取预定价格”来提供使用时间（TOU）间隔，而无需指定实际价格。 对于“发布价格命令”有效负载，“价格”字段将始终为0xff..ff，“价格层”字段应指定当前层名称。

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
    <td></td>
    <td>Identify</td>
   </tr>
   <tr align="center">
    <td>Metering</td>
    <td></td>
   </tr>
   <tr align="center">
    <td>Meter Identification</td>
    <td></td>
   </tr>
   <tr align="center">
   	<td colspan="2">Optional</td>
   </tr>
   <tr align="center"> 
       <td>Price</td>
       <td>Price</td>
   </tr>
   <tr align="center"> 
       <td></td>
       <td>Time</td>
   </tr>  
   <tr align="center"> 
       <td></td>
       <td>PrePayment</td>
   </tr>  
   <tr align="center"> 
       <td></td>
       <td>Message</td>
   </tr>
</table>
