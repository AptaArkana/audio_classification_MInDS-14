# Klasifikasi Suara Datasest Minds-14
<p align='justify'>Project Voice Recognition meminta kamu menyelesaikan masalah pengenalan ucapan atau suara untuk meningkatkan cara interaksi manusia dengan komputer menjadi lebih baik. Sistem akan dilatih untuk bisa memahami audio dengan ragam pola bicara, gaya bicara, dialek, aksen dan frasa yang berbeda.</p>

## Dataset
<p align='justify'>MINDS-14 adalah sumber daya training dan evaluasi untuk tugas deteksi intensi dengan data lisan. Ini mencakup 14 label/class yang diambil dari sistem komersial di domain e-banking, terkait dengan contoh lisan dalam 14 ragam bahasa yang beragam.</p>

## EDA
### Visualiasi Sinyal 
<img alt="EDA sinyal" src="https://github.com/AptaArkana/audio_classification_MInDS-14/assets/79633073/7476c813-5a27-4781-8da2-f3bd53585374">

### Persebaran Class
<img alt="Persebaran Label" src="https://github.com/AptaArkana/audio_classification_MInDS-14/assets/79633073/cf09b8cc-80b8-4cca-b947-1e25769015f2">

## Hasil
<img width="232" alt="Hasil Model" src="https://github.com/AptaArkana/audio_classification_MInDS-14/assets/79633073/3d6df305-e589-4479-a5e8-d5c21bdd7fc2">
<p align='justify'>Walau sudah mencari hyperparameter paling optimal dengan menggunakan library optuna namun model masih memiliki kinerja yang kurang. Ini bisa disebabkan karena kurangnya tahapan dalam preprocesessing.</p>

