🏥 Laporan Analisis Kesehatan: Prediksi Penyakit Kronis & Pola Gaya Hidup
📝 Executive Summary
Analisis ini mengevaluasi faktor risiko dan pola manifestasi klinis terkait penyakit kronis (Diabetes, Jantung, dan Stroke) pada populasi pasien mencakup 2.000 entri data. Dataset mengintegrasikan metrik klinis (tekanan darah, kolesterol, glukosa) dengan variabel gaya hidup serta riwayat keluarga untuk mengidentifikasi indikator risiko utama.

🔍 Temuan Utama (Key Insights)
1. Prevalensi Diabetes: Analisis Glukosa vs. Status Merokok
Data menunjukkan bahwa kadar glukosa tinggi adalah pendorong utama diagnosis diabetes, melampaui pengaruh status merokok tunggal.

Kelompok Perokok (Smoking=1): Terdeteksi pada pasien dengan glukosa tinggi, contohnya Pasien 1 (154 mg/dL).

Kelompok Non-Perokok (Smoking=0): Diabetes tetap bermanifestasi signifikan jika glukosa melonjak, seperti pada Pasien 12 (178 mg/dL).

Insight: Kontrol metabolik internal (Glukosa & BMI) lebih menentukan diagnosis daripada faktor eksogen merokok saja.

2. Distribusi Penyakit Kardiovaskular (CVD) & Gender
Risiko kardiovaskular ditemukan bersifat universal di seluruh jenis kelamin, namun memiliki korelasi kuat dengan penuaan.

Pola Usia Lanjut: Kasus dominan muncul di atas usia 60 tahun (contoh: Pasien 28 & Pasien 43).

Kasus Usia Madya: Penyakit juga menyerang kelompok usia 50-an, seperti Pasien 82 dan Pasien 47.

3. Anomali Tekanan Darah: Hipertensi Sistolik Terisolasi
Ditemukan pola klinis di mana tekanan sistolik sangat tinggi namun diastolik tetap normal/rendah.

Data Klinis: Pasien 116 menunjukkan tekanan darah 179/60 mmHg.

Insight: Kondisi ini meningkatkan risiko stroke secara signifikan akibat kekakuan arteri pada pasien lanjut usia.

4. Paradoks Gaya Hidup: Aktivitas Fisik vs. Kolesterol
Ditemukan adanya variabel perancu (confounding factors) yang merusak manfaat aktivitas fisik.

Temuan: Pasien aktif (Pasien 6 & 7) tetap memiliki kolesterol tinggi (>280 mg/dL) karena pengaruh konsumsi alkohol dan merokok.

Insight: Aktivitas fisik tidak cukup untuk mengimbangi asupan metabolik yang buruk dari alkohol.

🧬 Sinergi Faktor Genetik & BMI
Variabel Riwayat Keluarga (Family_History) bertindak sebagai katalisator percepatan penyakit.

Manifestasi Ganda: Pasien dengan genetik positif cenderung menderita komorbiditas (contoh: Penyakit Jantung + Stroke pada Pasien 28).

Ambang Batas: Riwayat keluarga menurunkan "ambang batas" usia munculnya penyakit, terutama pada pasien dengan BMI kategori obesitas.

💡 Kesimpulan & Rekomendasi Klinis
Prediktor Konsisten: Hipertensi sistolik dan glukosa adalah indikator risiko paling akurat.

Skrining Dini: Pasien dengan genetik positif harus memulai pemantauan profil lipid lebih awal.

Manajemen Holistik: Pengurangan alkohol krusial untuk menjaga efektivitas aktivitas fisik terhadap kesehatan kolesterol.

📊 1. Kamus Data (Data Dictionary)
Bagian ini menjelaskan variabel yang digunakan dalam analisis:

ID_Pasien: Identifikasi unik untuk setiap entri data.

Blood_Pressure (Systolic/Diastolic): Pengukuran tekanan darah dalam mmHg.

Cholest: Kadar kolesterol total dalam darah (mg/dL).

Glucose: Kadar glukosa darah puasa (mg/dL).

Smoking/Alcohol/Physical_Activity: Variabel gaya hidup (1 = Ya, 0 = Tidak).

Family_History: Riwayat genetik penyakit kronis dalam keluarga.

🛠️ 2. Metodologi & Alat (Methodology & Tools)
Langkah-langkah teknis dalam pengolahan data:

Data Cleaning (Excel): Melakukan pembersihan dataset dan penanganan nilai yang hilang menggunakan filter dan Power Query.

Data Analysis (Pivot Tables): Mengelompokkan data berdasarkan kategori usia, gaya hidup, dan riwayat keluarga untuk menemukan korelasi penyakit.

Data Visualization (Excel Dashboard): Membangun visualisasi interaktif termasuk bar chart dan scatter plot untuk memudahkan interpretasi tren kesehatan.

Narrative Insight (NotebookLM): Memanfaatkan AI untuk mempertajam analisis kontekstual terhadap anomali data klinis.

📂 3. Panduan Penggunaan (How to Use)
Instruksi untuk mereplikasi atau melihat data:

Unduh file .xlsx dari repositori ini.

Buka file menggunakan Microsoft Excel.

Akses sheet dashboard untuk melihat visualisasi data secara interaktif.

Analisis ini dihasilkan menggunakan integrasi Data Processing (Excel) dan AI Contextual Analysis (NotebookLM).
