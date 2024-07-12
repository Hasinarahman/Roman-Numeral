# Roman Numeral Converter 🚀

## Project Description 📝

> Roman Numeral Converter  project created in HTML, CSS and javaScript it can convert the number to the Roman Numerals.


### HTML:
```html

  <body>
  <header>
    <h1>ROMAN NUMERAL CONVERTER</h1>
  </header>
  <div class="new">
    <h2>Enter a Number</h2><br>
    <input id="number" type="number">
    <button id="convert-btn">CONVERT</button>
  </div>
  <div id="output"></div>
  <script src="script.js"></script>
</body>

```
### CSS:
```css

#convert-btn {
  width: 30%;
  height: 40px;
  border: none;
  cursor: pointer;
  margin-top: 20px;
  font-size: 12px;
  font-weight: 600;
  border-radius: 5px;
  color: black;
  background: rgb(255, 255, 254);
  box-shadow: 0 4px 8px rgba(3, 3, 3, 0.333);
}



```
### JS:
```javascript

number.addEventListener('keydown', (e) => {
  if (e.key === 'Enter') {
    convert.click();
  }
});

convert.addEventListener('click', () => {
  if (number.value === '') {
    result.innerHTML = 'Please enter a valid number';
    number.value = '';
    return false;
  }
  if (number.value < 0) {
    result.innerHTML = 'Please enter a number greater than or equal to 1';
    number.value = '';
    return false;
  }


```

## Demo 📸

![converter](https://github.com/Hasinarahman/Roman-Numeral/assets/168626170/5d0e43da-ec3b-4f61-b3f2-0d16a166bc0a


## Technologies Used 🛠️

- HTML
- CSS
- JavaScript

## Features ⭐

- Building Roman Numeral Converter

## Author 👩‍💻


- LinkedIn: (linkedin.com/in/hasina-rahmani-4a21a9311)
- Email: (hasinarahmani548@gmail.com)
- GitHub:(https://github.com/Hasinarahman/Roman-Numeral)
