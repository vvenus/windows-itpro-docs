---
Description: Create packages for multiple operating systems or languages
ms.assetid: 44051f9d-63a7-43bf-a427-d0a0a1c717da
ms.prod: IE11
ms.mktglfcycl: deploy
ms.sitesec: library
title: Create packages for multiple operating systems or languages (Internet Explorer 11 for IT Pros)
---

# Create packages for multiple operating systems or languages
You'll create multiple versions of your custom browser package if:

-   You support more than 1 version of Windows®.

-   You support more than 1 language.

-   You have custom installation packages with only minor differences. Like, having a different phone number.

 ![](images/wedge.gif) **To create a new package**

1.  Create an installation package using the Internet Explorer Customization Wizard 11, as described in the [Internet Explorer Customization Wizard 11 options](http://go.microsoft.com/fwlink/p/?linkid=328022) topic.

2.  Go to your **CIE/Custom** folder and rename the `Install.ins`file. For example, if you need a version for employees in Texas, rename the file to Texas.ins.

3.  Run the wizard again, using the Custom folder as the destination directory.<p>
**Important**<br>
Except for the **Title bar** text, **Favorites**, **Links bar**, **Home page**, and **Search bar**, keep all of your wizard settings the same for all of your build computers.

     

 

 


