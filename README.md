# Give your token an identity
## $\textcolor{green}{Getting\ Started}$

 ### :dart: $\textcolor{gray}{In\ this\ project\ you\ have\ to\ know:}$ 
<div>
     <img src="https://raw.githubusercontent.com/devicons/devicon/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/typescript/typescript-original.svg" title="typescript" **alt="typescript" width="40" height="40"/> 
</div>

---

### :memo: $\textcolor{gray}{ First,\ run\ the\ development\ server:}$ 
 
```bash
npm install @metaplex-foundation/js fs
npm install @metaplex-foundation/mpl-token-metadata
npm start
```
---

### :speech_balloon:  $\textcolor{gray}{ Be\ creative!!!\ Write\ your\ token\ details:}$ 

````ruby
const tokenName = "MangırCoin"
const description = "Welcome to rebirth of the everything."
const symbol = "PRC"
const decimals = 2
const amount = 1000
````
---
### :grey_exclamation:  $\textcolor{gray}{ Do\ not\ forget\ to\ add\ your\ token\ image}$ 

````ruby
  // file to buffer
  const buffer = fs.readFileSync("src/images.png")

  // buffer to metaplex file
  const file = toMetaplexFile(buffer, "images.png")
  ````
 ## :trophy: $\textcolor{brown}{Congratulations\, now\ you\ have\ your\ token!}$
<p align="center">
  <img src="https://user-images.githubusercontent.com/109158340/206389892-fe3020bf-574b-4b5a-bf6a-c2fa2a5ce8b3.png" >
 
 ###   $\textcolor{gray}{ Here's\ your\ token's\ metadata}$ 
 
 <p align="center">
  <img src="https://user-images.githubusercontent.com/109158340/206390331-6046ac77-171d-49c7-82a8-b8c308101190.png" >
 

