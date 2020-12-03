---
keywords: Experience Platform;home;popular topics;update accounts;
description: 
solution: Experience Platform
title: Update account details in the UI
topic: overview
type: Tutorial
---

# Update account details in the UI

In some circumstances, it may be required to update the details of an existing sources account. The [!UICONTROL Sources] workspace provides you with the ability to edit, add, and delete details of an account, including values for its name, description, and authentication credentials.

This tutorial provides steps for updating the details and credentials of an existing account from the [!UICONTROL Sources] workspace.

## Getting started

This tutorial requires a working understanding of the following components of Adobe Experience Platform:

- [[!DNL Experience Data Model (XDM)] System](../../../xdm/home.md): The standardized framework by which [!DNL Experience Platform] organizes customer experience data.
  - [Basics of schema composition](../../../xdm/schema/composition.md): Learn about the basic building blocks of XDM schemas, including key principles and best practices in schema composition.
  - [Schema Editor tutorial](../../../xdm/tutorials/create-schema-ui.md): Learn how to create custom schemas using the Schema Editor UI.
- [[!DNL Real-time Customer Profile]](../../../profile/home.md): Provides a unified, real-time consumer profile based on aggregated data from multiple sources.

## Update accounts

Log in to Log in to the [Experience Platform UI](https://platform.adobe.com) and then select **[!UICONTROL Sources]** ffrom the left navigation to access the [!UICONTROL Sources] workspace. Select **[!UICONTROL Accounts]** from the top header to view existing accounts.

![catalog](../../images/tutorials/update/catalog.png)

The **[!UICONTROL Accounts]** page appears. On this page is a list of viewable accounts, including information about their source, username, number of dataflows, and date of creation.

Select the filter icon ![filter](../../images/tutorials/update/filter.png) on the top left to launch the sort panel.

![accounts-list](../../images/tutorials/update/accounts-list.png)

The sort panel provides a list of all sources. You can select more than one source from the list to access a filtered selection of accounts associated with different sources.

Select the source you wish to work with to see a list of its existing accounts. Once you have identified the account you want to update, select the ellipses (`...`) beside the account name.

![accounts-sort](../../images/tutorials/update/accounts-sort.png)

A dropdown menu appears, providing you with options to **[!UICONTROL Add data]**, **[!UICONTROL Edit details]**, and **[!UICONTROL Delete]**. Select **[!UICONTROL Edit details]** from the menu to update your account.

![update](../../images/tutorials/update/update.png)

The **[!UICONTROL Edit account details]** dialog box allows you to update an account's name, description, and authentication credentials. Once you have updated the desired information, select **[!UICONTROL Save]**.

![edit-account-details](../../images/tutorials/update/edit-account-details.png)

After a few moments, a green confirmation box appears on the bottom of the screen to confirm a successful update.

![update-confirmed](../../images/tutorials/update/update-confirmed.png)

## Next steps

By following this tutorial, you have successfully used the [!UICONTROL Sources] workspace to update account information.

For steps on how to perform these operations programmatically using the [!DNL Flow Service] API, please refer to the tutorial on [updating connection information using the Flow Service API](../../tutorials/api/update.md).