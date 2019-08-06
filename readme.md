
# US Congresses

These export files represent all US Congresses that have taken place since March 4,1789.

**Downloads**

| File | Type |
| --- | --- |
| [congresses.json](congresses.json) | JSON |
| [congresses.yaml](congresses.yaml) | YAML |

## JSON Data Format

Each Congress is given in the following format.

```
{
    "1st Congress": {
        "name": "1st Congress",
        "date_start": "1789-03-04T17:56:13.000000Z",
        "date_end": "1791-03-03T17:56:13.000000Z",
        "sessions": [
            {
                "name": "1st session",
                "date_start": "1789-03-04T17:56:13.000000Z",
                "date_end": "1789-09-29T17:56:13.000000Z"
            },
            {
                "name": "2nd session",
                "date_start": "1790-01-04T17:56:13.000000Z",
                "date_end": "1790-08-12T17:56:13.000000Z"
            },
            {
                "name": "3rd session",
                "date_start": "1790-12-06T17:56:13.000000Z",
                "date_end": "1791-03-03T17:56:13.000000Z"
            }
        ]
    },
    "2nd Congress": {
```

# YAML Format

Each Congress is given in the following format.

```
name: '1st Congress'
date_start: 1789-03-04T18:42:37+00:00
date_end: 1791-03-03T18:42:37+00:00
sessions: [{ name: '1st session', date_start: 1789-03-04T18:42:37+00:00, date_end: 1789-09-29T18:42:37+00:00 }, { name: '2nd session', date_start: 1790-01-04T18:42:37+00:00, date_end: 1790-08-12T18:42:37+00:00 }, { name: '3rd session', date_start: 1790-12-06T18:42:37+00:00, date_end: 1791-03-03T18:42:37+00:00 }]

```


## License

This work is public domain, please use it as you wish.
