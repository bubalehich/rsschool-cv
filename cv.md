# Yana Vlasova
### Backend Developer

---

### Contacts:

 - **E-mail:** janeridebmx@gmail.com<br>
 - **Telegram:** @bubalehich<br>
 - [LinkedIn](https://www.linkedin.com/in/jane-bmx/)<br>

### Skills and Proficiency:

- PHP 7+, Symfony Framework, API Platform 
- Java 8+, Spring
- HTML5, CSS3, Js
- IntelliJ IDEA, PHP Storm, VS Code  
- MySQL, PostgreSQL
- Docker

---

### Code example:

```js
const fs = require('fs');
const crypto = require('crypto');
const files = fs.readdirSync(process.cwd());
files.forEach(file => {
    fs.readFile(file, function (err, data) {
        if (err) {
            console.error(err);
        } else {
            console.log(crypto.createHash('sha3-256')
                .update(data)
                .digest('hex') + ' ' + file);
        }
    })
})
```

---

## Education
 * BSUIR (Faculty of Infocommunications, 2022)
 * Java Web Development Training (Epam, 2020)

---

### Languages:

- English \- Intermediate/Upper-intermediate
- Russian \- Native
