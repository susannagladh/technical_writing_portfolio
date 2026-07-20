# FlowDesk Admin Troubleshooting Guide

[Home](../) | [About me](../about.md) | [Selected work](../#selected-work)

This troubleshooting guide helps administrators and support teams solve common issues in FlowDesk Admin.

Use this guide when users experience problems with invitations, sign-in, roles, permissions or notification settings.

## Who this guide is for

This guide is for:

- customer administrators
- support specialists
- customer success teams
- application specialists

To use this guide, you need access to FlowDesk Admin and permission to view or manage user accounts.

## Before you troubleshoot

Before you begin, check the following:

- The affected user has a FlowDesk account.
- The user’s email address is spelled correctly.
- The user has the correct role.
- The user is using the latest invitation or password reset email.
- No known service disruptions.

## Quick issue overview

Use this table to identify common issues in FlowDesk Admin.

First, find the issue that best matches the user’s problem. Then open the matching section below for detailed troubleshooting steps.

| Issue | Common cause | Recommended action | Detailed steps |
|---|---|---|---|
| User cannot sign in | Incorrect password, inactive account or expired invitation | Check the user status and send a password reset or new invitation | [User cannot sign in](#user-cannot-sign-in) |
| Invitation email not received | Email blocked, incorrect address or expired invitation | Verify the email address and resend the invitation | [Invitation email not received](#invitation-email-not-received) |
| User cannot access a feature | The assigned role does not include the required permission | Review the user’s role and update if needed | [User cannot access a feature](#user-cannot-access-a-feature) |
| User receives too many notifications | Notification settings are too broad | Review notification settings by role or group | [Too many notifications are sent](#too-many-notifications-are-sent) |
| User does not receive notifications | Notifications are disabled or sent to another group | Check notification settings and user group membership | [Notifications are not received](#notifications-are-not-received) |

## User cannot sign in

Use this section when a user cannot access FlowDesk.

### Possible causes

- The user entered the wrong password.
- The user has not accepted the invitation.
- The invitation has expired.
- The account is incative.
- The user is trying to sign in with the wrong email address.

### Steps to resolve

1. Go to **Users**.
2. Search for the affected user by name or email address.
3. Check the user status.

| Status | What it means | Action |
|---|---|---|
| Active | The user can sign in | Ask the user to reset their password |
| Pending | The user has not accepted the invitation | Resend the invitation |
| Inactive | The user has been deactivated | Reactivate the user if access is still needed |

4. Verify that the email address is correct.
5. If the user is active, ask them to use **Forgot password** on the sign-in page.
6. If the issue continues, contact support with the user’s email address and a description of the problem.

## Invitation email not received

Use this section when a user says they did not receive their invitation email.

### Possible causes

- The email address was entered incorrectly.
- The invitation email was filtered as spam.
- The user’s organization blocks automated emails.
- The invitation has expired.

### Steps to resolve

1. Go to **Users**.
2. Search for the invited user.
3. Check that the email address is correct.
4. Ask the user to check their spam or junk folder.
5. Select **Resend invitation**.
6. Ask the user to open the most recent invitation email.

> Note: If multiple invitations have been sent, the user should use the latest email. Older invitation links may no longer work.

## User cannot access a feature

Use this section when a user can sign in but cannot access a feature they expect to use.

### Possible causes

- The user has the wrong role.
- The organization’s subscription does not include the feature.
- The user belongs to the wrong team or group.
- The feature has not been enabled for the organization.

### Steps to resolve

1. Go to **Users**.
2. Open the affected user’s profile.
3. Check the assigned role.
4. Compare the role with the access needed.

| Role | Typical access |
|---|---|
| Admin | Full access to users, roles, settings and notifications |
| Manager | Access to team activity and selected team settings |
| Member | Access to main product features |
| Viewer | Read-only access |

5. Update the role if the user needs more access.
6. If the role is correct, check whether the feature is enabled for the organization.
7. If the issue continues, contact support.

> Tip: Give users the lowest role needed for their work. This helps reduce unnecessary access and administration risks.

## User has the wrong role

Use this section when a user has more or less access than expected.

### Steps to resolve

1. Go to **Users**.
2. Search for the user.
3. Open the user details page.
4. Review the assigned role.
5. Select a new role from the **Role** menu.
6. Select **Save changes**.
7. Ask the user to refresh the page or sign in again.

### Result

The user’s permissions are updated. In most cases, the change takes effect immediately.

## Notifications are not received

Use this section when users do not receive expected system notifications.

### Possible causes

- The notification type is disabled.
- The user’s role or group is not selected as a recipient.
- The email service filtered the message as spam.
- The user’s email address is incorrect.
- The notification was sent to a different administrator or group.

### Steps to resolve

1. Go to **Settings**.
2. Select **Notifications**.
3. Check that the notification type is enabled.
4. Verify that the correct roles or groups are selected.
5. Check the affected user’s email address.
6. Ask the user to check their spam or junk folder.
7. Save any changes and test the notification again.

## Too many notifications are sent

Use this section when users receive more notifications than expected.

### Possible causes

- A notification is enabled for too many roles.
- A user belongs to multiple groups.
- Notification settings were copied from a previous configuration.
- The account activity summary is sent too frequently.

### Steps to resolve

1. Go to **Settings**.
2. Select **Notifications**.
3. Review each enabled notification.
4. Check which roles and groups receive the notification.
5. Remove unnecessary recipients.
6. Review the frequency of recurring notifications.
7. Select **Save changes**.

## Error messages

| Error message | What it means | What to do |
|---|---|---|
| `Invitation has expired` | The user opened an old or expired invitation link | Resend the invitation and ask the user to use the latest email |
| `Access denied` | The user does not have permission to view the page | Check the user’s role and update it if needed |
| `User already exists` | The email address is already connected to an account | Search for the user instead of sending a new invitation |
| `Unable to save changes` | The update could not be saved | Refresh the page and try again. If the issue continues, contact support |
| `Invalid email address` | The email address is missing or incorrectly formatted | Check the email address and try again |

## When to contact support

Contact support if:

- the issue continues after following the steps in this guide
- several users are affected at the same time
- a user has the correct role but still cannot access expected features
- invitation or password reset emails are not delivered
- error messages appear repeatedly

When contacting support, include:

- the affected user’s email address
- the user’s current status
- the user’s assigned role
- a short description of the issue
- the steps already tried
- screenshots of any error messages, if available

## Related documentation

- [User guide](./user-guide.md)
- [UX copy sample](./ux-copy-sample.md)

---

[Back to case study](./) | [Back to portfolio](../)
