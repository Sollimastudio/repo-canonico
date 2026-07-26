# QA TÉCNICO DO DOSSIÊ

## Escopo

- 1 dossiê geral;
- 6 cadernos especializados;
- 68 trechos identificados;
- 6 pacotes individuais de envio;
- versões DOCX e Markdown;
- registro JSON de rastreabilidade;
- certificado de congelamento.

## Inspeção visual

Todos os sete DOCX foram renderizados em PDF e PNG e inspecionados página por página.

Resultado:

- nenhum texto cortado;
- nenhuma sobreposição;
- nenhuma tabela fora da página;
- títulos, IDs, paginação e rodapés legíveis;
- campos de resposta utilizáveis.

## Acessibilidade

A auditoria automatizada encontrou:

- **0 ocorrências de gravidade alta**;
- ocorrências médias restritas à ausência de marcação semântica de cabeçalho em tabelas mistas.

A correção automática global não foi aplicada porque parte das tabelas funciona como formulário e a primeira linha não é semanticamente um cabeçalho.

Mitigações:

- versão Markdown linear para cada caderno;
- rótulos textuais explícitos;
- nenhuma informação transmitida apenas por cor;
- relatórios JSON de acessibilidade preservados no pacote principal.

## Integridade

Marco 02 verificado pelo SHA-256:

`6e0297a3a4889779711d23a28b962713fb2442e8b2246e9cf83311cabfe80ca7`

Nenhuma alteração foi realizada no manuscrito durante a preparação do dossiê.