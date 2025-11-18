## Task 1

### Command

```sql
SELECT * FROM products;
```

![alt text](/img/p1_image1.png)

### Command

```sql
SELECT name, phone FROM shippers;
```

![alt text](/img/p1_image2.png)

## Task 2

```sql
SELECT AVG(price) FROM products;
```

![alt text](img/p2_image3.png)

```sql
SELECT MIN(price) FROM products;
```

![alt text](img/p2_image4.png)

```sql
SELECT MAX(price) FROM products;
```

![alt text](img/p2_image5.png)

## Task 3

```sql
SELECT DISTINCT category_id, price FROM products;
```

![alt text](img/p3_image6.png)

```sql
SELECT DISTINCT category_id, price 
FROM products 
ORDER BY price
LIMIT 10;
```

![alt text](img/p3_image7.png)

## Task 4

```sql
SELECT COUNT(id) 
FROM products 
WHERE price > 20 AND price < 100;
```

![alt text](img/p4_image7.png)

## Task 5

```sql
SELECT supplier_id, COUNT(id), AVG(price)
FROM products 
GROUP BY supplier_id
```

![alt text](img/p5_image8.png)