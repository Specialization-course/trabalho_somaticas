# trabalho_somaticas

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)]([https://gitpod.io/#https://github.com/fabio-marcelo/trabalho_somaticas])


## Requisitos

Gitpod account

Github account

## Arquivos deste repositório

1) README.md - passo a passo das análises realizadas
2) comitando - passo a passo de como subir alterações feitas no gitpod para o github

## Instalar ferramentas

```bash
# instalar sra toolkit
brew install sratoolkit
```

```bash
# instalar parallel-fastq-dump
pip install parallel-fastq-dump

# rodar validate
echo "Aexyo" | vdb-config -i
```

```bash
# instalar o bwa
brew install bwa
```


## Baixar fastq (SRR8832737)

```bash
time parallel-fastq-dump --sra-id SRR_ID \
--threads 4 --outdir ./ \
--split-files --gzip
```

## Download do genoma referencia (hg38)

```bash
# -c continua o download de onde parou caso caia a conexao
wget -c https://hgdownload.soe.ucsc.edu/goldenPath/hg38/chromosomes/
```

##Teste 02
