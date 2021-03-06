# AEC Openshift Lab Guide

<!-- TOC -->
1. [Workshop Architecture and Objective](#workshop-architecture-and-objective)
  * [Workshop Architecture Before the Performing Labs](#workshop-architecture-before-the-performing-labs)
  <a href="https://github.com/ShivaniThadiyan/DocRepo/blob/master/workshoparchitecture.md">workshoparchitecture.md</a>
  * [Labs Objective](#labs-objective)
  * [Workshop Architecture after deploying ARM Template](#workshop-architecture-after-deploying-ARM-template)
 2. [Lab 1: Introduction to Azure Portal](#lab-1:introduction-to-azure-portal)
  * [Lab Overview](#lab-overview)
  * [Prerequisites](#Prerequisites)
  * [Time Estimate](#time-estimate)
  * [Exercise 1: Log into your Azure Portal](#exercise-1:log-into-your-azure-portal)
  * [Exercise 2: Verify access to the Subscription](#exercise-2:verify-access-to-the-subscription)
 3. [Lab 2: Deploying Open Shift cluster using ARM templates](#lab-2:deploying-open-shift-cluster-using-ARM-templates)
  * [Lab Overview](#lab-overview)
  * [Prerequisites](#Prerequisites)
  * [Time Estimate](#time-estimate)
  * [Exercise 1: Create an Azure AD Application](#exercise-1:create-an-azure-AD-application)
  * [Exercise 2: Create a Keyvault](#exercise-2:create-a-keyvault)
  * [Exercise 3: Deploy Openshift Cluster using ARM Template](#exercise-3:deploy-openshift-cluster-using-ARM-template)
  * [Exercise 4: Configure Azure AD Authentication](#exercise-4:configure-azure-AD-authentication)
  * [Exercise 5: Deploy a 2 Tier Node JS Application on Open Shift](#exercise-5:Deploy-a-2-tier-node-JS-application-on-open-shift)
  * [Exercise 6: Integrate ACR with OpenShift](#exercise-6:integrate-ACR-with-openShift)
<!-- /TOC -->

## Workshop Architecture and Objective
### Workshop Architecture Before the Performing Labs
As part of Hand on Lab, you will get following details via email. Make a note of these details as these shall be leveraged throughout the lab exercise
 * [Azure Access: Azure Username and Password (Default Password, Change at first login)](#azure-access:azure-username-and-password-default-password,Change-at-first-login)
 
## Labs Objectives
During this lab, you will deploy Open Shift cluster on Azure and integrate Azure AD Authentication and Azure Container Registry into Open Shift. Detailed steps to achieve this is as follows.
  * [Get Familiar with Azure Portal and Ansible Tower UI](#get-familiar-with-Azure-Portal-and-Ansible-Tower-UI)
  * [Create an Azure AD Application for Authentication](#create-an-Azure-AD-Application-for-Authentication)
  * [Create a key vault to store SSH Key](#create-a-key-vault-to-store-SSH-Key)
  * [Deploy Open Shift using ARM Template](#deploy-Open-Shift-using-ARM-Template)
  * [Configure Azure AD Authentication](#configure-Azure-AD-Authentication)
  * [Deploy 2 Tier App on Open Shift](#deploy-2-tier-app-on-open-shift)

## Workshop Architecture after deploying ARM Template
Following illustrates the architecture in your Azure deployment after completion of exercise’s part of workshop.

<img src="https://raw.githubusercontent.com/ShivaniThadiyan/DocRepo/master/Images/img1.jpg"/>

## Lab 1: Introduction to Azure Portal
### Lab Overview
This lab will take you through Azure login and portal experience.

### Prerequisites
* Windows or a Mac machine with HTML5 supported browser such as Microsoft Edge, Internet Explorer, Chrome or Firefox
* You should have registered in the [training portal](https://azuretraining.spektrasystems.com) and received the confirmation message with the credentials to login to the [Azure portal](https://Portal.azure.com).

<img src="https://github.com/ShivaniThadiyan/DocRepo/blob/master/Images/image2.png"/>

### Time Estimates
10 minutes

### Exercise 1: Log into your Azure Portal
In this exercise, you will log into the Azure Portal using your Azure credentials.
1. Launch a browser and Navigate to [Azure portal](https://Portal.azure.com). Provide the credentials that you received via email. Click on Sign In.
<img src="https://github.com/ShivaniThadiyan/DocRepo/blob/master/Images/login.png"/>

*Note : At the first login, you may have to change the password, if asked for.

2. Enter a new password. Then select Update password and sign in.
<img src="https://github.com/ShivaniThadiyan/DocRepo/blob/master/Images/UpdatePasswd.png"/>

3.	Now, you will be directed to the Azure Dashboard
<img src="https://github.com/ShivaniThadiyan/DocRepo/blob/master/Images/Portal.png"/>

### Exercise 2: Verify access to the Subscription
In this exercise, you will verify the type of role you are assigned in this Subscription.
1. Launch a browser and Navigate to [Azure portal](https://Portal.azure.com). Provide the credentials that you received via email. 
<img src="https://github.com/ShivaniThadiyan/DocRepo/blob/master/Images/LoginPortal.png"/>

2.	Click on Microsoft Azure  at the top left corner of the screen, to view the Dashboard.
<img src="https://github.com/ShivaniThadiyan/DocRepo/blob/master/Images/click-microsoft-azure.png"/>

3.	To toggle show/hide the Portal menu options with icon, Click on the Show Menu button.
<img src="https://github.com/ShivaniThadiyan/DocRepo/blob/master/Images/click-showMenu.png"/>

4.	Click on the Resource groups button in the Menu navigation bar to view the Resource groups blade.
<img src="https://github.com/ShivaniThadiyan/DocRepo/blob/master/Images/click-resource-groups.png"/>

5.	You will see a Resource Group which you have access to, click on it.
<img src="https://github.com/ShivaniThadiyan/DocRepo/blob/master/Images/click-on-RG.png"/>
*Note: The Resource Group shown here is for demo purpose only. Actual name of the Resouce Group that you see may differ.

6.	From the Resource Group blade that come up, Select the Access Control ( IAM ) which is on the left side of the blade.
<img src="https://github.com/ShivaniThadiyan/DocRepo/blob/master/Images/click-IAM.png"/>

7.	In the new blade that come up, you can see the role that is assigned to you.
<img src="https://github.com/ShivaniThadiyan/DocRepo/blob/master/Images/see-roles.png"/>

# Lab 2: Deploying Open Shift cluster using ARM templates
### Lab Overview
In this lab, you will learn how to deploy the Open Shift Cluster on Azure using ARM templates.

### Prerequisites
* Lab 1 must be completed

### Time Estimates
45 minutes

### Exercise 1: Create an Azure AD Application
In this exercise, you will create an Azure AD App and retrieve the Client ID and Client secret values.
1. Launch a browser and Navigate to [Azure portal](https://Portal.azure.com). Provide the credentials that you received via email. 
<img src="https://github.com/ShivaniThadiyan/DocRepo/blob/master/Images/LoginPortal.png"/>. 

























































