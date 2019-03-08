.. APInf API management documentation master file, created by
   sphinx-quickstart on Thu Jan 24 12:34:27 2019.

APInf - API management for everyone
========================================

We are proud to be part of `FIWARE <https://www.fiware.org>`_ thus the look and feel. 

You will find the source code of this project in `GitHub <https://github.com/apinf/platform>`_.
You will find the documentation of this project in Read the Docs and partially in Github. We are refactoring documentation. If you feel that there is information missing, please `raise an issue <https://github.com/apinf/platform/issues>`_ at Github as we tend to get blind. We do this all day.	

Quick Start
-----------

        Easy way to get familiar with APInf platform is to use our `SaaS <https://apinf.io>`_ 

We understand that poking around to see how things work is not for everyone. Please see this `document <https://github.com/apinf/platform/blob/develop/QuickStart.md>`_ to get introduction to the basics. There is a short `video <https://www.youtube.com/watch?v=yCR6pCnTm5w>`_ too!

Admin Installation - standalone
-------------------------------

We are updating this documentation, in the meanwhile please refer to `this <https://github.com/apinf/platform/blob/develop/INSTALL.md>`_.

Admin Installation - docker
---------------------------

We are updating this documentation, in the meanwhile please refer to `this <https://github.com/apinf/platform/blob/develop/INSTALL.md>`_.

Developer Documentation - how to call the API programmatically
--------------------------------------------------------------

APInf relies on Open API Spec documentation (previously Swagger) please see these links on how to access API management programmatically:

`Analytics <https://apinf.io/apis/apinf-analytics-api#api-documentation>`_

`Catalog <https://apinf.io/apis/apinf-catalog-rest-api-design#api-documentation>`_

`Management <https://apinf.io/apis/apinf-management-rest-api#api-documentation>`_


User Documentation - how to use the GUI
---------------------------------------

Basic flow after successful installation

1) sign-up (if you are the 1st user, you'll get admin rights!)
2) sign-in
3) add a proxy (if it does not already exist)
4) add an API and connect it to a proxy
5) test


        Easy way to test the APInf platform is to try our `SaaS <https://apinf.io>`_ 

Check `this video <https://www.youtube.com/watch?v=yCR6pCnTm5w>`_


APInf API management
--------------------

Why use APInf API management? If you have APIs and you are looking for additional control on API access, API documentation and analytics in one package, this is for you.

The APInf platform offers a comprehensive tool for API management. Building on APInf Umbrella, it provides enhanced user interface features for API managers and consumers alike.

For API consumers APInf provides simple key management, key usage analytics and API discovery along with API documentation. Managers have simplified workflow for common tasks, such as key management, rate limiting and viewing API usage analytics.


Basic Architecture
------------------
APInf API management is composed of two main components; APInf platform and proxy. The proxy in use is APInf umbrella and it is controlled via APInf platform UI, no need to touch the Umbrella directly, unless you really, really know what you are doing. 


Roadmap
-------
Roadmap is maintained in `"roadmap" <https://github.com/apinf/platform/blob/develop/roadmap.md>`_


.. toctree::
   :maxdepth: 2
   :caption: Contents:

