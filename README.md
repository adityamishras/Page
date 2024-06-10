# PORTFOLIO
Hello Everyone, this a PORTFOLIO using html, Css, and Javascript.

<img src="https://github.com/adityamishras/Page/assets/136791974/2b8c4d10-24ea-4e19-bdf8-42419fac2d73" width="1000"/>
<img src="https://github.com/adityamishras/Page/assets/136791974/b8f55ae3-aa11-45a7-b7a8-262dc67d3837"  width="1000"/>

<img src="https://github.com/adityamishras/Page/assets/136791974/f4c32881-3dac-4daf-867b-7e91a327f610"/>

# Javascript
```javascript
<div><span id="element"></span></div>
```

<video src="https://github.com/adityamishras/Page/assets/136791974/6e81b108-77ba-4402-bd24-c95946497816" autoplay/>

# Javascript
```javascript
<script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    <!-- Setup and start animation! -->
    <script>
      var typed = new Typed("#element", {
        strings: [
          "<b> Web Developer</b>.",
          " <b> Content Creater. </b>",
          " <b> Web Designer. </b>",
          "<b> Web Developer</b>.",
          " <b> Content Creater. </b>",
          " <b> Web Designer. </b>",
        ],
        typeSpeed: 40,
      });
    </script>

```
<img src="https://github.com/adityamishras/Page/assets/136791974/ae242440-8d1b-425d-8e73-dd65390e6cd4"/>

# Navigation Bar 
```html
<div class="navigationbar">
      <div class="nav">
        <img src="images/menu.png" alt="" class="menubtn" onclick="Menubtn()" />
        <img src="images/adilogo.png" alt="" class="logo"/>
        <ul id="MenuItems" class="navlinks">
          <li><a href="index.html">Home</a></li>
          <li><a href="#About">About</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
```
# Javascript
Script For Toggle Menu
```Javascript 
<script>
      var Menuitems = document.getElementById("MenuItems");
      Menuitems.style.maxHeight = "0px";

      function Menubtn() {
          if (Menuitems.style.maxHeight == "0px") {
              Menuitems.style.maxHeight = "400px";
          } else {
              Menuitems.style.maxHeight = "0px";
          }
      }

      // Function to close the menu if clicked outside
      function closeMenu(event) {
          if (!event.target.closest('.nav') && Menuitems.style.maxHeight == "400px") {
              Menuitems.style.maxHeight = "0px";
          }
      }

      // Add event listener to document for clicks
      document.addEventListener('click', closeMenu);
  </script>
```

## Screenshots

![App Screenshot](https://github.com/adityamishras/Calculator/assets/136791974/cf4de489-0705-4a22-8d42-48efb5ffca56)

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://adityamishras.github.io/page/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adityamishras)
[![instagram](https://img.shields.io/badge/instagram-1DA1F2?style=for-the-badge&logo=instagram!&logoColor=white)](https://instagram.com/adityamishras)
