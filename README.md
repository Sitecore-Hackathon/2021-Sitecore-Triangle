
<img src="https://github.com/Sitecore-Hackathon/2021-Sitecore-Triangle/blob/main/docs/images/Team-Sitecore%20Triangle.png" alt="Sitecore Triangle Hackathon Logo" title="Sitecore Triangle Hackathon Logo" /><br />

# Sitecore Triangle

Sitecore Hackathon 2021 entry by Team **Sitecore Triangle**

Topic: **Best use of SPE to help Content authors and Marketers.**

Video Link:

---

The **Sitecore Triangle** team picked-up the above mentioned topic and used following products/technologies:

* **[Sitecore Experience Platform 10.1](https://dev.sitecore.net/Downloads/Sitecore_Experience_Platform/101/Sitecore_Experience_Platform_101.aspx/)**
* **[Sitecore PowerShell Extensions 6.2.0.34182](https://doc.sitecorepowershell.com/)**

## Module Purpose
The purpose of **Display Help Section Field Details** is to list down **Help Section** field details like Long description, Short description and Help link if particular item template already set those fields.

If any template which not having any custom fields then items created from those templates would not be visible in the listing.

This script will be present in **Context Menu** as **Display Help Section Fields** and *if you select any item then it will traverse all the items underneath*. When **Display Help Section Field Details** displayed then we have to select the **WEBSITE** node from the *Content Tree*.

<img src="https://github.com/Sitecore-Hackathon/2021-Sitecore-Triangle/blob/main/docs/images/2021-Sitecore-Triangle%20-1.png" alt="2021-Sitecore-Triangle" title="2021-Sitecore-Triangle" style="max-width:100%;">

The **Display Help Section Field Details** script will be avaliable to all items in content tree and you can execute it from any item, and you can select particular site node from the content tree.
template user interactive and not easy to maintain. The idea here is to use **[Sitecore Experience Accelerator](https://doc.sitecore.com/users/sxa/17/sitecore-experience-accelerator/en/introducing-sitecore-experience-accelerator.html)** module to:
* Help content teams create, edit, and deploy web content across channels in less time
* Easily change page components using drag-and-drop functionality
* Enjoy a CMS with WYSIWYG (What You See Is What You Get) editing
* Reuse pre-built components, templates, and layouts
* Quickly get your websites up and running
* Greatly reduce the time needed for custom development
#### Features include:
* Sample Site
* **Home Page** will provide:
    * Promo/Hero Banner: Content Author can setup rich content
    * Listing of Last 03 Hackathon events
* Content Author can create **Judge details (rich text)** for every year Hackathon event
* Content Author can manage the **Hero banner/Promo Content** for the Home Page
* End User can submit the **Hackathon registration request** via **Custom Hackathon Registration Form**
* **Hackathon Registration Form** having **time limit validation** for Hackathon registration and after that user will see the custom message and this message can be setup by the Content Author
* Once **Hackathon Registration Form** submitted by the End user then **Thank You message** would be visible to user and this message can be setup by the Content Author
* After submission of **Hackathon Registration Form** team details would be stored in the **MASTER DB** with this Content Author/Admin can review the content and publish after validaiton to **WEB DB**
* End user can view **listing of Hackathon's**
* Each year **Hackathon** will provide:
    * Hackathon Details: Content Author can setup rich content
    * Listing of Teams participating in Hackathon
    * Listing of Judge details (rich text) in Hackathon

#### Limitations:
* No valiation on Form fields
* All fields are mandatory currently
* No autmation on publishing
* No registration confirmation email
* No Personalization
* Currently each Hackathon page displaying listing of Year 2020 Participants only, and this can be avoided by creating custom query and use in the PageList component
* Site User Interface: We have tried our best to on UI part but can't compete with UI developer :)


## Module Sitecore Hackathon Category
**Sitecore Hackathon Website – This idea is sooo meta! Several years have passed with the current version and it’s in need of a refresh.**

## How does the end user use the Module?
#### Pre-requisites
This module depends on the following
* Sitecore 9.3 Initial Release
* Sitecore Powershell Extensions (SPE)
* Sitecore Experience Accelerator

#### Configuration/Setup
* Download the Sitecore Package (https://github.com/Sitecore-Hackathon/2020-Sitecore-Triangle/blob/master/documentation/SitecoreHackathon2020.zip) which contains:
    * Required Template
    * Required Content Tree items
* Install the Downloaded Sitecore Package
* After installation you will see following items in the content tree:
    * **Site Templates:** <br/>
      <img src="https://github.com/Sitecore-Hackathon/2020-Sitecore-Triangle/blob/master/documentation/Sitecore SXA Site Templates.png" /><br />
    * **Site:** <br/>
      <img src="https://github.com/Sitecore-Hackathon/2020-Sitecore-Triangle/blob/master/documentation/Sitecore SXA Site.png" /><br />
    * **Media Library:** <br/>
      <img src="https://github.com/Sitecore-Hackathon/2020-Sitecore-Triangle/blob/master/documentation/Sitecore SXA Media Library.png" /><br />
    * **Page/Partial Design:** <br/>
      <img src="https://github.com/Sitecore-Hackathon/2020-Sitecore-Triangle/blob/master/documentation/Sitecore SXA Page-Partial Design.png" /><br />
* Each Year following configuration/item needs to be created/changes:
    * Create the New Year item at **/sitecore/content/Sitecore/Hackathon/HackathonTeams/** like **2021**
    * Inside new year folder i.e. 2021 (which created above), create **Judge Folder** and then create required **Judge** items.
    * Inside new year folder i.e. 2021 (which created above), create **Participant Folder**.
    * Copy path of newly created **Participant Folder** and goto **/sitecore/content/Sitecore/Hackathon/Data/HackathonTeam/HackathonRegistration** and past the url. This url used **Custom Hackathon Registration Form** to store the participant details.
    
   

## Screenshots
#### Home Page
<img src="https://github.com/Sitecore-Hackathon/2020-Sitecore-Triangle/blob/master/documentation/HomePage.jpg" /><br />

#### Hackathon Registration Form
<img src="https://github.com/Sitecore-Hackathon/2020-Sitecore-Triangle/blob/master/documentation/Hackathon-RegistrationForm.png" /><br />

#### Listing of Hackathon's
<img src="https://github.com/Sitecore-Hackathon/2020-Sitecore-Triangle/blob/master/documentation/Hackathon-Listing.png" /><br />

#### Hackathon Details
<img src="https://github.com/Sitecore-Hackathon/2020-Sitecore-Triangle/blob/master/documentation/Hackathon-Details.png" /><br />

## Video

[Download video](https://drive.google.com/file/d/1yxxlIfTJO9idTdkE40c6QIHNuVHTVa_V/view?usp=drivesdk).

[![Sitecore Hackathon Video Embedding Alt Text](https://github.com/Sitecore-Hackathon/2020-Sitecore-Triangle/blob/master/documentation/VideoThubnailImage.jpg)](https://drive.google.com/file/d/1yxxlIfTJO9idTdkE40c6QIHNuVHTVa_V/view?usp=drivesd)
