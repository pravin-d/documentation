# Manage Brands

## View all Brands
1. Click on _Brands_ menu item (annotation (1))  
![Brand Main Menu](/images/bank/brands/viewall1.png)
2. The item will expand to show two sub-menu items
3. Click on _List_ sub menu item (annotation(2))  
![Brand Main Menu](/images/bank/brands/viewall2.png)
4. Brand List View
![Brand Main Menu](/images/bank/brands/listview1.png)

#### List Page description

The _Brands list_ page will display a list of brands (max 10 at a time) in a table format.

1. Search for a Brand by name  - Annotation (3)
![Brand Main Menu](/images/bank/brands/listview2.png)
2. Sort the items based on the given column - Annotation (4)  
**Note :** Sorting can be done only for one column at a time
![Brand Main Menu](/images/bank/brands/listview3.png)
3. Navigate to view next/previous 10 brands - Annotation (5)
![Brand Main Menu](/images/bank/brands/listview4.png)
4. _CurrentPage Page Number_ / _Total Pages_ - Annotation (6)
![Brand Main Menu](/images/bank/brands/listview5.png)

## Create a Brand

1. Navigate to List view. See [Link](#view-all-brands)
2. Click on (+) button (annotation (7)).
![Brand Main Menu](/images/bank/brands/createview1.png)
3. Create form popup will appear.  
Screenshot 1
![Brand Main Menu](/images/bank/brands/createview2.png)  
Screenshot 2
![Brand Main Menu](/images/bank/brands/createview3.png)
4. Enter the required details and click on _Add_ button at the bottom of the Popup (refer to Screenshot 2)  
**Note :** Click on the placeholder image (annotation (8)) to upload Brand Logo.
![Brand Main Menu](/images/bank/brands/createview4.png)
5. On success, a success notification will be displayed on top right corner of the screen
6. On failure, a failure notification with error from the server will be displayed  
on the top right corner of the screen

## Bulk Create Brands

1. Navigate to List view. See [Link](#view-all-brands)
2. Click on _cloud_ button (annotation (9)).
![Brand Main Menu](/images/bank/brands/bulkcreateview1.png)
3. File upload popup will appear.
![Brand Main Menu](/images/bank/brands/bulkcreateview2.png)
3. Select a brands CSV file by clicking on file input.
4. Click on _Upload_ button to upload the file
5. On success, a success notification will be displayed on top right corner of the screen
6. On failure, a failure notification with error from the server will be displayed  
on the top right corner of the screen

### Sample CSV Brands

```

"name","bank_id","website","registration_id","registered_address","description","logo"
"Brand 1 of Bank 1","1","http://52.66.207.191:8001/future1","324sdfsdk22","sdfh dsflsdf","This is seed data for Brand 1 of Bank 1",NULL
"Brand 2 of Bank 1","1","http://52.66.207.191:8002/future2","324sdfsdk22","sdfh dsflsdf","This is seed data for Brand 2 of Bank 1",NULL

```


## Update Brand details

1. Navigate to List view. See [Link](#view-all-brands)
2. Click on edit button (annotation (10)).
![Brand Main Menu](/images/bank/brands/updateview1.png)
3. Edit form popup will appear with prefilled Brand data  
Screenshot 1
![Brand Main Menu](/images/bank/brands/updateview2.png)
Screenshot 2
![Brand Main Menu](/images/bank/brands/updateview3.png)
4. Edit the required details and click on _Edit_ button
5. On success, a success notification will be displayed on top right corner of the screen
6. On failure, a failure notification with error from the server will be displayed on the  
top right corner of the screen

#### Brand Create/Edit Form Description

1. Brand Logo
	- Brand Logo Image.
2. Name : Name of the Brand
	- Required field
	- Has to Unique for a given Bank
3. Bank : The Bank to which the Brand will be associated to.
	- Required field
4. Registered Address : Registered Address of the Brand
	- Required field
5. Registration Id : Brand's Registration Id
	- Required field
6. Website : Link to Brand's webpage
	- Required field
7. Description : Description of the Brand
	- Required field


## Delete a Brand

1. Navigate to List view. See [Link](#view-all-brands)
2. Click on _Trash_ button (annotation (11)).
![Brand Main Menu](/images/bank/brands/deleteview1.png)
3. Delete confirmation popup will appear.
![Brand Main Menu](/images/bank/brands/deleteview2.png)
4. Click on _Delete_ button
5. On success, a success notification will be displayed on top right corner of the screen
6. On failure, a failure notification with error from the server will be displayed on the  
top right corner of the screen

