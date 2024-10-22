---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /project
---

{% include base_path %}

This page is currently being updated. Please refer to the [[Project Page](https://rgblimp.github.io/)] for the latest information. 

---

# Research Projects
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Video Switcher</title>
</head>
<body>
    <div id="videoContainer"></div>
    <script>
        fetch('https://ipapi.co/json/')
        .then(response => response.json())
        .then(data => {
            const country = data.country;
            const videoContainer = document.getElementById('videoContainer');
            if (country === 'CN') {
                videoContainer.innerHTML = `
                    <iframe src="https://www.bilibili.com/video/BV1Y1421k7SD" width="560" height="315" frameborder="0" allowfullscreen></iframe>
                `;
            } else {
                videoContainer.innerHTML = `
                    <iframe src="https://www.youtube.com/watch?v=yA_nncO6qE4" width="560" height="315" frameborder="0" allowfullscreen></iframe>
                `;
            }
        })
        .catch(error => console.error('Error fetching IP data:', error));
    </script>
</body>
</html>

<script>
  fetch('https://ipapi.co/json/')
  .then(response => response.json())
  .then(data => {
      const country = data.country;
      const videoContainer = document.getElementById('videoContainer');
      if (country === 'CN') {
          videoContainer.innerHTML = `
              <iframe src="https://www.bilibili.com/video/BV1Y1421k7SD" width="560" height="315" frameborder="0" allowfullscreen></iframe>
          `;
      } else {
          videoContainer.innerHTML = `
              <iframe src="https://www.youtube.com/watch?v=yA_nncO6qE4" width="560" height="315" frameborder="0" allowfullscreen></iframe>
          `;
      }
  })
  .catch(error => console.error('Error fetching IP data:', error));
</script>



---

# Competition Projects