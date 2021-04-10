# Create an SLA Domain

To create an SLA Domain:

On the navigation bar at the top of the window, select **SLA Domains**.

{% hint style="info" %}
**Trail Map:**

_Managed by: GPS_ - an SLA Domain that is created and managed in Rubrik Polaris.

_Managed by: Cluster_Name_ - an SLA Domain that is created and managed locally on a Rubrik Cloud Data Management (CDM) cluster.
{% endhint %}

Above the Sla Domain list, click the blue **CREATE SLA DOMAIN** button.

<p align="center">
<img src="../../images/Sla Domains.png">
</p>

Create an SLA Policy using the following configuration values:

For demonstration purposes, select **EC2/EBS** and **Azure VM/Disk** then click **Next**.

<p align="center">
<img src="../../images/SLA1.png">
</p>

Configure the SLA to take snapshots each hour for a day, and each day for a week then click **Next**.

<p align="center">
<img src="../../images/SLA2.png">
</p>


{% hint style="info" %}
**Trail Map:** Rubrik's Cloud Native Protection allows you to build SLA Domains that can be used across public clouds and even hybrid deployments. Use a single policy to protect your mission critical workloads and ensure they are replicated to provide increased security and resiliency.
{% endhint %}S

Select **Next** to configure replication in the SLA Domain. 

Configure the SLA to replicate to US West (Oregon) in AWS and West US 2 in Azure.

<p align="center">
<img src="../../images/SLA3.png">
</p>

Click **Next** and give the SLA a name that contains your lab id.

<p align="center">
<img src="../../images/SLA4.png">
</p>

Review and then click **Create** to finish.