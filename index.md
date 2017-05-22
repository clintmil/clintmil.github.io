---
layout: archive
permalink: /
title:
img: "/images/images/banner-secondary4.jpg"

---

image:
  background-image: url("/images/banner-secondary4.jpg");
  height: 500px;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;

<div style="text-align:center;">
We integrate human genetics and multi-omics datasets from large cohorts and primary tissues to unravel causal mechanisms and identify new targets for cardiovascular diseases. Ultimately these targets are subjected to rigorous and disease-relevant functional screens employing both genetic and pharmacological/biological perturbations.

</div>



<div class="post-entry">
        <h1 class="post-subtitle">About us</h1>
	<div style="text-align:left;">
We integrate human genetics and multi-omics datasets from large cohorts and primary tissues to unravel causal mechanisms and identify new targets for cardiovascular diseases. Ultimately these targets are subjected to rigorous and disease-relevant functional screens employing both genetic and pharmacological/biological perturbations.
</div>


<div class="post-entry">
        <h1 class="post-subtitle">News</h1>
	<div style="text-align:center;">
<a class="twitter-timeline" href="https://twitter.com/clintomics" data-widget-id="338870296415174656">Tweets by @clintomics</a> <script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>
	
   	</div>
</div>

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
