---
title: Namespace Configuration Guide
description: Namespace Configuration Guide
---

# Introduction 

Prior to diving into this guide, it is recommended that you read the Architect Guide for a high-level overview of the capabilities of RadiantOne and the System Admin Guide for an understanding of general concepts and usage of the Main Control Panel and Server Control Panel. This guide provides step-by-step instructions to configure the virtual namespace. Configuring persistent cache is out of the scope of this guide. For details on persistent cache, see the [RadiantOne Deployment and Tuning Guide](/documentation/deployment-and-tuning-guide/00-preface).

>[!warning] 
>For production deployments, RadiantOne configuration changes must be performed during non-peak/off-hours to avoid any disruption in service.

For details on deploying RadiantOne including tuning and maintenance, please see the RadiantOne Deployment and Tuning Guide.

## How this Manual is Organized

This guide is broken down into the following chapters:

[Introduction](01-introduction)
This chapter offers a quick introduction to this guide in addition to how the manual is organized and how to contact Radiant Logic technical support.

[Directory Namespace Design](02-directory-namespace-design)
This chapter introduces the main concepts of namespace design and how to create and delete root naming contexts.

[ Virtual Views of LDAP Backends](03-virtual-view-of-ldap-backends)
This chapter provides step-by-step configuration details for virtualizing LDAP backend data sources.

[Virtual Views of Database (JDBC/ODBC-accessible) Backends](04-virtual-views-of-database-backends)
This chapter provides step-by-step configuration details for virtualizing JDBC-accessible database backend data sources.

[RadiantOne Universal Directory](05-radiantone-universal-directory)
This chapter provides step-by-step configuration details for the RadiantOne Universal Directory storage.

[Virtual Views based on an Aggregation of Multiple Types of Backends](06-virtual-views-based-on-aggregation)
This chapter provides step-by-step configuration details for virtualizing many different types of backends (e.g. LDAP, JDBC) below a common root naming context.

[ Virtual Views of Cloud Applications](08-virtual-views-of-cloud-directories-or-services)
This chapter provides step-by-step configuration details for virtualizing cloud applications and directories like Salesforce, Azure AD, Google directory, PingOne Directory, and SailPoint IdentityIQ.

## Technical Support

Technical support can be reached using any of the following options:

- E-mail: support@radiantlogic.com
- Website: https://support.radiantlogic.com

## Expert Mode

Some settings in the Main Control Panel are accessible only in Expert Mode. To switch to Expert Mode, click the Logged in as, (username) drop-down menu and select Expert Mode. 

![An image showing ](Media/expert-mode.jpg)
 
Figure 1.1: Expert Mode

