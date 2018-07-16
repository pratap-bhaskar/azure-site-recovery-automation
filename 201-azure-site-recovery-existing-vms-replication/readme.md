# Replicating existing VMs on Azure to an existing Azure Site Recovery using ARM Templates

This template takes existing VMs in Azure and replicate them into already existing recovery service vault.

## Prerequistes

Before running this template you would need the following resource setup

1. VMs running in Azure in the source location, lets call this region PrimaryLocation.

2. A Recovery resource group created in a location other than the location where VMs are deployed, lets call this region TagetLocation.

3. Have a recovery service vault created in a region that is neither PrimaryLocation or TargetLocation.
