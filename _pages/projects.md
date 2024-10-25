---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /project
---

{% include base_path %}

<script>
document.addEventListener("DOMContentLoaded", function() {
    if (window.location.hash) {
        const targetId = window.location.hash.substring(1);
        const targetElement = document.getElementById(targetId);
        const offset = 60;

        const top = targetElement.getBoundingClientRect().top + window.pageYOffset - offset;

        window.scrollTo({
            top: top,
            behavior: "smooth"
        });
    }
});
</script>

<div style="margin-top: 5px;">

---

# Research Projects

<div style="margin-top: -10px;"></div>
<h2> <font color=D95319>R</font><font color=77AC30>G</font><font color=0072BD>B</font>limp-Q: <font color=D95319>R</font>obotic <font color=77AC30>G</font>liding <font color=0072BD>B</font>limp With Moving Mass Control Based on a Bird-Inspired Continuum Arm </h2>

<p align="center">
  <img width="25.3%" src="../files/research/rgblimp-q/Cover.jpg">
  <img width="55%" src="../files/research/rgblimp-q/ProjectPage.gif">
</p>
<div style="text-align: justify;">
  <p style="margin-bottom: -5px;"><strong>Description</strong>:
    Robotic blimps, as lighter-than-air aerial systems, offer prolonged duration and enhanced safety in human-robot interactions due to their buoyant lift. However, robust flight against environmental airflow disturbances remains a significant challenge, limiting the broader application of these robots.
  </p>
  <p style="margin-bottom: -2px;">
    Drawing inspiration from the flight mechanics of birds and their ability to perch against natural wind, this project introduces RGBlimp-Q, a robotic gliding blimp equipped with a birdinspired continuum arm. This arm allows for flexible attitude adjustments through moving mass control to enhance disturbance resilience, while also enabling object capture by using claws to counteract environmental disturbances, similar to a bird. This project presents the design, modeling, and prototyping of RGBlimp-Q, thus extending the advantages of robotic blimps to more complex environments. To the best of the authors’ knowledge, this is the first interdisciplinary design integrating continuum mechanisms onto robotic blimps. Experimental results from both indoor and outdoor settings validate the improved flight robustness against environmental disturbances offered by this novel design. 
  </p>
  [<a href="https://rgblimp.github.io/" style="text-decoration: underline;">Project Page</a>] [<a href="https://github.com/RGBlimp/RGBlimp-Q" style="text-decoration: underline;">Hardware & Code</a>] 
</div>


---

# Competition Projects

<div style="margin-top: -10px;"></div>

<h2 id="bcar"> Bluetooth Cargo Robot </h2>
<p align="center" >
  <img width="27.3%" src="../files/competitions/bcar.jpg">
  <img width="50%" src="../files/competitions/bcar.gif">
</p>
<div style="text-align: justify;">
  <p style="margin-bottom: -5px;"><strong>Description</strong>:
    This project, originated from <i>the 2015 Beijing Engineering Ability Competition</i>, entailed the development of a Bluetooth cargo robot operated via a smartphone. The robot incorporates a differential drive mechanism facilitating flexibility. The robot is equipped with automatic control for lid opening, object retrieval, and cargo transportation, ensuring the secure conveyance of 100g loads to designated locations. The project involves mechanical design, electronic control, and system integration. 
  </p>
  <p style="margin-bottom: -5px;"><strong>Outcome</strong>:
    2nd Place in Beijing Engineering Ability Competition, 2015（Team Leader）
  </p>
</div>