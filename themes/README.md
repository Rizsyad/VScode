# instalisasi

1. clone repository

```
git clone https://github.com/Rizsyad/VScode.git && cd VScode
```

2. jalankan perintah

```
cp -r ./themes/indosec-violet ~/.vscode/extensions/
```

3. done


untuk mengecek installisasi sudah benar
```
if ls ~/.vscode/extensions/ | grep "indosec-violet"; then echo true; fi
```

# pasang themes

silahkan refresh dulu vs codenya jika sudah

tekan tombol keyboard (`Ctrl+Shift+P` atau `Cmd+Shift+P` di Mac)

ketik > `preferences: color Theme` > enter

pilih indosec violet, done