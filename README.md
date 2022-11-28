
# Quote application with blockchain

*A project for blockchain beginners.*

This **Quote Application** is built with **Solidity, Python and React Typescript**.
By using this application, one can *upload a quote*, which will be visible to all the users.

The **smart contract**, which is built with **Solidity**, has the capabilities of **adding a new user**, **uploading a quote** and **catching new quotes uploaded at that time**.

The Python script `deploy_app.py` is the main script to deploy a new contract to a network like `Goerli`.
To run this script you will need [brownie](https://eth-brownie.readthedocs.io/en/stable/) python pakage installed.

The **Web UI** is built with **React Typescript**. One should have [NodeJs](https://nodejs.org/en/) and [npm](https://www.npmjs.com/package/npm) installed to run this application.

By using **MetaMask** and some **Goerli chain faucets**, one can **interact** with the smart contract.

- [@useDApp/core](https://www.npmjs.com/package/@usedapp/core) is used here to **call the functions** of the **smart contract** deployed on the live chain.

- [@material-ui/core](https://www.npmjs.com/package/@material-ui/core) is used here to **style** the **Web UI** within the **typescript** file.

- [react-toastify](https://www.npmjs.com/package/react-toastify) npm package is used here to **show notifications** in the **Web UI**.

**Here's the guide to run this application :**
- Setup
    - Add **MetaMask** extension to your **web browser**.
    - **Create** a new wallet or **import** one.
    - Click on **Ethereum mainnet** next to the icon.
    - Click **Show/Hide** Test networks.
    - Turn on that feature.
    - Switch the network to **Govan Test Network**.
    - Now go to this [website](https://goerlifaucet.com/).
    - **Log In** with your *Alchemy* account.
    - After logging in you should **paste your Metamask wallet address** in the text box.
    - Click the **Send Me ETH** button.
    - Install [**NodeJs**](https://nodejs.org/en/) and [**npm**](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm).

- Running application
    - Execute the command `npm install --force`
    - Now execute the command `npm start`
- Application usage
    - Once the app is opened up in the web browser, **Connect** the wallet by clicking connect button.
    - After connecting, Click **SignIn** button. Fill your username in the input feild and press proceed.
    - Click on the **confirm** button in the metamask that has been popped up.
    - After SignIn you can **post** any quote on the website.
    - Get a quote and type it in the input field on the bottom.
    - Then click the **send** button. After a few seconds, the quote will be posted.



## Authors

- [@Tanay-ErrorCode](https://github.com/Tanay-ErrorCode/)


## 🔗 Links
[![Youtube](https://img.shields.io/badge/MY_YOUTUBE-000?style=for-the-badge&logo=youtube&logoColor=red)](https://www.youtube.com/channel/UCN7Lo2yjOFomJLDpAxxcSMw)
[![StackOverfow](https://img.shields.io/badge/Stack_Overflow-fff?style=for-the-badge&logo=stackoverflow&logoColor=orange)](https://stackoverflow.com/users/17675859/tanay)


<!-- ceheco9805@evilant.com -->

<!-- Kutta_Kala_Hai1 -->

<!-- git remote add origin https://github.com/Evil-Deer/my-Repo.git
git branch -M main
git push -u origin main -->
<!-- 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 -->
<!-- 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 -->

<!-- git init -b main
git add .
git commit -m 'first commit'
git remote -v
git remote add origin https://Evil-Deer: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@github.com/Evil-Deer/my-Repo.git
git remote set-url origin https://Evil-Deer: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@github.com/Evil-Deer/my-Repo.git
git push --set-upstream origin main
 -->