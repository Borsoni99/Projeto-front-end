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
| 5w2h | Resposta |
|-------------|-------------|
| What - O quê  | A Nimbus planeja remodelar a sua página que exporta o histórico de dados para seus clientes, tornando-o mais robusto. |<br>
| Why - Por quê  | A empresa reconhece que sua plataforma atual é pouco intuitiva e deseja melhorar a experiência do cliente. Isso inclui otimizar o visual, responsividade e usabilidade do site, a fim de oferecer um serviço de maior qualidade.O objetivo do sistema é disponibilizar dados meteorológicos precisos para empresas e individuos que trabalham em areas que dependem desses tipos de dados.  |
| Where - Aonde | O sistema estará disponível tanto para desktops quanto para dispositivos móveis, garantindo acesso flexível. Os usuários poderão acessar os dados meteorológicos por meio de um site na web. |
| When - Quando | As empresas e indivíduos buscarão os dados meteorológicos sempre que planejarem uma obra ou precisarem de informações meteorológicas. O sistema poderá ser utilizado durante a execução da obra e também após a conclusão, para monitoramento contínuo.  |
| Who - Quem | O sistema será usado por empresas e indivíduos que necessitam de dados meteorológicos precisos. Esses usuários estão envolvidos em obras, áreas de meteorologia, estaleiros e outros setores que dependem de informações meteorológicas confiáveis.  |
| How - Como | O sistema absorve dados meteorológicos e de radar, incluindo dados de raios, informações de estações meteorológicas e dados das obras e localizações a serem monitoradas. Ele utiliza um endpoint com estações pré-listadas para coletar os dados. Os dados serão apresentados aos usuários por meio de tabelas, gráficos e um mapa com marcadores georreferenciados. O acesso ao sistema será realizado por meio de um site na web, que será otimizado para oferecer uma experiência mais intuitiva e responsiva aos clientes.  |

**What - O que será feito?** <br>
- Desenvolver um protótipo de uma página web, que permita uma melhor usabilidade para todos os clientes. 

**Why - Por que será feito?** <br>
A empresa Nimbus possui um sistema de previsão personalizada por região de interesse e um histórico de dados disponíveis para exportação de relatórios e laudos.

-> A Nimbus deseja uma página robusta para melhorar a experiência dos usuários/clientes com os serviços da empresa. Com novas formas de disponibilizar dados, 
adaptações e dinamicidade.

**Where - Onde será feito?** <br>
O desenvolvimento do projeto se dará por meio das reuniões da equipe, com apresentações semanais durante as aulas.
A equipe utilizará o notion para aplicar os métodos ágeis.


**When - Quando será feito?** <br>
Durante o segundo semestre de 2023.

**Who - Por quem será feito?** <br>
 O projeto será confeccionado pela equipe Lucky Roll. Os Integrantes são:<br>
  * Daniel (3° periodo Ciência de Dados)<br>
  * Henrique (3° periodo Engenharia da Computação)<br>
  * Hudson (3° periodo Engenharia da Computação)<br>
  * Thiago (3° periodo Ciência de Dados)<br>
  * Ricardo (2° periodo Engenharia da Computação)<br>

**How - Como será feito?** <br>

O projeto será desenvolvido por um grupo de estudantes ao longo do periodo 2023.2, com o auxilio do professor.

**How much - Quanto vai custar?** <br>

O projeto não conta com verba ou auxílios.

***Requisitos Funcionais*** <br>
Rf-1: Os dados devem estar disponíveis em formatos de: 
tabela; gráficos.

Rf-2: Botões que exportem os dados em diferentes modelos, como CSV, PDF e PNG.

Rf-3: Botões que permitam filtrar os dados, como por exemplo, data, local, estação.

Rf-4: Dinamicidade na página, marcadores georreferenciais que alteram as cores com base nos dados requisitados pelo cliente.


***Requisitos Não Funcionais*** <br>
***Portabilidade:***
Pr-1: É essencial uma portabilidade para aparelhos mobile.

***Usabilidade:***
US-1: O cliente poderá interagir com marcadores no mapa, podendo visualizar informações importantes, como nome/tipo da estação e a situação atual.

US-2: O cliente poderá desenhar um retangulo no mapa e pesquisar várias estações.

