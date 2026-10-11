# War Tênis | E-commerce de Tênis e Sneakers

Landing page de e-commerce desenvolvida para a marca fictícia **War Tênis**, uma loja de tênis e sneakers online. O projeto foi construído com HTML e CSS puros, com foco em layout responsivo, organização de componentes e boas práticas de semântica e acessibilidade.

## Visão geral

A página apresenta:

- **Header** com logo, menu de navegação (categorias principais e secundárias) e menu hambúrguer responsivo para dispositivos móveis.
- **Seção Hero** com banner de destaque, chamada principal e botões de ação (ver modelos / comprar).
- **Seção de categorias** com cards para os estilos Casual, Esportivo, Moderno e Futurista.
- **Grid de produtos em destaque** com cards em diferentes tamanhos (top, meio e inferior).
- **Footer** com formulário de newsletter, redes sociais e links organizados por categoria (Masculino, Feminino, Outlet, Nossas lojas, Sobre).

## Estrutura de pastas

```
ecommerce-wartenis/
├── README.md
└── projeto-sapatos/
    ├── index.html                      # Página principal do site
    ├── css/
    │   ├── reset.css                   # Reset de estilos padrão do navegador
    │   ├── variables.css                # Variáveis globais (fontes, cores, etc.)
    │   ├── base.css                     # Estilos base aplicados ao documento
    │   └── components/
    │       ├── header.css               # Estilos do cabeçalho e navegação
    │       ├── hero.css                  # Estilos da seção hero/banner
    │       ├── product-category.css      # Estilos dos cards de categorias
    │       ├── product-grid.css          # Estilos do grid de produtos
    │       └── footer.css                # Estilos do rodapé
    └── images/
        ├── banners/                     # Imagens do banner hero (desktop/mobile)
        ├── favicons/                    # Ícones de favicon do site
        ├── icons/                       # Ícones de interface (menu, carrinho, redes sociais, etc.)
        ├── logo/                        # Logo da marca
        └── products/                    # Imagens dos produtos e categorias
```

## Tecnologias utilizadas

- **HTML5** — marcação semântica (`header`, `main`, `nav`, `section`, `footer`).
- **CSS3** — estilização modularizada por componente, com variáveis CSS e design responsivo (mobile first / media queries).
- **Google Fonts** — fonte `Ubuntu` utilizada em todo o projeto.

## Como executar o projeto

Como é um projeto estático (sem build ou dependências), basta abrir o arquivo diretamente no navegador:

1. Clone o repositório:
   ```bash
   git clone <url-do-repositorio>
   ```
2. Abra o arquivo `projeto-sapatos/index.html` no navegador de sua preferência.

Opcionalmente, para evitar problemas de carregamento de caminhos relativos, utilize uma extensão como o **Live Server** (VS Code) para servir o arquivo localmente.

## Responsividade

O layout foi desenvolvido com media queries para se adaptar a diferentes tamanhos de tela, incluindo:

- Menu hambúrguer no header para telas menores.
- Banner hero com imagem alternativa para mobile (`hero-mobile.jpg`).
- Reorganização dos cards de categorias, grid de produtos e colunas do footer em telas reduzidas.

## Status do projeto

Projeto em desenvolvimento. Os links de navegação, botões e formulário de newsletter estão presentes na interface, porém ainda sem integração funcional (front-end estático/protótipo visual).

## Autor

Desenvolvido por **Guilherme Ignácio**.
