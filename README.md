# 🤖 uArm Swift Pro - Controlador Android

Um aplicativo Android nativo desenvolvido em Kotlin para fornecer uma interface de controlo sem fios, rápida e intuitiva para o braço robótico **uArm Swift Pro**. 

Este projeto substitui interfaces complexas por um ecrã de controlo simplificado, focado na comunicação Bluetooth de baixa latência e preparado para futura integração IoT (Internet of Things) através do ecossistema Firebase.

---

## 🎯 Objetivo do Projeto
O objetivo desta aplicação é permitir que os utilizadores enviem comandos de movimento precisos para o uArm Swift Pro diretamente de um smartphone Android. Foi desenhado para ser leve, removendo visualizações de câmara desnecessárias e botões redundantes, focando-se estritamente na estabilidade da conexão e na execução de movimentos.

## ✨ Funcionalidades Detalhadas

* **📡 Gestão de Conexão Bluetooth:** 
  * Emparelhamento seguro com o módulo Bluetooth do uArm.
  * Feedback visual em tempo real do estado da conexão no ecrã (Ex: `🟡 Conectando...` / `🟢 Conectado` / `🔴 Desconectado`).
* **🕹️ Controlo de Movimento Simplificado:** 
  * Interface limpa (Clean UI) contendo apenas os controlos essenciais para operar a máquina, evitando toques acidentais.
  * Envio de pacotes de dados formatados que o microcontrolador do uArm consegue interpretar instantaneamente.
* **☁️ Infraestrutura IoT (Em Desenvolvimento):**
  * Integração nativa com o **Firebase**. 
  * Preparado para sincronização de dados na nuvem, permitindo futuramente que os comandos sejam registados num banco de dados em tempo real ou controlados via scripts em Python.

---

## 🛠 Tecnologias e Arquitetura

* **Linguagem Principal:** Kotlin
* **Interface de Utilizador (UI):** XML (Layouts simplificados com foco na usabilidade)
* **Ferramenta de Desenvolvimento:** Android Studio
* **Configuração de Build (Gradle):** 
  * `compileSdk 35` (Garante compatibilidade total com as bibliotecas mais recentes e regras de AAR metadata).
* **Dependências de Nuvem:** Serviços Google (Firebase Realtime Database)
* **Controlo de Versões:** Git / GitHub

---

## 📋 Pré-requisitos

Para clonar e editar este projeto na sua própria máquina, irá precisar de:
1. **Android Studio** (Versão mais recente recomendada, Iguana ou superior).
2. **SDK do Android** atualizado para a API 35 (Android 15).
3. Um dispositivo físico Android (telemóvel ou tablet) com o Bluetooth ativado para testar a comunicação com o robô (emuladores de computador não suportam conexões Bluetooth reais).
4. O braço robótico **uArm Swift Pro** ligado e com o módulo Bluetooth ativado.

---

## 🚀 Como Executar o Projeto

1. Faça o clone deste repositório para a sua máquina local:
   ```bash
   git clone [https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git](https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git)
