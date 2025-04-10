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

Digite a nota do 1º semestre: 6.5 Digite a nota do 2º semestre: 7.8 Digite o total de aulas: 60 Digite quantas aulas você assistiu: 54

Média final: 7.3 Frequência: 90.0% Resultado: Aprovado ✅

## 🧑‍💻 Autor

**Matheus Moya Oliveira**  
[LinkedIn](https://www.linkedin.com/in/matheusmoyaoliveira/) | [GitHub](https://github.com/matheusmoyaoliveira)

## 🚀 Tecnologias

- Python 3

## 📁 Como executar

1. Clone este repositório:
```bash

git clone https://github.com/matheusmoyaoliveira/calculadora-media-frequencia.git

cd calculadora-media-frequencia

python main.py
