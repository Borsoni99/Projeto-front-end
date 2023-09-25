<h1>Projeto front-end para a empresa Nimbus</h1>

<h2>5W2H</h2>

Pergunta | Resposta
-------------|-------------
What - O quê  | A Nimbus planeja remodelar a sua página que exporta o histórico de dados para seus clientes, com mais formas de visualizar os dados, como gráficos e tabelas, e um mapa com marcadores interativos.
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

Rf-8 O sistema deve permitir desenhar um quadrado no mapa possibilitando a seleção de multiplos marcadores.


***Requisitos Não Funcionais***

Rn-1 O sistema deve apresentar um novo layout, melhorando a experiência do usuário.

Rn-2 O sistema deverá ser acessado pela web.

Rn-3 O sistema deve possuir portabilidade para mobile.

Rn4: O sistema deve estar disponível 24/7

<h3>Propósito</h3>
O propósito do sistema é fornecer uma ferramenta para a visualização, exportação e análise de dados históricos meteorológicos para que os usuários possam tomar decisões baseados nos dados visualizados.

**Caso de Uso 1: Visualização e Análise de Dados**

- **Nome**: Visualização e Análise de Dados
- **Ator Principal**: Usuário
- **Pré-Condições**: O usuário deve estar logado no sistema.
- **Fluxo Básico**:
   1. O usuário acessa a opção de "Visualizar Dados" no sistema.
   2. O sistema apresenta opções para escolher o tipo de visualização desejado.
   3. O usuário seleciona o tipo de visualização desejado.
   4. O sistema oferece opções de filtro para refinar os dados a serem exibidos.
   5. O usuário configura os filtros de acordo com suas necessidades.
   6. O sistema exibe os dados conforme as configurações selecionadas.
- **Pós-Condições**: 
   - Os dados são exibidos de acordo com as escolhas do usuário.
   - O usuário pode interagir com os dados visualizados.
   - As opções de filtro permitem ao usuário ajustar os dados exibidos conforme necessário.
   - A visualização dos dados é concluída com sucesso.

**Caso de Uso 2: Exportar Dados**

- **Nome**: Exportar Dados
- **Ator Principal**: Usuário
- **Pré-Condições**: O usuário deve estar logado no sistema.
- **Fluxo Básico**:
   1. O usuário acessa a opção de "Visualizar Dados" no sistema.
   2. O sistema apresenta opções para escolher o tipo de visualização desejado.
   3. O usuário seleciona o tipo de visualização desejado.
   4. O sistema oferece opções de filtro para refinar os dados a serem exibidos.
   5. O usuário configura os filtros de acordo com suas necessidades.
   6. O sistema exibe os dados conforme as configurações selecionadas.
   7. O usuário seleciona a opção "Exportar Dados".
- **Pós-Condições**: 
   - O sistema permite ao usuário exportar os dados conforme selecionado.
   - Os dados exportados estão em um formato ou local especificado pelo usuário.
   - O usuário recebe uma confirmação de que a exportação foi concluída com sucesso.
   - Os dados exportados podem ser acessados ou salvos pelo usuário conforme necessário.

<h3>Integrantes</h3>

Daniel Lloyd <br>
Henrique Dantas <br>
Hudson Assumpção <br>
Thiago Borsoni <br>
Ricardo Castro
