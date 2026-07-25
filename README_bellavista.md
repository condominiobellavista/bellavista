# 🏢 Condomínio Bella Vista — App de Cadastro

**URL:** https://condominiobellavista.github.io/bellavista/

App público para cadastro e acesso dos moradores do Condomínio Bella Vista.

---

## 📱 Funcionalidades

### Tela Inicial
- **Acessar meu cadastro** — login com senha pessoal de 6 dígitos
- **Fazer meu cadastro** — novo cadastro de morador
- **ℹ️ Informações importantes** — manual de acesso e documentos

### Tipos de Cadastro
| Tipo | Descrição |
|------|-----------|
| Proprietário Morador | Dono do apartamento que reside no local |
| Proprietário Não Morador | Dono do apartamento que não reside (locador) |
| Inquilino | Locatário do apartamento |
| Dependente | Familiar do proprietário |
| Dependente (Inquilino) | Familiar do inquilino |
| Serviços → Prestador | Diarista, babá, cuidador etc. (unidades particulares) |
| Serviços → Zeladoria | Zeladora, jardineiro, leiturista etc. (condomínio) |

### Área do Morador (login com senha)
Abas disponíveis após login:
- 👤 **Meus dados** — visualizar e editar dados pessoais
- 🚗 **Veículos** — gerenciar veículos cadastrados
- 👨‍👩‍👧 **Dependentes** — dependentes vinculados ao apartamento
- 🔧 **Prestadores** — prestadores de serviço do apartamento
- 🎉 **Salão** — reservar salão de festas (Piso Inferior ou Superior)
- 🚛 **Mudança** — agendar mudança de entrada ou saída

### Reserva de Salão
- Salão Piso Inferior e Salão Piso Superior
- Taxa: R$ 50,00 por uso
- 1ª reserva do ano: solicitar isenção (aprovação da administração)
- Cancelamento com mínimo 2 dias de antecedência

### Agendamento de Mudança
- Somente segunda a sexta-feira
- Períodos: Manhã (07:30–11:30) ou Tarde (13:00–16:30)
- Máximo 1 mudança por período por dia
- Sábados, domingos e feriados: **proibido**
- Aprovação obrigatória pela administração

### Informações Importantes
- Manual do Sistema de Acesso MIP-1000 IP (Intelbras)
- Regimento Interno do condomínio
- Contato da administração

---

## 🔒 Segurança
- Dados protegidos conforme LGPD (Lei 13.709/2018)
- Rate limiting: bloqueio após 5 tentativas incorretas
- Timeout de sessão: 60 minutos
- Sanitização completa de inputs
- Meta tags de segurança

---

## 🏗️ Estrutura do Condomínio
- **35 apartamentos:** 101–107, 201–207, 301–307, 401–407, 501–507
- **Unidade 100:** Zeladoria (colaboradores do condomínio)

---

## 📬 Contato
condominiobellavistasbs@gmail.com

---

## 🛠️ Tecnologia
- HTML5 / CSS3 / JavaScript puro
- Backend: Google Apps Script + Google Sheets
- Hospedagem: GitHub Pages (gratuito)
- Desenvolvido por Jeferson Wedderhoff com Claude (Anthropic) — Julho/2026
