# AluraBooks 📚 - Versão Interativa

Uma evolução do projeto AluraBooks original, agora com funcionalidades interativas desenvolvidas em JavaScript. Esta segunda versão mantém o design refinado da primeira iteração e adiciona recursos dinâmicos como filtragem, ordenação e integração com API externa para criar uma experiência completa de catálogo de livros de tecnologia.

## 🔄 Evolução do Projeto

Este projeto representa a **segunda fase** do AluraBooks:

- **Primeira versão**: Foco no design e layout responsivo (HTML + CSS)
- **Segunda versão (atual)**: Adição de funcionalidades interativas com JavaScript

### Principais Melhorias da V2:
- Interface totalmente funcional com dados dinâmicos
- Consumo de API externa para catálogo real
- Sistema de filtros inteligente
- Cálculos automáticos de preços
- Reformulações visuais para melhor usabilidade

## 🚀 Funcionalidades Interativas

- **Catálogo dinâmico**: Carrega livros automaticamente via API
- **Filtros por categoria**: Front-end, Back-end e Dados
- **Filtro por disponibilidade**: Exibe apenas livros em estoque
- **Ordenação por preço**: Organiza livros do menor ao maior valor
- **Cálculo automático**: Soma total de livros disponíveis
- **Sistema de desconto**: Aplica 30% de desconto em todos os livros
- **Interface responsiva**: Design adaptável e moderno

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica da aplicação
- **CSS3**: Estilização com variáveis CSS e flexbox
- **JavaScript ES6+**: Lógica de negócio com métodos de array modernos
- **Google Fonts**: Tipografia Poppins
- **API Externa**: Integração com endpoint de livros

## 📁 Estrutura do Projeto

```
alurabooks/
├── index.html
├── style.css
├── imagens/
│   ├── Logo-1.png
│   ├── Banner-1.png
│   └── [capas dos livros]
└── app/
    ├── main.js
    ├── metodoForEach.js
    ├── metodoMap.js
    ├── metodoFilter.js
    ├── metodoSort.js
    └── metodoReduce.js
```

## 🎯 Funcionalidades Técnicas

### Métodos JavaScript Utilizados

- **forEach()**: Renderização dinâmica dos livros na tela
- **map()**: Aplicação de desconto nos preços
- **filter()**: Filtragem por categoria e disponibilidade
- **sort()**: Ordenação por preço
- **reduce()**: Cálculo do valor total dos livros

### Principais Funções

```javascript
// Busca livros da API
getBuscarLivrosDaAPI()

// Aplica desconto de 30%
aplicarDesconto(livros)

// Filtra por categoria
filtrarPorCategoria(categoria)

// Calcula valor total
calcularValorTotalDeLivrosDisponiveis(livros)
```

## 🎨 Design

- **Paleta de cores**: Tons de azul (#326589, #002f52) e laranja (#fc6621)
- **Tipografia**: Poppins (Google Fonts)
- **Layout**: Flexbox para disposição responsiva
- **Estados visuais**: Livros indisponíveis com opacidade reduzida

## 🚀 Como Executar

1. Clone o repositório:
```bash
git clone [seu-repositorio]
```

2. Abra o arquivo `index.html` em um navegador web

3. A aplicação carregará automaticamente os livros da API

## 📱 Funcionalidades da Interface

- **Filtros disponíveis**:
  - Livros de Front-end
  - Livros de Back-end
  - Livros de Dados
  - Livros Disponíveis
  - Ordenar por Preço

- **Informações exibidas**:
  - Capa do livro
  - Título
  - Autor
  - Preço (com desconto aplicado)
  - Categoria
  - Status de disponibilidade

## 🔧 API Utilizada

A aplicação consome dados da API:
```
https://guilhermeonrails.github.io/casadocodigo/livros.json
```

## 🎓 Conceitos Aprendidos

Este projeto demonstra a evolução de uma página estática para uma aplicação interativa:

### Primeira versão (Design):
- Estruturação HTML semântica
- Estilização avançada com CSS
- Layout responsivo com Flexbox
- Variáveis CSS (Custom Properties)

### Segunda versão (Funcionalidades):
- Manipulação avançada do DOM
- Consumo de APIs com fetch() e async/await
- Programação funcional com métodos de array
- Event listeners e manipulação de eventos
- Gerenciamento de estado da aplicação

## 🤝 Contribuição

Sinta-se à vontade para contribuir com melhorias:
1. Faça um fork do projeto
2. Crie uma branch para sua feature
3. Commit suas mudanças
4. Push para a branch
5. Abra um Pull Request

## 📝 Licença

Este projeto foi desenvolvido para fins educacionais durante o curso da Alura.

---

**Desenvolvido por Mauricio Grass de Bronstein**

**Projeto desenvolvido em duas etapas:**
1. **Primeira fase**: Desenvolvimento do design e layout (HTML + CSS)
2. **Segunda fase**: Implementação de funcionalidades interativas (JavaScript + API)

*Parte do curso "JavaScript: métodos de array" da Alura* 🎯
