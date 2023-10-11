---
title: Deployment and Tuning Guide
description: Deployment and Tuning Guide
---

# Preface

## About this Manual

This guide provides conceptual and procedural information for tuning and deploying RadiantOne. This includes the topics of caching and the server settings for different types of deployment configurations. The tuning tips described in this guide refer to the specific parameters you should take into consideration when tuning. For specific details and exact steps on configuring these parameters, you should see the RadiantOne System Administration Guide.

## Audience

This manual is intended for administrators who are responsible for tuning and deploying RadiantOne. This manual assumes that the reader is familiar with the following:

-	SQL Queries

-	LDAP Queries

-	TCP/IP Connections

-	Cache

-	LDAP failover and load balancing

## How the Manual is Organized

[Global Tuning](01-global-tuning)
<br>This chapter describes tuning options that apply to the RadiantOne service at a global level, no matter what kind of namespace configuration options you use.

[Tuning Tips for Caching in the RadiantOne](02-tuning-tips-for-caching-in-radiantone.md) Federated Identity Service 
<br> This chapter describes memory and persistent caching in RadiantOne FID.

[Tuning Tips for Specific Types of Backend Data](03-tuning-tips-for-specific-types-of-backend-data-sources.md) <br>Sources in the RadiantOne Federated Identity Service
This chapter describes tuning options for specific types of backends virtualized by RadiantOne FID.

[Tuning Tips for RadiantOne Universal Directory Stores](04-tuning-tips-radiantone-universal-directory.md)
<br> This chapter describes how best to tune the RadiantOne Universal Directory stores.

[Testing RadiantOne Performance](05-testing-radiantone-performance.md)
<br> This chapter describes what tool to use to test RadiantOne search and authentication performance.

[Starting and Stopping Components](06-starting-and-stopping-components-and-services.md)
<br> This chapter describes how to start and stop RadiantOne service and Control Panel. This also includes steps on how to installs these components to run as Windows services and Linux daemons.

[Deployment Architectures](07-deployment-architecture.md)
<br> This chapter describes possible deployment architectures including how to migrate from a Development/QA environment to production. 

## Technical Support

Technical support can be reached using the following options:
-	Website: https://support.radiantlogic.com
-	E-mail: support@radiantlogic.com 

## Expert Mode

Some settings are accessible only in Expert Mode. To switch to Expert Mode, click the Logged in as, (username) drop-down menu and select Expert Mode. 

![An image showing ](Media/expert-mode.jpg)

>[!note] 
>The Main Control Panel saves the last mode (Expert or Standard) when you log out and returns to this mode automatically when you log back in. The mode is saved on a per-role basis.
