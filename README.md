# 🚀 TecBlog

> Blog fictício de tecnologia desenvolvido para praticar HTML5 e CSS3.

[![Status](https://img.shields.io/badge/status-Educacional-blue)]()
[![Version](https://img.shields.io/badge/version-0.1.0-blue)]()
[![License](https://img.shields.io/badge/license-MIT-blue)]()

---

## 📋 Sobre o projeto

O **TecBlog** é um projeto educacional de desenvolvimento front-end, criado para praticar conceitos fundamentais de HTML5 e CSS3 durante o curso **Domine Web – 20 Cursos**, disponível na Udemy.

A página representa a interface de um blog de tecnologia, com cabeçalho, navegação por categorias, área principal de postagens, barra lateral e rodapé. O conteúdo atual é demonstrativo e utiliza textos fictícios e imagens locais.

### 🎯 Objetivos de aprendizagem

- Estruturar uma página com HTML5.
- Aplicar estilos utilizando uma folha CSS externa.
- Praticar seletores por ID e classe.
- Trabalhar com cores, tipografia, margens, espaçamentos e fundos.
- Criar menus e links com estados visuais para interação (`:link`, `:visited` e `:hover`).
- Organizar uma página em áreas de conteúdo principal e lateral.
- Referenciar corretamente recursos estáticos, como imagens e arquivos CSS.

### 🧩 Características da implementação

- **Tipo:** página estática, sem backend.
- **Marcação:** HTML5.
- **Estilos:** CSS3 em arquivo externo.
- **Layout:** posicionamento com `float` e largura fixa, conforme o objetivo didático original.
- **Conteúdo:** postagens e textos de exemplo.
- **Interatividade:** navegação por links; os links “Leia mais” e algumas categorias ainda utilizam `#` como destino demonstrativo.

> **Nota:** o projeto é uma base de estudo. Alguns links do menu apontam para páginas que não estão presentes na estrutura atual (`jogos.html`, `celulares.html`, `informatica.html` e `eletronicos.html`). O layout também utiliza largura fixa e não possui regras específicas de responsividade, portanto pode exigir ajustes em telas menores.

---

## 🖥️ Estrutura da página

| Área | Descrição |
|---|---|
| Cabeçalho e logotipo | Exibe a marca TecBlog e a navegação principal. |
| Menu | Apresenta links para Home e categorias de tecnologia. |
| Postagens | Exibe títulos, datas, imagens, textos e links “Leia mais”. |
| Barra lateral | Contém blocos de postagens recentes e categorias. |
| Rodapé | Exibe uma mensagem de direitos reservados. |

A implementação atual possui uma página HTML principal: `index.html`.

---

## 🛠️ Tecnologias utilizadas

- **HTML5** — estrutura e conteúdo da página.
- **CSS3** — cores, tipografia, espaçamento, layout e estados dos links.
- **Git** — controle de versão, caso esteja habilitado no repositório.

O projeto não utiliza frameworks JavaScript, bibliotecas externas, gerenciadores de pacotes ou ferramentas de compilação.

---

## 📁 Estrutura do projeto

```text
fe_tecblog/
├── index.html
├── css/
│   └── estilo.css
├── imagens/
│   ├── imagem1.jpg
│   ├── imagem2.jpg
│   ├── imagem3.jpg
│   ├── imagem4.jpg
│   └── imagem5.jpg
└── README.md
```

As imagens `imagem3.jpg`, `imagem4.jpg` e `imagem5.jpg` estão disponíveis no diretório, mas não são utilizadas na página inicial atual.

---

## ▶️ Como executar

Por ser uma página estática, não é necessário instalar dependências nem executar um servidor de aplicação.

1. Baixe ou clone o repositório.
2. Abra a pasta do projeto.
3. Abra `index.html` diretamente no navegador.

### Executar pelo Visual Studio Code

1. Abra a pasta `fe_tecblog` no VS Code.
2. Abra `index.html`.
3. Opcionalmente, utilize a extensão **Live Server** para servir a página localmente e atualizar o navegador durante as alterações.

Não são necessários comandos como `npm install` ou `npm run dev`.

---

## ✅ Checklist de validação

- [ ] `index.html` abre sem erros no navegador.
- [ ] O arquivo `css/estilo.css` é carregado corretamente.
- [ ] As imagens `imagem1.jpg` e `imagem2.jpg` aparecem nas postagens.
- [ ] O menu e os links exibem os estilos esperados ao passar o cursor.
- [ ] A área principal, a barra lateral e o rodapé estão posicionados corretamente.
- [ ] A página continua legível em diferentes larguras de janela.
- [ ] Os links que apontam para outras páginas foram verificados.

---

## ⚠️ Limitações conhecidas

- O conteúdo das postagens é fictício e contém texto de preenchimento.
- Os links “Leia mais” e os links das categorias com destino `#` não levam a artigos ou páginas específicas.
- Os links do menu para categorias referenciam arquivos HTML que não estão presentes no projeto atual.
- O layout utiliza larguras fixas e `float`, sem uma estratégia completa para dispositivos móveis.
- As imagens das postagens possuem `alt` vazio; caso sejam informativas, devem receber descrições textuais adequadas.
- A mensagem do rodapé não inclui ano nem identificação detalhada do responsável pelo conteúdo.

---

## 🗺️ Melhorias futuras

1. **Responsividade:** substituir larguras fixas por unidades flexíveis e adicionar media queries.
2. **Layout moderno:** migrar o posicionamento baseado em `float` para Flexbox ou CSS Grid.
3. **HTML semântico:** utilizar elementos como `header`, `nav`, `main`, `article`, `aside` e `footer`.
4. **Acessibilidade:** adicionar textos alternativos apropriados, revisar a hierarquia dos títulos e garantir foco visível na navegação por teclado.
5. **Conteúdo:** substituir textos demonstrativos por artigos reais e revisar datas, títulos e categorias.
6. **Navegação:** criar as páginas de categoria ou ajustar os links para destinos existentes.
7. **Manutenção:** remover estilos inline e manter as regras de apresentação concentradas no arquivo CSS.
8. **Evolução funcional:** se necessário, adicionar uma camada de dados ou backend para gerenciar artigos e categorias.

---

## 👤 Autor

**Diego Prates**

- GitHub: [@pratesddev](https://github.com/pratesddev)
- LinkedIn: [Diego Prates](https://linkedin.com/in/prates-diego)
- E-mail: [dmoprates1@gmail.com](mailto:dmoprates1@gmail.com)

---

<div align="center">

Desenvolvido por **Diego Prates** para fins educacionais.

</div>
