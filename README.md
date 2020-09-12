# telefone_VoIP_VIVO

Este tutorial é para como conseguir configurar o aparelho VoIP ATA GKM 2210T da intelbrás utilizando o serviço VoIP da VIVO

O roteador da vivo Mitrastar que somos obrigado a utilizar ele porque nele está travado o sistema de internet e telefone VoIP
O de internet é possível utilizar outro roteador e conseguir utilizar, o problema está no serviço VoIP, onde os dados vem oculto e a VIVO nega a fornecer o login e senha para utilizar outro aparelho como roteador

Nesse tutorial é ensinado como obter os dados de login e senha para conseguir utilizar o serviço VoIP como deseja

Primeiramente entrando no roteador como administrador

**192.168.1.1/padrao**

login **support** <br>
senha **debaixo do roteador** <br>

Ir em Management ->Settings -> Backup Botão Backup Settings
<img src="https://github.com/mariliahoshino/telefone_VoIP_VIVO/blob/master/pictures/001.png?raw=true" widht="400" >

Será feito o dowload do arquivo <br>
Abrir o arquivo e pesquisar por **SIP**
  
Irá achar duas informações <br>
**AuthUserName** e <br>
**AuthPassword** <br>
Copie a senha nesse campo <br>
<img src="https://github.com/mariliahoshino/telefone_VoIP_VIVO/blob/master/pictures/002.png?raw=true" widht="400" >

    
Ir no site <br>
https://www.base64decode.org/

Cole essa senha e clique em converter, será obtida a senha real <br>
<img src="https://github.com/mariliahoshino/telefone_VoIP_VIVO/blob/master/pictures/003.png?raw=true" widht="400" >

Copie essa senha <br>
Acesse o aparelho VoIP da intelbras <br>
Na parte Usuário -> Usuário 1 <br>
preencher conforme a imagem, tendo o seu número de telefone que deverá ser digitado <br>
e no campo senha colar a senha obtido do site <br>
<img src="https://github.com/mariliahoshino/telefone_VoIP_VIVO/blob/master/pictures/004-5.png?raw=true" widht="400" >

Reinicia o aparelho VoIP da Intelbras e esperar carregar, testar ligando e recebendo chamadas e pronto a configuração <br>

Deverá ficar assim a página inicial do aparelho VoIP<br>
<img src="https://github.com/mariliahoshino/telefone_VoIP_VIVO/blob/master/pictures/005.png?raw=true" widht="400" > <br>

fontes <br>
https://forum.vivo.com.br/threads/114368-Configura%C3%A7%C3%A3o-SIP <br>

https://www.base64decode.org/ <br>
