# trabalho_somaticas

## Requisitos

Gitpod account

Github account

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

##
