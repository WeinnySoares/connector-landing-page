# Guia de Importação para o Figma — Landing Page connector

Como o formato nativo `.fig` é proprietário e fechado da Figma Inc., a forma oficial e mais fiel de transformar código web em camadas editáveis (Auto Layout, textos, vetores SVG e estilos) no Figma é importar o arquivo `connector-landing-page.html` incluído neste pacote.

## Passo a Passo (2 minutos)

1. **Extraia o arquivo ZIP** e localize o arquivo `connector-landing-page.html`.
2. Abra o **Figma** (Desktop ou Web) e crie um novo arquivo de design (`New design file`).
3. Abra o menu de plugins (`Resources` / `Plugins` ou atalho `Ctrl + /` / `Cmd + /`) e busque pelo plugin gratuito **html.to.design** (da ‹div›RIOTS).
4. Execute o plugin **html.to.design**, selecione a aba **File / Upload** (ou arraste o arquivo `connector-landing-page.html` diretamente para dentro da janela do plugin).
5. Escolha os viewports desejados:
   - **Desktop:** `1440px`
   - **Mobile:** `390px` (opcional, para gerar a versão responsiva automaticamente)
6. Clique em **Import**.

## O que será gerado automaticamente no seu Canvas Figma:
- **Frames organizados por seção** (`Header`, `Hero`, `Estatísticas & Gráfico`, `Comparativo`, `Soluções`, `CTA` e `Footer`).
- **Auto Layout** configurado nos grids, cards e botões.
- **Logo SVG editável** (as chaves `{ }` e os pixels brancos vetoriais separados).
- **Tipografia Inter** e paleta de cores oficial (`#5313B8`, `#2B0768`, `#150433`, `#E11D48`).
