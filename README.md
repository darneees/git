#  Introdução ao Git 

Git é um sistema de controle de versão distribuído que permite aos
desenvolvedores rastrear alterações no código-fonte durante o desenvolvimento
de software. Ele facilita a colaboração entre equipes, mantém o histórico de
alterações e ajuda a gerenciar diferentes versões do código. Vamos explorar os
conceitos básicos do Git e entender como ele funciona. 📂�

---

### Instalando o GIT

1. Acesse o site oficial:

```
https://git-scm.com/
```

2. Baixe o instalador:

```
Windows, macOS e Linux.
```

3. Instale o Git:

```
Siga as instruções do instalador.
```

4. Verifique a instalação, abra o terminal ou prompt e execute o comando:

```
git --version
```

---

### Árvore de Diretórios

`Working Directory:` Onde você faz alterações nos
arquivos. É o estado atual do seu projeto no sistema de arquivos.

`Staging Area:`  Pense na staging area como um local onde você
pode revisar e organizar suas mudanças antes de fazer um commit.

`Repository:`  No repositório, todos os commits são armazenados
de maneira segura e eficiente.

![arvore-de-diretorios](https://github.com/user-attachments/assets/33451a64-2e74-4b96-93f4-e84a7709ce61)

---

### Comando básicos

Inicializa um resositorio
```
git init
```

Clonar um resositorio
```
git clone (url-do-respositório)
```

Verificar o estado de um respositorio
```
git status
```

Adicionar um arquivo para a area de staging
```
git add (nome-do-arquivo)
```

Adicionar todos os arquivos para a area de staging
```
git add .
```

Adicionar um commit (utilizado para descrever o que foi desenvolvido ou alterado)
```
git commit -m "mensagem-do-commit"
```

Verificar todo o historico de commits do repositório (hash do commit, branch, autor, data/hora e descrição do commit)
```
git log
```

Verificação limitada por 1 ou mais historicos (tratá apenas a quantidade que for passada no comando)
```
git log (exemplo: -1, -2, -3 ...)
```

Verificação da diferença entre o estado atual e o último commit
```
git diff
```

Cria uma nova branch(permiti trabalhar em diferentes linhas de desenvolvimento simultaneo)
```
git branch (nome-da-branch)
```

Lista as branchs existente
```
git branch
```

Mudar de branch (exemplo: main -> nova-branch / nova-branch -> main)
```
git checkout (nome-da-branch)
```

Combinar branchs distintas em uma única
```
git merge (nome-da-branch)
```

Alterar a mensagem de um commit
```
git commit --amend -m "nova-mensagem"
```