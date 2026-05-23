# THYMOS — Sistema Estratégico Premium

![THYMOS Version](https://img.shields.io/badge/Vers%C3%A3o-2.0--Premium-c9a84c?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Pronto%20para%20Produ%C3%A7%C3%A3o-success?style=for-the-badge)

O **THYMOS — Sistema Estratégico Premium** é uma interface de alta performance e design minimalista desenvolvida para a coleta centralizada de dados operacionais, alinhamento de branding, logística avançada, marketing e ativos digitais da marca.

Esta solução consolida um ecossistema inteligência de negócios através de um formulário fluído dividido em 8 seções estratégicas, totalizando uma triagem ultra detalhada (incluindo mais de 21 perguntas dedicadas à infraestrutura logística e frete).

---

## 🚀 Funcionalidades Principais

* **Arquitetura Serverless (Sem Backend):** Integração nativa e segura com a API do **Web3Forms**, roteando todas as submissões diretamente para o SMTP configurado sem expor credenciais sensíveis no client-side.
* **Seção de Logística Ultra Premium:** Mapeamento completo contendo 21+ pontos de auditoria operacional (prazos, transportadoras, capacidade de armazém, política de trocas e modelo de fulfillment).
* **Interface Fluída e Responsiva:** Estilização escura premium com acentuações em dourado (`#c9a84c`), tipografia refinada (Playfair Display & Inter) e efeitos visuais baseados em `IntersectionObserver` (Scroll Reveal).
* **Persistência de Dados Local (Auto-Save):** Utilização de `localStorage` para salvar o progresso do usuário em tempo real, prevenindo a perda de dados caso a página seja recarregada.
* **Validação e Upload de Arquivos:** Sistema Drag & Drop inteligente com limitação estrita de segurança para arquivos até 10MB.
* **Rastreamento e Analytics Integrado:** Estrutura pronta para acoplamento do Google Analytics (Gtag) e Meta Pixel para monitoramento de conversão.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5** (Estrutura semântica por seções)
* **CSS3** (Variáveis nativas, Grid/Flexbox Layout, Efeitos de vidro com `backdrop-filter`, Animações customizadas)
* **JavaScript Assíncrono (Vanilla JS)** (Manipulação de DOM, API Fetch, LocalStorage, Intersection Observer)
* **Web3Forms API** (Gateway seguro para processamento de formulários por e-mail)

---

## ⚙️ Configuração e Instalação

Como o sistema é construído inteiramente sobre tecnologias nativas do navegador (Front-End), não há necessidade de instalar dependências complexas ou servidores Node/PHP.

1. Clone ou baixe o arquivo HTML do projeto.
2. Abra o código e localize as tags de integração do **Web3Forms**:
   ```html
   <input type="hidden" name="access_key" value="3bce0b14-787a-414f-b0de-8799f08ff8ec" />
