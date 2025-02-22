# UAS-Pengolahan-Citra

![image](https://github.com/user-attachments/assets/b7ba2499-5967-4d34-badd-a4f6b2a5cee7)

Pada Roberts di mana menggunakan kernel 2 x 2 memiliki hasil tepi yang cenderung tipis, kasar, dan tidak terlalu kontinu. Artinya, ini disebabkan oleh sensitivitas kernel Roberts terhadap noise atau variasi intensitas yang terbilang kecil. Roberts dapat digunakan untuk aplikasi yang membutuhkan kecepatan tinggi dan tidak memerlukan deteksi tepi yang sangat akurat. Namun, hasilnya kurang optimal untuk gambar dengan tepi yang halus atau kompleks.

Berbanding terbalik dengan Sobel yang menggunakan kernel lebih besar sebanyak 3x3, sehingga tepi yang dihasilkan cenderung tebal, halus, dan kontinu. Hal ini dikarenakan kemampuan kernel Sobel dalam mengurangi noise dan menangkap perubahan intensitas yang lebih halus. 

Roberts lebih sesuai untuk aplikasi yang memprioritaskan kecepatan dan tidak memerlukan deteksi tepi yang sangat akurat, seperti dalam sistem real-time atau pemrosesan gambar sederhana.
Sobel lebih sesuai untuk aplikasi yang membutuhkan deteksi tepi yang akurat dan halus, seperti dalam analisis citra medis atau pengolahan gambar yang memerlukan presisi tinggi.
