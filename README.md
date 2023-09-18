<h1>Projeto front-end para a empresa Nimbus</h1>

**Sobre o Projeto:** <br>
O grupo deverá confeccionar uma página que disponibilizará dados do sistema da empresa para os usuários/clientes

O objetivo do sistema é prever com a ajuda de inteligencia artifical o clima, ondas, marés, ventos e etc. 
com o propósito de vender este serviço para outras empresas como construtoras e etc.

**Sobre os dados:** <br>
Os dados absorvidos pela plataforma:
  * Radares
  * Raios
  * Estações
  * Localização das obras
    
Quais dados serão retornados ao usuário:
  * Lista de variáveis extensas
  * Estacoes sísmicas
  * Estacoes oceânicas
  * Outros sensores e métricas diferentes
  * Retorno do tipo Json ou CSV
  * teremos acesso a endpoints para a obtenção dos dados(obs: não tem documentação)

**Sobre as Funcionalidades:** <br>
 Criar uma pagina mais robusta, que disponibilize esses dados nos formatos:
  * Tabelas
  * Gráficos
  * Marcadores de georeferência
  * Botões para exportação para CSV, PDF e PNG
  * Interação entre os componentes
  * Adaptação para mobile

**Sobre os Desafios:** <br>
 Formatos de pesquisa de dados:
  * Além do formulário
  * Interagir com os marcadores
  * Desenhar um retângulo na imagem e pesquisar varias estações
  * Marcador no mapa é alterado conforme os critérios(já configurados no sistema)

 * Gráfico dinâmico:
   * Gráfico criado com base nos dados requisitados pelo usuário

 * Otimização no layout da tabela:
   * Criar um layout responsivo para que mantenha uma forma agradável em um monitor e em um celular

<h2>5W2H</h2>

Pergunta | Resposta
-------------|-------------
What - O quê  | A empresa Nimbus possui o Chronos, um sistema que fornece dados para previsões personalizadas, diárias ou semanais, por área ou regiâo de interesse, o que facilita o planejamento do projeto e reduz a chance de atrasos no cronograma.
Why - Por quê  | A empresa reconhece que sua plataforma atual é pouco intuitiva e deseja melhorar a experiência do cliente. Isso inclui otimizar o visual, responsividade e usabilidade do site, a fim de oferecer um serviço de maior qualidade.O objetivo do sistema é disponibilizar dados meteorológicos precisos para empresas e individuos que trabalham em areas que dependem desses tipos de dados.
Where - Aonde | O sistema estará disponível tanto para desktops quanto para dispositivos móveis, garantindo acesso flexível. Os usuários poderão acessar os dados meteorológicos por meio de um site na web. 
When - Quando | As empresas e indivíduos buscarão os dados meteorológicos sempre que planejarem uma obra ou precisarem de informações meteorológicas. O sistema poderá ser utilizado durante a execução da obra e também após a conclusão, para monitoramento contínuo.  
Who - Quem | O sistema será usado por empresas e indivíduos que necessitam de dados meteorológicos precisos. Esses usuários estão envolvidos em obras, áreas de meteorologia, estaleiros e outros setores que dependem de informações meteorológicas confiáveis. 
How - Como | O sistema absorve dados meteorológicos e de radar, incluindo dados de raios, informações de estações meteorológicas e dados das obras e localizações a serem monitoradas. Ele utiliza um endpoint com estações pré-listadas para coletar os dados. Os dados serão apresentados aos usuários por meio de tabelas, gráficos e um mapa com marcadores georreferenciados. O acesso ao sistema será realizado por meio de um site na web, que será otimizado para oferecer uma experiência mais intuitiva e responsiva aos clientes.  

<h2>Requisitos</h2>


***Requisitos Funcionais***

RF-1 O sistema deve apresentar dados por meio de tabelas, gráficos e marcadores georreferenciados em um mapa.

Rf-2 O sistema deve permitir  a exportação dos dados em formatos diferentes. (CSV, PDF e PNG).

Rf-3 O sistema deve permitir a busca de dados específicos.

Rf-4 O sistema deve incluir um mapa interativo com marcadores para cada ponto de monitoramento e estação.

RF-5 O sistema deve disponibilizar relatorios de uma estação, caso selecionada no mapa.

Rf-6 O sistema deve permitir a interatividade com os gráficos.

Rf-7 O sistema deve possibilitar a escolha das variáveis a serem exibidas simultaneamente.


***Requisitos Não Funcionais***

Rn-1 O sistema deve apresentar um novo layout, melhorando a experiência do usuário.

Rn-2 O sistema deverá ser acessado pela web.

Rn-3 O sistema deve possuir portabilidade para mobile.

Rn-4 O sistema deve permitir desenhar um quadrado no mapa e porseguinte a seleção de multiplos marcadores.

***Integrantes***
Daniel Lloyd
Henrique Dantas
Hudson Assumpção
Thiago Borsoni
Ricardo Castro
