
# Transactions and Impressions

Optionally Admin can upload transactions and impressions in a csv format to the server.

## Upload Transactions and Impressions

1. Click on _Campaign Overviews_ menu item on the sidebar (annotation (1))  
![Campaign Overviews Menu](/documentation/images/admin/co/view1.png)
2. Select a transactions CSV file by clicking on file input (annotation (2)).
3. Select a impressions CSV file by clicking on file input (annotation (3)).
![Campaign Overviews Menu](/documentation/images/admin/co/view2.png)
4. Click on _Upload Doc_ button  
__Note :__ Upload Docs requires both transactions and impressions file. User cannot upload just one doc

### Sample Transactions File Format

```

"bank_id","customer_token","customer_id","campaign_id","branch_id","date","tx_date","tx_amount","tx_commission","createdAt","updatedAt"
"1","1","1","1","1",NULL,"2019-05-02 18:30:00","100","10","2019-06-11 12:41:19","2019-06-11 12:41:19"
"1","2","2","1","2",NULL,"2019-05-03 18:30:00","200","20","2019-06-11 12:41:19","2019-06-11 12:41:19"

``` 

### Sample Impressions File Format

```

"bank_id","customer_token","customer_id","campaign_id","branch_id","user_impression","user_impression_at","user_interaction","user_interaction_at","createdAt","updatedAt"
"1","1","1","1","1",NULL,"2019-05-02 18:30:00",NULL,NULL,"2019-06-11 12:41:19","2019-06-11 12:41:19"
"1","1","1","1","1",NULL,"2019-05-02 18:30:00",NULL,NULL,"2019-06-11 12:41:19","2019-06-11 12:41:19"

```
