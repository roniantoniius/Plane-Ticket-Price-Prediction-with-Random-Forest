# Plane-Ticket-Price-Prediction-with-Random-Forest-RSCV--91-

## Projek Prediksi Harga Tiket Pesawat pada suatu situs 🤨 🧐 
#### 1. Business Understanding 😇 
Disini saya ingin mencoba untuk memprediksi harga tiket pesawat di India 😆😆😆. Prediksi harga tiket pesawat menjadi krusial dalam industri penerbangan untuk membantu penumpang dan perusahaan penerbangan dalam perencanaan perjalanan dan strategi harga yang efektif 😱😱. Permasalahan yang ingin diselesaikan meliputi pemahaman terhadap faktor-faktor apa yang memengaruhi fluktuasi harga tiket pesawat, seperti musim perjalanan, maskapai penerbangan, rute penerbangan, dan waktu keberangkatan. Dengan membangun model prediksi yang akurat, kita dapat membantu penumpang mendapatkan perkiraan harga tiket yang lebih baik sebelum memesan, sementara perusahaan penerbangan dapat menggunakan informasi ini untuk mengoptimalkan strategi harga mereka. Proyek ini juga bertujuan untuk memberikan wawasan yang lebih baik kepada masyarakat tentang dinamika harga tiket pesawat dan menjelaskan konsep machine learning dalam konteks yang relevan dengan industri penerbangan. Maka dari itu salah satu solusi yang bisa saya buat yaitu model prediksi (kalau bisa sampai tahap deploy dengan azure/aws). Pada kernel ini sebagian besar saya akan menggunakan beberapa teknik dari regresi linear. Ayoo 🫡


#### 2. Data Understanding 😁
Dataset tiket pesawat tahun 2019 di India merupakan kumpulan data yang berisi informasi tentang harga tiket pesawat untuk berbagai maskapai dan rute penerbangan di India. Fitur-fitur dalam dataset ini meliputi informasi seperti maskapai penerbangan, tanggal keberangkatan, bandara keberangkatan dan tujuan, rute penerbangan, waktu keberangkatan dan kedatangan, durasi penerbangan, jumlah perhentian, informasi tambahan tentang penerbangan, serta harga tiket. Dataset ini dapat digunakan untuk memprediksi atau menganalisis faktor-faktor apa yang mempengaruhi harga tiket pesawat di India pada tahun 2019, seperti musim perjalanan, popularitas maskapai, atau waktu keberangkatan.

- Airline: maskapai penerbangan yang beroperasi untuk penerbangan tertentu. Maskapai ini dapat mempengaruhi harga tiket berdasarkan reputasi, jenis layanan, dan popularitas.
- Date_of_Journey: tanggal keberangkatan penerbangan. Harga tiket pesawat dapat bervariasi berdasarkan musim, hari dalam seminggu, atau hari libur.
- Source: kota atau bandara keberangkatan dari penerbangan. Harga tiket juga bisa dipengaruhi oleh popularitas rute tertentu.
- Destination: kota atau bandara tujuan dari penerbangan. Seperti source, harga tiket bisa berbeda tergantung pada tujuan akhir.
- Route: rute penerbangan yang meliputi perhentian atau transfer yang mungkin dilakukan. Jumlah dan jenis perhentian dapat mempengaruhi harga.
- Dep_Time: waktu keberangkatan pesawat. Harga tiket bisa bervariasi tergantung pada waktu keberangkatan (pagi, siang, malam).
- Arrival_Time: waktu kedatangan pesawat di tujuan akhir. Durasi perjalanan bisa mempengaruhi harga tiket.
- Duration: Durasi penerbangan dari keberangkatan hingga kedatangan. Durasi yang lebih pendek atau lebih lama dapat mempengaruhi harga tiket.
- Total_Stops: Jumlah perhentian selama penerbangan. Harga tiket biasanya lebih mahal untuk penerbangan non-stop dibandingkan dengan yang berhenti di beberapa tempat.

- Additional_Info: Informasi tambahan tentang penerbangan seperti layanan khusus, aturan bagasi, atau keterangan lainnya. Ini mungkin mempengaruhi harga tiket.
- Price: target atau variabel yang ingin diprediksi. Harga tiket pesawat adalah variabel kontinu yang ingin diestimasi berdasarkan fitur-fitur lain dalam dataset.

#### 3. Data Preparation: Feature Engineering 😢
- Outlier Removal
- Analisis Unvariate dan Bivariate

#### 4. Modelling 😨 😰
- Decision Tree Regressor
- Random Forest Regressor
- XGGradient Boost

#### 5. Evaluation 🧐 🤓 😎
- MSE
- RMSE
- R2
