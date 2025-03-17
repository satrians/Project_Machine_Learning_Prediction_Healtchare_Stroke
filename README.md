# Project_Machine_Learning_Prediction_Healtchare_Stroke
# Dataset
![Screenshot 2025-03-17 143516](https://github.com/user-attachments/assets/fc137bde-05ec-41b9-9bb2-b2647ee3a5ba)

# Latar Belakang dan Masalah
Stroke merupakan salah satu penyebab utama kematian dan kecacatan di dunia. Deteksi dini sangat penting untuk mencegah dampak fatal dari penyakit ini. Dengan kemajuan teknologi pembelajaran mesin (machine learning), terdapat potensi untuk mengembangkan model prediksi yang dapat menilai risiko stroke berdasarkan data medis, seperti usia, tekanan darah, kadar kolesterol, dan faktor lainnya. Namun, tantangan utama terletak pada pemilihan algoritma yang tepat dan ketersediaan data yang memadai untuk menghasilkan prediksi yang akurat. Proyek Machine Learning Prediction for Healthcare Stroke bertujuan untuk mengembangkan model prediksi yang dapat membantu mendeteksi risiko stroke lebih cepat dan efisien, sehingga meningkatkan upaya pencegahan dan pengobatan dini.

# Tujuan dan Target Pencapaian
Proyek Machine Learning Prediction for Healthcare Stroke bertujuan untuk mengembangkan model pembelajaran mesin yang dapat memprediksi risiko stroke berdasarkan data medis individu, seperti usia, tekanan darah, kadar kolesterol, dan faktor risiko lainnya. Tujuannya adalah meningkatkan akurasi deteksi dini stroke, sehingga memungkinkan intervensi medis lebih cepat dan pengobatan yang lebih efektif. Target pencapaiannya meliputi akurasi prediksi di atas 85%, pengembangan sistem yang memberikan hasil prediksi secara real-time, serta pengoptimalan model agar dapat digunakan dalam berbagai perangkat dan sistem informasi kesehatan. Selain itu, proyek ini diharapkan dapat memberikan laporan dan analisis untuk mendukung penelitian lebih lanjut mengenai faktor-faktor risiko stroke.

# Data Loading
- Menggunakan Dataset dari link https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset
- Membaca dataset ke dalam Dataframe
  ![Screenshot 2025-03-17 144333](https://github.com/user-attachments/assets/3fe6532a-6700-4de2-978b-737d9352ce6a)

# Data Cleaning
Proses ini bertujuan untuk membersihkan dan memvalidasi data yang digunakan dalam model. Ini mencakup penghapusan data yang tidak relevan, penanganan nilai yang hilang, serta konversi data agar siap digunakan dalam analisis dan pelatihan model.

# EDA (Exploratory Data Analysis)
Tahap ini bertujuan untuk menggali lebih dalam tentang struktur data, mendeteksi pola, hubungan antar variabel, dan menganalisis distribusi data. EDA membantu memahami karakteristik data dan menyediakan wawasan yang berguna untuk proses berikutnya, seperti rekayasa fitur.

# Feature Engineering
Pada tahap ini, fitur-fitur yang ada dalam dataset akan dievaluasi dan dimodifikasi untuk meningkatkan kemampuan model dalam melakukan prediksi. Ini bisa mencakup pembuatan fitur baru, normalisasi data, atau transformasi variabel yang lebih relevan.

# Model Architecture Definition
Setelah data dipersiapkan, tahap selanjutnya adalah mendefinisikan arsitektur model pembelajaran mesin yang akan digunakan. Pemilihan model yang tepat, seperti regresi logistik, pohon keputusan, atau jaringan saraf, akan ditentukan berdasarkan karakteristik dataset dan tujuan prediksi.

# Model Training
Pada tahap ini, model yang telah didefinisikan akan dilatih menggunakan dataset yang sudah diproses. Proses ini melibatkan penyetelan parameter dan penggunaan teknik optimisasi untuk meningkatkan akurasi prediksi model.

# Model Evaluasi
Setelah pelatihan, model dievaluasi menggunakan berbagai metrik evaluasi seperti akurasi, presisi, recall, dan F1 score. Tujuannya adalah untuk memastikan model yang dikembangkan dapat memberikan hasil yang akurat dan dapat diandalkan dalam prediksi risiko stroke.
Setelah melatih ulang model dengan hyperparameter yang dioptimalkan, maka dapat dilihat apakah performa model telah meningkat. Evaluasi performa model dapat memberikan pemahaman yang lebih baik tentang kemampuan model dalam melakukan prediksi stroke. Terakhir, dapat memilih model terbaik berdasarkan matriks evaluasi yang telah digunakan.
