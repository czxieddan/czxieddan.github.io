---
title: ciallo
tags: [ciallo, audio, daily]
date: 2024-06-18 22:43:11
categories: daily
---

<button id="play-audio" style="padding: 10px 20px; background-color: #4CAF50; color: white; border: none; border-radius: 5px; cursor: pointer; font-size: 16px;">ciallo</button>

<script>
  var audio = new Audio('audio/ciallo.mp3'); // 替换为您的音频文件URL
  document.getElementById('play-audio').addEventListener('click', function() {
    audio.play();
  });
</script>
