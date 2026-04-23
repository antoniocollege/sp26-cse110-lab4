1. values added:  20
2. final result:  20
3. vars cause issue with scope and can be accidentally redefined.
4. values added:  20
5. Error. result is not defined. let is block-scoped and the console log is outside the if statement.
6 and 7. The statements do not get printed because there is an error trying to reassign result. Since it was intialized as a constant, the value cannot be changed.
