MySQL for Beginners
## คำสั่ง SELECT
```
SELECT column1, column2, ...
FROM table_name;
```

```
SELECT * FROM table_name;
```

## คำสั่ง WHERE
```
SELECT column1, column2, ...
FROM table_name
WHERE condition;
```
### Note: WHERE นอกจากสามารถใช้กับ SELECT ยังสามารถใช้กับ UPDATE, DELETE ได้
ตัวดำเนินการดังต่อไปนี้ที่สามารถใช้กับ WHERE ได้
=, <, >, >=, <=, <>, BETWEEN, LIKE, IN, AND, OR, NOT

## คำสั่ง ORDER BY
default เรียงลำดับจากน้อยไปมาก ascending

```
SELECT column1, column2, ...
FROM table_name
ORDER BY column1, column2, ... ASC|DESC;
```

