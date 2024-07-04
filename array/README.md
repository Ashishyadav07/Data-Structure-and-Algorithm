## Array

- It is a collection of data element of specified data types.
- All data elements have contiguos memory location.
- Size of array is fixed and cannot be modified once it is created.
- Being adjacent each partition is indexed and can be determined by its position.
- Index starts at 0 and ends at length - 1.

## Declaration of one dimensional array

```java
//First: datatype variableName[];
int myArray[];

//Second: datatype[] variableName;
int[] myArray;

```

## Initialization of one dimensional array

- Using new operator: variableName = new datatype[size]; 
- Combining declaration and initialization: datatype[] variableName = new datatype[size];
- Initializing with values: datatype[] variableName = {value1, value2, ...};
- Example: ```java int[] myArray = new int[5]; ```

## Default value of array of different data types

- int: 0
- float: 0.0
- boolean: false
- String: null
- User defined type: null





