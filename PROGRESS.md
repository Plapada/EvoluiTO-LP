# Project Progress

## Goal
Landing page para o EvoluiTO - SaaS para Terapeutas Ocupacionais com IA.

## Status
In Progress

## Completed
- [x] Criado `serve.mjs` - servidor HTTP local na porta 3000
- [x] Criado `screenshot.mjs` - utilitario de screenshot com Puppeteer
- [x] Criado `index.html` - landing page completa com 11 secoes
- [x] Screenshot round 1 - todas as secoes verificadas visualmente
- [x] Screenshot round 2 - verificacao final de todas as secoes
- [x] Mudanca de modelo de negocio: assinatura → sob medida/personalizado
- [x] Todos CTAs "Comece Gratis" → "Solicitar Aplicativo"
- [x] "Notas SOAP" → "Relatorios Completos e Estruturados" em todo o site
- [x] Secao Pricing removida → nova secao "Solicitar / Como Adquirir" (3 steps + CTA card)
- [x] Nav link "Planos" → "Solicitar"
- [x] Final CTA atualizado: "Solicitar Meu Aplicativo" + "Resposta em ate 24h"
- [x] Footer "Precos" → "Como Adquirir"
- [x] Fix alinhamento "Tudo Sempre Atualizado" (lg:pl-6)

## Sections Implemented
1. Navbar (sticky, frosted glass on scroll, mobile hamburger)
2. Hero (two-column, phone mockup com screenshot real do dashboard, gradient text, CTAs)
3. Social Proof Bar (counters animados: 500+ TOs, 10k+ relatorios, 4.8/5, 98%)
4. Features (6 cards em grid 3-col com icones Lucide, tilt effect)
5. How It Works (3 steps com phone mockups reais + processing animation)
6. Benefits (4 rows alternados com screenshots reais do app)
7. Testimonials (3 cards com quotes, stars, avatars)
8. **Solicitar / Como Adquirir** (3 steps: Fale Conosco → Personalizamos → Pronto para Usar + CTA card "Pague apenas pelo que precisa")
9. FAQ (6 perguntas com accordion animado)
10. Final CTA (gradient azul com noise texture)
11. Footer (dark, multi-column)

## Libraries Used (CDN)
- Tailwind CSS (custom config com brand colors)
- GSAP + ScrollTrigger (hero animation, parallax)
- Lenis (smooth scroll)
- Vanilla-tilt.js (card 3D tilt effect)
- AOS (scroll reveal animations)
- Lucide Icons

## Animations & Interactions
- Cursor glow follow (desktop only)
- Mouse parallax on hero phone
- Counter count-up animation
- Staggered fade-up reveals on scroll
- 3D tilt on feature cards
- FAQ accordion with chevron rotation
- Navbar background transition on scroll
- Floating hero phone animation
- Badge pulse animation

## Brand Guidelines Applied
- Colors: #3478C6 (primary), #1D4ED8 (dark), #7ED321 (green), #9B59B6 (purple), #F39C12 (orange)
- Fonts: Plus Jakarta Sans (headings) + Inter (body)
- Lucide icons at 2px stroke
- Layered brand-tinted shadows
- SVG noise grain texture overlays

## Decisions Made
- Estilo light/clean com acentos bold azuis (escolha do usuario)
- Tom pessoal para TOs individuais (escolha do usuario)
- Pacote completo de secoes (escolha do usuario)
- Screenshots reais do app usados como mockups nos phone frames
- Single index.html com todos os estilos inline
- **Modelo de negocio: app personalizado sob medida (nao assinatura fixa)** - cliente solicita, equipe personaliza, paga pelo que precisa

## Known Issues / Blockers
- Nenhum

## Resume From Here
Todas as mudancas de modelo de negocio foram aplicadas. Proximo passo:
- **Usuario quer atualizar as perguntas do FAQ** ("depois nos iremos para mudar aqui as perguntas")
- Rodar `node serve.mjs` e abrir http://localhost:3000
- Substituir depoimentos por reais quando disponiveis
- Adicionar links reais de contato/WhatsApp nos botoes "Solicitar"
