---
layout: post
title:  "Java Test 01"
date:   2021-07-22
desc: "java_test_01"
keywords: "Ryanvuha,thơ,poems,blog,for_me"
categories: [HTML]
tags: [Ryanvuha]
icon: icon-html
---

<p>Here, a JavaScript changes the value of the src (source) attribute of an image.</p>

<script>
function light(sw) {
  var pic;
  if (sw == 0) {
    pic = "https://www.w3schools.com/html/pic_bulboff.gif"
  } else {
    pic = "https://www.w3schools.com/html/pic_bulbon.gif"
  }
  document.getElementById('myImage').src = pic;
}
</script>

<img id="myImage" src="https://www.w3schools.com/html/pic_bulboff.gif" width="100" height="180">

<p>
<button type="button" onclick="light(1)">Light On</button>
<button type="button" onclick="light(0)">Light Off</button>
</p>
