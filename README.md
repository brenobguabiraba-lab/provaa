Landing Page Pessoal

Este projeto consiste em uma landing page pessoal responsiva, desenvolvida com HTML, CSS e Bootstrap. O objetivo é apresentar um perfil profissional ou pessoal de forma moderna e acessível em diferentes dispositivos.

Funcionalidades

•
Design Responsivo: Utiliza Bootstrap para garantir que a página se adapte a qualquer tamanho de tela.

•
Estrutura Clara: Dividida em seções como Cabeçalho, Sobre Mim, Serviços/Portfólio e Contato.

•
Formulário de Contato: Inclui um formulário simples para facilitar a comunicação.

•
Estilização Personalizada: CSS customizado para um visual único e moderno, incluindo animações.

•
Interatividade: JavaScript para scroll suave, destaque de navegação e validação básica de formulário.

Estrutura do Projeto

Plain Text


personal-landing-page/
├── .devcontainer/         # Configurações do GitHub Codespaces
│   └── devcontainer.json
├── index.html             # Estrutura principal da landing page
├── style.css              # Estilos personalizados e animações
├── script.js              # Lógica JavaScript para interatividade
└── README.md              # Este arquivo


Como Executar (Localmente)

1.
Clone o repositório:

2.
Abra o index.html:
Você pode simplesmente abrir o arquivo index.html em seu navegador web preferido.

Como Executar (GitHub Codespaces)

1.
Abra o projeto no Codespaces:
No GitHub, navegue até o repositório e clique em Code, depois selecione a opção Codespaces e crie um novo codespace.

2.
O Codespace será inicializado:
O ambiente será configurado automaticamente com as extensões e ferramentas definidas no .devcontainer/devcontainer.json.

3.
Visualize a página:
Dentro do Codespace, você pode usar a extensão Live Server (já configurada no .devcontainer) para visualizar a página. Abra o index.html, clique com o botão direito e selecione Open with Live Server.

Personalização

•
index.html: Edite o conteúdo textual, adicione suas informações, links e imagens.

•
style.css: Modifique cores, fontes e outros estilos para refletir sua marca pessoal.

•
devcontainer.json: Adicione ou remova extensões do VS Code conforme suas necessidades de desenvolvimento.

Publicação (Azure Static Web Apps)

Este projeto está configurado para ser publicado automaticamente no Azure Static Web Apps. O arquivo de configuração .github/workflows/azure-static-web-apps-<ID_UNICO>.yml (a ser criado) orquestrará o processo de build e deploy a cada push para a branch principal (main).




Autor: [Seu Nome/Usuário do GitHub]

