# NutriFlow — Landing Page

Landing page de conversão para um serviço de automação de pré-atendimento voltado a nutricionistas autônomos e pequenas clínicas.

## Sobre o projeto

O NutriFlow é um sistema de pré-atendimento inteligente que filtra leads via formulário automatizado antes de encaminhá-los ao WhatsApp do nutricionista. Esta landing page apresenta e vende esse serviço, com foco em conversão.

## Estrutura de arquivos

```
nutriflow/
├── index.html    # Estrutura e conteúdo da página
├── styles.css    # Estilização completa (variáveis, layout, responsivo)
└── script.js     # Navbar scroll, FAQ accordion e scroll reveal
```

## Seções da página

1. **Hero** — Headline, mockup de chat e estatísticas
2. **Problemas** — Dores do nutricionista no pré-atendimento
3. **Solução** — Como o sistema funciona em 3 passos
4. **Benefícios** — O que o nutricionista ganha com a automação
5. **Como implementamos** — Processo de onboarding do serviço
6. **Prova social** — Depoimentos e métricas de confiança
7. **FAQ** — Perguntas frequentes com accordion
8. **CTA final** — Chamada para contato via WhatsApp

## Tecnologias

- HTML5
- CSS3 (Grid, Flexbox, variáveis CSS, animações)
- JavaScript puro (sem frameworks ou dependências)
- Google Fonts — [Sora](https://fonts.google.com/specimen/Sora) + [DM Sans](https://fonts.google.com/specimen/DM+Sans)

## Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nutriflow.git
   ```
2. Abra a pasta no VS Code (ou editor de preferência)
3. Abra o `index.html` no navegador — não é necessário servidor local

## Personalização

Antes de publicar, atualize os seguintes pontos no `index.html`:

- **Link do WhatsApp** — localize `wa.me/5500000000000` e substitua pelo número real com DDI
- **Nome/marca** — substitua `NutriFlow` pelo nome do seu serviço, se necessário
- **Depoimentos** — atualize os nomes, cargos e textos com depoimentos reais
- **Métricas** — ajuste os números de conversão e satisfação conforme os seus dados reais

## Responsividade

A página é mobile-first com dois breakpoints:

| Breakpoint | Comportamento |
|---|---|
| `≤ 900px` | Layout em coluna única, nav simplificada |
| `≤ 600px` | Ajustes de espaçamento e grid |

## Licença

Este projeto é de uso privado. Todos os direitos reservados.
