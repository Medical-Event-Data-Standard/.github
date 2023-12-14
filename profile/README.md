# Medical Event Data Standard
This organization contains GitHub Repositories for the _Medical Event Data Standard_ (MEDS), a simple dataset schema for machine learning over electronic health record (EHR) data. Unlike existing tools, pipelines, or common data models, MEDS is a minimal standard designed for maximum interoperability across datasets, existing tools, and model architectures. By providing a simple standardization layer between datasets and model-specific code, MEDS can help make machine learning research for EHR data dramatically more reproducible, robust, computationally performant, and collaborative. Alongside this report, we also release several existing integrations with models, datasets, and tools, and will work actively with the community going forward for further adoption and use. See [our draft proposal](https://github.com/Medical-Event-Data-Standard/.github/blob/main/Medical_Event_Data_Standard.pdf) for more details, and please leave comments or questions via github issues to help us improve this effort!

Relevant repos:
  * The MEDS schema: https://github.com/Medical-Event-Data-Standard/meds
  * Some reference MEDS ETLs: https://github.com/Medical-Event-Data-Standard/meds_etl
  * [IN PROGRESS] MEDS transformations for data pre-processing: https://github.com/Medical-Event-Data-Standard/meds_transformations
  * [IN PROGRESS] A sample MEDS model for binary classification using some of the transformations and showing how the schema can be used: https://github.com/Medical-Event-Data-Standard/meds_transformations

Tools that are (or will soon be) compatible with MEDS (ordered alphabetically):
  * ESGPT: https://eventstreamml.readthedocs.io/en/latest/
  * FEMR: https://github.com/som-shahlab/femr
  * GenHPF: https://github.com/hoon9405/GenHPF/tree/master/preprocess/meds_support
  * YAIB: https://github.com/rvandewater/YAIB

Pretrained models that are compatible with MEDS:
  * clmbr-t-base: https://huggingface.co/StanfordShahLab/clmbr-t-base
