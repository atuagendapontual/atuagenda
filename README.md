# 📅 AtuAgenda

**A agenda para profissionais independentes** — cabeleireiros, esteticistas, barbeiros, técnicas de unhas e muito mais.

Disponível na Google Play Store.

---

## ✨ Funcionalidades

### Agenda
- Calendário mensal com indicadores de dias ocupados
- Agenda hora a hora com blocos livres e ocupados
- Vista semanal e lista de eventos futuros
- Adicionar, editar e apagar compromissos
- Copiar compromisso para outro dia

### 🌐 Agendamento Online *(Premium)*
- Link público personalizado para os clientes marcarem 24/7
- O cliente escolhe o serviço, a data e a hora disponível
- Notificações push instantâneas ao profissional quando chega um pedido
- Aceitar, recusar ou ajustar o horário antes de confirmar
- Email automático de confirmação/recusa enviado ao cliente
- Verificação automática de conflitos com a agenda existente
- Configuração avançada:
  - Horários de funcionamento por dia da semana
  - Duração específica por serviço
  - Pausa configurável entre marcações
  - Limite diário de atendimentos
  - Antecedência mínima para marcações online
  - Dias fechados (feriados, férias, dias especiais)

### Clientes
- Autocomplete com clientes anteriores
- Histórico completo de visitas por cliente
- Nota permanente por cliente
- Ligar, WhatsApp e Instagram diretamente do compromisso

### Serviços
- Lista de serviços personalizável (adicionar, remover, reordenar)
- Duração específica por serviço para agendamento online
- Selecionar múltiplos serviços por compromisso

### Faturação
- Total do dia automático
- Balanço anual com detalhe por mês
- Exportar balanço em PDF e Excel
- Estatísticas avançadas do negócio

### Lembretes
- Lembrete personalizável por compromisso (minutos ou dias antes)
- Notificações nativas Android

### Geral
- Sincronização em tempo real (Firebase Firestore)
- Funciona sem internet após o primeiro login
- Backup e restauro de dados (JSON)
- Modo escuro
- 6 temas de cor (Roxo, Rosa, Verde, Petróleo, Dourado, Grafite)
- Notas rápidas

---

## 💰 Planos

| | Gratuito | Premium Mensal | Premium Anual |
|---|---|---|---|
| Compromissos | 20 (total) | Ilimitados | Ilimitados |
| Agendamento Online | ❌ | ✅ | ✅ |
| Clientes | — | Histórico completo | Histórico completo |
| Balanço anual | ❌ | ✅ | ✅ |
| Exportação PDF/Excel | ❌ | ✅ | ✅ |
| Estatísticas | ❌ | ✅ | ✅ |
| Lembretes | ❌ | ✅ | ✅ |
| Backup | ❌ | ✅ | ✅ |
| **Preço** | **Grátis** | **5,00€/mês** | **48,00€/ano** |

**Premium Mensal:** 5,00€/mês  
**Premium Anual:** 48,00€/ano (equivalente a 4,00€/mês — poupa 12€ por ano)

---

## 🛠️ Tecnologias

- **Frontend:** HTML, CSS, JavaScript (Capacitor)
- **Backend:** Firebase Authentication + Firestore + Cloud Functions (Node.js)
- **Pagamentos:** Google Play Billing (In-App Subscriptions)
- **Notificações:** FCM (Firebase Cloud Messaging) + Capacitor Push Notifications
- **Email:** SendGrid via domínio atuagenda.pt
- **Exportação:** SheetJS (Excel), Print API (PDF)

---

## 📁 Estrutura do Repositório

**atuagenda/**
- `index.html` — App principal (Capacitor WebView)
- `agendar.html` — Página pública de agendamento online
- `privacy.html` — Política de privacidade
- `terms.html` — Termos de utilização
- `delete-account.html` — Página de eliminação de conta
- `favicon.ico` — Ícone do site

---

## 🌐 Website

[atuagendapontual.github.io/atuagenda](https://atuagendapontual.github.io/atuagenda)

---

## 📬 Contacto

Para suporte ou questões: [atuagendapontual@gmail.com](mailto:atuagendapontual@gmail.com)

---

## 📄 Licença

© 2026 AtuAgenda · Todos os direitos reservados.
