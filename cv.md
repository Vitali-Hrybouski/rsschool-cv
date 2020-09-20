# Vitali Hrybouski

Age: 33

## Contacts

Service | Link
------------ | -------------
Email | harvi2005@mail.ru
Telegram | t.me/harvi_hv
GitHub | https://github.com/Vitali-Hrybouski

### Summary

My life principle is to be an honest and open person. Constantly self-develop and seek communication with the same people.

### Skills

`HTML5` `CSS3`  `JS`  - basic lvl.

### Code examples

```js
solution = function (pocketStr) {  let x = 0;
    let y = 0;
    let a = pocketStr.split(" + ");
    for (let i = 0; i < a.length; i++) {
        if (a[i].includes("коп") == 1) {
            let arr = a[i].split("коп");
            y += +arr[0];
        }
        if (a[i].includes("бун") == 1) {
            let arr = a[i].split("бун");
            x += +arr[0];
        }
    }
    if (y > 99) {
        x += Math.floor(y / 100);
        y -= Math.floor(y / 100) * 100;
    }
    return String(x + "бун" + " " + y + "коп");
};
```
### Tools

- VScode
- Photoshop
- TIA PORTAL V15.0

### Education and Experience

"Belarusian-Russian University" Faculty of Engineering, Automation Engineer.

### Working for Branch of Open Joint-Stock Company "BELAZ" - Holding Company "BELAZ-HOLDING" 

Electronic engineer

### Languages
* English  - A2
* French  - A1

