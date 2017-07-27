<html>
<h>
This template is Step1 of 3 templates to build and Automate Secure Production like deployment on Azure Cloud and utilize best practice for creating IaaS V2 Infrastructure on Azure.

</h>
It creates a VNet with 2 Subnets:  Web, and DB subnet. 

It also creates 2 Network Security groups one per each subnet.

It creates DMZ rules for the Web Subnet to expose endpoints to the Internet. 

It blocks Outbound Internet access to VMs in  DB Subnet

It opens up DB Subnet only on the mysql DB port to Web Subnet.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsrakesh28%2Fazure-iaas-2-tier%2Fmaster%2Fstep1-network%2Fazuredeploynet.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>


</html>
