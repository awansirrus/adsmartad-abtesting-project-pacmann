# adsmartad-abtesting-project-pacmann
Sebuah perusahaan berinisiatif mengganti iklan yang selama ini digunakan dengan iklan yang baru. Iklan ini biasa digunakan untuk menjangkau sebanyak mungkin user mengisi kuesioner. Perusahaan menginginkan sebuah iklan yang efektif yang dapat menjangkau lebih banyak lagi user untuk mengisi kuesioner. Perusahaan kemudian dihadapkan dua pilihan, yaitu iklan statis atau iklan interaktif dengan merek SmartAd. Untuk mengetahui apakah iklan interaktif memberikan lebih banyak tanggappan terhadap kuesioner mereka, maka perusahaan akan melakukan A/B testing. Pengambilan data dilakukan dengan mengukur beberapa parameter yaitu:

auction_id: ID unik pengguna online yang telah disajikan BIO-nya. Pengguna mungkin melihat kuesioner tetapi memilih untuk tidak merespons. Dalam hal ini kolom "yes" dan "no" sama dengan nol.
eksperimen: pengguna termasuk dalam grup mana - "control" atau "exposed".
control: pengguna yang telah melihat iklan tiruan
exposed: pengguna yang telah diperlihatkan materi iklan, iklan interaktif online, dengan merek SmartAd.
tanggal: tanggal dalam format YYYY-MM-DD
jam: jam dalam sehari dalam format HH.
device_make: nama jenis perangkat yang dimiliki pengguna, mis. Samsung
platform_os: id OS yang dimiliki pengguna.
browser: nama browser yang digunakan pengguna untuk melihat kuesioner.
yes: bernilai 1 jika pengguna memilih tombol “yes” untuk kuesioner BIO.
no: bernilai 0 jika pengguna memilih tombol “no” untuk kuesioner BIO.
