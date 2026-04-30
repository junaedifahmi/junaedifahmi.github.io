---
title: What's went wrong with a Donut
publish: true
tags:
  - "#document-extraction"
  - "#transformer"
  - "#donut"
  - "#ocr"
enableToc: true
draft: false
---
# Which Donut?

Donut yang ini beda sih, bukan kaya donut yang seratus lima puluh ribu dapat tiga biji itu, tapi donut yang biasa dipakai buat dokument ekstraksi. Atau tepat nya Document Understanding Transformer (DONUT). Jadi intinya donut ini adalah satu model AI yang sengaja dibuat untuk menalar inputan berupa dokumen. 

## Whats wrong with current AI?
Kamu tau kah perbedaan lulusan SMA dan SMK? Yup, SMK itu sudah lebih terarah dibandingkan SMA. In the same sense, yang membedakan Donut dan Transormer model lainnya adalah arah (*downstream task*) nya. Building blok nya tetap sama, tapi donut dilatih dan diarahkan khusus untuk memahami dokumen. 

Loh terus kan model yang ada juga sudah bisa kan? Yups. Sebenernya model-model yang udah stable kaya OCR itu udah bisa banget me-*recognisi* dokumen in a sense mengekstrak kata-kata dalam dokumen tersebut. Tapi pada kenyataannya, dokumen itu bukan cuma soal kata. Tapi ada struktur yang perlu diperhatikan. Contoh yang paling besar dari limitasi OCR adalah dokumen struktur. Iya toh? OCR bisa aja mengekstrak kata-kata dengan benar, tapi ketika dihadapkan pada satu tabel, informasi yang diekstrak menjadi kurang tepat. Plain OCR tidak bisa memahami mana baris mana kolom, semua teks yang dapat dia kenali, akan disimpan apa adanya dari kiri ke kanan. Nah, makanya si DONUT ini dibuat untuk melampaui limitasi-limitasi itu.

DONUT ini dirancang, agar dapat mengekstraksi informasi yang lebih "cerdas" dibanding OCR. Kapan dia disebut lebih cerdas? yaitu ketika dia ditanya mengenai isi dari dokumen dan bisa menjawab dengan tepat. 