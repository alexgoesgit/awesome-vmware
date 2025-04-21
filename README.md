# List of awesome VMware alternatives 

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A list of virtualization software and solutions as a starting point for replacing VMware products. 

The solutions listed here offer similar functions to VMware virtualization products. Whether they are really suitable as an alternative depends heavily on individual requirements.

# Contents

* [Workstation](#workstation)
  * [VMware on Desktops](#vmware-on-desktops)
  * [Desktop Alternatives](#desktop-alternatives)
* [Server](#server)
  * [VMware](#vmware-for-servers)
  * [KVM-based Hypervisors](#kvm-based)
  * [Xen Hypervisors](#xen-hypervisors)
  * [Other Hypervisors](#other-hypervisors)
* [Orchestration and Cloud Management solutions](#orchestration-and-cloud-management-solutions)
  * [VMware vCenter](#vmware-vcenter)
  * [Cloud Management Alternatives](#cloud-management-alternatives)
* [Cloud](#cloud)
  * [Managed VMware by Cloud Providers](#managed-vmware-by-cloud-providers)
* [Contributing](#contributing)
* [License](#license)
  
# Workstation

## VMware on Desktops

- [VMware Workstation Pro](https://www.vmware.com/products/workstation-pro.html) - Build and run Windows, Linux and BSD virtual machines on a Windows or Linux desktop.
- [VMware Workstation Player](https://www.vmware.com/products/workstation-player.html) - Run multiple operating systems as virtual machines on your Windows or Linux desktop (Free for Personal Use).
- [VMware Fusion Pro](https://www.vmware.com/products/fusion.html) - Run Windows, Linux, containers, Kubernetes and more in virtual machines (VMs) on MacOS.
- [VMware Fusion Player](https://www.vmware.com/products/fusion.html) - Run Windows, Linux, containers, Kubernetes and more in virtual machines (VMs) on MacOS (Free for Personal Use).

## Desktop Alternatives

- [GNOME Boxes](https://github.com/ubuntu/gnome-boxes) - Application of the GNOME Desktop Environment, used to access virtual systems. Boxes uses the QEMU, KVM, and libvirt virtualization technologies.
- [Parallels Desktop for Mac (Standard/Pro/Business Edition)](https://www.parallels.com/products/desktop/) - Run Windows, Linux, or macOS in virtual machines on a Mac.
- [Microsoft Hyper-V](https://learn.microsoft.com/en-us/virtualization/hyper-v-on-windows/about/) - Lets you run multiple operating systems as virtual machines on Windows 10/11.
- [Oracle VM VirtualBox (Enterprise)](https://www.oracle.com/virtualization/virtualbox/) - Popular open source, cross-platform, virtualization software.
- [UTM](https://mac.getutm.app/) - UTM is a full featured system emulator and virtual machine host for iOS and macOS. [[docs](https://docs.getutm.app/)]
- [Virtualbox](https://www.virtualbox.org/) - General-purpose full virtualizer for x86 hardware, targeted at server, desktop and embedded use.
- [Virtualbox with KVM Backend](https://github.com/cyberus-technology/virtualbox-kvm) - KVM Backend for VirtualBox (has to be build from source).
- [VMTek](https://www.getvmtek.com/) - Mac virtualization platform. Run multiple instances and versions of macOS, Linux and other operating systems side-by-side on a Mac.

# Server

## VMware for Servers

- [VMware vSphere](https://docs.vmware.com/en/VMware-vSphere/index.html) - VMwares virtualization platform.
  - [VMware Cloud Foundation](https://www.vmware.com/products/cloud-foundation.html) - vSphere Enterprise Plus, vSAN Enterprise, NSX Ent Plus (nur Netzwerk), Aria Suite Term Enterprise, Aria Ops for Networks ENT, HCX Enterprise, SDDC Manager, Tanzu Kubernetes Grid und vCenter Server Standard.
  - [VMware vSphere Foundation](https://www.vmware.com/products/vsphere-foundation.html) - vSphere Enterprise Plus, vCenter Standard, Tanzu Kubernetes Grid und Aria Suite Standard. 
  - [VMware vSphere Essentials Plus](https://www.vmware.com) - Server virtualization solution for data center consolidation and enhanced application availability (vSphere Hypervisor (ESXi) and vCenter Standard).
  - [VMware vSphere Standard](https://www.vmware.com/products/cloud-infrastructure/vsphere) - All-in-one solution for small businesses (vSphere Essentials Plus and vCenter Essentials).
  - [VMware vSphere Enterprise Plus](https://www.vmware.com/products/cloud-infrastructure/vsphere) - ESX Enterprise Plus with vCenter Standard (basically without VSAN, Kubernetes and VCF Operations).  

## KVM-based

- [Harvester](https://harvesterhci.io/) - Hyperconverged infrastructure (HCI) solution built for bare metal servers usingopen-source technologies including Linux, KVM, Kubernetes, KubeVirt, and Longhorn. [[docs](https://docs.harvesterhci.io/)]
- [HPE VME hypervisor](https://www.hpe.com/emea_europe/en/hpe-vm-essentials.html) - KVM-based Hypervisor from HPE.
- [Oracle Linux Virtualization Manager](https://www.oracle.com/uk/virtualization/#oracle-linux-kvm) - Open source KVM environment and oVirt-based management with support from Oracle. [[docs](https://docs.oracle.com/en/virtualization/oracle-linux-virtualization-manager/)]
- [Proxmox VE](https://www.proxmox.com/en/proxmox-virtual-environment/overview) - Open-source server management platform for virtualization. It integrates the KVM hypervisor and Linux Containers (LXC). [[docs](https://pve.proxmox.com/pve-docs/), [forum](https://forum.proxmox.com/), [endoflife.date](https://endoflife.date/proxmox-ve)]
- [Nutanix AHV](https://www.nutanix.com/products/ahv) - HCI-optimized Hypervisor included with every Nutanix node [[docs](https://portal.nutanix.com/page/documents/list?type=software&filterKey=software&filterVal=AHV)]
- [Nutanix Community Edition](https://www.nutanix.com/products/community-edition) - Free version of Nutanix AOS intended for internal business operations and non-production use only.
- [Scale Computing HyperCore](https://www.scalecomputing.com/sc-hypercore) - Type 1 (bare metal) hypervisor
- [Softiron VM Squared](https://softiron.com/vmsquared/) - KVM-based hypervisor
- [StorMagic SvHCI](https://stormagic.com/svhci/) - Based on open-source Linux KVM/QEMU technology and Open vSwitch, with storage virtualization provided by SvSAN. [[docs](https://support.stormagic.com/hc/en-gb/sections/18777732563997-StorMagic-SvHCI)]
- [Ubuntu LXD](https://canonical.com/lxd) - Open-source solution for managing virtual machines and system containers. LXD provides both KVM-based VMs and system containers based on LXC.
- [VergeOS](https://www.verge.io/) - VergeOS is an ultraconverged infrastructure (UCI) solution that integrates virtualization, storage, and networking into a single data center operating system. [[docs](https://wiki.verge.io/), [download](https://wiki.verge.io/public/implementation/2-3)]
- [Virtuozzo Hybrid Server](https://www.virtuozzo.com/hybrid-server/) - Bare-metal virtualization solution that includes container virtualization, KVM-based virtual machines, software-defined storage. It runs on top of VzLinux, a RHEL-based Linux distribution. [[docs](https://docs.virtuozzo.com/master/index.html)]

## Xen Hypervisors

- [Citrix Hypervisor](https://www.citrix.com/platform/citrix-app-and-desktop-virtualization/) - High-performance hypervisor optimized for virtual app and desktop workloads and based on the Xen Project hypervisor [deprecated]
- [Vates Virtualization Stack](https://vates.tech/xcp-ng/) - Complete and fully open source virtualization stack.
- [XCP-ng](https://xcp-ng.org/) - User-friendly, high-performance virtualization solution, developed collaboratively for unrestricted features and open-source accessibility. [[docs](https://docs.xcp-ng.org/), [forum](https://xcp-ng.org/forum/), [endoflife.date](https://endoflife.date/xcp-ng)]
- [XenServer (formerly Citrix Hypervisor)](https://www.xenserver.com/) - Server virtualization platform, with all the capabilities required to create and manage a virtual infrastructure. XenServer is optimized for both Windows and Linux virtual servers. [[docs]](https://docs.xenserver.com/en-us/xenserver/8)

## Other Hypervisors

- [Azure Stack HCI](https://azure.microsoft.com/en-us/products/azure-stack/hci) - Azure Stack HCI is a hyperconverged infrastructure solution that VMs or containers and their storage. [[docs](https://learn.microsoft.com/en-us/azure-stack/hci/)]
- [BSD bhyve](https://bhyve.org/) - hypervisor/virtual machine manager available on FreeBSD and illumos. [[docs](https://wiki.freebsd.org/bhyve)]
- [Canonical MicroCloud](https://canonical.com/microcloud) - Small-scale clouds optimised for repeatable and reliable remote deployments. [[docs](https://canonical-microcloud.readthedocs-hosted.com/en/latest/)]
- [Microsoft Windows Server Hyper-V](https://www.microsoft.com/en-us/windows-server) - The Hyper-V role in Windows Server lets you create a virtualized computing environment where you can create and manage virtual machine. [[docs](https://learn.microsoft.com/en-us/windows-server/virtualization/hyper-v/hyper-v-technology-overview)]
- [Triton SmartOS](https://www.tritondatacenter.com/smartos) - Converged Container and Virtual Machine Hypervisor [[downloads](https://docs.smartos.org/download-smartos/), [docs](https://docs.smartos.org/)]

## Orchestration and Cloud Management solutions

## VMware vCenter

- [VMware vCenter](https://www.vmware.com/products/vcenter.html) - Server management software that provides a centralized platform for controlling vSphere environments (part of VMware Cloud Foundation and VMware vSphere Foundation).

## Cloud Management Alternatives

- [Apache CloudStack](https://cloudstack.apache.org/) - Open-source software system designed to deploy and manage large networks of virtual machines, as a highly available, highly scalable Infrastructure as a Service (IaaS) cloud computing platform. [[docs](http://docs.cloudstack.apache.org/en/latest/), [downloads](https://cloudstack.apache.org/downloads)]
- [ManageIQ](https://www.manageiq.org/) - Open source management platform for Hybrid IT. It can manage small and large environments, and supports multiple technologies such as virtual machines, public clouds and containers. [[docs](https://www.manageiq.org/docs/), [downloads](https://www.manageiq.org/download/)]
- [HPE VM Essentials](https://www.hpe.com/emea_europe/en/hpe-vm-essentials.html) - Virtualization management solutiion for HPE VME Hypervisor hosts and vCenter integration.
- [OpenNebula](https://opennebula.io/) - Open Source Cloud Computing Platform to build and manage Enterprise Clouds. It supports multiple virtualization technologies, e.g. VMware, KVM and also LXC and Firecracker. [[docs](https://docs.opennebula.io/), [downloads](https://opennebula.io/use/#download_opennebula), [forum](https://forum.opennebula.io/)]
- [OpenStack](https://www.openstack.org/) - Cloud operating system that controls large pools of compute, storage, and networking resources throughout a datacenter, all managed and provisioned through APIs with common authentication mechanisms.
  - [OpenStack Marketplace](https://www.openstack.org/marketplace/distros/) - List of several openstack distros & appliances
- [Platform9 Private Cloud Director](https://platform9.com/private-cloud-director/) - Offers virtualization administrators a familiar private cloud experience with enterprise-grade features.
- [Platform9 Private Cloud Director Community Edition](https://platform9.com/docs/private-cloud-director/private-cloud-director/getting-started-with-community-edition) - Free, community-supported, and full-featured version of Private Cloud Director
- [Triton DataCenter](https://www.tritondatacenter.com/) - Open source platform that offers unified management of containers and virtualization. [[docs](https://www.tritondatacenter.com/documentation), [downloads](https://www.tritondatacenter.com/downloads)]
- [Virtualizor](https://www.virtualizor.com/) - Web based VPS Control Panel which a user can deploy and manage VPS on servers with a single click. Virtualizor supports KVM, Xen, OpenVZ, Proxmox, Virtuozzo, LXC, etc with an inbuilt hourly billing system. [[docs](https://www.virtualizor.com/docs/)]
- [VMmanager](https://www.ispsystem.com/vmmanager) - Platform for virtualization management. The platform allows to manage multiple clusters, create virtual machines, install OS, and run scripts. [[docs](https://docs.ispsystem.com/vmmanager-admin)]
- [Xen Orchestra](https://xen-orchestra.com/) - Management interface for XenServer/XCP-ng [[docs](https://xen-orchestra.com/docs/)]
  
# Cloud

## Managed VMware by Cloud Providers

- [Google Cloud VMware Engine](https://cloud.google.com/vmware-engine) - VMware Engine is a fully managed service that lets you run the VMware platform in Google Cloud.
- [VMware Cloud on AWS](https://aws.amazon.com/vmware/) - Managed VMware by Amazon.
- [VMware on Azure](https://azure.microsoft.com/en-us/products/azure-vmware) - Managed VMware by Microsoft.
- [Oracle Cloud VMware Solution](https://www.oracle.com/cloud/compute/vmware/) - VMware cloud environment based on VMware Cloud Foundation (VCF).

# Contributing

Contributing guidelines can be found [here](https://github.com/alexgoesgit/awesome-vmware/blob/main/Contributing.md).

# License

This list is under the Creative Commons Attribution-ShareAlike 1.0 Generic License.
Terms of the license are summarized [https://creativecommons.org/licenses/by-sa/1.0/](https://creativecommons.org/licenses/by-sa/1.0/).
