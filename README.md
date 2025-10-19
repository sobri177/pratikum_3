# pratikum_3
Sobri/312510236
a = int(input("Masukkan bilangan pertama: "))
b = int(input("Masukkan bilangan kedua: "))
c = int(input("Masukkan bilangan ketiga: "))

Program meminta pengguna untuk memasukkan empat bilangan (a, b, c, dan d).
int() digunakan agar bisa menerima bilangan desimal (misal 3.5, 2.1, dll).
Tapi, walau ada d, nilai d tidak digunakan dalam perhitungan — jadi hasilnya tetap hanya membandingkan a, b, dan c.

if a >= b and a >= c:
    terbesar = a
if b >= a and b >= c:
    terbesar = b
else:
    terbesar = c

Pertama, dicek apakah a lebih besar atau sama dengan b dan c.
Jika benar, terbesar diisi dengan nilai a.
Lalu dicek lagi apakah b lebih besar atau sama dengan a dan c.
Jika benar, terbesar diisi dengan nilai b.
Jika kondisi kedua salah, berarti c yang paling besar → terbesar = c.


print(f"Bilangan terbesar adalah: {terbesar}")
Program menampilkan hasil akhir dengan format string f-string.
Misalnya, jika a=5, b=2, c=3, maka output-nya:
Bilangan terbesar adalah: 5 
