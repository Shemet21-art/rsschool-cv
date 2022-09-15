#Shemet Ihor
### Junior Frontend Developer

---

### Contact information:

**Phone:** +38 066 212 333 7 <br>
**E-mail:** shemetttttttt8@@gmail.com<br>

---



### Skills and Proficiency:

- HTML5, CSS3, js, bootstrap, react
- JavaScript Basics
- Git, GitHub
- VS Code, IntelliJ IDEA
- Adobe Photoshop, Illustrator, InDesign

---

### Code example:

**Peak array index KATA from CODEWARS:**
*Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.*

```javascript
function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```
---



### Languages:

- English \- B1
- Russian \- Native
- Ukrainian \- Intermediate
- Polish \- Basic
