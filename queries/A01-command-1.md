
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

```SQL
SELECT *


FROM `sales` 

WHERE type_of_payment LIKE '%debit%' OR '%credit%';
```

____

```SQL
SELECT *

FROM `sales` 

WHERE type_of_payment LIKE '%visa%';
```

____
