# Floresça — Arquitetura da Intervenção
## Estrutura superficial vs. estrutura profunda

**Para que serve este documento:** guiar adaptações do Floresça para outros
públicos (adolescentes, idosos, contextos organizacionais, outras culturas)
sem perder eficácia. Referência metodológica: adaptação cultural de programas
preventivos (Resnicow et al., 1999; metodologia GEPPSVida/Murta).

- **Estrutura superficial** = roupa da intervenção. Pode (e deve) mudar ao
  adaptar: linguagem, exemplos, metáforas, cores, ícones, nomes.
- **Estrutura profunda** = mecanismo ativo de mudança. NÃO pode ser alterada
  sem reavaliar a eficácia: é o que a evidência sustenta.

**Regra prática:** se a mudança altera O QUE a pessoa pratica ou POR QUE
funciona → estrutura profunda (não mexer sem novo estudo). Se altera COMO
se explica/ilustra → superficial (adaptar à vontade).

---

## Elementos transversais (todo o app)

| Elemento | Superficial (adaptável) | Profundo (preservar) |
|---|---|---|
| Metáfora do jardim | Canteiros, regar, semente→jardim. Pode virar qualquer metáfora de cultivo gradual | Comunicar que bem-estar é **prática incremental**, não estado fixo; normalizar pausas sem culpa |
| Jardim visual (substitui XP, níveis e emblemas) | Plantas, cores, formas, textos dos marcos (7, 30 e 100 dias) | Retorno de **significado**, não de pontos: cada emoção nomeada, em dias diferentes, faz uma planta avançar (no máximo 1 avanço/dia); nada encolhe nem murcha; devolutiva com as palavras da própria pessoa. XP continua guardado em segundo plano só para continuidade dos dados |
| Nudges da Home | Textos, emojis, ordem visual | Retorno após pausa SEM culpa (evitar efeito "estraguei tudo"); efeito Zeigarnik (módulo a meio); lembrar experimento aberto |
| Contagem de dias | Texto e ícone do contador | Contagem **cumulativa** de dias de cultivo, que nunca zera (sequência consecutiva pune pausas e reforça o "tudo ou nada") |
| Primeira prática (1 min) | Texto, animação, duração da fase | Benefício percebido cedo, antes do pré-teste; expiração prolongada (sistema calmante, TFC); sempre opcional (pular) |
| Gatilho de rotina (âncora) | Opções de âncora, horários sugeridos | Plano quando-então **logo após a primeira prática** (dia 0), ligado ao lembrete (Gollwitzer, 1999) |
| Lembrete | Texto, horário | Honesto sobre o limite técnico: evento de calendário (.ics) como canal confiável; notificação do navegador só com o app aberto ou em segundo plano. Sem servidor de push |
| Registro com "porquê" | Texto da dica, posição do campo | Campo opcional **"Por que isso foi bom?"**: é o ingrediente ativo das Três Coisas Boas (Seligman et al., 2005). Um dia com porquê vale 2 pontos de cuidado na planta (teto de 2 por dia), então elaborar cresce mais do que repetir registros vazios |
| Compartilhar uma boa notícia | Texto da mensagem, botões | Capitalização (Gable et al.): contar a alguém amplia o efeito. Só envia o que a pessoa tocar para enviar (Web Share ou cópia); sem rede social interna, sem conta |
| Frases de identidade | Texto das frases, onde aparecem (retorno, "hoje já foi regado", Progresso) | Só enunciar o que a pessoa **de fato fez** ("Você já nomeou 4 emoções"), nunca elogio genérico, comparação com outras pessoas ou ranking. Reforça identidade a partir de evidência comportamental |
| Resumo semanal | Redação, posição na Home, tipografia da citação | Reflete a semana com os **dados e as palavras da própria pessoa** (uma frase dela é citada). Sem nota, sem comparação, sem alerta quando a semana foi vazia: se não houve registro, o resumo simplesmente não aparece |
| Meta semanal | Número padrão (2), texto | Meta **semanal** e editável, nunca diária; abaixo da meta não gera aviso negativo |
| Pesquisa e consentimento | Textos do convite | **Separado do uso do app.** Consentimento só é gravado após aceite explícito (18+); `syncToResearch` exige consentimento; recusar não muda nada no app |
| Apoio em crise | Texto, ordem dos serviços | Acesso permanente ("Preciso de apoio agora") na Home, no Registro e em Dados, e linguagem de estado (não de traço) nos resultados do SPANE |
| Planos "quando-então" | Frases específicas dos planos | Formato implementation intention (Gollwitzer, 1999): gatilho situacional + ação específica |
| Registro de Momentos | Chips, emojis, textos do formulário | Registro escrito + nomeação da emoção + intensidade (dose recebida / estado) |
| Dose Cultivada | Tags, pergunta, visual do card | Auto-relato SEMANAL de prática ativa (dose cultivada ≠ dose recebida); não bloqueante; dispensável |
| Laboratório | Banco de 12 experimentos, títulos, emojis | Ciclo do experimento comportamental: **previsão registrada ANTES → teste → observação → comparação** (TCC) |
| SPANE + escala de crenças | Telas, cores, ordem das fases | Itens e escala de resposta do SPANE (Diener et al., 2009) — não parafrasear (perde validade); crenças: manter pré/pós idênticos |
| Tailoring (3 caminhos) | Textos das opções do onboarding | m1/m2 sempre primeiros; caminho 2 (medo do prazer): sistema calmante e teste de crenças ANTES de gratidão |

---

## Módulo 1 — Por que Cultivar Emoções Positivas
**Mecanismo ativo (profundo):** estabelecer o racional da intervenção —
(a) viés de negatividade como herança evolutiva (normaliza a dificuldade,
reduz autocrítica); (b) broaden-and-build (Fredrickson): emoções positivas
ampliam cognição e constroem recursos duráveis; (c) distinção explícita
entre cultivar o positivo e negar o negativo (anti-positividade tóxica) —
sem isso, público com sofrimento resiste à proposta.
**Superficial:** metáfora velcro/teflon, diagrama da espiral, os 6 mitos
das cartas, exemplos do quiz.

## Módulo 2 — O Repertório: 10 Emoções Positivas
**Mecanismo ativo:** granularidade emocional (Barrett) — rotular com
precisão melhora regulação e diferenciação da experiência; apresentar
repertório que INCLUI emoções de baixa ativação (serenidade, contentamento,
gratidão) — quem só procura euforia não encontra o repertório completo.
**Superficial:** os emojis, as cenas das cartas ("ver o mar à noite"),
a atividade expansiva/tranquila como recurso didático.

## Módulo 3 — Notar: o Radar do Positivo
**Mecanismo ativo:** treino atencional deliberado para eventos positivos
via REGISTRO ESCRITO regular (Três Coisas Boas — Seligman et al., 2005),
com três ingredientes: (a) escrever (atenção sustentada + consolidação),
(b) incluir o pequeno/cotidiano, (c) elaborar o porquê. + Âncora de hábito
("depois de X, registro") — cria oportunidade (COM-B).
**Superficial:** nome "radar", prática "caça ao positivo", exemplos.

## Módulo 4 — Saborear
**Mecanismo ativo:** amplificação atencional deliberada da experiência
positiva (savoring — Bryant & Veroff): absorção sensorial, expressão
comportamental da emoção, prolongamento intencional; nos 3 tempos
(presente/reminiscência/antecipação); identificação dos amortecedores
(dampening: desqualificar, multitarefa, viajar para o problema).
**Superficial:** metáfora do mel, prática do café/música, itens da
atividade "amplifica ou apaga".

## Módulo 5 — Gratidão que Transforma
**Mecanismo ativo:** reorientação da atenção para o RECEBIDO + ativação
de vínculo (Emmons & McCullough, 2003); eficácia depende de
ESPECIFICIDADE + VARIEDADE (contra adaptação hedônica); carta de gratidão
com destinatário real e elaboração do efeito (Seligman — gratitude visit).
Distinguir gratidão de dívida/obrigação (protege contra iatrogenia).
**Superficial:** exemplos Ana/Bia, fases da prática guiada, formato carta.

## Módulo 6 — Contentamento e Segurança (TFC)
**Mecanismo ativo:** ativação do sistema calmante/afiliativo (Gilbert):
(a) psicoeducação dos 3 sistemas + distinção positivas-de-conquista vs.
positivas-de-calmaria; (b) respiração em ritmo calmante com EXPIRAÇÃO
PROLONGADA (freio vagal); (c) imagética de memória de afeto/gentileza
(o sistema responde a lembrança como a evento); (d) alegria compassiva.
Pré-requisito no caminho 2: prepara quem tem medo do prazer.
**Superficial:** diagrama dos círculos, gesto âncora específico, textos.

## Módulo 7 — Crenças que Bloqueiam a Alegria
**Mecanismo ativo:** (a) identificação e NORMALIZAÇÃO dos medos de emoções
positivas como aprendizado protetor (Gilbert; fear of happiness — Joshanloo);
(b) o ciclo crença→evitação→não-testagem→manutenção; (c) experimento
comportamental com previsão registrada ANTES do teste — a mente acredita
no vivido, não no argumentado. É a ponte para o Laboratório.
**Superficial:** as 6 crenças das cartas, exemplos, numeração dos passos.

## Módulo 8 — Um Jardim que Dura
**Mecanismo ativo:** manutenção e generalização — (a) seleção pelo usuário
de 2-3 práticas QUE FUNCIONARAM (não prescrição); (b) conversão em planos
quando-então; (c) desenho do ambiente (COM-B: oportunidade); (d) resposta
ativa-construtiva a boas notícias (capitalização — Gable); (e) plano
explícito para o lapso ("recomeçar sem drama" — prevenção do efeito de
violação da abstinência); (f) variedade contra adaptação (Lyubomirsky).
**Superficial:** grid PERMA, carta ao futuro como formato, exemplos.

---
© 2026 Psicoterapia e Afins · Documento técnico interno
