## Fontbakery report

Fontbakery version: 0.7.11

<details>
<summary><b>[8] Solway-ExtraBold.ttf</b></summary>
<details>
<summary>🔥 <b>FAIL:</b> Checking OS/2 fsType.</summary>

* [com.google.fonts/check/fstype](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype)
* 🔥 **FAIL** OS/2 fsType is a legacy DRM-related field.
In this font it is set to 4 meaning that:
The font may be embedded, and temporarily loaded on the remote system, but documents that use it must not be editable.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead.
Fonts with this setting indicate that they may be embedded and permanently installed on the remote system by an application.

More detailed info is available at:
https://docs.microsoft.com/en-us/typography/opentype/spec/os2#fstype [code: drm]

</details>
<details>
<summary>🔥 <b>FAIL:</b> License URL matches License text on name table?</summary>

* [com.google.fonts/check/name/license_url](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url)
* 🔥 **FAIL** A known license URL must be provided in the NameID 14 (LICENSE INFO URL) entry. Currently accepted licenses are Apache: 'http://www.apache.org/licenses/LICENSE-2.0' or Open Font License: 'http://scripts.sil.org/OFL'
For a small set of legacy families the Ubuntu Font License 'https://www.ubuntu.com/legal/terms-and-policies/font-licence' may be acceptable as well.
When in doubt, please choose OFL for new font projects. [code: no-license-found]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts</summary>

* [com.google.fonts/check/font_copyright](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright)
* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright (c) 2018 by Mariya Pigoulevskaya. All rights reserved." [code: bad-notice-format]
* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright (c) 2018 by Mariya Pigoulevskaya. All rights reserved." [code: bad-notice-format]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent.</summary>

* [com.google.fonts/check/family/win_ascent_and_descent](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent)
* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 970 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 263, but got 230 instead [code: descent]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics.</summary>

* [com.google.fonts/check/os2_metrics_match_hhea](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea)
* 🔥 **FAIL** OS/2 sTypoAscender and hhea ascent must be equal. [code: ascender]

</details>
<details>
<summary>⚠ <b>WARN:</b> Checking OS/2 achVendID.</summary>

* [com.google.fonts/check/vendor_id](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id)
* ⚠ **WARN** OS/2 VendorID is 'UKWN', a font editor default. You should set it to your own 4 character code, and register that code with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx [code: bad]

</details>
<details>
<summary>⚠ <b>WARN:</b> Stricter unitsPerEm criteria for Google Fonts. </summary>

* [com.google.fonts/check/unitsperem_strict](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict)
* ⚠ **WARN** Even though unitsPerEm (1000) in this font is reasonable. It is strongly advised to consider changing it to 2000, since it will likely improve the quality of Variable Fonts by avoiding excessive rounding of coordinates on interpolations. [code: legacy-value]

</details>
<details>
<summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps.</summary>

* [com.google.fonts/check/linegaps](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps)
* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]

</details>
<br>
</details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS |
|:-----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 5 | 3 | 75 | 7 | 70 |
| 0% | 3% | 2% | 47% | 4% | 44% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
