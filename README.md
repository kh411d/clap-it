# Clap-it (Frontend)

a medium-like Clap button made with [Svelte](https://svelte.dev/) custom web component

### Install

```
$ node -v
v11.15.0

$ npm install
$ npm run build && npm run start
```

### Usage

Move `public/build/bundle.js` to your webhost and then add this code to your web page, 

```
<script src='bundle.js'></script>
<clap-it style="" api=""/>
```

###### Tag Attributes

- style, css need to be inline i.e. `width:60px; height:60px; margin-top:30px; fill:red; stroke:red; color:red;`
- api, Base API URL i.e `http://0.0.0.0:3000`, make use of your own API

### Demo

[Live on CODEPEN](https://codepen.io/kh411d/full/eYZQYWZ)
