# CreoleMT 2026

> [**GMU WMT 2026 CreoleMT System Description**](https://www2.statmt.org/wmt26/pdf/2026.wmt-1.187.pdf)

We extracted creole–English parallel data from archival linguistic resources for 28 creole languages.
The data is in `data/`, with one password-protected zip file per language pair.
Use `unzip.sh` to extract data; it reads the password from the `PASSWORD` environment variable.
The password is `drowssap`.

Each extracted file is a JSONL file with one sentence pair per line, e.g. `{"aoa": "...", "eng": "..."}`.

**Statistics:**

| Pair      |     #Lines | #Creole words | #English words |
|-----------|-----------:|--------------:|---------------:|
| aoa-eng   |        333 |         3,009 |          3,099 |
| bah-eng   |         13 |            84 |             74 |
| brc-eng   |      1,678 |        11,629 |         13,366 |
| bzj-eng   |      6,188 |        64,917 |         65,286 |
| bzk-eng   |        260 |         2,254 |          2,328 |
| cri-eng   |        128 |           764 |            819 |
| dcr-eng   |        742 |         5,357 |          5,201 |
| fab-eng   |        556 |         4,918 |          4,992 |
| fng-eng   |        812 |         5,892 |          6,857 |
| fpe-eng   |      3,327 |        29,123 |         28,911 |
| gcr-eng   |        882 |         5,747 |          6,257 |
| gpe-eng   |        470 |         4,258 |          4,171 |
| gul-eng   |        256 |         1,819 |          1,934 |
| gyn-eng   |        591 |         6,507 |          6,763 |
| icr-eng   |        488 |         3,872 |          4,200 |
| jam-eng   |      1,681 |        14,723 |         15,697 |
| kea-eng   |      1,483 |        10,266 |         11,099 |
| kri-eng   |        933 |         6,861 |          7,022 |
| ktu-eng   |        983 |         9,853 |          9,755 |
| mue-eng   |        129 |           708 |          1,079 |
| pov-eng   |        517 |         2,953 |          3,213 |
| pre-eng   |        788 |         8,201 |          9,335 |
| rcf-eng   |        543 |         7,172 |          8,003 |
| srm-eng   |      2,955 |        22,020 |         22,244 |
| srn-eng   |        764 |         6,974 |          7,052 |
| svc-eng   |        216 |         2,056 |          2,078 |
| tpi-eng   |     20,318 |       167,310 |        163,934 |
| wes-eng   |      1,807 |        13,700 |         13,627 |
| **Total** | **49,841** |   **422,947** |    **428,396** |


## Citation
If you find this repository helpful, please cite our paper:
```
TODO
```
