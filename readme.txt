TUBES ML: Sentimen Analisis: Case 5 : Sentiment Analysis on Universities under APERTI BUMN Alliance through Google Review
Harus ada di Tubes:
- model baseline/model dasar 
- dan model yg diusulkan

nanti cek juga apakah model itu underfitting atau bestfitting

sentiment analisi:
- tantangan di labelling
- labelling pake LLM
- bisa bikin sentiment analisi berbasis ABSA(Aspect-Based Sentiment Analysis (ABSA)) atau berbasis aspek (jadi dia bagi ke aspik-aspek missal fasilitas, layanan, lingkungan, suasana, dll)
- analisis sentiment bisa juga pake skala missal dari 1-5( bukan hanya positif negatf netral)
- lakukan dengan minimal 2 LLM (dibandingkan)
- untuk menghasilkan aspek atau topik untuk ABSA bisa dilakukan dengan dua cara yakni metode kualitatif dan kuantitatif. kalo kualitatif artinyay kita yang menentukan aspeknya dengan cara membaca beberapa ulasan dataset dan mengelompokannya dalam aspek2 tertentu missal fasilitas, lokasi, lingkungan dll. kalo kuantitatif kita bisa menggunakan metode topic modelling misalnya dengan LDA yang sudah didapat di PSD
- bisa pake LSTM atau yg lebih maju lagi seperti Bi LSTM, atau juga CNN.
- harus ada landasan atau alas an kenapap harus kita bikin seperti ini, atau milih metode seperti ini, atau kenapa hasilnya begini, intinya kita harus tahu apa yang kita lakukan harus dengan alasan dan landasan ilmiah yang kuat.
- boleh pake SVM 
- minggu depan kita buat tahapan apa yang akan kita lakukan misalnya pengumpulan data, setelah itu ngapain, dan setelah itu lagi ngapain lagi.

==================================
Studi Kasus 5: Sentiment Analysis terhadap Universitas di bawah Naungan APERTI BUMN melalui Google Review

Komponen Wajib dalam Tugas Besar:
1. Model Dasar (Baseline Model)
	- Digunakan sebagai pembanding performa dengan model utama/usulan.

2. Model Usulan
	- Model utama yang akan dikembangkan dan dievaluasi performanya.
	- Perlu dianalisis apakah model mengalami underfitting, overfitting, atau best-fitting.

Pendekatan Analisis Sentimen:
1. Tantangan dalam Labelling Data
	- Labeling manual memakan waktu dan subyektif.
	- Solusi: Gunakan LLM (Large Language Model) untuk membantu proses pelabelan.
2. Tipe Analisis Sentimen:
	- Polaritas Umum: Positif, Negatif, Netral.
	- Skala Nilai: Misalnya skala 1–5 untuk memperkaya analisis sentimen.

3. Pendekatan Berbasis Aspek – ABSA (Aspect-Based Sentiment Analysis):
	- Sentimen dikelompokkan berdasarkan aspek tertentu seperti: Fasilitas, Layanan, Lingkungan, Suasana.

Dua pendekatan untuk menentukan aspek:
	- Kualitatif: Aspek ditentukan secara manual dari pengamatan dan pengelompokan ulasan.
	- Kuantitatif: Gunakan teknik topic modeling seperti LDA.

Penggunaan Model LLM:
- Minimal menggunakan dua model LLM untuk perbandingan performa.
- Bisa digunakan untuk klasifikasi sentimen maupun ekstraksi aspek.

Model Machine Learning yang Bisa Digunakan:
- LSTM (Long Short-Term Memory)
- Bi-LSTM (Bidirectional LSTM)
- CNN (Convolutional Neural Network)
- SVM (Support Vector Machine) sebagai baseline atau model tambahan

Hal Penting yang Harus Diperhatikan:
- Harus ada landasan teori dan alasan ilmiah yang kuat untuk: Pemilihan metode atau model, Proses labeling, Interpretasi hasil evaluasi

bisa pake LLM:
- gemini dan GPT, dibandingkan gitu

Pelabelan:
- bisa pake positif, negative, netral
- bisa pake skoring (missal 1-10)
- atau yang lainnya

ada juga zero-shot learning