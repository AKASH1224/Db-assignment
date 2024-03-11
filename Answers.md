Ques 1-
Ans 1:-The relationship between Product and Product Category is One-To-many. This means single product can belong to one category,but a category can have many products assigned to it.
Ques2 -
Ans 2:- There are two ways to ensure that each product in the "Product" table has a valid category assigned to it:
     1. Database Constraints : you can set up a database constraints on the "category_id" column in the "Product" table. This constraint can be a foreign key reference to the "id" 
        column in the "product_category" table. This would ensure that any value entered into the "category_id" column must exist as a valid category ID in the "product_category" 
        table.

2.    Application Logic: You can implement application logic to ensure that a category is selected before a product is saved. This could be done through a form validation rule or a business rule within your application code.
