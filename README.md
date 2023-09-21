# Create your Token
* # $\textcolor{green}{Getting\ Started}$
* ## :dart: $\textcolor{gray}{In\ this\ project\ you\ have\ to\ know:}$ 
<div>
     <img src="https://raw.githubusercontent.com/devicons/devicon/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/typescript/typescript-original.svg" title="typescript" **alt="typescript" width="40" height="40"/> 
</div>

---
 * ##  :memo: $\textcolor{gray}{First,\ run\ the\ development\ server: }$ 
```bash

npm install @solana/web3.js
npm install @metaplex-foundation/js fs
npm install @metaplex-foundation/mpl-token-metadata
npm start
```
 ---
 * ## $\textcolor{green}{Let's\ start}$ 
 * ##  :black_nib: $\textcolor{gray}{Be\ creative,\ Describe\ your\ token\ metadata! }$
  
  ```ruby
const tokenName = "MangırCoin"
const description = "Welcome to rebirth of the everything."
const symbol = "PRC"
const decimals = 2
const amount = 1000

```
* ### $\textcolor{red}{Do\ not\ forget\ to\ add\ your\ image\ in\ SRC!}$ :v:
 ```ruby
// file to buffer
  const buffer = fs.readFileSync("src/images.png")

  // buffer to metaplex file
  const file = toMetaplexFile(buffer, "images.png")

```
---

* ## :tada:  $\textcolor{brown}{ And\ run\ code\,Congratulations\ here\ is\ your\ TOKEN! :}$ 

<p align="center">
    <img src="https://user-images.githubusercontent.com/109158340/206427048-f20ceea1-5ee8-4a80-8211-1cda63c50e25.png">
 
 ---
 
 * ##  $\textcolor{brown}{ And\ your\ token's\ metadata:}$ 

<p align="center">
    <img src="https://user-images.githubusercontent.com/109158340/206429066-9e03b363-4348-4ce7-a7f9-d6f177068c6e.png">




