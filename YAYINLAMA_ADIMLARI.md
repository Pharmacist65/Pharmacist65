# GitHub Profil README Yayinlama Adimlari

Bu klasordeki `README.md`, GitHub profil sayfanda gorunmesi icin hazirlandi.

## Mantik

GitHub profil README'nin gorunmesi icin ozel repo adinin GitHub kullanici adinla birebir ayni olmasi gerekir.

Senin GitHub kullanici adin:

```text
Pharmacist65
```

Bu yuzden GitHub'da acman gereken repo adi:

```text
Pharmacist65
```

Repo yolu boyle olmali:

```text
https://github.com/Pharmacist65/Pharmacist65
```

## GitHub Uzerinden Kolay Yontem

1. GitHub'da yeni repo olustur.
2. Repository name alanina `Pharmacist65` yaz.
3. Repo public olsun.
4. `Add a README file` secenegini isaretleyebilirsin.
5. Repo acildiktan sonra `README.md` dosyasini duzenle.
6. Bu klasordeki `README.md` icerigini oraya koy.
7. `Commit changes` de.

Profilin su adreste otomatik gorunur:

```text
https://github.com/Pharmacist65
```

## Terminal Ile Yayinlama

Bu yerel klasoru direkt repo olarak kullanmak istersen:

```bash
cd "/Users/cihangirakman/Desktop/social_medya /github"
git init
git add README.md .gitignore
git commit -m "Create GitHub profile README"
git branch -M main
git remote add origin https://github.com/Pharmacist65/Pharmacist65.git
git push -u origin main
```

Not: Bu klasorde duran ornek PDF `.gitignore` ile disarida birakildi. Profil reposuna sadece gerekli README dosyasini koymak daha temiz olur.

## Profilde Sabitlemen Iyi Olacak Repolar

GitHub profilinde `Customize your pins` bolumunden su repolari sabitle:

- `clinical-intake-ai-workflow`
- `regional-health-risk-ai`
- `Revealog` veya varsa ana mobil app reposu
- `Maphise` veya varsa ana mobil app reposu
- Sedecio / portfolio ile ilgili public repo varsa onu da ekle

