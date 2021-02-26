# WEB Server Apache2.4 PHP_7.4.15 MySql_5.7.11 / SSL_HTTPS

SERVIDOR WEB SIMPLES, SEGURO, EFICIENTE E DE FÁCIL COFIGUACAO.
## Instalação:
ESSA APLICACAO ESTÁ CONFIGURADA PARA FUNCIONAR NO DIRETÓRIO C:\oito
VOCE PODE DESCOMPACTAR E UTILIZAR EM QUALQUER DIRETORIO, PORÉM TERAR QUE
ALTERAR ALGUNS ARQUIVOS, EXEMPLO ABAIXO:

1. /apache/conf/httpd.conf
Altere a linha que contém 'Define OITO C:/oito/' para seu diretorio escolhido
Exemplo 'C:/Users/jose/oito/'

2. /php/php.ini
Altere a linha que contém 'extension_dir = "/oito/php/ext"'

3. /mysql/my.ini 
Altere a linha que contém 'datadir		= "/oito/mysql/data"'

4. win-acme/settings.config  
Altere a linha que contém '<value>C:\oito\win-acme\certificates</value>,'
## Configuração 
Após concluir as alteracoes acima, execute o arquivo 'oito_Panel' que fica na raiz da aplicacao.
DIGITE 'A' *Instalar Apache*
DIGITE 'B' *Instalar MySql*

1. Para outras opções Siga o Menu.

2. Se Você criar um site primeiro em HTTP e posteriomente quiser transformá-lo em HTTPS, será preciso ir ao Memu selecionar a opção *Abrir httpd.conf*, apagar a versao HTTP antes criada, voltar ao Menu escolher a opção *Abrir pasta dos Sites*, renomear ou deletar e pasta correspondente e após criar o site em HTTPS, vá a pasta renomeada e mova os arquivos para nova pasta criada automaticamente na criação da versão HTTPS.

3. Para gerar o certificado SSL/HTTPS será necessário abrir as portas 80 e 443 no Firewall do Windows.


4. O Usuário e Senha padrão do MySql é root / root


4. Para Windows 8.1 faça download da dll https://oito.us/libsqlite3.dll e copie para pasta C:\Windows\System32, instale o NET Framework https://oito.us/ndp48-web.exe e o Microsoft Visual Studio 2015-2019 https://oito.us/VC_redist.x64.exe

5. Não apague ou mova nenhum arquivo da pasta raiz.


## Download direto
1. https://oito.us/oito.zip
