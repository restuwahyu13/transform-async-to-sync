# How To Fix Race Codition

Race condition adalah dimana sebuah process saling balap membalap satu sama lain, katakanlah saya mempunyai sebuah fungsi A dan fungsi B, yang dimana fungsi B di eksekusi terlebih dahulu sebelum process fungsi A itu di eksekusi, inilah yang dinamakan race condition yang dimana process nya itu bersifat asyncronus (non blocking), untuk mengatasi masalah ini semua anda bisa menggunakan module yang bernama `async-mutex` atau `mutexify`, untuk merubah asyncronus (non blocking) process menjadi asyncronus (blocking) process agar tidak terjadinya race condition, pada fungsi yang telah kita buat.