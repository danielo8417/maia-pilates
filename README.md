# WebApp React JS, Tailwind & Vite


<p align="center">
<img src="https://blog.logrocket.com/wp-content/uploads/2022/06/setting-up-dev-environment-react-vite-tailwind.png" />
</p>


### Requirements:

1. Install the packages:
```
$ npm install
```
2. Create a .env file:
```
$ npm run dev
```

### Styles
You can update the `styles/index.css` or create new `.css` files inside `styles/` and import them into your current scss or js files depending on your needs.

### Components
Add more files into your `./src/components` or styles folder as you need them and import them into your current files as needed.

### Pages
Add all the pages like Home, About, Contact or whatever you need. These should be routed in src/App.jsx, don't touch src/main.jsx. Pages shuld contener at list:

alomoves.com buen ejemplo a seguir

```
HOME =>
  Inicio                  
CLASSES =>
   * Que es el pilates  
   * A quien va orientado 
   * Metodologia  
   * Videos del canal   
   * Enlace Instagram
INSTRUCTORS=> 
  * Card con cada instructor 
  * Trayectoria profesional  
  * Foto
CENTER=> 
  * Fotos del centro, cuando pinchas se abre un Carousel
CONTACT=> 
  * Horario  
  * Ubicacion con google maps  
  * Contacto via mail
```             
               

**Note (New changes)**: Components have been converted into functions to support the use of hooks:
* Instead of a class component, we're using a `const` function.
* Class `constructor` and `state` have been replaced by `useState()` hooks.
* `componentDidMount()` was replaced by `useEffect({}, [])` - It runs at mount thanks to the second parameter (`[]`).
* `Actions` and `Store` still work the same way.
