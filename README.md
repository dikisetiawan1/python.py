# python.py
nama=(input("masukan nama barang :"))

hr=int(input("harga barang :"))

jb=int(input("jumlah barang :"))

total=hr * jb

print("barang yang bernama",nama,"totalnya",total)

pem=int(input("masukan pembayarannya:"))

hutang=total-pem

if (pem >=total):

    print("jumlah kembalian anda adalah:",pem-total)
else:

    print("anda mempunya hutang sebesar:",hu****tang)