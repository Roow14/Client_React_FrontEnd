# Projeto Rater , Streaming de Filmes 

Este projeto é um site de streaming de filmes desenvolvido utilizando as mais modernas tecnologias front-end para proporcionar uma experiência de usuário rica e dinâmica. O projeto é construído com **React** e **TypeScript**, o que garante uma aplicação escalável e com tipagem segura. A gestão do estado global é feita com **Zustand**, permitindo um gerenciamento de dados eficiente e reativo. Para a estilização dos componentes, são utilizados **styled-components**, que oferecem um sistema de estilos modular e reutilizável, mantendo o código CSS organizado e específico para cada componente.

### Funcionalidades Principais:

1. **Exibição de Filmes**: 
   - O site exibe uma variedade de filmes organizados em diferentes categorias, como lançamentos, recomendados e assistidos.
   - O layout inclui componentes como `SelectionContainer`, que destaca filmes em uma seção principal, e `Lancamento`, que mostra os últimos lançamentos em um carrossel interativo.

2. **Banners Dinâmicos**:
   - Banners grandes e pequenos são usados para destacar filmes específicos. Esses banners incluem títulos, descrições, avaliações, e botões para assistir ao trailer ou ao filme.
   - A exibição dos banners é responsiva e adaptada tanto para desktop quanto para dispositivos móveis.

3. **API Integration**:
   - O projeto consome dados de uma API pública de filmes (como o IMDB) para exibir tendências da semana, detalhes de filmes, e outras informações relevantes.
   - A aplicação utiliza paths específicos, como `/trending/all/week`, para buscar os filmes mais populares em determinado período.

4. **Componentes Customizados**:
   - Diversos componentes foram desenvolvidos para criar uma experiência única, como `SmallImageContainer` e `Lancamento`, que organizam filmes em layouts distintos.
   - Os componentes foram projetados para serem altamente reutilizáveis e facilmente ajustáveis conforme as necessidades do projeto.

5. **Design Responsivo**:
   - A aplicação é projetada para ser responsiva, garantindo uma experiência de usuário fluida em dispositivos móveis e desktops.
   - Os componentes de banner e outros elementos do layout têm dimensões e estilos específicos para diferentes tamanhos de tela.

6. **Banco de Dados**:
   - O projeto se conecta a um banco de dados MySQL para armazenar informações sobre filmes, incluindo nome, descrição, nota, e celebridades associadas.

### Tecnologias Utilizadas:

- **React** e **TypeScript**: Para a criação de componentes interativos e com tipagem estática.
- **Zustand**: Para gerenciamento de estado global da aplicação.
- **Styled-Components**: Para a estilização dos componentes de forma modular.
- **FontAwesome**: Para ícones estilizados e representativos.
- **MySQL**: Para armazenamento de dados relacionados aos filmes e usuários.

Este projeto representa uma solução completa e moderna para o streaming de filmes, com uma interface bem projetada, uma experiência de usuário fluida, e uma forte integração com APIs de filmes.
