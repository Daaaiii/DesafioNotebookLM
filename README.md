# 📘 Miniguia de Estudos: Reforma Tributária de Consumo no NotebookLM

![Status](https://img.shields.io/badge/Status-Concluído-success)
![Desafio](https://img.shields.io/badge/Desafio-DIO-blue)
![Tema](https://img.shields.io/badge/Tema-Reforma_Tributária-orange)

Este repositório contém o projeto prático do desafio da **DIO (Digital Innovation One)**, focado no uso da Inteligência Artificial como ferramenta de aprendizagem ativa, pensamento crítico e curadoria de conhecimento. 

🔗 **Link do meu Caderno Temático no NotebookLM:** [Acessar Caderno](https://notebooklm.google.com/notebook/730cd60d-9abf-4649-a534-32296f0a5116)

---

## 🎯 Contexto e Objetivos

O assunto de interesse escolhido para este caderno temático foi a **Reforma Tributária do Consumo Brasileira**, com foco nas mudanças operacionais que impactarão os negócios.

**Objetivos de Estudo:**
1. [cite_start]Compreender o novo ecossistema do IVA Dual no Brasil, dominando as diferenças entre IBS e CBS[cite: 6, 14, 16].
2. [cite_start]Explorar os mecanismos de mitigação de cumulatividade, especificamente a aplicação e os impactos do **Crédito Presumido** em diversos setores[cite: 8, 9].
3. Utilizar o Google NotebookLM para extrair, compilar e formatar (em ABNT) referências e glossários técnicos com base em documentações legais e materiais acadêmicos.

---

## 📚 Curadoria de Fontes

Para evitar alucinações da IA e garantir a veracidade jurídica, o NotebookLM foi alimentado com documentos oficiais e técnicos da nova legislação. As fontes principais incluem:

* **Legislação e Regulamentação:**
  * BRASIL. Decreto nº 12.955/2026. [cite_start]Regulamenta a CBS[cite: 28].
  * COMITÊ GESTOR DO IMPOSTO SOBRE BENS E SERVIÇOS (CGIBS). [cite_start]Resolução CGIBS nº 6/2026[cite: 37].
* **Manuais e Glossários Oficiais:**
  * BRASIL. Secretaria Especial da Receita Federal. [cite_start]Reforma Tributária sobre Consumo RTC – Glossário[cite: 30].
  * [cite_start]Plataforma Pública de Split Payment: Manual de Integração[cite: 34].
  * CGIBS. [cite_start]Apuração do IBS: cartilha orientativa[cite: 35].
* **Materiais de Apoio / Transcrições:**
  * [cite_start]Arquivos de aulas detalhando Casos Específicos (Produtor Rural, Transportador Autônomo de Cargas - TAC, Resíduos Sólidos e Bens Móveis Usados)[cite: 24, 25, 26, 27].

---

## 🛠️ Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Durante a interação, ficou claro que pedir para a IA explicar tudo de uma vez geraria uma resposta superficial. A estratégia ("cicatriz") foi fatiar a requisição de conceitos complexos por nicho de mercado e solicitar formatações de saída bem definidas:

* **1. Abertura do Escopo:** *"Faça um resumo sobre credito presumido, explicando detalhadamente o que é e como vai funcionar a partir da reforma. Busque mais fontes se for necessário."*
* **2. Fatiamento por Nicho (Aprofundamento):**
  * *"Explique como o credito presumido funciona para transporte de cargas"*
  * *"Agora explique sobre produtor rural"*
  * *"agora explique detalhadamente sobre credito presumido para Bens Móveis Usados Adquiridos para Revenda"*
* **3. Formatação e Organização Final:**
  * *"Crie um glossário com os principais termos relacionados a Reforma Tributária."*
  * *"Crie uma lista das fontes no formato ABNT"*
  * *"Liste todos os comandos que eu já utilizei neste chat"*

---

## 📖 Miniguia de Estudo (Entrega Final)

Com base nas curadorias e nas respostas refinadas, consolidei este material de consulta rápida:

### 1. Resumos Estruturados: O Novo Crédito Presumido
* [cite_start]**O que é?** É um benefício fiscal desenhado para corrigir a cumulatividade de impostos quando empresas do regime regular adquirem produtos/serviços de quem não cobra imposto na operação[cite: 8, 9].
* [cite_start]**Aplicação no Transporte (TAC):** Transportadores Autônomos de Cargas (Pessoas Físicas ou MEIs) perdem a condição de contribuinte padrão para proteger sua categoria[cite: 21]. [cite_start]Assim, a empresa que contrata o frete ganha o direito de se apropriar do crédito presumido[cite: 21].

### 2. Glossário Essencial
* [cite_start]**IBS (Imposto sobre Bens e Serviços):** Tributo que substitui os atuais ICMS e ISS[cite: 14]. [cite_start]É de competência de Estados e Municípios e cobrado no local de consumo[cite: 14].
* [cite_start]**CBS (Contribuição sobre Bens e Serviços):** Tributo exclusivo da União que entra para substituir o PIS e a COFINS[cite: 6]. [cite_start]Juntos (IBS+CBS), formam o IVA Dual[cite: 6].
* [cite_start]**Split Payment:** Inovação onde o sistema financeiro (PIX, cartão, etc.) separa automaticamente a fatia do imposto (IBS e CBS) e já repassa direto ao governo no momento do pagamento[cite: 20].
* [cite_start]**Cashback:** Devolução de parte dos impostos pagos para famílias inscritas no CadÚnico[cite: 5].
* [cite_start]**Apuração Assistida (AA):** O fisco usa os dados das notas fiscais para gerar uma apuração automática (prévia) dos impostos devidos, diminuindo a burocracia[cite: 4].

### 3. Prompts Reutilizáveis (Para Revisões Futuras)
Se eu precisar atualizar meu conhecimento ou revisar este assunto no NotebookLM, utilizarei os seguintes padrões:

> 💡 *"Explique como o [INSERIR CONCEITO/REGRA] funciona especificamente para o setor de [INSERIR SETOR], baseando-se apenas nos documentos anexados. Detalhe os impactos operacionais."*

> 💡 *"Crie uma tabela comparando os termos técnicos listados nos documentos com suas respectivas definições oficiais."*

> 💡 *"Gere um documento no formato ABNT contendo a lista de todas as normativas e fontes que você utilizou para compor suas respostas anteriores."*

---
*Projeto desenvolvido para o desafio da DIO.*
