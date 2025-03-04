# Azure VM Image Builder Quick QuickStarts

Welcome to the Azure VM Image Builder QuickStarts, these are some key scenarios you can test using Azure CloudShell in the Portal, or Azure CLI.

**First time using Image Builder??** 

Get started with the short walkthrough video below, or go straight to the Quick Starts below.

[<img src="./mediumVideoplay.png" alt="drawing" width="450"/>
](https://youtu.be/IgKARHm5Yus)

**Second time using Image Builder??**  
On the 12th March we have just released a whole wave of New Features and API version, see here for [details](/aibMarch2019Update.md).


1. [Create a Custom Linux Image from an Azure Platform Vanilla OS Image.](./0_Creating_a_Custom_Linux_Managed_Image/readme.md)

2. [Create a Custom Windows Image from an Azure Platform Vanilla OS Image.](./0_Creating_a_Custom_Windows_Managed_Image/readme.md)

3. [Create a Custom Linux Image, then Distribute and Version over Multiple Regions.](./1_Creating_a_Custom_Linux_Shared_Image_Gallery_Image/readme.md)

4. [Creating a custom RHEL image using a RHEL ISO where you can use eligible Red Hat licenses.](./2_Creating_a_Custom_Image_using_Red_Hat_Subscription_Licences/readme.md)  

5. [Create a Custom Linux Image from an Existing Custom Managed Image.](./5_Creating_a_Custom_Image_from_Custom_Managed_Image/readme.md)

6. [Create a Custom Linux Image and Export to VHD](./4_Creating_a_Custom_Linux_Image_to_VHD/readme.md)

7. [Troubleshooting Guide & Log Locations](https://github.com/danielsollondon/azvmimagebuilder/blob/master/troubleshootingaib.md)

** Note: The quickstarts are designed to show you the different types of configuration you can have, many of these are supported on Windows and Linux, there will be more Windows examples soon!!

Any questions or feedback, please [here](https://aka.ms/aibfeedback), the Azure Image Builder Dev team is there during the week, Pacific time.

These are designed to get you started quickly, where at a minimum you just need to supply your subscriptionID (except for the RHEL example), showing you how the Azure VM Image Builder can be used to build images to meet these requirements:

* Security & Compliance - e.g. building corporate golden images, that meet your organizations security and compliance requirements.
* Licensing - e.g. building RHEL images using your eligible Red Hat Subcription licenses.
* Performance - e.g. creating images with applications pre-installed
* Management - e.g. managing images updates and global region replication

## Next Steps
* Want to learn more???
    * Explore the detailed documentation in [MS Docs](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/image-builder-json) (Files).

* Want to try more???
* Image Builder does support deployment through Azure Resource Manager, see here in the repo for [examples](https://github.com/danielsollondon/azvmimagebuilder/tree/master/solutions/4_Using_ENV_Variables), you will also see how you can use a RHEL ISO source too, and manu other capabilities.
