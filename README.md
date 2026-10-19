<div align="center">

# Guilherme Henrique Mendes

**Analista de Dados Júnior · Analytics Engineer · BI**

*Rigor quantitativo (UFF Matemática + 6x aprovações militares) · Engenharia de dados em produção · Comunicação com stakeholders*

<p>
  <strong>🇧🇷 Português</strong> &nbsp;|&nbsp; <a href="./README.en.md"><strong>🇺🇸 English</strong></a>
</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ghmendes02-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ghmendes02/)
[![GitHub](https://img.shields.io/badge/GitHub-StylishGH-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/StylishGH)
[![Email](https://img.shields.io/badge/Email-guiguimendes2002%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:guiguimendes2002@gmail.com)
[![Localização](https://img.shields.io/badge/Mesquita--RJ-Brasil-009c3b?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

## 📌 Sobre Mim

Sou graduando em **Licenciatura em Matemática na Universidade Federal Fluminense (UFF/CEDERJ)** e construo sistemas e pipelines de dados que rodam em produção — indo muito além de notebooks experimentais. Minha fundação é ancorada em **álgebra linear, cálculo, inferência estatística e otimização**, combinada com a prática diária de **ETL, modelagem relacional (PostgreSQL/SQL analítico), machine learning e deploy**.

Fui aprovado em concursos militares de altíssima exigência quantitativa e concorrência:
- ⚓ **EFOMM (Escola de Formação de Oficiais da Marinha Mercante)** — Aprovado **2 vezes** (Cálculo Diferencial e Integral, Física, Álgebra Linear e Inglês).
- ✈️ **EEAr (Escola de Especialistas de Aeronáutica)** — Aprovado **3 vezes**.
- 🎖️ **ESA (Escola de Sargentos das Armas)** — Aprovado **1 vez**.

Essa bagagem forjou minha resiliência, disciplina de execução sob extrema pressão e raciocínio lógico analítico para diagnosticar e resolver problemas complexos com velocidade.

Além disso, atuo como **tutor particular de exatas**, onde desenvolvi a habilidade crítica de **tradução de complexidade para stakeholders**: sintetizar conceitos abstratos e volumetria de dados em insights acionáveis, visuais e compreensíveis para tomadores de decisão de negócio.

---

## 🛠️ Stack Tecnológico

<div align="center">

![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Advanced_CTEs_&_Windows-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.5-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0.115-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-1.40-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-pgvector-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-Flow-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 🚀 Projetos em Destaque

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">📐 LemmaS — Plataforma EdTech de Aprendizado Adaptativo</h3>
      <p align="center"><em>Plataforma em produção que integra banco de dados vetorial, repetição espaçada SM-2 e tutoria socrática multi-provedor</em></p>
      <ul>
        <li><strong>Escala Real:</strong> <strong>21.272 questões</strong> catalogadas de bancas militares e <strong>2.000 lemas axiomáticos</strong> mapeados em PostgreSQL (Supabase).</li>
        <li><strong>Pipeline ETL:</strong> Ingestão automatizada de PDFs oficiais via <code>PyMuPDF</code>, extração nativa de figuras XObjects e taxonomia por banca e dificuldade.</li>
        <li><strong>Motor de Tutoria Socrática:</strong> Arquitetura multi-provedor (Gemini 2.5 Flash + NVIDIA NIM) com fallback resiliente, cache de inferência e validação estrita de LaTeX.</li>
        <li><strong>Busca Vetorial & SM-2:</strong> Embeddings com <code>pgvector</code> (índices HNSW) para busca semântica sub-100ms e algoritmo SM-2 para retenção de longo prazo.</li>
      </ul>
      <p align="center">
        <a href="https://lemmas-ochre.vercel.app/dashboard"><strong>🌐 Aplicação ao Vivo</strong></a> ·
        <a href="https://github.com/StylishGH/LemmaS"><strong>📦 Código Fonte</strong></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">📈 Análise Preditiva e Clusterização de Empresas da B3</h3>
      <p align="center"><em>Pipeline end-to-end de dados fundamentalistas, clusterização K-Means e classificação de resiliência financeira</em></p>
      <ul>
        <li><strong>Ingestão e Tratamento:</strong> Extração e padronização de demonstrativos da <strong>CVM</strong> (DRE, Balanço Patrimonial e Fluxo de Caixa) de centenas de empresas listadas.</li>
        <li><strong>Feature Engineering:</strong> Cálculo de múltiplos de valuation (P/L, P/VP, EV/EBITDA) e liquidez (Liquidez Corrente, Dívida Líquida/EBITDA); tratamento de outliers por IQR.</li>
        <li><strong>Machine Learning:</strong> Segmentação não-supervisionada via <strong>K-Means</strong> (validação por Elbow Method e Silhouette Score) e classificação com <strong>Random Forest</strong>.</li>
        <li><strong>Dashboard Interativo:</strong> Aplicação <strong>Streamlit</strong> com filtros dinâmicos, gráficos interativos em Plotly e tabelas analíticas para tomada de decisão.</li>
      </ul>
      <p align="center">
        <a href="https://ghmendes.streamlit.app"><strong>🌐 Dashboard ao Vivo</strong></a> ·
        <a href="https://github.com/StylishGH/Empresas-B3-analise-de-dados"><strong>📦 Código Fonte</strong></a>
      </p>
    </td>
  </tr>
</table>

---

## 🧠 Filosofia de Dados & Métodos Analíticos

| Princípio | Aplicação Prática |
| :--- | :--- |
| **Rigor Estatístico** | Validação cruzada estratificada (k-fold), intervalos de confiança e testes de hipóteses antes de inferir correlações espúrias. |
| **Qualidade & Integridade (ETL)** | 80% do sucesso analítico reside no tratamento: sanitização, tipagem estrita, imputação fundamentada e prevenção de *data leakage*. |
| **Explicabilidade & Negócio** | Todo modelo preditivo deve responder a uma dor de negócio: uso de Feature Importance e tradução de métricas para linguagem executiva. |
| **Reprodutibilidade** | Ambientes containerizados (Docker), dependências pinadas e código modular documentado em repositórios rastreáveis. |

---

## 🎯 Formação & Conquistas

- 🎓 **Licenciatura em Matemática** — Universidade Federal Fluminense (UFF / CEDERJ) *(Previsão de conclusão: 2027)*
- ⚓ **EFOMM** — Aprovado 2x *(Cálculo Diferencial e Integral, Física, Álgebra Linear e Inglês)*
- ✈️ **EEAr** — Aprovado 3x
- 🎖️ **ESA** — Aprovado 1x
- 🌐 **Idiomas:** Português (Nativo) · Inglês (Leitura técnica fluente, escrita e comunicação intermediária)

---

## 📬 Contato & Conexão

Estou ativamente buscando oportunidades efetivas (CLT/PJ) como **Analista de Dados Júnior**, **Analytics Engineer** ou **Analista de BI**.

- 💼 **LinkedIn:** [linkedin.com/in/ghmendes02](https://www.linkedin.com/in/ghmendes02/)
- 📧 **E-mail Profissional:** [guiguimendes2002@gmail.com](mailto:guiguimendes2002@gmail.com)
- 🐙 **GitHub:** [github.com/StylishGH](https://github.com/StylishGH)
- 📍 **Localização:** Mesquita, RJ — Disponível para atuação **Remota** ou **Híbrida/Presencial no Rio de Janeiro**.

<div align="center">
  <sub>"Reduzo custo de decisão sob incerteza unindo rigor quantitativo, comunicação com stakeholders e engenharia de dados em produção."</sub>
</div>
