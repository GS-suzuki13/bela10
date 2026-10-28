# Bela10 — loja demonstrativa de cosméticos

Vitrine de e-commerce para pequenos negócios: catálogo com busca, filtros e
ordenação, sacola persistente, cupom de desconto, frete grátis progressivo e
checkout em 4 etapas.

> Projeto de portfólio. Produtos, preços e pagamentos são fictícios.

## Destaques

- **HTML, CSS e JavaScript puros**, sem framework e sem build. Um arquivo,
  carregamento instantâneo.
- **Frete por CEP**: o endereço é preenchido sozinho pela API pública
  [ViaCEP](https://viacep.com.br).
- **Pix de verdade no formato**: o código "copia e cola" segue o padrão
  BR Code (EMV) do Banco Central, com CRC16, e vira QR Code. A chave usa um
  domínio `.invalid`, então o código é lido pelo app do banco mas não há para
  quem pagar.
- **Resumo do pedido no WhatsApp** com os itens, o total e o endereço.
- **Sacola e cupom salvos** no `localStorage`. Layout responsivo.

Cupom de teste: `BELA10` (10% off).

## Rodar localmente

Abra o `index.html` no navegador ou rode `python -m http.server`.

## Autor

Desenvolvido por **Gustavo Suzuki**:
[portfólio](https://gustavosuzuki.vercel.app) ·
[LinkedIn](https://www.linkedin.com/in/gustavo-suzuki-858189163/) ·
[GitHub](https://github.com/GS-suzuki13)
