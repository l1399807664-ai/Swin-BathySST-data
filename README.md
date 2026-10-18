# Swin-BathySST data

Data-only research records supporting the V37 manuscript, "Swin-BathySST: High-fidelity reconstruction of complex deep-sea bathymetry from sparse soundings through multi-feature terrain awareness".

## Reuse requires permission

No open reuse licence is granted for the authors' result tables and metadata. Reuse of material protected by rights held or controlled by the authors requires prior written authorization, for both commercial and non-commercial purposes. Public inspection of this repository does not grant additional reuse permissions. Applicable law, GitHub's Terms of Service and third-party licences remain applicable.

See [Rights and permissions](RIGHTS_AND_PERMISSIONS.md). Permission requests should be directed to the corresponding author, Xiaowen Luo, at luoxiaowen@sio.org.cn.

## Contents

This package contains 18 result tables and 6 observation, spatial-support and source-metadata tables. DATA_MANIFEST.csv lists their row counts and SHA-256 checksums.

The results cover the principal g1 method comparison, terrain attributes, component comparisons, paired geometry-injection seeds, geographic holdouts, fixed-weight multibeam transfer, matched observations, survey-line spacing, and controlled observation errors. Metadata describes evaluation conditions, observation realizations, the working grid, geographic splits, source products and patch roles.

## Reading the data

Use the method, fold, seed, checkpoint-selection step, condition, layout and scope fields to identify each comparison. GC0, GC1-GC7 and GC0-GC7 are different aggregation scopes. Geographic assignments, observation layouts and training seeds are distinct dimensions. Historical g0 fixed-transfer records and matched g1 component results keep their original identities.

All result rows and retained cell values preserve their source precision. Empty or NA fields remain unavailable, not zero. The observation-condition metadata table contains the 17 formal GEBCO, multibeam and matched-I2 definitions. Training-bank, validation-recipe and obsolete I3 rows are outside this data-only subset.

Elevation and observation-consistency errors are in metres; slope and aspect errors are in degrees. Derivative metrics retain the operators and units specified in the manuscript and accompanying metadata. The TFaSR finite-aspect support rule remains explicitly identified in the result fields.

## Scope and access

This is a data-only subset of the manuscript's supporting records. It excludes executable code, model weights, implementation and checkpoint inventories, training/architecture configurations, internal file paths and execution logs. The research source code and trained weights are not publicly available because a patent application is being prepared; access and use require prior written approval from the authors. No software or weight licence is granted by this data package.

Third-party source products are not redistributed here. S1_complete_source_inventory.csv provides their original access URLs and source-specific citation or licence information.

This package does not itself claim a repository DOI, journal acceptance or completion of the journal's data-archiving requirements.
