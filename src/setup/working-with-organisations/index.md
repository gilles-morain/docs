# Working with Organisations
<Badge text="deprecated" type="error"/>

:::danger
Organisations were replaced by [**Workspaces**](../../manage/workspaces/).
:::

In <MainPlatformNameLink />, **Organisations** can be used for easier management of users and projects within your team.

Just like ordinary user accounts, organisations can own and manage <MainPlatformName /> projects. All projects listed under an organisation use its  storage quota - rather than consuming storage quota of individual users that have created them.

Another advantage of organisations is that other users can be invited and they will get access to organisation's projects - it is not necessary to grant or revoke permissions of a single user manually for each project.

## Creating an Organisation

- Log in to <AppDomainNameLink />
- Select **+ Create** in the **Organisations** section
  ![new organisation](./mergin-organisation-create.png)
- Type a name for your **Organisation name**
- Fill in the **Description**
- Press **Save** to create your organisation

![](./create-organisation.png)

::: warning
To be able to use organisation features, you need to [**subscribe to the Team plan**](../subscriptions/index.md) first. You can create an organisation even if you are not subscribed to the Team plan, but until your subscription the storage allocation for your organisation will be 0 MB.
:::

## Organisation profile

To access your organisation profile:

- From the left panel, under **Organisations** select your organisation to switch to your organisation profile
- From the left panel, under **Settings** select **Profile**

Under profile you can:
- Change your organisation description by selecting **Edit profile**
- **Close Organisation**
- View project transfer requests to your organisation

## Inviting members

To invite <MainPlatformNameLink /> users to your new organisation:

- From the left panel, under **Organisations** select your organisation to switch to your organisation profile
- From the left panel, under **Settings** select **Members**
- By default, the user who created the organisation should be listed in the top as the owner
- To add more users, under **Find user** section, type the username
- Click on **Invite**

After the users accept the invitation, they should appear as members. Note that the invitation will expire after a certain number of days. If the user does not accept the invitation within this period, you will need to resend a new invitation.

By default, the new members will be assigned **Read** access to all projects within the organisation. You can change the permission level here or at the project level. See [permissions](../../manage/permissions.md) for more details.
