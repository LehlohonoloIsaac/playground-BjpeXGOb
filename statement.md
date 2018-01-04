# Welcome!

This Swift template gives an example of using Collections

```swift runnable
// Collecitons
/*#################################*/

// Create an array of all odd squares of 1-20 using map and filter

let oneToTen = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20]
var oddSquares = oneToTen.map { $0 * $0 }.filter { $0 % 2 != 0 }
print(oddSquares)
```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced Swift template](https://tech.io/select-repo/575)
