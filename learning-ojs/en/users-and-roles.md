---
book: learning-ojs
version: 3.4
showPageTOC: true
title: Learning Open Journal Systems 3.4 - Users and Roles
---

# Users and Roles

This section provides information on accessing all of user accounts associated with your journal, as well as managing roles and permissions.

## Managing Users

This PKP School video explains how to manage users in OJS. To watch other videos in this series, visit [PKP’s YouTube channel](https://www.youtube.com/playlist?list=PLg358gdRUrDVTXpuGXiMgETgnIouWoWaY).

{% include video.html id="_AAtxnFEodQ" provider="youtube" title="Video of how to manage users in OJS"%}

In addition to managing the journal web site, the Journal Manager is also responsible for all of the user accounts in the system.

To view the user accounts, select Users & Roles from the left menu.

![Users and Roles screen with list of journal users](./assets/learning-ojs3.1-jm-users.png)

If you want to export a list of all registered users, you can find the option to export it as an XML file under the **Tools** menu. If you prefer your user data in a spreadsheet format, you can download it as a CSV file from **Statistics > Users**.

### Users

Users are displayed in last name order.

You can edit a user account by selecting the blue arrow to the left of an entry.

![Blue arrow selected by a user's name with options to edit their account](./assets/learning-ojs3.1-jm-users-edit.png)

This opens the options to Email, Edit User, Disable, Remove, Login As, Merge User.

#### Email Users

If you want to email a user about a particular submission, you can use the Discussion feature in the submission. This keeps all communication about a submission in one place.

To send an email to a user that is unrelated to a submission:

1. In the Journal Manager or Editor’s dashboard, go to Users & Roles > Users
2. Find the user you want to email
3. Click the blue arrow next to the user’s name to reveal links below it
4. Click Email. A pop-up box will appear where you can type in your message and send it

![Email pop-up box for emailing a user](./assets/learning-ojs-3-users-email.png)

##### Bulk Email Notifications by Role

In OJS 3.3 you can email multiple users at the same time using the Notify tab. This feature will need to be enabled for each journal by the journal administrator under Site Settings > Bulk Emails. The site administrator can also disable certain roles in the journal from receiving bulk emails under Hosted Journals > Settings Wizard.

If enabled for the journal by the site administrator, emails can be sent to all users in one or more role, such as all journal managers and / or all section editors, etc. See [Site Administration > Site Settings](./site-administration#site-settings) for instructions on enabling this feature.

In the Notify tab, select the user roles that you would like to email. Type your subject and email message. You have the option to send a copy of the email to your own email address. You will receive a status notification indicating that the message was sent successfully.

![OJS 3.3 selecting multiple users to notify with an email message](./assets/learning-ojs3.3-users-roles-notify.png)

This email feature can be used to send practical, core service emails to users who are actively working on the journal. For example, you might send an email to all copy editors reminding them of the “house style” for a particular word use or spelling. Avoid using this feature to notify large numbers of readers; the Announcement feature is preferable for large broadcast emails. See [Website Settings > Setup > Announcements](./settings-website#announcements) for details about this feature.

If several recipients flag your message as spam, it could result in all emails from the journal being sent to the spam folder. Care must be taken not to abuse this feature by sending excessive, unwanted emails. Become familiar with anti-spam and email privacy laws in your region, such as CASL in Canada and GDPR in the EU and UK. Note that there is no “unsubscribe” option available for users who receive these emails.

It is not possible to add cc or bcc addresses other than your own, or to add attachments to messages. To send attachments you can instead use the Discussion feature or the Submission Library.

**Edit User** allows you to make changes to that user's account.

![Edit information about a user](./assets/learning-ojs-3-users-edit-user.png)

**Disable** keeps the account in place, but blocks the user from accessing it.

**Remove** un-enrolls the user from all roles in the journal, but the user account remains in the system. The only way to actually remove a user account from your system is to **Merge Users** (see below).

**Login As** allows you to temporarily log in as that user, for example, to complete an outstanding task.

#### Merge User

The Merge User feature lets you fold this user account, including any submissions or assignments, into another user account on your system.

> **Note**: This is the only way to completely delete an account from the system.

You may want to create a dummy user account (e.g., Deleted Users), and use that to merge unwanted accounts into.

To merge users:

1. At Users & Roles > Users, find the user account you want to remove
2. Click the blue arrow next to the username
3. Click **Merge User** from the menu that appears below
4. Find the user account that you want to merge this user account into (the user you want to maintain)
5. Click the blue arrow next to username
6. Click **Merge into this user**
7. Press **OK** to confirm

#### Search Users

When you have a large number of users, you will want to take advantage of the search feature.

![Search for a journal user by name, email, and role](./assets/learning-ojs-3-users-search.png)

This can help you quickly find a user by first name, last name, or email address, or to see all users in a particular role.

**Note**: If you leave the Search field blank, select a Role, and hit Search, you will get a list of all users in that role (e.g., all copyeditors).

![Search for all users with a given role](./assets/learning-ojs-3-users-search-roles.png)

#### Add User

To add a new user to your journal, select the Add User link. This will open a new window with a set of fields to fill in.

![Add a user and enter their information](./assets/learning-ojs-3-users-add-new.png)

Once these fields are completed and you hit _Save_, you will then be asked to assign roles to the new account. Use the _Add Role_ link to open the role selector.

![Assign a role to a new user's account](./assets/learning-ojs-3-users-add-new-roles1.png)

Once you have added all of the roles, hit the **Save** button.

#### Register a User from Another Journal

On multi-journal installations, an Administrator or Journal Manager can register a user from Journal A as a user on Journal B.

1. Log in to Journal B as an Administrator or Journal Manager account
2. Go to Users & Roles > Users
3. Search for the user from Journal A that you want to register on Journal B, checking off **Include users with no roles in this journal**
4. When the user appears, click the blue arrow next to their name
5. Click **Edit User**
6. Scroll down to **User Roles** on the Edit User box that appears.
7. Check off the role that you want the user to have on Journal B
8. Click **Save** at the end of the form

#### If a User Can't Log In

If a user can't log in to your journal site, tell them to select **Forgot your password** on the Login page. They will then receive a reset password link by email and will be able to reset their password.

If the user has further issues, a Journal Manager or Editor can do the following:

1. Go to Users & Roles > Users
2. Find the user who can't log in and click the blue arrow next to their name
3. Click the **Edit User** button that appears below
4. Enter a new password in the **Password** field, making note of what the password is
5. Check off **User must change password on next log in**
6. Click **Save** at the end of the form
7. Send the new password to the user and instruct them to log in with it

If the user still cannot log in, their account may have been disabled. To re-enable it:

1. Go to Users & Roles > Users
2. Find the user who can't log in and click the blue arrow next to their name
3. Look below their name for **Enable** or **Disable.**  If Disable appears, the account is already enabled. If Enable appears, click it to re-enable the account.

<hr />

## Permissions and Roles

This PKP School video explains how to manage roles in OJS. To watch other videos in this series, visit [PKP’s YouTube channel](https://www.youtube.com/playlist?list=PLg358gdRUrDVTXpuGXiMgETgnIouWoWaY).

{% include video.html id="3sqD41OKuFs" provider="youtube" title="Video of how to manage roles in OJS"%}

The OJS workflow revolves around different roles with different permissions and responsibilities for each user, allowing them access to different parts of the workflow. Users in the system must have at least one role. Users can also have more than one role, for example, being a Journal Manager, Editor, and Author in the same journal.

Each role is first assigned a permission level, which will broadly define what level of access a user has to a particular journal. Roles are then further customized by providing a position name, and granting or restricting access to various stages of the Editorial Workflow.

There are a number of predefined roles that you can use and edit in OJS. Read in-depth about these predefined roles organized by their permissions level. Italicized roles are new in OJS 3.
 
* The **Site Administrator** is a single user responsible for administration of the entire OJS installation. This permissions level will not appear in user lists or in role settings. Site administrators, by default, have access to all journals within a given instance and can take any actions that can be undertaken by Journal Managers.

* **Journal Managers** have access to the entire Editorial Workflow, as well as all other journal settings.
Available predefined Journal Manager roles: Journal Manager, Journal Editor (formerly “Editor” in OJS 2), Production Manager
* **Section Editors** have access to the entire Editorial Workflow, but cannot make any changes to journal settings.
Available predefined Section Editor roles: Section Editor, *Guest Editor*
* **Assistants** can access only the parts of the Editorial Workflow assigned to their role.
Available predefined Assistant roles and their assigned editorial workflow stages:
    * Submission & Review stages: *Funding coordinator*
    * Copyediting stage: Copyeditor, *Marketing and sales coordinator*
    * Production Stage: *Designer*, *Indexer*, Layout Editor, Proofreader
* **Reviewers** are users who appear when you're assigning reviews in the Editorial Workflow and have access to that stage when they're assigned.
* **Authors** can make new submissions.
* **Readers** can access the reader-facing website. This is the minimum permissions level granted to all users.
* **Subscription Managers** can edit site access settings as well as settings related to subscriptions. This is a new permissions level in OJS 3, with one predefined role, *Subscription Manager*.

Predefined and custom roles can be checked from the Roles tab.

![Roles tab showing all current roles in the journal](./assets/learning-ojs3.1-jm-users-roles.png)

From this page, you can see each role, and the editorial stage each role can access. A good example of this is the Copyeditor role, which can only access the copyediting stage. Copyeditors cannot jump to the Review stage to see what happened during the peer review process. See the Editorial Workflow chapter for more information about the different editorial stages.

In addition to assigning and editing the predefined roles, Site Administrators and Journal Managers can also create new roles or rename existing ones. 

### Editing Roles

Unchecking a box removes access to that stage for users with that role.

Selecting the blue arrow to the left of the role name reveals the edit link. Clicking this opens the editing window.

![Edit details of a role](./assets/learning-ojs3.1-jm-users-roles-edit.png)

**Permission Level**: This indicates how much a user with this role can do in any stage.

The Journal Assistant level can communicate with other users and upload and revise files. In Journals where only one user has been assigned with an Assistant role, they will be automatically assigned to a new submission. Once a second person has been assigned this role, this action will stop.

**Role Name**: You can use this field to easily rename any role.

**Abbreviation**: Each role must have a unique abbreviation.

**Stage Assignment**: This allows you to determine which stage users with this role can access.

**Role Options**: Use these checkboxes to show anyone with this role in the contributor list \(e.g., the author list\). As of OJS 3.2, roles can be assigned permission to edit submission metadata by enabling the checkbox.

Use the second option to determine whether users can self-register in this role. Authors and Reviewers are good candidates for self-registration. You would definitely NOT want to allow users to self-register as Journal Managers or Editors!

The third option is useful for guest editors or possibly section editors, depending upon your preferred workflow and authority chain.

### Create New Roles

Use the _Create New Roles_ link to open a window where you can create a new role for your journal, including setting which stages it can access and how much permission it should have.

<hr />

## Site Access Options

This PKP School video explains how to configure site options in OJS. To watch other videos in this series, visit [PKP’s YouTube channel](https://www.youtube.com/playlist?list=PLg358gdRUrDVTXpuGXiMgETgnIouWoWaY).

{% include video.html id="lqf4GmA01PA" provider="youtube" title="Video of how to configure site access options in OJS"%}

This page allows you to determine how readers can access your journal.

![Site access options tab under Users and Roles](./assets/learning-ojs3.1-jm-users-siteoptions.png)

**Additional Site and Article Access Restrictions**: Choose from these options to limit access.

> Keep in mind that while requiring registration to read open access content can be convenient for your tracking, it can dissuade some people from reading your content. Use with care.

**User Registration**: This option allows you to determine whether users can create their own accounts or must be enrolled by a Journal Manager.

> Allowing users to register themselves, but only into Author, Reviewer, or Reader roles, is a good choice.
