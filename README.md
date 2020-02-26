# money-manager-ss-fake-db

## example transaction

```
    {
      "id": 1,
      "TransCode": -1, // -1 withdraw, 1 deposit, 0 transfer
      "AccountID": 1,
      "ToAccountID": null, // only have value when transfer
      "SubCategoryID": 1,
      "CategoryID": 1,
      "PayeeID": 1,
      "Notes": "shopping",
      "Amount": 100,
      "ToAmount": 0, // be 0, if it is not transfer
    }
```
