<!DOCTYPE html>
<head>
    <title>TinkerRat</title>
    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon" /> <!--small image in top corner (16x16) change "favicon.ico for different image file"-->
</head>
<style>
    header{
        color: #00ff00;
        background-color: #838383;
        font-family:'Andalé Mono', monospace;
        font-size: 300%;
        text-align: center;
        margin: 0px;
        padding: 0px;
        line-height: 10px;
        padding-top: 25px;
        padding-bottom: 35px;  
    }

    nav{
        color: #00ff00;
        background-color: #838383;
        font-family:'Andalé Mono', monospace;
        font-size: x-large;
        text-align: center;
        margin: 0px;
        padding: 0px;
        line-height: 10px;
        padding-top: 25px;
        padding-bottom: 35px;
    }

    body    {
    color: #00ff00;
    background-color: #838383;
    font-family:'Andalé Mono', monospace;
    text-align: center;
    margin: 0px;
    }
    footer {
        color: #00ff00;
        background-color: #838383;
        font-family:'Andalé Mono', monospace;
        font-size: large;
        text-align: left;
        margin: 0px;
        padding: 0px;
        line-height: 10px;
        padding-top: 25px;
        padding-bottom: 35px;
        
    }
    a:link, a:visited {
        background-color: #838383;
        color: #00ff00;
        padding-left: 10px;
        padding-right:50px;
        padding-bottom: 10px;
        padding-top: 10px;
        text-align: left;
        text-decoration: none;
        display: inline-block;
    }
    a:hover, a:active {
        color: #838383;
        background-color: #00ff00
    }

    a {
        font-size: 20px;
    }


    .row::after {                   /**/
        content: "";                /**/
        clear: both;                /**/
        display: table;             /**/
    }                               /**/
    .column {                       /**/
        float: left;                /**/
        width: 33.3%;               /* Three columns (use 25% for four, and 50% for two, etc)*/
        padding: 5px;               /**/
    }                               /**/
    * {                             /**/
         box-sizing: border-box;    /**/
    }                               /*REQUIRED FOR FOOTER*/
</style>
<header>
    <a href="TinkerRat.html" style="font-size: 250%; padding: 5%;">TinkerRat</a>
</header>
<nav>
    <div class="row">
        <div class="column">
            <a href="Current Projects.html" style="font-size: 200%; padding: 5%;">Current Projects</a>
        </div>
        <div class="column">
            <a href="Complete Projects.html" style="font-size: 200%; padding: 5%;">Complete Projects</a>
        </div>
        <div class="column">
            <a href="Resources.html" style="font-size: 200%; padding: 5%;">Resources</a>
        </div>
      </div>
</nav>
<body>
    <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
</body>
<footer>
    <svg width="100%" height="60">
        <path d="M0 10 L200 10 L210 40 L410 40 L420 20 L620 20 L630 10 L830 10 L840 20 L1040 20 L1050 40 L1250 40 L1260 20 L1366 20" stroke="#00ff00" stroke-width="10" fill="#838383">
    </svg>
    <div class="row">
        <div class="column" style="width: 25%;">
            <a href="Current Projects.html" style="font-size: 200%; padding: 20px; padding-left: 10px; padding-right: 10px;">Current Projects</a><br>
            <a href="Current Project 1.html">Project 1</a><br>
            <a href="Current Project 2.html">Project 2</a><br>
            <a href="Current Project 3.html">Project 3</a><br>
        </div>
        <div class="column" style="width: 25%;">
            <a href="Complete Projects.html" style="font-size: 200%; padding: 20px; padding-left: 10px; padding-right: 10px;">Complete Projects</a><br>
            <a href="Complete Project 1.html">Project 1</a><br>
            <a href="Complete Project 2.html">Project 2</a><br>
            <a href="Complete Project 3.html">Project 3</a><br>
        </div>
        <div class="column" style="width: 20%;">
            <a href="Resources.html" style="font-size: 200%; padding: 20px; padding-left: 10px; padding-right: 10px;">Resources</a><br>
            <a href="Resource 1.html">Resource 1</a><br>
            <a href="Resource 2.html">Resource 2</a><br>
            <a href="Resource 3.html">Resource 3</a><br>
        </div>
        <div class="column" style="width: 25%;">
            <a href="Contacts.html" style="font-size: 200%; padding: 20px; padding-left: 10px; padding-right: 10px;">Contacts</a><br>
            <a href="Resource 1.html">Resource 1</a><br>
            <a href="Resource 2.html">Resource 2</a><br>
            <a href="Resource 3.html">Resource 3</a><br>
        </div>
      </div>
</footer>
</html>
