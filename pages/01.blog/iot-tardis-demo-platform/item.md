---
title: 'IoT Tardis Demo Platform'
date: '12:34 05-08-2018'
taxonomy:
    category: blog
    tag:
        - link 
        - demo 
        - IoT 
        - node-red
hide_git_sync_repo_link: false
external_links:
    target: _blank
blog_url: /blog
show_sidebar: false
show_breadcrumbs: true
show_pagination: true
post_icon: tv
hide_from_post_list: false
link: 'http://demo.techdogs.us'
hero_classes: text-light title-h1h2 hero-large parallax overlay-dark-gradient
hero_image: '2018-08-05_12-40-10-IoT-Tardis.png'
highlight:
    theme: darkula
    lines: true 
---

link: http://demo.techdogs.us

===

A fully functional demonstation of the IoT Tardis project.  The project is hosted on a Raspberry Pi.

```yaml

hero_classes: text-light title-h1h2 overlay-dark-gradient hero-large parallax

```

```html
<!DOCTYPE html>
<!--[if lt IE 7 ]><html class="ie ie6" lang="en"> <![endif]-->
<!--[if IE 7 ]><html class="ie ie7" lang="en"> <![endif]-->
<!--[if IE 8 ]><html class="ie ie8" lang="en"> <![endif]-->
<!--[if (gte IE 9)|!(IE)]><!--><html lang="en"> <!--<![endif]-->

<head>
        <meta charset="utf-8">
        <title>techDogs IoT project</title>
        <link rel="icon" href="http://raspi3b/favicon.ico?v=2" />
        <meta name="description" content="web portal for RaspberryPi services">
        <meta name="keywords" content="raspberry pi node-red webmin nodemcu>
        <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes"/>

        <!-- // CSS Reset – http://meyerweb.com/eric/tools/css/reset/ -->
        <link rel="stylesheet" type="text/css" href="/resources/reset.css" media="all">
        <link href='https://fonts.googleapis.com/css?family=Fjalla+One|Anaheim' rel='stylesheet' type='text/css'>
        <!-- // Option one: Live updating CSS -->
        <!-- // This embed code adds your fonts and live Typecast CSS to the page -->
        <script type="text/javascript" src="/resources/js/my_css.js"></script>
        <script src="/resources/js/jquery-3.1.1.min.js"></script>
</head>

<!--  Ricks Comments
added background color
added text color for h1
edited each line item to change font color
<script src="https://code.jquery.com/jquery-3.1.1.min.js"></script>
<body style="background-color:#82624b;">
<body style="background-color:#775F55;">
<p><img src="/resources/logo/techdogs1.png" width="60%"></p>
<body style="background-color:#82624b;">
<body style="background-color:#EBE1CC;">
-->

<body style="background-color:#82624b;">
<article>

<p><img src="/resources/logo/techDogs_logo_white_bar.png" width="50%"></p>
<h1 style="color:#7faedb;font-size:50px; text-transform: none;">IoT TARDIS Project</h1><br/>
<h1 style="color:#7faedb;font-size:40px; text-transform: none;">DEMONSTRATION</h1><br/>
<h1 style="color:#7faedb;font-size:30px; text-transform: none;">status:
                <a style="color:Red">Alpha[</a>
                <a style="color:White">h</a>
                <a style="color:Red">]</a>
</h1><br/>
<h1 style="color:#7faedb;font-size:25px; text-transform: none;">[host: <script language="JavaScript"> document.write(window.location.hostname +'</a>' );</script>]</h1>
<p style="font-size:25px;" class="author">creator: Richard Hoppel</p>
<h1 style="font-size:50px;"> <script language="JavaScript">
        document.write('<a style="color:#7faedb;" target="_blank" href="' + window.location.protocol + '//' + window.location.hostname + ':1880' +  '/ui" >enter</a>' );
</script></h1>

<p style="font-size:20px;" class="intro">the remote control center for the universe<br/>[Raspberry Pi, NodeMCU and Node-Red]</p>

<p>
        <a style="color:#7faedb;" target="_blank" href="/resources/png/MainControl__a.png">TARDIS Node-RED flow graphic</a><br/>
        <a style="color:#7faedb;" target="_blank" href="/resources/png/IoT_TARDIS_Demo5_schem.png">K9-Node Sa><br/>c</
        <a style="color:#7faedb;" target="_blank" href="/resources/png/IoT_TARDIS_Demo5_bb.png">K9-Node Breadboard</a><br/>
        <a style="color:#7faedb;" target="_blank" href="https://1drv.ms/p/s!AmlRt1Ah7vyImIkNnG3AiufU6QrO1Q">Online Presentation [ppt]</a><br/>

<script language="JavaScript"]>
        document.write('<a style="color:white;" target="_blank" href="' + window.location.protocol + '//' + window.location.hostname + ':1880' +  '" >Node Red [Control Panel]</a><br/>' );
</script>
        <a style="color:Black;" >default user is READ-only</a><br/>
<script language="JavaScript"]>
        document.write('<a style="color:white;" target="_blank" href="' + window.location.protocol + '//' + window.location.hostname + ':1880' +  '/ui" >Node Red [UI Desktop]</a><br/>' );
</script>
        <a style="color:Black;" >demo for UI [user:password] = </a><br/>
        <a style="color:Black;" >node-red-user : node-red-user-default</a><br/>
<script language="JavaScript"]>
        document.write('<a style="color:white;" target="_blank" href="' + window.location.protocol + '//' + window.location.hostname + ':56000' +  '/mjpeg" >WebCam [host]</a><br/>' );
        document.write('<a style="color:white;" target="_blank" href="' + window.location.protocol + '//' + window.location.hostname + ':10000' +  '" >Webmin Adminstrator</a><br/>' );
        document.write('<a style="color:white;" target="_blank" href="' + window.location.protocol + '//' + window.location.hostname + ':8888' +  '" >RPI Monitor</a><br/>' );
</script>

        <a style="color:white;   "target="_blank"href="/phpliteadmin">SQLite Administrator</a><br/>
        <a style="color:white;   "target="_blank"href="/phpsysinfo">System Information</a><br/>
        <a style="color:#7faedb; "target="_blank"href="http://hs2:8080/secure/RapidBoard.jspa?rapidView=10&selectedIssue=ESP-6">IoT TARDIS Project [JIRA PM]</a><br/>
        <a style="color:#7faedb; "target="_blank" href="https://www.evernote.com/pub/rhoppel/iottardis">IoT TARDIS Project  [PUBLIC Evernote Notebook]</a><br/>
        <a style="color:#7faedb; "target="_blank" href="https://goo.gl/TqXi6L">IoT TARDIS Project [Evernote Notebook]</a><br/>
        <a style="color:#7faedb;" target="_blank"
                href="https://onedrive.live.com/view.aspx?resid=88FCEE2150B75169%21394362&id=documents onenote:https://d.docs.live.net/88fcee2150b75169/Archive/Documents/IOT%20TARDIS%20Project/">
                IoT TARDIS Project [MS OneNote notebook]</a><br/>
        <a style="color:white;   "target="_blank"href="https://drive.google.com/file/d/18bh70gd2mTj7RL1JWIwgLLujGYuZLBxW/view?usp=sharing">K9-node Code Component Diagram</a><br/>
</p>
<p style="font-size:20px;"class="intro">Style</p>
<p>
        <a style="color:white">[background:#82624b]</a>
        <a style="color:#7faedb">[border:#7faedb]</a>
        <a style="color:#ed7d31">[accent:#ed7d31]</a><br/>
        <a style="color:white">[text colors:
                <a style="color:#7faedb">#7faedb</a>,
                <a style="color:#ed7d31i">#ed7d31</a>,
                <a style="color:white">white</a>,
        slack   <a style="color:LightBlue">LightBlue]</a>
        </a><br/>
        <a style="color:white;   "target="_blank"href="https://fonts.google.com/specimen/Fjalla+One?selection.family=Fjalla+One">Font: Fjalla One</a><br/>
        <a style="color:white;   "target="_blank"href="https://fonts.google.com/specimen/Anaheim?selection.family=Anaheim">Font: Anaheim</a><br/>
</p>
<p style="font-size:20px;"class="intro">Documents</p>
<p>
        <a style="color:#7faedb; "target="_blank"href="https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet">Markdown Cheatsheet</a><br/>
        <a style="color:#7faedb; "target="_blank"href="http://www.simplehtmlguide.com/cheatsheet.php">HTML Cheatsheet</a><br/>
        <a style="color:white;   "target="_blank"href="https://nodered.org/docs/">Node-Red Docs</a><br/>
        <a style="color:white;   "target="_blank"href="https://nodered.org/blog/">Node-Red Blog</a><br/>
        <a style="color:white;   "target="_blank"href="https://github.com/node-red/node-red/releases">Node-Red Releases</a><br/>
        <a style="color:white;   "target="_blank"href="https://docs.jsonata.org">JSONata</a><br/>
        <a style="color:white;   "target="_blank"href="https://www.raspberrypi.org/documentation/">Raspberry Pi Docs</

        <a style="color:white;   "target="_blank"href="https://github.com/billw2/rpi-clone">RPi-clone</a><br/>
        <a style="color:white;   "target="_blank"href="https://www.raspberrypi.org/documentation/hardware/raspberrypi/README.md">Raspberry Pi Hardware</a><br/>
        <a style="color:white;   "target="_blank"href="https://nodemcu.readthedocs.io/en/master/">NodeMCU Docs</a><br/

        <a style="color:white;   "target="_blank"href="https://www.lua.org/manual/5.1/"> Lua 5.1 Reference</a><br/>

        <a style="color:white;   "target="_blank"href="https://github.com/LuaDist/luasrcdiet"> Lua LuaSrcDiet</a><br/>

        <a style="color:white;   "target="_blank"href="https://iotbytes.wordpress.com/managing-files-with-nodemcu/"> Lua File Operations on ESP826</a><br/>
        <a style="color:white;   "target="_blank"href="https://www.espressif.com/sites/default/files/documentation/2c-esp8266_non_os_sdk_api_reference_en.pdf"> ESP8266 Non-OS SDK API Reference</a><br/>
        <a style="color:white;   "target="_blank"href="https://tttapa.github.io/ESP8266/Chap04%20-%20Microcontroller.h

        <a style="color:white;   "target="_blank"href="https://github.com/pellepl/spiffs">SPIFFS FLASH file system</a>

        <a style="color:white;   "target="_blank"href="https://wiki.wemos.cc/start">WeMos Devices</a><br/>
        <a style="color:white;   "target="_blank"href="https://www.aliexpress.com/store/1331105">WeMos Store</a><br/>

        <a style="color:white;   "target="_blank"href="https://nurdspace.nl/ESP8266">ESP8266</a><br/>
        <a style="color:white;   "target="_blank"href="https://en.wikipedia.org/wiki/Web_colors">Web Colors</a><br/>

        <a style="color:white;   "target="_blank"href="https://en.wikipedia.org/wiki/LED_circuit">LED Circuit</a><br/>

        <a style="color:white;   "target="_blank"href="https://ESP8266.com">ESP8266.com Resource</a><br/>
</p>
<p style="font-size:20px;"class="intro">Tools</p>
<p>
        <a style="color:white;   "target="_blank"href="https://bramp.github.io/js-sequence-diagrams/">js sequence diagrams</a><br/>
        <a style="color:white;   "target="_blank"href="https://marxi.co/">marxi.co markup editor for Evernote</a><br/>

        <a style="color:white;   "target="_blank"href="https://www.draw.io/">draw.io diagramming</a><br/>
        <a style="color:white;   "target="_blank"href="https://iotbytes.wordpress.com/sqlite-db-on-raspberry-pi/">SQLite DB on Raspberry Pi</a><br/>
        <a style="color:white;   "target="_blank"href="https://etcher.io/">Etcher: Burn SD card images>i</a><br/>

        <a style="color:white;   "target="_blank"href="https://blogs.msdn.microsoft.com/wsl/2017/04/14/serial-support-on-the-windows-subsystem-for-linux/">Serial port support using Windows Subsystems for Linux</a><br/>
        <a style="color:white;   "target="_blank"href="https://github.com/nodemcu/nodemcu-firmware/blob/master/docs/en/spiffs.md">spiffmsg - Manipulate SPI FLASH file systems images</a><br/>
        <a style="color:white;   "target="_blank"href="https://developers.google.com/web/tools/chrome-devtools/">Chrome Development Tools</a><br/>
</p>
<p style="font-size:20px;"class="intro">Social</p>
<p>
        <a style="color:white;   "target="_blank"href="https://discourse.nodered.org/">Node-Red Discourse Discussion Group</a><br/>
        <a style="color:white;   "target="_blank"href="https://groups.google.com/forum/#!forum/node-red">Node-Red Google Group</a><br/>
        <a style="color:white;   "target="_blank"href="http://node-red.blogspot.com">Learning Node-Red</a><br/>
        <a style="color:white;   "target="_blank"href="http://nodered.org/slack">Slack for Node-Red</a><br/>
</p>
<p style="font-size:20px;"class="intro">Security</p>
<p>
        <a style="color:white;   "target="_blank"href="https://letsencrypt.org/">Let's Encrypt</a><br/>
        <a style="color:white;   "target="_blank"href="https://certbot.eff.org/">CertBot</a><br/>
        <a style="color:white;   "target="_blank"href="http://www.haproxy.org/">HAproxy</a><br/>
        <a style="color:white;   "target="_blank"href="https://www.ssllabs.com/ssltest/analyze.html?d=techdogs.us">Test SSL</a><br/>
        <a style="color:white;   "target="_blank"href="https://domains.google.com">Google Domains</a><br/>
</p>
<p style="font-size:20px;"class="intro">Ideas</p>
<p>
        <a style="color:white;    "target="_blank"href="http://techdogs.us">techDogs</a><br/>
        <a style="color:LightBlue;"target="_blank"href="http://www.pighixxx.net/">PighiXXX</a><br/>
        <a style="color:LightBlue;"target="_blank"href="https://www.flickr.com/photos/28521811@N04/with/15199114563/">PighiXXX photostream</a><br/>
        <a style="color:LightBlue;"target="_blank"href="https://tech.scargill.net/">Scargill's Tech Blog</a><br/>

        <a style="color:LightBlue;"target="_blank"href="https://bitbucket.org/snippets/scargill/">Scargill Snippets</a

        <a style="color:LightBlue;"target="_blank"href="https://cssreset.com/scripts/eric-meyer-reset-css/">reset CSS<

        <a style="color:LightBlue;"target="_blank"href="https://www.webpagefx.com/blog/web-design/the-history-of-css-resets/">more on CSS reset</a><br/>
        <a style="color:LightBlue;"target="_blank"href="https://tech.scargill.net/home-:control-2016/">Home Control 20

        <a style="color:LightBlue;"target="_blank"href="https://tech.scargill.net/nextion-wifi-touch-display/">Nextion WiFi display</a><br/>
        <a style="color:white;    "target="_blank"href="https://en.wikipedia.org/wiki/TARDIS"><br/><img src="/resources/png/tardis4a.png" width="10%"></a>
        <a style="color:LightBlue;"target="_blank"href=""></a><br/>
        <a style="color:white;    "target="_blank"href=""></a><br/>
</p>

</article>
</body>
</html>
```
