# system center configuration manager

[![system center configuration manager](gett-detail.png)](https://github.com/techwhoop/system.center.configuration.manager/)

Microsoft Endpoint Configuration Manager, formerly known as System Center Configuration Manager (SCCM), is a Windows-centric endpoint management tool for devices within an Active Directory domain. Historically deployed on prem on a Windows Server, SCCM can now also be deployed as cloud-hosted within Azure.

The paid lifecycle management solution from Microsoft keeps track of a network’s inventory, assists in application installation, and deploys updates and security patches across a network.

## How does system center configuration manager work?

At the highest level, SCCM is installed on a Windows Server to help organizations manage endpoints. Generally, it requires an agent on the managed endpoints to work. And typically devices outside the corporate network need to connect back via VPN to receive patches, configuration updates, software, and more (unless the organization has also set up cloud management gateway (CMG) servers to help reduce VPN dependence with SCCM).

Underneath SCCM, WSUS helps cache and distribute patches to managed devices. Also, an SQL database is needed to store information for SCCM. If you want to learn more about WSUS, review our first blog in the tooling series.

## Which operation systems are covered under system center configuration manager?

* Windows 8.1, 10, 11
* Windows Server 2012-2022 (including core)
* Windows devices in Azure Virtual Desktop
* Windows embedded devices (IoT), think point of sales and other types of lightweight devices
* macOS Mojave, Catalina, and Big Sur – Deprecated in January 2022 in favor of migrating management to Intune.

## features of Microsoft system center configuration manager

* Windows management -- to keep pace with updates to Windows 10.
* Endpoint protection -- to provide identification and malware protection.
* Reporting -- to present information on users, hardware, software, applications and software updates.
* Operating system (OS) deployment -- to distribute operating systems to devices in an enterprise.
* Software update management --which allows users administrators to deliver and manage updates to devices across an enterprise.
* Application delivery --which allows administrators to deliver an application to all devices across an enterprise.
* Health monitoring -- which shows client activities and health in the console, and can alert users if health statistics decrease past a specified level.
