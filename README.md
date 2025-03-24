# 📝 Atividade Checkpoint 1

## 📆 Entrega
- **Data limite:** 24/03/2025
- **Formato:** grupos de até **3 alunos**
- **Valor:** **0 a 10 pontos**

---

## ✅ Objetivos da Avaliação
Avaliar os seguintes conhecimentos:
- Declaração e uso de variáveis, tipos e operadores.
- Compreensão de estruturas condicionais (`if`, `else`, `switch`).
- Laços de repetição (`for`, `while`, `do-while`).
- Correção de códigos com erros.
- Desenvolvimento de um programa com base nos dados dos integrantes.

---

## 📘 Parte 1: Conceitos (2,0 pontos)
Responda com suas próprias palavras. Justifique com exemplos simples.

1. (0,5 pt) O que são variáveis em C e como são declaradas?
2. (0,5 pt) Explique a diferença entre `if`, `else if`, `else` e `switch`.
3. (0,5 pt) Qual a diferença entre os laços `for`, `while` e `do-while`? Dê um exemplo de cada.
4. (0,5 pt) Para que serve o operador `&` no `scanf()`?

---

## 🛠️ Parte 2: Análise de Código com Erros (3,0 pontos)
Analise os seguintes trechos de código, identifique os erros e reescreva-os corrigidos.

### a) (1,5 pt)
```c
#include <stdio.h>

int main() {
    int idade
    printf("Digite sua idade:");
    scanf("%d", idade);

    if idade >= 18 {
        printf("Maior de idade\n");
    else
        printf("Menor de idade\n");
    return 0;
}
```

### b) (1,5 pt)
```c
#include <stdio.h>

int main() {
    int i;
    for(i = 10; i > 0; i--)
        printf("Valor de i: %d\n")

    return 0
}
```

---

## 💻 Parte 3: Projeto em Grupo (5,0 pontos)

### 📚 Descrição:
Desenvolva um programa em linguagem C que:
1. Permita o cadastro de até 3 alunos.
2. Para cada aluno, solicite:
   - Nome (sem espaços)
   - RM (registro do aluno)
   - Idade
   - Nota da prova 1
   - Nota da prova 2
3. Ao final, exiba para cada aluno:
   - Nome, RM e idade
   - Média entre as duas notas
   - Resultado:
     - "Reprovado" (média < 7)
     - "Aprovado" (média ≥ 7)
     - "Aprovado com excelência" (média ≥ 9)

### 📆 Requisitos obrigatórios:
- Uso de `scanf()` e `printf()`
- Declaração correta de variáveis
- Uso de `if`, `else if`, `else` ou `switch`
- Uso de `for` ou `while` para repetção
- Saída personalizada com o RM de cada integrante

### 📌 Exemplo de Saída:
```
Aluno: Julia  | RM: 12345
Idade: 19     | Média: 8.5
Resultado: Aprovado
```

---

## 🎖️ Critérios de Avaliação

| Critério                            | Pontos |
|------------------------------------|--------|
| Parte 1: Conceitos                 | 2,0    |
| Parte 2: Análise e correção        | 3,0    |
| Projeto funcional e estruturado   | 5,0    |
| **Total**                          | **10** |

---

## 📁 Entrega
- Enviar arquivos:
  - `atividade_rm1_rm2_rm3.c` com o código do projeto.
  - `respostas_rm1_rm2_rm3.pdf` com as respostas das partes 1 e 2.
- Enviar via Portal do Aluno pelo representante do grupo até o prazo estabelecido.

---

**💡 Em caso de dúvidas, procure o professor antes da data de entrega!**
