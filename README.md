### Basic Internet Computer Asset Canister
#### DFX Version 0.22.0

This is a very simple asset canister layout for the Internet Computer that is ready for easy deployment.

#### Instructions:

This will clone the project and locally deploy it as long as you have DFX up correctly.

```
git clone https://github.com/id-daniel-mccoy/basic-assets.git
cd basic-assets
dfx start --clean --background
dfx deploy
```

There is a text file in the asset canister called `test.txt`. To test your asset canister, after dfx deploys it locally, open the link it provides and add `/test.txt` to see your file in the browser.