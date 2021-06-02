**The challenge**

0) Fetch items from fake API `http://5af1eee530f9490014ead8c4.mockapi.io/items`

1) Sort fetched items in the next order,

 - children items in list should be connected to their parents (see list.jpg)

```[
    {"id":1,"label":"List item 1","parent_id":0, "children": [
        {"id":5,"label":"List item 5","parent_id":1},
        {"id":6,"label":"List item 6","parent_id":1},
        {"id":7,"label":"List item 7","parent_id":1, "children": [
            {"id":8,"label":"List item 8","parent_id":7},
            {"id":9,"label":"List item 9","parent_id":7}
        ] },
    ]},
    {"id":2,"label":"List item 2","parent_id":0},
    {"id":3,"label":"List item 3","parent_id":0},
    {"id":4,"label":"List item 4","parent_id":0},

]
```


2) Try to optimize application as much as possible 

3) Extra points for adding eslint

4) Extra point for adding unit tests
