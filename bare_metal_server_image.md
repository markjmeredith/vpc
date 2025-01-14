---

copyright:
  years: 2021, 2022
lastupdated: "2022-02-02"

keywords: bare metal license, esxi license, byol, bring your own license, ESXi 7.x BYOL

subcollection: vpc

---

{:codeblock: .codeblock}
{:screen: .screen}
{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:preview: .preview}
{:pre: .pre}
{:tip: .tip}
{:note: .note}
{:important: .important}
{:deprecated: .deprecated}
{:external: target="_blank" .external}
{:table: .aria-labeledby="caption"}
{:ui: .ph data-hd-interface='ui'}
{:cli: .ph data-hd-interface='cli'}
{:api: .ph data-hd-interface='api'}

# Bare Metal Servers for VPC images
{: #bare-metal-image}

You can license the ESXi hypervisor that is installed on a bare metal server with your own license (bring-your-own-license), or IBM can handle the licensing for you.
{: shortdesc}

You can specify how a bare metal server is licensed by selecting from different ESXi image options: "ESXi 7.x BYOL" or "ESXi 7.x".

* The "ESXi 7.x BYOL" option provides ESXi in evaluation mode. The evaluation period is 60 days and begins at the time of provisioning. At any time during the 60-day evaluation period, you can convert from evaluation mode to licensed mode with your appropriate customer provided license.

* The "ESXi 7.x" option provides ESXi in licensed mode and is activated during the provisioning process. Billing applies for IBM rented licenses. 

VMware ESXi on a Bare Metal Server for VPC is charged monthly and is calculated per CPU based on the selected profile. If you choose to rent VMware ESXi with your server, you are subject to a prorated monthly cost for the license instead of an hourly rate. Proration amount is variable based on your billing anniversary date. 
{: note}

For more information about how to license ESXi, see [Licensing ESXi Hosts](https://docs.vmware.com/en/VMware-vSphere/7.0/com.vmware.esxi.install.doc/GUID-28D25806-748B-49C0-97A1-E7DE5CB335A9.html){: external}.

You can view and manage your VMWare licenses [here](https://cloud.ibm.com/classic/devices/vmwarelicenses){: external}.
