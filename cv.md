# FAMA HARBUNOU


## Contact

* GitHub: [@PG-54](http://github.com/PG-54)
* Telegram: [@PG-54](https://t.me/PG_54)
* Email: [gedonisticussr@gmail.com](mailto:gedonisticussr@gmail.com)
* Phone: [+375-29-678-69-98](tel:+375-29-678-69-98)

## EDUCATION

+ ***The Rolling Scopes School JS/FE course*** (hopefuly)


## Job Experience
Well, i made a game based on "Space Invader" with PyGame library.


## Skills

* JavaScript
* HTML
* CSS
* Git/GitHub
* Photoshop


### Code example:
JS
```
//function that counts letters in strings

function count(string) {
  let obj = {};
  for (ch of string) {
    obj[ch] ? obj[ch]++ : obj[ch] = 1;
  }
  return obj;
}


//function that converts rgb to hex

function rgb(r, g, b) {
  return [r, g, b].map(v => {
    if (v > 255) return 255;
    if (v < 0) return 0;
    return v;
  })
  .map(v => v.toString(16))
  .map(v => v.length == 1 ? '0' + v : v)
  .reduce((v, res) => v + res, '')
  .toUpperCase();
}
```