# 🧱 CSS Box Model Practice – Padding e Cores

Este projeto é uma prática de **Box Model em CSS**, focando no uso de **padding**, **cores de fundo** e **organização de conteúdo** com HTML e CSS puro.

---

## 🎯 Objetivo

Recriar o layout visual representado na imagem de referência, aplicando:

- Cores de fundo distintas para cada caixa.
- Texto centralizado com cores específicas.
- Uso uniforme de `padding: 10px` em todas as caixas.
- Estruturação em blocos aninhados com margens e alinhamento visual.

---

## 📦 Estrutura do Layout

A estrutura é composta por:

1. **Contêiner Externo (roxo)**  
   - Cor de fundo: roxo escuro  
   - Padding: 10px  

2. **Blocos Azuis** (dois blocos)  
   - Cor de fundo: azul  
   - Padding: 10px  
   - Contêm dois elementos:  
     - Título (texto amarelo)  
     - Caixa interna (vermelha)

3. **Caixas Internas Vermelhas**  
   - Cor de fundo: vermelho  
   - Texto: branco  
   - Padding: 10px

---

## 🖍️ Cores utilizadas

| Elemento              | Cor     | Código       |
|-----------------------|---------|--------------|
| Contêiner externo     | Roxo    | `purple`     |
| Blocos intermediários | Azul    | `blue`       |
| Caixas internas       | Vermelho| `red`        |
| Texto do título       | Amarelo | `yellow`     |
| Texto das caixas      | Branco  | `white`      |

---

## ✨ Estilo aplicado via CSS

Exemplo genérico de CSS para este projeto:

```css
* {
  padding: 10px;
  box-sizing: border-box;
}

.container {
  background-color: purple;
}

.block {
  background-color: blue;
  color: yellow;
}

.inner-box {
  background-color: red;
  color: white;
}
