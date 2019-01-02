# tenant-configurator
A service for SAP Business One Cloud Partners to accelerate volume business for pre-configured solutions

## Solution Brief and Target Audience 
This solution is targeted to SAP Business One partners operating on the cloud (private cloud), helping them to accelerate their volume business for pre-configured solutions, such as:
* OEM deals
* Packaged solutions (e.g., Starter Package)
* Vertical/Micro-vertical solutions

The solution automates the tenant provisioning in the cloud without manual intervention of the cloud operator/partner. This enables the partners to streamline the on-boarding process of their customers and by that increase their volume business.

## How to use the solution 
The solution is composed from 2 web user interfaces: one user interface is used by the _**cloud operator**_ to configure the tenant provisioning parameters and the second one integrates with the on-boarding process of the partner’s customers and is used by the _**customer**_. The user interface is written in java script (based on SAPUI5) and it interacts with a server-side component, written in NodeJS. 
There are 3 main steps to work with the solution:
* Prepare Pre-configured template, using the **Tenant Configurator wizard**
* Build on-boarding web pages  
* Integrate **customer configuration page** in the on-boarding pages 

More details can be found in the User guide under the Documentation folder.  

## Prerequisites
SAP Business One Cloud, PL 12 or lower. In addition, you need [nodeJS](https://nodejs.org/en/) to be installed on the same machine you install the server-side of the solution. 

## Installation 
The solution is written in Java script, so you can easily deploy it and customize it – in order to see how to install it, please refer to the User Guide under the Documentation folder. 

## License 
The Tenant Configurator is released under the terms of the MIT license. See LICENSE for more information or see https://opensource.org/licenses/MIT
