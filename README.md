---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Network
  platforms: java
---

# Getting Started with Network - Manage Network Watcher - in Java #


  Azure Network sample for managing network watcher.
  - Create Network Watcher
  - Manage packet capture - track traffic to and from a virtual machine
  Create a VM
  Start a packet capture
  Stop a packet capture
  Get a packet capture
  Delete a packet capture
  - Verify IP flow - verify if traffic is allowed to or from a virtual machine
  Get the IP address of a NIC on a virtual machine
  Test IP flow on the NIC
  - Analyze next hop - get the next hop type and IP address for a virtual machine
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

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/master/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/master/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/network-java-use-new-watcher.git

    cd network-java-use-new-watcher

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.