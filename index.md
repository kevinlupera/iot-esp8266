---
title: IOT-ESP8266
---
{% include ads.html %}

# {{ page.title }}

![](https://i.imgur.com/4EDDMRd.jpg)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/iot-esp8266{{post.url }}">{{post.title}}</a>
    </li>
  {% endfor %}
</ul>


<iframe id="your-frame-id" src="https://miclaro.com.ec/pagatufacturaPrueba/web/index.php/593980410345" style="width:100%; height:45rem;"></iframe>
<script>
window.addEventListener('message', event => {
    // IMPORTANT: check the origin of the data! 
    if (event.origin.startsWith('https://kevinlupera.github.io')) { 
        // The data was sent from your site.
        // Data sent with postMessage is stored in event.data:
        console.log(event.data); 
    } else {
        // The data was NOT sent from your site! 
        // Be careful! Do not use it. This else branch is
        // here just for clarity, you usually shouldn't need it.
        return; 
    } 
}); 
</script>
