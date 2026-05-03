# Klasifikasi Daging Sapi dan Babi Berbasis Near Infrared Menggunakan ANN
## Deskripsi Proyek
Projek ini bertujuan untuk membantu masyarakat untuk membedakan ciri-ciri antara daging sapi dengan babi berbasis cahaya Near Infrared. Hasil pembacaan cahaya dari sensor cahaya Near Infrared (AS7263) akan diklasifikasikan menggunakan model ANN dan diimplementasikan pada ESP32.

## Perangkat Keras & Perangkat Lunak
1. ESP32 flash storage 4 MB
2. Sensor Near Infrared (AS7263)
3. LCD 16 x 2
4. Push Button
5. Baterai
6. Battery Shield
7. Jumper
8. Kabel Micro USB
9. Arduino IDE
10. Google Colab

## Dataset
Dataset yang digunakan pada projek ini dikumpulkan secara mandiri menggunakan sensor cahaya Near Infrared (AS7263) pada berbagai kondisi yang mungkin dapat mempengaruhi hasil pembacaan sensor, berikut dataset yang saya gunakan:
https://docs.google.com/spreadsheets/d/1gISc5Jm8_lfPKQive3rjuxklTbuFNk2EEZ4XthKUDsw/edit?usp=sharing

## Batasan
Berdasarkan percobaan yang telah dilakukan didapati bahwa terdapat batasan jarak penggunaan untuk mendapatkan hasil klasifikasi yang akurat. Selain itu, nilai pembacaan daging sapi didapati terlalu overlapping dengan objek selain daging dan daging kambing, sehingga projek ini hanya dapat digunakan untuk mengklasifikasikan daging sapi dan babi saja. 
