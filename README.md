# Tugas-M1
Nama : Sandi Bintara
<br>
NIM : 312010039
<br>
<br>
Syntax
<br>
<br>

```def hitung_karakter(nama, nim):
    jumlah_karakter_nama = 0
    jumlah_karakter_nim = 0
    
    for huruf in nama:
        if huruf != ' ':
            jumlah_karakter_nama += 1
    
    for angka in nim:
        if angka != ' ':
            jumlah_karakter_nim += 1
    
    return jumlah_karakter_nama, jumlah_karakter_nim

nama = "Sandi Bintara"
nim = "312010039"
jumlah_karakter_nama, jumlah_karakter_nim = hitung_karakter(nama, nim)

print("Nama :", nama)
print("jumlah karakter nama :", jumlah_karakter_nama)
print("\nNIM :", nim)
print("jumlah karakter nim :", jumlah_karakter_nim)
```