# Projeto_Biblioteca_Nacional
Um sistema web para gestão de bibliotecas pessoais ou institucionais. Seu nome faz referência a Biblioteca Nacional do Rio de Janeiro, a maior do Brasil e uma das maiores e principais do mundo, remontando ao perído do Brasil Império.

biblioteca-online/ 
│
├── config/
│   ├── database.php          # Configuração de conexão com MySQL
│   └── config.php            # Configurações gerais
│
|── db/                       # querries SQL
|
├── public/                   # Arquivos públicos
│   ├── index.php             # Ponto de entrada
│   ├── styles/               # Estilos CSS
│   ├── js/                   # Scripts JavaScript
│   └── images/               # Imagens e capas de livros
│
├── includes/                 # Arquivos PHP incluídos
│   ├── header.php
│   ├── footer.php
│   ├── sidebar.php
│   └── functions.php         # Funções utilitárias
│
├── classes/                  # Classes PHP (abordagem OO)
│   ├── Usuario.php
│   ├── Livro.php
│   ├── Emprestimo.php
│   └── Database.php
│
├── api/                      # Endpoints da API
│   ├── livros.php
│   ├── usuarios.php
│   └── emprestimos.php
│
└── admin/                    # Área administrativa
    ├── index.php
    ├── livros.php
    └── usuarios.php