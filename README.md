GeoSaúde Brasil: Análise e Visualização de Dados de Saúde e Sociais
O projeto GeoSaúde Brasil oferece uma plataforma interativa para explorar e visualizar dados estatísticos e de saúde de todos os estados brasileiros. Utilizando o poder das bibliotecas Leaflet e TopoJSON, o mapa permite uma análise geográfica detalhada de diferentes indicadores, desde a distribuição de renda e população até o impacto de condições de saúde como a Tuberculose, HIV e Arboviroses.

Funcionalidades Principais
Mapas Temáticos: Navegue por uma variedade de mapas que destacam dados como:

Indicadores Sociais: Renda Média, População, Servidores Públicos, Professores e mais.

Saúde Pública: Casos de COVID-19 (por região), Arboviroses, Tuberculose, Sífilis e HIV/AIDS.

Análise de Clusters: Mapas gerados por Análise de Clusters de IA, combinando diferentes variáveis para identificar padrões (e.g., Renda x HIV, População x Deficientes Auditivos).

Interatividade: Passe o mouse sobre um estado para ver informações detalhadas em um pop-up.

Legenda Dinâmica: A legenda do mapa se ajusta automaticamente ao indicador selecionado, facilitando a interpretação das cores e dos valores.

Controles de Navegação: Botão para centralizar o mapa no Brasil e controles de zoom e movimento para uma exploração intuitiva.

Coerência Visual: As camadas de dados socioeconômicos (Deficientes Auditivos, Servidores Públicos, Professores e Professores Federais) utilizam paletas de cores em gradiente unificadas, garantindo uma representação visual consistente.

Como Usar
Abra o arquivo index.html em seu navegador web. Não é necessário um servidor local, pois o projeto funciona totalmente offline.

Selecione o Mapa: Use o menu suspenso "Escolha o mapa desejado" para alternar entre os diferentes conjuntos de dados.

Explore: Use o mouse para mover e o scroll para dar zoom. Clique no botão "Centralizar Mapa" para retornar à visualização completa do Brasil.

Interaja: Passe o cursor sobre os estados para visualizar o nome e as estatísticas detalhadas de cada um. A legenda no canto inferior direito explica a escala de cores do mapa atual.

Tecnologias Utilizadas
HTML5: Estrutura base do projeto.

CSS3: Estilização da interface, incluindo o mapa e a legenda.

JavaScript: Lógica de manipulação de dados, interatividade do mapa e atualização dinâmica dos elementos.

Leaflet.js: Biblioteca JavaScript de código aberto para mapas interativos e responsivos.

TopoJSON: Extensão do GeoJSON que otimiza o tamanho do arquivo de dados geográficos para um carregamento mais rápido.
