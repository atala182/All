# 3D InCertA Kurumsal Site

Statik site (`index.html`) + Supabase iletişim formu + etkileşimli 3D basınçlı tank (three.js).

## Kurulum
1. Supabase > SQL Editor'da `supabase.sql` dosyasını çalıştırın.
2. Supabase > Project Settings > API bölümünden **anon public** anahtarı kopyalayın.
3. `index.html` içinde `SUPABASE_ANON_KEY` değerini bu anahtarla değiştirin (service_role anahtarını asla koymayın).
4. GitHub'a yükleyin:
   ```bash
   git init && git add . && git commit -m "3D InCertA site"
   git branch -M main
   git remote add origin https://github.com/KULLANICI/3d-incerta-site.git
   git push -u origin main
   ```
5. Vercel'de repoyu içe aktarın (framework: Other, build komutu yok) ve yayınlayın.

## Mesajları görmek
Supabase > Table Editor > `contact_messages`.
