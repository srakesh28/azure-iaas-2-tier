<html>
<h>
This template is Step2 of 3 templates to build and Automate Secure Production like deployment on Azure Cloud and utilize best practice for creating IaaS V2 Infrastructure on Azure.
</h>
It creates a 2 Ubuntu Linux VM's per in each subnet Web, App and DB.
It also creates  Availability Sets for VM pairs in respective subnets for HA
It provides option to deploy Chef Agent extensions as part of the deployment.

Note: After this Template is deployed, Please login to portal and assosiate Subnets with NSG's, in-future release we will include this task within ARM template. This will make all FW rules effective e.g Assosiate WebNSG with WebSubnet

This Template builds up-on Next Template as Step3 for building your Infrastructure on Azure

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsrakesh28%2Fdemo-working%2Fmaster%2Fstep2-linuxvm%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>




</html>
