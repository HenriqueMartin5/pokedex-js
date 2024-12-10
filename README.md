### README - Pokedex Project

---

## 📋 Sobre o Projeto

A **Pokedex** é um aplicativo web que utiliza a [PokéAPI](https://pokeapi.co/) para exibir uma lista de Pokémon, permitindo ao usuário explorar detalhes como tipos, nomes, números e imagens. Com uma interface simples e funcional, o usuário pode carregar mais Pokémon progressivamente por meio de um botão "Mostrar mais".

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação do conteúdo.
- **CSS3:** Estilização com foco em responsividade e usabilidade.
- **JavaScript (ES6+):** Manipulação dinâmica da interface e consumo da API.
- **PokéAPI:** Fonte de dados dos Pokémon.
- **Normalize.css:** Garantia de consistência no estilo entre navegadores.
- **Google Fonts:** Uso da fonte *Roboto* para melhorar a experiência visual.

---

## 🎯 Funcionalidades

1. **Listagem Progressiva de Pokémon:**
   - Os Pokémon são carregados dinamicamente em grupos de 10.
   - O botão "Mostrar mais" permite carregar mais Pokémon até um máximo de 151.

2. **Exibição Detalhada:**
   - Cada Pokémon é exibido com:
     - Nome.
     - Número.
     - Tipos (com cores representativas).
     - Imagem oficial (Dream World).

3. **Integração com a PokéAPI:**
   - Os dados são obtidos em tempo real via requisições HTTP para a PokéAPI.

---

## 📂 Estrutura do Projeto

```
pokedex/
│
├── index.html                # Página principal
├── assets/
│   ├── css/
│   │   ├── global.css        # Estilos globais
│   │   └── pokedex.css       # Estilos específicos da Pokedex
│   ├── js/
│   │   ├── main.js           # Lógica principal da aplicação
│   │   ├── poke-api.js       # Interação com a PokéAPI
│   │   └── pokemon-model.js  # Classe para modelar os dados do Pokémon
│
└── README.md                 # Documentação do projeto
```

---

## 🚀 Como Executar o Projeto

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seu-usuario/pokedex.git
   ```

2. **Navegue até o diretório do projeto:**

   ```bash
   cd pokedex
   ```

3. **Abra o arquivo `index.html` em um navegador.**

---

## 📦 Dependências

- **PokéAPI:** Nenhuma instalação necessária, pois a API é consumida via HTTP.
- **Normalize.css:** Incluído via CDN.
- **Google Fonts:** Incluído via CDN.

---

## 📝 Próximas Melhorias

1. Adicionar barra de pesquisa para encontrar Pokémon específicos.
2. Implementar paginação em vez de carregamento infinito.
3. Exibir mais informações do Pokémon, como habilidades e peso.
4. Melhorar a responsividade para dispositivos móveis.

---

## 🧑‍💻 Autor

**Henrique**  
- [LinkedIn](https://www.linkedin.com/in/henriquemartinsvasc)  

---

## 📜 Licença

Este projeto está licenciado sob a [MIT License](https://opensource.org/licenses/MIT). Sinta-se à vontade para usá-lo e modificá-lo. 😊
