# scala

Run scale console by typing `sbt console` to run commands like Python IDLE.

## Data Types

- Int (32-bit)
- Double (64-bit)
- Boolean (t/f)
- String (text)

## Notes

- Infix expressions can be used to remove `.` and `()` from compact expressions while keeping the answer and solutions intact throughout. For example:

```scala
1.to(10) == 1 to 10
```

- `def` vs `val`: In `val`, the right hand side is evaluated as soon as it is reached upon and the value is referred to instead of variable. However, in `def` each time evaluation is done. 

- Functions are defined by sort of Python syntax:

```scala
def myFunction(variableName: dataType) = or : doSomethingHere
```

Funtion argumanets are evaluated from left to right.

### Outputs

**Ch #1: Terms and Types:**

```scala
scala> 16.toHexString
res0: String = 10

scala> "bar".take(2)
res1: String = ba

scala> (0 until 10).contains(10)
res2: Boolean = false
```
