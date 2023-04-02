# Arduino-serial-port-light-control
## Langkahnya
1. Siapkan perangkat keras, yaitu Arduino, LED (lampu), resistor, dan kabel jumper.

2. Hubungkan kaki positif LED ke pin 13 pada Arduino, sementara kaki negatif LED dihubungkan ke resistor, dan kabel jumper dari resistor dihubungkan ke ground pada Arduino.

3. Buka program Arduino IDE di komputer Anda dan buatlah program berikut:
## Codenya
https://github.com/fajarjulyana/Arduino-serial-port-light-control/blob/0ebd59eb5ec98e90cb5ccc490acc06be1b7d965e/src/code.cpp#L1-L29
## Uji Coba
1. Setelah selesai menulis program di Arduino IDE, upload program tersebut ke Arduino Anda.

2. Buka Serial Monitor pada Arduino IDE dengan menekan tombol ikon serial monitor atau menggunakan shortcut Ctrl+Shift+M.

3. Pada Serial Monitor, pilih baud rate yang sama dengan yang diatur dalam program yaitu 9600. Kemudian, ketikkan karakter '1' untuk menyalakan LED atau karakter '0' untuk mematikan LED.

4. Setelah Anda memasukkan karakter, Anda akan melihat LED menyala atau mati sesuai dengan karakter yang dimasukkan.

Sekarang, instruksi kontrol lampu dengan serial port Arduino sudah berhasil dibuat dan dapat digunakan sesuai kebutuhan.



