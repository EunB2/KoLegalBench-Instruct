# KoLegalBench-Instruct

**KoLegalBench-Instruct** is a Korean legal instruction dataset constructed to train large language models in legal reasoning within the Korean legal domain.

The dataset is inspired by the task taxonomy proposed in **[LEGALBENCH](https://github.com/HazyResearch/legalbench/)**, which systematizes types of legal reasoning tasks, and reformulates legal reasoning problems based on the **IRAC (Issue–Rule–Application–Conclusion)** framework to suit Korean legal data.

KoLegalBench-Instruct publicly releases **two types of legal reasoning tasks**, described below.

---

## Tasks

### Issue-Spotting  
**(22,494 instances)**

The Issue-Spotting task is constructed using the **Casename Classification Plus** dataset from **[LBOX Open](https://github.com/lbox-kr/lbox-open)**.

It represents an ability to identify legally salient issues or case types from a given factual scenario.  
Specifically, this task is intended to capture whether a model can correctly recognize which legal issue is implicated within complex factual descriptions.

---

### Rule–Conclusion Reasoning  
**(17,830 instances)**

The Rule–Conclusion Reasoning task is constructed using the **Statute Classification Plus** dataset from **[LBOX Open](https://github.com/lbox-kr/lbox-open)**.

It represents an ability to identify applicable legal rules or statutes and derive an appropriate legal conclusion based on a given situation.  
Rather than focusing on rote memorization of legal provisions, this task emphasizes the **logical application of legal rules to factual contexts**.
