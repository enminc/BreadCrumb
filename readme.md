BreadCrumb Extra for MODx Revolution
=======================================


**Author:** Benjamin Vauchel <contact@omycode.fr>


Bugs and Feature Requests: https://github.com/omycode/breadcrumb

Breadcrumb is a snippet for MODx Revolution, inspired by the Jared's BreadCrumbs snippet.
It will create a breadcrumb navigation for the current resource or a specific resource.

This snippet support most of Jared's BreadCrumbs features :

*   maxCrumbs
*   pathThruUnPub (now as showUnPub)
*   respectHidden (now as showHidden)
*   showCrumbsAtHome
*   showCurrentCrumb
*   showHomeCrumb
	
And add new features : 

*   chunk as templates (properties &containerTpl, &currentCrumbTpl, &linkCrumbTpl, &maxCrumbTpl)
*   breadcrumb for specific resource (property &resourceId)
*   direction (property &direction)
*   showContainer property
	
Some features of Jared's BreadCrumbs are missing but easily can be replaced by chunk / CSS customization, as :

*   crumbSeparator
*   currentAsLink
*   descField
*   homeCrumbDescription
*   homeCrumbTitle
*   maxDelimiter
*   titleField