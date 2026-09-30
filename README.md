def hitung_total_panen(jumlah_kg, harga_per_kg):
    return jumlah_kg * harga_per_kg


jumlah = 100
harga = 7000

total = hitung_total_panen(jumlah, harga)

print("Jumlah panen:", jumlah, "kg")
print("Harga per kg: Rp", harga)
print("Total hasil panen: Rp", total)
