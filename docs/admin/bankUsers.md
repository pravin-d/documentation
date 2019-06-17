# Manage Bank Users

## View a list of Bank Users details

1. Click on _Banks_ menu item (annotation (1))  
![Bank Users Main Menu](/documentation/images/admin/bankusers/viewall1.png)
2. The item will expand to show two sub-menu items
3. Click on _Users_ sub menu item (annotation(2))  
![Bank Users Main Menu](/documentation/images/admin/bankusers/viewall2.png)
4. Bank Users Users List View
![Bank Users Main Menu](/documentation/images/admin/bankusers/viewall3.png)

#### Bank Users List Page description

The _Bank Users List_ page will display a list of bank users (max 10 at a time) in a table format.

1. Search for a Bank User by name or email  - Annotation (3)
![Bank Users Main Menu](/documentation/images/admin/bankusers/listview2.png)
2. Sort the items based on the given column - Annotation (4)  
**Note :** Sorting can be done only for one column at a time
![Bank Users Main Menu](/documentation/images/admin/bankusers/listview3.png)
3. Navigate to view next/previous 10 bankusers - Annotation (5)
![Bank Users Main Menu](/documentation/images/admin/bankusers/listview4.png)
4. _CurrentPage Page Number_ / _Total Pages_ - Annotation (6)
![Bank Users Main Menu](/documentation/images/admin/bankusers/listview5.png)

## Create a User for a given Bank

1. Navigate to List view. See [Link](#view-a-list-of-bank-users-details)
2. Click on (+) button (annotation (7))  
![Bank Main Menu](/documentation/images/admin/bankusers/createview1.png)
3. Create form popup will appear.
![Bank Main Menu](/documentation/images/admin/bankusers/createview2.png)
4. Enter the required details and click on _Add_ button
5. On success, a success notification will be displayed on top right corner of the screen
6. On failure, a failure notification with error from the server will be displayed  
on the top right corner of the screen

## Update Bank User details

1. Navigate to List view. See [Link](#view-a-list-of-bank-users-details)
2. Click on edit button (annotation (8)). Edit form popup will appear.
![Bank Main Menu](/documentation/images/admin/bankusers/updateview1.png)
3. Edit the required details and click on _Edit_ button
![Bank Main Menu](/documentation/images/admin/bankusers/updateview2.png)
4. By Default, user password is not updated. To reset the password of the User click on  
_Reset Password_ button.
5. On success, a success notification will be displayed on top right corner of the screen
6. On failure, a failure notification with error from the server will be displayed on the  
top right corner of the screen

#### Bank Create/Edit Form Description

1. Email : Email of the User
	- Required field
	- Has to Unique for across all Banks
2. Name : Display Name of the User
	- Required field
3. Password : Password for the given Login
	- Required field
4. Confirm Password : Password for the given Login
	- Required field
	- Should match password field
5. Bank : The Bank to which the User belongs
	- Required field
6. Role : User's role within the Bank
	- Required field

## Delete a Bank User
1. Click on _Trash_ button (annotation (9)).
![Bank Main Menu](/documentation/images/admin/bankusers/deleteview1.png)
2. Delete confirmation popup will appear.
![Bank Main Menu](/documentation/images/admin/bankusers/deleteview2.png)
3. Click on _Delete_ button
4. On success, a success notification will be displayed on top right corner of the screen
5. On failure, a failure notification with error from the server will be displayed on the  
top right corner of the screen

