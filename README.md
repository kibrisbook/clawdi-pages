# Clawdi Pages

GitHub Pages ile host edilen statik web siteleri.

## Deploy Edilen Siteler

### T-Rex Transfer
- **Klasör:** `/trex-transfer/`
- **Telefon:** 0555 444 33 22
- **URL:** https://clawdi.github.io/clawdi-pages/trex-transfer/

## Deploy Adımları

```bash
# GitHub reposuna push et
git remote add origin https://github.com/clawdi/clawdi-pages.git
git branch -M main
git push -u origin main

# GitHub Pages aktif et:
# 1. GitHub repo ayarlarına git
# 2. Pages bölümünde source olarak "Deploy from a branch" seç
# 3. Branch olarak "main" ve klasör olarak "/ (root)" seç
```

## Yeni Site Ekleme

1. Yeni klasör oluştur: `/yeni-site/`
2. İçine `index.html` ekle
3. Git commit ve push
4. Site https://clawdi.github.io/clawdi-pages/yeni-site/ adresinde yayında!
