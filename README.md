# VCoolor

## با این پلاگین ما میتونیم با پنجره ای که هنگام کد زنی برای ما باز میشه بیایم و اون کد رنگی که خودمون میخوایم رو اعمال کنیم

### برای نصب کردن داخل لینوکس ما باید اول از همه یکی از دو پکیج زیر رو داشته باشیم

‍‍‍```
sudo apt install Zenity
```

### or

```
sudo apt install yad
```

### بعد از نصب کردن این موارد ما باید plugin پایین رو داخل  .vimrc خودمون نصب کنیم
```
Plug 'KabbAmine/vCoolor.vim'
```

### الان برای استفاده کردن از اون کافیه ابتدا cursor رو جایی که میخوایم کد رنگ رو بنویسیم قرار بدیم بعد دستور :VCoolor رو توی مود command اجرا کنیم تا اون پنجره برای ما باز شه

```
:VCoolor
```
### علاوه بره :VCoolor ما میتونیم از کامند های پایین هم استفاده کنیم که تفاوت اون ها توی
```
:VCoolor
:VCoolIns r " For rgb color insertion
:VCoolIns h " For hsl color insertion
:VCoolIns ra " For rgba color insertion
```
