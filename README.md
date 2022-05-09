# Project-DEEQU-for-DATA-QUALITY
Using DeeQU to asses the quality of dataframe

From an external source system you are supplied with data about available shoe products. Using the capabilities of pydeequ, develop a data analysis task.

**Dataset Structure**

| Name |	Description |
| -- | -- |
| id |	Unique object identifier |
| vendor_code |	Unique position (product) identifier |
| name |	Model name |
| type |	Type of model |
| label |	Brand |
| price |	Price ($) |
| discount |	Discount in percents [0-100] |
| available_count |	Quantity available in stock |
| preorder_count |	Quantity of preorders |

The task is to analyze the following conditions:

1. The size of the dataset
2. Completeness of all columns (x9)
3. Uniqueness of the id
4. Are there any records with a discount less than 0
5. Records with a discount of more than 100 are present
6. Are records present with available quantity in stock less than 0
7. Are there records with a quantity of pre-orders less than 0
8. The report must contain a total of 15 conditions.
