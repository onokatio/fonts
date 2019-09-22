# fonts

### patch nerd for inner fonr

Download fonr from https://github.com/rsms/inter release.

```
$ sudo powerpill -S fontforge
$ aria2c -x10 https://github.com/ryanoasis/nerd-fonts/archive/master.zip
$ unzip nerd-fonts-master.zip
$ ls Inter-*.otf |while read line;do ./nerd-fonts-master/font-patcher $line;done
```
