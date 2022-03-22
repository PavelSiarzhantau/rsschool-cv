# link

---

# Pavel Serzhantov

---

## Contact information

- **Phone:** +375(25) 728-25-76
- **Email:** pavel.siarzhantau@gmail.com
- **Telegram:** @pSerz
- **Linkedln:** **[Pavel Serzhantov](https://www.linkedin.com/in/pavelsiarzhantau/)**
- **Skype:** **[Pavel Serzhantov](live:.cid.2c1b2630d490567a)**

---

## Job objective

To obtain Salesforce Developer junior position in a highly-established company that will help to develop my career.

---

## Professional skills

- Strong communication skills and ability to build relationships at all levels.
- Good understanding of web technologies and OOP principles.
- Basic knowledge of Java, Apex, HTML, CSS, GIT, JS, LWC, Aura, Visualforce,Salesforce.
- Flexible and able to adapt to a changing environment.

---

## Code Example

**Objective:** Given an array of integers.Return an array, where the first element is the count of positives numbers and the second element is sum of negative numbers. 0 is neither positive nor negative.

If the input is an empty array or is null, return an empty array.

**Example:**

```
For input [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, -11, -12, -13, -14, -15], you should return [10, -65].
```
**Solution:**
```
function countPositivesSumNegatives(input) {
      if (!input || input.length  == 0) return [];
      var sum = 0, count = 0; input.forEach(function(el){
         if (el > 0) count++; else sum+=el});
         return [count, sum];
   }
```
