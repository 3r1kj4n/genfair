# Genderfair translation from Swedish to English and Swedish to German

Fine-tuning experiments with [NLLB-200 distilled 600M](https://huggingface.co/facebook/nllb-200-distilled-600M) on gender-fair translation


## Dataset
- Gender-balanced (F/M/X) Dataset: 1302 sentences in Swedish, English and (gender-fair) German
- Dataset includes non-binary pronouns (hen in Swedish, they in English, and dey in German)
- Training/Validation and Test Data are split manually to avoid an overlap in professions from the training to the test set
- The dataset is built on [SweWinoGender 2.0](https://spraakbanken.gu.se/en/resources/swewinogender) and [MT-GenEval](https://github.com/amazon-science/machine-translation-gender-eval)

## Sources
Anna Currey, Maria Nadejde, Raghavendra Reddy Pappagari, Mia Mayer, Stanislas Lauly, Xing Niu, Benjamin Hsu, and Georgiana Dinu (2022). MT-GenEval: A counterfactual and contextual dataset for evaluating gender accuracy in machine translation. In Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing, pages 4287–4299, Abu Dhabi, United Arab Emirates. Association for Computational Linguistics.

Adesam, Yvonne, & Bouma, Gerlof (2023). SweWinogender 2.0 (updated: 2023-03-30). Språkbanken Text. https://doi.org/10.23695/wy9w-mw74 
