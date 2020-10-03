Jika di lihat di gambar 02.png source code aplikasi di upload ke Github/gitlab, biasanya yang memiliki hak akses penuh di reporsitory adalah devops, sedangkan developer backend dan frontend hak aksesnya sebagai developer yang hanya bisa push dan pull code. berikut langkah-langkah dalam mendeploy aplikasi :

    # buat reporsitory baru di gitlab/github
    # developer push software ke reporsitory
    # devops membuat image menggunakan docker
    # setelah itu menyiapkan script ci/cd untuk menjalankan   atau meremot ke server sehingga kita tidak perlu masuk ke servernya langsung. Devops membuat script untuk build dan deploy
    # pertama buat script deployment ke server test/development
    # jika aplikasi sudah di testing dan berjalan normal maka script ci/cd akan menjalankan deployment ke server production/release
