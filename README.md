# Internetradio & Podkāsti (Material 3 PWA — v6)

## Kas jauns šajā versijā
1. **Latviešu podkāsti (`Podkāsti (LV)` cilne):** Iekļauti Latvijas Radio 1 un Pieci.lv raidieraksti (*Krustpunktā*, *Zināmais nezināmajā*, *Kultūras Rondo*, *Ģimenes studija*, *Monopols*, *Pieci.lv*), kā arī iespēja pievienot jebkuru citu podkāstu pēc tā RSS saites.
2. **Podkāstu vadība:** Laika josla (*Seek Bar*), `-15s` / `+30s` attīšanas pogas, ātruma maiņa (`1.0x` – `1.75x`) un automātiska klausīšanās pozīcijas saglabāšana.
3. **GitHub Actions automatizācija (`.github/workflows/update-podcasts.yml`):** Automātisks darbs, kas ik pēc 6 stundām atjauno latviešu podkāstu epizodes failā `podcasts.json` tieši jūsu repozitorijā bez CORS ierobežojumiem.

## Kā aktivizēt automatizāciju GitHub repozitorijā
1. Augšupielādējiet visus arhīva failus (tostarp `.github/workflows/update-podcasts.yml` un `podcasts.json`) savā repozitorijā.
2. GitHub repozitorijā atveriet **Settings → Actions → General** un sadaļā **Workflow permissions** atzīmējiet **Read and write permissions**, pēc tam nospiediet **Save**.
3. Atveriet cilni **Actions** → **Update Latvian Podcasts Feed** → **Run workflow**, lai uzreiz ielādētu jaunākās latviešu podkāstu epizodes.
