# 🚨 ISSUE AGING REPORT - SISTEMA L10

## ISSUES CRÍTICAS (>1 SEMANA PARADAS)

### 🔴 VERMELHO - AÇÃO IMEDIATA (>2 semanas)

| Issue # | Descrição | Owner | Dias Parada | Última Ação | Bloqueio |
|---------|-----------|-------|-------------|-------------|----------|
| IDS-045 | Sistema faturamento lento | Tech | 15 dias | 20/07 | Aguardando vendor |
| IDS-048 | Turnover alto junior | People | 12 dias | 23/07 | Sem budget aprovado |

**AÇÕES AUTOMÁTICAS DISPARADAS:**
- ✅ CEO notificado via Slack
- ✅ War room agendado para hoje 16h
- ✅ Recursos realocados

### 🟡 AMARELO - ATENÇÃO (1-2 semanas)

| Issue # | Descrição | Owner | Dias Parada | Status |
|---------|-----------|-------|-------------|---------|
| IDS-052 | Processo onboarding | People | 8 dias | Em revisão |
| IDS-053 | Dashboard vendas | Tech | 7 dias | Desenvolvimento |
| IDS-054 | Conflito equipe X | Ops | 9 dias | Mediação agendada |

## ANÁLISE DE CAUSA RAIZ

### TOP 3 CAUSAS DE TRAVAMENTO:
1. **Dependência externa** (35%)
   - Solução: SLAs com fornecedores
   
2. **Falta de ownership claro** (25%)
   - Solução: RACI matrix por issue
   
3. **Complexidade subestimada** (20%)
   - Solução: Break down obrigatório

## MÉTRICAS DE PERFORMANCE L10

| Métrica | Atual | Meta | Tendência |
|---------|-------|------|-----------|
| Issues resolvidas/semana | 12 | 15 | ↘️ |
| Tempo médio resolução | 5.2 dias | 3 dias | ↗️ |
| Issues >1 semana | 5 | 0 | ↗️ |
| Recorrência | 15% | <10% | →️ |

## ISSUES POR DEPARTAMENTO

```
Tech:       ████████ 8 issues (40%)
People:     ██████ 6 issues (30%)
Operations: ████ 4 issues (20%)
Finance:    ██ 2 issues (10%)
```

## PLANO DE AÇÃO IMEDIATO

### PARA ISSUES VERMELHAS:
1. [ ] **IDS-045**: Call com vendor HOJE - escalar para CEO do vendor
2. [ ] **IDS-048**: Aprovar budget emergencial ou cancelar iniciativa

### PARA ISSUES AMARELAS:
1. [ ] Daily check-in até resolução
2. [ ] Apoio adicional se necessário
3. [ ] Documentar bloqueios

## SISTEMA DE NOTIFICAÇÕES

### CONFIGURADO:
- **7 dias**: Email para owner
- **10 dias**: Email para owner + supervisor
- **14 dias**: Slack para C-Level + War room automático

### WEBHOOKS ATIVOS:
```javascript
// Slack: #l10-alerts
// Email: l10-escalation@grupobrio.com
// SMS: Para issues >R$ 50k impacto
```

## HISTÓRICO DE ESCALAÇÕES

| Semana | Total Issues | Escaladas | Resolvidas pós-escalação |
|--------|--------------|-----------|--------------------------|
| 30/07 | 18 | 3 | 3 (100%) |
| 23/07 | 22 | 5 | 4 (80%) |
| 16/07 | 15 | 2 | 2 (100%) |

---

### LINKS ÚTEIS:
- [Template IDS](../Meetings/L10-templates/ids-template.md)
- [Processo Escalação](./escalation-process.md)
- [War Room Protocol](./war-room-protocol.md)

*Report gerado: 04/08/2025 15:00*
*Próxima atualização: 05/08/2025 09:00*
*Notificações automáticas: ATIVAS ✅*