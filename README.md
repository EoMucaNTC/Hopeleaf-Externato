# HopeLeaf — Externato

Apresentação institucional do ecossistema educacional HopeLeaf para escolas de Ensino Médio.

## Apresentação

Os sete slides estão em `dist/index.html`, um único arquivo HTML com CSS e JavaScript incorporados. Basta abrir o arquivo no navegador.

- Navegação pelos botões Anterior e Próximo ou pelas setas do teclado.
- Atalhos Home e End para o primeiro e o último slide.
- Layout responsivo, referências científicas e contatos do projeto.
- Impressão em formato de apresentação.

A fonte Inter é carregada pelo Google Fonts quando há conexão. O restante da apresentação não depende de bibliotecas externas.

## Hospedagem

Site estático com diretório de publicação `dist/`.

O fluxo `.github/workflows/deploy-pages.yml` publica esse diretório no GitHub Pages quando há alterações na apresentação na branch `main`. No repositório, a origem do Pages deve ser configurada como GitHub Actions. O fluxo também permite execução manual pela aba Actions.

A configuração da hospedagem anterior em Sites permanece em `.openai/hosting.json`.

## Contato

- José Cláudio
- ramos.filho@unesp.br
- WhatsApp: +55 (19) 99973-3281
