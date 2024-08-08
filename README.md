# FlowTrack - Monitoramento de Linhas de Produção

## Visão Geral

FlowTrack é um sistema inovador projetado para monitorar e otimizar as linhas de produção em tempo real, fornecendo dados importantes como taxa de produção, consumo de energia e rastreabilidade das peças. Este projeto é especialmente indicado para a indústrias automotivas que buscam melhorar a eficiência de produção e evitar gastos desnecessários. 

## Objetivo

O principal objetivo do projeto é monitorar, em tempo real, parâmetros essenciais para o funcionamento da linha de produção, como a taxa de produção, tempo de ciclo, velocidade da linha, consumo de energia, consumo de água, rastreabilidade das peças, e análise de desempenho das máquinas.

## Justificativa

Atualmente, é desafiador acessar informações críticas como velocidade da esteira, consumo de energia e rastreabilidade das peças para analisar a eficiência da produção. Além disso, cada equipamento possui um software diferente para realizar essa análise. Este projeto propõe a integração desses softwares em uma única plataforma, permitindo a análise, otimização e automação da linha de produção.

## Funcionalidades Principais

- *Monitoramento em Tempo Real:* Acompanhe a taxa de produção, consumo de energia e outros parâmetros críticos diretamente de um aplicativo móvel ou website.
- *Rastreamento de Peças:* Cadastre e rastreie peças através do sistema, garantindo a visibilidade completa da produção.
- *Controle de Máquinas:* Envie comandos para máquinas e ajuste parâmetros de produção remotamente.
- *Notificações:* Receba alertas em tempo real sobre falhas de sensores e máquinas.
- *Manutenção Preditiva:* Agende manutenções com antecedência para evitar falhas inesperadas.

## Benefícios

- Acesso centralizado a todas as informações dos componentes do chão de fábrica.
- Flexibilidade no ajuste dos parâmetros de produção.
- Redução de custos operacionais e aumento da produtividade.
- Prevenção de falhas e minimização de tempo de inatividade.

## Arquitetura do Sistema

A arquitetura do sistema FlowTrack é baseada em uma estrutura de microserviços, utilizando ferramentas e padrões modernos para garantir escalabilidade, flexibilidade e manutenção. 

### Ferramentas Utilizadas

- *Node-RED:* Integração de dados do chão de fábrica.
- *GitHub:* Controle de versionamento.
- *Discord:* Comunicação interna da equipe.
- *Taiga.io:* Gerenciamento de projetos e backlog

## Requisitos do Projeto

### Funcionais

1. *RU-F1:* Acessar informações pelo aplicativo móvel
2. *RU-F2:* Acessar informações pelo website
3. *RU-F3:* Cadastrar peças no sistema
4. *RU-F4:* Remover peças do sistema
5. *RU-F5:* Cadastrar máquinas no sistema
6. *RU-F6:* Remover máquinas do sistema
7. *RU-F7:* Enviar comandos para as máquinas
8. *RU-F8:* Fornecer interface gráfica intuitiva no website
9. *RU-F9:* Fornecer interface gráfica intuitiva no aplicativo móvel
10. *RU-F10:* Notificação de erros de sensores
11. *RU-F11:* Notificação de erros das máquinas

### Não Funcionais

1. *RU-NF1:* Disponibilidade contínua do sistema
2. *RU-NF2:* Treinamento básico
3. *RU-NF3:* Sistema offline
4. *RU-NF4:* Segurança do sistema
5. *RU-NF5:* Navegador web
6. *RU-NF6:* Sistema operacional
7. *RU-NF7:* Segurança do usuário
8. *RU-NF8:* Filtro de informações
9. *RU-NF9:* Acesso com biometria no aplicativo móvel

## Sprints Planejados

### Sprint 1

- *US1:* Como gerente, quero acessar dados em tempo real via aplicativo móvel (RU-F1, RU-NF2, RU-NF6)
- *US3:* Como engenheiro, quero cadastrar peças no sistema (RU-F3, RS-F1)
- *US4:* Como engenheiro, quero remover peças do sistema (RU-F4, RS-F1)

### Sprint 2

- *US2:* Como gerente, quero acessar dados em tempo real via website (RU-F2, RU-NF5)
- *US5:* Como engenheiro, quero cadastrar máquinas no sistema (RU-F5, RS-F2)

### Sprint 3

- *US6:* Como engenheiro, quero remover máquinas do sistema (RU-F6, RS-F2)
- *US7:* Como gerente, quero enviar comandos para as máquinas (RU-F7, RS-F3, RS-F4)

### Sprint 4

- *US8:* Como usuário da planta, quero uma interface gráfica intuitiva no website (RU-F8, RU-NF2, RU-NF5)
- *US9:* Como usuário da planta, quero uma interface gráfica intuitiva no aplicativo móvel (RU-F9, RU-NF2, RU-NF6)

### Sprint 5

- *US10:* Como técnico de manutenção, quero receber notificações de erros de sensores (RU-F10, RS-F6)

### Sprint 6

- *US11:* Como técnico de manutenção, quero receber notificações de erros das máquinas (RU-F11, RS-F5)
- *US12:* Como gestor de segurança, quero visualizar alertas de segurança na planta (RS-NF9, RS-F9)
