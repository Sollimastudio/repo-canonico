# PROTOCOLO DE DEVOLUÇÃO E INTEGRAÇÃO — PATCH 026

## Devolução

Cada parecer deve retornar com:

- DOCX preenchido;
- identificadores preservados;
- conclusão final da área;
- nome, qualificação e registro profissional, quando aplicável;
- data de validade ou corte;
- conflitos de interesse;
- fontes e fundamentos.

Nome recomendado:

`PARECER_RETORNADO_[AREA]_[NOME]_[AAAA-MM-DD].docx`

## Matriz única

Cada recomendação receberá:

- ID original;
- área e parecerista;
- disposição e gravidade;
- fundamento;
- redação proposta;
- impacto local e transversal;
- decisão editorial;
- justificativa;
- status de aplicação;
- hash antes e depois.

## Divergências

Quando pareceres divergirem:

1. a divergência será preservada;
2. será verificado se respondem ao mesmo trecho e à mesma pergunta;
3. segurança, legalidade, precisão factual, coerência metodológica e identidade autoral serão ponderadas no contexto;
4. risco crítico poderá exigir nova consulta;
5. nenhuma redação será aplicada apenas pela autoridade do parecerista.

## Saída

Somente recomendações aprovadas serão aplicadas pelo **Patch 026 — Integração dos Pareceres Externos**.

O Marco 02 permanece preservado. Um eventual Marco 03 só nasce depois da aplicação controlada e de novo QA global.