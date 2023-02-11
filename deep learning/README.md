

# Deep learning model





[TOC]





## File Structure







**Transformer_based**: based on transformers, refering [Personalized Transformer for Explainable Recommendation](https://github.com/lileipisces/PETER)

**GPT2_based**: 2 models based on GPT2, refering  [DGMER-----Deep Generative Model for Explainable Recommendation](https://github.com/JumingZhao/DGMEM----Deep-Generative-Model-for-Explainable-Recommendation)and  [Personalized Prompt Learning for Explainable Recommendation](https://github.com/lileipisces/PEPLER)

**output: douban_for_*** :The file records the training process of the three models respectively

​			   **generated_*** :The file records the output results of the three models respectively



## Usage



Transformer_based: 

```python
python -u main.py \
--data_path ../reviews_s.csv \
--cuda \
--checkpoint ./douban/ \
--peter_mask >> douban.log
```





GPT2_based: 





GPT2 based model :

```python
python -u basic.py \
--data_path ../reviews_s.csv \
--cuda \
--checkpoint ./douban/ >> douban.log
```





improved GPT2 based model :

```python
python -u improved.py \
--data_path ../reviews_s.csv \
--cuda \
--checkpoint ./douban/ >> douban.log
```