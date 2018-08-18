Introduction

F5® BIG-IP® Cloud EditionTM was built to help network operations teams and applications teams collaborate more effectively in the rapid delivery of secure, appropriately supported applications. BIG-IP Cloud Edition simplifies and centralizes core device and app services management functions like setup, licensing, upgrades, analytics, and scaling. Operations teams can easily define a self-service catalog of application services that developers can then access, on demand, via a dashboard or API call. These services are defined, updated, and deployed for each application in contrast to the traditional, consolidated model in which a single Application Delivery Controller (ADC) supports multiple applications.

Infrastructure Components

1) BIG-IP Per-App virtual editions (VEs), each dedicated to a single application.

2) F5 BIG-IQ® Centralized Management which provides management, visibility, and licensing services across all instances—no matter where they are located.

Logical Components

1) Cloud providers - BIG-IP Cloud Edition supports deployment and auto scale of BIG-IP instances on the following cloud platforms:

. Amazon Web Services (AWS)
 
. VMware vCenter-based private clouds

2) Device templates - Device templates define all infrastructure-level characteristics (time zone, DNS, hostname, accounts, NTP, licensing, networking, etc.) that are required to deploy a BIG-IP device.

3) Service scaling groups - When application services are deployed from an application template and a service scaling group is selected as the target, BIG-IP Cloud Edition manages the availability and elastic scaling of resources to deliver the services, plus manages the lifecycle and upgrade process for the BIG-IP devices delivering those services.

4) Application templates - Application templates define the application delivery and security services that will be deployed for an application, including all BIG-IP objects such as virtual servers, profiles, monitors, SSL certificates, security policies, etc.