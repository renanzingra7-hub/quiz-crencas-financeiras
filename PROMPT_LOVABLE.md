# Prompt Otimizado para Lovable - Quiz de Crenças Financeiras

Copie e cole o conteúdo abaixo diretamente no **Lovable (formerly Lovable.dev)** para gerar o app completo.

---

## PROMPT COMPLETO

Crie um aplicativo web interativo de QUIZ sobre crenças limitantes em relação ao dinheiro, em um único arquivo HTML (HTML + CSS + JavaScript embutidos, sem dependências externas).

### OBJETIVO
A pessoa responde o quiz e recebe, no final, seu perfil de mentalidade financeira com pontuação e sugestões de reflexão. O tom é inspirador, acolhedor e sem julgamento.

### DESIGN
- **Paleta de cores**: azul marinho (#0A1F3D), dourado (#D4AF37), preto (#0D0D0D), com texto branco suave (#F5F5F5)
- **Estilo**: moderno e elegante com cantos arredondados (border-radius 18-28px), sombras suaves (box-shadow com blur), transições animadas entre perguntas (fade-in/out 280ms)
- **Tipografia**: font-family "Inter", "Segoe UI", Roboto, Helvetica, Arial, sans-serif
- **Layout**: totalmente responsivo usando clamp() para fontes fluidas, grid/flex, media queries para mobile (max-width: 640px)
- **Barra de progresso**: no topo, mostrar avanço (0% até 100%) com gradiente ouro e animação suave

### ESTRUTURA DO APP
1. **Tela inicial**: 
   - Título "Qual é a Sua Relação Real com o Dinheiro?"
   - Breve introdução (2-3 frases) explicando o objetivo
   - Botão "Começar o Quiz" (estilo ouro com sombra)

2. **Tela de perguntas**: 
   - Uma pergunta por vez
   - Opções clicáveis (botões com hover effect)
   - Ao clicar, avança automaticamente para a próxima

3. **Tela de resultado**: 
   - Mostra pontuação total (grande e destaque em ouro)
   - Nome do perfil + emoji + descrição
   - Sugestão de reflexão em caixa destacada
   - Botão "Refazer o Quiz"

### PERGUNTAS (14 NO TOTAL)

**Parte 1 — Afirmações com escala de 1 a 5**
(Discordo totalmente = 1 ponto ... Concordo totalmente = 5 pontos)

1. "Dinheiro é fonte de estresse na minha vida." [1-5, normal]
2. "Se eu ganhasse mais, meus problemas financeiros acabariam." [1-5, normal]
3. "Gastar dinheiro em mim me faz sentir culpa." [1-5, normal]
4. "Pessoas ricas são, em geral, sortudas ou desonestas." [1-5, normal]
5. "Eu evito olhar meu saldo bancário quando as contas apertam." [1-5, normal]
6. "Investir é coisa para quem já tem muito dinheiro." [1-5, normal]
7. "Falo abertamente sobre dinheiro com as pessoas próximas." [1-5, REVERSO: 5=1 ponto, 1=5 pontos]
8. "Se eu ganhasse na loteria, saberia exatamente o que fazer com o dinheiro." [1-5, REVERSO: 5=1 ponto, 1=5 pontos]

**Parte 2 — Múltipla escolha (uma opção por vez)**

9. Quando você pensa no seu futuro financeiro, o sentimento dominante é:
   - a) Ansiedade — sinto que nunca vai ser suficiente (4 pts)
   - b) Indiferença — prefiro não pensar nisso (3 pts)
   - c) Esperança, mas com dúvidas (2 pts)
   - d) Confiança — tenho um plano e sigo ele (1 pt)

10. Quando surge uma oportunidade de investimento, sua primeira reação é:
   - a) "É golpe." (4 pts)
   - b) "Não entendo nada disso." (3 pts)
   - c) "Quero, mas tenho medo de perder." (2 pts)
   - d) "Vou estudar antes de decidir." (1 pt)

11. Na sua infância, a frase mais ouvida sobre dinheiro foi algo como:
   - a) "Dinheiro não cresce em árvore" / "Somos pobres, acostuma" (4 pts)
   - b) "Dinheiro é sujo" / "Rico é tudo ladrão" (4 pts)
   - c) "Precisamos economizar cada centavo" (3 pts)
   - d) "Trabalhe com o que ama e o resto vem" (2 pts)
   - e) Não lembro de frases marcantes (1 pt)

12. Quando você recebe uma quantia extra (bônus, 13º, presente):
   - a) Gasto rápido, antes que "suma" (4 pts)
   - b) Quito dívidas atrasadas (3 pts)
   - c) Guardo sem plano claro (2 pts)
   - d) Divido entre consumo e crescimento (1 pt)

13. Complete a frase: "Dinheiro é..."
   - a) ...uma fonte constante de preocupação (4 pts)
   - b) ...algo que nunca me sobra (3 pts)
   - c) ...uma ferramenta que ainda estou aprendendo a usar (2 pts)
   - d) ...liberdade para viver do meu jeito (1 pt)

14. Sobre aprender sobre finanças, você:
   - a) Acha que é complicado demais para você (4 pts)
   - b) Já tentou, mas desiste no meio (3 pts)
   - c) Aprende aos poucos, no seu ritmo (2 pts)
   - d) Estuda com constância e aplica o que aprende (1 pt)

### PONTUAÇÃO E PERFIS
(Pontuação mínima: 14, máxima: 69)

- **14 a 24** → **🌱 Mente da Prosperidade**
  - Descrição: "Você tem uma relação saudável com o dinheiro: enxerga oportunidades e entende que riqueza é construída com hábitos, não com sorte."
  - Reflexão: "Escolha um hábito financeiro para transformar em sistema (ex: aporte automático mensal)."

- **25 a 40** → **🌿 Em Transição**
  - Descrição: "Você já percebe padrões limitantes, mas eles ainda aparecem em momentos de pressão."
  - Reflexão: "Reescreva a frase sobre dinheiro que você ouviu na infância e cole onde você vê todos os dias."

- **41 a 54** → **🌳 Mente da Escassez Ativa**
  - Descrição: "Crenças de falta e merecimento estão no comando com frequência. Isso não diz nada sobre o seu valor — diz sobre programações que você absorveu."
  - Reflexão: "Registre todos os gastos por 30 dias. O ato de olhar já desconstrói a evitação."

- **55 a 69** → **🌰 Sobrecarga Emocional**
  - Descrição: "Dinheiro ocupa um espaço grande e doloroso na sua mente. O primeiro passo é reduzir a ansiedade para decidir com clareza."
  - Reflexão: "Escolha uma única ação de controle esta semana: listar dívidas, cancelar uma assinatura ou definir um valor fixo de lazer."

### REGRAS TÉCNICAS
- Usar apenas HTML, CSS e JavaScript nativo — **sem React, sem Tailwind, sem CDN**
- Tudo em um único arquivo ou estrutura autocontida
- Cálculo de pontuação em JavaScript puro
- Escala (1-5) com botões numerados claramente rotulados
- Animações suaves ao trocar de pergunta (transition: opacity, transform, 280ms ease)
- **Totalmente responsivo**: funciona perfeitamente em mobile, tablet e desktop
- Todo o texto em português do Brasil
- Gradient de fundo: radial-gradient para ouro + linear-gradient para azuis/pretos
- Backdrop-filter blur para efeito glass-morphism nas cards
- Sem fontes externas do Google Fonts — usar system fonts

### ESTRUTURA VISUAL DETALHADA

**Container principal:**
- max-width: 820px
- border-radius: 28px
- background: rgba(17, 26, 38, 0.82) com border dourado transparente
- box-shadow: 0 18px 40px rgba(0,0,0,0.30)

**Botões de opção:**
- min-height: 64px
- border-radius: 18px
- Ao hover: background muda, borda dourada, translateY(-1px)
- Cada opção tem um círculo colorido à esquerda (bullet) com letra/número

**Caixa de reflexão no resultado:**
- background: rgba(255, 255, 255, 0.03)
- border: 1px solid rgba(212, 175, 55, 0.2)
- border-radius: 18px
- padding: 18px
- A palavra "Reflexão:" em ouro (bold)

**Progresso:**
- Altura: 10px
- Barra preenchida com gradiente ouro (#D4AF37 → #f7d776)
- Animação de width com transition 350ms

### DETALHES EXTRAS (OPCIONAL)
- Adicionar eyebrow/badge "Autoconhecimento financeiro" na tela inicial
- Ao resultado, mostrar também um "resultado em números" (ex: "Você conseguiu 28 de 69")
- Animação ao aparecer/desaparecer de screens (fade + scale pequeno)
- Focus-visible outline em ouro para acessibilidade

### PALETA EXATA
```
--navy: #0A1F3D
--gold: #D4AF37
--black: #0D0D0D
--white-soft: #F5F5F5
--gold-light: #f7d776
--panel: rgba(255, 255, 255, 0.04)
--text-muted: rgba(245, 245, 245, 0.82)
```

---

**Pronto! Cole este prompt no Lovable e ele gerará o app completo, funcional e lindíssimo.** ✨

