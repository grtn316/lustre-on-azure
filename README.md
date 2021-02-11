# Lustre client and server node VMs deployment

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FDDNStorage%2Flustre-on-azure%2Fmaster%2Fazuredeploy.json" target="_blank">
<img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FDDNStorage%2Flustre-on-azure%2Fmaster%2Fazuredeploy.json" target="_blank">
<img src="http://armviz.io/visualizebutton.png"/>
</a>


This template provides Automated Lustre server deployment on Azure and create Lustre filesystem.

# Components
- CentOS 7.6
- Lustre-2.12.0
- Clustered OSS/OST and MDS/MDT with ldiskfs

---
# Original code and references

https://github.com/Azure/azure-quickstart-templates/tree/master/intel-lustre-client-server

# CLI Deployment
`az deployment group create --resource-group dab-lustre-eus --template-file azuredeploy.json`