# OpenRouter Chat

![Versão](https://img.shields.io/badge/versão-2.1-blue)
![Licença](https://img.shields.io/badge/licença-MIT-green)
![Idioma](https://img.shields.io/badge/idioma-Português--BR-yellow)

## 📝 Descrição

OpenRouter Chat é uma interface web moderna e intuitiva para interação com modelos de IA através da API OpenRouter. A aplicação permite conversas com diferentes modelos de linguagem (LLMs) diretamente pelo navegador, com suporte completo a formatação Markdown, código, temas claro/escuro e muito mais.

## ✨ Características

### Modelos de IA
- **Modelos Gratuitos**: 
  - GPT-3.5 Turbo (OpenAI)
  - Llama 3 8B Instruct (Meta)
- **Informações sobre Modelos Premium**: Acesso a informações sobre modelos premium disponíveis via OpenRouter (GPT-4, Claude 3, etc)

### Interface
- **Design Responsivo**: Adapta-se a diferentes tamanhos de tela
- **Tema Claro/Escuro**: Alternância de tema com persistência de preferência
- **Badges Coloridos**: Identificação visual por provedor de modelo (OpenAI, Meta, etc)
- **Indicadores de Digitação**: Animações visuais durante o processamento da resposta
- **Área de texto ajustável**: Expansão automática do campo de entrada

### Formatação e Código
- **Suporte completo a Markdown**: Renderização de formatação de texto, listas, títulos
- **Highlight de Código**: Destacamento de sintaxe para blocos de código
- **Botões de Cópia**: Adição automática de botão "Copiar" em blocos de código

### Histórico e Persistência
- **Histórico por Modelo**: Armazenamento separado de conversas para cada modelo
- **Persistência Local**: Salvamento de conversas no localStorage do navegador
- **Limpeza de Chat**: Opção para limpar histórico atual mantendo outros

### Tratamento de Erros
- **Mensagens Amigáveis**: Exibição de erros de forma compreensível
- **Notificações Toast**: Sistema de notificações para eventos do sistema
- **Detecção de Problemas**: Identificação automática de erros comuns (limite de taxa, autenticação)

## 🚀 Como Usar

1. **Acesso**: Abra o arquivo `index.html` em seu navegador
2. **Escolha do Modelo**: Selecione um dos modelos gratuitos disponíveis
3. **Conversa**: Digite sua mensagem na área de texto e pressione Enter ou clique no botão de enviar
4. **Alternância de Tema**: Utilize o botão de tema (sol/lua) no cabeçalho para alternar entre os modos claro e escuro
5. **Histórico**: O histórico é salvo automaticamente no navegador e pode ser limpo com o botão "Limpar"

## 🔧 Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Bibliotecas**:
  - Bootstrap 5 (interface responsiva)
  - Font Awesome (ícones)
  - Highlight.js (destacamento de código)
  - Marked (processamento de Markdown)
- **API**: OpenRouter (https://openrouter.ai)

## ⚙️ Requisitos Técnicos

- Navegador moderno com suporte a ES6+ (Chrome, Firefox, Safari, Edge)
- Conexão com internet para comunicação com a API OpenRouter
- Chave de API OpenRouter (configurada diretamente no código)

## 🔒 Segurança e Privacidade

- As conversas são armazenadas apenas localmente no navegador do usuário
- A chave de API é definida no código-fonte para facilitar o uso
- Para ambientes de produção, recomenda-se implementar armazenamento mais seguro para a chave API

## ⚠️ Limites de Uso dos Modelos

Embora os modelos marcados como "gratuitos" sejam disponibilizados sem custo financeiro, eles possuem limitações:

- **Cota diária/mensal**: A OpenRouter oferece uma cota gratuita limitada (geralmente cerca de $1-2/mês em créditos)
- **Limites de taxa (rate limits)**: Os modelos gratuitos têm limites no número de solicitações por minuto
- **Tamanho de contexto**: Limite no número de tokens (palavras/caracteres) que podem ser processados por conversa
- **Prioridade**: Solicitações gratuitas podem ter prioridade menor nos horários de pico

Quando a cota gratuita é atingida, a API retorna um erro "insufficient_quota", que a interface exibe como uma mensagem de erro. Para uso além dos limites gratuitos, é necessário:

1. Criar uma conta na [OpenRouter](https://openrouter.ai)
2. Adicionar créditos à conta
3. Utilizar sua própria chave API no aplicativo

**Nota:** Os limites exatos podem mudar com o tempo conforme a política da OpenRouter.

## 📋 Implementações Futuras

- Suporte a upload de arquivos
- Integração com mais provedores de modelos
- Sistema de configuração avançada com interface administrativa
- Exportação e importação de conversas
- Otimização para dispositivos móveis

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para detalhes.

---

Desenvolvido por Marco Porto © 2025