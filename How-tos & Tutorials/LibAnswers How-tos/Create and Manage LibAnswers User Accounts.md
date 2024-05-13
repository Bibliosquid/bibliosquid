# Accounts: Create and Manage User Accounts #

| In this Article  | 
| ------------- | 
| [Add a New User Account](###Add-a-New-User-Account)  |
| [Manage User Accounts](###Manage-User-Accounts)  |
| [Delete an Account](https://github.com/Bibliosquid/bibliosquid/edit/main/How-tos%20%26%20Tutorials/LibAnswers%20How-tos/Create%20and%20Manage%20LibAnswers%20User%20Accounts.md#delete-an-account) |
| [View a Single Email List of Accounts by Level](###View-a-Single-Email-List-of-Accounts-by-Level)

### Add a New User Account ###

1. Go to **Admin > Accounts**.
2. On the **Manage Account** Page, click on the **Create a New Account** tab.
3. In the **Login/Email** field, enter the email address of the user you want to add and click the **Look-up Account** button.
4. If an existing LibApps account for that email is found, LibAnswers will be added to their LibApps user account. As a result, you will not need to provide a **First Name** or **Last Name** for the new account.
   - Once a LibApps account is created, *only the user or a LibApps Admin will be able to change the user's name and email address*.
5. In the **Nickname** field, you can enter an optional alias that displays while chatting with patrons in LibChat.
   - To also use this nickname in place of the full name on all ticket replies and applicable public pages, check the **Use nickname for ticket replies and public pages** checkbox.
6. From the **User Level** dropdown, select the permissions you want to assign to the new user,
   - **Admin users** can create content, edit all content in the system, and manage system settings & customizations. They have access to all ticket queues, FAQ groups, and chat departments.
     - If the account is being set to the Admin-level and the user does not need access to Libchat, you can click Create account without configuring any other settings on the remaining tabs.
   - **Regular users** can create and edit FAQs within assigned groups and reply to tickets in assigned queues. This user type is appropriate for most general users.
   - **Reader users** have read-only access to the public pages of Internal and Restricted Internal FAQ Groups. These users cannot access the admin side of LibAnswers. This user type is appropriate for users who may need to review internal content without editing privileges.
   - **Ref.Analytics Only** can only add, view, and analyze transactions in your Reference Analytics datasets. This is helpful if you want certain users (such as student assistants or volunteers) to record transactions, but not have access to other areas of LibAnswers.
7. Use the **Profile Image** to select whether the user's LibApps profile image or a generic image should display as the user's avatar.

  
### Manage User Accounts ###

1. Go to **Admin > Accounts**.
   
   <img src="/../main/Assets/Images/Manage_Accounts.png" width="450" alt="Screenshot of the manage accounts options window, showing access to queues, groups, and departments.">
   
2. Under the **Manage Accounts** tab:
  - Click on a user's edit icon in the **Actions** column on the right side of the table to edit that user's account information, permissions, and defaults.
    - You can also manage user access to queues, groups, departments, and Ref. Analytics datasets in each queue, group, department, and dataset's settings.
    - For accounts that should no longer have access to LibAnswers but should have historical user data assigned to them still, set their account to **Inactive**.
  - To remove a user, click on their trash can icon in the **Actions** column.
    - You will be prompted to reassign that user's data to another user.
    - If you do not want to reassign the user's data, but prevent that user from logging into LibAnswers, edit their account and change their permission level to **Inactive**.
  - To reactivate an inactive user's account, click on the refresh icon in the **Actions** column for the user.


### Delete an Account ###

You can delete an account to permanently remove it from the system. To retain stats and not reassign the user’s data, but prevent that user from logging in, you can alternatively change their permission level to Inactive. To fully delete an account:

1. Go to **Admin > Accounts**. 
2. Click on the user's trash icon in the **Actions** column on the right side of the table.
3. A list of content assigned to the soon-to-be-deleted user will display.
  - You will need to select a user to reassign the soon-to-be-deleted user's assigned content to. Select that user's name form the **User account you wish to reassign** dropdown.
4. Select **Yes, I'm sure** to delete the account fully. After deletion, the account cannot be recovered.

<img src="/../main/Assets/Images/delete-user.png" width="450" alt="Screenshot of the Delete user window, showing a list of assigned user content.">

### View a Single Email List of Accounts by Level ###

1. Go to **Admin > Accounts**.
2. Click on the **Email Users** tab.
3. If you need to send a bulk email to all LibAnswers users, copy and paste email addresses into your email application of choice. 



