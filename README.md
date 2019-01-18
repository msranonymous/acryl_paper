# Data-Driven Solutions to Detect API Compatibility Issues in Android: An Empirical Study

The replication package contains the following material:
- android-apis.txt: list of Android APIs (taken from CiD)
- snapshots.csv: list of the considered snapshots (date, GitHub repository URL, and commit id)
- results: folder with the results
  - acryl: results for ACRyL
    - acryl.csv: detection results
    - acryl.fixed.csv: fixed issues
    - acryl.unfixed.csv: unfixed issues
    - acryl.unique.csv: all the issues
  - cid: results for CiD
  - subset: results for the apps analyzed by both ACRyL and CiD
