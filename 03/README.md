# Pengenalan Model Bahasa Besar

1. Pelajari dan Pahami teori yang ada [disini](https://rpradeepmenon.medium.com/introduction-to-large-language-models-and-the-transformer-architecture-534408ed7e61)
2. Kuasai tutorial tentang [LLM di python](https://huggingface.co/docs/transformers/llm_tutorial)

# Penguasaan Bahasa Pemrograman Rust
1. Latihan sebanyak 8 jam mengikuti buku [8 Jam Belajar Rust](./8jamrust.pdf) sertakan buktinya. (nilai:5)
2. Praktekkan ownership,reference,borrowing,clone,copy,scope,mutable,dangling,slice disertakan contoh deklarasi dan contoh penggunaannya sebanyak 10 contoh. (nilai:5)
3. Praktekkan contoh pembuatan dan pemanggilan struct dan function sebanyak 10. (nilai:5)
4. Praktekkan cara memisahkan fungsi dan memanggilnya dari file berbeda di rust. (nilai:5)
5. Praktekkan cara penggunaan dan perbedaan perintah cargo run dan cargo build, serta penjelasan setiap baris di file cargo.toml. (nilai:5)
=>
### cargo run
- Membangun proyek dan langsung menjalankan file eksekusi. Digunakan untuk mempercepat proses pengembangan dengan melakukan kompilasi dan eksekusi dalam satu langkah.
### cargo build
- Hanya membangun proyek. Tidak menjalankan file eksekusi. Digunakan untuk memeriksa dan menghasilkan file eksekusi.
6. Jelaskan kegunaan crates.io. (nilai:5)
=> Crates.io adalah repositori yang digunakan oleh Rust, sebuah bahasa pemrograman, untuk menyimpan dan berbagi paket-paket perangkat lunak yang ditulis dalam Rust. Crates.io dapat digunakan untuk mencari dan mengintegrasikan paket-paket Rust yang relevan dalam pengembangan AI.
7. Jelaskan perbedaan membuat library dan file utama di rust. (nilai:5)
=>
### Library (crate):
Sebuah library dalam Rust adalah kumpulan fungsi-fungsi dan struktur data yang dapat digunakan oleh aplikasi lain. Biasanya dibuat dengan tujuan untuk digunakan kembali dalam berbagai proyek. Dapat diakses dan digunakan oleh aplikasi lain dengan menambahkan dependensi pada file Cargo.toml proyek mereka. Dikompilasi menjadi sebuah file .rlib atau .so (shared object) yang kemudian dapat diinkorporasikan ke dalam aplikasi lain.
### File Utama:
File utama dalam Rust adalah file yang berfungsi sebagai titik masuk utama ke dalam aplikasi. Biasanya berisi fungsi main() yang akan dijalankan pertama kali ketika program dijalankan. Digunakan untuk mengatur logika program, menginisialisasi struktur data, memanggil fungsi dari library eksternal, dan menjalankan proses aplikasi secara keseluruhan. File utama biasanya merupakan bagian dari proyek aplikasi dan menggunakan library-library atau crate-crate yang diperlukan untuk membangun fungsionalitasnya. Jadi, intinya adalah bahwa library berisi kode yang bisa digunakan oleh proyek lain, sementara file utama adalah bagian utama dari proyek yang mengatur jalannya aplikasi.
8. Praktekkan membuat web service di rust dengan panduan dari [inarust.github.io](https://inarust.github.io/). (nilai:5)


# Penguasaan Hugging Face

1. Jelaskan apa itu Hugging Face Candle dan praktekkan cara penggunaannya.(nilai : 10)
=> Hugging Face Candle adalah sebuah pustaka (library) open-source yang dikembangkan oleh Hugging Face untuk membantu dalam pengembangan dan pelatihan model-model machine learning dan pemrosesan bahasa alami (NLP). Hugging Face menawarkan berbagai alat dan utilitas untuk mempermudah integrasi model-model NLP ke dalam aplikasi, serta mendukung berbagai model prapemrosesan dan inferensi.
3. Jelaskan per baris kode program dan jalankan [phi](https://github.com/mymyid/phi). (nilai:10)
4. Jelaskan per baris kode program dan jalankan [rwkv](https://github.com/mymyid/rwkv). (nilai:10)
5. Jelaskan per baris kode program dan jalankan [mistral](https://github.com/mymyid/mistral). (nilai:10)
6. Analisis perbedaan dari ketiga model llm tersebut dari waktu generasi kalimat, akurasi dan kebutuhan komputasinya. (Nilai : 10)
7. Jealskan bagaimana cara mengatasi error di rust pada saat menjalankan aplikasi ini. (Nilai : 10)
