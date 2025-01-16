## daystack

Este paquete es una combinacion con [dayjs](https://www.npmjs.com/package/dayjs) en la cual agregamos 3 metodos, las cuales son:

- formatDate
- isWeekend
- isValidDate

## install

```
npm install daystack
```

## examples

```js
const daystack = require("daystack");
const response = daystack.formatDate(new Date(), "DD/MM/YYYY");
console.log(response, "response");
```
