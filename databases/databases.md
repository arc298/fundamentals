# Databases

### What is an index? What is a clustered index?

A database index is a data structure that allows for faster retrieval of data stored in a database. They are created from one or more columns of a table, allowing for fast look-ups that use the columns of the index. A clustered index is a special index that reorders the way records in the table are physically stored. This allows for even greater speed of retrieval when data is accessed sequentially in the same or reverse order of the clustered index.

### What is the HAVING clause and what is it used for?

The HAVING clause is a SQL construct that is used to only return rows that have aggregate values that satisfy a specified condition.

### What is the difference between a LEFT OUTER JOIN and an INNER JOIN

A left outer join will always return all of the records of the left table, even if the join condition does not find any matching records in the right table. In contrast, in an INNER JOIN both the left and right tables must satisfy the join predicate in order to be included in the result set.
