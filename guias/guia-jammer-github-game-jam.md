---
share_link: https://share.note.sx/995jo8am#lQvNpv8qzfYUtplWTtXuQbiACaWiduYMCKkgvqFwDfQ
share_updated: 2026-03-25T10:00:51-03:00
---

> [!espero que esse guiazinho ajude <3]
> Qualquer dúvida, pode falar comigo no insta ou discord @ashcrysis

## 1. Por que usar GitHub?

O GitHub permite versionar seu projeto, evitar perda de arquivos e trabalhar em equipe sem sobrescrever o trabalho dos outros.

---
## 2. Instalar o Git (Windows)

Baixe e instale o Git pelo link oficial:

- Git for Windows  
    [https://git-scm.com/download/win](https://git-scm.com/download/win)

Durante a instalação, pode deixar tudo no padrão.

---
## 3. Criando um repositório local

1. Abra a pasta do seu projeto
    
2. Clique com botão direito → abrir com Git Bash
    
3. Rode:

> [!TERMINAL]
> git init .
> 

Isso serve pra transformar a pasta atual do projeto em um repositório Git, evitando que o GitHub Desktop crie outra pasta separada.

---
## 4. Baixe o Github Desktop
https://desktop.github.com/download/

1. Após instalar, vá na opção "Adicionar repositório existente"  
2. Adicione a pasta do projeto (onde você rodou `git init .`)  
3. Clique em **"Publish repository"**  
4. Isso vai:  
	- Criar o repositório remoto no github
	- Conectar automaticamente ao remoto  
	- Enviar o projeto (primeiro push)

---
## 5. .gitignore (IMPORTANTE)

Crie um arquivo chamado .gitignore na raiz do projeto.

Use como base (exemplo focado em Unity):

- [.gitignore](https://drive.google.com/file/d/1BP8APEWc0o6wNAC6uavGVdyhb_nRwvX3/view?usp=sharing)

Isso evita subir arquivos desnecessários e pesados.

---
## 6. Dicas para Game Jams

- Evite commitar arquivos gigantes
    
- Combine regras com o time (quem mexe em quê)
  
- Trabalhem em cenas separadas, se possível branchs separadas, e depois juntem tudo
    
- Faça push com frequência, mas faça pushs detalhados com uma mensagem que faça sentido
    
- Se algo quebrar, dá pra voltar versões anteriores
  
- Lembrar que é preciso adicionar quem vai poder colaborar com o projeto no site do GitHub, nas configurações do projeto você convida seu parceire de equipe em "Colaborators" :D
  
  Documentações que podem ser uteis:
-  https://git-scm.com/docs 
-  https://docs.github.com/en/desktop
- https://docs.unity.com/en-us
- https://docs.godotengine.org/en/stable/