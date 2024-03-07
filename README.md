# Go as second language
Tips and tricks for a seamless transition to Go from your primary programming language

## How to init a 2D array of numbers with predefined values in Go
```
matrix := [][]int{{1, 2, 3}, {4, 5, 6}, {7, 8, 9}}
```

## How to determine if a value exists in a map in Go
```
if val, ok := myMap["foo"]; ok {
    // ...
}
```

## How to convert strings to integers in Go
```
number, _ := strconv.Atoi(str)
```

## How to append a value to an array in Go
```
arr = append(arr, n)
```

## How to prepend a value to an array in Go
```
values := []string{"World", "!"}
prependValue := "Hello"
values = append([]string{prependValue}, values...)
```

## How to remove last element of array in Go
```
stack = stack[:len(stack)-1]
```

## How to return error in Go
```
func fooBar() error {
    // ...
    return errors.New("It's the wrong castle")
}
```

## How to write foreach loop in Go
```
for i, n := range nums {
    // ...
}
```

## How to write while loop in Go
```
for isValid {
    // ...
}
```

## How to write for loop with counter in Go
```
for i := 0; i < n; i++ {
    // ...
}
```

## Function argument with "any" type in Go
```
func foo(value interface{}) error {
    // ...
}
```

## Json encode in Go
```
jsonString, err := json.Marshal(value)
```

## Json decode in Go
```
err = json.Unmarshal(jsonString, &value)
```

## How to implode (join) strings in Go
```
answer := strings.Join(items, ", ")
```

## How to print something in Go
```
fmt.Println("Hello world")
```

## Ellipsis, variadic functions, variable number of arguments in function in Go
```
func foo(nums ...int) {
	// ...
	for _, num := range nums {
		// ...
	}
	// ...
}

// ...

foo(1, 2, 3)
```
