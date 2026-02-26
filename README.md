# Sistema B4 - Validação Institucional de Diploma

Projeto estático pronto para Cloudflare Pages.

## Estrutura final

- `index.html` → página institucional de validação no padrão do Sistema B4.
- `_headers` → cabeçalhos de segurança para produção.
- `diploma-01247760-modelo.xml` → XML adaptado ao perfil do diplomado, disponível para download na interface.

## Deploy no Cloudflare Pages

1. Suba esta pasta para um repositório Git.
2. No Cloudflare Pages, crie um projeto apontando para esse repositório.
3. Configuração:
   - Build command: *(vazio)*
   - Build output directory: `/`
4. Deploy.

## QR Code

Configure o QR do diploma para abrir a URL final do Pages, por exemplo:

`https://seu-projeto.pages.dev/`
