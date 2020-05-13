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

<div id="results"></div>
<iframe id="your-frame-id" src="https://miclaro.com.ec/pagatufacturaPrueba/web/index.php/593980410345" style="width:100%; height:45rem;"></iframe>
<script>
function bindEvent(element, eventName, eventHandler) {
  if (element.addEventListener) {
    element.addEventListener(eventName, eventHandler, false);
  } else if (element.attachEvent) {
    element.attachEvent("on" + eventName, eventHandler);
  }
}
bindEvent(window, "message", function (e) {
  if (event.origin !== "https://miclaro.com.ec") return;
  if (e.data == "statusPayBill-EXITO") {
    succesPayBill();
  } else if (e.data == "statusPayBill-ERROR") {
    errorPayBill();
  }
});
function succesPayBill() {
  //Codigo pago con éxito
}
function errorPayBill() {
  //Codigo pago con error
  alert('error');
}
</script>
