### Hello!

This app can transform string into valid BIT code, beautify by inserting spaces and breaks and parse into its printing function output afterwards.

[Learn about BIT](http://www.dangermouse.net/esoteric/bit.html)

``` 
node BIT.js nameOfFunc argument
```

#### Functions list:
```
- beautify:
  argument - './path/to/file' with minified BIT code block;
  output   - file with unminified code 'BIT_beautified.txt'
- printBIT:
  argument - 'string' to transform into BIT code;
  output   - file with minified BIT code 'BIT_input.txt'
- decipher:
  argument - './path/to/file' with minified BIT code block
  output   - deciphred BIT code into readable string 'BIT_decompiled.txt'
```
### You can read documentation about every function in /functions folder.
