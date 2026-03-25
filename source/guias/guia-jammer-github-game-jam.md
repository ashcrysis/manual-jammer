---
share_link: https://share.note.sx/995jo8am#lQvNpv8qzfYUtplWTtXuQbiACaWiduYMCKkgvqFwDfQ
share_updated: 2026-03-25T10:00:51-03:00
---

> [!espero que esse guiazinho ajude <3]
> Qualquer dúvida, pode falar comigo no insta ou discord @ashcrysis

## 1. Por que usar GitHub?

O GitHub permite versionar seu projeto, evitar perda de arquivos e trabalhar em equipe sem sobrescrever o trabalho dos outros.
Saiba mais sobre versionamento em: [Versionamento Semântico](https://semver.org/lang/pt-BR/)

---
## 2. Instale o Git (Windows)

Baixe e instale o Git pelo link oficial:

- Git for Windows  
    [https://git-scm.com/download/win](https://git-scm.com/download/win)

Durante a instalação, pode deixar tudo no padrão.

---

## 4. Baixe o Github Desktop
[https://desktop.github.com/download/](https://desktop.github.com/download/)

---

## 5. Crie o repositório
1. Abra o Github Desktop
2. Em File, clique em "Add Local Repository" ou aperte CTRL + O, e busque pela pasta do seu projeto.
3. Vai aparecer um erro como "O diretório parece não estar num repositório Git. Você gostaria de criar um repositório aqui?", e clique no link para criar.
4. Isso abrirá um popup, todas as opções você pode deixar como padrão, porém, é recomendado que todo repositório tenha um .gitignore (falamos mais sobre num passo adiante) e por esta tela você já consegue criar um template.

---

## 5. Adicione o .gitignore (IMPORTANTE)
Crie um arquivo chamado .gitignore na raiz do projeto.
**(Atenção: é .gitignore mesmo, não .gitignore.txt)**

Use como base (exemplo focado em Unity):
- [.gitignore](https://drive.google.com/file/d/1BP8APEWc0o6wNAC6uavGVdyhb_nRwvX3/view?usp=sharing)

Isso evita subir arquivos desnecessários e pesados.

Outros templates podem ser encontrados [aqui](https://www.toptal.com/developers/gitignore)

---

## 6. Publique o repositório
3. Clique em **"Publish repository"**
4. Nesta etapa, ele pode pedir por sua conta no Github. Se ocorrer, logue.
5. Depois, um popup vai aparecer onde você pode escolher se o repositório será público ou não. Depois de tudo pronto, clique em "Publish repository" novamente.
7. Isso vai:  
	- Criar o repositório remoto no github
	- Conectar automaticamente ao remoto  
	- Enviar o projeto (primeiro push)

---

## 6. Dicas para Game Jams

- Evite commitar arquivos gigantes

- Combine regras com o time (quem mexe em quê)

- Trabalhem em cenas separadas, se possível branchs separadas, e depois juntem tudo

- Faça push com frequência e com commits detalhados: escreva uma mensagem que faça sentido. Saiba mais em: [Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0/)

- Se algo quebrar, dá pra voltar versões anteriores

- Lembrar que é preciso adicionar quem vai poder colaborar com o projeto no site do GitHub, nas configurações do projeto você convida seu parceire de equipe em "Colaborators" :D
  
### Documentações e outros links que podem ser uteis:
- https://git-scm.com/docs 
- https://docs.github.com/en/desktop
- https://docs.unity.com/en-us
- https://docs.godotengine.org/en/stable/
- https://semver.org/lang/pt-BR/
- https://www.toptal.com/developers/gitignore
- https://www.conventionalcommits.org/pt-br/v1.0.0/
