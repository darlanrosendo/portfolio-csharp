# Portfólio C# | Darlan Rosendo

Bem-vindo ao meu portfólio de projetos desenvolvidos em **C# e .NET**!

Este repositório reúne meus projetos práticos, aplicações desktop e estudos de desenvolvimento de software, demonstrando minha evolução e os conhecimentos adquiridos ao longo da minha jornada como desenvolvedor.

## Tecnologias e conhecimentos

- C# e .NET
- Windows Forms
- Programação orientada a objetos
- LINQ
- Coleções e estruturas de dados
- Desenvolvimento de interfaces desktop
- Git e GitHub

---

## Meus projetos

### 01 — Gráficos Interativos | Windows Forms

Aplicação desktop desenvolvida em C# para criação e personalização de gráficos interativos.

**Funcionalidades:**
- Inserção e atualização de valores X e Y.
- Visualização dos dados em tabela.
- Diferentes tipos de gráficos.
- Personalização das paletas de cores.
- Visualização em 3D.
- Geração automática de dados aleatórios.

![Gráfico de pizza em 3D](https://raw.githubusercontent.com/darlanrosendo/csharp-windows-forms-graficos/master/screenshots/grafico-pizza-3d.png)

**[Ver código-fonte e documentação do projeto](https://github.com/darlanrosendo/csharp-windows-forms-graficos)**

---



### 02 — Chat TCP em Tempo Real | Windows Forms

Aplicação de chat com servidor e cliente desktop, desenvolvida em C# usando sockets TCP e threads.

![Servidor e clientes conversando](https://raw.githubusercontent.com/darlanrosendo/chat-tcp-csharp/main/docs/chat-funcionando.jpg)

**Funcionalidades:**

- Servidor que atende vários clientes ao mesmo tempo (uma thread por cliente).
- Mensagens enviadas para todos os usuários conectados.
- Avisos de entrada e saída de usuários.
- Bloqueio de nomes repetidos e do nome reservado "Administrador".
- Log do servidor com horário de cada evento.
- Encerramento organizado: ao fechar o servidor, os clientes são avisados sem travar.

**O que aprendi e apliquei:**

- Comunicação em rede com `TcpListener` e `TcpClient`.
- Programação com múltiplas threads e controle de concorrência com `lock`.
- Atualização segura da interface a partir de outras threads (`BeginInvoke`).
- Tratamento de erros de rede para que a falha de um cliente não derrube o servidor.
- Refatoração de código: correção de loop infinito, remoção de duplicação e melhoria de nomes.

🔗 **Repositório:** [chat-tcp-csharp](https://github.com/darlanrosendo/chat-tcp-csharp)

---


## Sobre mim

Sou Darlan Rosendo, desenvolvedor em constante aprendizado e aprimoramento profissional.

Utilizo este espaço para compartilhar projetos, aplicar meus conhecimentos e documentar minha evolução no desenvolvimento de software.

## Contato

**GitHub:** https://github.com/darlanrosendo

---

*Portfólio em constante evolução. Novos projetos serão adicionados conforme forem desenvolvidos e publicados.*
