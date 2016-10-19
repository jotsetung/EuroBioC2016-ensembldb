## `ensembldb`: extending transcript-centered databases with protein annotations

## Extending `ensembldb`: MySQL backend and protein annotations

Johannes Rainer (twitter/github:jotsetung) and Laurent Gatto (twitter:lgatt0/github:lgatto)

The `ensembldb` package allows to create and query `AnnotationDbi` comliant
`EnsDb` databases to store and extract genomic coordinates of genes, transcrips
and exons. While providing similar annotations than the `TxDb` databases,
`ensembldb` implements a rich filtering framework enabling fast and customized
queries to the databases. Recently, `ensembldb` was extended with the capability
to switch from the default SQLite to a MySQL database backand and the ability to
add protein annotations to `EnsDb`s. Dedicated methods allow to query DNA/RNA
related annotations along with protein annotations enabling the use of
`ensembldb` as an annotation source for proteomics based packages like
`Pbase`. In my talk I will briefly present the capabilities of `ensembldb` and
highlight how it can be used together with `Pbase` to map peptide features
within proteins to the genome.
