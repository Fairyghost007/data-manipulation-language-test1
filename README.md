# data-manipulation-language-test1

# SQL Insert Statements

## Product Table

```sql
INSERT INTO Product (Product_id, Product_Name, Category, Price) VALUES
('P01', 'Samsung Galaxy S20', 'Smartphone', 3299),
('P02', 'ASUS Notebook', 'PC', 4599);
```
## Customer Table

```sql
INSERT INTO Customer (Customer_id, Customer_Name, Customer_Tel) VALUES
('C01', 'Ali', '71321009'),
('C02', 'ASMA', '77345823');
```

## Orders Table

```sql
INSERT INTO Orders (Customer_id, Product_id, OrderDate, Quantity, Total_amount) VALUES
('C01', 'P02', '27/05/2020', 2, 9198),
('C02', 'P01', '28/05/2020', 1, 3299);
```
