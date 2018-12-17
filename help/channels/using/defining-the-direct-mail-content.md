---
title: Defining the direct mail content
seo-title: Defining the direct mail content
description: Defining the direct mail content
seo-description: Learn how to define the content for your direct mail delivery.
page-status-flag: never-activated
uuid: 6451282a-5864-4a04-9c40-da3dae642364
contentOwner: sauviat
products: SG_CAMPAIGN/STANDARD
audience: channels
content-type: reference
topic-tags: direct-mail
discoiquuid: 1560638f-9b50-495b-b39a-c651c8ac1991
isreadyforlocalization: true
index: y
internal: n
snippet: y
---

# Defining the direct mail content{#defining-the-direct-mail-content}

Defining the direct mail content

You can either define the content in the last screen of the creation wizard or by clicking on the **Content** section of the delivery dashboard.

![](assets/direct_mail_6.png)

The **Content** definition screen is specific to the direct mail channel. It is divided into four tabs: **Extraction**, **File structure**, **Header** and **Footer**.

![](assets/direct_mail_11.png)

## Defining the extraction {#defining-the-extraction}

1. Start by defining the name of the extraction file. Click on the button to the right of the **Output file** field and enter the desired label. You can use personalization fields, content blocks and dynamic text (see [Defining content](../../designing/using/example--email-personalization.md)). For example, you can complete the label with the delivery ID or the extraction date. 

   ![](assets/direct_mail_12.png)

1. Click the **+** or **Add an element** button to add an output column. The **Output columns** let you define the profile information (columns) to be exported into the output file.

   >[!CAUTION]
   >
   >Make sure that your profiles include a postal address as this information is essential to the direct mail provider. Also make sure you have checked the **Address specified** box in your profiles' information. See [Recommendations](../../channels/using/about-direct-mail.md#recommendations).

   ![](assets/direct_mail_13.png)

1. Create as many columns as you need. You can edit columns by clicking their expressions and labels.

>[!NOTE]
>
>For more information on output column definition, refer to the [Extract file](../../automating/using/extract-file.md) workflow activity section.

## Defining the file structure {#defining-the-file-structure}

The **File structure** tab allows you to configure the output, date, and number formats for the file that will be exported.

![](assets/direct_mail_14.png)

>[!NOTE]
>
>The available options are detailed in the [Extract file](../../automating/using/extract-file.md) workflow activity sections.

## Defining the header and footer {#defining-the-header-and-footer}

Sometimes you may need to add information at the beginning or at the end of the extraction file. For this, use the **Header** and **Footer** tabs of the **Content** configuration screen. 

![](assets/direct_mail_7.png)

For example, you might want to include, for the direct mail provider, the sender information in the header of the file. It is possible to personalize the footer and header with information available in the context of the delivery. See [Defining content](../../designing/using/example--email-personalization.md).

The sender address is defined in the **Send** section of the direct mail properties or at the template level.

![](assets/direct_mail_24.png)
