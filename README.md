# Débora Machado | Beauty Artist

Landing page de noivas (maquiagem e penteado, São Paulo e destination wedding).

## Onde está a página

- **`layout-nina/index.html`** é a página atual. Abra esse arquivo, ou sirva a pasta `debora-machado` com qualquer servidor estático (por exemplo `node serve.js` e abrir http://localhost:4173/layout-nina/).
- `layout-nina/fotos` e `layout-nina/video` têm as imagens e o vídeo usados nela.
- `index.html` na raiz é uma versão anterior, mantida só como referência.
- Os arquivos `opcoes-*.html`, `ideias-*.html` e `motion-*.html` são propostas de design mostradas durante o trabalho. Não fazem parte do site.

## Como a página é gerada

`layout-nina/index.html` é gerado por `tools/gerar-layout-nina.js`. Ele lê o layout-base da pasta `nina-costa` (somente leitura) e aplica o conteúdo, as fotos e o estilo da Débora. Por isso, **o arquivo gerado não deve ser editado à mão**: as alterações vão no gerador.

```bash
node tools/gerar-layout-nina.js
```

Os caminhos no começo do gerador (`SRC` e `OUT`) apontam para o computador onde o projeto foi feito e precisam ser ajustados em outra máquina.

## Antes de publicar

Veja `PENDENCIAS.md`. O número de WhatsApp já está preenchido, mas faltam domínio, imagem de compartilhamento e a confirmação de textos e depoimentos pela Débora.

## Contato

WhatsApp: +55 11 96917-4209 · Instagram: @deboramachadomake · Equipe: @equipedmmake
