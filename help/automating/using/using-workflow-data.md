---
title: Using workflow data
seo-title: Using workflow data
description: Using workflow data
seo-description: Learn the different possibilities to consume the data you imported or targeted.
page-status-flag: never-activated
uuid: 3dd66aeb-3a26-4214-b6a0-242c2b7fbc49
contentOwner: sauviat
products: SG_CAMPAIGN/STANDARD
audience: automating
content-type: reference
topic-tags: workflow-general-operation
discoiquuid: 90b250f1-f32d-4256-83ea-4c0627628610

internal: n
snippet: y
---

# Using workflow data{#using-workflow-data}

Once the data has been identified and prepared, it can be used in the following contexts:

* The **[!UICONTROL Update data]** activity allows you to perform a mass update on fields in the database.
* The **[!UICONTROL Save audience]** activity allows you to update an existing audience or create a new audience from the population computed upstream in a workflow. The audiences created or updated from this activity are **List** or **File** audiences. This activity also allows you to export profiles as Adobe Experience Cloud audiences/segments.
* The **[!UICONTROL Subscription Services]** activity allows you to take profiles in mass and subscribe them to a service or unsubscribe them from a service.
* The **[!UICONTROL Extract file]** activity allows you to export data from Adobe Campaign in the form of an external file.

After defining a profile target, you can use several activities to create and send deliveries:

* The **[!UICONTROL Email delivery]** activity allows you to configure sending an email in a workflow. This can be a **single send** email and sent just once, or it can be a **recurring** email.
* The **[!UICONTROL SMS delivery]** activity allows you to configure sending an SMS in a workflow. This can be a **single send** SMS and sent just once, or it can be a **recurring** SMS.
* The **[!UICONTROL Mobile app delivery]** activity allows you to configure sending a push notification in a workflow. This can be a **single send** notification and sent just once, or it can be a **recurring** notification.

