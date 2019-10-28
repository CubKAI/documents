# User Management

When we click Administration/Users menu, we enter the user management page:

<img src="images/user-management-core-3.png" alt="User management" class="img-thumbnail" />

**Users** are people who can **login** to the application and perform some operations based on their **permissions**.

Current **user list** can be downloaded as an Excel file. new users can be imported from an excel file. Also, invalid user information is sent back with the reason for invalidity via notification system after import process ends.

**User** class represents a user. User class [can be extended](Extending-Existing-Entities.md) by adding new properties.

**UserManager** is used to perform domain logic, **UserAppService** is used to perform application logic for users.

A user can have zero or more **roles**. If a user has more than one role, he inherits union of permissions of all these roles. Also, we can set **user-specific permission**. A user specific permission setting overrides role settings for this permission. A screenshot of user permission dialog:

<img src="images/user-permissions-1.png" alt="User Permissions" class="img-thumbnail" />

*Note that not all permissions shown in the figure above*

A dialog is used to create/edit a user:

<img src="images/edit-user-3.png" alt="Editing User" class="img-thumbnail" />

We can change user's **password**, make her **active/passive** and so on... A user can have a **profile picture**. It can be changed by the user (See User Menu section). **Admin** user can not be deleted as a business rule. If you don't want to use admin, you can make it passive.

## User Impersonation

As admin (or any allowed user), we may want to login as a user and perform operations on behalf of that user, without knowing his password. When we click "**Login as this user**" icon in the actions of a user, we
are automatically redirected and logged in as this user. This is called as "**user impersonation**". When we impersonate a user, a "**back to my account**" option is added to the user profile menu:

<img src="images/back-to-my-account-link-3.png" alt="Back to my account link" class="img-thumbnail" />

In an impersonated account, we can only perform operations allowed to that user. That means, everything **exactly** works as same as this user logged in himself. The only difference is shown in audit logs which
indicates that operations are performed by somebody else. Notice that; Also a **red 'back' icon** shown near to the user name to indicate that you are in an impersonated account.

Impersonation is done in **AccountController** of the Web project.

## Next

- [Language Management](Features-Mvc-Core-Language-Management)


