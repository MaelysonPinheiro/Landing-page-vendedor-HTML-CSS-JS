# Landing-page-vendedor-HTML-CSS-JS

# 🚗 VS Aluguel de Carros — Landing Page

Landing page moderna, responsiva e otimizada para conversão da **VS Aluguel de Carros**. O projeto permite que o cliente escolha o local, datas, horários e a categoria do veículo, sendo redirecionado automaticamente para o WhatsApp da unidade responsável (Maranhão ou Santa Catarina) com uma mensagem pré-formatada.

---

## 🌟 Funcionalidades

- **Roteamento Dinâmico por Região:** Identifica se o local escolhido é do Maranhão ou de Santa Catarina e direciona o atendimento para o número de WhatsApp correspondente.
- **Mensagem Personalizada Automática:** Formata os dados do formulário (datas, horários, local e categoria) em uma mensagem inicial de conversa.
- **Validação de Formulário:** Bloqueia seleções de datas passadas e garante que a data de devolução seja posterior à data de retirada.
- **Layout Responsivo:** Otimizado para desktop e dispositivos móveis, com barra de cotação fixa no rodapé para telas menores (*Mobile Sticky Bar*).
- **CSS Estruturado:** Estilos organizados por seções e variáveis globais para facilitar a manutenção.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura semântica do formulário e conteúdo.
- **CSS3:** Flexbox, CSS Grid, Variáveis CSS (`:root`) e Media Queries.
- **JavaScript (Vanilla):** Lógica de validação de datas, verificação de região e integração com a API do WhatsApp (`wa.me`).
- **Google Fonts:** Importação das fontes *Outfit* e *DM Sans*.

---

## ⚙️ Configuração dos Números de WhatsApp

Antes de publicar o projeto, atualize os números de atendimento diretamente no script no final do arquivo HTML:

```javascript
const WHATSAPP_MA = '5598999999999'; // Número da unidade Maranhão (DDI + DDD + Número)
const WHATSAPP_SC = '5547999999999'; // Número da unidade Santa Catarina (DDI + DDD + Número)
