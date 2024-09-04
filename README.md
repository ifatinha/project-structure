
# Estrutura do Projeto

Este documento descreve a estrutura de pastas e arquivos do projeto, organizando recursos e estilos para facilitar o desenvolvimento e a manutenção.

## Estrutura de Pastas

```
project-structure/
├── assets/
│   ├── config/
│   ├── css/
│   ├── images/
│   ├── js/
│   └── sass/
│       ├── base/
│       ├── components/
│       ├── global/
│       ├── layouts/
│       ├── modules/
│       ├── pages/
│       └── util/
├── index.html
├── package.json
└── README.md

```

### Descrição das Pastas

- **assets/**: Contém todos os recursos estáticos do projeto.
  - **config**: Contém um arquivo que define as configurações para a execução correta do projeto.
  - **css/**: Armazena os arquivos CSS compilados a partir do SCSS.
  - **images/**: Contém as imagens utilizadas no projeto.
  - **js/**: Armazena os arquivos JavaScript do projeto.
  - **sass/**: Contém os arquivos SCSS organizados de forma modular.
    - **base/**: Contém configurações globais e utilitários base para o projeto.
    - **components/**: Contém os estilos específicos para componentes individuais do projeto.
    - **global/**: Contém estilos globais aplicáveis a todo o projeto.
    - **layouts/**: Armazena os estilos referentes ao layout geral do projeto.
    - **modules/**: Contém módulos SCSS reutilizáveis em diferentes partes do projeto.
    - **pages/**: Estilos específicos para páginas individuais.
    - **util/**: Contém funções e mixins utilitários.
  - **main.scss**: Arquivo SCSS principal que importa todos os outros arquivos SCSS do projeto.

- **index.html**: O arquivo HTML principal do projeto.

- **package.json**: Arquivo de configuração do Node.js que define as dependências e scripts do projeto.

- **README.md**: Documento explicativo sobre o projeto, incluindo informações de instalação, uso e contribuição.

## Como Utilizar

1. Organize seus arquivos SCSS dentro da pasta `sass/` conforme a estrutura acima.
2. Compile o SCSS para gerar os arquivos CSS na pasta `css/`.
3. Certifique-se de que os caminhos para as imagens, CSS e JS estão corretos no `index.html`.
4. Utilize o `package.json` para gerenciar as dependências e automações do projeto.

## Contribuição

Contribuições são bem-vindas! Por favor, siga as diretrizes de estrutura e mantenha a organização dos arquivos conforme descrito.

Sinta-se à vontade para ajustar ou adicionar mais detalhes conforme necessário para seu projeto!
