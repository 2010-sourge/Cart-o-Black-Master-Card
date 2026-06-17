# 💳 Credit Card UI — HTML & CSS

Um componente de **cartão de crédito** dark com textura de ondas, construído com **HTML e CSS puro**. O design sofisticado apresenta um cartão preto com padrão de linhas onduladas em relevo, sobre um fundo azul claro minimalista.

---

## ✨ Preview

O projeto exibe:
- **Cartão preto** com textura decorativa de ondas em CSS
- **Logo Mastercard** com os círculos vermelho e laranja sobrepostos
- **Chip dourado** no canto superior direito
- **Número do cartão**, nome do titular e data de validade
- **Fundo azul claro** minimalista com sombra suave no card

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** — estrutura semântica do card
- **CSS3** — textura de ondas com `repeating-linear-gradient` ou SVG inline, `border-radius`, `box-shadow` e Flexbox

---

## 📁 Estrutura do Projeto

```
credit-card-dark/
├── index.html
└── style.css
```

---

## 🚀 Como Executar

1. Clone ou baixe este repositório
2. Abra o arquivo `index.html` no seu navegador

Nenhuma instalação ou dependência necessária!

---

## 🎨 Detalhes do Design

### Textura de Ondas
O padrão de linhas onduladas do fundo do cartão é criado puramente em CSS:

```css
.card {
  background-color: #111;
  background-image: repeating-linear-gradient(
    -45deg,
    transparent,
    transparent 2px,
    rgba(255,255,255,0.03) 2px,
    rgba(255,255,255,0.03) 4px
  );
  border-radius: 20px;
  box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
}
```

### Logo Mastercard
Os dois círculos sobrepostos da bandeira são feitos com CSS puro:

```css
.mastercard .circle-red  { background: #eb001b; }
.mastercard .circle-orange { background: #f79e1b; margin-left: -15px; }
```

---

## 🧩 Estrutura Visual

```
┌──────────────────────────────────────────┐
│  🔴🟠 Master Card              [Chip 💳] │  ← Fundo preto com ondas
│                                          │
│  Card Number                             │
│  8050  5040  2030  3020                  │
│                                          │
│  Prem Kumar Shahi         Valid Thru     │
│                            05/28         │
└──────────────────────────────────────────┘
           (fundo azul claro #e8f0f7)
```

---

## ⚙️ Personalização

| Elemento | Como alterar |
|---|---|
| Número do cartão | Edite o texto `.card-number` no HTML |
| Nome do titular | Altere o texto `.card-holder` |
| Data de validade | Edite o `.valid-thru` |
| Cor do cartão | Altere o `background-color` em `.card` |
| Intensidade das ondas | Ajuste a opacidade no `repeating-linear-gradient` |
| Cor do fundo da página | Altere o `background` do `body` |

---

## 📌 Funcionalidades

- [x] Design dark com textura de ondas em CSS
- [x] Logo Mastercard com círculos sobrepostos
- [x] Chip do cartão estilizado em dourado
- [x] Sombra suave realista no card
- [x] Layout com Flexbox
- [x] Fundo minimalista azul claro
- [x] 100% HTML e CSS — sem JavaScript

---

## 🎨 Inspiração

Projeto criado pelo canal **CodingLab**, demonstrando como recriar componentes de UI bancários modernos usando apenas HTML e CSS.

---

## 📄 Licença

Este projeto é livre para uso educacional e pessoal.
