# DAMA-DMBOK 2ª Edição

## Sumário

* [Capítulo 1 - Gestão de Dados](/src/docs/chapter_1/chapter_1.md) [Revisado ✅]
* [Capítulo 2 - Ética no tratamento de dados](/src/docs/chapter_2/chapter_2.md) [Revisado ✅]
* [Capítulo 3 - Governança de Dados](/src/docs/chapter_3/chapter_3.md) [Revisado ✅]
* [Capítulo 4 - Arquitetura de Dados](/src/docs/chapter_4/chapter_4.md)
* [Capítulo 5 - Modelagem e Design de Dados](/src/docs/chapter_5/chapter_5.md)
* [Capítulo 6 - Armazenamento e Operações de Dados](/src/docs/chapter_6/chapter_6.md)
* [Capítulo 7 - Segurança de Dados](/src/docs/chapter_7/chapter_7.md)
* [Capítulo 8 - Integração e Interoperabilidade de Dados](/src/docs/chapter_8/chapter_8.md)
* [Capítulo 9 - Gerenciamento de documentos e conteúdo](/src/docs/chapter_9/chapter_9.md)
* [Capítulo 10 - Dados de Referência e Mestres](/src/docs/chapter_10/chapter_10.md)
* [Capítulo 11 - Data Warehousing e Business Intelligence](/src/docs/chapter_11/chapter_11.md)
* [Capítulo 12 - Gerenciamento de Metadados](/src/docs/chapter_12/chapter_12.md)
* [Capítulo 13 - Qualidade de Dados](/src/docs/chapter_13/chapter_13.md)
* [Capítulo 14 - Big Data e Ciência de Dados](/src/docs/chapter_14/chapter_14.md)
* [Capítulo 15 - Avaliação de Maturidade em Gestão de Dados](/src/docs/chapter_15/chapter_15.md)
* [Capítulo 16 - Expectativas da Organização e do Papel da Gestão de Dados](/src/docs/chapter_16/chapter_16.md)
* [Capítulo 17 - Gestão de Dados e Gestão de Mudanças Organizacionais](/src/docs/chapter_17/chapter_17.md)

## Construção do e-book

Abaixo há os comando para gerar o documento em formato digital usando o pandoc (certifique-se de tê-lo instalado):

```sh
pandoc metadata.yaml --epub-cover-image=cover.jpg --resource-path=src/assets \
src/docs/preface.md \
src/docs/chapter_1/chapter_1.md \
src/docs/chapter_2/chapter_2.md \
src/docs/chapter_3/chapter_3.md \
src/docs/chapter_4/chapter_4.md \
src/docs/chapter_5/chapter_5.md \
src/docs/chapter_6/chapter_6.md \
src/docs/chapter_7/chapter_7.md \
src/docs/chapter_8/chapter_8.md \
src/docs/chapter_9/chapter_9.md \
src/docs/chapter_10/chapter_10.md \
src/docs/chapter_11/chapter_11.md \
src/docs/chapter_12/chapter_12.md \
src/docs/chapter_13/chapter_13.md \
src/docs/chapter_14/chapter_14.md \
src/docs/chapter_15/chapter_15.md \
src/docs/chapter_16/chapter_16.md \
src/docs/chapter_17/chapter_17.md \
-o dama-dmbok-2.epub
```

Para converter em .azw3 utilize o calibre com o comando abaixo:

```sh
ebook-convert dama-dmbok-2.epub dama-dmbok-2.azw3
```
