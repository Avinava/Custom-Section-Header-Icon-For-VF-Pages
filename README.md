Custom Section Header Icons For VF Pages
=========

A custom Section Header component. Replacement of standard '&lt;apex:sectionHeader/&gt;'. This component is similar to the standard section header but here you can select your own icon for the header. 

Description
-


Ever used a Section header in VF Page which is not exposed as a tab?

You will notice a weird thing,You cant actually control the icon that appears in the section header and it puts a default image(Home Icon) there. To replace the Icon you have to either provide a tabstyle or create a new tab for the VF Page or have to use a standard controller.

Solution
-
Use this custom component and specify the desired Icon url.

Version
-

1.0


Installation
--------------

1.Install the Package from https://login.salesforce.com/packaging/installPackage.apexp?p0=04t90000000M9Ul


Usage
-
Here is a sample code which shows how to uses the Standard Salesforce Account icon in the custom section header.

        <c:sectionHeader iconsrc="/img/icon/accounts32.png" title="Visualforce Auto-Complete Component" subTitle=" Auto-Complete Demo"/> 

  
    
