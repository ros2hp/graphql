## A Graphql Query Server ##

Supports Query operations only.  

Queries with multiple statements has statements executed concurrently.

Implements the GraphQL specification of 2018: http://spec.graphql.org/June2018/

## Test Scripts ##
```
  cd parser
  go test  -v > test.all.log &
  tail -10f test.all.log
```
