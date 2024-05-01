# Devtools Part 2

1. The bug was that the values were being treated as strings getting concatenated rather than being treated as numbers getting added.
2. In the `calculateSum()` method, I used the `parseInt()` function on `num1` and `num2` so that when they got added together their values would be summed, rather than their string representations getting concatenated. 
