---
layout: post
title: Image Editor
---
# Tweak with an image
I have an image here that is loaded through Cloudflare Transformations, so you can click it to cycle the saturation. There is only one image file, but the saturation is adjusted in real time on Cloudflare's servers.

Image credits: katorisi, [CC BY 3.0](https://creativecommons.org/licenses/by/3.0), via Wikimedia Commons

> Note: the image will reload upon clicking. The service is limited to 5000 transformations a month.

<img src="/cdn-cgi/image/saturation=1.0/chrysanthemum.jpg" onclick="let x = document.querySelector('#image1').src;switch(x){case '/cdn-cgi/image/saturation=1.0/chrysanthemum.jpg': x='/cdn-cgi/image/saturation=1.5/chrysanthemum.jpg';break;case '/cdn-cgi/image/saturation=1.5/chrysanthemum.jpg': x='/cdn-cgi/image/saturation=0.5/chrysanthemum.jpg';break;case '/cdn-cgi/image/saturation=0.5/chrysanthemum.jpg': x='/cdn-cgi/image/saturation=1.0/chrysanthemum.jpg';break;default: x='/cdn-cgi/image/saturation=1.0/chrysanthemum.jpg';break;};document.querySelector('#image1').src=x">
