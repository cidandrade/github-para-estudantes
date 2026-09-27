# Guia de Trabalhos em Grupo com Github

Guia rápido para utilização do Github em trabalhos acadêmicos e escolares.

## Preparação

### Conta e instalação


- Todos os membros do grupo precisam de uma conta no Github. Convém que tenha uma foto profissional de perfil, um nome de usuário sério relacionado com o nome da pessoa e o nome completo.

- O ideal (embora não obrigatório) é ter o git instalado em cada computador. Ele pode ser obtido em [https://git-scm.com/](https://git-scm.com/)

- Quem for usar o git a partir do computador deve configurar nome e e-mail com
```
git config --global user.name "Seu Nome Completo"
git config --global user.email "seu-email@exemplo.com"
```

- Para configurar o Github (não chega a ser obrigatório), instale o gh (Veja o roteiro em [https://github.com/cli/cli](https://github.com/cli/cli)) e rode   
```
gh auth login
```

### Criação do repositório

Estas tarefas abaixo cabem somente ao administrador do repositório:

- Crie um novo repositório com um nome significativo, visibilidade pública, com README e uma licença adequada (na dúvida, opte pela "*MIT License*")

- Vá em *Settings* -\> *Collaborators* -\> *Add People* e adicione os membros do grupo. Cada colega receberá um convite por e-mail e deve aceitá-lo

- Vá em *Settings* \> *Rulesets* \> *Rulesets* \> *New ruleset* \> *New ruleset* -\> *New branch ruleset*. Dẽ um nome como "Proteção de main". Em *Enforcement Status*, marque como *Active*. Em *Target branches*, clique em *Add Target* e selecione *Include default branch*. Nas *Branch Rules*, marque *Require a pull request before merging* e clique no botão *Create.*

- A partir desta configuração, nem mesmo o administrador do repositório poderá fazer alterações diretamente nele.

- Envie o link do repositório para os colegas

### Trabalhando

Os alunos podem trabalhar em diferentes cenários a partir daqui.

- Em aplicativos com suporte ao Github, como o VS Code, com o plugin *Github Pull Requests*

- Em ambientes de codificação com suporte de IA, como o *Claude Code*

- Outros, podendo operar diretamente no Github

Em todos os casos é necessário clonar o repositório, criar uma nova *branch* com um nome descritivo, fazer o *commit* (com uma mensagem adequada), publicar a *branch* e fazer um *Pull Request.*

### Avaliando Pull Requests

O administrador do repositório deve ir até a página dele no Github e escolher a opção *Pull Requests*. Escolha cada PR disponível e aceitar as alterações em *Merge Pull Request* (ou recusar)
