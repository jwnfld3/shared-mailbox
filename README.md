# Creating a Shared Mailbox and Assigning Permissions in Microsoft 365

## Lab Overview:
This lab guides users through the process of creating a shared mailbox in Microsoft 365 and assigning the appropriate permissions (Full Access, Send As, and Send on Behalf) to enable users to manage the mailbox collaboratively.

## Lab Requirements:
- Microsoft 365 admin account
- Access to the Microsoft 365 Admin Center
- Users who will receive permissions to access the shared mailbox

## Who, What, When, Where, Why:
- **Who:** IT administrators, users who need access to shared mailboxes
- **What:** The lab covers the creation of a shared mailbox and assigning the necessary permissions to users.
- **When:** This lab should be performed when a team or department requires a central email address and multiple users need access.
- **Where:** This procedure is carried out within the Microsoft 365 Admin Center, specifically under the Exchange Admin Center.
- **Why:** Shared mailboxes are essential for team collaboration, allowing users to send, receive, and manage emails from a common account.

## Lab Steps:

### Step 1: Create a Shared Mailbox
1. **Login to Microsoft 365 Admin Center:**
   - Open a web browser and go to [admin.microsoft.com](https://admin.microsoft.com).
   - Sign in with your Microsoft 365 admin account. This account must have administrative privileges to create mailboxes and manage settings within the Exchange Admin Center.
   - **Explanation:** The Admin Center is the centralized dashboard where administrative tasks for Microsoft 365 are handled. Only admin accounts can perform configuration tasks like creating shared mailboxes.

2. **Navigate to the Exchange Admin Center:**
   - Once logged into the Admin Center, locate and click on **Show All** in the left-hand sidebar to expand the menu.
   - Under **Admin centers**, click **Exchange**. This will open the Exchange Admin Center, where mailbox-related tasks can be performed.

![image](https://github.com/user-attachments/assets/4a4f83b1-9031-44da-9aa6-e742f2c67cf6)

   - **Explanation:** The Exchange Admin Center (EAC) is the platform used to configure email-related services in Microsoft 365. Shared mailboxes fall under this section, allowing admins to manage mailboxes beyond the typical user mailboxes.

4. **Create the Shared Mailbox:**
   - In the **Exchange Admin Center**, go to **Recipients** > **Shared** from the left-hand menu. This section displays all shared mailboxes in your organization.
   - Click the **+ Add a shared mailbox** button located at the top of the page.
   
![image](https://github.com/user-attachments/assets/1e9b000f-3fb5-4490-9615-6f9bce7b23fd)

   - A form will appear where you need to enter the following details:
     - **Display Name:** Enter a name for the shared mailbox, such as "Support Team" or "Sales Department." This is the name that will be visible to users when they interact with the mailbox.
     - **Email Address:** Enter an email address for the shared mailbox (e.g., support@domain.com). This will be the email address that users will send messages from and receive messages at.
     - Once you have filled in the required information, click **Save** to create the mailbox.
   - **Explanation:** The shared mailbox is now created with the chosen display name and email address. It allows multiple users to access and manage the mailbox, sending and receiving emails on behalf of the team or department.

 ![image](https://github.com/user-attachments/assets/6ed68a34-44ee-409c-8973-f80c2940f7a2)
![image](https://github.com/user-attachments/assets/6472b771-aa10-43f2-ae16-fc624fa9fd2b)

### Step 2: Assign Permissions to the Shared Mailbox
1. **Assign Full Access Permissions:**
   - After the mailbox is created, it will appear in the list of shared mailboxes. Select the mailbox you just created.

![image](https://github.com/user-attachments/assets/99ae7203-7478-4a0a-b43b-7022d757d2af)
![image](https://github.com/user-attachments/assets/1f707fc4-604f-4108-8522-abf4fc37715b)

   - Under the **Mailbox delegation** section, click **Edit** next to **Full Access**. Full access allows a user to read, delete, and manage the emails in the shared mailbox.
   
   ![image](https://github.com/user-attachments/assets/4bf1bb03-e9a2-49d8-8509-2ec8c03a614e)

   - In the dialog box that appears, click the **+** button to add users. A list of users in your organization will be displayed.
   - Select the users who need full access to the mailbox and click **Add**, then **Save**.
   - **Explanation:** Full Access permissions allow users to view, delete, and modify messages in the shared mailbox. These users can operate as though the mailbox belongs to them, but they cannot send emails from it unless they have Send As permissions.

![image](https://github.com/user-attachments/assets/9dacefcd-5143-41cd-878b-6e46a6e29b56)
![image](https://github.com/user-attachments/assets/5114d2b3-d297-4db3-9f3a-9eeefdd1388f)
![image](https://github.com/user-attachments/assets/5a36d486-20d8-4e86-8c21-ba9f7a7ab404)
![image](https://github.com/user-attachments/assets/db7c076a-6ef7-4295-a9d8-46bb2e458aba)

3. **Assign Send As Permissions:**
   - In the **Mailbox delegation** section, click **Edit** next to **Send As**. This permission allows users to send emails as if they are the shared mailbox.

![image](https://github.com/user-attachments/assets/7a1b547b-9d67-44e4-8ed5-762be58234a9)

   - Click the **+** button to add users who will have this permission. Select the appropriate users and click **Add**, then **Save**.
   - **Explanation:** Send As permissions give users the ability to send emails as the shared mailbox itself. This is useful when users need to send emails from a central email address (e.g., support@domain.com) rather than their personal email addresses.

![image](https://github.com/user-attachments/assets/3e9a189a-c018-4195-aef7-50642ada40da)
![image](https://github.com/user-attachments/assets/cbc58310-733d-49cc-9504-e04317c35c7a)
![image](https://github.com/user-attachments/assets/e24e0503-b5bd-4805-ba15-4068255198ef)
![image](https://github.com/user-attachments/assets/77446081-4ae9-49fd-af23-4b147be16674)

5. **Assign Send on Behalf Permissions (Optional):**
   - If users need to send emails on behalf of the shared mailbox (e.g., “John Doe on behalf of support@domain.com”), go to the **Send on Behalf** section and click **Edit**.

![image](https://github.com/user-attachments/assets/f0fb5b34-20d1-4009-94c1-bac0e9cb9ae2)

   - Add users who will send on behalf of the mailbox by clicking the **+** button, selecting users, and clicking **Add** > **Save**.
   - **Explanation:** Send on Behalf permissions allow a user to send an email on behalf of the shared mailbox, with the email indicating that the message was sent by the user on behalf of the shared mailbox.

![image](https://github.com/user-attachments/assets/528b2cd0-6cba-4c20-a294-9d7dc7202a7d)
![image](https://github.com/user-attachments/assets/94e8d442-bd9b-4148-af18-982932129965)
![image](https://github.com/user-attachments/assets/f01b35f9-aa4a-4736-94ba-83c57b64f901)
![image](https://github.com/user-attachments/assets/c9f405cf-0f18-445c-ae41-ff5fee3a4bb3)

### Step 3: Verify Permissions
1. **Check User Access to the Shared Mailbox:**
   - Once permissions are assigned, have the users log into **Outlook** or **Outlook on the Web**.
   - Users with **Full Access** should see the shared mailbox listed under their own mailbox folders. They should be able to read, delete, and move emails within the shared mailbox.
   - Users with **Send As** permissions should be able to send emails from the shared mailbox as though they are the shared mailbox. They should select the shared mailbox from the "From" field when composing a new email.
   - Users with **Send on Behalf** permissions should be able to send emails on behalf of the shared mailbox. The email will display the user’s name followed by “on behalf of” the shared mailbox (e.g., "John Doe on behalf of support@domain.com").
   - **Explanation:** Verifying the permissions ensures that the users can effectively access and send emails from the shared mailbox according to the permissions granted.

### Conclusion

This lab demonstrated how to create a shared mailbox in Microsoft 365 and assign the appropriate permissions: Full Access, Send As, and Send on Behalf to designated users. By completing these steps, IT administrators ensure seamless collaboration across teams by allowing multiple users to access, manage, and send emails from a centralized mailbox. Proper configuration of shared mailboxes supports efficient communication workflows, enhances team productivity, and aligns with Microsoft 365 best practices for shared resource management.
