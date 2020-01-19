# In The Name of ALLAH 
---
# Command and Query Responsibility Segregation (CQRS) pattern

## Gotta Think 
- if you apply __Microservice Architecture Pattern__ and __Database per service pattern__  as a result :
  - it is no longer straightforward to implement queries that __join data__ from multiple services.
  - if you have applied the __Event sourcing pattern__ then the data is __no longer easily queried__.

## Problem
> How to implement a query that retrieves __data from multiple services__ in a microservice architecture?
