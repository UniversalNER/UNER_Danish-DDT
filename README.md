# UNER_Danish-DDT

The UNER dataset for the Danish Dependency Treebank. UNER_Danish-DDT is part of [Universal NER](https://www.universalner.org/) and is based on the [UD_Danish-DDT](https://github.com/UniversalDependencies/UD_Danish-DDT) dataset. This dataset was originally developed as part of [the DaN+ corpus](https://github.com/bplank/DaNplus) and then converted into the UNER format and released with UNER v1.

The canonical reference commit to the Universal Dependencies dataset is [`e3c52aeba949b0634e513f4b4839ca290e0db78d`](https://github.com/UniversalDependencies/UD_Danish-DDT/tree/e3c52aeba949b0634e513f4b4839ca290e0db78d)

If you use this dataset, please cite the corresponding [paper](https://aclanthology.org/2024.naacl-long.243/):
```
@inproceedings{
  mayhew2024universal,
  title={Universal NER: A Gold-Standard Multilingual Named Entity Recognition Benchmark},
  author={Stephen Mayhew and Terra Blevins and Shuheng Liu and Marek Šuppa and Hila Gonen and Joseph Marvin Imperial and Börje F. Karlsson and Peiqin Lin and Nikola Ljubešić and LJ Miranda and Barbara Plank and Arij Riab and Yuval Pinter}
  booktitle={Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics (NAACL)},
  year={2024},
  url={https://aclanthology.org/2024.naacl-long.243/}
}
```

And cite the [paper](https://aclanthology.org/2020.coling-main.583/) for the original dataset: 
```
@inproceedings{plank2020danplus,
    title = "{D}a{N}+: {D}anish Nested Named Entities and Lexical Normalization",
    author = "Plank, Barbara and Jensen, Kristian N{\o}rgaard and van der Goot, Rob",
    editor = "Scott, Donia and Bel, Nuria and Zong, Chengqing",
    booktitle = "Proceedings of the 28th International Conference on Computational Linguistics",
    month = dec,
    year = "2020",
    address = "Barcelona, Spain (Online)",
    publisher = "International Committee on Computational Linguistics",
    url = "https://aclanthology.org/2020.coling-main.583",
    doi = "10.18653/v1/2020.coling-main.583",
    pages = "6649--6662",
}
```

## Metadata

Contributor: Barbara Plank

Danish UNER data

The xner label data are the merged (with #) nested annotations (2-level) from the DaNplus corpus, which added a manually annotated NER layer to the Danish UD treebank (https://aclanthology.org/2020.coling-main.583.pdf). 
