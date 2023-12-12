# Preface

The content of this document mainly relies on the content of the online course
[Data Sharing in Clinical Research](https://www.bihealth.org/en/translation/innovation-enabler/quest-center/events/course/data-sharing-in-clinical-research)[^1]

# Sharing of survey data

One of the big questions of the initiators of the ISAR archive is:

---
>Is it allowed to share the pseudonymous of our noise annoyance data?

The short answer is **no**.

The longer answer is however: Yes, if it is anonymous. According to the GDPR, personal data protection principles do not apply to anonymous data. This means that the GDPR does not apply to data that has been stripped of any identifying information and cannot be used to identify an individual.

If there is no legal basis (such as the informed consent) for the researcher to share personal data of study participants, anonymisation is one potential option to share the data.

Even if there is a legal basis for sharing personal data, it is important to minimize the data as much as possible. Data minimization is a principle in the General Data Protection Regulation (GDPR). The goal of data minimization is to protect the privacy of individuals by limiting the amount of personal data collected and processed.

Even in case, that the informed consent allows for data sharing, it is **not allowed to publish pseudonymised data!** 


## Important terms

| Term | Description |
| :--- | --- |
|Personal data|According to recital 26 of the [GDPR](https://gdpr-info.eu/), personal data is defined as any information relating to an **identified or identifiable** natural person (data subject), whether by **direct** or **indirect means**.|
|Direct identifiers|Pieces of information that can be used to identify, locate, or contact an individual without any additional context or information.|
|Indirect identifiers|Pieces of information that, when combined with other information, can be used to identify an individual.|
|Sensitive attributes|A special category of data where it can be assumed that individuals do not want others to know this information about them. Special categories of data, such as genetic, biometric, or health data, are expected to be particularly sensitive.|
|Pseudonymised data|Data that could be used to re-identify an individual with additional information.|
|Anonymised data|Data that has undergone the process of anonymisation.|
|Anonymous data |Data that can no longer be attributed to a specific individual.|

## Anonymising data

The [Opinion 05/2014 on Anonymisation Techniques](https://ec.europa.eu/justice/article-29/documentation/opinion-recommendation/files/2014/wp216_en.pdf) was written by a "Working Party" set up under Article 29 of Directive 95/46/EC, which is an independent European advisory body on data protection and privacy.
It states

> The main anonymisation techniques, namely randomization and generalization, are described
> in this opinion. In particular, the opinion discusses
> 
> - noise addition
> - permutation
> - differential privacy
> - aggregation
> - k-anonymity
> - l-diversity
> - t-closeness.
> 
> It explains their principles, their strengths and weaknesses, as well as the common mistakes and failures related to the use of each technique.
> 
> The opinion elaborates on the robustness of each technique based on three criteria:
> 
> 1. is it still possible to single out an individual,
> 1. is it still possible to link records relating to an individual, and
> 1. can information be inferred concerning an individual?
> 
> Knowing the main strengths and weaknesses of each technique helps to choose how to design
> an adequate anonymisation process in a given context.
> 
> Pseudonymisation is also addressed to clarify some pitfalls and misconceptions: **pseudonymisation is not a method of anonymisation**. It merely reduces the linkability of a dataset with the original identity of a data subject, and is accordingly a useful security measure. 

### Anonymisation tools
The [ARX software](https://arx.deidentifier.org/) has been developped mainly at Charité Berlin and is desribed in this [paper](https://doi.org/10.1186/s12911-020-1041-3)[^2].
According to the homepage
> ARX is a comprehensive open source software for anonymizing sensitive personal data. It supports a wide variety of (1) privacy and risk models, (2) methods for transforming data and (3) methods for analyzing the usefulness of output data.



[^1]: Habermehl, Christina; Bobrov, Evgeny; Bernard, René (2023): Data Sharing in Clinical Research. Berlin Institute of Health@Charité. Berlin. Online verfügbar unter https://www.bihealth.org/en/translation/innovation-enabler/quest-center/events/course/data-sharing-in-clinical-research, zuletzt geprüft am 04.12.2023. 
[^2]: Eicher, J., Bild, R., Spengler, H. et al. A comprehensive tool for creating and evaluating privacy-preserving biomedical prediction models. BMC Med Inform Decis Mak 20, 29 (2020). [https://doi.org/10.1186/s12911-020-1041-3](https://doi.org/10.1186/s12911-020-1041-3)
