# ProjetoJS_LuxoAlugueldeiates
Site de aluguel de iates com área administrativa e gestão de mensagens. Projeto de Front-End 2 com implementação de API simulada via LocalStorage.


# ⚓ Luxo - Aluguel de Iates Exclusivos

> Projeto desenvolvido para a disciplina de Front-End 2.
> Um sistema web que une uma interface institucional de luxo a um painel administrativo funcional para gestão de contatos.

---

## 📋 Sobre o Projeto

Este projeto simula o site de uma agência de aluguel de iates de alto padrão. O objetivo principal foi realizar a **implementação** da comunicação entre o formulário de contato (público) e um painel de controle (restrito), utilizando **JavaScript** e **LocalStorage** para simular uma API e persistência de dados.

### 🌟 Funcionalidades Implementadas

#### 1. Área Pública (Cliente)
* **Vitrine de Iates:** Apresentação da frota e serviços.
* **Destinos (Curadoria):** Página exclusiva com recomendações de viagens.
* **Formulário de Contato:** Captura de Nome, E-mail e Mensagem.
* **Validação:** Verificação de campos obrigatórios antes do envio.

#### 2. Área Administrativa (Restrita)
* **Login de Segurança:** Acesso protegido por e-mail e senha.
    * 📧 **Login:** `admin@luxo.com`
    * 🔑 **Senha:** `1234`
* **Gestão de Mensagens:**
    * Listagem de todas as mensagens recebidas.
    * **Status Visual:** Mensagens não lidas aparecem em **negrito**; lidas ficam em texto normal.
    * **Ações:** Botões funcionais para "Marcar como Lida" e "Excluir" (com confirmação).

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica das páginas.
* **CSS3:** Design responsivo e estilização visual.
* **JavaScript (ES6):** Lógica completa de validação e controle.
* **jQuery:** Manipulação do DOM e eventos de clique.
* **LocalStorage:** Armazenamento das mensagens no navegador (Simulação de Backend).

---

## 📂 Estrutura de Arquivos

A organização do projeto segue a estrutura solicitada:

```text
Projeto-Luxo-Iates/
│
├── index.html          # Página Inicial
├── aluguel.html        # Frota
├── destinos.html       # Destinos Turísticos
├── tripulacao.html     # Equipe
├── contato.html        # Formulário de Envio
├── admin.html          # Login Admin
├── mensagens.html      # Dashboard Admin
│
├── css/
│   └── default.css     # Estilização Global
│
├── js/
│   ├── jquery-3.6.4.min.js  # Biblioteca Base
│   ├── api.js               # Lógica de Dados (Implementada)
│   └── functions.js         # Eventos de Tela (Implementada)
│
└── images/             # Imagens do projeto



✒️ Autores
Professor / Base do Projeto: Gláucio Rocha

Implementação Final: Alyere Targino

Curso: Front-End 2 - 2025.2
