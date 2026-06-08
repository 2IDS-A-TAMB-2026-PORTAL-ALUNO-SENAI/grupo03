# 🏫 Portal do Aluno SENAI - Sistema de Acessibilidade

Este é um projeto amador de um **Portal do Aluno para o SENAI**, desenvolvido com foco total em **Acessibilidade Web**. O objetivo principal foi criar uma interface simples, bonita e totalmente adaptável para usuários com diferentes necessidades visuais e auditivas.

---

## 🚀 O que o projeto faz? (Funcionalidades)

* **🌐 Componente de LIBRAS Integrado:** O site possui um botão flutuante com o símbolo internacional da surdez. Ao clicar nele, o assistente virtual do **VLibras** é ativado automaticamente para traduzir os textos da tela para a Língua Brasileira de Sinais.
* **🌓 Alto Contraste Inteligente:** Um botão que transforma o site inteiro no padrão Preto e Branco (fundo preto e letras/bordas 100% brancas), garantindo leitura perfeita para pessoas com baixa visão.
* **🔍 Controle de Zoom Dinâmico (A+ / A-):** Botões diretos no menu que aumentam ou diminuem o tamanho de absolutamente todos os elementos do site de forma proporcional, sem quebrar o layout.
* **🔔 Alertas Modernos (SweetAlert2):** Quando o aluno clica em "Realizar Cadastro", o site exibe uma janela de confirmação bonita e interativa antes de mudar de página.
* **🔗 Sistema de Navegação Simples:** Links configurados para alternar perfeitamente entre a página inicial (`index.html`) e a página de cadastro (`formulario.html`).

---

## 🛠️ Tecnologias Utilizadas

Para não precisar baixar um monte de arquivos para o computador, o projeto usa links diretos (CDNs) das tecnologias mais conhecidas do mercado:
* **HTML5 & CSS3** (Estrutura e estilização básica)
* **Bootstrap 5** (Para deixar o site alinhado e responsivo no celular)
* **FontAwesome 6.5.1** (Para os ícones bonitinhos dos cards)
* **SweetAlert2** (Para as janelas de aviso modernas)
* **Plugin Oficial VLibras** (Para a tradução em libras)
* **JavaScript Vanilla** (Para fazer os botões de zoom, contraste e links funcionarem)

---

## Integrantes do Projeto4️⃣
* Bruno Donizetti
* Sopha Peron
* Lorrano
* Paula ZIto

---

## 📂 Estrutura das Páginas

Para o site funcionar certinho, os arquivos devem estar salvos dentro da **mesma pasta** com os seguintes nomes:

```text
📁 portal-senai/
│
├── 📄 index.html        <-- Página principal (Portal do Aluno)
├── 📄 formulario.html   <-- Página com o formulário de cadastro
└── 🖼️ image_a70242.png  <-- Imagem do ícone de libras (opcional)



