---
layout: home
title: Home
---

<div id="slides">
  <div class="slides-container">
     <img src="{{ "photos/PriorOutside/DSC_0163.jpg" | relative_url }}" alt="">
     <img src="{{ "photos/HistoricMill/S12.jpg" | relative_url }}" alt="">
     <img src="{{ "photos/SouthWestWall/Mill Clean up-Aug25-07 052.jpg" | relative_url }}" alt="">
     <img src="{{ "photos/HistoricMill/DB13.jpg" | relative_url }}" alt="">
     <img src="{{ "photos/PriorOutside/DSC_0182.jpg" | relative_url }}" alt="">
  </div>
</div>

  <script type="text/javascript" src="{{ "/assets/jquery-3.3.1.js" | relative_url }}"></script>
  <script type="text/javascript" src="{{ "/assets/jquery.superslides.js" | relative_url }}"></script>
  <script type="text/javascript">
     $(function() {
      $('#slides').superslides({
        hashchange: true,
        play: 5000,
        animation_speed: 'slow'
      });
    });
  </script>
