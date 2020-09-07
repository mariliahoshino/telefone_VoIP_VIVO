# telefone_VoIP_VIVO

Este tutorial é para como conseguir configurar o aparelho VoIP ATA GKM 2210T da intelbrás utilizando o serviço VoIP da VIVO

O roteador da vivo Mitrastar que somos obrigado a utilizar ele porque nele está travado o sistema de internet e telefone VoIP
O de internet é possível utilizar outro roteador e conseguir utilizar, o problema está no serviço VoIP, onde os dados vem oculto e a VIVO nega a fornecer o login e senha para utilizar outro aparelho como roteador

Nesse tutorial é ensinado como obter os dados de login e senha para conseguir utilizar o serviço VoIP como deseja

Primeiramente entrando no roteador como administrador

192.168.1.1/padrao

login support
senha debaixo do roteador

Ir em Management ->Settings -> Backup Botão Backup Settings

Será feito o dowload do arquivo
Abrir o arquivo e pesquisar por *<SIP>*
  
Irá achar duas informações
<AuthUserName> e
<AuthPassword>
Copie a senha nesse campo
    
Ir no site
https://www.base64decode.org/

Cole essa senha e clique em converter, será obtida a senha real

Copie essa senha 
Acesse o aparelho VoIP da intelbras
Na parte Usuário -> Usuário 1
preencher conforme a imagem, tendo o seu número de telefone que deverá ser digitado 
e no campo senha colar a senha obitido do site

fontes
https://forum.vivo.com.br/threads/114368-Configura%C3%A7%C3%A3o-SIP <br>

https://www.base64decode.org/ <br>
