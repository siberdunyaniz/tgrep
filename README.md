TGREP - Telegram Raporlama Aracı
Telegram'daki bağlantılar, gruplar ve hesapları kolayca bildirmek için güçlü bir araç ⚠️
TGREP , Telegram platformunda karşılaştığınız ihlalleri (spam, şiddet, sahte hesaplar vb.) hızlı ve etkili bir şekilde bildirmenize olanak sağlayan bir Python tabanlı raporlama aracıdır. Kullanıcı dostu bir tasarımla tasarlanmış bu araç, Telegram bağlantılarını, kanallarını ve hesaplarını raporlamayı kolaylaştırır.

Not: Bu bir test aracıdır ve kullanımından doğabilecek tüm sorumluluklar kullanıcıya aittir.

Özellikler
Telegram bağlantılarını düzenliyor ve raporlama (grup/kanal takibi ile)
Kanal ve hesap raporlama seçenekleri
Sosyal medya bağlantıları ve admin ile iletişim desteği
Raporlama işlemlerinin log kaydına kaydedilmesi
Renkli terminal arayüzü ile kullanıcı dostu deneyim
Türkçe: Şikayet Et
TGREP, aşağıdaki Telegram'da raporlama yapmanızı sağlar: tanır:

+----------------+-------------------------+
| Numara         | Yöntem                  |
+----------------+-------------------------+
| 1              | Spam Bildir             |
| 2              | Diğer Bildir            |
| 3              | Şiddet Bildir           |
| 4              | Pornografi Bildir       |
| 5              | Telif Hakkı Bildir      |
| 6              | Sahte Bildir            |
| 7              | Coğrafi Alakasız Bildir |
| 8              | Yasadışı Uyuşturucu Bildir |
| 9              | Kişisel Detaylar Bildir |
+----------------+-------------------------+
Desteklenen Platformlar
Termux ✅
Kali Linux ✅
Python (Windows/Linux) ✅
Kurulum ve Çalıştırma
Ön Gereksinimler
Python 3.x yüklü olmalı
Git'in kurulu olması
İnternet erişimi
1. Termux'ta Kurulum
Termux üzerinde aracın çalıştırılması için aşağıdaki adımları izleyin:

pkg update && pkg upgrade
pkg install python git
pip install prettytable colorama
git clone https://github.com/siberdunyaniz/tgrep.git
cd tgrep
python main.py
Şifre sorusunun cevabını ariva girin.
2. Kali Linux'ta Kurulum
Kali Linux'ta aracı çalıştırmak için:

sudo apt update && sudo apt upgrade
sudo apt install python3 python3-pip git
pip3 install prettytable colorama
git clone https://github.com/siberdunyaniz/tgrep.git
cd tgrep
python3 main.py
Şifre olarak ariva kullanın.
3. Python ile Genel Kurulum (Windows/Linux)
Herhangi bir Python destekli sistemin kurulumu için:

# Gerekli paketleri yükleyin
pip install prettytable colorama
# Depoyu klonlayın
git clone https://github.com/siberdunyaniz/tgrep.git
cd tgrep
python main.py
Giriş şifresi: ariva
Kullanım
Aracı çalıştırdıktan sonra şifreyi ( ariva ) girerek giriş yapın.
Ana menüden bir seçenek seçin:
1: Araç menüsüne girerek raporlama işlemlerini başlatın.
2: Yönetici ile iletişim geçin ( t.me/atahanarslan ).
3: Sosyal medya kanallarını ziyaret edin ( @siberdunyaniz ).
4: Çıkış yapın.
Araç menüsündeki bağlantı, kanal veya hesap raporlama seçeneklerinden birini kullanarak işlemi tamamlayın.
Uyarı
Yanlış raporlamalar hesabınızın riske girmesine neden olabilir.
Raporlama logları report_log.txt dosyasında bulunur.
Araç test amaçlıdır, ömrün kullanım sorumluluğu sahibinin mülkiyetindedir.
İletişim
Telegram Kanalı: @siberdunyanizz
Yönetici: @atahanarslan
Hoşça kalın, arkadaşlar! 🚀
