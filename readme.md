# User Interface Technical Specification

## 1.Introduction
  This document describes how users interact with the interface.

## 2.Interface scope
This document includes the UI components, the state of the page and the situations that users will encounter.
## 3.Overview


![Home](https://lists.office.com/Images/969df1bb-97b6-44ef-9108-dc18a5fd96c2/298428f6-6729-4501-a9de-dcaf554877fe/T1RGZ5H7YQMWKPQXFLFIUG5UQ1/c2f1cb7e-5022-433a-93a2-1ac0b6ec1015)

* The "+New User" button will be used to add a new user to the system.The action of the page in case of use is shown in the figure.
 
  * In this section, user name, displayname, phone, mail, user roles (Guest, Admin, Superadmin) should be included.
  
  * In addition, the user's enabled status should be selected
    

*  [] "Hide Disabled User"  will be used to hide inactive users on the system.
   
* The "Save User" button will be used to save the user information entered in the "New User" section to the database.
  

  
* In the table where we list the users, there should be user ID, username, email and the user's activity status.
  
  * | ID  | Username  |Email   | Enabled  |
    | ------------ | ------------ | ------------ | ------------ |
    |  1 |AdminUser | admin@piworks.net  |  true |
    |  2 | TestUser  | testuser@piworks.net  | true  |

  * "ID" must be unique and must be given by user registration.
  
  *  The status of the "Enabled" column should be selected in the "New User" section.
    