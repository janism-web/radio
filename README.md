# Internetradio & Podkāsti (Material 3 PWA — v14)

- **Drošība (XSS aizsardzība):** Pievienota `escapeHTML()` un droša URL sanitizācija visiem ārējo RSS un kataloga datiem.
- **PWA ikonas:** Izlabota `icon-monochrome-512.png` ar caurspīdīgu alfa kanālu Android Material You motīvu ikonām.
- **Service Worker (v14):** Ieviesta *Network-First* stratēģija HTML navigācijai un *Cache-First* ikonām.
- **Tiešraides stabilitāte:** Pievienota automātiska savienojuma atjaunošana (Auto-Reconnect) straumes pārtrūkuma vai ilgstošas buferēšanas gadījumā.
