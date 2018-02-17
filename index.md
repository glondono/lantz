---
layout: home
title: Home
---


<div id="slides">
  <ul class="slides-container">
    <li>
      <img src="https://raw.githubusercontent.com/nicinabox/superslides/0.6-stable/examples/images/affinity.jpeg" alt="">
      <div class="container">
        Slide one
      </div>
    </li>
  
  </ul>
  <nav class="slides-navigation">
    <a href="#" class="next">Next</a>
    <a href="#" class="prev">Previous</a>
  </nav>
</div>

  <script type="text/javascript" src="{{ "/assets/jquery-3.3.1.js" | relative_url }}"></script>
  <script type="text/javascript" src="{{ "/assets/jquery.superslides.js" | relative_url }}"></script>
  <script type="text/javascript">
    $(document).ready(function(){
      $('#slides').superslides()
    });
  </script>
