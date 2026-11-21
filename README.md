# Shirley — Beleza Brasil e China

Landing page **mobile-first** para apresentação e venda de cosméticos do Brasil e da China, optimizada para telemóveis e sem dependências externas.

## Funcionalidades
- Navegação simplificada e barra inferior fixa para telemóveis.
- Catálogo de 13 artigos identificados a partir das imagens fornecidas: Corpo, Rosto, Lábios e Kits.
- Filtros por categoria e cartões de produtos.
- Carrinho interactivo, com alteração de quantidades e subtotal.
- Encomenda preparada para envio por WhatsApp.
- Disposição adaptável para telemóveis, tablets e computadores.

## Executar
Abra o ficheiro `index.html` num navegador. Não necessita de instalação, compilação ou servidor de aplicações.

## Personalizar antes de publicar
1. A marca da loja é **Beleza Brasil e China**. Pode alterá-la no código, caso seja necessário.
2. Configure o número WhatsApp da loja com indicativo internacional.
3. Actualize os preços provisórios em meticais no array `products` do `index.html` (campo `price` de cada produto).
4. Confirme os rótulos, a autenticidade, as variantes, a disponibilidade e as políticas de entrega, pagamento, trocas e devoluções. As imagens de catálogo foram recriadas com IA a partir das referências visuais; podem diferir das embalagens físicas.

O botão **Personalizar loja** altera apenas os dados guardados no navegador onde a demonstração está aberta (localStorage). **Não configura a loja para todos os visitantes.** Para disponibilizar o WhatsApp real em produção, actualize os valores iniciais da configuração no código.

## Estrutura
- `index.html` — página completa (HTML, CSS e JavaScript).
- `assets/images/hero-desktop.webp` — fotografia horizontal utilizada na secção hero em computador.
- `assets/images/hero-mobile.webp` — fotografia vertical apresentada em telemóveis.
- `assets/images/catalogo/*.webp` — 13 imagens de catálogo optimizadas (960 × 1280 px, cerca de 1,25 MB no total).
- `assets/logo.svg` — logótipo profissional vectorial da Beleza Brasil e China.
- `assets/favicon.svg` — símbolo utilizado como ícone do navegador.
- `README.md` — instruções.

## Publicação
Pode alojar a página em serviços que suportem ficheiros estáticos, incluindo GitHub Pages, Vercel, Netlify ou alojamento próprio. O envio para o GitHub, por si só, **não publica a página automaticamente**.

## Limitações
Esta versão é uma demonstração comercial. Não inclui pagamentos em linha, inventário, base de dados nem painel administrativo. As encomendas são iniciadas por WhatsApp e requerem confirmação por parte da loja.

## Preços e imagens do catálogo
Os 13 preços estão **provisórios**, definidos para demonstrar a organização do catálogo e o cálculo no carrinho. O nome, o volume e a descrição baseiam-se nas embalagens de referência fornecidas; confirme-os antes de publicar. Os ficheiros são referidos pelo campo `img` de cada produto, relativos à pasta `assets/images/catalogo/`.
