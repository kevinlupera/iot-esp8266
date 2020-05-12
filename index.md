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


<iframe src="https://miclaro.com.ec/pagatufactura/web/index.php/593980410345" style="width:100%; height:45rem;"></iframe>
<script>
window.addEventListener('statusPayBill', function(e) { 
    var estado = e.detail.estado;
    if(estado == 'EXITO'){
        succesPayBill();
    }else{
        errorPayBill();
    }
    
}, false);

function succesPayBill() { 
  //Codigo pago con éxito
}
function errorPayBill() { 
  //Codigo pago con error
}
</script>
