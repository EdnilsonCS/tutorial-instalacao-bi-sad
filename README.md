# Tutorial ferramenta de bi
<b> Um pequendo tutorial (mais detalhado) de como instalar e usar o <i>Power BI</i> e testar a ferramenta</b>

## How install the Power BI?
![](https://www.multimidiaearte.com.br/wp-content/uploads/2019/03/power-BI-1030x579.png)
 * Passo 1 <br/>
   Vamos lá,
   primeiro entre no [site](https://powerbi.microsoft.com/pt-br/).
   clique no incone laranja de "Começe gratuitamente", depois que a nova tela carregar clique clique em baixar gratuitamente.
 * Passo 2 <br/>
   Depois,
   Vai abrir a loja do windows
   você precisa deixar permitido a instalação de progamas de fontes externas.
   depois que a loja estiver aberta clique em <b>"ober"</b> 
 * Passo 3 <br/>
   Espere baixar (vai depender da velocidade da sua internet)
 * Passo 4 <br/>
   Depois, clique em <b>Iniciar</b>
  
  ## How install the MySql SGBD?
![](https://www.hospedagemsegura.com.br/wp-content/uploads/2016/03/MySQL.jpg)

 * Passo 1 <br/>
   Primeiro acesse o [site](https://dev.mysql.com/downloads/installer/) 
   para poder baixar o mysql
 * Passo 2 <br/>
   Depois baixe a verção Community para windows 
   com o nome mysql-installer-community-_._._._.msi (os traços é por causa da mudança de verção).
   você vai ser redirecionado para outra págna, clique apenas em <b>No thanks, just start my download</b>. 
 * Passo 3 <br/>
   Espere concluir o dawload.
 * Passo 4 <br/>
   Encontre o local no qual o arquivo foi salvo
 * Passo 5 <br/>
   Clique duas vezes para instalar o programa.
 * Passo 6 <br/>
   Permita que ele tenha acesso de adiministrador ao pc
 * Passo 7 <br/>
   Selecione a opção de desenvolvedor
 * Passo 8 <br/>
   Clique em next, next  e depois execute.
 * Passo 9 <br/>
   Clique em next, next e depois coloque uma senha para seu SGBD
   Depois clique em next, next e depois finish, depois next ,depois finish, next,execute, depois finish
   depois next e finalmente finish
 * OK MY SQL INSTALADO NO PC
   
## How add the Sakila database
![](http://jcvandenberg.eu/images/IMG_0248.jpg)  
 * Passo 1 <br/>
   Baixe a base de dado nessa [págna](https://dev.mysql.com/doc/index-other.html)
   Selecione sakila data base como arquivo zip 
 * Passo 2 <br/> 
   Abra o zip baixado e selecione sakila-schema.sql
 * Passo 3 <br/>
   Vai Abrir o mysql Workbench, vá em data base no menu e selecione connect to database.
   vai abrir uma janela clique em Store in vult e digite sua senha. 
 * Passo 4 <br/>
   vai abrir uma nova janela cole o script do banco nessa  nova janela e clique no raio
 * Passo 5 <br/>
   Depois volte no arquivo zip e clique no arquivo sakila-schema.sql
   Copie o código e cole na pagna que esta conectada ao SGBD
   e clique no raio.
 *  OK BASE DE DADOS INICIALIZADA

## How to make a graph in Power BI
![](https://www.resumoescolar.com.br/wp-content/imagens/construindo-a-ciencia.jpg)
  * Passo 1 <br/>
    Abra o power bi pesquisando no windows ou na tela inicial do windows
  * Passo 2 <br/>
    Agora vamos conectar o banco de dados ao power bi, para isso feixe uma 
    pequena janela que abre no power BI ( não a janela do programa)
  * Passo 3 <br/>
    Clique em obter dados no menu superior 
  * Passo 4 <br/> 
    pesquise por mysql na tela que abrir e clique no banco de dados mysql
  * Passo 5 <br/>
    no local de servidor colocar localhost
  * Passo 6 <br/>
    no local de banco de dados colocar Sakila
  * Passo 7 <br/>
    selecione as tabelas que vão ser usada no banco de dados  
