# Build your first Dapp using moralis


- first you need to create a free moralis server at [moralis](https://moralis.io)

 ![moralis](https://docs.moralis.io/~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-MVStbACGLCycg7J5WQ2%2F-MhT9ur04bEBvZ15Qlrf%2F-MhTBE9FPnuaKJ8O4T4e%2Fimage.png?alt=media&token=ccc65322-55bb-472b-93a7-3a95c471b6b7)
 
 - This will take a while , so while you're doing that , let's start writing our codes 

## include moralis on your web page (HTML specifically for now)

- In order to communicate with the Moralis Server, we need to include the Moralis code in our dApp. Open your favorite text editor. I recommend [Visual Studio Code](https://code.visualstudio.com) with the [Live server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension to make running the web page super easy.

- Create a new file in your visual studio code called ``index.html`` and copy the following code.

```
 <html>
  <head>
  
    <!-- Moralis software development kit code -->
    <script src="https://cdn.jsdelivr.net/npm/web3@latest/dist/web3.min.js"></script>
    <script src="https://unpkg.com/moralis/dist/moralis.js"></script>
  </head>
  <body>
    <span>Moralis Dapp</span>
    
    <button id="btn-login">login to moralis</button>
    <button id="btn-logout">Logout</button>
    <script>
      // connect to Moralis server
      const serverUrl = "https://xxxxx/server";
      const appId = "YOUR_APP_ID";
      Moralis.start({ serverUrl, appId });

    </script>
  </body>
</html>
```

## Get your Moralis Application ID and Moralis Server URL

- When the server instance has been created, get your Moralis server URL and application ID and paste them into the ``<script>`` tag where indicated in the code above

![image address](https://docs.moralis.io/~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-MVStbACGLCycg7J5WQ2%2F-MhT9ur04bEBvZ15Qlrf%2F-MhTCJn-jDryN6LL7rbc%2Fimage.png?alt=media&token=dc0517b3-fb21-43ab-b62d-23f07835a5b3)


![image itelsef](https://docs.moralis.io/~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-MVStbACGLCycg7J5WQ2%2F-MhT9ur04bEBvZ15Qlrf%2F-MhTCdAlRtJ1MHmYCZc5%2Fimage.png?alt=media&token=84ead725-fb89-4989-9d3a-da4680639696)

-So after all has been fixed, feel free to run with with live server , then your first Dapp( decentralized application ), is ready 

# Hurray!!!, 

use and enjoy

If you wanna go on , with more, feel free to visit  [The place to help you up more](https://docs.moralis.io/guides/build-a-simple-dap-in-3-mins-login-part-2)
