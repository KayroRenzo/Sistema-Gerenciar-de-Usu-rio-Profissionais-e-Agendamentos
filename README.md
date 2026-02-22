# 🏥 NAPE - Núcleo de Atendimento Pedagógico Especializado

![Banner NAPE](https://via.placeholder.com/1200x300/2d5a8c/ffffff?text=NAPE+-+Sistema+de+Gestão+Especializada)

> Sistema completo para gestão de atendimentos pedagógicos especializados, desenvolvido com foco em usabilidade, segurança e eficiência.

[![PHP Version](https://img.shields.io/badge/PHP-8.0%2B-777BB4?style=for-the-badge&logo=php)](https://php.net)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql)](https://mysql.com)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)

## 📋 Sobre o Projeto

O NAPE é uma plataforma desenvolvida para otimizar a gestão de atendimentos pedagógicos especializados, oferecendo ferramentas completas para coordenadores, profissionais e atendentes. Com uma interface intuitiva e recursos robustos, o sistema facilita o acompanhamento de pacientes, profissionais e agendamentos.

## ✨ Funcionalidades Principais

### 👤 Gestão de Usuários (Pacientes)
- Usuários vinculados a profissionais
- **Dados Completos dos Usuários**:
  - Nome, número do prontuário e situação
  - Nome do pai, nome da mãe e data de nascimento
  - Diagnóstico, possui laudo, quantidade de terapias, multiprofissional
  - Zona (Urbana/Rural) e endereço completo
  - Quais profissionais ele passa
- Visualização completa de dados
- Geração de PDF com todas as informações do usuário

### 👨‍⚕️ Gestão de Profissionais
- **Controle de Permissões**:
  - 👑 **Coordenador**: Acesso total ao sistema
  - 👤 **Profissional**: Acesso aos próprios usuários
  - 🤝 **Atendente**: Acesso auxiliar para gestão de usuários/agendamentos
- **Dados Profissionais**:
  - Nome, cargo e contato
  - Email e vínculo
  - Endereço completo
  - Data de nascimento e CPF

### 📅 Sistema de Agendamentos
- Agendamentos vinculados a profissionais e pacientes
- **Dados dos Agendamentos**:
  - Data e hora
  - Tipo de atendimento (Mensal, Quinzenal, Semanal)
- Visualização completa dos dados do usuário vinculado
- Geração de PDF com informações do agendamento

### 📊 Recursos Adicionais
- **Lista de Espera** - Gerenciamento de usuários aguardando atendimento
- **Equipe NAPE** - Visualização completa da equipe
- **Dados Pessoais** - Área individual para cada profissional
- **Usuários Gerais** - Visão completa de todos os usuários do sistema

## 🛠️ Tecnologias Utilizadas

### Backend
- **PHP** - Lógica de negócio e implementação de segurança
- **SQL** - Consultas otimizadas e gerenciamento do banco de dados relacional
- **PDO (PHP Data Objects)** - Camada de abstração para acesso seguro ao banco de dados
- **Hash de Senhas** - Criptografia robusta para proteção de dados sensíveis
- **Prevenção contra SQL Injection** - Implementação de consultas parametrizadas e validação rigorosa de inputs

### Frontend
- **HTML5** - Estrutura semântica e acessível
- **CSS3** - Estilização moderna, responsiva e design system personalizado
- **JavaScript** - Interatividade e dinamismo nas interfaces
- **AJAX** - Requisições assíncronas para melhor performance e experiência do usuário, sem recarregamento de páginas

## 👨‍💻 Minhas Contribuições no Projeto

Atuei de forma estratégica no desenvolvimento, com responsabilidades divididas entre **Back-end** e **Front-end**:

### 🔧 Back-end (100% do projeto)
**Responsável por toda a arquitetura e lógica do servidor:**

- ✅ Desenvolvimento **completo** da lógica de negócio com **PHP**
- ✅ Modelagem e otimização de todas as consultas **SQL** para garantir performance e segurança
- ✅ Implementação de **PDO** com prepared statements para prevenir SQL Injection em todo o sistema
- ✅ Sistema de **hash de senhas** para proteção dos dados dos profissionais
- ✅ Criação de APIs internas para comunicação eficiente com o front-end
- ✅ Estruturação da camada de segurança e autenticação por níveis de acesso (coordenador, profissional, atendente)
- ✅ Desenvolvimento de toda a lógica de CRUD para usuários, profissionais e agendamentos

### 🎨 Front-end (50% do projeto)
**Responsável pelo desenvolvimento de interfaces estratégicas:**

- ✅ Desenvolvimento das telas:
  - **📋 Dados Pessoais** - Interface para profissionais visualizarem e gerenciarem seus dados
  - **👥 Usuários Gerais** - Visualização completa de todos os usuários do sistema com design intuitivo
  - **👪 Equipe NAPE** - Visualização completa da equipe com design moderno e responsivo
  - **⏳ Lista de Espera** - Gerenciamento intuitivo de pacientes aguardando atendimento
- ✅ Implementação de **requisições AJAX** para tornar o site mais dinâmico e responsivo
- ✅ Criação de interfaces fluidas que proporcionam melhor experiência ao usuário
- ✅ Integração perfeita entre front-end e back-end via chamadas assíncronas
- ✅ Desenvolvimento de componentes reutilizáveis e design consistente

### 🚀 Impacto das Minhas Contribuições

| Área | Contribuição | Impacto |
|------|--------------|---------|
| **Back-end** | 100% do desenvolvimento | Base sólida, segura e escalável para todo o sistema |
| **Front-end** | 50% das interfaces | Experiência do usuário aprimorada com design moderno |
| **Segurança** | Implementação completa | Proteção contra SQL Injection e dados criptografados |
| **Performance** | Consultas otimizadas + AJAX | Site rápido com atualizações em tempo real |

### ✨ Diferenciais Técnicos Implementados
- **🏗️ Arquitetura Robusta** - Site com estrutura bem definida e escalável
- **⚡ Experiência Dinâmica** - Atualizações em tempo real sem refresh de página via AJAX
- **🔒 Código Seguro** - Implementação seguindo as melhores práticas de desenvolvimento web
- **📱 Design Responsivo** - Interfaces adaptadas para diferentes dispositivos
- **🔄 Integração Perfeita** - Comunicação fluida entre front-end e back-end
