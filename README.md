
### Links

https://www.youtube.com/watch?v=Ly3Dor8HZUA&list=PLZoTAELRMXVOk1pRcOCaG5xtXxgMalpIe&index=3

https://github.com/c17hawke/wafer_mlops_docs

https://c17hawke.github.io/wafer_mlops_docs/reference/

https://c17hawke.github.io/wafer_mlops_docs/stage1_init_setup/#step-10-add-remote-storage

<br>
https://cloud.google.com/architecture/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning

- https://cloud.google.com/architecture/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning#mlops_level_2_cicd_pipeline_automation

### Install

```bash
poetry install
poetry run cookiecutter https://github.com/drivendata/cookiecutter-data-science

poetry add dvc
poetry run dvc init
poetry run dvc add Training_Batch_Files/*.csv Prediction_Batch_files/*.csv
git add Training_Batch_Files/. Prediction_Batch_files/. && git commit -m "add raw data"
```
