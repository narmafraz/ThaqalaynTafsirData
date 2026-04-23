# Data Sources & Licensing

This repository redistributes tafsir (Quranic exegesis) data aggregated from
multiple third-party sources. The repository infrastructure (netlify.toml,
scripts, README) is licensed under MIT (see LICENSE). The **data itself** is
subject to the terms of its original sources, as documented below.

## Sources

### 1. app-furqan / quran-app-data (GitHub)

**URL:** https://github.com/app-furqan/quran-app-data
**License:** Creative Commons Attribution-NoDerivatives 4.0 (CC BY-ND 4.0)
**Editions redistributed:**

- `ar.mizan`, `en.mizan`, `fa.mizan` — Al-Mizan fi Tafsir al-Quran (Allamah Tabatabai)
- `fa.nemooneh`, `en.nemooneh` — Tafsir Nemooneh (Ayatollah Makarem Shirazi)
- `fa.noor`, `en.noor` — Tafsir Noor (Mohsen Gharaati)
- `ar.safi`, `en.safi` — Tafsir as-Safi (Mulla Mohsin Fayz Kashani)

**Attribution:** Original data compiled for the "Quran - Furqan" mobile
application. Distributed here with attribution as required by CC BY-ND 4.0.

**Note on transformations:** The data has been converted from SQLite to JSON
and from Markdown to HTML for the Thaqalayn web application. These are
considered format conversions for compatibility, not creative derivatives.

### 2. altafsir.com (Royal Aal al-Bayt Institute for Islamic Thought)

**URL:** https://www.altafsir.com
**Terms:** Academic and non-commercial use. Content is made available by the
Royal Aal al-Bayt Institute for Islamic Thought (Jordan) for research and
educational purposes.
**Editions redistributed:**

- `ar.qummi` — Tafsir al-Qummi (Ali ibn Ibrahim al-Qummi, d. 329 AH)
- `ar.tibyan` — Al-Tibyan (Sheikh al-Tusi, d. 460 AH)
- `ar.majma` — Majma' al-Bayan (al-Tabarsi, d. 548 AH)
- `ar.burhan` — Al-Burhan (Hashim al-Bahrani, d. 1107 AH)
- `ar.saadah` — Bayan al-Sa'adah (Sultan Muhammad al-Junabadhi, d. 1327 AH)
- `ar.sadra` — Tafsir Sadr al-Muta'allihin (Mulla Sadra, d. 1059 AH)

## Public Domain Content

The underlying Arabic texts of the classical tafsirs listed under altafsir.com
(authored before 1928) are **public domain**. The typesetting and digitization
provided by altafsir.com is used under their academic use terms.

## Modern Copyright

Several modern tafsirs remain under copyright:

- **Al-Mizan fi Tafsir al-Quran** — by Allamah Tabatabai (d. 1981). Copyright
  may extend until approximately 2051 (life + 70 years) depending on
  jurisdiction.
- **Tafsir Nemooneh** — by Ayatollah Naser Makarem Shirazi (living).
- **Tafsir Noor** — by Hujjat al-Islam Mohsen Gharaati (living).

These works are included here under the terms of their original distribution
(CC BY-ND 4.0 via app-furqan) for educational and non-commercial research use.
Commercial use may require separate permission from the respective copyright
holders.

## For Commercial Users

If you intend to use this data for commercial purposes, you **must** obtain
appropriate permissions from:

1. The app-furqan repository maintainers for CC BY-ND 4.0 content
2. The Royal Aal al-Bayt Institute for altafsir.com sourced content
3. Copyright holders of any individual tafsir still under copyright

## For Academic and Non-Commercial Users

This data is redistributed for research, scholarship, and personal study under
the fair-use / educational exemption provisions recognized in most
jurisdictions. Please provide appropriate attribution when using this data in
published work.

## Reporting Issues

If you are a copyright holder and wish to have content removed or attributed
differently, please open an issue at:
https://github.com/narmafraz/ThaqalaynTafsirData/issues
