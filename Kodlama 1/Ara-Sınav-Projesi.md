# **Arasınav Projesi: Wordle Oyunu Yapımı (C Dilinde)**

#lectures 

**Amaç:** Bu ödevde, kelime tahmin oyunu *Wordle*’ın basit bir sürümünü C dilinde kodlayacaksınız. Oyuncu her tahmininde kelimenin harflerinin doğru olup olmadığını görecek ve doğru kelimeyi bulmaya çalışacak.

**Ödev Gereksinimleri:**

	1.	**Kelime Listesi:** Bir dizi içinde en az 5 kelimelik bir kelime listesi oluşturun. Kelimeler beş harfli ve anlamlı olmalıdır. Örneğin: char* kelimeler[] = {"çanak", "kalem", "biber", "kargo", "kemer"};
	2.	**Hedef Kelime:** Kodunuz her çalıştırıldığında rastgele bir kelime seçerek hedef kelime olarak belirleyecek. (İpucu: srand ve rand işlevlerini kullanabilirsiniz.)
	3.	**Kullanıcı Girdisi:** Oyuncudan beş harfli bir kelime tahmini alacak ve oyuncunun girdiği tahminin geçerli bir kelime olup olmadığını kontrol edeceksiniz.
	4.	**Tahmin Kontrolü ve Geri Bildirim:** Kullanıcının tahminini hedef kelime ile karşılaştırın:
	* 	Her harfi ve konumunu kontrol edin.
	* 	Eğer harf doğru pozisyonda ise BÜYÜK HARF olarak gösterin.
	* 	Harf doğru ama yanlış konumda ise küçük harf olarak gösterin.
	* 	Harf hedef kelimede yoksa * ile gösterin.
Örnek Çıktı:
	* 	Hedef Kelime: kalem
	* 	Kullanıcının Tahmini: kemer
	* 	Çıktı: K**e*
	5.	**Kazanç ve Deneme Limiti:** Oyuncunun hedef kelimeyi bilene kadar 6 tahmin hakkı olacak. Eğer doğru tahmin edilirse, oyuncuya “Tebrikler! Doğru kelimeyi buldunuz.” mesajı verin. Aksi takdirde, “Üzgünüz, doğru kelime [hedef kelime] idi.” mesajı verin.
	6.	**Tekrar Oynama Seçeneği:** Oyunun sonunda oyuncuya tekrar oynamak isteyip istemediğini sorun.

**Teslim:** GitHub üzerinden teslim edilecektir: link

**Bonus Görevler (İsteğe Bağlı):**

	* 	Hedef kelimeyi kelimeler.txt adlı bir dosyadan rastgele seçin.
	* 	Türkçe karakterli kelimeler (ç, ş, ğ, ü, ö, ı) kullanın.

**Örnek Kod Yapısı:**

```
#include <stdio.h>
#include <string.h>
#include <stdlib.h>
#include <time.h>

int main() {
    *// Kelime listesi, rastgele seçim, tahmin kontrolü gibi ana yapıları buraya ekleyin*
    return 0;
}
```
