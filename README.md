# Tentang Project
Project ini merupakan final task yang saya kerjakan setelah kurang lebih 1 bulan mengikuti Project Based Virtual Internship IDX Partners x Rakamin Academy

# Company Profile
IDX Partners perusahaan IT solution yang berfokus pada data analytics dan pengambil keputusan dimana perusahaan ini menawarkan solusi teknologi yang komprehensif.

# Problem Statement
Suatu lending campany yang bekerja sama dengan ID/X Partners membutuhkan bantuan untuk membagun sebuah model yang mampu melakukan prediksi credit risk dari dataset yang diberikan guna mempermudah lending company
dalam menentukan peminjam yang pantas di berikan pinjaman dan tidak
pantas. Sehingga perusahaan dapat meningkatkan efisiensi waktu dalam
menganalisa ajuan pinjaman dan menghindari kerugian.

Credit risk sangat penting untuk di kelola oleh lending company untuk
menghindari kerugian yang disebabkan karena peminjam yang tidak mampu / gagal mengembalikan uang/pinjaman yang diberikan. 

# Goals
Membantu perusahaan dalam menentukan peminjam yang high risk dan low risk.

# Objective
* Memahami tentang dataset
* Memprediksi credit risk dari peminjam

# Tahapan yang dilakukan
* `Expolatory Data Analysis`, melakukan descriptive statistic, Univariate analysis, dan multivariate analysis
* `Preprocessing`, melakukan handle missing value, outlier, feature engineering, feature selection, feature encoding, split data, feature scaling, dan handle imbalance data
* `Modelling` mencoba beberapa algoritma untuk melihat performa terbaik.
* `Evaluasi Hasil` menggunakan confussion matrix ROC sebagai acuan menentukan performa terbaik.

# Kesimpulan
* Model Machine Learning XGB Classifier memiliki performa ROC yang tinggi di banding model lain yang di uji yaitu 99.63% data training dan 96.32% testing. Namun Setelah melakukan pengecekan dengan cross validation, terjadi overfitting dimana model terlalu beradaptasi dengan data training sehingga performa di data testing turun menjadi 88.41%.
* Jika di tinjau dengan mempertimbangan overfitting atau tidak, model machine learning longistic Regression dan Ada boost memiliki performa ROC terbaik dan cenderung overfitting yang rendah.
