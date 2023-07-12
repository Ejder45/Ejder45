import random

def oyun():
    print("Sayı Tahmin Oyununa Hoş Geldiniz!")
    rastgele_sayi = random.randint(1, 100)
    tahmin_hakki = 5

    while tahmin_hakki > 0:
        print("Kalan tahmin hakkınız:", tahmin_hakki)
        tahmin = int(input("Bir sayı tahmin edin (1-100 arasında): "))

        if tahmin < rastgele_sayi:
            print("Daha yüksek bir sayı deneyin.")
        elif tahmin > rastgele_sayi:
            print("Daha düşük bir sayı deneyin.")
        else:
            print("Tebrikler! Doğru tahmin ettiniz.")
            break

        tahmin_hakki -= 1

    if tahmin_hakki == 0:
        print("Tahmin hakkınız bitti. Rastgele sayı:", rastgele_sayi)

oyun()
- 👋 Hi, I’m @Ejder45
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Ejder45/Ejder45 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
