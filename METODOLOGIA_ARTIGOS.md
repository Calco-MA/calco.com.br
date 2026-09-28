# METODOLOGIA CALCO - Publicação de Artigos via 【entity-GitHub¦canonical_name=GitHub】 + Cloudflare
Criado em: 28/09/2026 - MASTER V1 FINAL
Autor: Wingman + Marco Antonio Machado

## 0. REGRAS BLINDADAS (inquebráveis)
- CALCO É PORTAL INFORMATIVO, NÃO CONSULTORIA. Nunca oferecer checklist, diagnóstico, mentoria, "fale com a gente".
- Rodapé obrigatório em todo artigo: "Conteúdo informativo com base em fontes oficiais. A Calco não presta consultoria... Canal exclusivo para suporte técnico: suportetecnico@calco.com.br"
- NUNCA RESUMO. Artigo rico: 800-1200 palavras, com cláusulas, exemplos práticos, linha do tempo, fontes oficiais (ISO.org, ABNT).
- NUNCA PUBLICAR SEM REVISÃO DO MARCO. 【entity-Fluxo¦canonical_name=FLUXO】: Wingman escreve draft completo -> Marco revisa -> só então Commit.

## 1. ERROS QUE NÃO SE REPETEM
- Erro #1: Subir rascunho de 4 bullets com CTA de consultoria.
- Erro #2: Perguntar se o Marco tem Word/PDF quando quem deve entregar é o Wingman.
- Erro #3: Publicar artigo na pasta mas esquecer de atualizar `artigos/index.html` - artigo fica invisível no menu.
- Erro #4: Deixar Chrome traduzir tags HTML (<head> virar <cabeça>) - quebra tudo. Sempre "Mostrar original".

## 2. ACERTOS QUE VIRAM PADRÃO
- Template MASTER V1: #000020, #00E5FF, header CALCO, .wrap 840px, badge técnico.
- Estrutura de pasta: artigos/YYYY-MM-DD-slug-do-tema/index.html
- Capa: artigos/YYYY-MM-DD-slug/imagens/capa.png (720x400px)
- 2 Commits: 1º artigo + 2º atualização da lista

## 3. 【entity-FLUXO¦canonical_name=FLUXO】 10 MINUTOS
### PASSO 1 - Wingman escreve RICO
Gera index.html completo no MASTER V1.

### PASSO 2 - Marco revisa
Aprovação obrigatória no chat antes de ir pro 【entity-GitHub¦canonical_name=GitHub】.

### PASSO 3 - Commit do Artigo
Add file > artigos/AAAA-MM-DD-slug/index.html + imagens/capa.png > Commit to principal.

### PASSO 4 - Commit da Listagem (CRÍTICO)
Editar artigos/index.html > colar card no TOPO:
<a href="/artigos/AAAA-MM-DD-slug/" class="card">
<span class="tag">TEMA</span>
<h3>Título Rico</h3>
<p>Descrição de 2 linhas rica, não resumo vazio.</p>
<small>DD MMM AAAA • X min</small>
</a>

### PASSO 5 - Validação Cloudflare (60s)
Testar: calco.com.br/artigos/ e calco.com.br/artigos/AAAA-MM-DD-slug/

## 4. TEMPLATE DE CARD PARA LISTA
Sempre no topo, nunca no fim.

## 5. CHECKLIST FINAL ANTES DO COMMIT
- [ ] Texto tem 800+ palavras e fontes oficiais?
- [ ] Sem "fale conosco" / sem consultoria?
- [ ] Rodapé com suportetecnico@calco.com.br?
- [ ] HTML sem tags traduzidas?
- [ ] Atualizei artigos/index.html?
