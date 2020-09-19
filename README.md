# Clap-it (Frontend)

a medium-like Clap button made with Svelte custom web component

### Install

```
$ node -v
v11.15.0

$ npm install
$ npm run build && npm run start
```

### Usage

Add this code on your web page, 

```
	<script src='bundle.js'></script>
	<clap-it style="width:60px;height:60px;margin-top:30px;fill:red;stroke:red;color:red;" api="http://0.0.0.0:3000"/>
```

###### Tag Attributes

style
: inline css properties
api
: you can add your own base API URL backend or you can host my ready-made serverless backend [https://github.com/kh411d/clapi](https://github.com/kh411d/clapi)