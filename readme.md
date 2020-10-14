# Convert SQL Server tables to entities

1. Go to SQL Management Studio and select the table you want to parse
2. Right click on the table -> Script table as -> Create to -> New Query Window
3. Copy the columns (only the columns) to the `table` variable in `table-to-entity.js`
4. Save
5. From cmd run
    ```bash
    node table-to-entity.js
    ```