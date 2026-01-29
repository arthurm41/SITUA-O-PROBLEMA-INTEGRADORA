# Semaforo_Inteligente

# 🚦 Cruzamento 4.0 – Semáforo Inteligente

## 📌 Objetivo
Desenvolver uma solução mínima viável (MVP) para um cruzamento inteligente,
utilizando IoT, algoritmos adaptativos e boas práticas de segurança e versionamento.

## 🧠 Descrição da Solução
O sistema monitora o fluxo de veículos, condições climáticas e estado dos sensores
para ajustar dinamicamente os tempos do semáforo, garantindo segurança e fluidez
no trânsito mesmo em situações de falha.

## 📋 Requisitos
### Funcionais
- Ajustar tempo do semáforo conforme fluxo
- Detectar chuva intensa
- Ativar modo de segurança em falha de sensor
- Operar localmente em caso de queda do servidor
- Enviar dados via MQTT

### Não Funcionais
- Alta disponibilidade
- Segurança na comunicação
- Tempo de resposta inferior a 2s
- Código limpo e modular
- Uso de software livre

## 🏗 Arquitetura IoT
- Sensores de fluxo, chuva e luminosidade
- Controlador IoT (ESP32 – conceitual)
- Comunicação MQTT
- Servidor local Linux
- Topologia híbrida (Mesh + Cliente-Servidor)

📷 *Diagrama disponível em /docs*

## 🔐 Sistema Operacional e Segurança
- SO escolhido: Ubuntu Server
- Firewall configurado (porta 1883 – MQTT)
- Controle de usuários e permissões
- Política de Segurança da Informação (PSI)

## 🔄 Algoritmo do Semáforo
- Estruturas condicionais e repetição
- Vetores para armazenar fluxo
- Modo de segurança (pisca amarelo)
- Clean Code

📄 Código disponível em `/algoritmo`

## 🖥 Evidências
- Prints das VMs em `/vm`
- Fluxograma em `/docs`

## 👥 Equipe
Projeto desenvolvido para a disciplina do SENAI – DEVT26
