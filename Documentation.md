# ERP TO ATP INTEGRATION DOCUMENTATION


## OBJECTIVE

This document outlines a step-by-step guide on how to integrate ERP and ATP in Oracle Integration Cloud (OIC).
The purpose of the integration is to create a purchase order in ERP, hash the purchase order details, and send the actual purchase order details along with the hashed values to ATP. 


## COMPONENTS COVERED

* How to create and configure ERP and ATP connections in OIC
* How to register an OIC instance in SOA Composer
* How to create an integration
* Assign variables
* Map attributes between ERP and ATP
* How to register a custom script in OIC Libraries 
* How to call a custom script as a function in OIC integration orchestration 
* How to activate and monitor integration
* How to test integration using SQLDeveloper


## TOOLS & APPLICATIONS USED

* Oracle Integration Cloud Instance
* ERP Application
* SQLDeveloper Version 18.4.0.376



Let's start by logging into the Oracle Integration Cloud platform.
![Homepage](images/homepage1.1.png)