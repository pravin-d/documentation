# Manage Brand Users

## View a list of Brand Users details

1. Click on _Brand Users_ sub menu item (annotation(2))  
![Brand Users Main Menu](/documentation/imagesbrand/brandusers/viewall1.png)
2. Brand Users Users List View  
**Note :** The current ___Logged In User___ will not be displayed in the list
![Brand Users Main Menu](/documentation/imagesbrand/brandusers/viewall2.png)

#### Brand Users List Page description

The _Brand Users List_ page will display a list of brand users (max 10 at a time) in a table format.

1. Search for a Brand User by name or email  - Annotation (2)
![Brand Users Main Menu](/documentation/imagesbrand/brandusers/listview1.png)
2. Sort the items based on the given column - Annotation (3)  
**Note :** Sorting can be done only for one column at a time
![Brand Users Main Menu](/documentation/imagesbrand/brandusers/listview2.png)
3. Navigate to view next/previous 10 brandusers - Annotation (4)
![Brand Users Main Menu](/documentation/imagesbrand/brandusers/listview3.png)
4. _CurrentPage Page Number_ / _Total Pages_ - Annotation (5)
![Brand Users Main Menu](/documentation/imagesbrand/brandusers/listview4.png)

## Create a User for a given Brand

1. Navigate to List view. See [Link](#view-a-list-of-brand-users-details)
2. Click on (+) button (annotation (6))  
![Brand Main Menu](/documentation/imagesbrand/brandusers/createview1.png)
3. Create form popup will appear.
![Brand Main Menu](/documentation/imagesbrand/brandusers/createview2.png)
4. Enter the required details and click on _Add_ button
5. On success, a success notification will be displayed on top right corner of the screen
6. On failure, a failure notification with error from the server will be displayed  
on the top right corner of the screen

## Update Brand User details

1. Navigate to List view. See [Link](#view-a-list-of-brand-users-details)
2. Click on edit button (annotation (7)). Edit form popup will appear.
![Brand Main Menu](/documentation/imagesbrand/brandusers/updateview1.png)
3. Edit the required details and click on _Edit_ button
![Brand Main Menu](/documentation/imagesbrand/brandusers/updateview2.png)
4. By Default, user password is not updated. To reset the password of the User click on  
_Reset Password_ button.
5. On success, a success notification will be displayed on top right corner of the screen
6. On failure, a failure notification with error from the server will be displayed on the  
top right corner of the screen

#### Brand Create/Edit Form Description

1. **Email** : Email of the User
	- Required field
	- Has to Unique for across all Brands
2. **Name** : Display Name of the User
	- Required field
3. **Password** : Password for the given Login
	- Required field
4. **Confirm Password** : Password for the given Login
	- Required field
	- Should match password field
5. **Brand** : The Brand to which the User belongs
	- This will be prefilled and is noneditable
6. **Role** : User's role within the Brand
	- Required field

## Delete a Brand User

1. Click on _Trash_ button (annotation (8)).
![Brand Main Menu](/documentation/imagesbrand/brandusers/deleteview1.png)
2. Delete confirmation popup will appear.
![Brand Main Menu](/documentation/imagesbrand/brandusers/deleteview2.png)
3. Click on _Delete_ button
4. On success, a success notification will be displayed on top right corner of the screen
5. On failure, a failure notification with error from the server will be displayed on the  
top right corner of the screen

