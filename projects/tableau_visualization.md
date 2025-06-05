---
layout: default
title: Tableau Visualization
---

# Tableau Visualization

I built an interactive dashboard highlighting trends in car insurance claims. Stakeholders could explore the data and quickly identify areas of high risk.

<div class="tableauPlaceholder" id="tableau-car-claims" style="position: relative;">
  <noscript>
    <a href="https://public.tableau.com/views/DVT-Project_16435506976430/Story1">
      <img alt="Data visualization on Car Claims of Insurance"
           src="https://public.tableau.com/static/images/DV/DVT-Project_16435506976430/Story1/1_rss.png"
           style="border: none" />
    </a>
  </noscript>
  <object class="tableauViz" width="100%" height="600px">
    <param name="host_url" value="https%3A%2F%2Fpublic.tableau.com%2F" />
    <param name="embed_code_version" value="3" />
    <param name="site_root" value="" />
    <param name="name" value="DVT-Project_16435506976430/Story1" />
    <param name="tabs" value="no" />
    <param name="toolbar" value="yes" />
    <param name="static_image" value="https://public.tableau.com/static/images/DV/DVT-Project_16435506976430/Story1/1.png" />
    <param name="animate_transition" value="yes" />
    <param name="display_static_image" value="yes" />
    <param name="display_spinner" value="yes" />
    <param name="display_overlay" value="yes" />
    <param name="display_count" value="yes" />
    <param name="language" value="en-US" />
    <param name="filter" value="publish=yes" />
  </object>
</div>

<script type="text/javascript">
  document.addEventListener("DOMContentLoaded", function () {
    var divElement = document.getElementById("tableau-car-claims");
    var vizElement = divElement.getElementsByTagName("object")[0];
    vizElement.style.width = "100%";
    vizElement.style.height = (divElement.offsetWidth * 0.75) + "px";
    
    var scriptElement = document.createElement("script");
    scriptElement.src = "https://public.tableau.com/javascripts/api/viz_v1.js";
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
  });
</script>
[View the interactive dashboard](https://public.tableau.com/views/DVT-Project_16435506976430/Story1)
