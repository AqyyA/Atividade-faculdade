<div align="center">

# 🔥 Tinder

### Conecte-se, descubra novas pessoas e encontre combinações perto de você.

<br>

![Idade](https://img.shields.io/badge/classificação-18%2B-red?style=for-the-badge)


</div>

---

## 📖 Sobre o projeto

O **Tinder** é um aplicativo de relacionamentos baseado em geolocalização. Nele, os usuários podem descobrir pessoas próximas, visualizar perfis e demonstrar interesse por meio de *swipes*.

Quando duas pessoas demonstram interesse mútuo, ocorre um **match**, permitindo que elas iniciem uma conversa pelo chat.

> Este projeto tem como objetivo proporcionar conexões de maneira simples, intuitiva e segura.

## 🎯 Público-alvo

A plataforma é destinada a adultos com **18 anos ou mais** que buscam:
- ❤️ Relacionamentos amorosos;
- 🤝 Novas amizades;
- 💬 Interações sociais;
- 🌐 Networking.

## 👥 Criadores & Fundadores

O Tinder foi concebido e criado dentro da incubadora de startups **Hatch Labs** em 2012 por:

- **Sean Rad:** Co-fundador e primeiro CEO.
- **Justin Mateen:** Co-fundador e ex-Diretor de Marketing (CMO).
- **Jonathan Badeen:** Co-fundador e ex-Diretor de Estratégia (CSO), um dos principais responsáveis pelo desenvolvimento do sistema e mecânica do *swipe*.
- **Whitney Wolfe Herd:** Co-fundadora e ex-Vice-Presidente de Marketing (posteriormente fundou o *Bumble*).
- **Joe Munoz:** Co-fundador e engenheiro responsável pela construção do protótipo inicial (MatchBox).
- **Chris Gulczynski:** Co-fundador e ex-Diretor de Criação (CCO), responsável pelo design e identidade visual inicial.

## 💻 Linguagens e Tecnologias

A arquitetura do Tinder é construída utilizando linguagens e ferramentas focadas em alto desempenho e escalabilidade:

### **Mobile (Frontend)**
- **Swift / Objective-C:** Desenvolvimento nativo para a plataforma iOS.
- **Kotlin / Java:** Desenvolvimento nativo para a plataforma Android.
- **JavaScript / TypeScript (React Native):** Utilizado em componentes multiplataforma e na versão Web.

### **Backend & APIs**
- **JavaScript / Node.js:** Processamento em tempo real (como o sistema de chat e notificações).
- **Java / Go:** Microsserviços de alta performance e algoritmos de recomendação.
- **Python:** Modelos de Machine Learning, processamento de dados e filtros de IA.

### **Scripts & Infraestrutura**
- **Bash / Shell Script:** Automação de pipelines de CI/CD e gerenciamento de infraestrutura em nuvem (AWS).

## ✨ Funcionalidades

| Funcionalidade | Descrição |
|---|---|
| 👤 **Perfil personalizado** | Adicione fotos, uma biografia e informações pessoais |
| 📍 **Descoberta por localização** | Encontre pessoas próximas utilizando geolocalização |
| 👉 **Sistema de swipe** | Demonstre interesse ou avance para o próximo perfil |
| 💞 **Matches** | Combine com pessoas que também demonstraram interesse |
| 💬 **Chat privado** | Converse com seus matches em um ambiente exclusivo |
| 🔍 **Filtros de busca** | Refine os resultados por idade, distância e interesses |
| ✅ **Verificação de perfil** | Aumente a segurança e a confiabilidade dos perfis |
| ⭐ **Recursos premium** | Tenha acesso a Super Like, Boost e outras vantagens |

## 🔄 Como funciona

```mermaid
flowchart LR
    A[👤 Criar perfil] --> B[📍 Ativar localização]
    B --> C[🔎 Descobrir pessoas]
    C --> D[👉 Dar swipe]
    D --> E{💞 Interesse mútuo?}
    E -- Sim --> F[🔥 Match]
    F --> G[💬 Chat liberado]
    E -- Não --> C
