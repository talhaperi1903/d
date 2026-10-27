# truOS Tarayıcı Tanılama

Togg T10X (truOS) araç tarayıcısının dışarıya açtığı web yüzeyini ölçmek için basit bir tanılama sayfası. Hiçbir şey kurmaz/yazmaz; yalnızca tarayıcının verdiği bilgileri okur ve bir indirme testi tetikler.

## GitHub Pages ile yayınlama

1. GitHub'da yeni bir repo oluştur (ör. `truos-diag`), **Public**.
2. Bu klasördeki dosyaları repoya yükle (web arayüzünden "Add file → Upload files" ile `index.html` ve `README.md`).
3. Repo → **Settings → Pages**.
4. **Source**: "Deploy from a branch", **Branch**: `main` / `(root)` seç, Save.
5. 1-2 dakika sonra adres hazır: `https://<kullanici-adin>.github.io/truos-diag/`
6. Bu adresi araçtaki tarayıcıda aç.

## Komut satırıyla (alternatif)

```bash
git init
git add .
git commit -m "truOS tarayici tanilama sayfasi"
git branch -M main
git remote add origin https://github.com/<KULLANICI>/truos-diag.git
git push -u origin main
```
Sonra Settings → Pages'ten yayınla.
