## Fontbakery report

Fontbakery version: 0.8.11a10.dev12+g998a9805.d20230124

<details><summary><b>[8] NGTVinaSans-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>

>
>The fsType in the OS/2 table is a legacy DRM-related field. Fonts in the Google Fonts collection must have it set to zero (also known as "Installable Embedding"). This setting indicates that the fonts can be embedded in documents and permanently installed by applications on remote systems.
>
>More detailed info is available at: https://docs.microsoft.com/en-us/typography/opentype/spec/os2#fstype
>
* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>

>
>Google Fonts expects that fonts in its collection support at least the minimal set of characters defined in the `GF-latin-core` glyph-set.
>
* 🔥 **FAIL** Missing required codepoints:

	- 0x201C (LEFT DOUBLE QUOTATION MARK)


	- 0x201D (RIGHT DOUBLE QUOTATION MARK)


	- 0x2018 (LEFT SINGLE QUOTATION MARK)


	- 0x2019 (RIGHT SINGLE QUOTATION MARK)


	- 0x00AB (LEFT-POINTING DOUBLE ANGLE QUOTATION MARK)


	- 0x00BB (RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK)


	- 0x0308 (COMBINING DIAERESIS)


	- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


	- 0x0304 (COMBINING MACRON)


	- 0x02D9 (DOT ABOVE)


	- 0x00C4 (LATIN CAPITAL LETTER A WITH DIAERESIS)


	- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


	- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


	- 0x00C5 (LATIN CAPITAL LETTER A WITH RING ABOVE)


	- 0x00C6 (LATIN CAPITAL LETTER AE)


	- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


	- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


	- 0x00C7 (LATIN CAPITAL LETTER C WITH CEDILLA)


	- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


	- 0x00D0 (LATIN CAPITAL LETTER ETH)


	- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


	- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


	- 0x00CB (LATIN CAPITAL LETTER E WITH DIAERESIS)


	- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


	- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


	- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


	- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


	- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


	- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


	- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


	- 0x0132 (LATIN CAPITAL LIGATURE IJ)


	- 0x00CE (LATIN CAPITAL LETTER I WITH CIRCUMFLEX)


	- 0x00CF (LATIN CAPITAL LETTER I WITH DIAERESIS)


	- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


	- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


	- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


	- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


	- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


	- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


	- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


	- 0x0141 (LATIN CAPITAL LETTER L WITH STROKE)


	- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


	- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


	- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


	- 0x00D1 (LATIN CAPITAL LETTER N WITH TILDE)


	- 0x014A (LATIN CAPITAL LETTER ENG)


	- 0x00D6 (LATIN CAPITAL LETTER O WITH DIAERESIS)


	- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


	- 0x014C (LATIN CAPITAL LETTER O WITH MACRON)


	- 0x00D8 (LATIN CAPITAL LETTER O WITH STROKE)


	- 0x0152 (LATIN CAPITAL LIGATURE OE)


	- 0x00DE (LATIN CAPITAL LETTER THORN)


	- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


	- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


	- 0x0156 (LATIN CAPITAL LETTER R WITH CEDILLA)


	- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


	- 0x0160 (LATIN CAPITAL LETTER S WITH CARON)


	- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


	- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


	- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


	- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


	- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


	- 0x016C (LATIN CAPITAL LETTER U WITH BREVE)


	- 0x00DB (LATIN CAPITAL LETTER U WITH CIRCUMFLEX)


	- 0x00DC (LATIN CAPITAL LETTER U WITH DIAERESIS)


	- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


	- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


	- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


	- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


	- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


	- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


	- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


	- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


	- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


	- 0x0178 (LATIN CAPITAL LETTER Y WITH DIAERESIS)


	- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


	- 0x017D (LATIN CAPITAL LETTER Z WITH CARON)


	- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


	- 0x00E4 (LATIN SMALL LETTER A WITH DIAERESIS)


	- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


	- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


	- 0x00E5 (LATIN SMALL LETTER A WITH RING ABOVE)


	- 0x00E6 (LATIN SMALL LETTER AE)


	- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


	- 0x010D (LATIN SMALL LETTER C WITH CARON)


	- 0x00E7 (LATIN SMALL LETTER C WITH CEDILLA)


	- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


	- 0x00F0 (LATIN SMALL LETTER ETH)


	- 0x010F (LATIN SMALL LETTER D WITH CARON)


	- 0x011B (LATIN SMALL LETTER E WITH CARON)


	- 0x00EB (LATIN SMALL LETTER E WITH DIAERESIS)


	- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


	- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


	- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


	- 0x011F (LATIN SMALL LETTER G WITH BREVE)


	- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


	- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


	- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


	- 0x0131 (LATIN SMALL LETTER DOTLESS I)


	- 0x00EE (LATIN SMALL LETTER I WITH CIRCUMFLEX)


	- 0x00EF (LATIN SMALL LETTER I WITH DIAERESIS)


	- 0x0133 (LATIN SMALL LIGATURE IJ)


	- 0x012B (LATIN SMALL LETTER I WITH MACRON)


	- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


	- 0x0237 (LATIN SMALL LETTER DOTLESS J)


	- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


	- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


	- 0x013E (LATIN SMALL LETTER L WITH CARON)


	- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


	- 0x0142 (LATIN SMALL LETTER L WITH STROKE)


	- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


	- 0x0148 (LATIN SMALL LETTER N WITH CARON)


	- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


	- 0x00F1 (LATIN SMALL LETTER N WITH TILDE)


	- 0x014B (LATIN SMALL LETTER ENG)


	- 0x00F6 (LATIN SMALL LETTER O WITH DIAERESIS)


	- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


	- 0x014D (LATIN SMALL LETTER O WITH MACRON)


	- 0x00F8 (LATIN SMALL LETTER O WITH STROKE)


	- 0x0153 (LATIN SMALL LIGATURE OE)


	- 0x00FE (LATIN SMALL LETTER THORN)


	- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


	- 0x0159 (LATIN SMALL LETTER R WITH CARON)


	- 0x0157 (LATIN SMALL LETTER R WITH CEDILLA)


	- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


	- 0x0161 (LATIN SMALL LETTER S WITH CARON)


	- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


	- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


	- 0x00DF (LATIN SMALL LETTER SHARP S)


	- 0x0165 (LATIN SMALL LETTER T WITH CARON)


	- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


	- 0x016D (LATIN SMALL LETTER U WITH BREVE)


	- 0x00FB (LATIN SMALL LETTER U WITH CIRCUMFLEX)


	- 0x00FC (LATIN SMALL LETTER U WITH DIAERESIS)


	- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


	- 0x016B (LATIN SMALL LETTER U WITH MACRON)


	- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


	- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


	- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


	- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


	- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


	- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


	- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


	- 0x00FF (LATIN SMALL LETTER Y WITH DIAERESIS)


	- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


	- 0x017E (LATIN SMALL LETTER Z WITH CARON)


	- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


	- 0x00AA (FEMININE ORDINAL INDICATOR)


	- 0x00BA (MASCULINE ORDINAL INDICATOR)


	- 0x201A (SINGLE LOW-9 QUOTATION MARK)


	- 0x201E (DOUBLE LOW-9 QUOTATION MARK)


	- 0x2039 (SINGLE LEFT-POINTING ANGLE QUOTATION MARK)


	- 0x203A (SINGLE RIGHT-POINTING ANGLE QUOTATION MARK)


	- 0x0307 (COMBINING DOT ABOVE)


	- 0x030C (COMBINING CARON)


	- 0x030A (COMBINING RING ABOVE)


	- 0x0312 (COMBINING TURNED COMMA ABOVE)


	- 0x0326 (COMBINING COMMA BELOW)


	- 0x0327 (COMBINING CEDILLA)


	- 0x0328 (COMBINING OGONEK)


	- 0x00A8 (DIAERESIS)


	- 0x0060 (GRAVE ACCENT)


	- 0x00B4 (ACUTE ACCENT)


	- 0x02DD (DOUBLE ACUTE ACCENT)


	- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


	- 0x02C7 (CARON)


	- 0x02D8 (BREVE)


	- 0x02DA (RING ABOVE)


	- 0x02DC (SMALL TILDE)


	- 0x00AF (MACRON)


	- 0x00B8 (CEDILLA)
 

	- 0x02DB (OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>

>
>A known licensing description must be provided in the NameID 14 (LICENSE DESCRIPTION) entries of the name table.
>
>The source of truth for this check (to determine which license is in use) is a file placed side-by-side to your font project including the licensing terms.
>
>Depending on the chosen license, one of the following string snippets is expected to be found on the NameID 13 (LICENSE DESCRIPTION) entries of the name table:
>
>- "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL"
>
>- "Licensed under the Apache License, Version 2.0"
>
>- "Licensed under the Ubuntu Font Licence 1.0."
>
>Currently accepted licenses are Apache or Open Font License. For a small set of legacy families the Ubuntu Font License may be acceptable as well.
>
>When in doubt, please choose OFL for new font projects.
>
* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright (c) 2021 by Nguyen Type. All rights reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>

>
>Google Fonts has several rules which need to be adhered to when setting a font's name table. Please read: https://googlefonts.github.io/gf-guide/statics.html#supported-styles https://googlefonts.github.io/gf-guide/statics.html#style-linking https://googlefonts.github.io/gf-guide/statics.html#unsupported-styles https://googlefonts.github.io/gf-guide/statics.html#single-weight-families
>
* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | NGT Vina Sans | NGT Vina Sans |
| Subfamily Name | Regular | Regular |
| Full Name | NGT Vina Sans Regular | NGT Vina Sans Regular |
| Poscript Name | NGTVinaSans-Regular | NGTVinaSans-Regular |
| Typographic Family Name | NGT Vina Sans | N/A |
| Typographic Subfamily Name | Regular | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have components which are themselves components. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyf_nested_components">com.google.fonts/check/glyf_nested_components</a>)</summary><div>

>
>There have been bugs rendering variable fonts with nested components. Additionally, some static fonts with nested components have been reported to have rendering and printing issues.
>
>For more info, see: * https://github.com/googlefonts/fontbakery/issues/2961 * https://github.com/arrowtype/recursive/issues/412
>
* 🔥 **FAIL** The following glyphs have components which themselves are component glyphs:
	* uni1EAE
	* uni1EB0
	* uni1EB2
	* uni1EB4
	* uni1EA4
	* uni1EA8
	* uni1EAA
	* uni1EBE
	* uni1EC2
	* uni1EC4
	* uni1ED0
	* uni1ED4
	* uni1ED6
	* uni1EAF
	* uni1EB1
	* uni1EB3
	* uni1EB5
	* uni1EA5
	* uni1EA9
	* uni1EAB
	* uni1EBF
	* uni1EC3
	* uni1EC5
	* uni1ED1
	* uni1ED5
	* uni1ED7
	* yacute
	* uni1EF5
	* ygrave
	* uni1EF7 and uni1EF9 [code: found-nested-components]
</div></details><details><summary>🔥 <b>FAIL:</b> PPEM must be an integer on hinted fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/integer_ppem_if_hinted">com.google.fonts/check/integer_ppem_if_hinted</a>)</summary><div>

>
>Hinted fonts must have head table flag bit 3 set.
>
>Per https://docs.microsoft.com/en-us/typography/opentype/spec/head, bit 3 of Head::flags decides whether PPEM should be rounded. This bit should always be set for hinted fonts.
>
>Note: Bit 3 = Force ppem to integer values for all internal scaler math; May use fractional ppem sizes if this bit is clear;
>
* 🔥 **FAIL** This is a hinted font, so it must have bit 3 set on the flags of the head table, so that PPEM values will be rounded into an integer value.

This can be accomplished by using the 'gftools fix-hinting' command.

# create virtualenv
python3 -m venv venv
# activate virtualenv
source venv/bin/activate
# install gftools
pip install git+https://www.github.com/googlefonts/tools [code: bad-flags]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>

>
>A font's winAscent and winDescent values should be greater than or equal to the head table's yMax, abs(yMin) values. If they are less than these values, clipping can occur on Windows platforms (https://github.com/RedHatBrand/Overpass/issues/33).
>
>If the font includes tall/deep writing systems such as Arabic or Devanagari, the winAscent and winDescent can be greater than the yMax and abs(yMin) to accommodate vowel marks.
>
>When the win Metrics are significantly greater than the upm, the linespacing can appear too loose. To counteract this, enabling the OS/2 fsSelection bit 7 (Use_Typo_Metrics), will force Windows to use the OS/2 typo values instead. This means the font developer can control the linespacing with the typo values, whilst avoiding clipping by setting the win values to values greater than the yMax and abs(yMin).
>
* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 1100 instead [code: ascent]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 8 | 11 | 119 | 8 | 93 | 0 |
| 0% | 3% | 5% | 50% | 3% | 39% | 0% |

**Note:** The following loglevels were omitted in this report:
* **WARN**
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
