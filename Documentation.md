---
title: Azure with Microsoft Teams
description: Monitor your application and infrastructure on Azure from Microsoft Teams
ms.date: 02/14/2020
---

# Azure with Microsoft Teams
If you use Microsoft Teams you can use the Azure App 

If you use Microsoft Teams, you can use the Azure app for Teams to easily monitor your application and infrastructure on Azure. Link action groups of your choice with the channel and get notified on the alerts.


## Prerequisites
> [!NOTE]
> * The app posts notifications for metric alerts. Support for 'activity log' and 'log alerts' will added soon.
> * Alerts with multiple conditions or a single metric alert with multiple dimensions are not supported.
> * For feedback and suggestions, users can create an issue


## Add the Azure app to your team in Microsoft Teams
Download the manifest file from [this](https://google.com) location and upload it as a custom app and install it to the team of your choice. 
> ![Add as custom app](./teams/add-as-custom-app.png)

Upon installing, a welcome message is displayed as shown in the following image. Use the @azure handle to start interacting with the app.
> ![welcome message](./teams/welcome-message.png)


> ![Image](./teams/image.png)


## Link the Azure app to action groups 

1. Once the app has been installed in your team, authenticate yourself to Azure app using the @azure signin command.

> ![sigin1](./teams/signin1.png)
> ![sigin2](./teams/signin2.png)
> ![sigin3](./teams/signin3.png)

2. To start monitoring your application and infrastructure, use the following command inside a channel:

  ```
   @azure actionGroups
  ```
This command 



To link an action group to a channel, one must be part of Azure Monitor Contributor group. 

## Manage action groups



## Troubleshooting

