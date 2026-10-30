
# DIO Agent - Especialização em Segurança Defensiva (AppSec)

Este repositório apresenta a evolução do **DIO Agent**, transformando-o num mentor especializado em **Cibersegurança e Segurança de Aplicações (AppSec)**. O objetivo é capacitar o agente a conduzir análises estruturadas de segurança, priorizando a avaliação de riscos, a compreensão do contexto e a adoção de boas práticas defensivas, em vez de fornecer respostas automáticas ou código de exploração.

---

## 🎯 1. A Especialização do Agente e o Porquê

A especialização introduzida transforma o agente num consultor defensivo (*Blue Team*).

* **Porquê?** No ecossistema de desenvolvimento moderno, a segurança não pode ser apenas uma etapa secundária. Um mentor de Inteligência Artificial deve ensinar os desenvolvedores a pensarem de forma defensiva, compreendendo os impactos reais das vulnerabilidades (como a Tríade CIA — Confidencialidade, Integridade e Disponibilidade) e aplicando remediações estruturais, como consultas parametrizadas e princípios de menor privilégio.

---

## 📁 2. Arquivos Criados ou Alterados

Para implementar esta especialização sem alterar o código-base do harness, foram criados e modificados os seguintes ficheiros:

* **`skills/vulnerability-analysis/SKILL.md` (Novo):** Roteiro passo a passo que o agente segue automaticamente para conduzir análises de segurança, exigindo sempre a validação do contexto do ambiente antes de qualquer orientação técnica.
* **`skills/vulnerability-analysis/README.md` (Novo):** Documentação explicativa da skill para consulta de utilizadores e novos desenvolvedores.
* **`agent/knowledge/security-basics.md` (Novo):** Base de conhecimento conceptual contendo definições sobre vulnerabilidades, ameaças, riscos, a Tríade CIA e matrizes de impacto e probabilidade.
* **`agent/persona.md` (Alterado):** Ajustado para incluir o tom e o comportamento de um consultor de AppSec experiente, focando em perguntas orientadoras e mentorias defensivas.
* **`AGENTS.md` (Alterado):** Atualizado com a nova linha na tabela principal de skills, permitindo que o agente reconheça quando deve acionar a análise de vulnerabilidades.

---

## ⚙️ 3. Como Rodar o Agente no Harness e a Melhoria Escolhida

### Como Executar:

1. Garante que descarregaste ou clonaste este repositório para a tua máquina.
2. Abre o terminal **estritamente na pasta raiz do projeto** (`dio-agent`). Se o terminal estiver aberto noutro diretório, o harness não conseguirá ler os ficheiros de configuração.
3. Inicia o teu harness preferido (por exemplo, *Hermes* ou *Google Antigravity*), seguindo a documentação oficial da ferramenta.
4. Interage com o agente de forma natural, fornecendo cenários ou trechos de código para revisão defensiva.

### A Melhoria Escolhida:

A melhoria implementada consistiu na **estruturação padronizada de risco baseada em Impacto, Probabilidade e Severidade**. Sempre que uma análise é solicitada, o agente formata a resposta seguindo uma matriz de risco rigorosa, permitindo comparar casos diferentes e priorizar correções de forma alinhada aos padrões de mercado em DevSecOps.

---

## ✒️ Autor

* **Nome:** David Juan Garcia Dos Santos
* **LinkedIn:** [Perfil no LinkedIn](https://www.google.com/search?q=https://www.linkedin.com/in/davidjuansantos/)
