<h1>Question 2 </h1>

**Problem Statement:** Joy is really happy with the simple search method you
developed in the previous section. But now he wants to build a user
interface for it and also want to connect it with a real data source (REST
API).

For solving this problem, We have some datasets with. 


```json
{
    "error": false,
    "cafes": [{
        "name": "Bazaar Cafe",
        "location_id": "kjk234g4gcvfx8usg1l33pi"
    }, {
        "name": "Ashley's Cafe",
        "location_id": "asjdh8hftys0kght2yskyvy"
    }, {
        "name": "Avenue Cafe",
        "location_id": "skjd86svvfdrsv55svbvf3f"
    }, {
        "name": "Hi-Lo Cafe",
        "location_id": "mjdhgetr4pojfyts22fzfsh"
    }, {
        "name": "California Chicken Cafe",
        "location_id": "12hydbdf76sljfts87sbfis"
    }, {
        "name": "Corner Bakery Cafe",
        "location_id": "jahgde7wgdiau8ewsahgosd"
    }, {
        "name": "Philz Coffee",
        "location_id": "urhw3837ehalod7w02b7835"
    }, {
        "name": "The Alma Gathering Cafe",
        "location_id": "mjdhgetr4pojfyts22fzfsh"
    }, {
        "name": "Lakeland Memory Cafe",
        "location_id": "jahgde7wgdiau8ewsahgosd"
    }, {
        "name": "Baron Memory Cafe",
        "location_id": "kjk234g4gcvfx8usg1l33pi"
    }, {
        "name": "Lakeshores Memory Cafe",
        "location_id": "mjdhgetr4pojfyts22fzfsh"
    }, {
        "name": "Monarch Memory Cafe",
        "location_id": "jahgde7wgdiau8ewsahgosd"
    }]
}
```


```json
{
  "error": false,
  "places": [
    {
      "id": "jahgde7wgdiau8ewsahgosd",
      "street_no": "60H",
      "locality": "Solomos Island Road",
      "postal_code": "20688",
      "lat": "36.7783 N",
      "long": "119.4179 W"
    },
    {
      "id": "12hydbdf76sljfts87sbfis",
      "street_no": "1B",
      "locality": "Macarthur Blvd",
      "postal_code": "20619",
      "lat": "38.1781 N",
      "long": "118.4171 W"
    },
    {
      "id": "kjk234g4gcvfx8usg1l33pi",
      "street_no": "45250",
      "locality": "Worth Avenue, Unit A",
      "postal_code": "20619",
      "lat": "36.1152",
      "long": "117.521"
    },
    {
      "id": "saswe3s6yydtdr52hsd72yst",
      "street_no": "1X",
      "locality": "Macarthur Blvd",
      "postal_code": "20687",
      "lat": "36.7783",
      "long": "119.4179"
    },
    {
      "id": "skjd86svvfdrsv55svbvf3f",
      "street_no": "7S",
      "locality": "Three Notch Road",
      "postal_code": "20619",
      "lat": "36.83",
      "long": "119.6"
    },
    {
      "id": "asjdh8hftys0kght2yskyvy",
      "street_no": "1B",
      "locality": "Ambey Mantion",
      "postal_code": "29087",
      "lat": "31.21",
      "long": "119.7"
    },
    {
      "id": "mjdhgetr4pojfyts22fzfsh",
      "street_no": "22803",
      "locality": "Gunston Dr Lexington Park",
      "postal_code": "20688",
      "lat": "35.7788",
      "long": "119.979"
    },
    {
      "id": "urhw3837ehalod7w02b7835",
      "street_no": "225",
      "locality": "Macarthur Blvd",
      "postal_code": "20687",
      "lat": "35.77813",
      "long": "119.41791"
    }
  ]
}
```

_output:_
![Sample Image](https://camo.githubusercontent.com/a89506ffb5d7f8d01f10603971011b8cbd93435d68cb149e3e2e8cc1c9d6bf0f/68747470733a2f2f7265732e636c6f7564696e6172792e636f6d2f647161666d623033322f696d6167652f75706c6f61642f76313537303630353331362f6363642e706e67)
