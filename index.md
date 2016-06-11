---
layout: default
title: Hello
---

<div class="well">
  <div class="title">What I do</div>
  <p class="justify-text">
    I'm an experienced <b>HTML5</b> and <b>JavaScript</b> developer creating modern web applications using latest technologies and standards. I've worked in countries all around the world, in large corporations and in small start ups, in big, multinational project teams and as a free lancer.
  <p>
  <p class="justify-text">
    Mostly I focus on <b>Single Page Applications</b> that are based on powerful frameworks like <b>Angular</b>, <b>React</b>, or <b>Backbone</b>. I've also build JavaScript-based Back Ends for <b>REST</b> or <b>WebSocket</b> services and set up a variety of blogs, web sites, and online shops using <b>Content Management Systems</b>.
  </p>
</div>

<div class="divider"></div>

<div class="well">
  <div class="title">Who I've worked for</div>

  <div class="cells">
    <a href="https://www.telstra.com.au" target="_blank" class="cell">Telstra <small>(AUS)</small></a>
    <a href="http://www.ie.com.au" target="_blank" class="cell">IE <small>(AUS)</small></a>
    <a href="https://www.plycode.com" target="_blank" class="cell">Plycode <small>(AUS)</small></a>
    <a href="http://www.akquitek.de" target="_blank" class="cell">Akquitek <small>(GER)</small></a>
    <a href="http://www.telekom.de" target="_blank" class="cell">Telekom <small>(GER)</small></a>
    <a href="http://www.musala.com" target="_blank" class="cell">Musala Soft <small>(BG)</small></a>
    <a href="https://www.trtech.ca" target="_blank" class="cell">TRTech <small>(CA)</small></a>
    <a href="http://www.aidagroup.com.au" target="_blank" class="cell">AIDA <small>(AUS)</small></a>
    <a href="http://www.sternengalerie.de" target="_blank" class="cell">Sternengalerie <small>(GER)</small></a>
    <a href="http://www.strathconaanimalbedding.ca" target="_blank" class="cell">Strathcona Animal Bedding <small>(CA)</small></a>
  </div>
</div>

<div class="divider"></div>

<div class="well">
  <div class="title">How to get in touch</div>
  <button class="btn" onclick="contact()">Click me</button>
</div>

<script>
  var contact = function() {
    var socialBar = document.querySelector('.social-links');

    // scroll up
    document.body.scrollTop = socialBar.offsetTop - 100;

    // highlight bar
    socialBar.classList.add('highlight');

    // un-highlight bar
    setTimeout(function() {
        socialBar.classList.remove('highlight');
    }, 1000);
  }
</script>
