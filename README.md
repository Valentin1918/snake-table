# snake-table
Create a table with n size and fulfill it with numbers by spiral. Can be fulfilled from the top corner or from the center, clockwise of inverse direction depends on incoming parameters.

### Parameters
Add in query string following params:

- **n** --> generated table size

- **direction** -- (right/left) --> numbers will be placed clockwise if param is right and inverse

- **type** -- (rise/fall) --> if fall -- numbers starts from the table center, otherwise from the top corner

### URL example

``` js
http://localhost:8080/snake-table/snake.html?n=6&direction=right&type=fall
```