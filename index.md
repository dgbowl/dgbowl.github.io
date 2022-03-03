<style>
    .header {grid-area: header;}
    .footer {grid-area: footer;}
    .main1  {grid-area: main1;}
    .main2  {grid-area: main2;}
    .main3  {grid-area: main3;}

    .grid-container {
        display: grid;
        grid-template-areas:
            'header header header'
            'main1 main2 main3'
            'footer footer footer';
        gap: 10px;
        padding: 10px;
    }
    
    .grid-container > div {
        text-align: center;
        font-size: 18px;
    }
</style>
<div class="grid-container">
    <div class="header"><h1>dgbowl: tools for digital (electro-)catalysis</h1></div>
    <div class="main1">
        <img src="images/tomato.svg" alt="tomato" height="150"/>
        <a href="https://dgbowl.github.io/tomato"><img src="https://badgen.net/badge/docs/dgbowl.github.io/grey?icon=firefox"></a>
        <a href="https://github.com/dgbowl/tomato"><img src="https://badgen.net/github/tag/dgbowl/tomato/?icon=github"></a>
        <a href="https://pypi.org/project/tomato"><img src="https://badgen.net/pypi/v/tomato/?icon=pypi"></a>
    </div>
    <div class="main2">
        <img src="images/yadg.svg" alt="yadg" height="150"/>
        <a href="https://dgbowl.github.io/yadg"><img src="https://badgen.net/badge/docs/dgbowl.github.io/grey?icon=firefox"></a>
        <a href="https://github.com/dgbowl/yadg"><img src="https://badgen.net/github/tag/dgbowl/yadg/?icon=github"></a>
        <a href="https://pypi.org/project/yadg"><img src="https://badgen.net/pypi/v/yadg/?icon=pypi"></a>
    </div>
    <div class="main3">
        <img src="images/dgpost.svg" alt="dgpost" height="150"/>
        <a href="https://dgbowl.github.io/dgpost"><img src="https://badgen.net/badge/docs/dgbowl.github.io/grey?icon=firefox"></a>
        <a href="https://github.com/dgbowl/dgpost"><img src="https://badgen.net/github/tag/dgbowl/dgpost/?icon=github"></a>
        <a href="https://pypi.org/project/dgpost"><img src="https://badgen.net/pypi/v/dgpost/?icon=pypi"></a>
    </div>
    <div class="footer"><p>© 2021-2022</p></div>
</div>