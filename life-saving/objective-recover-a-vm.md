# Objective: Recover a VM

In this lab, you will perform the following tasks:

* Restore a VM
* Export a VM

Rubrik radically simplifies the recovery process of virtual machines to deliver near-zero RTOs without additional manual intervention. Quickly test upgrades or recover from ransomware without data loss.

## Getting Started
Rubrik's Cloud Native Protection for Azure eliminates toil associated with protecting Azure VM workloads at scale. Polaris automates the protection VMs and replication of recovery points across regions in Microsoft Azure. Additionally, Polaris automates recovery operations allowing for full VM recovery in place, as well as across regions and subscriptions.

{% hint style="info" %}
**Trail Map:**

_Restore_ - Select a point in time and automatically roll an Azure VM back to a known good point in time, preserving its resourceId and private IP address. This operation ensures that disks are restored in a crash-consistent manner to the desired point in time, attached to the right mount points, and with the original tags, if desired.

_Export_ - Create a new Azure VM from the selected snapshot using either the original snapshot in the source region or a replica in another region. This workflow allows the user to define the VM name, type, size, subscription, resource group, region, VNet, subnet, and network security group. Tags that were on the source VM at the time of the snapshot can also be included or excluded from the export process.
{% endhint %}