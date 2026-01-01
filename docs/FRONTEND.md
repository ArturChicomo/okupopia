# Chat Inbox System - Documentação Frontend

## 1. Visão Geral
O Chat OKUPOPIA é um sistema de mensagens que permite comunicação em tempo real.
O design das telas foi desenvolvido no [Figma](https://www.figma.com/design/wdUycLgLeIlan0Zj5nuo8i/Chat-Inbox-System).

**Status atual:**
- Código frontend ainda não versionado.
- Design disponível no Figma.
- API simulada online (Kassovita).

---

## 2. Telas / Layouts

### Tela Login
- Campos: Email, Password
- Botão: Entrar
- Observações: Validar campos antes de enviar para API
- Figma: Tela 1

### Tela Lista de Conversas
- Mostra todas as conversas do usuário
- Seleção de conversa abre o chat correspondente
- Figma: Tela 2

### Tela Chat
- Mostra mensagens em tempo real
- Campo para enviar nova mensagem
- Botões de ação: Enviar
- Figma: Tela 3

### Tela Perfil / Configurações
- Visualização de perfil do usuário
- Editar informações e configurações da conta
- Figma: Tela 4

---

## 3. Funcionalidades principais
- Autenticação de usuário (via API simulada)
- Listagem de conversas
- Envio e recebimento de mensagens
- Atualização de perfil
- Design responsivo (desktop / mobile)

---

## 4. Fluxo de navegação
```text
Login -> Lista de Conversas -> Chat -> Perfil
