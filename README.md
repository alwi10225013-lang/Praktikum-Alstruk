# Praktikum-Alstruk

# Program Perhitungan Nilai Mahasiswa

nama = input("Masukkan Nama Mahasiswa: ")
nim = input("Masukkan NIM: ")

tugas = float(input("Masukkan Nilai Tugas: "))
uts = float(input("Masukkan Nilai UTS: "))
uas = float(input("Masukkan Nilai UAS: "))

# Menghitung nilai akhir
nilai_akhir = (tugas * 0.30) + (uts * 0.30) + (uas * 0.40)

# Menentukan status kelulusan
if nilai_akhir >= 60:
    status = "Lulus"
else:
    status = "Belum Lulus"

# Menampilkan hasil
print("\n===== HASIL NILAI MAHASISWA =====")
print("Nama Mahasiswa:", nama)
print("NIM:", nim)
print("Nilai Akhir:", nilai_akhir)
print("Status Kelulusan:", status)
alwi: nama = "Alwi Hidayat"
Nim = 10225013 
umur = 20
berat = 54.5
terdaftar = True

print("Nama:", nama)
Print ("Nim:",Nim)
print("Umur:", umur)
print("Berat:", berat)
print("Terdaftar:", terdaftar)

print("Tipe nama:", type(nama))
print("Tipe Nim:", type(nim))
print("Tipe umur:", type(umur))
print("Tipe berat:", type(berat))
print("Tipe terdaftar:", type(terdaftar))

umur = 20
print("Umur setelah diubah:", umur)
print("Tipe umur setelah diubah:", type(umur))
[22/10, 13.09] alwi: harga = 12500
jumlah = 4

total = harga * jumlah
sisa = total % 2000
diskon = 5000
harga_setelah_diskon = total - diskon

print("Harga per buku: Rp", harga)
print("Jumlah buku:", jumlah)
print("Total harga: Rp", total)
print("Sisa pembagian total dengan 2000:", sisa)
print("Harga setelah diskon: Rp", harga_setelah_diskon)
alwi: nilai = 82
kehadiran = 90

print("Memenuhi syarat nilai:", nilai >= 75)
print("Memenuhi syarat kehadiran:", kehadiran >= 80)
print("Lulus:", nilai >= 75 and kehadiran >= 80)

nilai = 70

print("Nilai setelah diubah:", nilai)
print("Memenuhi syarat nilai:", nilai >= 75)
print("Memenuhi syarat kehadiran:", kehadiran >= 80)
print("Lulus:", nilai >= 75 and kehadiran >= 80)

print("Lulus jika salah satu syarat terpenuhi:",
      nilai >= 75 or kehadiran >= 80)
[22/10, 13.13] alwi: nilai = [78, 85, 90, 85]
mahasiswa = {"nama": "Nadia", "kelas": "IF-A"}
koordinat = (5, 8)
angka = {2, 4, 4, 6, 8}

print("Nilai pertama:", nilai[0])

nilai.append(95)
print("List terbaru:", nilai)

print("Nama mahasiswa:", mahasiswa["nama"])

print("Koordinat pertama:", koordinat[0])

print("Angka unik:", sorted(angka))
alwi: poin = 100
print("Nilai awal:", poin)

poin += 25
print("Setelah poin += 25:", poin)

poin -= 10
print("Setelah poin -= 10:", poin)

poin *= 2
print("Setelah poin *= 2:", poin)

poin /= 2
print("Setelah poin /= 2:", poin)
alwi: # Data mahasiswa pertama
nama = "Alwi"
nilai_tugas = 80
nilai_ujian = 90

rata_rata = (nilai_tugas + nilai_ujian) / 2
lulus = rata_rata >= 75

print("=== REKAP NILAI MAHASISWA ===")
print("Nama:", nama)
print("Nilai tugas:", nilai_tugas)
print("Nilai ujian:", nilai_ujian)
print("Rata-rata:", rata_rata)
print("Status lulus:", lulus)

print()

# Data mahasiswa kedua
nama = "Budi"
nilai_tugas = 60
nilai_ujian = 70

rata_rata = (nilai_tugas + nilai_ujian) / 2
lulus = rata_rata >= 75

print("=== REKAP NILAI MAHASISWA ===")
print("Nama:", nama)
print("Nilai tugas:", nilai_tugas)
print("Nilai ujian:", nilai_ujian)
print("Rata-rata:", rata_rata)
print("Status lulus:", lulus)
alwi: nilai = [80, 90, 95]
nilai[0] = 85

koordinat = (5, 8)
print(nilai)
print(koordinat)
alwi: umur = 20
print(umur == 20)
alwi: nilai = 80
kehadiran = 90

print(nilai >= 75 and kehadiran >= 80)
print(nilai >= 75 or kehadiran >= 80)
alwi: angka = {2, 4, 4, 6, 8}
print(angka)
