minggu-02

dalam bab 4 ini python memperkenalkan kontrol lain dengan beberapa diantaranya:

* dengan pernyataan if sebagai contoh:

>>> x = int(raw_input("Please enter an integer: "))
Please enter an integer: 42
>>> if x < 0:
...     x = 0
...     print 'Negative changed to zero'
... elif x == 0:
...     print 'Zero'
... elif x == 1:
...     print 'Single'
... else:
...     print 'More'
...
More

Bisa ada nol atau lebih bagian elif, 
dan bagian yang lain adalah opsional. Kata kunci ‘elif’ adalah singkatan dari ‘else if’, 
dan berguna untuk menghindari indentasi yang berlebihan. Sebuah jika ... elif ... elif ... 
urutan adalah pengganti untuk switch atau pernyataan kasus yang ditemukan dalam bahasa lain.

