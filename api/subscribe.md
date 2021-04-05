# Подписка

Подписка на рассылку

Принимает только один параметр - email-адрес

## Пример:

```javascript
fetch( 'https://fe-diplom.herokuapp.com/subscribe?email=hello@kitty.com' )
    .then( response => response.json())
    .then( data => console.log( data ));
```

