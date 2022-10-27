# layout-flexbox
Layout Flexbox basic task for MEA

layout flexbox 

Dalam task ini dibuat layout flexbox dengan menggunakan elemen semantic seperti header, aside, section dan article.
header terdiri dari dua element left header dan right header dipisah dengan jarak maksimal menggunakan justify-content space-between.

Pada element Body, digunakan align-items: center; karena body menggunakan display flex dan flex directionnya column, maka main axisnya adalah vertikal. Jadi align items center akan meratakan cross axisnya (horizontal) menjadi rata tengah. Jika dihapus, maka elemen dalam body akan kembali default ke rata kiri.

Bedanya, jika menggunakan justify content maka posisi content element akan diubah sesuai dengan main axis dari element tersebut, misalnya header menggunakan display flex dan direction row, maka justify content akan meratakan main axisnya. Jika justify content dihapus maka element akan kembali default ke rata kiri.

## Justify Content: 
menata elemen pada main axisnya, contoh jika menggunakan flex direction column maka main axis adalah vertikal

## Align Items:
menata elemen pada cross axis dari main axisnya, contoh jika menggunakan flex direction column maka cross axisnya adalah horizontal

## Justify Content : Space Between
mendistribusi elemen pertama pada awal bagian dan elemen terakhir pada akhir bagian elemen
