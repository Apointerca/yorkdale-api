# API documentation for Yorkdale


## Edition
While editing, please use `aglio` to compile and render the file locally:
```
aglio --theme-variables slate --theme-style default -s -i src/main/resources/apib/index.apib
```

## Publication
Once finish editing, it's time to push it to apiray.
We need to generate apiary compatible version, please use:
```
aglio --input index.apib --compile --output apiary.apib
```

After that, don't forget to manually replace the header as
```
FORMAT: 1A
HOST: http://apointer.com

# API documentation for Yorkdale
```

Only if you have the header will Apiary able to parse this file properly.
