# Genderfair translation from Swedish to English and Swedish to German

Fine-tuning experiments with [NLLB-200 distilled 600M](https://huggingface.co/facebook/nllb-200-distilled-600M) on gender-fair translation


## Dataset
- Gender-balanced (F/M/X) Dataset: 1302 sentences in Swedish, English and (gender-fair) German
- Dataset includes non-binary pronouns (hen in Swedish, they in English, and dey in German)
- Training/Validation and Test Data are split manually to avoid an overlap in professions from the training to the test set
- The dataset is built on [SweWinoGender 2.0](https://spraakbanken.gu.se/en/resources/swewinogender) and [MT-GenEval](https://github.com/amazon-science/machine-translation-gender-eval)
