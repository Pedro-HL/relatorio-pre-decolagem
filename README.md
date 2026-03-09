# Relatório Operacional de Pré-Decolagem

Projeto acadêmico desenvolvido para simular um sistema automatizado de verificação pré-decolagem baseado em dados de telemetria aeroespacial.

---

## Objetivo

Construir um sistema capaz de:

- Interpretar dados de telemetria
- Verificar parâmetros críticos
- Decidir automaticamente:
  - PRONTO PARA DECOLAR
  - DECOLAGEM ABORTADA
- Realizar análise energética
- Identificar possíveis riscos operacionais

---

##  Parâmetros Monitorados

- Temperatura interna e externa
- Integridade estrutural (0/1)
- Nível de energia (%)
- Pressão dos tanques
- Status dos módulos críticos

---

##  Lógica do Sistema

O sistema utiliza Programação Orientada a Objetos (POO) em Python para:

1. Validar cada parâmetro individualmente
2. Consolidar as verificações
3. Gerar relatório detalhado
4. Emitir decisão final baseada em faixas seguras predefinidas

---

## Análise Energética

O projeto calcula:

- Energia disponível (kWh)
- Perdas energéticas estimadas
- Energia restante após decolagem
- Autonomia operacional

---

##  Tecnologias Utilizadas

- Python 3
- Jupyter Notebook
- Programação Orientada a Objetos
- Estruturas condicionais
- Funções modulares
