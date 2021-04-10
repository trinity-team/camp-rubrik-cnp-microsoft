# Inventory Walkthrough

Polaris' simple user interface is built on a API-driven framework with a HTML5 web user interface. To see it for yourself:

Once you have accessed the Camp Rubrik lab environment, select the **Jump1** Host and authenticate using the following OS credentials:

* Username: `demo@rubrik.lab`
* Password: `Welcome10!`

Open up the web browser (Chrome) and browse to the Polaris URL specified in the jumpbox credentials tray. Log in using the credentials specified below the Polaris URL.

<p align="center">
<img src="../images/Polaris Login.png">
</p>

Once authenticated, the Rubrik UI will default to the **Clusters** page. Let’s explore the **Inventory** page.

<p align="center">
<img src="../images/Polaris Inventory.png">
</p>

The **Inventory** page provides a high-level overview of the types and quantities of workloads protected by source. This include cloud, saas, and data center workloads.

Click on **Azure** to display the Azure VMs discovered in the existing subscription.

<p align="center">
<img src="../images/Azure Inventory.png">
</p>

Use the **Resource Group** filter to filter the inventory down to the `prod` Resource Group whose name contains your Oasis lab id. This id can be found inside the jumpbox credentials tray. In this guide we will be using `oasis` as the lab id.

<p align="center">
<img src="../images/Azure Inventory Filtered.png">
</p>

The **Inventory** page now shows only the VMs associated with your lab environment. Click on the **VM name** that matches `your_lab_id-win-vm-1`. The **Overview** page for this vm appears. Here you can see manny details about the vm, its protection status, and an unpopulated snapshot calendar view.

<p align="center">
<img src="../images/Azure VM Overview.png">
</p>