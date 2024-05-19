# NaijaRC
Dataset can be found at:https://huggingface.co/datasets/aremuadeolajr/NaijaRC
  
license: cc-by-nc-4.0


language:
  - ig
  - yo
  - ha
size_categories:
  - n<1K
multilinguality:
  - multilingual
pretty_name: NaijaRC
language_details: ibo, yor, hau
tags:
  - naijarc
task_categories:
  - multiple-choice
task_ids:
  - multiple-choice-qa
configs:
  - config_name: ibo
    data_files:
      - split: test
        path: ibo/test.csv
  - config_name: yor
    data_files:
      - split: train
        path: yor/train.csv
      - split: validation
        path: yor/dev.csv
      - split: test
        path: yor/test.csv
  - config_name: hau
    data_files:
      - split: test
        path: hau/test.csv
