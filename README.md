# UAS_PBO
Menghitung Volume 
kelas Luas:
    def __init__(diri sendiri):
        self.satu = angka1
        self.dua = angka2
    def persegi_panjang(self,):
        print(self.satu * self.dua)
    def lingkaran(diri):
        print(self.satu * self.dua * self.dua)
    def segitiga(self):
        print(1/2 * (self.satu * self.dua))

Volume kelas:
    def __init__(diri sendiri):
        self.satu = angka1
        self.dua = angka2
        self.tiga = angka3
    def kubus (sendiri):
        cetak(self.satu**3)
    def balok (diri):
        print(self.satu*self.dua*self.tiga)
    def bola (diri sendiri):
        print(self.satu*self.dua*(self.tiga**3))
    def tabung(diri):
        print(self.satu*(self.dua**2)*self.tiga)
    def jarum(diri):
        print(1/3*(self.satu*(self.dua**2)*self.tiga))


cetak("=" * 50)
print("=", "Kalkulator Luas & Volume".center(46), "=")
cetak("=" * 50)
sementara Benar:
    print("\n1. Kalkulator Luas \n2. Kalkulator Volume \n3. Keluar")
    pilihan = int(input("Masukkan Pilihan : "))
    jika pilihan == 1:
        sementara Benar:
            print("\n1. Persegi / Persegi Panjang \n2. Lingkaran \n3. Segitiga \n4. Kembali")
            pilihan = int(input("Masukkan Pilihan : "))
            jika pilihan == 1:
                angka1 = float(input("Masukkan panjang persegi : "))
                angka2 = float(input("Masukkan lebar persegi : "))
                hasil = Luas()
                hasil.persegi_panjang()
                print(input("Tekan Tombol Apapun Untuk Lanjutan"))
            elif pilihan == 2:
                angka1 = 3,14
                angka2 = float(input("Masukkan Jari-Jari Lingkaran : "))
                hasil = Luas()
                hasil.lingkaran()
                print(input("Tekan Tombol Apapun Untuk Lanjutan"))
            elif pilihan == 3:
                angka1 = float(input("Masukkan Tinggi Segitiga : "))
                angka2 = float(input("Masukkan Alas Segitiga : "))
                hasil = Luas()
                hasil.segitiga()
                print(input("Tekan Tombol Apapun Untuk Lanjutan"))
            elif pilihan == 4:
                merusak
            kalau tidak:
                print("Perintah Tidak Ditemukan")
                print(input("Tekan Tombol Apapun Untuk Lanjutan"))
    elif pilihan == 2:
        sementara Benar:
            print("\n1. Kubus \n2. Balok \n3. Bola \n4. Tabung \n5. Kerucut \n6. Kembali")
            pilihan = int(input("Masukkan Pilihan : "))
            jika pilihan == 1:
                angka1 = float(input("Masukkan panjang rusuk : "))
                angka2 = 0
                angka3 = 0
                hasil = Volume()
                hasil.kubus()
                print(input("Tekan Tombol Apapun Untuk Lanjutan"))
            elif pilihan == 2:
                angka1 = float(input("Masukkan Panjang Balok : "))
                angka2 = float(input("Masukkan Lebar Balok : "))
                angka3 = float(input("Masukkan Tinggi Balok : "))
                hasil = Volume()
                hasil.balok()
                print(input("Tekan Tombol Apapun Untuk Lanjutan"))
            elif pilihan == 3:
                angka1 = 4/3
                angka2 = 3,14
                angka3 = float(input("Masukkan Jari-Jari Bola : "))
                hasil = Volume()
                hasil.bola()
                print(input("Tekan Tombol Apapun Untuk Lanjutan"))
            elif pilihan == 4:
                angka1 = 3,14
                angka2 = float(input("Masukkan Jari-Jari Lingkaran : "))
                angka3 = float(input("Masukkan Tinggi Tabung : "))
                hasil = Volume()
                hasil.tabung()
                print(input("Tekan Tombol Apapun Untuk Lanjutan"))
            elif pilihan == 5:
                angka1 = 3,14
                angka2 = float(input("Masukkan Jari-Jari Lingkaran : "))
                angka3 = float(input("Masukkan Tinggi Kerucut : "))
                hasil = Volume()
                hasil.kerucut()
                print(input("Tekan Tombol Apapun Untuk Lanjutan"))
            elif pilihan == 6:
                merusak
            kalau tidak:
                print("Perintah Tidak Ditemukan")
                print(input("Tekan Tombol Apapun Untuk Lanjutan"))
    elif pilihan == 3:
        merusak
    kalau tidak:
        print("Perintah Tidak Ditemukan")
        print(input("Tekan Tombol Apapun Untuk Lanjutan"))
