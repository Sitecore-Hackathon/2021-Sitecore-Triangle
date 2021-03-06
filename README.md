<img src="https://github.com/Sitecore-Hackathon/2021-Sitecore-Triangle/blob/main/docs/images/Team-Sitecore%20Triangle.png" alt="Sitecore Triangle Hackathon Logo" title="Sitecore Triangle Hackathon Logo" /><br />

# Sitecore Triangle

Sitecore Hackathon 2021 entry by Team **Sitecore Triangle**

Topic: **Best use of SPE to help Content authors and Marketers.**

Video Link: **[Sitecore Hackathon >> 2021 Sitecore Triangle Video](https://drive.google.com/file/d/1AAE7gWBb5Zql75QrpNLbU1mexKAMzSID/view?usp=drivesdk)**

---

The **Sitecore Triangle** team picked-up the above mentioned topic and used following products/technologies:

* **[Sitecore Experience Platform 10.1](https://dev.sitecore.net/Downloads/Sitecore_Experience_Platform/101/Sitecore_Experience_Platform_101.aspx/)**
* **[Sitecore PowerShell Extensions 6.2.0.34182](https://doc.sitecorepowershell.com/)**

## Module Purpose
The purpose of **Display Help Section Field Details** is to list down **Help Section** field details like Long description, Short description and Help link if particular item template already set those fields.

If any template which not having any custom fields then items created from those templates would not be visible in the listing.

This script will be present in **Context Menu** as **Display Help Section Fields** and *if you select any item then it will traverse all the items underneath*. When **Display Help Section Field Details** displayed then we have to select the **WEBSITE** node from the *Content Tree*.

<img src="https://github.com/Sitecore-Hackathon/2021-Sitecore-Triangle/blob/main/docs/images/2021-Sitecore-Triangle%20-1.png" alt="2021-Sitecore-Triangle" title="2021-Sitecore-Triangle" style="max-width:100%;">

The **Display Help Section Field Details** script will be *avaliable to all items in content tree and you can execute it from any item, and you can select particular site node from the content tree*.

The idea here is to use **[Sitecore PowerShell Extensions](https://doc.sitecorepowershell.com/)** module to:
* Help Content Authors to identify the details about all Help Section fields
* With this **Display Help Section Field Details** script *Content Authors can easily identify that which Custom Template field not contains the values in Help Section Fields*
* At any given point, Content Author can use **Display Help Section Field Details** script from **Context Menu >> Display Help Section Fields**
* This **[Sitecore PowerShell Extensions](https://twitter.com/hashtag/SCHackathon)** can be reuse on any Sitecore instance
* Quickly get listing of Help Section fields of your websites
* Greatly reduce the time needed to manually go to each custom template and verify
#### Features include:
* Sitecore Powershell Script
* **Display Help Section Field Details** scrip will provide:
    * Selection of Website node from the Content Tree
    * Listing of Help Section Fields of Custom Templates
* With **[Sitecore PowerShell Extensions](https://doc.sitecorepowershell.com/)** OOTB functionality you can export content to CSV, JSON, etc.
* Content Author can access SPE scripts from any item in Content Tree

#### Limitations:
* Not accessing the Datasource item from the page renderings
* Listing of Site nodes to process the underneath items

## Module Sitecore Hackathon Category
**Best use of SPE to help Content authors and Marketers**

## How does the end user use the Module?
#### Pre-requisites
This module depends on the following
* Sitecore Experience Platform 10.1
* Sitecore Powershell Extensions (SPE)

#### Configuration/Setup
* Download the Sitecore Package (https://github.com/Sitecore-Hackathon/2021-Sitecore-Triangle/blob/main/docs/images/2021-Sitecore-Triangle-1.0.zip) which contains:
    * Required Script which created in **Master DB** at **/sitecore/system/Modules/PowerShell/Script Library/Sitecore Triangle/Content Editor/Context Menu/Display Help Section Field Details**
     <img src="https://github.com/Sitecore-Hackathon/2021-Sitecore-Triangle/blob/main/docs/images/2021-Sitecore-Triangle-2.png" alt="2021-Sitecore-Triangle" title="2021-Sitecore-Triangle" style="max-width:100%;" />
    * Required Content Editor Content Menu Item created in **Core DB** at **/sitecore/system/Modules/PowerShell/Script Library/Sitecore Triangle/Content Editor/Context Menu/Display Help Section Field Details**
         <img src="https://github.com/Sitecore-Hackathon/2021-Sitecore-Triangle/blob/main/docs/images/2021-Sitecore-Triangle-3.png" alt="2021-Sitecore-Triangle" title="2021-Sitecore-Triangle" style="max-width:100%;" />
* Install the Downloaded Sitecore Package
* After installation you will see following items in the content tree:
    * **Master DB >> Sitecore Powershell Extensions (SPE) Script:** <br/>
      <img src="https://github.com/Sitecore-Hackathon/2021-Sitecore-Triangle/blob/main/docs/images/2021-Sitecore-Triangle-2.png" alt="2021-Sitecore-Triangle" title="2021-Sitecore-Triangle" style="max-width:100%;" /><br />
    * **Core DB >> Content Editor >> Context Menu Item:** <br/>
         <img src="https://github.com/Sitecore-Hackathon/2021-Sitecore-Triangle/blob/main/docs/images/2021-Sitecore-Triangle-3.png" alt="2021-Sitecore-Triangle" title="2021-Sitecore-Triangle" style="max-width:100%;" />
    
   

## Screenshots
#### Access Script on any item in Content tree by right click
<img src="https://github.com/Sitecore-Hackathon/2021-Sitecore-Triangle/blob/main/docs/images/2021-Sitecore-Triangle-4.png" alt="2021-Sitecore-Triangle" title="2021-Sitecore-Triangle" style="max-width:100%;" /><br />

#### Once Click on the **Display Help Section Field Details**, it will open dialog box to select Site node from the Content tree
<img src="https://github.com/Sitecore-Hackathon/2021-Sitecore-Triangle/blob/main/docs/images/2021-Sitecore-Triangle-5.png" alt="2021-Sitecore-Triangle" title="2021-Sitecore-Triangle" style="max-width:100%;" /><br />

#### Select the Site node and click on **Execute** button, it will open Help Section field listing
<img src="https://github.com/Sitecore-Hackathon/2021-Sitecore-Triangle/blob/main/docs/images/2021-Sitecore-Triangle-6.png" alt="2021-Sitecore-Triangle" title="2021-Sitecore-Triangle" style="max-width:100%;" /><br />

## Sitecore Powershell Script >> [**Display Help Section Field Details**](https://gist.github.com/AmitKumar-AK/6a01489c357393390bbba5168d7bf611)

## Video

[Download video](https://drive.google.com/file/d/1AAE7gWBb5Zql75QrpNLbU1mexKAMzSID/view?usp=drivesdk).

[![Sitecore Hackathon >> 2021 Sitecore Triangle Video Embedding Alt Text](https://github.com/Sitecore-Hackathon/2021-Sitecore-Triangle/blob/main/docs/images/2021-Sitecore-Triangle-7.png)](https://drive.google.com/file/d/1AAE7gWBb5Zql75QrpNLbU1mexKAMzSID/view?usp=drivesdk)
