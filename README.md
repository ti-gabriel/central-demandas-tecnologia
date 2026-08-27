# Central de Demandas de Tecnologia

> Case técnico de automação, integração e orquestração de demandas.

Solução desenvolvida para centralizar a abertura, o roteamento automático
e o acompanhamento do ciclo de vida de demandas de Tecnologia.

## Arquitetura

Microsoft Forms
      ↓
Power Automate
      ↓
SharePoint — Roteamento
      ↓
Azure DevOps
      ↓
Work Item
  ↙    ↓    ↘
Teams  E-mail  Central de Tickets
                  ↓
          New → Doing → Done
