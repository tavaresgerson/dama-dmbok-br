# DAMA-DMBOK 2ª Edição

## Construção de e-book

Abaixo há os comando para gerar o documento em formato digital usando o pandoc (certifique-se de tê-lo instalado):

```sh
pandoc metadata.yaml --resource-path=src/assets \
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

Para converter em .mobi utilize o calibre com o comando abaixo:

```sh
ebook-convert dama-dmbok-2.epub dama-dmbok-2.mobi
```
