# Bible Reference
This repository is how any one can reference any bible version in any language provided.

# How Does It Word?
Reference
```
fetch('https://raw.githubusercontent.com/BenjaminBurnell/bible/main/{version}-{language}/{book}.js') //Example: 'https://raw.githubusercontent.com/BenjaminBurnell/bible/main/NIV-EN/JHN.js'
.then((response) => response.json())
.then((data) => console.log(data))
```
