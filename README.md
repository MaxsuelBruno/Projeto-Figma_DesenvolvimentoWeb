# LiricPlay ♫

> Implementação do protótipo do Figma — Projeto Final (Desenvolvimento Web I)

---

## Descrição
LiricPlay é uma adaptação de um protótipo criado no Figma. O projeto contém páginas em HTML e CSS (sem JavaScript) que exibem letras de músicas com cards, página de detalhes e formulário de contato. A estrutura segue o protótipo e a paleta definida no Figma.

---

## Objetivo do Projeto
Colocar em prática os conceitos aprendidos na disciplina **Desenvolvimento Web I**.  
Criar um site completo em **HTML** e **CSS**, respeitando design, paleta de cores e estrutura do protótipo do Figma.  
Entrega: publicação no **GitHub Pages** com link do repositório e README.

---

## Requisitos (resumido)
- Apenas **HTML** e **CSS** (sem JavaScript).
- Três páginas principais: `index.html`, `detalhes.html`, `contato.html`.
- Cabeçalho (`header`) e rodapé (`footer`) compartilhados entre páginas.
- Página inicial com **cards** (imagem, título, descrição).
- Página de detalhes com imagem principal, título, descrição e informações adicionais.
- Página de contato com formulário (nome, e-mail, assunto, mensagem).
- Arquivo CSS externo (`css/style.css`).
- Responsividade básica com **Flexbox**.

---

## Estrutura de pastas (modelo)
```
projeto_final/
├── index.html
├── contato.html
├── msc/
│   ├── musica1.html
│   ├── musica2.html
│   ├── musica3.html
│   └── musica4.html
├── css/
│   └── style.css
├── img/                    # imagens usadas no site (prints do Figma, capas, thumbnails)
│   ├── prototype_home.png
│   ├── prototype_detalhes.png
│   ├── prototype_contato.png
│   └── (outras imagens...)
├── README.md               # documento explicativo (este arquivo)
```
---

## Conteúdo dos arquivos (breve)
- **index.html** — Página inicial com cards dos itens (músicas). (Ex.: `index.html`).  
- **msc/** — Pasta exibindo páginas de músicas (detalhes).  
- **contato.html** — Formulário de contato com `label` associado aos campos. (Ex.: `contato.html`).  
- **css/style.css** — Estilos compartilhados entre as páginas.  

---


### Protótipo (Figma)
![Figma - Página Inicial](img/inicio_figma.png)
![Figma - Página de Contato](img/contato_figma.png)
![Figma - Página de Detalhes (Exemplo)](img/detalhes_figma.png)

### Implementação (HTML/CSS)
![Site - Página Inicial](img/inicio_projeto.png)
![Site - Página de Contato](img/contato_projeto.png)
![Site - Página de Detalhes (Exemplo)](img/detalhes_projeto.png)


## 🎨 Semelhanças e Diferenças entre o Protótipo (Figma) e o Site Final (HTML/CSS)

### ✅ Semelhanças
- Estrutura principal das páginas foi mantida (header, conteúdo e footer).
- Os cards da página inicial seguem o mesmo formato previsto no protótipo.
- As páginas possuem navegação igual ao layout do Figma.
- O posicionamento dos elementos respeita o que foi planejado no design inicial.
- O conteúdo segue o mesmo padrão do design no Figma.

### ⚠️ Diferenças
- A paleta de cores muda o padrão definido no Figma.
- Algumas imagens precisaram ser ajustadas para tamanhos mais adequados ao layout final.
- Diferenças de espaçamento/margens devido à adaptação prática no CSS.
- Tipografia pode variar conforme a fonte disponível no navegador.
- Alguns elementos foram simplificados para manter o site mais responsivo.
- No Figma havia efeitos mais visuais (sombras, gradientes, etc.) que foram adaptados para CSS puro.
