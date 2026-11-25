# gautomation-agenda

Para o ambiente `gautomation` do Jelastic às 21h e inicia às 8h (horário de Brasília/Fortaleza) para economizar créditos.

- `.github/workflows/parar.yml`: 00:00 UTC (21h)
- `.github/workflows/iniciar.yml`: 11:00 UTC (08h)
- Secret necessário: `JELASTIC_TOKEN` (Settings > Secrets and variables > Actions)
- Teste manual: aba Actions > escolher o workflow > Run workflow
