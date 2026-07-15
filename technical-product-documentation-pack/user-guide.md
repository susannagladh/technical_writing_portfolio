# FlowDesk Admin User Guide

[Home](../) | [About me](../about.md) | [Selected work](../#selected-work)

FlowDesk Admin is a fictional web-based admin portal for managing users, roles and notification settings in a SaaS product.

This guide explains how customer administrators can perform common admin tasks, such as inviting users, assigning roles, deactivating accounts and updating notification settings.

## Who this guide is for

This guide is for customer administrators who manage users in FlowDesk Admin.

You do not need a technical background, but you should have administrator access to FlowDesk Admin.

## Before you begin

You need:

- an active FlowDesk Admin account
- administrator permissions
- access to the email address connected to your account
- the name and email address of any user you want to invite

## User roles

FlowDesk Admin uses roles to control what each user can view and do.
In this guide, **user** means a person with a FlowDesk account. **Role** means the permission level assigned to that person.

| Role | Description |
|---|---|
| Admin | Can manage users, roles, account settings and notifications. |
| Manager | Can view team activity and manage selected team settings. |
| Member | Can access the main product features but cannot manage users or account settings. |
| Viewer | Can view information but cannot make changes. |

> Note: Available roles may vary depending on your organization’s subscription and configuration.

## Invite a new user

Use this task to give a new person access to FlowDesk.

### Steps

1. Sign in to FlowDesk Admin.
2. Go to **Users**.
3. Select **Invite user**.
4. Enter the user’s name and email address.
5. Select a role from the **Role** menu.
6. Select **Send invitation**.

FlowDesk sends an invitation email to the user. The user must accept the invitation before they can access the product.

### Result

The invited user appears in the user list with the status **Pending** until they accept the invitation.

## Change a user role

Use this task to change a user’s access level in FlowDesk.

### Steps

1. Go to **Users**.
2. Find the user in the user list.
3. Select the user’s name to open the user details page.
4. Under **Role**, select the new role.
5. Select **Save changes**.

### Result

The user’s permissions are updated immediately.

> Tip: Review role changes carefully before saving. Giving a user more access than they need can increase security and administration risks.

## Deactivate a user

Use this task to remove a user's access to FlowDesk, for example when they leave the organization or change responsibilities.

### Steps

1. Go to **Users**.
2. Find the user you want to deactivate.
3. Open the user details page.
4. Select **Deactivate user**.
5. Confirm the action.

### Result

The user can no longer sign in to FlowDesk. Their historical activity remains visible in reports and audit logs.

> Note: Deactivating a user does not delete historical data connected to that user.

## Reactivate a user

Use this task to restore access for a previously deactivated user.

### Steps

1. Go to **Users**.
2. Filter the user list by **Inactive users**.
3. Select the user you want to reactivate.
4. Select **Reactivate user**.
5. Review the assigned role.
6. Select **Save changes**.

### Result

The user can sign in again using their existing account.

## Configure notification settings

Notification settings control which system emails users receive from FlowDesk.

### Steps

1. Go to **Settings**.
2. Select **Notifications**.
3. Choose which notifications should be enabled.
4. Select the user groups or roles that should receive each notification.
5. Select **Save changes**.

### Common notification types

| Notification | Description |
|---|---|
| Invitation email | Sent when a new user is invited. |
| Password reset email | Sent when a user requests a password reset. |
| Role change notification | Sent when a user’s access level changes. |
| Account activity summary | A recurring summary of account activity. |

## Search and filter users

Use search and filters to find users quickly.

### Search for a user

1. Go to **Users**.
2. Enter the user’s name or email address in the search field.
3. Review the search results.

### Filter users

You can filter users by:

- role
- status
- team
- invitation status

User statuses include:

| Status | Meaning |
|---|---|
| Active | The user can sign in and use FlowDesk. |
| Pending | The user has not accepted the invitation. |
| Inactive | The user has been deactivated. |

## Best practices

Use these recommendations to keep your FlowDesk account organized and secure:

- Give users the lowest role needed for their work.
- Review admin access regularly.
- Deactivate users who no longer need access.
- Use clear naming conventions for teams and user groups.
- Check pending invitations regularly and resend them if needed.
- Review notification settings after major team or process changes.

## Related documentation

- [Troubleshooting guide](./troubleshooting-guide.md)
- [UX copy sample](./ux-copy-sample.md)

---

[Back to case study](./) | [Back to portfolio](../)
