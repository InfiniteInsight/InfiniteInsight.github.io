---
layout: default
title: Dust-Off
description: For when Active Directory is looking a bit dusty.
---

# Dust-Off
![Dust-Off](assets\images\Dust-OffBanner.jpg)
_Purge Active Directory and Entra of the cruft_

Keeping active Directory clean and orderly can be a challenge. Unused computer objects, Empty groups, abandoned service accounts all pile up.

Dust-Off is a tool that helps give the administrator context around these objects, logs their configuration, creates an audit trail, and helps you remove it all. 

It can allow for approval workflows or be configured to operate without them.

You can restore everything or granularly.

At the moment the backend is being worked on, there's not much to the frontend yet. It will run in the browser or through Tauri.

The backend is written in .NET 8, ASP.NET Core, Entity Framework Core.
The Frontend stack will be React, TypeScript and Tailwind CSS.

The database is Postgres.

V1.0 will be released on Github when the milestone is reached.

![login](assets\images\dust-off\DustOff-Login.png)





[back](./)
