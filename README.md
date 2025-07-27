# data-costing-system
A Data Costing System (DCS) is meant to distribute data related costs across the driving cost centers, abiding by contractual agreements and implementing automated cost down measures (such as data tiering). 

## Architecture

From a domain perspective, the user, data, and requirements domains are joined to form the system domain. 
![DCS Architecture Diagram](/data-costing-system/architecture/figures/VisualArch.png)

The system admin holds end to end (E2E) responsibility of the data costing system.
- The system domain is integrated with SAP for costing and SNMP for notification. 
- The data domain is controlled via data admins, operating the storage systems. 
- The system interfaces with the data domain to compress and reallocate files for cost savings measures. 
- Within the requirements domain, legal frameworks are possessed to extract requirements. 
- Requirements are enriched by share admins and provided to the system for operations. 