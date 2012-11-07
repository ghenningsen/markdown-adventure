markdown-adventure
==================

A playground for learning *git-markdown*

This is an [example link](http://example.com/).

![Alt text](/path/to/img.jpg)

![Alt text](/path/to/img.jpg "Optional title")

Markdown will generate:

<p>This is a normal paragraph:</p>

<pre><code>This is a code block.
This is a code block.
This is a code block.
</code></pre>

Methods
=======

* AppVersion  
  * getVersionRequired
* Authentication  
* Browse  
* Cart  
* Checkout  
* CookieStore  
* ExtendedItem/BatchItem    
* GS  
* Item – Deprecated. Replaced by the ExtendedItem Service.   
* Item Inventory  



getVersionRequired 
------------------

<b>Example URL</b>  
http://mobile.walmart.com/m/j?service=AppVersion&method=getVersionRequired

<b>Parameters</b>   None

<b>Special Handling</b> 

<b>Cookies?</b>  No

<b>HTTPS?</b>	No

<b>post Method Required?</b>	No

<b>Gotchas</b>

<b>Response Payload</b>
    [TBD]


.. _get-started-section:


=============================
Getting Started with Usergrid
=============================


To appreciate the extensive functionality of Usergrid, this section steps you through *Messagee*, a simple Twitter-style messaging application. There are two client versions of Messagee available: 


* An :ref:`messagee-ios`  
* An :ref:`messagee-android`  


The descriptions below shows you how easy it is to create a new app, populate a series of test users, and test the app. To run a copy of *Messagee*, you’ll use the Usergrid Admin Portal, a user interface that streamlines Usergrid data and application management. The portal itself is also a reference application that shows how to incorporate Usergrid APIs with Javascript (for a more detailed discussion of the portal’s functionality, see :ref:`portal-section`).


.. _messagee-setup:


--------------------------
Creating an App and Users 
--------------------------


**1.** Enter the URL https://apigee.com/usergrid/ in your browser to access the login screen for the *Usergrid Admin Portal*. If you are new to Usergrid, sign up for an account to access the portal, specifying an organization (e.g., the name of your company or project team) and a username and password that you’ll use to authenticate. Since Usergrid is designed for use by development teams, the same username can be associated with one or more organizations. 


New accounts receive a confirmation email that contains a URL that you must click to activate the account. After this, simply log into the portal with your username and password.


.. figure:: _static/login.png 


**2.** Click on **New Application** to begin creating a new application:


.. figure:: _static/portal-1.png


**3.** Enter a unique application name. The name must be unique to avoid a conflict with another user running the same application.


.. figure:: _static/portal-2.png

