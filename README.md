# tugas_pbo
Fungsional programming dan Object-Oriented Programming (OOP)
# Contoh program fungsional programming pada Python:
# Fungsi rekursif untuk menghitung faktorial
def faktorial(n):
    if n == 0:
        return 1
    else:
        return n * faktorial(n-1)

print(faktorial(5))'''

# Contoh program untuk menghitung kuadrat dari setiap bilangan dalam list
'''numbers = [1, 2, 3, 4, 5]

squares = list(map(lambda x: x**2, numbers))

print(squares)



# Contoh program OOP pada Python:
# Membuat kelas Mahasiswa
class Mahasiswa:
    def __init__(self, nama, npm):
        self.nama = nama
        self.npm = npm

    def info(self):
        print(f"Nama: {self.nama}, NPM: {self.npm}")

# Membuat objek dari kelas Mahasiswa
mhs1 = Mahasiswa("Neli Agustin", "G1A022048")
mhs2 = Mahasiswa("Ulfa  Stevi Juliana", "G1A022042")

# Memanggil metode info pada objek mhs1 dan mhs2
mhs1.info()
mhs2.info()


# Contoh program untuk menghitung volume bola
import math

class Sphere:
    def __init__(self, radius):
        self.radius = radius

    def volume(self):
        return (4/3) * math.pi * self.radius ** 3

sphere = Sphere(5)

print(sphere.volume())
