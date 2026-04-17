# PRD - Gestão Devoto Construtor (Dizimo)

## Origem
Projeto clonado de https://github.com/psjttatuape-design/Dizimo.git em Jan/2026.

## Objetivo
Sistema de gestão de dízimos da Paróquia São Judas Tadeu (Tatuapé - São Paulo), agora renomeado para "Gestão Devoto Construtor".

## Stack
- Backend: FastAPI + MongoDB (motor) + JWT + openpyxl
- Frontend: React 19 + Tailwind + Radix UI + React Router 7 + Recharts

## Credenciais padrão
- admin / admin123

## Funcionalidades existentes
- Autenticação JWT com permissões granulares
- CRUD de Dizimistas, Contribuições, Valores Mensais, Usuários
- Importação/Exportação Excel de dizimistas
- Relatórios com filtros (período, status, nota)
- Dashboard com resumos

## Alterações realizadas nesta sessão (Jan/2026)
- Projeto clonado do GitHub e integrado em /app
- Dependências instaladas (openpyxl, passlib, bcrypt, pyjwt, python-jose, python-multipart)
- Renomeação do sistema:
  - "Sistema de Gestão de Dízimos" → "Gestão Devoto Construtor" (tela de login)
  - Sidebar: "Gestão de Dízimos" → "Gestão Devoto Construtor"
  - Título da aba (index.html): "Emergent | Fullstack App" → "Gestão Devoto Construtor"

## Backlog / Próximas funcionalidades sugeridas
- P1: Recibo/comprovante PDF
- P1: Gráficos avançados (evolução mensal, ranking)
- P2: Notificações/lembretes WhatsApp (Twilio)
- P2: Mensagens de aniversário
- P2: PIX QR Code
- P2: Backup JSON
