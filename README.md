# ESP32_IO

ESP32 adalah nama dari mikrokontroler yang dirancang oleh perusahaan yang berbasis di Shanghai, China yakni Espressif Systems. ESP32 menawarkan solusi jaringan WiFi dan BLE. ESP32 menggunakan prosesor dual core yang berjalan di instruksi Xtensa LX16. Selain itu, ESP32 telah mendukung protokol komunikasi seperti I2C, UART dan SPI.

**ALAT DAN BAHAN** 
1) ESP32
2) Breadboard
3) Kabel jumper
4) Potensiometer 10k Ohm (1)
5) Sensor Capacitive Soil Moisture
6) LED (5) dan Push Button (3)
7) Multimeter
8) Resistor 330,1K, 10K Ohm (@ 3)

**A. GPIO**
1. Program ini bisa mengendalikan satu LED dengan push button dimana LED bisa menyala apabila push button ditekan dan akan mati apabila dilepaskan.



https://user-images.githubusercontent.com/121172074/209278488-fd56521a-e1fe-4978-b0f2-8e86041bdf72.mp4




2. Selanjtunya pada program GPIO yang kedua, ditambahkan 1 LED yang akan mati selama 5 setik dan menyala selama 5 detik. Apabila push button tetap ditekan tetapi waktu sudah habis, LED akan tetap mati.


https://user-images.githubusercontent.com/121172074/209063304-6791ca81-854a-452d-a14d-6ad36a9a8094.mp4


3. Pada percobaan GPIO yang ketiga menggunakan 3 LED yang dikendalikan oleh satu push button. Saat push button ditekan maka LED akan menyala secara berurutan (continue).


https://user-images.githubusercontent.com/121172074/209064986-9cb8c0b3-2421-48bf-b092-3b5cb46f4042.mp4


**B. PWM**
1. Percobaan ini menggunakan metode Pulse Width Modulation yaitu pendekatan pelebaran pulsa yang menghasilkan nilai tegangan analog dengan maksimal tegangan HIGH 3,3 V dan LOW 0 V. Pin pada PWM mengeluarkan sinyal digital yang dihasilkan dari dutty cycle (perbandingan HIGH dan LOW dalam 1 periode). LED akan menyala 5x lebih terang. Karena terdapat delay 0,015 maka LED akan redup dengan kecepatan 0,015 detik, lalu kemudian akan terang kembali.



https://user-images.githubusercontent.com/121172074/209066498-01275e63-3359-40e3-821c-4cff233d1df6.mp4


2. Percobaan yang kedua hampir sama dengan PWM yang pertama, hanya saja menggunakan 3 LED.


https://user-images.githubusercontent.com/121172074/209067060-24155b49-0197-4393-a30e-c5ecc0b2ef29.mp4



**C. ADC dan DAC**
1. Percobaan ini menggunakan potensiometer yang menghasilkan output apabila potensiometer diputar. Semakin ke kanan maka nilainya akan semakin bertambah dan sebaliknya.


https://user-images.githubusercontent.com/121172074/209260152-9453205d-2e8a-49fe-8c5d-2fe2d85ba86e.mp4



2. Percobaan ini ditambahkan dengan LED dan GPIO. Ketika program ini dijalankan akan menghasilkan output apabila potensiometer diputar ke kanan maka lampu akan semakin terang nyala lampunya dan begitupun sebaliknya.


https://user-images.githubusercontent.com/121172074/209268953-ebf8bc94-e46b-4a13-8a37-f848641e2988.mp4
