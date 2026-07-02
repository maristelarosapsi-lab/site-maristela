# Site — Maristela Rosa Guedes · Psicóloga · Terapia Sistêmica

## 🌐 NO AR
**https://maverickguedes77-hue.github.io/site-maristela/**

Hospedado no GitHub Pages (grátis, HTTPS automático) — repositório: `maverickguedes77-hue/site-maristela` (publicado em 02/07/2026).

## Estrutura (esta pasta É a pasta de edição do site)
- `index.html` — o site inteiro (HTML único, CSS e JS embutidos)
- `fotos/maristela.jpg` — foto atual
- `ebooks/` — os 2 PDFs de download direto ("5 Padrões" e "Pensar Sistêmico")
- `council/` — relatório e transcript da análise do conselho de especialistas (não publicado)
- `psi/` — arquivos originais da sessão anterior (não publicado)

## ✏️ Como editar e republicar
1. Edite `index.html` (ou peça ao Claude nesta pasta).
2. No terminal, dentro desta pasta:
   ```
   git add -A
   git commit -m "descrição da mudança"
   git push
   ```
3. O GitHub Pages republica sozinho em ~1 minuto.

Para testar localmente antes: `python -m http.server 8000` e abrir `http://localhost:8000`.

## ✔ Estado atual (02/07/2026)
- Copy 100% do documento oficial (`SITE OFICIAL (2).docx`) + brandbook (Fraunces+Inter, Forest/Bone/Clay/Gold)
- Valor da sessão: **R$ 200** · Formação: 4 anos · Público: adolescentes, adultos, casais e famílias
- Calendly real embutido (`calendly.com/maristelarosapsi/sessao-psicoterapia`)
- Mercado Pago real (botão de pagamento na seção Agendamento)
- E-books com **download direto** após preencher nome/e-mail (sem passar pelo WhatsApp; WhatsApp é opcional)
- Quiz de padrão relacional (roda 100% no navegador — nada é enviado; declarado no site)
- **Zero tags EDITAR** em produção (conselho de especialistas apontou como quebra de confiança)
- Nota de privacidade LGPD no rodapé · Aviso ético CFP (CVV 188 / SAMU 192)
- Painel "primeira conversa de 20 min" **removido** a pedido (agendamento direto)

## 📋 Pendências (pós-lançamento)
1. **Teste de ponta a ponta** (recomendação nº 1 do conselho): agendar um horário-teste no Calendly e abrir o checkout do Mercado Pago até o fim, conferindo se cobra **R$ 200**.
2. **Leads do e-book**: hoje o download funciona, mas o e-mail digitado **não é salvo em lugar nenhum** (site sem servidor). Fix de 15 min: criar conta grátis no [Formspree](https://formspree.io) e seguir o comentário no bloco `/* E-book */` do JS.
3. **Depoimentos**: continuam marcados "exemplo ilustrativo" — substituir por reais somente com autorização por escrito (CFP).
4. **Fotos melhores** (sugestão do próprio documento oficial): Hero = rosto próximo; "Quem sou eu" = espontânea (poltrona/xícara); Propósito = voluntariado; extra = caminhando em parque ("novos caminhos"). Manter proporção 4:5.
5. **Domínio próprio** (opcional): comprar `maristelaguedes.com.br` (~R$40/ano no registro.br) e apontar para o GitHub Pages (Settings → Pages → Custom domain).

## O que NÃO alterar sem consultar o brandbook
- Paleta (hex exatos) e regra 60/25/10/5 · Fraunces + Inter · Aviso ético do rodapé (não-negociável) · Alternância de fundos claro/escuro
