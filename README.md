# Python Math Functions Example

This repository demonstrates various mathematical functions available in Python through the `math` module. The functions include factorials, radians, trigonometric functions, logarithms, and more. 

## Features
- **Factorial**: Calculate the factorial of a number.
- **Radians**: Convert degrees to radians.
- **Trigonometric functions**: Sin, Cos, Tan, and more.
- **Logarithms and Exponentiation**: Compute logarithms and power.
- **Time and Mathematical Constants**: Work with timestamps, constants like `math.e` and `math.pi`.

## math factorial
```
print(math.factorial(6))  # 720
print(math.factorial(5))  # 120
print(math.factorial(3))  # 6
print(math.factorial(0))  # 1
```

## math radians
```
print(math.radians(180))  # 3.141592653589793
```

## math acos
```
print(math.acos(0.5))  # 0.6761305095606613
```

## math.ldexp
```
print(math.ldexp(5, 4))  # 80.0
```

## math.erfc
```
print(math.erfc(1))  # 1.6715105790914593e-07
```

## math fsum
```
print(math.fsum([1.1, 2.2]))  # 3.3
```

## math comb
```
print(math.comb(14, 2))  # 91
```

## math fmod
```
print(math.fmod(10, 3))  # 1.0
```

## math.inf
```
print(math.inf)  # inf
print(-math.inf)  # -inf
```

## math log
```
print(math.log(23))  # 3.1354942159291497
```

## math tau
```
print(math.tau)  # 6.283185307179586
```

## time example
```
print(time.time())  # Timestamp in seconds
print(time.ctime())  # Human-readable format
```

## power example
```
print(pow(4, 3))  # 64
```

## math fabs
```
print(math.fabs(-13.4))  # 13.4
```

## math isfinite
```
print(math.isfinite(100))  # True
```

## math isinf
```
print(math.isinf(math.inf))  # True
```

## math floor
```
print(math.floor(11.7))  # 11
print(math.floor(-11.7))  # -12
```

## arc sine function
```
print(math.asin(1))  # 1.5707963267948966
```

## math copysign
```
print(math.copysign(24, -35))  # -24.0
```
## sin, cos, tan
```
print(math.sin(math.pi / 4))  # 0.7071067811865476
print(math.cos(math.pi / 4))  # 0.7071067811865476
print(math.tan(math.pi / 4))  # 0.9999999999999999
```

## Euler's Number
```
print(math.e)  # 2.718281828459045
```

## math ceil and floor
```
print(math.ceil(2.3))  # 3
print(math.floor(2.3))  # 2
```

## min and max
```
print(min(5, 25))  # 5
print(max(5, 25))  # 25
```

## round function
```
print(round(5.6))  # 6
print(round(5.4))  # 5
```

