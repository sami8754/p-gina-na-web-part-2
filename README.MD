# Literatura Clássica — Site Acessível

Projeto que apresenta o tema **Literatura Clássica** com **recursos de acessibilidade** (controle de fonte, alto contraste, ARIA) e **animações** com ScrollReveal.

## ✅ Tecnologias
- HTML5 + CSS3 + JavaScript
- Bootstrap 5 (CDN)
- Bootstrap Icons (CDN)
- ScrollReveal (CDN)
- Google Fonts (CDN)

## 📁 Estrutura de pastas
.
├── index.html  
├── styles.css  
├── script.js  
└── img/  
&ensp;&ensp;├── logo-literatura.png  
&ensp;&ensp;├── logo-literatura2.png  
&ensp;&ensp;├── fundo-biblioteca.jpg  
&ensp;&ensp;├── biblioteca-antiga.png  
&ensp;&ensp;├── autor-classico.png  
&ensp;&ensp;├── pluma.png  
&ensp;&ensp;├── pergaminho.png  
&ensp;&ensp;├── marcas-papel.png  
&ensp;&ensp;├── manuscrito-antigo.jpg  
&ensp;&ensp;├── busto-filosofo.jpg  
&ensp;&ensp;├── livros-antigos.jpg  
&ensp;&ensp;└── sala-leitura.jpg  

> Obs.: os nomes acima são os mesmos usados no HTML/CSS. Se mudar o nome de algum arquivo, ajuste as referências.

## 🚀 Como executar
1. Coloque **index.html**, **styles.css** e **script.js** na mesma pasta.
2. Crie a pasta **img/** e adicione as imagens listadas acima.
3. Abra **index.html** no navegador (clique duas vezes).
4. Se algo não aparecer, dê **Ctrl+F5** para limpar o cache.

## ♿ Recursos de acessibilidade
- **Menu de acessibilidade** (botão fixo):  
  - Aumentar fonte (A+)  
  - Diminuir fonte (A-)  
  - **Alto contraste** (troca esquema de cores)
- Atributos **ARIA** e **tabindex** nas seções principais.
- **Texto alternativo (alt)** em todas as imagens.
- **Contraste** reforçado no modo alto contraste (fundo/texto/links/botões).

## ✨ Efeitos
- **ScrollReveal** para revelar as seções `#inicio`, `#literatura`, `#galeria`, `#contato`.

## 🔗 Dependências via CDN (já incluídas no `index.html`)
- Bootstrap 5  
- Bootstrap Icons  
- Google Fonts (Montserrat, Lemon)  
- ScrollReveal

## 🧩 Dicas de solução de problemas
- **Página não abre**: certifique-se de abrir **index.html**, não o CSS/JS.
- **Imagens não aparecem**: verifique se a pasta **img/** existe e se os nomes dos arquivos batem com o código.
- **Fonte/ícones não carregam**: verifique a conexão com a internet (CDNs).
- **Mudanças não refletem**: atualize com **Ctrl+F5**.

## 📜 Licença
Uso educacional/didático.
