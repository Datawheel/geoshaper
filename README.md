# Setup and Installation
`pip install geoshaper`

# Getting started
```
import geoshaper as gsh

gsh.convert("cb_2017_us_division_20m", "topojson", "myfile")


[1] myfile.json has been saved successfully!
```

### convert()
|param|description|default|
|---|---|---|---|
|folder_name|Folder path that includes the shape files to be converted|shapes|
|output_format|Format of the geographical features using JSON notation. Options are `geojson` and `topojson`|geojson|
|output_name|Output filename|output|

