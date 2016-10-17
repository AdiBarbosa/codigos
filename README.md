# codigos

Script ativa botão 

<!-- INICIO DO CÓDIGO --->

<script type="text/javascript">
 <!--
 function escondeDiv() {
 document.getElementById("addtocart").style.display = "block";
 }

 function escondeTempo() {
 document.getElementById("tempo").style.display = "none";
 }
  var minutos = 0;
   var segundos = 4;

  function chamar(){
 	 if(segundos>0){document.getElementById('segundos').innerHTML = --segundos;}
 	  if(segundos==0 && minutos>0){document.getElementById('minutos').innerHTML = --minutos;
 	  segundos = 60;
 	  }

 	   if(minutos==0 && segundos==0){setTimeout("escondeDiv()",1000);
 	   setTimeout("escondeTempo()",1000);

 	   }
 }
 setInterval("chamar();", 1000);

 //-->
 </script>


<div id="addtocart" style="display:none;">

<a title="Pagamento Seguro" HREF="https://pay.hotmart.com/order/checkout/paycomponent.html?order=O3992858C&checkoutMode=6&cid=1095856"><img alt="Pagamento Seguro" SRC="https://s10.postimg.org/driw1jczd/comprar.png" BORDER="0"/>
</a>

</div>

<!-- FIM DO CÓDIGO --->
