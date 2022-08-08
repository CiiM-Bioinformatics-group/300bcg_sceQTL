# Scripts or tools used in the analysis


# SingleR reference

+-------------------------------------+---------+-----------------------------------------------------------------------------------------------------------+
| Database                            | Species | Comments                                                                                                  |
| :---------------------------------: | :-----: | :-------------------------------------------------------------------------------------------------------: |
| Monaco immnune data                 | Human   | RNA-Seq profiling on 29 immune cell types consituting PBMCs sorted from 4 Singaporean-Chinese individuals |
| Human Primary Cell Atlas            | Human   | Microarray datasets derived from human primary cells                                                      |
| Blueprint / ENCODE                  | Human   | Bulk RNA-seq data for pure stroma and immune cells generated by Blueprint                                 |
| Database of Immnune Cell Expression | Human   | Bulk RNA-seq samples of sorted human immune cell populations                                              |
+-------------------------------------+---------+-----------------------------------------------------------------------------------------------------------+

# Installation of limix

Marc-Jan et al. limix QTL pipeline

Step 0 **Setup a python environment**
```python3 -m venv .env```

Step 1 **Install dependencies**

```
source .env/bin/activate
python3 -m pip install pytest tables scikit-learn

```

**Current dependencies used:**
```
+--------------+---------+----------+
| Package      | Version | Comments |
+ :----------: | :-----: | :------: |
| joblib       | 1.1.0   |          |
| numexpr      | 2.8.1   |          |
| numpy        | 1.22.3  |          |
| pytest       | 7.1.1   |          |
| scikit-learn | 1.0.2   |          |
| scipy        | 1.8.0   |          |
| tables       | 3.7.0   |          |
+--------------+---------+----------+
```

Step 2 **Clone the repo.**
```
cd tools
git clone https://github.com/single-cell-genetics/limix_qtl.git
```
