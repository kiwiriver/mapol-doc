# FastMAPOL ATBD Builder
## FastMAPOL in nutshell
## Update documents in chapters
Use Markdown format

- Each chapter start with level ##
- To cite a paper, follow the format as @Gao:2021aa, where Gao:2021aa is defined in the bib file

- Define a figure reference

``` markdown
Based on the synthetic data, retrieval results as shown in @fig-validation_harp2_l2  

![Retrieval performance: AOD (550 nm) and ALH showing retrieval, truth, and uncertainty (a–c, d–f). Figure is adopted from @Gao:2023aa](../figure/validation_harp2_l2.png){#fig-validation_harp2_l2 width=80%}
```

- The final document will be generated in each atbd folder, such as atbd_v1, 
where index.md define the overall information, to generate the whole document:
``` bash
quarto render
```
