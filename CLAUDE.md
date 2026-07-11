# Contexto — Landing page do "Corretor IA"

## Objetivo

Página única (one-page) para divulgar o atendente de IA no WhatsApp para
corretores/imobiliárias. Serve para MANDAR UM LINK (em vez de anexar vídeo),
com cara profissional, e converter em conversa no WhatsApp.

## Este projeto é SEPARADO do bot

O repositório do bot (agente-ia-imobiliaria) é backend privado que roda em VPS.
Esta landing é um projeto NOVO, estático e público. Não misturar os dois.

## Produto que a landing vende

Atendente de IA no WhatsApp que atende leads 24/7, qualifica e avisa o corretor.
Posicionamento: "a opção simples e barata" (sem CRM caro, no ar em ~2 dias).
Preço: R$200/mês no plano anual ou R$300/mês mensal.
Público: corretores autônomos e imobiliárias pequenas.

## Stack (deliberadamente simples)

- Um único index.html + um style.css. Sem framework, sem build.
- Vídeo: YouTube "não listado", embutido via <'iframe'> (não hospedar o arquivo).
- CTA principal: botão "Falar no WhatsApp" via link wa.me:
  "https://wa.me/55DDNUMERO?text=Oi,%20vi%20a%20demo%20e%20quero%20saber%20mais"
- Hospedagem: Vercel (repo novo no GitHub conectado, deploy automático, HTTPS).

## Seções da página (rascunho)

1. Título + subtítulo (dor: "cansou de responder os mesmos WhatsApps o dia todo?").
2. Vídeo da demo (embed YouTube).
3. Como funciona (3 passos curtos).
4. Preço (R$200 anual / R$300 mensal).
5. Botão "Falar no WhatsApp" (repetido no topo e no fim).
6. Rodapé simples.

## Pendências a decidir na conversa

- Número de WhatsApp de destino do botão (com DDI+DDD).
- Link do vídeo no YouTube (não listado).
- Nome/domínio na Vercel (ex.: corretor-ia.vercel.app).
- Texto final de cada seção.

## Princípio

Simples, rápida, 1 página, 1 ação (falar no WhatsApp). Nada de complexidade.
