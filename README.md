# Enough
_It's zetas to make a man go crazy_
<br><br>

<h2>Kurulum</h2>

```console
git clone https://github.com/anonym1ux/ZetaSsms.git
cd ZetaSsms
pip3 install -r requirements.txt
python3 zetas.py
```
<h2>If it doesn’t work from the terminal, right-click the zetas.py file, then select "Open with" → "Python" (or "Run with Python").</h2>

<h2>TÜRKCESI AŞAĞIDA</h2>

<h2>(Terminalden çalışmazsa zetas.py dosyasına sağ tıklayın, ardından "Birlikte aç" → "Python" (veya "Python ile çalıştır") seçeneğini seçin.)</h2>

from PIL import Image, ImageTk

foto = ImageTk.PhotoImage(Image.open("/home/zetassavage/Resimler/Screenshot_2025-12-03_15_48_43.png"))
Label(pencere, image=foto).pack()
