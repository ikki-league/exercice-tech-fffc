# This project generates a csv file based on a given data and metada files

## How to execute the program: 

```
node index.js testA/classique.txt testA/metada.txt
```

## How to create a metada file

The file structure is described in a metadata file in csv format with a line for each column defining:

the name of the column, the length of the column, the column type.
### Example:
```
birthay, 10, date
name, 15, chaîne
```

## The file to parse

### Example:
```
1996-04-25Zita
2000-02-13 Marion
```


> [!NOTE]
> The csv file is named info.csv.

- The folder testA contains the classic files and some error management example
- The folder testB contains more than 3 columns and with more line data
- The folder testC contains metada that is incorect
- The folder testD contains a large data file to test
