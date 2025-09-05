# O que é Git e GitHub?

## Git

Git é como um controle de histórico para o código. Ele ajuda a manter um registro de todas as mudanças feitas, permitindo que você volte a qualquer versão anterior do seu projeto quando necessário. Isso permite que várias pessoas trabalhem no mesmo projeto ao mesmo tempo, sem um atrapalhar no projeto do outro.

### Principais conceitos:

- **Commit:** Registra suas alterações no repositório.
- **Branch:** Cria uma "ramificação" para trabalhar em novas ideias sem afetar o projeto principal.
- **Merge:** Junta as alterações feitas em diferentes branches.

## GitHub

GitHub é como o "Google Drive" do código. Ele usa o Git para armazenar seus projetos online e, além disso, oferece uma maneira super prática de colaborar com outros desenvolvedores. É onde você compartilha seu código por meio dos repositórios, pede revisões e até automatizar algumas tarefas do projeto.

### Principais funcionalidades:

- **Pull Requests (PR):** Quando você termina uma tarefa e quer que outra pessoa revise e aprove antes de integrar ao código principal.
- **Issues:** Para rastrear bugs, ideias ou tarefas a serem feitas.
- **Actions:** Automatiza processos, como rodar testes sempre que alguém faz uma mudança no código.

**Resumindo:** Git é a ferramenta que mantém o controle das versões do seu código, e o GitHub é onde você armazena, compartilha e colabora com a equipe de forma prática e organizada.

---

## Como configurar o Git no seu PC

### 1. Instalar o Git

Faça o download da versão mais recente do Git e siga o processo de instalação.

### 2. Verificar a instalação

Após instalar, abra o terminal e digite o seguinte comando:

```bash
git --version
```

Se aparecer a versão do Git, significa que a instalação foi bem-sucedida. ✅

### 3. Configurar suas credenciais do Github

Dentro do terminal da sua IDE (vscode, cursor) você faz a seguinte configuração:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@dominio.com"
```

Depois disso seu git tá configurado, só começar a fazer seu projeto, iniciar o repositório, enviar os commits e tudo mais (vou ensinar no próximo).

### Links Úteis

- [Documentação Oficial do Git (em português)](https://git-scm.com/doc)

---

## Guia Rápido: Como "Comitar" no GitHub

### Passo 1: Verifique o Status das Suas Alterações

Depois de modificar seus arquivos, o primeiro passo é verificar o que foi alterado. Use o comando:

```bash
git status
```

- **Arquivos em vermelho:** Foram modificados, mas ainda não estão preparados para o commit (não estão no "stage").
- **Arquivos em verde:** Já estão no "stage" e prontos para serem commitados.

### Passo 2: Adicione os Arquivos ao "Stage"

Para incluir os arquivos que você deseja no próximo commit, utilize o comando `git add`.

Para adicionar um arquivo específico:

```bash
git add <nome_do_arquivo>
```

Para adicionar TODOS os arquivos modificados de uma vez:

```bash
git add .
```

### Passo 3: Faça o Commit das Alterações

Agora, registre as alterações adicionadas com uma mensagem.

```bash
git commit -m "feat(login): adiciona validação de senha"
```

## Boas Práticas para Mensagens de Commit

É sempre bom seguir um padrão para manter o histórico do projeto claro e organizado.

### Principais tipos:

- **feat:** Para novas funcionalidades.
- **fix:** Para correção de bugs.
- **docs:** Para alterações na documentação.
- **style:** Para formatação de código, sem alteração de lógica.
- **refactor:** Para melhorias internas que não alteram o comportamento.
- **chore:** Para tarefas de build, pacotes, etc.

**Exemplos de commits:** [Conventional Commits](https://www.conventionalcommits.org/).

### Passo 4: Envie as Alterações para o GitHub

Depois, só enviar seus commits para o repositório remoto (GitHub) com o comando `git push`.

```bash
git push origin <nome-da-branch>
```

Substitua `<nome-da-branch>` pelo nome da branch em que você está trabalhando (ex: `feature/nova-tela` ou `main`).

---

## Dicas de Boas Práticas

Evite enviar alterações diretamente para a branch `main` ou `master`. Crie sempre uma branch nova para cada funcionalidade ou correção.

Para criar e já mudar para uma nova branch, use:

```bash
git checkout -b <nome-da-sua-branch>
```
