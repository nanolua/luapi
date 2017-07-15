# luapi

"<code>فایل API.LUA رو باز کنید
به خط 5 برید و توکن رباتی که ساختید  و میخواید از اون اینلاین دریافت بشه رو بزارید
اینلاین رو هم فعال کنید

حالا برید به خط های 10 و 12 و شناسه خودتون روبزارید
حالا بیاید به خط 162
و بجای شناسه اول شناسه ربات cli رو قرار بدید.
و بجای شناسه دوم شناسه خودتون رو قرار بدید
_________
خب حالا وارد سرور بشین ودستورات زیر رو بزنین:

cd luapi
بعد 
chmod +x launch.sh

./launch.sh

برای اجرا بااتولانچ
screen ./launch.sh
روبزنید
_______________________________________________
تو یه یوزر جدید دستورات زیر رو بزنید:

sudo apt-get update

sudo apt-get upgrade

sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev tmux subversion


wget http://luarocks.org/releases/luarocks-2.2.2.tar.gz

 tar zxpf luarocks-2.2.2.tar.gz
 
 cd luarocks-2.2.2
 ./configure; sudo make bootstrap
 sudo luarocks install luasocket
 sudo luarocks install luasec
 sudo luarocks install redis-lua
 sudo luarocks install lua-term
 sudo luarocks install serpent
 sudo luarocks install dkjson
 sudo luarocks install lanes
 sudo luarocks install Lua-cURL
sudo luarocks install luaxmlrpc
_____________________________
از سرور خارج میشیم دوباره وارد میشیم و کدهای زیر رو میزنیم:

cd luapi

chmod +x tg

chmod +x launch.sh
و بعد دستور زیر رو برای اجرای اون بزنید:
./tg -s bot.lua
بعد از شما شماره میخواد و بعد که شماره و کد رو زدید ربات ران میشه

راه اندازی بااتولانچ
screen ./launch.sh
یادتون باشه اگر با دستور 
./tg -s bot.lua 
ربات رو ران کردید
و خواستید افلاینش کنید با دستور
quit
رو تو ترمینال بزنید افلاین میشه
ctrl +c ya x نزنید.
یادتون نره تو فایل BOT.LUA
مسیر خط های 1 و 2 و 9 رو درست کنید مطابق با مسیر سرور خودتون
همچنین توی فایل API.LUA
 هم تو خط 4 مسیر رو درست کنید.
_____________________________________
قبل از این که ران بشه برید توی فایل bot.lua
تو خط 10 شناسه خودتون رو به عنوان سودو بزارید
الان برید به خط 801و بجای شناسه قرار داده شده شناسه ربات api رو بزارید.
بعد ذخیره کنید اطلاعات رو و اگر درست پیش رفته باشید اگر دستور
settings</code>"
رو در گروه بزنید

[کانال ما](http:t.me/Cybrt_Sat)

Pv
[@HsamDew](http://t.me/HsamDew)

منبع 
[@alireza_Pt](http://t.me/alireza_pt)

باتشکر از علیرضا پی تی
