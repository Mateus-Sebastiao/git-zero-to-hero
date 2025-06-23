# Flask Hello World

Este é um projeto simples de aplicação web com **Flask**, criado para praticar conceitos de versionamento com **Git**, incluindo uso de **branches**, **commits**, **pull requests** e boas práticas de colaboração.

## Objectivo

Aprender sobre como trabalhar com **repositórios, branches, tags, commits, merge, pull requests local e remotamente**.

## Git Commands Essentials

### Creating repository:
```bash	
git init
```

## Check file status:
```bash	
git status
```

## Git staging:
```bash	
git add <file>
git add --all
```

## Unstaging files:
```bash
git restore --staged <file>
```

## Git Commit:
```bash
git commit -m "<message>"
git commit -a -m "<message>"
```

## View commit history:
```bash
git log [options]
```

## Viewing history:
```bash
git log
git log --oneline
git show <commit>
git diff
git diff --staged
```

## Git branch:
```bash
git branch
git branch <branch_name>
git branch -d <branch_name>
git branch -D <branch_name>
git branch -m <old_branch_name> <new_branch_name>
git checkout <branch_name> or git switch <branch_name>
git checkout -b <branch_name>
```

## Git merge:
```bash
git merge <branch_for_merging>
git merge --no-off <branch_for_merging>
git merge --squash >branch_for_merging>
git merge --abort
```

## Tecnologias

- Git 2.34.1+
- Python 3.10.12+
- Flask

## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/Mateus-Sebastiao/git-zero-to-hero
cd git-zero-to-hero
```

2. Crie e ative um ambiente virtual (opcional, mas recomendado):

```bash
python -m venv venv
source venv/bin/activate
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Rode a app:

```bash
python app.py
```

Acesse: http://localhost:5000

## O que aprendi...

- Trabalhar com repositório local e remoto
- Organizar o trabalho em branches
- Trabalhar em equipe com branches remotamente
- Mesclar branches e trabalhar com Pull Requests
- Lidar com conflitos
- Maneiras de trabalhar com Git.

## O que farei...

Vou aplicar cada conceito nos meus próximos projetos e tornar tudo mais profissional.

***

Desenvolvido por: **Mateus Sebastião**
