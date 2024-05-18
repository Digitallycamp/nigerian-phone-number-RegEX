# nigerian-phone-number-RegEX
Regulart expreesion for Nigerian phone numbers

```js
  /** Supports +234, 234, or without country code
let RegEx =/^(?:(?:(?:\+?234(?:\h1)?|01)\h*)?(?:\(\d{3}\)|\d{3})|\d{4})(?:\W*\d{3})?\W*\d{4}$/;
const phoneRegExp =/(?:(?:(?:\+?234(?:\h1)?|01)\h*)?(?:\(\d{3}\)|\d{3})|\d{4})(?:\W*\d{3})?\W*\d{4}(?!\d)/;
console.log(phone.match(phoneRegExp));

```
RFERENCE: https://stackoverflow.com/questions/70182264/issue-with-a-regex-to-validate-the-nigerian-phone-numbering-system
