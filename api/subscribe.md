# Подписка

Подписка на рассылку

Принимает только один параметр - email-адрес

## Пример:

```javascript
fetch( 'https://netology-trainbooking.netoservices.ru/subscribe?email=hello@kitty.com' )
    .then( response => response.json())
    .then( data => console.log( data ));
```

