# 📊 Calculadora de Custos - API Oficial do WhatsApp (Meta)

Ferramenta interativa desenvolvida para simular e estimar os custos mensais com o envio de mensagens na **API Oficial do WhatsApp**, considerando a tabela tarifária oficial da Meta para o Brasil e a franquia gratuita de mensagens de serviço.

🚀 **Acesse a Calculadora Online:** [https://oviniciuslopes.github.io/calculadorawpp-apioficialmeta/](https://oviniciuslopes.github.io/calculadorawpp-apioficialmeta/)

---

## ⚡ Funcionalidades
- **Cálculo Automático de Franquia:** Abate automaticamente as primeiras 1.000 mensagens de serviço gratuitas do mês.
- **Preenchimento Flexível:** Permite ajustar os volumes usando os *sliders* ou digitando o número exato de mensagens.
- **Atualização em Tempo Real:** Recálculo imediato por categoria (Serviço, Marketing, Utilidade e Autenticação).

---

## 💰 Tabela de Tarifas Aplicada (BRL / Brasil)

| Categoria | Valor por Mensagem | Observações |
| :--- | :--- | :--- |
| **Serviço** | R$ 0,0350 | **Franquia de 1.000 msgs/mês gratuitas** (cobrança apenas sobre o excedente) |
| **Marketing** | R$ 0,3217 | Mensagens ativas/outbound para campanhas e ofertas |
| **Utilidade** | R$ 0,0350 | Notificações transacionais, confirmações e avisos |
| **Autenticação** | R$ 0,0350 | Envio de códigos OTP e verificação de segurança |

---

## 🛠️ Tecnologias Utilizadas
- **HTML5**
- **Tailwind CSS** (via CDN para estilização e responsividade)
- **JavaScript (ES6+)** (lógica dinâmica e formatação de moeda)
- **GitHub Pages** (hospedagem contínua)
