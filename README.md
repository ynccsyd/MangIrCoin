# Solana-Token-Metadata
## $\textcolor{green}{Getting\ Started}$

First, run the development server:
```bash

npm install @solana/web3.js
npm install @metaplex-foundation/js fs
npm install @metaplex-foundation/mpl-token-metadata
npm start
```
 ---
 ### $\textcolor{green}{Let's\ start}$
  - First describe your token metada:
  ```ruby
const tokenName = "Paracoin"
const description = "Welcome to the rebirth of everything."
const symbol = "PRC"
const decimals = 2
const amount = 1

```
#### $\textcolor{red}{Do\ not\ forget\ to\ add\ your\ image\ in\ SRC!}$ :v:
 ```ruby
// file to buffer
  const buffer = fs.readFileSync("src/phoenix.jpg")

  // buffer to metaplex file
  const file = toMetaplexFile(buffer, "phoenix.jpg")

  // upload image and get image uri
  const imageUri = await metaplex.storage().upload(file)
  console.log("image uri:", imageUri)

```
### :tada:  $\textcolor{green}{ And\ run\ code\, here\ is\ your\ METADATA :}$ 
 
````json
{
"name":"Paracoin",
"description":"Welcome to the rebirth of everything.",
"image":"https://arweave.net/rdkW0-WL8RVPOxvkDk7VnHv2Z9aofQuB16VmEhT7LnI"
}
````

<p align="center">
    <img src="https://arweave.net/rdkW0-WL8RVPOxvkDk7VnHv2Z9aofQuB16VmEhT7LnI" width="200" height="200">


