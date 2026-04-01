# Álgebra Linear — Unidade 1

**UEPB | Ciências da Computação | Prof.ª Thiciany Matsudo Iwano**

Este repositório contém uma série de notebooks Jupyter dedicados ao estudo dos tópicos da **Unidade 1 de Álgebra Linear**, combinando teoria baseada em Boldrini com visualizações geométricas e implementação prática em Python + SymPy.

> **Uso de IA:** este material foi estruturado com auxílio de modelos de linguagem (Claude — Anthropic), com revisão e validação do conteúdo pelo autor.

---

## 📚 Referência Principal

**BOLDRINI, J. L.; COSTA, S. I. R.; FIGUEIREDO, V. L.; WETZLER, H. G.**
*Álgebra Linear*. 3. ed. São Paulo: Harper & Row do Brasil, 1984.

---

## 🗺️ Roadmap — Ordem de Estudo

| Notebook | Tópico | Referência (Boldrini) |
|----------|--------|-----------------------|
| [`00_introducao_e_roadmap.ipynb`](notebooks/00_introducao_e_roadmap.ipynb) | Visão geral e dependências | — |
| [`01_matrizes.ipynb`](notebooks/01_matrizes.ipynb) | Definição, tipos especiais e operações | Cap. 1, p. 1–28 |
| [`02_sistemas_lineares.ipynb`](notebooks/02_sistemas_lineares.ipynb) | Método de Gauss, classificação de soluções | Cap. 2, p. 29–62 |
| [`03_espacos_vetoriais.ipynb`](notebooks/03_espacos_vetoriais.ipynb) | Definição formal e os 8 axiomas | Sec. 4.2, p. 103 |
| [`04_subespacos_vetoriais.ipynb`](notebooks/04_subespacos_vetoriais.ipynb) | Definição, verificação, exemplos | Sec. 4.3, p. 105 |
| [`05_combinacao_linear.ipynb`](notebooks/05_combinacao_linear.ipynb) | Definição, cálculo, exemplos | Sec. 4.4, p. 112 |
| [`06_span.ipynb`](notebooks/06_span.ipynb) | Subespaço gerado, geometria, redundância | Sec. 4.4, p. 112 |
| [`07_li_ld.ipynb`](notebooks/07_li_ld.ipynb) | Independência/dependência linear | Sec. 4.5, p. 114 |
| [`08_base_e_dimensao.ipynb`](notebooks/08_base_e_dimensao.ipynb) | Base, base canônica, dimensão | Sec. 4.6, p. 116 |

---

## 🛠️ Como Usar

### Google Colab (recomendado)
1. Acesse [colab.research.google.com](https://colab.research.google.com)
2. Vá em **Arquivo → Abrir notebook → GitHub**
3. Cole a URL deste repositório

### Localmente
```bash
pip install sympy numpy matplotlib jupyter
jupyter notebook notebooks/
```

---

## 📁 Estrutura

```
├── README.md
└── notebooks/
    ├── 00_introducao_e_roadmap.ipynb
    ├── 01_matrizes.ipynb
    ├── 02_sistemas_lineares.ipynb
    ├── 03_espacos_vetoriais.ipynb
    ├── 04_subespacos_vetoriais.ipynb
    ├── 05_combinacao_linear.ipynb
    ├── 06_span.ipynb
    ├── 07_li_ld.ipynb
    └── 08_base_e_dimensao.ipynb
```

---

## 📝 Convenções

- **Matrizes:** letras maiúsculas em itálico — $A$, $B$
- **Vetores:** letras minúsculas em negrito — $\mathbf{v}$, $\mathbf{u}$
- **Citações:** padrão autor-data — (BOLDRINI, 1984)
- **LI/LD verificado:** vetores montados como **colunas** da matriz
