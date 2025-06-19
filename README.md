# AUCAD: Automated Construction of Alignment Dataset from Log-Related Issues for Enhancing LLM-based Log Generation

This replication package contains supplementary material for the paper "AUCAD: Automated Construction of Alignment Dataset from Log-Related Issues for Enhancing LLM-based Log Generation".

## Dataset

The dataset is available in [dataset](dataset).

- AucadLog Dataset: [aucad_log.json](dataset/aucad_log.json)
- LANCE Dataset
    - Training set: [lance_train.json](dataset/lance_train.json.part00)
      - Considering GitHub's file size limitations, please clone the repository using *git-lfs*. 
      - Please join the `lance_train.json.part*` files by the following command to obtain the `lance_train.json` file:
        `cat lance_train.json.part00 lance_train.json.part01 lance_train.json.part02 > lance_train.json`
    - Validation set: [lance_valid.json](dataset/lance_valid.json)
    - Testing set: [lance_test.json](dataset/lance_test.json) (for ours), [lance_prompt_unilog.json](dataset/lance_prompt_unilog.json) (for UniLog)
    - See: https://doi.org/10.1145/3510003.3511561
- LogBench-T Dataset: [logbench-t_test.json](dataset/logbench-t_test.json)
    - See: https://doi.org/10.1109/ASE51524.2021.9678596

## Original Response

The original response is available in [original_response](original_response).

## Citation

```bibtex
TBD
```