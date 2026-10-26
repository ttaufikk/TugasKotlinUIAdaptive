# TugasKotlinUIAdaptive
Tugas pemrograman mobile membuat aplikasi kotlin dengan UI adpative dengan jetpack compose.
- cara membuka di android studio : 
1. extract zip
2. open project di android studio
3. buka folder studentplanner_jetpackcompose
4. jika terjadi error ketika di build , buka gradle/libs.versions.toml build dan ubah isi dari ini :
coreKtx = "1.17.0"
lifecycleRuntimeKtx = "2.9.4"
activityCompose = "1.10.1"
composeBom = "2025.04.01"
