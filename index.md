---
layout: page
title: dgbowl
tagline: "dgbowl: tools for digital (electro-)catalysis"
description: >-
    Landing page of the dgbowl project, containing automation and FAIR data post 
    processing tools. Targetted at catalysis, electrocatalysis, battery testing.
    Developed by Peter Kraus at Empa, in the lab of Corsin Battaglia.
---
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
    <div class="header">
        <div style="display: table-cell; vertical-align: middle; 
        min-width: 120px; min-height: 120px; max-width: 120px; max-height: 120px">
            <img src="images/dgbowl.png" alt="dgbowl">
        </div>
        <div style="display: table-cell; vertical-align: middle">
            <h2>: tools for digital (electro-)catalysis</h2>
        </div>
        <hr/>
    </div>
    <div class="main1">
        <img src="images/tomato.png" alt="tomato" height="120" width="120"/><br/>
        <a href="https://dgbowl.github.io/tomato"><img src="https://badgen.net/badge/docs/dgbowl.github.io/grey?icon=firefox"></a><br/>
        <a href="https://github.com/dgbowl/tomato"><img src="https://badgen.net/github/tag/dgbowl/tomato/?icon=github"></a><br/>
        <a href="https://pypi.org/project/tomato"><img src="https://badgen.net/pypi/v/tomato/?icon=pypi"></a><br/>
    </div>
    <div class="main2">
        <img src="images/yadg.png" alt="yadg" height="120"/><br/>
        <a href="https://dgbowl.github.io/yadg"><img src="https://badgen.net/badge/docs/dgbowl.github.io/grey?icon=firefox"></a><br/>
        <a href="https://github.com/dgbowl/yadg"><img src="https://badgen.net/github/tag/dgbowl/yadg/?icon=github"></a><br/>
        <a href="https://pypi.org/project/yadg"><img src="https://badgen.net/pypi/v/yadg/?icon=pypi"></a><br/>
    </div>
    <div class="main3">
        <img src="images/dgpost.png" alt="dgpost" height="120"/><br/>
        <a href="https://dgbowl.github.io/dgpost"><img src="https://badgen.net/badge/docs/dgbowl.github.io/grey?icon=firefox"></a><br/>
        <a href="https://github.com/dgbowl/dgpost"><img src="https://badgen.net/github/tag/dgbowl/dgpost/?icon=github"></a><br/>
        <a href="https://pypi.org/project/dgpost"><img src="https://badgen.net/pypi/v/dgpost/?icon=pypi"></a><br/>
    </div>
    <div class="footer">
        <hr/>
        <p>
            Developed at <img src="images/Empa.svg" alt="empa" height="20"/>,
            <a href="https://www.empa.ch/web/s501">Lab 501: Materials for Energy Conversion</a><br/>
            © 2021-2022
        </p>
    </div>
</div>