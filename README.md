# MacroPilot — Giulia Victor

Aplicativo mobile-first para acompanhar o plano alimentar, registrar refeições, peso, composição corporal e medidas.

## Publicação

O projeto usa GitHub Pages e o workflow `.github/workflows/deploy-pages.yml`.

1. Copie o conteúdo **interno** da pasta `macropilot/` do pacote MVP v2 para a **raiz** deste repositório. O arquivo `index.html` deve ficar na raiz, junto com a pasta `assets/`.
2. No GitHub, acesse **Settings → Pages → Build and deployment → Source** e escolha **GitHub Actions**.
3. Execute o workflow ou faça um push na branch `main`.
4. Acesse https://mauropimentel.github.io/Giulia/

## Limitações do MVP

Os perfis são salvos no armazenamento local do navegador; não há login ou sincronização entre dispositivos. A importação do plano ainda não é um parser universal de PDFs. O cálculo automático de macros e o rebalanceamento precisam de integração posterior.

## Privacidade

**Não commitar** dados pessoais de pacientes, registros de saúde, PDFs individuais de dietas ou segredos/API keys. GitHub Pages neste repositório é público. Verifique também os direitos de uso da marca e fotografias antes da distribuição pública.
