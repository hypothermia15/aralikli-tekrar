# Uyarlama kaydı

Kaynak: [ncase/remember](https://github.com/ncase/remember), commit `c42502c` (26.08.2022), CC0 1.0. Türkçe çeviri: Oğul Can Yurdakul (özgün depodaki `tr.html`).

## 23 Kasım 2026

### Yapı
- Türkçe sayfa (`tr.html`) ana sayfa (`index.html`) yapıldı. İngilizce özgün sayfa, diğer on iki dil sayfası, bu dillere özgü stil ve yazı tipi dosyaları ile `words/` taslak klasörü kaldırıldı. Diğer diller için özgün siteye bağlantı verildi.
- `translations.txt` yalnızca Türkçe kaydı içerecek biçimde kısaltıldı. `js/comic.js` sayfa dilini dosya adından değil `<html lang>` değerinden okuyor; "aslı İngilizce" bağlantısı özgün siteye gidiyor.
- `<html lang>` değeri `en` kalmıştı, `tr` yapıldı. Paylaşım kartı adresleri bu kopyaya çevrildi.

### Gizlilik
- Sayfadaki iki gömülü YouTube videosu (youtube-nocookie.com) düz bağlantıya çevrildi. Sayfa açılırken üçüncü taraf sunucuya istek gitmiyor.
- Google Fonts çağıran iki stil dosyası (`comic-ar.css`, `comic-fa.css`) Türkçe sayfada kullanılmıyordu, dil dosyalarıyla birlikte kaldırıldı.

### Sesler
- Özgün README'de "Beeps and Boops" (Owdeo) sesi CC BY-NC olarak geçiyor. Depoda hangi dosyanın bu kaynaktan geldiği yazılı değil. README'deki diğer kaynaklarla eşleşmeyen beş arayüz sesi (`button_down`, `button_up`, `slider_down`, `slider_up`, `reset`) bu kaynaktan sayıldı ve ffmpeg ile üretilen sinüs tonlarıyla değiştirildi. Yeni sesler CC0'dır. Eşleştirme çıkarıma dayanır, doğrulanmamıştır.
- Diğer sesler değişmedi. CC BY olanların (Un Chat, Ding!, Typing) atıfları README'de duruyor.

### Metin
- Yazım ve çeviri düzeltmeleri: derslerimde, yaratıcılığı, bilinçli, anıya bağlıdır, zamanlayıcını, ihtiyacım, camiası, çizgi, soruların, takvimde, başlarda, mitokondri, Ebbinghaus'tur, Patreon, Leitner, birkaç, hiçbiriyle, hâlâ, Tabii, İnternet. Çevrilmeden kalmış İngilizce satırlar silindi ya da çevrildi (Question, decay, french, iki tekrar eden cümle).
- "cramming" karşılığı "hızlı anlatım" yerine "son dakika ezberi" yapıldı; "lectures" için "düz anlatım dersler" kullanıldı (panel ve ilgili kart).
- "fun way to learn" karşılığı "eğlenceli bir eğlenme yolu" yerine "eğlenceli bir öğrenme yolu".
- Ebbinghaus cümlesi: özgün metin "most of what you learn" diyor; çeviri "neredeyse tamamını" diyordu, "çoğunu" yapıldı.
- "Aralıklı Tekrarlama" terimi çevirmenin tercihi olarak korundu.

### İçerik
- TinyCards: Duolingo bu uygulamayı 1 Eylül 2020'de kapattı. Karşılaştırma panelindeki TinyCards bölümü yerine uyarlayanın notu kondu; seçenek listesinden, metin içi anmalardan ve bağlantılardan çıkarıldı.
- "Saçma hayran kurguları" panelindeki üç cümle (gerçek bir siyasetçinin adının geçtiği parodi) yerine uyarlama için yazılmış zararsız bir parodi kondu. Bu üç cümle özgün metnin çevirisi değildir.
- Jenerik bölümüne "Uyarlama hakkında" kutusu eklendi (kaynak, çevirmen, uyarlayan, değişikliklerin özeti, eğitim amaçlı olduğu notu).
- Nicky Case'in Patreon ve teşekkür bölümleri yazarın sözü olarak korundu.

### Doğrulanmayanlar
- Çevirinin tamamı özgün metinle cümle cümle karşılaştırılmadı; yalnızca şüpheli görülen yerler karşılaştırıldı.
- README'de kamu malı olarak geçen görsellerin (Rossetti, Le Sueur, NASA, Ebbinghaus) lisans durumu tek tek denetlenmedi.
- Sayfadaki Anki, SuperMemo, NimbleNotes ve Mnemosyne bağlantılarının güncelliği denetlenmedi.
