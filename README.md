# Unexpected Behavior of map() on MutableList in Kotlin

This code demonstrates a subtle difference between using the `map()` function on immutable and mutable lists in Kotlin.  While `map()` creates a new list containing the transformed elements when used with an immutable list, it doesn't modify the original mutable list directly; instead, it returns a new list.

The solution illustrates how to modify the mutable list in place using other collection functions like `mapIndexedTo` or an explicit loop.