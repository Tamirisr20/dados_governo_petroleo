# 📊 Painel Analítico de Dados Abertos — Boletim Informativo Petróleo e Gás

<p align="center">
  <b>Dashboard interativo de Business Intelligence para análise de metadados e indicadores do setor de óleo e gás.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge" alt="Status Concluído">
  <img src="https://img.shields.io/badge/Tecnologias-HTML5_%7C_Tailwind_CSS_%7C_Chart.js_%7C_JavaScript-blue?style=for-the-badge" alt="Tecnologias">
  <img src="https://img.shields.io/badge/Licença-MIT-blueviolet?style=for-the-badge" alt="Licença">
</p>

---

## 🚀 Sobre o Projeto

Este projeto consiste em um **Dashboard Analítico em HTML navegável**, leve e de alta performance, alimentado por um conjunto de dados estruturado em formato **JSON**. 

Desenvolvido com foco em usabilidade e experiência de usuário (*UX*), o painel permite a exploração dinâmica de metadados institucionais, oferecendo recursos avançados de filtragem em tempo real, gráficos interativos com suporte a *drill-down* por clique, indicadores executivos (*KPIs*) e exportação de dados filtrados.

---

## 🎯 Tema e Conjunto de Dados

* **Tema:** Transparência e Monitoramento do Setor de Petróleo e Gás
* **Conjunto de Dados:** Boletim Informativo Petróleo e Gás
* **Órgão Responsável:** CGU - Controladoria-Geral da União
* **Link da Fonte:** *(Disponível nos portais oficiais de dados abertos)*

---

## ✨ Funcionalidades Principais

1. **KPIs Executivos Dinâmicos:** 
   * Acompanhamento em tempo real do total de conjuntos filtrados, volume acumulado de downloads, recursos técnicos e reutilizações.
2. **Busca Preditiva com Autocompletar:** 
   * Campo de pesquisa inteligente que exibe sugestões instantâneas conforme o usuário digita parte do nome ou da organização.
3. **Gráficos Interativos (Chart.js):**
   * **Gráfico de Barras:** Exibição dos principais conjuntos de dados classificados por volume de downloads com eixo Y fixo/travado para manter a estabilidade visual durante os filtros.
   * **Gráfico de Rosca (*Doughnut*):** Participação proporcional por órgão/organização com suporte a *drill-down* interativo (clique nas fatias ou no espaço em branco para alternar ou limpar filtros).
4. **Tabela Interativa e Organizações Clicáveis:**
   * Listagem detalhada dos registros com paginação e nomes de organizações interativos que permitem filtrar o painel com um único clique.
5. **Modais de Detalhes e Estatísticas:**
   * Janelas modais para inspeção de descrições completas e visualização de um resumo estatístico global.
6. **Exportação de Dados:**
   * Botão dedicado para exportar o subconjunto de dados atualmente filtrado diretamente para um arquivo **CSV**.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 / CSS3:** Estruturação semântica e estilização moderna.
* **Tailwind CSS (via CDN):** Framework utilitário para design responsivo e identidade visual customizada (com foco nas cores Laranja Vivo `#FF5000` e Cinza Escuro `#454545`).
* **Chart.js (via CDN):** Biblioteca JavaScript para renderização de gráficos estatísticos responsivos.
* **JavaScript (ES6+):** Lógica de manipulação do DOM, controle de estado, tratamento assíncrono de JSON e eventos de interatividade.

---

## 📂 Estrutura de Arquivos

```text
📦 projeto-dashboard-petroleo-gas
 ┣ 📜 index.html       # Arquivo principal contendo toda a interface e lógica do dashboard
 ┗ 📜 dados.json       # Base de dados estruturada em formato JSON