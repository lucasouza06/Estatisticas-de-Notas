
# 🧮 Sistema de Cálculo de Notas em C

Este projeto é um programa simples e funcional desenvolvido em **linguagem C**, cujo objetivo é **calcular a média** e **identificar a maior nota** entre um conjunto de notas inseridas pelo usuário.

---

## 📌 Funcionalidades

✅ Solicita ao usuário quantas notas deseja inserir (entre 1 e 10)  
✅ Realiza validação da entrada para garantir a quantidade correta  
✅ Recebe as notas e as armazena em um vetor  
✅ Calcula a média das notas  
✅ Determina a maior nota  
✅ Exibe os resultados formatados

---

## 📂 Estrutura do Código

O programa está dividido em três partes principais:

### 1. **Função `calcularMedia`**
Calcula a média aritmética das notas:

```c
float calcularMedia(float notas[], int quantidade) {
    float soma = 0;
    for (int i = 0; i < quantidade; i++) {
        soma += notas[i];
    }
    return soma / quantidade;
}
```

---

### 2. **Função `encontrarMaior`**
Identifica a maior nota do vetor:

```c
float encontrarMaior(float notas[], int quantidade) {
    float maior = notas[0];
    for (int i = 1; i < quantidade; i++) {
        if (notas[i] > maior) {
            maior = notas[i];
        }
    }
    return maior;
}
```

---

### 3. **Função `main`**
Realiza a interação com o usuário e exibe os resultados:

- Solicita a quantidade de notas
- Valida o valor informado
- Coleta as notas
- Exibe média e maior nota

---

## 🧠 Requisitos de Conhecimento

Para entender completamente o programa, é recomendável conhecer:

- Vetores em C
- Funções
- Estrutura de repetição `for`
- Entrada e saída com `scanf` e `printf`

---

## 🎓 Aplicações Educativas

Este projeto é ideal para:

- Exercícios introdutórios de programação em C
- Atividades práticas em disciplinas como Lógica de Programação, Algoritmos ou Estrutura de Dados
- Demonstração de manipulação básica de vetores e funções

---

## 🤝 Contribuição

Sinta-se à vontade para fazer um fork e propor melhorias!
---
