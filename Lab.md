# Lab: Building Microsoft Graph Applications

In this lab, you will walk through building applications that connect with the Microsoft Graph API using multiple technologies.

## In this lab

1. [Build a .NET console application using Microsoft Graph](#exercise1)
1. [Build a JavaScript application using Microsoft Graph](#exercise2)
1. [Build an Azure Function using Microsoft Graph](#exercise3)
1. [Build a mobile application with Xamarin using Microsoft Graph](#exercise4)

## Prerequisites

This lab uses Visual Studio 2017. Exercise 4 requires Windows 10. It also requires an **Azure Active Directory** tenant and a user with administrative privileges.

## Setup

Open the Visual Studio installer and enable the **.NET desktop development**, **Mobile development with .NET**, **Azure development**,and **Universal Windows Platform development** features. Make sure to update Visual Studio 2017 to the latest version, and update VSIX packages (Tools > Extensions and Updates).

<a name="exercise1"></a>

## Exercise 1: Build a .NET console application using Microsoft Graph

In this exercise you will create a .NET console application from scratch using .NET Framework 4.7.0, the Microsoft Graph SDK, and the Microsoft Authentication Library (MSAL).

> The steps for this exercise can be found **docs.microsoft.com**: [Build you first SharePoint client-side web part (Hello World part 1)](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/web-parts/get-started/build-a-hello-world-web-part)
> 
> Complete the steps in the tutorial above and return to this lab to proceed with the next exercise.

<a name="exercise2"></a>

## Exercise 2: Build a JavaScript application using Microsoft Graph

There are many sample applications that demonstrate how to use the Microsoft Graph API and the Microsoft Graph SDK available online. This lab will walk you through creating a JavaScript application leveraging the QuickStart project template to quickly get started.

> The steps for this exercise can be found **docs.microsoft.com**: [Connect your client-side web part to SharePoint (Hello World part 2)](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/web-parts/get-started/connect-to-sharepoint)
> 
> Complete the steps in the tutorial above and return to this lab to proceed with the next exercise.

<a name="exercise3"></a>

## Exercise 3: Build an Azure Function using Microsoft Graph

This exercise will build an Azure Function that runs on a scheduled basis to obtain all the users in the directory.

This solution will require an organizational account. An admin is required to provide consent. To facilitate this, you will start with an existing solution. Once you have tested that the app is successfully authenticating and retrieving users, you will implement an Azure Function that synchronizes users.

> The steps for this exercise can be found **docs.microsoft.com**: [Deploy your client-side web part to a SharePoint page (Hello World part 3)](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/web-parts/get-started/serve-your-web-part-in-a-sharepoint-page)
> 
> Complete the steps in the tutorial above and return to this lab to proceed with the next exercise.
