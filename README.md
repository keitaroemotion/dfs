# MySQL Dump File Sorter (DFS)

This script is written for the following demands:

1. My boss wants mysqldump file
2. He is not happy with auto generated comments, except Table description
3. The scope of 2. is `/* ... */` part also should be eliminated
4. The requirement means dumped mysql file injection fails (since FK keys binding fails)
5. He told me manually change the order of table is fine
6. But this table schema change happens frequently. Should I manually change the order each time I dump?
7. I think 6. is insane and inhumane way as developer.

## Installation

Just move this to `/usr/local/bin` or any such kind of accessible directory, and chmod +x the file.

## Usage

```
dfs [your sql file path]
```

## Contact

`tobasojyo@gmail.com`
