# Painel de Tempo

Painel pessoal para acompanhar eventos da Google Agenda no computador e no celular.

## Acesso

Após habilitar GitHub Pages na branch main, pasta /(root), abra:
https://williamsilvamga.github.io/painel-de-tempo/

Na primeira abertura, conecte sua implantação pessoal do Google Apps Script pelo campo do painel. **Nunca publique o endereço `/exec` no GitHub**, pois ele pode permitir a leitura de seus compromissos.

## Arquivos

- `index.html`: interface original adaptada para esta conta.
- `google/Codigo.gs` e `google/appsscript.json`: backend de leitura da Google Agenda.

## Avisos

Esta cópia mantém os recursos do painel original. As notificações push 15 minutos antes, no começo e no término dos eventos, inclusive com página fechada, **ainda não estão implementadas**.

Baseado no projeto original de mottihomero-rgb/painel-de-tempo, respeitando a licença incluída.
