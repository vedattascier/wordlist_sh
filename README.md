
# Kişiye Özel Wordlist Oluşturma Aracı

Bu proje, kişiye özel bir wordlist oluşturmanıza yardımcı olur. Python betiğimiz ve bir shell betiği içerir. Python betiği, kurban bilgilerini toplar ve bir dosyaya kaydeder. Shell betiği ise Python betiğini çalıştırmak için kullanılabilir.

## Özellikler

- **Kurbanın Adı**
- **Kurbanın Soyadı**
- **Kurbanın Çocuğunun Adı**
- **Kurbanın Eşinin veya Sevgilisinin Adı**
- **Kurbanın Yaşadığı İl**
- **Kurbanın Yaşadığı İlçe**
- **Kurbanın Kullanıcı Adı**
- **Kurbanın TC No**
- **Kurbanın En Sevdiği Hayvanın Adı**
- **Kurbanın Plaka**
- **Kurbanın Telefonu**
- **Doğum Tarihi** (isteğe bağlı)
- **En çok kullanılan parolalar**

## Kurulum

1. **Python Kurulumu**

   Python 3.x sürümünü [Python'un resmi sitesinden](https://www.python.org/downloads/) indirebilirsiniz.

2. **Projeyi İndirme**

   Bu projeyi GitHub'dan indirebilir veya klonlayabilirsiniz:

   ```bash
   git clone https://github.com/vedattascier/wordlist_py.git
   ```



## Kullanım

### Python Betiğini Çalıştırma

1. Python betiğini doğrudan çalıştırmak için terminal veya komut istemcisinde aşağıdaki komutu kullanın:

   ```bash
   python3 wordlist.py
   ```

2. Betik çalıştığında, aşağıdaki bilgileri girmeniz istenecektir:
   - **Kurbanın Adı**
   - **Kurbanın Soyadı**
   - **Kurbanın Çocuğunun Adı**
   - **Kurbanın Eşinin veya Sevgilisinin Adı**
   - **Kurbanın Yaşadığı İl**
   - **Kurbanın Yaşadığı İlçe**
   - **Kurbanın Kullanıcı Adı**
   - **Kurbanın TC No**
   - **Kurbanın En Sevdiği Hayvanın Adı**
   - **Kurbanın Plaka**
   - **Kurbanın Telefonu**
   - **Doğum Tarihi** (isteğe bağlı)
   - **En çok kullanılan parolalar**


3. Bilgiler, kurban adıyla aynı ada sahip bir `.txt` dosyasına kaydedilecektir.

### Shell Betiğini Kullanma



   ```bash
   echo "alias wordlist='python3 /home/vedattascier/wordlist_py/wordlist.py'" >> ~/.bashrc
   ```

   ```bash
   echo "alias wordlist='python3 /home/vedattascier/wordlist_py/wordlist.py'" >> ~/.zshrc
   ```



## Notlar

- Doğum tarihi 0, 8 veya 10 karakter uzunluğunda olabilir. Bu alanı boş bırakabilirsiniz.
- Terminal başlığı, betiğin çalıştığı sürede "vedattascier" olarak ayarlanır.

## Katkıda Bulunanlar

- **Vedat Taşçıer** - [GitHub Profiliniz](https://github.com/vedattascier)

## Lisans

Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır.

## İletişim

Sorularınız veya önerileriniz için lütfen [Vedat Taşçıer](https://www.vedattascier.com/#iletisim) ile iletişime geçin.
