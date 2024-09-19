
```SQL
SELECT * FROM customers;
```

____



```SQL
SELECT *

FROM `products`

WHERE maker = 'B';

```

____

```SQL
SELECT *

FROM `products`

WHERE NOT (maker = 'B');

```

____

```SQL
SELECT *

FROM `pcs`

WHERE speed >= 3.00;

```

____

```SQL
SELECT *

FROM `printers`

WHERE type = 'laser'

AND color = 'TRUE';

```

____

Attempt:

```SQL
SELECT *


FROM `sales` 

WHERE type_of_payment LIKE '%debit%' OR '%credit%';
```

____

Correction:

```SQL
SELECT *

FROM `sales` 

WHERE type_of_payment LIKE '%visa%';
```

____

```SQL
SELECT firstname, lastname, city, address 

FROM customers

WHERE firstname LIKE '%e%' OR lastname LIKE '%e%';
```

____
