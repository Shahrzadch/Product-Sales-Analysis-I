**#Product Sales Analysis I**

We have two tables. The first table is Sales with five fields: sale_id, product_id, year, quantity, and price. (sale_id, year) is the primary key (combination of columns with unique values) of this table.
product_id is a foreign key (reference column) to Product table. Each row of this table shows a sale on the product product_id in a certain year. Note that the price is per unit.
The second table is Product with fields of product_id and product_name. product_id is the primary key (column with unique values) of this table. Each row of this table indicates the product name of each product.
Write a solution to report the product_name, year, and price for each sale_id in the Sales table.

Return the resulting table in any order.
