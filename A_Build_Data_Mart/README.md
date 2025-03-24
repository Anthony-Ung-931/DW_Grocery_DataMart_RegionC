## Subdirectory prefixed with `A` to denote that this is not actually for any deliverable.

Overall strategy:
- For the Store and Date dimensions,  
    &nbsp;  I will refactor Gideon's and Sean's code into a fresh Jupyter notebook  
    &nbsp;  to dump their records into a database table instead of a CSV.

- For the product dimension,  
    &nbsp;  I will take the CSV that was generated in its subdirectory  
    &nbsp;  since there are so many edge cases.

- I will also create a pipeline from each individual database.

- The fact tables will be generated in the following order:
  - Sales Fact (Transaction)
  - Sales Fact (Daily)
  - Inventory Fact (Daily)
  - Inventory Fact (Quarterly)