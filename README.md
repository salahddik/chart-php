# chart-php

sql 
 SELECT 
 MONTHNAME(created) as monthname,
   SUM(amount) as amount
FROM transactions
GROUP BY monthname
