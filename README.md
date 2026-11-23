# Fitrah content packs

Downloadable content for the Fitrah (فِطرة) app: translations of the meanings
of the Quran and, later, other translations and recitations. No app code lives
here.

Every file is published in the [`packs` release](../../releases/tag/packs).
`catalog.json` lists each pack with its version, size and SHA-256 checksum;
the app downloads a pack only when the user asks for it and refuses any file
that does not match its checksum.

## Sources and terms

| Pack | Language | Text | Source | Terms |
|---|---|---|---|---|
| `quran.en.saheeh` | en | Saheeh International — Noor International Center, v1.1.2 | [QuranEnc.com](https://quranenc.com) | Republished unmodified, with source and version credited (QuranEnc.com terms) |
| `quran.tr.rwwad` | tr | Rowwad Translation Center — Translated by the team of the Rowwad Translation Center, v1.0.4 | [QuranEnc.com](https://quranenc.com) | Republished unmodified, with source and version credited (QuranEnc.com terms) |
| `quran.ur.junagarhi` | ur | Muhammad Junagarhi — Translated by Muhammad Ibrahim Junagarhi, v1.1.3 | [QuranEnc.com](https://quranenc.com) | Republished unmodified, with source and version credited (QuranEnc.com terms) |
| `quran.id.affairs` | id | Ministry of Religious Affairs — Issued by the Indonesian Ministry of Religious Affairs, v1.0.1 | [QuranEnc.com](https://quranenc.com) | Republished unmodified, with source and version credited (QuranEnc.com terms) |
| `quran.fa.ih` | fa | Rowwad Translation Center — Translated by the team of the Rowwad Translation Center, v1.1.3 | [QuranEnc.com](https://quranenc.com) | Republished unmodified, with source and version credited (QuranEnc.com terms) |
| `quran.hi.omari` | hi | Azizul Haq Al-Omari — Translated by Azizul Haq Al-Omari, v1.1.5 | [QuranEnc.com](https://quranenc.com) | Republished unmodified, with source and version credited (QuranEnc.com terms) |
| `quran.es.montada_eu` | es | Noor International Center — Issued by Noor International, v1.0.1 | [QuranEnc.com](https://quranenc.com) | Republished unmodified, with source and version credited (QuranEnc.com terms) |
| `quran.sw.rwwad` | sw | Rowad Translation Center — Issued by the Islamic Content Service Association in Languages, v1.0.5 | [QuranEnc.com](https://quranenc.com) | Republished unmodified, with source and version credited (QuranEnc.com terms) |
| `quran.ha.gummi` | ha | Abu Bakr Jumi — Translated by Abu Bakr Mahmoud Jumi, v1.2.2 | [QuranEnc.com](https://quranenc.com) | Republished unmodified, with source and version credited (QuranEnc.com terms) |
| `quran.en.rwwad` | en | Rowwad Translation Center — Translated by the team of the Rowwad Translation Center, v1.0.21 | [QuranEnc.com](https://quranenc.com) | Republished unmodified, with source and version credited (QuranEnc.com terms) |
| `quran.fr.montada` | fr | Noor International Center — Translated by Dr. Nabil Rudwan - issued by Noor International Center, v1.0.0 | [QuranEnc.com](https://quranenc.com) | Republished unmodified, with source and version credited (QuranEnc.com terms) |
| `quran.de.bubenheim` | de | Frank Bubenheim — Translated by ‘Abdullah as-Sāmit (Frank Bubenheim) and Dr. Nadim Elias, v1.1.5 | [QuranEnc.com](https://quranenc.com) | Republished unmodified, with source and version credited (QuranEnc.com terms) |
| `quran.bn.zakaria` | bn | Abu Bakr Zakaria — Translated by Abu Bakr Zakaria, v1.1.1 | [QuranEnc.com](https://quranenc.com) | Republished unmodified, with source and version credited (QuranEnc.com terms) |
| `quran.ru.rwwad` | ru | Rowwad Translation Center — Translated by the team of the Rowwad Translation Center, v1.0.1 | [QuranEnc.com](https://quranenc.com) | Republished unmodified, with source and version credited (QuranEnc.com terms) |
| `quran.ms.basumayyah` | ms | Abdullah Basumayyah — Translated by Abdullah Basumayyah, v1.0.0 | [QuranEnc.com](https://quranenc.com) | Republished unmodified, with source and version credited (QuranEnc.com terms) |

The texts are reproduced exactly as published by their sources, footnotes
included. Corrections belong with the original publisher.

## المحتوى القابل للتحميل لتطبيق فطرة

ترجمات معاني القرآن وغيرها، منقولة حرفياً من مصادرها مع ذكر المصدر والإصدار،
ولكل ملف بصمة يتحقق منها التطبيق قبل استخدامه.

## Draft translations under review (adhkar + al-Nawawi's Forty)

`drafts/<lang>/` holds the **draft** translations of the in-app adhkar and
al-Nawawi's Forty Hadith, for review before release:

- `review.html`: Arabic beside the translation, item by item (download and open in a browser).
- `adhkar_nawawi40.<lang>.draft.json`: the source file the packs are built from.

English was reviewed by the project owner; every other language was translated
from that English by machine (Claude) and is **not yet reviewed by a native
speaker or scholar**. The app labels these packs as drafts. Quoted Quran verses
use each language's QuranEnc.com translation.

Languages: en, fr, tr, ur, id, fa, hi, de, es, sw, ha, bn, ru, ms.
