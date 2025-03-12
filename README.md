<span style="font-size: 20px;">Championship League Veri Analizi Projesi</span>
![Proje Logosu](championshipleaguelogo.png)
Bu proje, Championship League futbol maçlarına ait veri setini incelemek ve analiz etmek amacıyla oluşturulmuştur. 
Veri seti, maç sonuçları, takım performansları, gol istatistikleri,şut istatistikleri,sarı ve kırmızı kart istatistikleri,hakem istetikleri ve daha birçok bilgi içermektedir. 
Bu projede, veri seti üzerinde çeşitli analizler yapılmış ve sonuçlar görselleştirilmiştir.

<span style="font-size: 20px;">Veri Seti Hakkında</span>
Veri seti, Championship League'de oynanan maçlara ait bilgileri içermektedir.
Veri seti, 2004/2005 - 2024/25 (Sezon Ortası) arasındaki tarihsel verileri kapsamaktadır.


<span style="font-size: 20px;">Veri Seti Sütun Açıklamaları</span>
Veri seti, aşağıdaki 25 farklı değişkeni içermektedir:

1- Date: Maçın oynandığı tarih.
2- Season: Maçın gerçekleştiği futbol sezonu (genellikle iki yılı kapsar, örneğin 2023-2024).
3- HomeTeam: Kendi sahasında oynayan takım.
4- AwayTeam: Deplasman takımı.
5- FTH Goals: Maç sonunda ev sahibi takımın attığı toplam gol sayısı.
6- FTA Goals: Maç sonunda deplasman takımının attığı toplam gol sayısı.
7- FT Result: Maç sonucu (H: Ev sahibi galibiyeti, A: Deplasman galibiyeti, D: Beraberlik).
8- HTH Goals: İlk yarıda ev sahibi takımın attığı gol sayısı.
9- HTA Goals: İlk yarıda deplasman takımının attığı gol sayısı.
10- HT Result: İlk yarı sonucu (H: Ev sahibi takım önde, A: Deplasman takım önde, D: Beraberlik).
11- Referee: Maçın hakemi.
12- H Shots: Ev sahibi takımın toplam şut sayısı.
13- A Shots: Deplasman takımının toplam şut sayısı.
14- H SOT: Ev sahibi takımın kaleyi bulan şut sayısı.
15- A SOT: Deplasman takımının kaleyi bulan şut sayısı.
16- H Fouls: Ev sahibi takımın yaptığı faul sayısı.
17- A Fouls: Deplasman takımının yaptığı faul sayısı.
18- H Corners: Ev sahibi takımın kazandığı korner sayısı.
19- A Corners: Deplasman takımının kazandığı korner sayısı.
20- H Yellow: Ev sahibi takım oyuncularına gösterilen sarı kart sayısı.
21- A Yellow: Deplasman takımı oyuncularına gösterilen sarı kart sayısı.
22- H Red: Ev sahibi takım oyuncularına gösterilen kırmızı kart sayısı.
23- A Red: Deplasman takımı oyuncularına gösterilen kırmızı kart sayısı.
24- Display_Order: Maçların sıralanması veya sunumu için kullanılan sayısal bir sıralama sistemi.
25- League: Maçın oynandığı lig veya yarışma.



🚀 Kullanılan Teknolojiler

Python 🐍
Pandas 📊 (Veri işleme ve analiz)
NumPy 🔢 (Matematiksel işlemler)
Matplotlib 📈 & Seaborn 🎨 (Veri görselleştirme)
SciPy 🧪 (İstatistiksel analizler)
Scikit-learn 🤖 (Makine öğrenmesi tahminleri)


🔍 Yapılan Analizler

.Genel Lig Performans Analizi
.Takım Bazında İstatistikler
.Hakem Kararlarının Etkisi
.Şut ve Gol Verimliliği
.Kart ve Faul Analizi
.Makine Öğrenmesi ile Maç Tahmini(Yapılacak)

📊 Öne Çıkan Bulgular

.Hakemlerin verdiği sarı ve kırmızı kartlar ile maç sonucu arasındaki ilişki analiz edildi.
.Belirli hakemlerin daha fazla kart gösterme eğiliminde olduğu gözlemlendi.
.Bazı takımların iç saha ve deplasman performansları arasında belirgin farklar bulundu.
.Şut verimliliği yüksek olan takımların genellikle daha yüksek puan aldığı tespit edildi.
.Takımların geçmiş verilerine dayanarak maç sonuçlarını tahmin eden bir model oluşturuldu


📜 Lisans
Bu proje MIT Lisansı ile lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasına göz atabilirsiniz.

Pull Request ve issue ile bana ve kendinize katkı vermekten lütfen çekinmeyin
