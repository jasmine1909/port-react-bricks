package.json
"scripts": {
"dev": "next dev",
"build": "next build",
"start": "next start"
"export":"npm run build && next export && mv out \_static"
},
"engine":{
"node:"14.x"
}
