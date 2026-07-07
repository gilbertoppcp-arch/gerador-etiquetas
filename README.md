# Gerador de Etiquetas — Log&Print

Gerador de etiquetas 150×100 mm que lê a planilha padrão (aba **PPG**), busca por OP (Kit ou Item) e permite editar todo o conteúdo antes de imprimir.

## Como funciona

1. Abra a página e carregue a planilha padrão (aba PPG).
2. Digite a OP no campo de busca rápida e selecione o resultado.
3. Ajuste o conteúdo e as fontes no painel de edição, se necessário.
4. Clique em **Imprimir / PDF** (papel 150×100 mm, margens Nenhuma, escala 100%).

Tudo roda no navegador — nenhum dado sai do computador.

## Publicar no GitHub Pages

1. Crie um repositório novo (ex.: `gerador-etiquetas`).
2. Envie os arquivos `index.html` e `README.md` para a branch `main`.
3. No repositório: **Settings → Pages**.
4. Em **Source**, selecione **Deploy from a branch**.
5. Em **Branch**, escolha `main` e pasta `/ (root)`, depois **Save**.
6. Aguarde ~1 minuto. O endereço será `https://SEU_USUARIO.github.io/gerador-etiquetas/`.

## Dependências

As bibliotecas (SheetJS e JsBarcode) são carregadas via CDN, então é necessário estar online. Para uso offline, baixe os dois arquivos `.min.js` e troque os links `<script src="https://cdnjs...">` por caminhos locais.
