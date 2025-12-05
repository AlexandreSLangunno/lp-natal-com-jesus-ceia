# Plataforma de Engajamento para Doadores - Natal com Jesus 🎄

> **Projeto Acadêmico de Extensão** | Curso: Ciência da Computação - Centro Universitário Alves Faria (UniALFA)  
> **Disciplina:** Gestão de Projetos  
> **Cliente/Parceiro:** OSCEIA (Obras Sociais do Centro Espírita Irmão Áureo)

![Status do Projeto](https://img.shields.io/badge/Status-Concluido-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## 📄 Visão Geral do Projeto

### O Problema
A ONG enfrenta dificuldades em manter contato com doadores de campanhas passadas. Atualmente, a cada nova arrecadação, a organização não consegue acionar sua base de doadores anteriores por não possuir um sistema centralizado para capturar e gerenciar esses dados, perdendo oportunidades de re-engajamento.

### A Solução
Desenvolvimento de uma **Landing Page (Página de Aterrissagem)** responsiva e focada na campanha "Natal Solidário". A página serve como ponto de entrada para novos doadores, apresentando a missão da ONG, capturando intenções de doação e redirecionando o usuário para um contato direto via WhatsApp, garantindo a captura dos dados (Lead) e o consentimento legal (LGPD).

### Justificativa
Resolver este problema é fundamental para a sustentabilidade financeira da ONG. Criar um canal de comunicação direto permite construir um relacionamento duradouro, transformando doadores pontuais em recorrentes e otimizando o esforço de captação de recursos.

---

## 👥 Partes Interessadas (Stakeholders)

| Função | Nome | Responsabilidade |
| :--- | :--- | :--- |
| **Gestor de Projeto** | Gabriel | Coordenação geral, cronograma e comunicação. |
| **Programador** | Arthur | Desenvolvimento Front-end e lógica JS. |
| **Programador** | Alexandre | Desenvolvimento, integração e ponto de contato. |
| **Designer** | Pedro | Identidade visual e prototipagem. |
| **Assistente Virtual** | Gemini (Google) | Apoio em documentação e geração de código (Pair Programming). |
| **Cliente (ONG)** | Kassia/Alexandre | Validação de requisitos e aprovação final. |
| **Orientador** | Prof. Paulo Palhares | Supervisão acadêmica. |

---

## 📋 Escopo do Projeto

### ✅ O que está no escopo (In-Scope)
* **Landing Page Responsiva:** Compatível com Desktops e Dispositivos Móveis.
* **Seções:** Hero (Banner), Sobre/Missão, Impacto (Contadores) e Formulário.
* **Formulário de Captação:** Coleta de Nome, E-mail, Telefone e Tipo de Doação.
* **Automação WhatsApp:** Redirecionamento automático via API (`wa.me`) com mensagem pré-formatada.
* **Conformidade LGPD:** Checkbox obrigatório de consentimento de dados.
* **Identidade Visual:** Aplicação das cores institucionais da OSCEIA (Verde `#00A758`, Amarelo `#f59e0b`).

### ❌ O que NÃO está no escopo (Out-of-Scope)
* Integração com Gateways de Pagamento (ex: Stripe, PayPal) - Doações são finalizadas via PIX/WhatsApp.
* Sistema de Login/Área do Usuário.
* Painel Administrativo (Backend complexo) - Dados são geridos via contato direto.

---

## ⚙️ Requisitos do Sistema

### Requisitos Funcionais (RF)
* **[RF01]** O sistema deve apresentar um formulário para coleta de Nome, E-mail e Telefone.
* **[RF02]** O sistema deve validar o formato do telefone (máscara).
* **[RF03]** Ao submeter o formulário, o sistema deve redirecionar o usuário para o WhatsApp da ONG com os dados preenchidos.
* **[RF04]** O sistema deve exibir contadores animados de impacto social (cestas doadas).

### Requisitos Não-Funcionais (RNF)
* **[RNF01 - Usabilidade]** A página deve ser responsiva (*mobile-first*).
* **[RNF02 - Legal]** A solução deve estar em conformidade com a LGPD, solicitando consentimento explícito.
* **[RNF03 - Performance]** O carregamento deve ser otimizado utilizando CDNs para estilos e scripts.

---

## 📅 Cronograma e Marcos (GitHub Projects)

O desenvolvimento foi organizado utilizando o método Kanban no GitHub Projects:

**Fase 1: Iniciação**
- [x] Reunião de Kick-off e Alinhamento com a OSCEIA.
- [x] Definição do Termo de Abertura e Escopo.
- [x] Configuração do Repositório.

**Fase 2: Design e Prototipagem**
- [x] Definição da Identidade Visual (Cores e Ativos de Natal).
- [x] Estruturação do Wireframe.

**Fase 3: Desenvolvimento**
- [x] Configuração do ambiente (HTML5 + Tailwind CSS).
- [x] Implementação da Seção Hero e Conteúdo.
- [x] Desenvolvimento do Formulário e Lógica JS (WhatsApp).
- [x] Implementação de Máscaras e Validações.

**Fase 4: Entrega**
- [ ] Testes de Responsividade e QA.
- [ ] Documentação Técnica (README).
- [ ] Deploy (GitHub Pages) e Apresentação Final.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagens:** HTML5, CSS3, JavaScript (ES6+).
* **Framework CSS:** Tailwind CSS (via CDN).
* **Bibliotecas:**
    * Phosphor Icons (Ícones).
    * IMask.js (Máscaras de Input).
* **Ferramentas:** VS Code, Git, GitHub Projects.

---

## 🚀 Como Executar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/AlexandreSLangunno/lp-natal-com-jesus-ceia.git
    ```

2.  **Acesse a pasta:**
    ```bash
    cd lp-natal-com-jesus-ceia
    ```

3.  **Execute:**
    Basta abrir o arquivo `index.html` em qualquer navegador moderno (Chrome, Edge, Firefox).
    > **Nota:** Não é necessária instalação de dependências via npm/node, pois o projeto utiliza CDNs para máxima portabilidade.

---

## 📞 Plano de Comunicação

* **Equipe Interna:** Microsoft Teams (Reuniões Semanais) e GitHub Issues (Assíncrono).
* **Cliente (ONG):** Reuniões quinzenais de validação e contato via WhatsApp para urgências.
* **Entrega:** Apresentação em sala de aula e envio do link do repositório.

---

<p align="center">
  Goiânia, Outubro de 2025 <br>
  Desenvolvido com ❤️ e Código pela equipe de Ciência da Computação - UniALFA.
</p>
