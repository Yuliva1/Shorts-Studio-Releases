# Shorts Studio

Uzun yayınlarını ve videolarını (YouTube, Kick ya da kendi dosyan) otomatik
olarak **dikey 9:16 shorts** kliplerine çeviren, tamamen **bilgisayarında
çalışan** bir Windows uygulaması. Videoların hiçbir sunucuya yüklenmez.

- Konuşmayı yazıya döker (Whisper), heyecanlı/komik anları bulur
- Yüz/hareket takipli kadraj, kamera-üstte oyun-altta düzen
- Karaoke altyazı, başlık bandı, filigran
- Kurgu masası: kesim (jump cut), kadraj anahtar kareleri, yakınlaştırma, bip,
  sessizlikleri tek tıkla kesme
- Beğendiğin/beğenmediğin kliplerden öğrenir (isteğe bağlı)

## İndir

Sağdaki **Releases** bölümünden en son `ShortsStudio-Setup-x.y.z.exe`
dosyasını indir ve çalıştır. Yönetici izni gerekmez.

> İlk çalıştırmada Windows "kişisel bilgisayarınızı korudu" diyebilir
> (dosya imzasız). **Ek bilgi → Yine de çalıştır**'a bas.

## Gereksinimler

- Windows 10 / 11, 64 bit
- ~6 GB boş disk (uygulama + konuşma tanıma modeli)
- İnternet: yalnızca ilk kurulumda model indirmek için (~3 GB, bir kez)
- **Önerilen:** NVIDIA ekran kartı (GTX 1060 / RTX 2060 ve üstü). Uygulama
  kartı görürse "GPU paketini indir" önerir; işleme 5–10 kat hızlanır. Kart
  yoksa işlemcide çalışır, sadece daha yavaştır.

## Güncellemeler

Uygulama açılışta yeni sürüm olup olmadığına bakar (Ayarlar'dan kapatılabilir)
ve tek tıkla günceller. Klipler ve ayarların korunur.

## İsteğe bağlı: yapay zekâ sıralaması

[Ollama](https://ollama.com) kurup `ollama pull qwen2.5:7b` dersen, Ayarlar →
"Yapay zekâ ile yeniden sırala" ile aday anları yerel bir dil modeline
okutabilirsin. Bu da tamamen bilgisayarında çalışır.

## Lisanslar

Üçüncü taraf bileşenler ve lisansları kurulumda ve `THIRD_PARTY.txt`
dosyasında listelenir (FFmpeg GPL v3 dahil).
