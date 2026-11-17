# MoneyStone---Sistema-de-bolsas
osdjcpoj ovponf
MoneyStone
Financial Intelligence Dashboard --- um protótipo de aplicação web
para visualização e comparação de informações do mercado financeiro, com
foco em empresas listadas na B3.

O MoneyStone combina uma interface de identidade visual premium com
ferramentas para organizar análises, acompanhar indicadores
demonstrativos e consultar notícias e referências financeiras.
Status do projeto: protótipo funcional em desenvolvimento. As
cotações, projeções e notícias reais dependem de integrações futuras
com APIs e provedores de dados. Não utilize os valores demonstrativos
para decisões financeiras.

Visão geral
O projeto foi desenvolvido como uma aplicação web leve, com HTML, CSS e
JavaScript, priorizando simplicidade de execução e portabilidade.
Funcionalidades do protótipo
- Dashboard inicial: visão geral do painel, saudação e indicadores
  demonstrativos.
- Relógios internacionais: horários de Brasília, Nova York e
  Berlim.
- Mercado e notícias: área de indicadores e referências de
  notícias econômicas, com espaço para integração de fontes.
- Comparação de empresas: seleção de duas empresas para visualizar
  um painel comparativo e informações resumidas.
- Projeções demonstrativas: apresentação ilustrativa de cenários,
  sem caráter de previsão financeira real.
- Comparações salvas: criação, edição e exclusão de painéis
  armazenados localmente.
- Personalização: opções de tema e idioma (português, espanhol,
  inglês e alemão).
- Bloqueio local: opção de proteção do painel por senha no próprio
  navegador.
- Importação CSV: possibilidade de carregar uma lista de empresas
  a partir de um arquivo CSV.
Tecnologias
- HTML5
- CSS3
- JavaScript
- localStorage para persistência local de preferências e comparações
- APIs de internacionalização e fuso horário do navegador
O protótipo não exige instalação de dependências ou processo de build.
Como executar
Opção 1 --- navegador
1. Baixe ou clone este repositório.
2. Abra o arquivo moneystone.html em um navegador atualizado.
Opção 2 --- Visual Studio Code
1. Abra a pasta do projeto no Visual Studio Code.
2. Abra moneystone.html.
3. Execute com a extensão Live Server, ou abra o arquivo
   diretamente no navegador.
Não é necessário instalar Node.js, React ou executar npm install para
utilizar a versão estática.
Estrutura esperada
MoneyStone/
└── moneystone.html
A versão portátil concentra a estrutura, os estilos e os scripts em um
único arquivo.
Dados e limitações
Este repositório contém um protótipo de interface e funcionalidades
locais. Antes de considerar o sistema uma ferramenta de análise
financeira em produção, será necessário:
1. Integrar um provedor confiável de cotações e indicadores,
   respeitando disponibilidade, licença e limites de uso da API.
2. Validar a cobertura e a atualização da relação de empresas listadas
   na B3.
3. Integrar fontes de notícias e exibir claramente título, veículo,
   data e link original.
4. Definir uma metodologia transparente para indicadores e projeções,
   incluindo período, premissas e limitações.
5. Implementar um backend seguro caso sejam necessários autenticação,
   sincronização entre dispositivos ou armazenamento compartilhado.
Importante: os valores e projeções demonstrativos servem apenas para
apresentação e testes da interface. Não representam recomendações de
compra ou venda, nem aconselhamento de investimento.
Próximos passos
- [ ] Integrar cotações de mercado e indicadores com atualização
  conforme o provedor.
- [ ] Importar e validar a relação completa de ativos da B3.
- [ ] Conectar feeds de notícias em português e registrar as fontes.
- [ ] Documentar a metodologia de comparação e projeção.
- [ ] Avaliar backend e autenticação para uso multiusuário.
- [ ] Ampliar testes de usabilidade, acessibilidade e responsividade.
Identidade visual
O MoneyStone utiliza uma identidade visual inspirada no universo
financeiro e em tecnologia, com tons de verde esmeralda, dourado,
grafite e off-white.
Autor
Leonardo Lopes Ferreira Barbosa

Projeto desenvolvido para fins educacionais e de portfólio em Engenharia
de Software.
MoneyStone --- Financial Stability & Wealth Architecture.
