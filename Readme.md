# Build your first Dapp using moralis


- first you need to create a free moralis server at [moralis](https://moralis.io)

 ![moralis](https://docs.moralis.io/~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-MVStbACGLCycg7J5WQ2%2F-MhT9ur04bEBvZ15Qlrf%2F-MhTBE9FPnuaKJ8O4T4e%2Fimage.png?alt=media&token=ccc65322-55bb-472b-93a7-3a95c471b6b7)
 
 - This will take a while , so while you're doing that , let's start writing our codes 

## include moralis on your web page (HTML specifically for now)

- In order to communicate with the Moralis Server, we need to include the Moralis code in our dApp. Open your favorite text editor. I recommend [Visual Studio Code](https://code.visualstudio.com) with the [Live server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension to make running the web page super easy.

- Create a new file in your visual studio code called ``index.html`` and copy the following code.

`` <html>
  <head>
    <!-- Moralis software development kit code -->
    <script src="https://cdn.jsdelivr.net/npm/web3@latest/dist/web3.min.js"></script>
    <script src="https://unpkg.com/moralis/dist/moralis.js"></script>
  </head>
  <body>
    <h1>Moralis Dapp</h1>
    <button id="btn-login">login to moralis</button>
    <button id="btn-logout">Logout</button>
    <script>
      // connect to Moralis server
      const serverUrl = "https://xxxxx/server";
      const appId = "YOUR_APP_ID";
      Moralis.start({ serverUrl, appId });

    </script>
  </body>
</html>``



