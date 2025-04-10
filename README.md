# 📘 Calculadora de Média com Frequência

Projeto simples em Python que simula o cálculo da média final de um aluno com base nas notas semestrais e na frequência em aula, determinando se o aluno está **aprovado**, **em exame** ou **reprovado**.

## 💡 Objetivo
Consolidar os conhecimentos iniciais de lógica de programação, uso de `input`, `if`, `elif`, `else`, operadores matemáticos e tratamento de condições múltiplas.

## 🔧 Funcionalidades

- Leitura das duas médias semestrais
- Cálculo ponderado com pesos (4 e 6)
- Verificação da porcentagem de frequência
- Exibição do status final:
  - ✅ Aprovado
  - ❗ Em exame
  - ❌ Reprovado (nota ou falta)

## 🧠 Regras de aprovação

| Média Final | Frequência | Resultado   |
|-------------|------------|-------------|
| ≥ 6.0       | ≥ 70%      | Aprovado    |
| 4.0 a 5.9   | ≥ 70%      | Exame       |
| < 4.0       | qualquer   | Reprovado   |
| qualquer    | < 70%      | Reprovado   |

## 🖥️ Exemplo de uso

