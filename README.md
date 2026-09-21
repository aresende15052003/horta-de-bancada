# Horta de Bancada — versão final para GitHub + Vercel

Projeto estático pronto para publicar.

## Checkouts Hotmart já configurados

- Plano Básico 8,90 €: https://pay.hotmart.com/O107688696A?checkoutMode=10
- Plano Premium 14,90 €: https://pay.hotmart.com/K107688714A?checkoutMode=10

## Estrutura

- `index.html` — página completa
- `assets/originals/` — imagens originais em alta resolução
- `assets-manifest.json` — lista dos assets
- `vercel.json` — configuração de cache para publicação

## VSL

Vimeo em proporção 3:4. A página tenta autoplay com áudio; navegadores podem bloquear autoplay com som. O código tenta retomar/ativar no primeiro gesto do visitante sem exibir botão de áudio.

## Publicação

Suba todos os ficheiros e pastas deste diretório para a raiz do repositório no GitHub. Depois importe esse repositório na Vercel como projeto estático. Não é necessário comando de build.
