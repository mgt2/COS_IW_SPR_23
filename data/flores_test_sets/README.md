# Two New Evaluation Data-Sets for Low-Resource Machine Translation: Nepali–English and Sinhala–English

This repository contains the Wikipedia test sets from the paper:
[Two New Evaluation Data-Sets for Low-Resource Machine Translation: Nepali–English and Sinhala–English](https://arxiv.org/abs/1902.01382).

Code to reproduce the baselines is available at: https://github.com/facebookresearch/flores

V2 (2020/04/02)
+ Languages added: Khmer<>English, Pashto <> English.
+ The two newly added languages follow the same data collection procedure as V1 langauges.
+ The size of each set:

|language pair| tune (dev) |devtest|test (hold)|
|---|---|---|---|
|Sinhalese-English| 2898| 2766| 2905|
|Nepali-English| 2559| 2835| 2924|
|Khmer-English| 2378| 2309| 2320|
|Pashto-English| 3162| 2698| 2791|

V1 (2019/02/04)
+ Languages included: Sinhalese<>English, Nepali <> English.
+ Initial Sinhalese to English and Nepali to English sets that pass quality thresholds.
Fluency rating > 3.0/5.0 , Translation rating > 70.0/100.0
+ Translations with multiple references have been merged as additional training examples.
+ Direct and reverse translations are mixed  at approx. 50%.
+ Merging several references as test examples.
+ The sets are as follows:

|language pair| tune (dev) |devtest|test (hold)|
|---|---|---|---|
|Sinhalese-English| 2898| 2766| 2905|
|Nepali-English| 2559| 2835| 2924|

## Citation

```bibtex
@inproceedings{,
  title={Two New Evaluation Datasets for Low-Resource Machine Translation: Nepali-English and Sinhala-English},
  author={Guzm\'{a}n, Francisco and Chen, Peng-Jen and Ott, Myle and Pino, Juan and Lample, Guillaume and Koehn, Philipp and Chaudhary, Vishrav and Ranzato, Marc'Aurelio},
  journal={arXiv preprint arXiv:1902.01382},
  year={2019}
}
```
