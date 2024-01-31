# go_as_second_language
Tips and tricks for a seamless transition to Go from your primary programming language

## Init 2D array of numbers with preset values
```
matrix := [][]int{{1, 2, 3}, {4, 5, 6}, {7, 8, 9}}
```

## Check if a map has a value
```
if val, ok := myMap["foo"]; ok {
    ...
}
```

## String to int
```
number, _ := strconv.Atoi(str)
```

## Append to array
```
arr = append(arr, n)
```
