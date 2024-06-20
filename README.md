# Pengurangan-Karyawan

**Deskripsi Proyek**

Proyek ini bertujuan untuk menganalisis dan memprediksi faktor-faktor yang mempengaruhi pengurangan karyawan menggunakan data Employee Attrition. Data ini mencakup informasi demografis, pekerjaan, dan keadaan pribadi dari setiap karyawan. Dengan memahami pola-pola dalam pengurangan karyawan, perusahaan dapat mengembangkan strategi yang lebih efektif untuk meningkatkan retensi karyawan dan mengurangi biaya yang terkait dengan turnover.
Dataset yang digunakan dalam proyek ini adalah Synthetic Employee Attrition Dataset. Setiap entri dalam dataset ini memiliki ID Karyawan yang unik dan berbagai fitur yang mempengaruhi pengurangan karyawan.

**Tujuan Analisis**

1. Menemukan alasan-alasan karyawan meninggalkan perusahaan dan mengidentifikasi langkah-langkah yang harus diambil oleh perusahaan untuk meminimalkan tingginya turnover.

# Load the dataset
file_path = '/content/test.csv'
data = pd.read_csv(file_path)

# Display the first few rows of the dataset to understand its structure
data.head()
