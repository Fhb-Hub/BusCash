# Bus Cash

Um aplicativo mobile desenvolvido no Kodular (App Inventor) para atender as necessidades dos usuários de transportes públicos, as quais foram abordadas no TCC do técnico em Desenvolvimento de Sistema realizado na Etec Polivalente Americana.

# Manual de Instalação

Abaixo estão listados os passos para instalação e funcionamento da aplicação desenvolvida.

## Instalação do HeidiSQL

1.	Abra o navegador;
2.	Acesse o seguinte link: https://www.heidisql.com ;
3.	Execute o download; 
4.	Após o download, clique em abrir;
5.	Clique em executar; 
6.	Autorize os termos; 
7.	Escolha a pasta a qual o software deverá ser salvo; 
8.	Clique em instalar;
9.	 Aguarde a instalação.

## Instalação do Xampp

1.	Abra o navegador;
2.	Pesquise por Xampp;
3.	Acesse o seguinte link: https://www.apachefriends.org/pt_br/index.html ;
4.	Execute o download;
5.	Após o download, clique em abrir;
6.	Clique em executar; 
7.	Clique em próximo; 
8.	Aguarde a instalação.

## Download dos arquivos necessários 

1.	Abra o navegador
2.	Acesse o seguinte link: https://github.com/Fhb-Hub/BusCash ;
3.	Clique em “Code” e em sequência em “Download zip”;
4.	Após o download, extraia a pasta com os arquivos baixados.

## Conexão entre o banco de dados e a aplicação

1.	Abra o gerenciador de arquivo;
2.	Clique sobre disco local (C);
3.	Procure pela pasta “Xampp”;
4.	Após abrir a pasta, procure por “htdocs”;
5.	Dentro de “htdocs”, copie a pasta BusCash baixada anteriormente;
6.	Abra o Xampp;
7.	Procure “Mysql” e clique em “Start”;

## Criação do banco de dados local

1.	Abra a pasta “BusCash” baixada anteriormente;
2.	Clique sobre o arquivo “buscash”;
3.	O programa HeidiSQL deverá abrir, nele você deverá selecionar a linha responsável pela criação do banco de dados e pressionar as teclas “Ctrl + F9”;
4.	Atualize a aplicação e você encontra o banco de dados “buscash”, criado no passo anterior, basta selecioná-lo para torná-lo ativo; 
5.	Selecione as demais linhas de comando e pressione as teclas “Ctrl + F9”;
6.	Atualize o banco de dados e você notará a criação de uma tabela, cuja o nome é “usuarios”. Dessa forma, o banco de dados estará pronto para uso; 
 
## Importando o projeto para o Kodular

1.	Abra o navegador;
2.	Acesse o seguinte link “https://www.kodular.io”;
3.	Crie uma conta;
4.	Clique em “Import Project – Escolher Arquivo” e selecione o arquivo “BusCash.aia” baixado anteriormente;
5.	Aguarde alguns segundos e pronto o projeto já será importado.

## Como encontrar o IP do meu computador?

1.	Entre no “Prompt de Comando” do computador;
2.	Após o aplicativo abrir, digite o comando “ipconfig”;
3.	O prompt deverá exibir uma lista com as configurações das conexões disponíveis, procure por “Adaptador de Rede sem Fio Wi-Fi”, e copie o endereço IPv4 exibido;

## Alteração do IP no aplicativo no Kodular

1.	Voltando ao Kodular, abra o projeto importado anteriormente;
2.	Clique em “Blocks”; 
3.	Procure pelo bloco “initialize global URL” e substitua o endereço IP lá presente pelo da sua máquina (mantenha as outras configurações). Repita esse processo para as seguintes telas: “Screen6” e “Screen7”;
4.	Clique em Designer e abra a tela “Screen2”;
5.	Nos componentes da tela procure por “MySQL_DataBase1” e substitua o endereço IP lá presente pelo da sua máquina (mantenha as outras configurações). Repita esse processo para as seguintes telas: “Screen7” e “Screen9”;

## Instalando o aplicativo “Bus Cash”

1.	Ainda no projeto “BusCash” dentro do Kodular, clique em “Export” e em sequência clique em “Android App (.APK)”. Dessa forma, o site irá compilar o projeto e gerar um link e um QR Code para download do aplicativo;
2.	Efetue o download da aplicação em seu celular;
3.	Instale o arquivo baixado;
4.	Pronto o aplicativo já está disponível para uso;
5.	Para realizar as transações utilize o QR Code baixado anteriormente no GitHub;

Observação: para funcionamento do aplicativo ambos os dispositivos (computador e celular) devem estar conectados na mesma rede.

