# PRD — Gestão Devoto Construtor

## Origem
Projeto carregado do repositório público https://github.com/psjttatuape-design/devoto-construtor (Abril/2026).
Sistema de gestão de dízimos da Paróquia São Judas Tadeu (Tatuapé - SP).

## Stack
- Backend: FastAPI + MongoDB (motor) + JWT (pyjwt) + bcrypt (passlib) + openpyxl
- Frontend: React 19 + Tailwind + Radix UI + React Router 7 + Recharts + Axios + Sonner

## Credenciais padrão
- admin / admin123 (criado automaticamente no startup do backend)

## Funcionalidades existentes
- Autenticação JWT com permissões granulares
- CRUD de Dizimistas, Contribuições, Valores Mensais, Usuários
- Importação/Exportação Excel de dizimistas (template, import, export com filtros)
- Relatórios com filtros (período, status, nota)
- Dashboard com resumos e filtros (status/nota/mês de contribuição)
- Sincronização contribuições -> valores mensais

## O que foi feito nesta sessão (Abril/2026)
- Repositório público carregado em /app preservando .git, .emergent e .env protegidos
- Dependências instaladas (pip + yarn)
- Serviços backend e frontend reiniciados e funcionando
- Login admin/admin123 validado via API (/api/auth/login)

## Backlog (herdado do PRD original)
- P1: Recibo/comprovante PDF
- P1: Gráficos avançados (evolução mensal, ranking)
- P2: Notificações/lembretes WhatsApp (Twilio)
- P2: Mensagens de aniversário
- P2: PIX QR Code
- P2: Backup JSON
