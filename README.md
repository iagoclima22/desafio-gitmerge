# Desafio: Merge com Conflito
 
Projeto do curso **Git e GitHub Expert** (DevSuperior) para praticar branches, pull requests e resolução de conflitos de merge.
 
## Sobre
 
Um pequeno website estático (HTML) usado como base para o fluxo de trabalho com Git. O foco não é o site em si, mas o versionamento.
 
## Páginas
 
- `index.html` — página inicial com links de navegação
- `catalogo.html` — página de catálogo
- `sobre.html` — página "Sobre nós"
- `blog.html` — página de blog
## Fluxo de branches
 
- `main` — branch principal
- `ft-sobre` — adiciona a página "Sobre", integrada à `main` via pull request
- `ft-blog` — adiciona a página "Blog"; ao trazer as mudanças da `main`, ocorre um **conflito no `index.html`** que é resolvido manualmente antes do merge final
## O que foi praticado
 
- Criação de branches a partir de um mesmo commit
- Pull requests com commit de merge
- Sincronização do repositório local com `git pull origin main`
- Identificação e **resolução de conflito de merge** mantendo as últimas alterações nos links
