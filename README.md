<!DOCTYPE html>
<html lang="pt-BR">
<body>
    <h1>📚 Projeto React - Aula 5 Módulo 5</h1>
    <p>Este projeto foi desenvolvido durante a aula 5 do Módulo 5, com o objetivo de aprender a consumir APIs e manipular dados em um aplicativo React. Utilizamos a API de "Bob's Burgers" para buscar, exibir e manipular informações sobre personagens da série.</p>
    <h2>🚀 Visão Geral</h2>
    <p>O projeto consiste em uma aplicação React que busca dados de personagens da série "Bob's Burgers" a partir de uma API, exibe esses dados em forma de cards e permite manipular a exibição através de botões.</p>
    <h2>📋 Funcionalidades</h2>
    <ul>
        <li>🔍 <strong>Buscar Personagens:</strong> Recupera uma lista de personagens da API e os armazena no estado da aplicação.</li>
        <li>👁️ <strong>Mostrar Personagens:</strong> Exibe no console os personagens que foram buscados.</li>
        <li>🗑️ <strong>Deletar Todos:</strong> Remove todos os personagens exibidos na tela.</li>
    </ul>
    <h2>🛠️ Tecnologias Utilizadas</h2>
    <ul>
        <li><a href="https://reactjs.org/">React</a> - Biblioteca JavaScript para construção de interfaces de usuário.</li>
        <li><a href="https://bobsburgers-api.herokuapp.com/">Bob's Burgers API</a> - API pública para acessar dados sobre os personagens da série Bob's Burgers.</li>
    </ul>
    <h2>📦 Estrutura do Projeto</h2>
    <pre>
        react-project/
        │
        ├── public/
        │   ├── index.html
        │   └── ...
        ├── src/
        │   ├── components/
        │   │   ├── Button/
        │   │   │   └── Button.jsx
        │   │   ├── Card/
        │   │   │   └── Card.jsx
        │   ├── screens/
        │   │   └── Home/
        │   │       ├── Home.jsx
        │   │       └── style.css
        │   ├── App.css
        │   ├── index.css
        │   └── main.jsx
        ├── package.json
        └── ...
    </pre>
    <h2>📦 Dependências</h2>
    <ul>
        <li><a href="https://reactjs.org/">React</a> - Biblioteca JavaScript para construção de interfaces de usuário.</li>
        <li><a href="https://vitejs.dev/">Vite</a> - Ferramenta de build rápida para projetos web modernos.</li>
    </ul>
    <h2>🔧 Como Executar o Projeto</h2>
    <p>Siga os passos abaixo para clonar e executar o projeto em seu ambiente local:</p>
    <ol>
        <li>Clone o repositório:
            <pre><code>git clone https://github.com/seu-usuario/react-project.git</code></pre>
        </li>
        <li>Navegue até a pasta do projeto:
            <pre><code>cd react-project</code></pre>
        </li>
        <li>Instale as dependências:
            <pre><code>npm install</code></pre>
        </li>
        <li>Inicie o servidor de desenvolvimento:
            <pre><code>npm run dev</code></pre>
        </li>
        <li>Acesse o projeto no navegador em <a href="http://localhost:3000" target="_blank">http://localhost:3000</a>.</li>
    </ol>
    <h2>📝 Licença</h2>
    <p>Este projeto está licenciado sob a Licença MIT. Para mais detalhes, consulte o arquivo <code>LICENSE</code>.</p>

</body>
</html>
