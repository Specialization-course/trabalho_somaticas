# Projeto_Somático_2022 ![Badge em Desenvolvimento](https://img.shields.io/static/v1?label=STATUS&message=EmProdução&color=<YELLOW>)

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)]([https://gitpod.io/#https://github.com/fabio-marcelo/trabalho_somaticas])

# Pipeline Análise Variantes Somáticas 

**Tópicos**
1. [Introdução](#introducao)
2. [Objetivo](#objetivo)
3. [Referência](#referencia)
4. [Requisitos](#requisitos)
5. [Obtenção de Arquivos](#arquivos)
6. [Pipeline do Trabalho](#colab)
7. [Análise e Interpretação dos Dados](#dados)

<div id='introducao'/> 

## 📃 Introdução
Pipeline desenvolvida com intuito avaliativo para o programa de Pós Graduação em Bioinformática Aplicada a Genômica Médica do Instituto Israelita de Ensino e Pesquisa Albert Einstein. 
- *Grupo 4*
- Integrantes: 
  * Fábio Marcelo de Lima (GitHub - https://github.com/fabio-marcelo)
  * Yuri Nakau (GitHub - https://github.com/yurinf)
  * Paulo Nasser (GitHub - https://github.com/pdnasser)
  * Guilherme Bueno (GitHub - https://github.com/GuilhermeBPinheiro)
  * Giovanna Prezia (GitHub - https://github.com/GiovannaPrezia)

<div id='introducao'/> 

<div id='objetivo'/> 

## 🎯 Objetivo
Análise de variantes somáticas detectadas em genes de alto risco que são fatores de prognósticos adversos em Mielofibrose (MF).
- *Objetivos específicos*:
  * Rodar um pipeline somático e anotação das variantes somáticas através do programa Google Colab.
  * Identificar amostras com alterações no TP53 e nos genes de alto risco (EZH2, CBL, U2AF1, SRSF2, IDH1, IDH2, NRAS ou KRAS) que são fatores de prognósticos adversos em mielofibrose.

<div id='objetivo'/> 

<div id='referencia'/> 

## 📚 Referências
* [Artigo 01](https://pubmed.ncbi.nlm.nih.gov/33488802/)
 > Xia Y, Hong Q, Gao Z, Wang S, Duan S. Somatically acquired mutations in primary myelofibrosis: A case report and meta-analysis. Exp Ther Med. 2021 Mar;21(3):193. Doi: 10.3892/etm.2021.9625. Epub 2021 Jan 7. PMID: 33488802; PMCID: PMC7812576.
* [Artigo 02](https://pubmed.ncbi.nlm.nih.gov/33666653/)
 > Luque Paz D, Riou J, Verger E, Cassinat B, Chauveau A, Ianotto JC, Dupriez B, Boyer F, Renard M, Mansier O, Murati A, Rey J, Etienne G, Mansat-De Mas V, Tavitian S, Nibourel O, Girault S, Le Bris Y, Girodon F, Ranta D, Chomel JC, Cony-Makhoul P, Sujobert P, Robles M, Ben Abdelali R, Kosmider O, Cottin L, Roy L, Sloma I, Vacheret F, Wemeau M, Mossuz P, Slama B, Cussac V, Denis G, Walter-Petrich A, Burroni B, Jézéquel N, Giraudier S, Lippert E, Socié G, Kiladjian JJ, Ugo V. Genomic analysis of primary and secondary myelofibrosis redefines the prognostic impact of ASXL1 mutations: a FIM study. Blood Adv. 2021 Mar 9;5(5):1442-1451. Doi: 10.1182/bloodadvances.2020003444. PMID: 33666653; PMCID: PMC7948260.

<div id='referencia'/> 

<div id='requisitos'/>  

## 🖥 Requisitos
  * Acesso à internet
  * Conta Google
  * Arquivo VCF 
  * Arquivo de metadados
  * Arquivo de referência genômica (Hg19)
  * Instalar VEP

<div id='requisitos'/>

<div id='arquivos'/>

## 📥 Obtenção de Arquivos 

* [Arquivos VCF](https://drive.google.com/drive/folders/1m2qmd0ca2Nwb7qcK58ER0zC8-1_9uAiE)
* [Arquivo com Metadados](https://www.ncbi.nlm.nih.gov/Traces/study/?acc=PRJNA530251&search=MF&o=acc_s:a)
* [Arquivo Hg19](https://drive.google.com/drive/folders/1JeK0a9QURuZB77xuIOx2gBB03Wk3chQr)
* [Repositório ensembl-vep](https://github.com/Ensembl/ensembl-vep/tags)

<div id='arquivos'/>


<div id='colab'/>

## 📝 Pipeline do Trabalho
Pipeline com passo-a-passo desenvolvida no [Google Colab](https://drive.google.com/file/d/1Hy93rK3s-0aEwau8jGUlQGXFWIjUMY8G/view?usp=sharing)

<div id='colab'/>

<div id='dados'/>

## Análise e Interpretação dos Dados

* [Variantes de Interesse Clínico de Todas Amostas.pdf](https://github.com/fabio-marcelo/trabalho_somaticas/files/10289721/Variantes.de.Interesse.Clinico.de.Todas.Amostas.pdf)
* [Tabelas das Amostras.pdf](https://github.com/fabio-marcelo/trabalho_somaticas/files/10291077/Tabelas.das.Amostras.pdf)

<div id='dados'/>
