# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML/CSS: a single `index.html` with inline styles and a small inline script, no build step. Hosted on GitHub Pages from this repository.

## Users

Two audiences, equally important:

- **Accounting clients:** small businesses and self-employed professionals who want ongoing accounting (bookkeeping, taxes, deadlines, reports) and a closer relationship than an anonymous firm offers. They are often anxious about deadlines, tax obligations, and whether they are overpaying.
- **Perícia clients:** people, companies, and lawyers who need a reliable expert calculation or report (laudo) for a labor or accounting dispute, judicial or extrajudicial.

Both arrive wanting to know whether Flávia is trustworthy and competent, then to start a conversation.

## Product Purpose

The professional website of Flávia Balbo Contabilidade, a solo accountant and accounting expert witness (contadora e perita contábil). It presents her three services and turns visitors into contacts via WhatsApp. Success means a qualified visitor starts a WhatsApp conversation.

## Positioning

A single, named professional rather than a firm: personal attention, technical rigor, and plain-language explanation of the numbers. One person covers both routine accounting and forensic work (perícias), so the same expertise behind court reports also serves everyday accounting clients.

## Operating Context

- Content is in Brazilian Portuguese (`lang="pt-BR"`).
- Contact happens only through WhatsApp links (`.zap-link`), built by the inline script from the `WHATSAPP` and `MENSAGEM` variables. There is no form or booking system.
- Regulated profession: the accountant's CRC registration number is expected on the site.

## Capabilities and Constraints

- Services: Contabilidade, Perícias trabalhistas, Perícias contábeis.
- Page sections: header and nav (Sobre, Serviços, Contato), hero, pain points ("Soa familiar?"), about Flávia, services, testimonials, CTA, footer.
- The brand colors and fonts are set in `:root`, labeled as coming from the brand manual (identidade visual).
- Open: the "Saiba mais" service links, Privacidade, Instagram, and LinkedIn currently go nowhere or straight to WhatsApp. No service detail pages or privacy page exist yet.

## Brand Commitments

- Name: Flávia Balbo Contabilidade. Logo at `img/logo.png`, favicon at `img/favicon.png`.
- Brand manual palette and fonts are defined in the `:root` tokens of `index.html`; treat them as binding unless the user changes them.
- Voice: warm, first-person ("Oi, eu sou a Flávia"), direct, reassuring; precise without jargon.

## Evidence on Hand

- Photos: `img/hero.jpg`, `img/sobre.jpg`.
- **All of these are placeholders. They are not real and must not be presented as true:** the CRC/SP number (123.456/O-7), "12+ anos de experiência", "200+ clientes atendidos", both testimonials (Mariana Freitas, Rafael Mendes), the WhatsApp number (5511999999999), and the claim that the consultation is free. Replace them with real data from Flávia or remove them before launch. Do not invent replacements.

## Product Principles

1. Trust before persuasion: credentials and verifiable facts beat claims.
2. Plain language: numbers and legal-technical work explained so a non-accountant understands.
3. A person, not a firm: Flávia is visible and speaks in her own voice.
4. One clear path to contact: every route leads to a WhatsApp conversation.
5. Serve both audiences without making either feel like an afterthought.
