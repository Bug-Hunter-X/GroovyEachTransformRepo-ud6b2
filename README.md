# Groovy each Method Gotcha

This example demonstrates a common mistake when using Groovy's `each` method.  Many new Groovy developers expect `each` to return a transformed list, but it actually returns the original list.

The solution shows how to correctly transform the list using `collect`.