![LaskaKit CH9102 Programmer](https://github.com/LaskaKit/CH9102-Programmer/blob/main/img/3.jpg)

# Univerzální programátor s USB-UART převodníkem CH9102 určený k nahrávání firmware (nejen) do vývojových stavebnic LaskaKit. 

Pokud hledáš jednoduchý a levný programátor - USB-UART převodník - který můžeš použít s tvou či naší deskou s ESP32, ESP8266 nebo ESP32-C3, pak bys neměl přehlédnout právě tento. Tento převodník však můžete použít i pro desky jako je Arduino Mini, Mini Pro a to díky přepínači mezi 5V a 3.3V napájením, který na programátoru máme.

Programátor je založen na známém a odzkoušeném čipu CH9102. Na desce je také přepínač, kterým volíš jak napětí na pinu VCC, tak logickou úroveň sběrnice. Přepínač můžeš přepnout buď na 5V či 3.3V. Dalším přepínač umožňuje úplně vypnout odpojit napětí od VCC pinu.

![LaskaKit CH9102 Programmer](https://github.com/LaskaKit/CH9102-Programmer/blob/main/img/4.jpg)

S naším programátorem se také vyhneš neustálemu problému s hledáním vhodného kabelu. Buď použiješ kabel s microUSB konektorem nebo USB-C - prostě to, co máš po ruce.

CH9102 programátor má pinout stejný jako mají všechny naše vývojové desky programovatelné v Arduino IDE/PlatformIO aj. Můžeš jej ale použít i samostatně s tvou vlastní deskou či deskou jiného výrobce. 

Programátor má tři indikační LED - první signalizuje připojené napájení, druhá komunikaci na RX a třetí komunikaci na TX lince UART sběrnice. 

Maximální výstupní proud při přepnutí 3.3V výstupu je 500mA, což je dostatečný proud pro napájení nejrůznějších desek od Arduino Uno až po desky s ESP32 či ESP8266.

Kromě UART sběrnice a napájení jsou na konektoru k dispozici i piny DTR a RTS, ty se běžně používají pro přepnutí Wi-Fi a Bluetooth modulů ESP32 a ESP8266 do bootloader módu.

Instalační soubor najdeš na http://www.wch-ic.com/search?t=all&q=CH9102

Github CH9102 programátoru naleznete na https://github.com/LaskaKit/CH9102-Programmer/

K zakoupení je na naší stránce https://www.laskakit.cz/laskakit-ch9102-programmer-usb-c--microusb--uart/
