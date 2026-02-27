# 📍 ET-ADGV 3.0 — Estudo Interativo

> Plataforma de estudo completa para a **Especificação Técnica para Aquisição de Dados Geoespaciais Vetoriais (ET-ADGV 3.0)** do Exército Brasileiro / DSG — com teoria detalhada, resumo e 50 questões com progressão de dificuldade.

<br>

![Preview](https://img.shields.io/badge/Tecnologia-HTML%20%2F%20CSS%20%2F%20JS-blue?style=flat-square)
![Questões](https://img.shields.io/badge/Quest%C3%B5es-50-green?style=flat-square)
![Norma](https://img.shields.io/badge/Norma-ET--ADGV%203.0%20%E2%80%94%20DSG%202018-orange?style=flat-square)
![Deploy](https://img.shields.io/badge/Deploy-GitHub%20Pages-lightgrey?style=flat-square)

---

## 🖥️ Demo

Acesse diretamente pelo GitHub Pages:  
**[https://SantosIngrid.github.io/et-adgv/](https://SantosIngrid.github.io/et-adgv/)**

---

## 📚 O que tem dentro

### Aba 1 — Teoria
13 seções navegáveis com conteúdo completo:

| Categoria | Seções |
|-----------|--------|
| **Fundamentos** | Introdução e Objetivos · Escalas e Dimensões Mínimas · Primitivas Geométricas · Topologia e Regras |
| **Hidrografia** | Visão Geral · Trecho de Drenagem · Massa d'Água · Barragem e Açude · Regras Topológicas |
| **Transporte** | Visão Geral · Rodovias · Ferrovias · Regras Topológicas · Estruturas Viárias |

Inclui:
- Tabela de conversão de escalas (0,4 mm no mapa → metros no terreno)
- **Tabela de dimensões mínimas para 4 escalas** (1:25k / 1:50k / 1:100k / 1:250k)
- Atributos completos de cada classe de objeto
- Diagramas SVG de topologia (nós, gaps, confluências)

### Aba 2 — Resumo
Cards de consulta rápida organizados por tema — ideal para revisão de véspera.

### Aba 3 — Questões
- **50 questões** com 4 níveis de dificuldade
- Filtro por categoria: Hidrografia · Transporte · Escalas · Topologia · Fundamentos
- Feedback imediato com explicação técnica e referência à seção da norma
- Resultado final com aproveitamento percentual

---

## 🗂️ Estrutura do Projeto

```
et-adgv/
├── index.html       ← aplicação completa (single file)
└── README.md
```

> Projeto 100% frontend — sem dependências, sem build, sem framework. Abre direto no navegador.

---

## 🚀 Como usar localmente

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/et-adgv.git

# Entre na pasta
cd et-adgv

# Abra no navegador (qualquer um dos comandos abaixo)
open index.html           # macOS
xdg-open index.html       # Linux
start index.html          # Windows
```

Ou simplesmente arraste o `index.html` para o navegador.

---

## ☁️ Deploy no GitHub Pages

1. Vá em **Settings → Pages** no seu repositório
2. Em *Source*, selecione `Deploy from a branch`
3. Branch: `main` · Pasta: `/ (root)`
4. Clique em **Save**
5. Aguarde ~1 minuto e acesse `https://seu-usuario.github.io/et-adgv/`

---

## 📖 Base Normativa

| Documento | Publicação |
|-----------|-----------|
| ET-ADGV 3.0 | DSG / Exército Brasileiro · 21 dez 2018 |
| ET-EDGV 3.0 | CONCAR · dez 2017 |

O conteúdo cobre os temas mais cobrados em concursos e certificações técnicas da DSG, IBGE e CONCAR.

---

## 🤝 Contribuindo

Pull requests são bem-vindos! Sugestões de novas questões, correções ou novos temas:

1. Fork o projeto
2. Crie uma branch: `git checkout -b feat/nova-questao`
3. Commit: `git commit -m 'feat: adiciona questões de relevo'`
4. Push: `git push origin feat/nova-questao`
5. Abra um Pull Request

---

## 📄 Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

---

<p align="center">Feito para facilitar o estudo da cartografia brasileira 🗺️</p>
