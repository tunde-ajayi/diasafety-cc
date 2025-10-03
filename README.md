# Overview
DiaSafety-CC is an extension of [DiaSafety](https://github.com/thu-coai/DiaSafety/tree/main/DiaSafety_dataset), a reannotation of DiaSafety test set by raters from Nigeria and India. Raters provide labels as "Safe" or "Unsafe". Also, reasons are provided for the choice of labels as free-form text.<br><br>
The ```/data``` folder contains:<br>
```diasafety_cc.json``` : extended evaluation set<br>
```raters_metadata.json``` : anonymised raters' data

# Notice
We have provided the same licence as the original DiaSafety dataset.

# Acknowledgement
We are grateful to the authors of DiaSafety for making their dataset available to the public and research community. We are also grateful to the raters for their selfless contribution to this work.

# Publication
Link to the paper can be found [here](https://aclanthology.org/2025.ldk-1.1.pdf)

# Citation
@inproceedings{ajayi-etal-2025-diasafety,
    title = "{D}ia{S}afety-{CC}: Annotating Dialogues with Safety Labels and Reasons for Cross-Cultural Analysis",
    author = "Ajayi, Tunde Oluwaseyi  and
      Arcan, Mihael  and
      Buitelaar, Paul",
    editor = "Alam, Mehwish  and
      Tchechmedjiev, Andon  and
      Gracia, Jorge  and
      Gromann, Dagmar  and
      di Buono, Maria Pia  and
      Monti, Johanna  and
      Ionov, Maxim",
    booktitle = "Proceedings of the 5th Conference on Language, Data and Knowledge",
    month = sep,
    year = "2025",
    address = "Naples, Italy",
    publisher = "Unior Press",
    url = "https://aclanthology.org/2025.ldk-1.1/",
    pages = "1--12",
    ISBN = "978-88-6719-333-2",
    abstract = "A dialogue dataset developed in a language can have diverse safety annotations when presented to raters from different cultures. What is considered acceptable in one culture can be perceived as offensive in another culture. Cultural differences in dialogue safety annotation is yet to be fully explored. In this work, we use the geopolitical entity, Country, as our base for cultural study. We extend DiaSafety, an existing English dialogue safety dataset that was originally annotated by raters from Western culture, to create a new dataset, DiaSafety-CC. In our work, three raters each from Nigeria and India reannotate the DiaSafety dataset and provide reasons for their choice of labels. We perform pairwise comparisons of the annotations across the cultures studied. Furthermore, we compare the representative labels of each rater group to that of an existing large language model (LLM). Due to the subjectivity of the dialogue annotation task, 32.6{\%} of the considered dialogues achieve unanimous annotation consensus across the labels of DiaSafety and the six raters. In our analyses, we observe that the Unauthorized Expertise and Biased Opinion categories have dialogues with the highest label disagreement ratio across the cultures studied. On manual inspection of the reasons provided for the choice of labels, we observe that raters across the cultures in DiaSafety-CC are sensitive to dialogues directed at target groups compared to dialogues directed at individuals. We also observe that GPT-4o annotation shows a more positive agreement with DiaSafety labels in terms of F1 score and phi coefficient."
}
