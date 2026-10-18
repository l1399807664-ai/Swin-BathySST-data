# Swin-BathySST research data

Result tables and observation metadata for *Swin-BathySST: High-fidelity reconstruction of complex deep-sea bathymetry from sparse soundings through multi-feature terrain awareness*.

## Contents

The repository contains 24 CSV tables: 18 result tables and 6 metadata tables. [DATA_MANIFEST.csv](DATA_MANIFEST.csv) lists the files, row counts and checksums.

The results cover method comparisons, terrain attributes, component analyses, geographic holdouts, fixed-weight transfer, matched observations, survey-line spacing and observation errors. The metadata describes observation conditions, spatial support, source products and patch roles.

## Reading the tables

Identify each comparison by its method, fold, seed, checkpoint-selection step, condition, layout and aggregation scope. GC0, GC1-GC7 and GC0-GC7 denote different aggregation scopes. Geographic folds, observation layouts and training seeds identify separate dimensions of the experiments.

Elevation and observation-consistency errors are reported in metres; slope and aspect errors are reported in degrees. Empty fields indicate unavailable measurements. TFaSR aspect results identify their finite-value scoring support in the corresponding fields.

[S1_complete_source_inventory.csv](S1_complete_source_inventory.csv) provides the original data sources and access links.

## Permissions and contact

Reuse of the authors' protected result tables and experimental metadata requires prior written authorization. Send requests to **Xiaowen Luo**, [luoxiaowen@sio.org.cn](mailto:luoxiaowen@sio.org.cn), stating the requested files and intended use. See [Rights and permissions](RIGHTS_AND_PERMISSIONS.md).
