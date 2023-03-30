+++
title = "Platform"
date = "2023-03-17"
sidemenu = "true"
description = "Welcome to golab Platform"
+++

{{< figure src="/img/platform-illustration.svg" width="60%" >}}

## OVERVIEW
---------------

The golab platform is the backbone of our LIMS solution, provinding a powerful and flexible tool to manage all aspects of the laboratory workflow. 

### Technology

The application was developed using [Slingr](https://slingr.io/), a cloud-based low-code platform that allows developers to automate business workflows and integrate various tools and services.

{{< figure src="/img/slingr-logo.svg" width="50%" >}}

### Features

The platform features:

* [Administration Panel](#administration-panel): manage and store data of patients, methods, tests and templates.
* [User Management](#users-management): manage all users and their permissions.
* [Samples Management](#samples-management): main feature of the platform, it allows to manage all samples workflow.
* [Report Generator](#report-generator): automatically generates reports for ready samples.
* [Settings Panel](#settings-panel): configure the platform to meet the needs of the laboratory.
* [Notifications](#mailchimp-integration): send automated notifications to users.
* [Metrics Dashboard](#metrics): gain insights about the processes and historical metrics of the laboratory.
* [Data Set](#data-set): a feature to restore some platform fictitious data.


{{< figure src="/img/users.svg" width="60%" >}}

### User groups

In the platform you'll find three types of users with different permissions: Admins, Technicians, and Patients.

* [Admins](#admins): 

Admins are typically responsible for the overall management of the LIMS. They have full access to all features and records of the application. They have exclusive access to different features such as: user managment, settings, metrics dashboard and data set.

* [Technicians](#technicians): 
{{< figure src="/img/science.svg" width="60%" >}}

Technicians are responsible for the day-to-day management of the testing workflow using: samples managment, report generator, and notifications features. They also have access to other administration features such as methods and tests. 

* [Patients](#patients):

This group was created to give the patients the ability to access their samples status and results. They can access the platform using a username and password provided by the laboratory. A user patient must be related to the patient record. Despite this is not a common feature in LIMS and the laboratory can choose wether to use it or not, we believe that it could improve the patients experience and increase the laboratory's efficiency. 

