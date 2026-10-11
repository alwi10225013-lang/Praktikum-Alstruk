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
