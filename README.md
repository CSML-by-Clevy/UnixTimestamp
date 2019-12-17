# UNIXTIMESTAMP Lambda Function

## Compress
```$ cd src```
```$ zip -r9 ../unixtimestamp.zip index.py```

## Use on CSML Studio
- Create a new function
- Upload the zip file
- Name: as you wish
- Handler: index.handler
- Runtime: python3.6

You can now use it, the function will return the UNIX timestamp as a string.
