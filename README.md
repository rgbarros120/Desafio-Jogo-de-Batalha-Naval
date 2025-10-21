
# 🚢 Desafio Batalha Naval - Projeto Completo

Este repositório contém as soluções completas do **Desafio Batalha Naval**, desenvolvido em linguagem C, com implementação no nível: **Mestre**.

---

## 🔴 Nível Mestre

### 🎯 Funcionalidades

- Representação de **habilidades especiais** com matrizes 5x5.
- Três padrões:
  - 🔺 Cone
  - ➕ Cruz
  - ♦️ Octaedro
- `1` = área afetada, `0` = não afetada

### 💡 Exemplos

**Cone**
```
0 0 1 0 0
0 1 1 1 0
1 1 1 1 1
0 0 0 0 0
0 0 0 0 0
```

**Cruz**
```
0 0 1 0 0
1 1 1 1 1
0 0 1 0 0
0 0 0 0 0
0 0 0 0 0
```

**Octaedro**
```
0 0 1 0 0
0 1 1 1 0
0 0 1 0 0
0 0 0 0 0
0 0 0 0 0
```

### 🧠 Conceitos Aplicados

- Padrões visuais com matrizes
- Modularização com funções
- Impressão formatada

### ▶️ Como Executar

```bash
gcc batalha_naval_mestre.c -o mestre
./mestre
```

### 📁 Estrutura do Código

- `habilidadeCone()`
- `habilidadeCruz()`
- `habilidadeOctaedro()`
- `exibirMatriz()`

---

## ✍️ Autor

Desenvolvido por [Rodrigo Barros](https://github.com/rgbarros120/Desafio-Jogo-de-Batalha-Naval)  
Como parte dos estudos em Análise e Desenvolvimento de Sistemas.

