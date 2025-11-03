# 🚀 Atividade Prática: Aula 15 - Git e GitHub

**Disciplina:** Arquitetura Web (TADS/Ciência da Computação - UFRR)
**Professor:** Jean Bertrand

## 🎯 Objetivo

Bem-vindo(a) ao seu primeiro fluxo de colaboração profissional!

O objetivo desta atividade é simular como equipes de desenvolvimento usam o Git e o GitHub no dia a dia. Você **não** vai editar este projeto diretamente. Em vez disso, você vai:

1.  Criar uma cópia (Fork) deste projeto para sua própria conta.
2.  Clonar o projeto para sua máquina local.
3.  Criar uma "branch" (rascunho) segura para fazer sua alteração.
4.  Fazer sua "contribuição" (adicionar um arquivo).
5.  Enviar seu rascunho de volta para o *seu* GitHub (Push).
6.  Pedir para que sua contribuição seja incluída no projeto oficial da turma (Abrir um Pull Request).

## 🧑‍💻 Seu Desafio: Passo a Passo

Siga exatamente estas etapas. Os comandos devem ser executados no seu terminal (Git Bash, Terminal, etc.).

### 1. Fork: Crie sua cópia

No canto superior direito desta página, clique no botão **"Fork"**. O GitHub irá criar uma cópia exata deste repositório *na sua conta pessoal*.

### 2. Clone: Traga o projeto para seu PC

Agora, vá para o repositório que *você acabou de "forkar"* (ele estará na sua conta). Clique no botão verde **"<> Code"**, copie a URL (HTTPS ou SSH) e clone o projeto na sua máquina:

```bash
# Substitua a URL pela URL do SEU fork!
git clone [https://github.com/SEU-USUARIO/ufrr-arq-web-aula15-git.git](https://github.com/SEU-USUARIO/ufrr-arq-web-aula15-git.git)
```

### 3. Branch: Crie seu "Rascunho"

Entre na pasta do projeto e crie uma nova *branch* para trabalhar. Isso protege a `main` de mudanças acidentais.

```bash
# Entra na pasta
cd ufrr-arq-web-aula15-git

# Cria e já muda para a nova branch
# (Use o prefixo 'aluno/' seguido do seu nome ou usuário)
git checkout -b aluno/seu-nome-de-usuario
```

### 4. Contribua: Adicione seu arquivo

Crie um novo arquivo de texto simples. Por uma convenção do GitHub, vamos usar a extensão `.md` (Markdown).

* **Nome do arquivo:** `SEU-NOME-DE-USUARIO.md` (ex: `jean-bertrand.md`)
* **Conteúdo:** Escreva uma breve biografia sua. Por exemplo:

```md
# Jean Bertrand
**Curso:** Ciência da Computação
**Interesses:** IA, Jogos e Arquitetura de Software.
**Trabalho:** Analista de Sistemas na AMATUR.
```

### 5. Commit: Salve seu "Checkpoint"

Agora, adicione e "commite" sua mudança. Lembre-se da aula: `add` para o "carrinho" e `commit` para "pagar".

```bash
# Adiciona TODOS os arquivos novos/modificados ao carrinho (Staging Area)
git add .

# Cria o checkpoint (Commit) com uma mensagem clara
git commit -m "Feat: Adiciona biografia de [Seu Nome]"
```

### 6. Push: Envie para o SEU GitHub

Envie sua *branch* (seu rascunho) para o *seu* repositório remoto (seu fork) no GitHub.

```bash
# O 'origin' aqui é o SEU fork, não o do professor
git push origin aluno/seu-nome-de-usuario
```

### 7. Pull Request (PR): Peça para Juntar

Essa é a parte mágica!

1.  Volte para a página do **SEU fork** no GitHub.
2.  O GitHub provavelmente mostrará um aviso amarelo: *"Sua branch `aluno/seu-nome-de-usuario` está à frente..."*.
3.  Clique no botão verde **"Compare & pull request"**.
4.  Na tela seguinte, certifique-se de que o *repositório base* (o do professor) está à esquerda e o *seu fork* está à direita.
5.  Adicione um título (ex: "Adiciona biografia do Jean Bertrand") e uma breve descrição.
6.  Clique em **"Create pull request"**.

**Parabéns!** Você acabou de solicitar que sua mudança seja incluída no projeto oficial da turma.

---
