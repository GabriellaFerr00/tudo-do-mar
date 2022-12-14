##Projeto Elcoma

##Passo a passo da execução do MVP

O projeto teve como foco explorar o seguinte problema: O wi-fi fornecido pelo Elcoma apresenta ao público publicidades que geram relatórios de entregas do conteudo ao anunciante. No entanto, o relatorio esta com poucas informacoes expressivas e significativas, alem de nao ser esteticamente interessante. A partir disso desenvolvemos uma solucao com foco no problema identificado que consiste na criacao de um dashboard com maior detalhamento das informacoes sobre os dados coletados a partir do acesso do publico a plataforma, bem como a otimização e segmentação desses anuncios de acordo com o perfil de usuarios e geração de insights de dados.

#O MVP da solução foi construído utilizando as seguintes ferramentas:

#FRONT-END 
Ferramentas de construção de prototipação e desenvolvimento FIGMA e VISUAL STUDIO CODE Linguagens: HTML como linguagem de marcação, CSS como linguagem de estilo, JavaScript como linguagem de programação, Framework: BootStrap, Biblioteca: Libchart para gerar gráficos.

#BACK-END
Ferramentas de desenvolvimento: Eclipse e IntelliJ, Banco de dados: MySQL e FrameWorks: SpringBoot + SpringData.

#Descrição da construção do front-end:

1 - Instalação das ferramentas Figma e Visual Studio Code para a construção da prototipação e do desenvolvimento do sistema Web.

2 - Definição das linguagens HTML, CSS e Javascript, utilizadas para a construção da versão web do dashboard, tela de login para acessar o Wi-Fi, cadastro para acessar o Wi-fi do shooping e a tela da propaganda que irá aparecer semper que o usuário se conectar no Wi-fi ou finalizar seu cadastro.

3 - Instalação da Framework que é opcional a utilização BootStrap, que foi utilizada para aperfeiçoar a responsividade do sistema e usar funcionalidades de codificações pré-prontas.

4 - Utilização da Biblioteca Libchart da Google para a atribuição de dados para os gráficos e criar gráficos estáticos para apresentação da proposta.

Descrição da construção do back-end:

1 - Instalação das ferramentas de desenvolvimento Eclipse ou Intellij (vai da preferência do desenvolvedor) e Workbench do MySQL.

2 - Definição da linguagem base do framework, Java.

3 - Instalação do SpringBoot para fazer a conexão entre a tela de cadastro e o banco de dados, para que todo o dado registrado, seja armazenado no MySQL.

#Local dos arquivos 

1. Ir no arquivo src/main

2. No java/com/cadastro irá encontrar 3 páginas, as controllers, models, repository e o arquivo UsuarioApplication.java

3. Para rodar o programa é apenas na classe UsuarioApplication.java, aperta no botão direto do mouse e clica na opção run as

4. Ao entrar nos controllers, encontrará 3 arquivos IndexController.java (que diz qual será a ação do index.html), PropagandaController.java (que será a ação do propaganda.html) e UsuariosController.java (nesta parte será dito a ação do formUsuario.html)
 
5. Na pasta models encontrará a classe Usuario.java com todas as características do usuário e seus atributos
 
6. A pasta Repository será um arquivo de interface, que irá permitir o html se manifestar na página web

7. Voltando as pastas, encontrará a recources contendo 2 pastas, a static e templates e um arquivo application.properties

8. O apllication.properties é onde acontecerá a conexão com o banco de dados, note que pedirá o usuário, senha, url e etc. Nesta parte será necessário que você altere para o seu banco de dados local. OBS: N alinha 8: spring.jpa.hibernate.ddl-auto=update (para o primeiro acesso altere de update para create, assim, ipra criar a tabela no seu banco de dados e após a execção altere para update novamente, para sempre ir inserindo dados e não dropar e inserir novamente)

9. Entrando na pasta static, encontrará duas, uma img com as imagens utilizadas e outra css com os styles das páginas, os nomes estão bem intuitivos, apenas o style-register que se refere a pagina formUsuario.html.

10. Voltando tudo novamente, entrará na pasta templetes e lá contas todas as páginas html


##Requisitos para uso do programa

1. Ter alguma IDE para abrir os códigos, necessário ter o JDK17 ou versão semelhante (neste caso usamos a versão 17). Segue link: https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html

2. Baixar o mysql versão 8.0.29. Segue link: https://dev.mysql.com/downloads/workbench/

3. Baixar o driver de conexão com o banco de dados. Segue link: https://dev.mysql.com/downloads/connector/j/

4. Criar uma conexão com o banco de dados no +. Anotar todos os dados para posteriormente alterar o arquivo de conexão que abrirá na IDE 

5. Baixar o xamp responsável por ativar o servidor. Usamos o Laragon em sua versão atual.

6. Recomendo que use a IDE Intellij, pois, ao mudar a IDE será necessário adaptar o código e o nosso está adaptado para o Intellij.

7. Agora é só rodar a aplicação.
