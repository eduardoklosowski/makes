# Makes

Scripts para criar alguns tipos de arquivos.

## Comic Book Zip Archive (.cbz)

- **Script:** `makecbz`
- **Argumento:** Diretório contento as imagens
- **Saída:** `$1.cbz`

**Exemplo:**

```sh
makecbz diretório
```

## EPUB (.epub)

- **Script:** `makeepub`
- **Argumento:** Nome do arquivo do livro (Padrão: nome do diretório atual)
- **Saída:** `$1.epub`

**Nota:** `mimetype`, `META-INF` e `EPUB` devem estar no diretório atual.

**Exemplo:**

```sh
makeepub
```
