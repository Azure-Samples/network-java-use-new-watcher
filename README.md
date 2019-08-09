---
page_type: sample
languages: java
products: azure
services: network-watcher
platforms: java
author: yaohaizh
---

## Getting Started with Network - Manage Network Watcher - in Java ##


  Azure Network sample for managing network watcher.
   - Create Network Watcher
   - Manage packet capture – track traffic to and from a virtual machine
       Create a VM
       Start a packet capture
       Stop a packet capture
       Get a packet capture
       Delete a packet capture
   - Verify IP flow – verify if traffic is allowed to or from a virtual machine
       Get the IP address of a NIC on a virtual machine
       Test IP flow on the NIC
   - Analyze next hop – get the next hop type and IP address for a virtual machine
   - Retrieve network topology for a resource group
   - Analyze Virtual Machine Security by examining effective network security rules applied to a VM
       Get security group view for the VM
   - Configure Network Security Group Flow Logs
       Get flow log settings
       Enable NSG flow log
       Disable NSG flow log
   - Download a packet capture
   - Download a flow log
   - Delete network watcher
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/network-java-use-new-watcher.git

    cd network-java-use-new-watcher

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.