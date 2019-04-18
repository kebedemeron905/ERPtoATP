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

* Oracle Integration Cloud 
* ERP Application
* SQLDeveloper Version 18.4.0.376



## 1.1: CREATE A ERP CONNECTION 

#### 1.1.1: Log into the Oracle Integration Cloud platform <br/>
![Homepage](Images/image1.1.png)


#### 1.1.2: Click on Integrations from the left side menu <br/>
![Homepage](Images/image1.2.png)<br/>

#### 1.1.3: Click on Connections from the left side menu <br/>
![Homepage](Images/image1.3.png)<br/>

#### 1.1.4: Click on Create from the top right corner <br/>
![Homepage](Images/image1.4.png)<br/>

#### 1.1.5: Search "Oracle ERP Cloud" in the Create Connection - Select Adapter dialogue box, and click on select <br/>
![Homepage](Images/image1.5.png)<br/>

#### 1.1.6: Enter a connection name, select Trigger and Invoke for Role, and click create <br/>
![Homepage](Images/image1.6.png)<br/>

#### 1.1.7: Click on Configure Connectivity <br/>
![Homepage](Images/image1.7.png)<br/>

#### 1.1.8: Provide the ERP Services Catalog WSDL URL, and the ERP Events Catalog URL, and click OK <br/>
![Homepage](Images/image1.8.png)<br/>

#### 1.1.9: Click on Configure Security <br/>
![Homepage](Images/image1.9.png)<br/>

#### 1.1.10: Enter ERP credentials, and click OK <br/>
![Homepage](Images/image1.10.png)  <br/>

#### 1.1.11: Click on Test <br/>
![Homepage](Images/image1.11.png) <br/>

#### 1.1.12: Make sure the test is successful and shows 100%; click Save, and close. <br/>

Note: Make sure you save first before closing. <br/>
![Homepage](Images/image1.12.png) <br/>

#### 1.1.13: You'll see your ERP adapter appear under the list of connections <br/>
![Homepage](Images/image1.13.png) <br/>

***

## 1.2: CREATE A ATP CONNECTION 

#### 1.2.1: Click on Create from the top right corner <br/>
![Homepage](Images/image1.13.png)