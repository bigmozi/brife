---
name: Escale.ai — Plano de ajuste da landing page
description: Ações concretas pra fechar os gaps identificados em analise-lba.md, priorizadas por esforço x impacto
type: project
---

# Plano de ajuste — Landing page Escale.ai

> Deriva de [analise-lba.md](analise-lba.md). Cada item aqui é uma ação de execução em `index.html`, não mais diagnóstico. Ordem = prioridade (impacto alto / esforço baixo primeiro).

## Fase imediata (baixo esforço, alto impacto) — ✅ concluída 2026-08-11

**1. Seção "Sobre a Nebu"**
Inserir entre "Resultado" e "Licença". 1 bloco curto: quem constrói o Escale.ai, herança do padrão Mozi ("sistema simples, autonomia — conhecimento fica no sistema, não numa pessoa" — o mesmo princípio que o produto vende, aplicado a quem vende), sem bio clássica de "fundou X, faturou Y" (a LBA recomenda evitar esse clichê). Resolve prova pessoal.

**2. Ancoragem de valor**
Na seção "A conta não mente", adicionar 1 linha traduzindo as 210h/mês em ordem de grandeza de custo evitado — ex. comparar com o custo de manter uma pessoa dedicada full-time só pra produção, sem citar preço do Escale.ai. Não editar RNF04 (preço continua fora da página).

**3. FAQ — compliance TSE**
Adicionar pergunta: algo como "O uso de IA é permitido pelo TSE?". Resposta direta, sem juridiquês: revisão humana obrigatória, rotulagem de conteúdo sintético quando aplicável, o produto não substitui assessoria jurídica eleitoral. Fecha o risco que o PRD já mapeou internamente (seção 10) e nunca respondeu publicamente.

**4. FAQ — preço**
Adicionar pergunta "Quanto custa?". Resposta que não revela o número mas também não é vazia: menciona que varia por complexidade do mapeamento e que a Nebu apresenta a faixa depois de mostrar o sistema funcionando com o brief real do candidato.

## Fase seguinte (esforço médio, alto impacto — depende de material) — ✅ concluída 2026-08-11 (versão ilustrativa)

**5. Prova técnica — antes/depois** ✅
Implementado como exemplo ilustrativo fictício (prompt genérico vs. saída Escale.ai), com selo explícito "não reflete um candidato ou campanha real". Trocar pelo exemplo real assim que houver caso — ver item 9.

**6. Prova visual — mockup** ✅
Mockup de template de post construído em HTML/CSS (sem imagem externa), com selo "Exemplo". Trocar por print real do Canva quando disponível.

## Fase de manutenção (baixo esforço, roda quando surgir insumo)

**7. Dobra própria pro plugin de Figma** ✅ — virou seção própria, formato espelhado no add-on Inteligência Competitiva.

**8. Sonho explícito** ✅ — linha adicionada no hero: "O que fica: uma campanha que responde em minutos e ainda sobra tempo pra pensar estratégia todo dia." Ainda falta consolidar num documento de macronarrativa único (hoje espalhado em DNA+PRD+LP).

**9. Prova social** — entra assim que existir o primeiro cliente do posicionamento pós-pivô. Não dá pra adiantar sem case real. Quando existir, também trocar os exemplos ilustrativos dos itens 5 e 6 pelo caso de verdade.

**10. Consolidar `index 3.html` / `index .html`** ✅ — arquivos descartados (nunca estavam versionados no git, então não geram diff de remoção).

---

## Relacionados
- [analise-lba.md](analise-lba.md) — diagnóstico completo
- [DNA.md](DNA.md), [PRD.md](PRD.md) — fonte de verdade de posicionamento e requisitos
