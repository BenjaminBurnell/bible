# Bible Reference
This repository is how any one can reference any bible version in any language provided.

# How Does It Work?
### Reference
URL = 'https://raw.githubusercontent.com/BenjaminBurnell/bible/main/{version}-{language}/{book}.js' // Example: 'https://raw.githubusercontent.com/BenjaminBurnell/bible/main/NIV-EN/JHN.js'.
fetch(URL) 
.then((response) => response.json())
.then((data) => console.log(data)) // Get the data and log it.
```
### Format
```
// The Books are in order (GENESIS - REVELATION)
BOOKS = ["GEN", "EXO", "LEV", "NUM", "DEU", "JOS", "JDG", "RUT", "1SA", "2SA", "1KI", "2KI", "1CH", "2CH", "EZR", "NEH", "EST", "JOB", "PSA", "PRO", "ECC", "SNG", "ISA", "JER", "LAM", "EZK", "DAN", "HOS", "JOL", "AMO", "OBA", "JON", "MIC", "NAM", "HAB", "ZEP", "HAG", "ZEC", "MAL", "MAT", "MRK", "LUK", "JHN", "ACT", "ROM", "1CO", "2CO", "GAL", "EPH", "PHP", "COL", "1TH", "2TH", "1TI", "2TI", "TIT", "PHM", "HEB", "JAS", "1PE", "2PE", "1JN", "2JN", "3JN", "JUD", "REV"]

// Avaliable Languages are English, Español (España) & French
LANGUAGE = ["EN", "ES", "FR"]
```
