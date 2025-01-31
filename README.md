# Kotlin Nullable List and map() Function
This example demonstrates a potential NullPointerException when using the `map()` function on a nullable list in Kotlin. The `map()` function, when applied to a null list, returns null instead of an empty list, potentially leading to unexpected behavior or crashes in your code.

The solution demonstrates how to handle this by using the safe call operator and providing a default value when the list is null.  This prevents the `NullPointerException` and ensures that the code functions as expected, even with nullable input.