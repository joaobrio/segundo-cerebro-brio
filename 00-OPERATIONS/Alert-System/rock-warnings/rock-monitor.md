# 🚨 ROCK WARNING SYSTEM - GRUPO BRIO

## CONFIGURAÇÃO DE ALERTAS

### THRESHOLDS
- **🟢 Verde**: Rock no prazo, >80% concluído
- **🟡 Amarelo**: Rock com 1 semana de atraso OU 50-79% concluído
- **🔴 Vermelho**: Rock com >2 semanas de atraso OU <50% concluído

## ROCKS Q4 2025 - STATUS

| Rock | Owner | Target | Status | Progresso | Alerta |
|------|-------|--------|--------|-----------|--------|
| Implementação EOS Completa | João | 31/12 | On Track | 85% | 🟢 |
| Lançamento Produto X | Mariana | 15/12 | At Risk | 65% | 🟡 |
| Crescimento 50% Revenue | Francisco | 31/12 | Behind | 40% | 🔴 |

## AÇÕES AUTOMÁTICAS

### Alerta Amarelo (1 semana atraso)
1. Notificação Slack para owner
2. Agendamento 1:1 com supervisor
3. Inclusão em pauta L10

### Alerta Vermelho (2+ semanas atraso)
1. Escalação para C-Level
2. War room emergencial
3. Revisão de recursos alocados
4. Plano de recuperação em 48h

## INTEGRAÇÃO SLACK

```javascript
// Webhook configurado em: 00-OPERATIONS/Integration-Hub/api-connectors/slack-webhooks/
// Canal: #rock-alerts
// Frequência: Diária às 9h
```

## HISTÓRICO DE ALERTAS

| Data | Rock | Tipo | Ação Tomada | Resultado |
|------|------|------|-------------|-----------|
| 04/08 | Produto X | Amarelo | 1:1 com Mariana | Plano recuperação |

---
*Atualizado: 04/08/2025 | Próxima revisão: Semanal*