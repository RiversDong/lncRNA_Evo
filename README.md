# 1. lncRNA_age.zip
> Dating pipeline and parameters for lncRNA.

* **`20_dating.sh`**: The main script which calls:
    * `21_rbh.py`
    * `22_branch.py`
    * `23_calc_age.py`
    * `24_merge.py`
* **`ctl`**: Configuration file for BLASTn analysis for sequences > 200bp.
* **`ctl_short`**: Configuration file for BLASTn analysis for sequences > 200bp.

---

# 2. protein_age.zip
> Dating pipeline and parameters for protein-coding genes.

* **`20_dating.sh`**: The main script which calls:
    * `21_rbh.py`
    * `22_branch.py`
    * `23_calc_age.py`
* **`ctl`**: Configuration file for BLASTn analysis.
