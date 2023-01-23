<html>
  <head>
    <title>OptiFine</title>
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    <link rel="shortcut icon" href='images/of16r.png' />
    <meta name="description" content="OptiFine - Minecraft performance tuning and advanced graphics" />
    <meta name="keywords" content="optifine, minecraft, fps, lag, antialiasing, hd textures" />
<style type="text/css">
      @font-face {
        font-family: 'Roboto';
        font-weight: normal;
        font-style: normal;
        src: local('Roboto'), local('Roboto-Regular'), url('template/fonts/Roboto-Regular.woff') format('woff');
      }
      @font-face {
        font-family: 'Roboto';
        font-weight: bold;
        font-style: normal;
        src: url('template/fonts/Roboto-Bold.woff') format('woff');
        src: local('Roboto Bold'), local('Roboto-Bold'), url('template/fonts/Roboto-Bold.woff') format('woff');        
      }
      @font-face {
        font-family: 'Oswald';
        font-weight: normal;
        font-style: normal;
        src: url('template/fonts/Oswald-Regular.woff') format('woff');
      }
      @font-face {
        font-family: 'Oswald';
        font-weight: bold;
        font-style: normal;
        src: url('template/fonts/Oswald-Medium.woff') format('woff');
      }
      body {
        font-family:'Roboto', arial, helvetica, sans-serif;
        font-weight: normal;
        font-style: normal;
        font-size: medium;
        background-image:url('images/snow64b.gif');
      }
      A {
        color: #5168CF; 
        text-decoration: none; 
      }    
      h2 {
        margin-bottom: 0.3em
      }
      .tableRoot {
        margin: 0 auto; 
        min-width: 850px; 
        background-color: white; 
        box-shadow: 0px 0px 20px #CCCCCC;
        border: 0px solid #808080;
        /* Use border-spacing instead of border-collapse, otherwise IE doesn't show the shadow */
        border-spacing:0;
      }
      .header {
        background-color: #313E7C;
        padding-bottom: 0.32em;
      }
      .headerTitle {
        font-family:'Oswald', arial, helvetica, sans-serif;
        font-size:300%; 
        font-weight:bold; 
        padding-left: 20px;
        padding-right: 40px;
        line-height: 1.3em;
      }
      .headerTitle A {
        color: #F0F3FF; 
        text-decoration: none;
      }
      .headerNav {
        text-align: left; 
        background-color: #313E7C;
        border-width: 0px;
        margin-left: 0px
      }
      .headerNav A {
        color: #F0F3FF; 
        text-decoration: none;
        padding-left: 1em;
        padding-right: 1em;
        padding-top: 0.3em;
        padding-bottom: 0.3em;
      }
      .headerNav A:hover {
        background-color: #6974A3;
        transition: .25s;
        text-decoration: none;
      }
      .content {
        padding: 18px;
        padding-top: 10px; 
        text-align: left; 
        text-indent: 0px; 
        margin: 10px;
      }
      .content A:hover {
      }
      .footer {
        font-size:small; 
        text-align: right;  
        background-color: #313E7C; 
        padding-left: 0.3em;
        padding-right: 0.3em;
        padding-top: 0.5em;
        padding-bottom: 0.5em;
      }
      .footerIcon {
      }
      .footerIcon IMG {
        margin-bottom: -0.3em;
        margin-right: 0.7em;
        width: 1.2em;
        height: 1.2em;
      }
      .footerText A {
        text-decoration: none;
        padding-left: 0.7em; 
        padding-right: 0.7em;
        padding-top: 0.2em;
        padding-bottom: 0.2em;
        color: #F0F3FF;
      }
      .footerText A:hover {
        text-decoration: none;
        background-color: #6974A3;
        transition: .25s;
        color: #F0F3FF;
      }
      .downloads {
        width: 100%
      }
      .spoilerLink {
        line-height: 200%;
      }
      .showAll {
        text-align: center;
        margin-top: 2em;
      }
      .downloadTable {
        border-collapse: collapse;
        width: auto;
        line-height: 200%;
      }
      .downloadLine {
      }
      /* Columns */
      .downloadLine .colFile {
        width: 270px;
        padding-left: 10px;
      }
      .downloadLine .colDownload A,
      .downloadButton A {
        width: 80px;
        text-align: center;
        padding-left: 1em;
        padding-right: 1em;
        padding-top: 0.2em;
        padding-bottom: 0.2em;
        border: 1px solid #5168CF;
      }
      .downloadLine .colMirror {
        width: 100px; 
        text-align: center;
      }
      .downloadLine .colChangelog {
        width: 110px;
      }
      .downloadLine .colForge {
        width: 115px;
      }
      .downloadLine .colDate {
        width: 80px;
        text-align: right;
        padding-right: 10px;
      }
      /* Preview */
      .downloadLinePreview {
        background-color: #FFF6E3
      }
      /* Main */
      .downloadLineMain:first-child {
        background-color: #F0F3FF
      }
      .downloadLineMain:first-child .colDownload  A, 
      .downloadButton A{
        font-weight: normal;
        color: white;
        background-color: #313E7C;
        border: 1px solid #313E7C;
      }
      .downloadLineMain:first-child .colDownload A:hover,
      .downloadButton A:hover{
        background-color: #6974A3;
        transition: .25s;
      }
      LI STRONG {
        line-height: 200%;
      }
      .tableDownload {
        margin: 0 auto; 
      }
      .tableDonate TR {
        height: 35px;
      }
      .scaleNearest {  
        image-rendering:optimizeSpeed;             /* Legal fallback                 */
        image-rendering:-moz-crisp-edges;          /* Firefox                        */
        image-rendering:-o-crisp-edges;            /* Opera                          */
        image-rendering:-webkit-optimize-contrast; /* Chrome (and eventually Safari) */
        image-rendering:optimize-contrast;         /* CSS3 Proposed                  */
        -ms-interpolation-mode:nearest-neighbor;   /* IE8+                           */
        image-rendering:pixelated;                 /* Chrome 41+, Firefox            */
      }
      .tableData {
        border-collapse: collapse;
      }
      .tableData th {
        color: #F0F3FF;
        background-color: #313E7C;
        font-weight: normal;
      }
      .tableData, .tableData th, .tableData td {
        border: 0px solid black;
      }
      .tableData th, .tableData td {
        padding-left:10px;
        padding-right:10px;
        padding-top:5px;
        padding-bottom:5px;
      }
      .tableDataDis {
        background-color: #DCDCDC
      }
      .tableDataIcon {
        width: 1.5em;
        height: 1.5em;
      }
      .tableDataCape {
        max-height: 44px;
      }
      .tableDataCentered {
        text-align: center;
      }
      .tableBanner {
        width: 100%;
        padding: 8px;
      }
      .tableBanner TR {
        text-align: center;
        margin: 0.3em;
      }
      .tableBanner TD {
        padding-top: 1em;
      }
      .tableBanner IMG {
        border: 1px solid #f0f0f0;
      }
      .tableBanner TD * {
        margin: 0.3em;
      }
      .tableBanners TR TD {
        padding: 9px;
        padding-right: 8px;
      }
      .tableBanners IMG {
        border: 1px solid #f0f0f0;
      }
      .bannerSelTable {
        width: 100%;
      }
      .bannerSelUser {
        text-align: right;
      }
      .bannerNav {
        text-align: center;
      }
      .bannerNav * {
        margin: 0.3em;
      }
      TD .tableDataEditable {
        background-color: #FFF6E3;
        border: 2px solid transparent;
      }
      input,
      select {
        font-family:'Roboto', arial, helvetica, sans-serif;
        font-weight: normal;
        font-style: normal;
        font-size: medium;
        padding: 2px;
      }
      input[type=submit] {
        padding-left: 1em;
        padding-right: 1em;
        padding-top: 0.2em;
        padding-bottom: 0.2em;
      }
      input[type=checkbox] {
        transform : scale(1.3);
      }
    </style>
</head>
  <body>
    <table class="tableRoot">
      <tr>
        <td class="header">
          <!-- Title -->
          <span class="headerTitle">
            <a href="home">OptiFine</a>
          </span>
          <!-- Navigation -->
          <span class="headerNav">
            <a href="home">Home</a>
            <a href="downloads">Downloads</a>
            <a href="donate">Donate</a>
            <a href="cape">Cape</a>
            <a href="banners">Banners</a>
            <a href="login">Login</a>
            <a href="faq">FAQ</a>
          </span>
        </td>
      </tr>
      <tr>
        <td class="content">
          <!-- Content -->
<p>OptiFine is a Minecraft optimization mod.</p>
    <p>It allows Minecraft to run faster and look better with full support for HD textures and many configuration options.</p> 
    <p>The official OptiFine description is on the <a href="http://www.minecraftforum.net/topic/249637-">Minecraft Forums</a>.</p>
    <p>Resources: <a href="https://github.com/sp614x/optifine/tree/master/OptiFineDoc/assets/minecraft/optifine/lang" target="_blank">translation</a>, 
      <a href="https://github.com/sp614x/optifine/tree/master/OptiFineDoc/doc" target="_blank">documentation</a>, 
      <a href="https://github.com/sp614x/optifine/issues" target="_blank">issue tracker</a>.</p>
    <p>
      Social media: 
      <a href="https://discord.gg/3mMpcwW" target="_blank">Discord</a>, 
      <a href="https://twitter.com/OptiFineNews" target="_blank">Twitter</a>,
      <a href="https://reddit.com/r/optifine" target="_blank">Reddit</a>.
    </p>
    <h3>Features</h3>
    <ul class='bbc'>
      <li>
        <strong class='bbc'>FPS boost</strong> (<a href='http://imgur.com/a/4NhyN#0' class='bbc_url' title='' rel='nofollow'>examples</a>)<br>
        - doubling the FPS is common<br>
        - decreases lag spikes and smooths gameplay<br>
      </li>
      <li>
        <strong class='bbc'>Support for HD Textures</strong> (<a href='http://www.minecraftforum.net/topic/249637-/#HDTextures&amp;#91' class='bbc_url' title=''>info</a>)<br>
        - HD textures and HD fonts (MCPatcher not needed)<br>
        - custom terrain and item textures<br>
        - animated terrain and item textures<br>
        - custom HD Font character widths<br>
        - custom colors<br>
        - custom block color palettes<br>
        - custom lighting<br>
        - unlimited texture size<br>
      </li>
      <li>
        <strong class='bbc'>Support for Shaders</strong> (<a href='http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1286604-shaders-mod-updated-by-karyonix' class='bbc_url' title=''>info</a>)<br>
        - based on the Shaders Mod by Karyonix<br>
      </li>
      <li>
        <strong class='bbc'>Dynamic Lights</strong><br>
        - allows handheld and dropped light emitting items to illuminate the objects around them<br>
        - similar, but not related to the Dynamic Lights <a href='http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1272478-dynamic-lights' class='bbc_url' title='' rel='nofollow'>mod</a><br>
      </li>
      <li>
        <strong class='bbc'>Variable Render Distance</strong> (<a href='http://i.imgur.com/qT3P3.png' class='bbc_url' title='' rel='nofollow'>example</a>)<br>
        - from Tiny to Extreme (2 x Far) in 16m steps<br>
        - <a href='http://i.imgur.com/WZCmN.png' class='bbc_url' title='' rel='nofollow'>sun</a>, <a href='http://i.imgur.com/z9hBK.png' class='bbc_url' title='' rel='nofollow'>moon and stars</a> are visible in Tiny and Short distance<br>
      </li>
      <li>
        <strong class='bbc'>Configurable Smooth Lighting</strong> (<a href='http://imgur.com/a/q89Qb#0' class='bbc_url' title='' rel='nofollow'>examples</a>)<br>
        - from 1% - smooth lighting without shadows<br>
        - to 100% - smooth lighting with full shadows<br>
      </li>
      <li>
        <strong class='bbc'>Performance: VSync</strong><br>
        Synchronizes framerate with monitor refresh rate to remove split frames and smooth gameplay<br>
      </li>
      <li>
        <strong class='bbc'>Smart Advanced OpenGL</strong><br>
        - more efficient, less artifacts<br>
        - Fast - faster, some artifacts still visible<br>
        - Fancy - slower, avoids visual artifacts<br>
      </li>
      <li>
        <strong class='bbc'>Fog control</strong><br>
        - Fog: Fancy, Fast, OFF<br>
        - Fog start: Near, Far<br>
      </li>
      <li>
        <strong class='bbc'>Mipmaps</strong> (<a href='http://imgur.com/a/7YNwh#0' class='bbc_url' title='' rel='nofollow'>examples</a>)<br>
        - Visual effect which makes distant objects look better by smoothing the texture details<br>
        - Mipmap level - OFF, 1, 2, 3, Max<br>
        - Mipmap type - Nearest, Linear<br>
      </li>
      <li>
        <strong class='bbc'>Anisotropic Filtering</strong> (<a href='http://imgur.com/a/rtZBx#0' class='bbc_url' title='' rel='nofollow'>examples</a>)<br>
        - Restores details in mipmapped textures<br>
        - AF level - OFF, 2, 4, 8, 16 (depends on hardware support)<br>
      </li>
      <li>
        <strong class='bbc'>Antialiasing</strong> (<a href='http://imgur.com/a/rtZBx#0' class='bbc_url' title='' rel='nofollow'>examples</a>)<br>
        - Smooths jagged lines and sharp color transitions<br>
        - AA level - OFF, 2, 4, 6, 8, 12, 16 (depends on hardware support)<br>
      </li>
      <li>
        <strong class='bbc'>Better Grass</strong><br>
        Fixes grass blocks side texture to match surrounding grass terrain<br>
      </li>
      <li>
        <strong class='bbc'>Better Snow</strong> (<a href='http://imgur.com/a/h2yAE#0' class='bbc_url' title='' rel='nofollow'>examples</a>, <a href='http://www.reddit.com/r/Minecraft/comments/nbtzv/shall_i_continue_with_this_simple_change/' class='bbc_url' title='' rel='nofollow'>credit</a>)<br>
        Fixes transparent blocks textures to match surrounding snow terrain<br>
      </li>
      <li>
        <strong class='bbc'>Clear Water</strong> (<a href='http://imgur.com/a/en4Yf#0' class='bbc_url' title='' rel='nofollow'>examples</a>)<br>
        Clear, transparent water with good visibility underwater<br>
      </li>
      <li>
        <strong class='bbc'>Random Mobs</strong><br>
        Use random mob textures if available in the texture pack<br>
      </li>
      <li>
        <strong class='bbc'>Connected Textures</strong> (<a href='http://imgur.com/a/YQz3b#0' class='bbc_url' title='' rel='nofollow'>examples</a>)<br>
        Connects textures for glass, glass panes, sandstone and bookshelf blocks which are next to each other.<br>
      </li>
      <li>
        <strong class='bbc'>Natural Textures</strong> (<a href='http://imgur.com/a/A6ujp#0' class='bbc_url' title='' rel='nofollow'>examples</a>, <a href='http://www.minecraftforum.net/topic/468764-' class='bbc_url' title=''>idea</a>)<br>
        Removes the gridlike pattern created by repeating blocks of the same type.<br>
        Uses rotated and flipped variants of the base block texture.<br>
      </li>
      <li>
        <strong class='bbc'>FPS control</strong><br>
        - Smooth FPS - stabilizes FPS by flushing the graphics driver buffers (<a href='http://imgur.com/a/QsOdl#0' class='bbc_url' title='' rel='nofollow'>examples</a>)<br>
        - Smooth Input - fixes stuck keys, slow input and sound lag by setting correct thread priorities<br>
      </li>
      <li>
        <strong class='bbc'>Chunk Loading Control</strong><br>
        - Load Far - loads the world chunks at distance Far, allows fast render distance switching<br>
        - Preloaded Chunks - defines an area in which no new chunks will be loaded<br>
        - Chunk Updates per Frame - allows for faster world loading<br>
        - Dynamic Updates - loads more chunks per frame when the player is standing still<br>
      </li>
      <li>
        <strong class='bbc'>Configurable Details</strong><br>
        - Clouds - Default, Fast, Fancy<br>
        - Cloud Height - from 0% to 100%<br>
        - Trees - Default, Fast, Fancy<br>
        - Grass - Default, Fast, Fancy<br>
        - Water - Default, Fast, Fancy<br>
        - Rain and Snow - Default, Fast, Fancy<br>
        - Sky - ON, OFF<br>
        - Stars - ON, OFF<br>
        - Sun &amp; Moon - ON, OFF<br>
        - Depth Fog - ON, OFF<br>
        - Weather - ON, OFF<br>
        - Swamp Colors - ON, OFF<br>
        - Smooth Biomes - ON, OFF<br>
        - Custom Fonts - ON, OFF<br>
        - Custom Colors - ON, OFF<br>
        - Show Capes - ON, OFF (supports HD capes)<br>
      </li>
      <li>
        <strong class='bbc'>Configurable animations</strong><br>
        - Water Animated - OFF, Dynamic, ON<br>
        - Lava Animated - OFF, Dynamic, ON<br>
        - Fire Animated - OFF, ON<br>
        - Portal Animated - OFF, ON<br>
        - Redstone Animated - OFF, ON<br>
        - Explosion Animated - OFF, ON<br>
        - Flame Animated - OFF, ON<br>
        - Smoke Animated - OFF, ON<br>
        - Void Particles - OFF, ON<br>
        - Water Particles - OFF, ON<br>
        - Rain Splash - OFF, ON<br>
        - Portal Particles - OFF, ON<br>
        - Dripping Water/Lava - OFF, ON<br>
        - Terrain Animated - OFF, ON<br>
        - Items Animated - OFF, ON<br>
      </li>
      <li>
        <strong class='bbc'>Fast Texturepack Switching</strong><br>
        Switch the current Texturepack without leaving the world<br>
      </li>
      <li>
        <strong class='bbc'>Fullscreen Resolution</strong><br>
        Configurable fullscreen resolution<br>
      </li>
      <li>
        <strong class='bbc'>Debug</strong><br>
        - Fast Debug Info - removes lagometer from debug screen<br>
        - Debug Profiler - removes profiler from debug screen<br>
      </li>
      <li>
        <strong class='bbc'>Time Control</strong><br>
        Default, Day Only or Night Only - works in only in Creative mode<br>
      </li>
      <li>
        <strong class='bbc'>Autosave</strong><br>
        - Configurable Autosave interval<br>
        - A fix for the famous Lag Spike of Death
      </li>
    </ul>
    
    <!-- End of content -->
        </td>
      </tr>
      <tr>
        <td class="footer">
          <!-- Footer -->
          <span class="footerIcon">
            <a href="https://discord.gg/3mMpcwW" target="_blank"><img alt="Discord" src="images/discord.png"></a>
            <a href="https://twitter.com/OptiFineNews" target="_blank"><img alt="Twitter" src="images/twitter.png"></a>
            <a href="https://reddit.com/r/optifine" target="_blank"><img alt="Reddit" src="images/reddit.png"></a>
          </span>
          <span class="footerText">
            <a href="privacy">Privacy</a>
            <a href="refund">Refund</a>
            <a href="copyright">Copyright</a>
            <a href="contact">Contact</a>
          </span>
        </td>
      </tr>
      </table>
</body>
</html>
