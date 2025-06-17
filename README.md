# cupricccc
Yüksek Lisans için Linux ve R öğrenim aşamalarımı burada güncelleyeceğim. Kısmen online öğrenim günlüğü olacak. 
Bu dosyada olmasa da diğer dosyalarda neler yaptığımı en ufak SRA dosyası yüklemekten trimming'e kadar açıklayarak, kendi yolumun notunu tutacağım. 
Yüksek lisans hedeflerim arasında ODTÜ'de Mehmet Somel'in öğrencisi olmak ya da Sivas Cumhuriyet'de Özgül Doğan hocanın öğrencisi olmak var. 
Her ikisi için de fazla çalışmak gerek. Bu bağlamda kendimi geliştirmek için birkaç adım attım. Uzun zamandır öğrenip unuttuğum Linux'a tekrar ve okkalı bir dönüş hedefliyorum. 
Buna ek olarak R'ın basit setlerini kullanmayı öğrenme hedefindeyim. 



# 🚀 Yüksek Lisansa Yönelik Linux, R ve Veri İşleme Planı

## 🎯 Amaç
Antik DNA ve insan evrimi çalışmaları için:
- Yeterli düzeyde **Linux** terminal bilgisi
- Temel düzeyde **R programlama** ve veri analizi
- Antik DNA’ya özel **veri işleme araçlarına** giriş

---

## 📁 A. LINUX — 2 Hafta

### 🔑 Hedefler
- Komut satırında dosya yönetimi
- Bash script yazabilme
- Bioinformatik araçları indirip çalıştırma

### 🔧 Öğrenilecekler
- **Temel Komutlar:** `ls`, `cd`, `cp`, `mv`, `rm`, `mkdir`, `grep`, `head`, `tail`, `less`
- **Gelişmiş:** `awk`, `sed`, `find`, `xargs`
- **Script:** `.sh` dosyası, `for`, `if`, `while`
- **Yönetim:** `chmod`, `chown`, `sudo`, `apt`, `conda`, `wget`, `git`

### 📌 Uygulama Örnekleri
- 1000 Genomes veri indir
- `fastqc`, `samtools`, `bcftools` kur ve çalıştır
- `for` döngüsü ile çoklu dosya işleme

### 📚 Kaynaklar
- https://missing.csail.mit.edu
- https://github.com/holtjma/intro-to-bioinformatics-linux

---

## 📊 B. R PROGRAMLAMA — 3 Hafta

### 🔑 Hedefler
- Veri analizi, görselleştirme
- PCA ve temel popülasyon genetiği analizleri

### 🔧 Öğrenilecekler
- **Temel Syntax:** Vektör, dataframe, fonksiyon
- **Paketler:** `dplyr`, `tidyr`, `ggplot2`, `readr`, `tibble`
- **Genetik analiz:** `vcfR`, `adegenet`, `pegas`, `factoextra`

### 📌 Uygulama Örnekleri
- PCA analizi ve görselleştirme
- VCF dosyasını R'de okuma, dönüştürme
- Popülasyon içi varyasyon analizleri

### 📚 Kaynaklar
- https://r4ds.hadley.nz/
- https://grunwaldlab.github.io/Population_Genetics_in_R/

---

## 🧬 C. ANTİK DNA VERİ AKIŞI — Uzun Vadeli

### 🔑 Hedefler
- Veri tipi farklarını anlamak: FastQ → BAM → VCF
- Basit pipeline’ları çalıştırabilmek

### 🔧 Öğrenilecekler
- **Veri Temizleme:** `fastqc`, `cutadapt`, `AdapterRemoval`
- **Haritalama:** `bwa`, `bowtie2`
- **Dosya İşleme:** `samtools`, `mapDamage`, `angsd`
- **Pop gen:** `plink`, `vcftools`, `bcftools`, `ADMIXTOOLS` (ilerisi için)

### 📌 Uygulama Örnekleri
- Bir antik DNA projesi örneğini terminalde yeniden oluştur
- `samtools view`, `bamstats`, `depth` gibi komutlarla BAM dosyası analizi
- `angsd` ile site frequency spectrum veya genotype likelihood hesaplama

### 📚 Kaynaklar
- https://www.ebi.ac.uk/training/online/course/ebi-next-generation-sequencing-practical-course
- https://github.com/ekg/angsd-wrapper

---

## 🗓️ Haftalık Plan (Örnek)

| Gün      | Konu                              | Süre     |
|----------|-----------------------------------|----------|
| Pazartesi| Linux temel komutlar              | 1.5 saat |
| Salı     | Bash + program kurma              | 2 saat   |
| Çarşamba | R temelleri ve `ggplot2`          | 1.5 saat |
| Perşembe | PCA analizi (R)                   | 2 saat   |
| Cuma     | `vcfR` + antik DNA veri analizi   | 2 saat   |
| Cumartesi| Telafi veya tekrar                | Opsiyonel|
| Pazar    | Hafif tekrar + GitHub güncelleme  | 1 saat   |

---

## 💼 CV ve Portfolyo İçin

- [ ] GitHub'da bir repo aç: `ancient-dna-pipeline`
- [ ] Her hafta öğrendiğin komutları, analizleri `.md` dosyalarına yaz
- [ ] Küçük veri örnekleriyle analiz akışını belgeli şekilde kaydet
- [ ] README içine örnek görseller, grafikler ekle

---

## ✅ Son Notlar

- Her şeyin “tam” olması gerekmiyor; işleyen bir altyapı inşa etmen yeterli.
- Tekrar aynı yerden başlamamak için haftalık not al ve GitHub repo’nu canlı tut.
- İleride bu temel, master veya doktora başvurularında elmas gibi parlayacak.
