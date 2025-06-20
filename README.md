Pokémon App - Angular & PokeAPI
https://via.placeholder.com/800x400?text=Pok%C3%A9mon+App+Screenshot (Adicione uma imagem real do seu app aqui)

Descrição
Aplicativo desenvolvido em Angular com Ionic para listagem e visualização de Pokémon utilizando a API pública PokeAPI. O projeto inclui funcionalidades como listagem paginada, detalhes completos dos Pokémon, favoritos persistentes e design responsivo.

Funcionalidades Principais
✔ Listagem de Pokémon com scroll infinito
✔ Tela de detalhes com informações completas
✔ Sistema de favoritos com armazenamento local
✔ Design responsivo para mobile e desktop
✔ Navegação por rotas
✔ Filtro por tipos de Pokémon
✔ Cores temáticas baseadas no tipo do Pokémon

Tecnologias Utilizadas
Angular 15+

Ionic 6+

RxJS para gerenciamento de estado

PokeAPI (https://pokeapi.co/)

LocalStorage para persistência de dados

Como Executar o Projeto
Clone o repositório:

bash
git clone https://github.com/seu-usuario/pokemon-app.git
Instale as dependências:

bash
npm install
Inicie o servidor de desenvolvimento:

bash
ng serve
Acesse no navegador:

text
http://localhost:4200
Estrutura do Projeto
text
src/
├── app/
│   ├── pokemon-list/          # Componente da lista de Pokémon
│   ├── pokemon-details/       # Componente de detalhes
│   ├── favorites/             # Componente de favoritos
│   ├── services/              # Serviços da aplicação
│   ├── utils/                 # Funções utilitárias
│   ├── app.module.ts          # Módulo principal
│   └── app.routes.ts          # Configuração de rotas
Padrões de Desenvolvimento
Componentes reutilizáveis: Cada funcionalidade principal foi encapsulada em componentes independentes

Injeção de dependências: Serviços injetados nos componentes conforme necessidade

Gestão de estado: Utilização de RxJS para fluxo de dados reativo

Armazenamento local: Persistência de dados no cliente via localStorage

Responsividade: Layout adaptável a diferentes tamanhos de tela

Melhorias Futuras
Implementar busca por nome/número

Adicionar gráficos de status comparativos

Desenvolver visualização da cadeia de evolução

Adicionar testes unitários e E2E

Implementar PWA (Progressive Web App)

Autor
Pedro Henrique Santos França    
i.m.pedrofranca@gmail.com
www.linkedin.com/in/pedro-frança-0b3857279

