# Tipo de Triângulo -  Isósceles, Equilátero, Escaleno.

function funcao(){

  var v1 = parseInt(document.getElementById("v1").value);
  var v2 = parseInt(document.getElementById("v2").value);
  var v3 = parseInt(document.getElementById("v3").value);
 

  // let img = document.createElement('img')
  // img.src = "https://doutormultas.com.br/wp-content/uploads/2017/11/cnh-provisoria-pode-dirigir-em-rodovias-conheca-as-regras.jpg";
  // img.style = " width: 100vw";

  // let img2 = document.createElement('img')
  // img2.src = "https://images.emojiterra.com/google/android-pie/512px/1f51e.png";
  // img2.style = "width: 100vw";
  
  // equilatero
  if(v1 == v2 && v2 == v3){
    document.write("<h1 style='display: flex;justify-content: center; margin-top: 5vh;'>O triângulo é equilátero!</h1><br>");
    location.reload();

  }else if (v1 == v2 || v2 == v3){
    document.write("<h1 style='display: flex;justify-content: center; margin-top: 5vh;'>O triângulo é isósceles!</h1><br>");
    location.reload();
  }else if(v1 !== v2 && v2 !== v3){
    document.write("<h1 style='display: flex;justify-content: center; margin-top: 5vh;'>O triângulo é escaleno!</h1><br>");
    location.reload();
  }
}


