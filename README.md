# annotated-transformer-indonesia
This is a commented translation into Bahasa Indonesia of "The Annotated Transformer" by Alexander Rush.

Attention merupakan teknik yang pada saat ini merupakan teknik yang memberikan performa *state-of-the-art* pada banyak tugas pada Pengolahan Bahasa Alami (*Natural Language Processing*). Teknik ini pertama kali diperkenalkan oleh Bahdanau dkk. (2014) dalam makalah "Neural Machine Translation by Jointly Learning to Align and Translate", namun menjadi sangat populer pada tahun belakangan ini melalui makalah Vaswani dkk. (2017), "Attention is All You Need", yang selain memberikan performa penerjemahan yang unggul dengan biaya komputasi lebih rendah, juga merupakan makalah pertama di mana *attention* dipergunakan secara murni tanpa menggunakan arsitektur rekurensi misalnya dengan RNN.

Python Notebook ini merupakan terjemahan bahasa Indonesia dari "The Annotated Transformer" yang ditulis oleh Alexander Rush, dengan disertai komentar oleh penerjemah (Renny). Kode-kode ini telah dicoba dengan modifikasi untuk berjalan pada satu GPU, namun kode yang dituliskan di sini adalah kode dari posting asli di sini (http://nlp.seas.harvard.edu/2018/04/03/attention.html), demi kelengkapan kode. Untuk dapat dijalankan pada CPU, kode ini juga perlu dimodifikasi, namun tampaknya eksperimen pada CPU tidak terlalu feasibel untuk arsitektur yang dipergunakan. Terakhir, jangan lupa pula untuk memperhatikan isu-isu dependensi pustaka (*library*), dan versinya, seandainya Anda menemukan masalah. Konfigurasi yang sesuai untuk kode dapat menggunakan kode yang terdapat pada Google Colab pada alamat yang tercantum pada *notebook* ini, namun tampaknya versi `torchtext` yang sesuai untuk mempergunakan kode secara langsung adalah versi 0.2.3. Tentunya versi lain juga dapat dipergunakan, namun sekali lagi Anda perlu melakukan modifikasi pada kode sesuai versi pustaka yang Anda pergunakan.

Akhir kata, selamat mencoba, dan semoga bermanfaat.

--Renny
