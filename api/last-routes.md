# Последние направления

GET /routes/last

## Пример

```javascript
fetch( 'https://fe-diplom.herokuapp.com//routes/last' )
    .then( response => response.json())
    .then( data => {
        data.forEach( el => {
            console.log('el', el)
        })
    });
```


