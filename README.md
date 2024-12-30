# Kotlin MutableList removeIf() Gotcha

This repository demonstrates a subtle issue when using the `removeIf()` function with a `MutableList` in Kotlin.  Modifying the list during iteration with `removeIf()` can lead to unexpected results, skipping elements that would otherwise be removed.

The `bug.kt` file shows the problem. The solution, `bugSolution.kt`, demonstrates a correct and efficient way to remove elements from a list.