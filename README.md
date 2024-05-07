<p align="center">
<img src="assets/elastix-logo.png" alt="Elastix Logo" />
</p>

# PBX Deployment for General Contractor
Deployed Elastix PBX to replace a Centrex system significantly reducing PSTN costs for the business. The implementation provided the contractor with IVR, call routing, and voicemail features enabling them to manage inquiries seamlessly, optimize operations, and minimize expenses.

## Environments and Technologies Used

- Elastix ELX-025 IP PBX Appliance
    - 1U rack mountable chassis IP PBX 
        - 1.8GHz CPU 
        - 1 GB RAM 
        - 250GB HDD
- Grandstream GXP2120
- Cisco SPA122 ATA
- Callcentric Internet Phone Service

## Operating Systems Used

- Elastix 2.4

## High-Level Deployment and Configuration Steps

- Access the Elastix web interface using the default user name and password
- Change the admin password in System | User Management
- Configure the IP address, subnet mask, default gateway, and DNS settings in System | Network
- Add SIP extensions for each user or device that needs to connect to the system in PBX | Extensions
   - Configure extension settings such as name, number, password, and voicemail options
   - Configure IP phones with the defined extension settings
   - Configure the ATA to facilitate fax machine connectivity
- Add SIP trunks to external VoIP providers or PSTN gateways in PBX | Trunks
   - Configure trunk settings such as provider details, authentication, and dialing rules.
- Create inbound routes to specify how incoming calls are routed based on DID in PBX | Inbound Routes
- Create outbound routes to specify which trunk to use for each route in PBX | Outbound Routes
- Configure IVR, Ring Groups, Follow Me, and IVR features







<h2>Architecture Diagram</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
