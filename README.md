# Peppa Pig+ - A personal blogging system

### Team Name

Team Peppa Pig Plus

_Team members are:_

- Zhe Liu
- Liwei Zhou
- Zeyuan Liu
- Vincent Su
- Yingrao YI

## Special Setup Instructions

Install the required packages using npm install. The project includes the following dependencies:

- bcrypt

- jest

- supertest

No other special setup instructions are required beyond initializing the database and running the project.

## User Credentials

```
Username: JohnDoe
Password: JohnDoe
```

```
Username: testadmin
Password: testadmin
```

```
Username: JaneDoe
Password: JaneDoe
```

## API Document

Detailed API documentation is available in the file located at [api.md](backend/api.md).

## Web Application Pages Description

##### Home Page: Displays the latest articles and comments, as shown in the screenshot below.

- The unlog page is
  ![](./page-picture/unlog-home.png)
- The loged page is
  ![](./page-picture/homo-login.png)

##### Login Page: Allows users to log into the system.

![](./page-picture/login.png)

##### Singup page: Allow the user sing up to the blog

![](./page-picture/signup.png)

##### Profile Page: Shows user profile information and allow them to modify it.

![](./page-picture/infomation-modify.png)

##### Article Page: Displays a detailed view of a single article along with comments.

![](./page-picture/article.png)

- If the user is the author the page will be
  ![](./page-picture/article-author.png)
  They can see the history of the article and the modify the article

##### Search Page: Shows search result.

![](./page-picture/search.png)

It also have the filter part to check filte the article

![](./page-picture/search-filter.png)

## Java Swing Admin Interface Usage

##### Login Page： Allows admin to log into the system.

![](./page-picture/admin_login.png)

##### Main Page： Show all users.

This layout features a management system interface divided into three main sections:

Left Panel (Current Admin Information): On the left, there's a section displaying the information of the currently logged-in admin. It includes a profile image at the top, followed by a greeting message that says "Hi, [username]!" and a "Logout" button below it.

Center Panel (User List): The central area displays a table containing a list of users with columns for ID, Username, Fullname, Bio, Date of Birth, and Is Admin status. This section provides an overview of user details, including administrative roles.

Top Right Panel (Function Buttons): At the top-right corner, there are two buttons, Refresh and Delete. The Refresh button updates the user list, while the Delete button allows the admin to delete a selected user from the list.

This layout is designed to facilitate user management tasks within a single, organized view.

![](./page-picture/admin_user_list.png)

##### Main Page(user detail)： Show selected user's information.

When a row in the user list is double-clicked, a popup window labeled "User Details" appears, displaying detailed information about the selected user.
This detailed view allows the admin to quickly review comprehensive information about a specific user.

![](./page-picture/admin_user_detail.png)

##### Main Page(user deletion)： Delete selected user.

The admin has the ability to delete selected users from the list; however, the system prevents the admin from deleting other admin users. This restriction ensures that only non-admin accounts can be removed, protecting the integrity and security of administrative accounts.

![](./page-picture/admin_user_deletion.png)

## Additional Instructions

- Our comment system uses soft deletion rather than permanent deletion.

- The project supports article version history.

- Dark mode is implemented for improved user experience.

- Backend has undergone extensive unit testing and Postman testing to ensure reliability.
