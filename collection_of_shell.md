## Import Json
mongoimport --db test --collection example --type json --file example.json --jsonArray

### sample json
``` 
mongoimport --db test --collection example --type json --file example.json --jsonArray

Make sure you are using the --jsonArray flag

example.json

[
    {
        "color": "red",
        "value": "#f00"
    },
    {
        "color": "green",
        "value": "#0f0"
    },
    {
        "color": "blue",
        "value": "#00f"
    },
    {
        "color": "cyan",
        "value": "#0ff"
    },
    {
        "color": "magenta",
        "value": "#f0f"
    },
    {
        "color": "yellow",
        "value": "#ff0"
    },
    {
        "color": "black",
        "value": "#000"
    }
]
