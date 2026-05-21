
  Analisis Kinerja Akademik Siswa (Student Performance Analysis)

 Deskripsi Project

Project ini berisi analisis mendalam mengenai faktor-faktor yang memengaruhi pencapaian akademik siswa. Menggunakan dataset Student Performance, proyek ini bertujuan untuk melihat bagaimana latar belakang demografi, kebiasaan belajar, dan faktor lingkungan (seperti akses internet dan keikutsertaan ekstrakurikuler) berkontribusi terhadap persentase nilai akhir siswa.

Analisis yang dilakukan mencakup pembersihan data, eksplorasi statistik deskriptif, serta visualisasi data untuk menemukan pola dan korelasi antar variabel yang ada.

Informasi Dataset

Dataset ini (`Student_Performance_Dataset.csv`) berisi 5.000 baris data bersih yang mencakup berbagai metrik terkait siswa, mulai dari nilai mata pelajaran spesifik hingga indikator kebiasaan belajar.

Berikut adalah kamus data (Data Dictionary) dari kolom-kolom yang tersedia di dalam dataset:

 1. Informasi Demografi & Latar Belakang

 `Student_ID`: ID unik untuk setiap siswa.
   `Age`: Usia siswa.
   `Gender`: Jenis kelamin siswa.
   `Class`: Tingkatan kelas siswa.
   `Parental_Education`: Tingkat pendidikan terakhir dari orang tua siswa (menunjukkan latar belakang keluarga).

2. Perilaku & Lingkungan Belajar

 `Study_Hours_Per_Day`: Rata-rata jam yang dihabiskan siswa untuk belajar di luar jam sekolah setiap harinya.
   `Attendance_Percentage`: Persentase kehadiran siswa di kelas selama tahun ajaran.
   `Internet_Access`: Ketersediaan akses internet di rumah siswa (Ya/Tidak).
   `Extracurricular_Activities`: Keterlibatan siswa dalam kegiatan di luar akademik (Ya/Tidak).

 3. Pencapaian Akademik
   
  `Math_Score`: Nilai ujian mata pelajaran Matematika.
   `Science_Score`: Nilai ujian mata pelajaran Sains/IPA.
  `English_Score`: Nilai ujian mata pelajaran Bahasa Inggris.
  `Previous_Year_Score`: Nilai rata-rata siswa pada tahun ajaran sebelumnya.
  `Final_Percentage`: Persentase nilai akhir secara keseluruhan (menjadi target utama analisis).

 4. Indikator Evaluasi

`Performance_Level`: Tingkat performa siswa yang dikategorikan berdasarkan persentase akhir (misal: Sangat Baik, Baik, Cukup, Kurang).
`Pass_Fail`: Status akhir yang menunjukkan apakah siswa tersebut Lulus atau Gagal.

  Tujuan Analisis

Beberapa tujuan utama dari analisis yang dijalankan pada notebook= ini antara lain:

1. Pembersihan Data (Data Cleaning):Memastikan dataset bebas dari nilai yang hilang (missing values) dan duplikasi agar analisis lebih akurat.
2. statistik Deskriptif: Memahami distribusi nilai akhir siswa (rata-rata, nilai tertinggi, dan terendah).
3. Analisis Eksploratori (EDA): Melihat distribusi penyebaran nilai akhir menggunakan histogram.
 Menganalisis perbedaan performa akademik antara siswa yang memiliki akses internet dan yang tidak melalui visualisasi boxplot.* Menggali korelasi antara jam belajar atau persentase kehadiran dengan nilai akhir menggunakan scatterplot.



 tools yang Digunakan

 Python 
  Pandas & NumPy
  Matplotlib & Seaborn
  SciPy

