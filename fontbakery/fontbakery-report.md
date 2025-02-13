## FontBakery report

fontbakery version: 0.13.2





## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Vilnius-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check base characters have non-zero advance width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#base-has-width">base_has_width</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs had zero advance width:
- uniE005 (U+E005)</p>
<pre><code>- uniF4E0 (U+F4E0)

- uniF4EE (U+F4EE)

- uniF4EF (U+F4EF)

- uniF4F1 (U+F4F1)

- uniF4F2 (U+F4F2)
</code></pre>
 [code: zero-width-bases]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[22] Vilnius-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Name table records must not have trailing spaces. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#name-trailing-spaces">name/trailing_spaces</a></summary>
    <div>







* 🔥 **FAIL** <p>Name table record with key = (3, 1, 1033, 19) has trailing spaces that must be removed: ' Выⷣрꙋкᲂва[...]моничᲂвъ .'</p>
 [code: trailing-space]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ҁ, џ, Ꙃ, Џ, ҁ, ꙃ</td>
<td align="left">cu_Cyrl (Church Slavic)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following mark characters are missing from the font: ̧</td>
<td align="left">ca_Latn (Catalan), en_Latn (English), fr_Latn (French), pt_Latn (Portuguese) and sq_Latn (Albanian)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following mark characters are missing from the font: ̌, ̊</td>
<td align="left">cs_Latn (Czech) and fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following mark characters are missing from the font: ̊</td>
<td align="left">da_Latn (Danish), nb_Latn (Norwegian Bokmål) and sv_Latn (Swedish)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ẞ</td>
<td align="left">de_Latn (German)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following mark characters are missing from the font: ̌</td>
<td align="left">hr_Latn (Croatian) and sk_Latn (Slovak)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following mark characters are missing from the font: ̨</td>
<td align="left">is_Latn (Icelandic) and pl_Latn (Polish)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following mark characters are missing from the font: ̌, ̨</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following mark characters are missing from the font: ̧, ̌</td>
<td align="left">lv_Latn (Latvian)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to J when shaping the text 'ÍJ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to j when shaping the text 'íj́'</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ș, Ț, ț, ș</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following mark characters are missing from the font: ̦, ̧</td>
<td align="left">ro_Latn (Romanian)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following mark characters are missing from the font: ̦, ̧</td>
<td align="left">tr_Latn (Turkish)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǧ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ȟ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǩ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ș</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ẞ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ț</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǯ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǧ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ȟ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǩ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ș</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ț</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǯ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ẞ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǔ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǔ</td>
<td align="left">fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ẞ</td>
<td align="left">it_Latn (Italian), pl_Latn (Polish) and tr_Latn (Turkish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Aogonek when shaping the text 'Ą́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Aogonek when shaping the text 'Ą̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Eogonek when shaping the text 'Ę́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Eogonek when shaping the text 'Ę̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Edotaccent when shaping the text 'Ė́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Edotaccent when shaping the text 'Ė̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Idotaccent when shaping the text 'İ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Idotaccent when shaping the text 'İ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Idotaccent when shaping the text 'İ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Idotaccent when shaping the text 'İ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Idotaccent when shaping the text 'İ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Idotaccent when shaping the text 'İ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Iogonek when shaping the text 'Į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to Iogonek when shaping the text 'Į̇́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Iogonek when shaping the text 'Į̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to Iogonek when shaping the text 'Į̇̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to J when shaping the text 'J̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to J when shaping the text 'J̇̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to L when shaping the text 'L̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to M when shaping the text 'M̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to R when shaping the text 'R̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Uogonek when shaping the text 'Ų́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Uogonek when shaping the text 'Ų̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Umacron when shaping the text 'Ū́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Umacron when shaping the text 'Ū̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to aogonek when shaping the text 'ą́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to aogonek when shaping the text 'ą̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to eogonek when shaping the text 'ę́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to eogonek when shaping the text 'ę̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to edotaccent when shaping the text 'ė́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to edotaccent when shaping the text 'ė̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to i when shaping the text 'i̇́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to i when shaping the text 'i̇̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to i when shaping the text 'i̇̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to iogonek when shaping the text 'į̇́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to iogonek when shaping the text 'į̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to iogonek when shaping the text 'į̇̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to j when shaping the text 'j̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to j when shaping the text 'j̇̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to l when shaping the text 'l̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to m when shaping the text 'm̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to r when shaping the text 'r̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uogonek when shaping the text 'ų́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uogonek when shaping the text 'ų̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to umacron when shaping the text 'ū́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to umacron when shaping the text 'ū̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǎ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǎ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-license-OFL-copyright">googlefonts/license/OFL_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-license">googlefonts/name/license</a></summary>
    <div>







* 🔥 **FAIL** <p>Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set.</p>
 [code: missing]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DB (OGONEK)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x030A (COMBINING RING ABOVE)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0327 (COMBINING CEDILLA)


- 0x0328 (COMBINING OGONEK)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)


- 0x2122 (TRADE MARK SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-mark-chars">opentype/gdef_mark_chars</a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
uni034F (U+034F)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-spacing-marks">opentype/gdef_spacing_marks</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs seem to be spacing (because they have width &gt; 0 on the hmtx table) so they may be in the GDEF mark glyph class by mistake, or they should have zero width instead:
uni030B (U+030B), uni0485 (U+0485), uni0486 (U+0486), uni0488 (U+0488), uni0489 (U+0489), uni20DD (U+20DD), uni2DE3 (U+2DE3), uni2DE4 (U+2DE4), uni2DE5 (U+2DE5), uni2DE8 (U+2DE8), uni2DEE (U+2DEE), uni2DEF (U+2DEF), uni2DF9 (U+2DF9), uni2DFA (U+2DFA), uni2DFB (U+2DFB), uni2DFC (U+2DFC), uniA670 (U+A670), uniA671 (U+A671), uniA672 (U+A672), uniE001 (U+E001), uniE003 (U+E003), uniF4E1 (U+F4E1), uniF4E2 (U+F4E2), uniF4E3 (U+F4E3), uniF4E4 (U+F4E4), uniF4E5 (U+F4E5), uniF4E6 (U+F4E6), uniF4E7 (U+F4E7), uniF4E8 (U+F4E8), uniF4E9 (U+F4E9), uniF4EA (U+F4EA), uniF4EB (U+F4EB), uniF4EC (U+F4EC), uniF4ED (U+F4ED) and uniF4F0 (U+F4F0)</p>
 [code: spacing-mark-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#alt-caron">alt_caron</a></summary>
    <div>









* ⚠️ **WARN** <p>Lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>dcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>tcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if uppercase glyphs are vertically centered. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#caps-vertically-centered">caps_vertically_centered</a></summary>
    <div>







* ⚠️ **WARN** <p>Uppercase glyphs are not vertically centered in the em box.</p>
 [code: vertical-metrics-not-centered]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: uni0000	Contours detected: 5	Expected: 0

- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

- Glyph name: uni0435	Contours detected: 1	Expected: 2

- Glyph name: uni0436	Contours detected: 2	Expected: 1

- Glyph name: uni043A	Contours detected: 2	Expected: 1

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: afii10071	Contours detected: 3	Expected: 4

- Glyph name: uni0456	Contours detected: 1	Expected: 2

- Glyph name: afii10109	Contours detected: 3	Expected: 2

- Glyph name: uni046E	Contours detected: 1	Expected: 2

- Glyph name: uni046F	Contours detected: 1	Expected: 2

- Glyph name: uni0473	Contours detected: 2	Expected: 3

- Glyph name: uni0488	Contours detected: 12	Expected: 8

- Glyph name: uni0489	Contours detected: 12	Expected: 8

- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

- Glyph name: uni0435	Contours detected: 1	Expected: 2

- Glyph name: uni0436	Contours detected: 2	Expected: 1

- Glyph name: uni043A	Contours detected: 2	Expected: 1

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: uni0456	Contours detected: 1	Expected: 2

- Glyph name: uni046E	Contours detected: 1	Expected: 2

- Glyph name: uni046F	Contours detected: 1	Expected: 2

- Glyph name: uni0473	Contours detected: 2	Expected: 3

- Glyph name: uni0488	Contours detected: 12	Expected: 8

- Glyph name: uni0489	Contours detected: 12	Expected: 8

- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#gpos-kerning-info">gpos_kerning_info</a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 579 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 552:
less, greater</p>
<p>Width = 378:
minus</p>
<p>Width = 649:
uni223B, similar, uni223D, uni223E</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+007F : try adding symbols</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic</li>
<li>U+0305 COMBINING OVERLINE: try adding one of: elbasan, glagolitic, coptic, gothic, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, canadian-aboriginal, syriac, tai-le, tifinagh, coptic, hebrew, duployan, math, old-permic, todhri</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+033E COMBINING VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+034F COMBINING GRAPHEME JOINER: not included in any glyphset definition</li>
<li>U+037E GREEK QUESTION MARK: try adding greek</li>
<li>U+0387 GREEK ANO TELEIA: try adding greek</li>
<li>U+1DC0 COMBINING DOTTED GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+1DC1 COMBINING DOTTED ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: takri, tai-tham, syriac, manichaean, meetei-mayek, tifinagh, khmer, new-tai-lue, gunjala-gondi, buginese, nko, saurashtra, siddham, newa, thai, tagbanwa, tagalog, arabic, limbu, malayalam, sharada, bengali, psalter-pahlavi, duployan, kaithi, bhaiksuki, pahawh-hmong, modi, syloti-nagri, tibetan, gujarati, sogdian, hanunoo, chakma, grantha, myanmar, mahajani, oriya, gurmukhi, cham, avestan, rejang, sundanese, lepcha, lao, mandaic, tai-le, mongolian, masaram-gondi, buhid, balinese, dogra, kharoshthi, phags-pa, zanabazar-square, batak, devanagari, kannada, hatran, yi, tamil, hebrew, sinhala, brahmi, khojki, telugu, khudawadi, warang-citi, javanese, kayah-li, thaana, hanifi-rohingya, tirhuta, tai-viet</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: takri, tai-tham, syriac, manichaean, meetei-mayek, tifinagh, khmer, new-tai-lue, gunjala-gondi, buginese, nko, saurashtra, siddham, newa, thai, tagbanwa, tagalog, arabic, limbu, malayalam, sharada, bengali, psalter-pahlavi, duployan, kaithi, bhaiksuki, pahawh-hmong, modi, syloti-nagri, tibetan, gujarati, sogdian, hanunoo, chakma, grantha, myanmar, mahajani, oriya, gurmukhi, cham, avestan, rejang, sundanese, lepcha, lao, mandaic, tai-le, mongolian, masaram-gondi, buhid, balinese, dogra, kharoshthi, phags-pa, zanabazar-square, batak, devanagari, kannada, yi, tamil, hebrew, sinhala, brahmi, khojki, telugu, khudawadi, warang-citi, javanese, kayah-li, old-hungarian, hanifi-rohingya, tirhuta, thaana, tai-viet</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: arabic, syriac, hebrew, nko, thaana, phags-pa</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, hebrew, nko, thaana, phags-pa</li>
<li>U+2010 HYPHEN: try adding one of: arabic, yi, cham, sundanese, armenian, coptic, hebrew, sora-sompeng, kaithi, kayah-li, lisu, syloti-nagri, kharoshthi</li>
<li>U+2011 NON-BREAKING HYPHEN: try adding one of: syloti-nagri, arabic, yi</li>
<li>U+2012 FIGURE DASH: not included in any glyphset definition</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2024 ONE DOT LEADER: try adding armenian</li>
<li>U+2025 TWO DOT LEADER: try adding phags-pa</li>
<li>U+2027 HYPHENATION POINT: not included in any glyphset definition</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: phags-pa, mongolian, yi</li>
<li>U+203B REFERENCE MARK: not included in any glyphset definition</li>
<li>U+2060 WORD JOINER: not included in any glyphset definition</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+20DD COMBINING ENCLOSING CIRCLE: try adding symbols</li>
<li>U+223B HOMOTHETIC: try adding math</li>
<li>U+223C TILDE OPERATOR: try adding math</li>
<li>U+223D REVERSED TILDE: try adding math</li>
<li>U+223E INVERTED LAZY S: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: syriac, meetei-mayek, tifinagh, new-tai-lue, gunjala-gondi, wancho, saurashtra, siddham, soyombo, thai, tagbanwa, tagalog, bhaiksuki, pahawh-hmong, tibetan, hanunoo, mahajani, gurmukhi, cham, coptic, masaram-gondi, adlam, devanagari, tirhuta, music, takri, nko, elbasan, limbu, ahom, modi, gujarati, caucasian-albanian, rejang, sundanese, lao, mongolian, kharoshthi, kannada, tamil, armenian, khojki, warang-citi, old-permic, thaana, manichaean, khmer, mende-kikakui, newa, canadian-aboriginal, sharada, bengali, kaithi, syloti-nagri, sogdian, miao, tai-le, phags-pa, buhid, dogra, batak, sinhala, brahmi, symbols, javanese, kayah-li, tai-tham, buginese, malayalam, marchen, osage, psalter-pahlavi, duployan, chakma, grantha, myanmar, oriya, lepcha, bassa-vah, mandaic, math, balinese, zanabazar-square, yi, hebrew, telugu, khudawadi, hanifi-rohingya, tai-viet</li>
<li>U+25EF LARGE CIRCLE: try adding symbols</li>
<li>U+2626 ORTHODOX CROSS: try adding symbols</li>
<li>U+2720 MALTESE CROSS: try adding symbols</li>
<li>U+2E2F VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+2E34 RAISED COMMA: try adding coptic</li>
<li>U+2E43 DASH WITH LEFT UPTURN: try adding glagolitic</li>
<li>U+E001 : not included in any glyphset definition</li>
<li>U+E003 : not included in any glyphset definition</li>
<li>U+E005 : not included in any glyphset definition</li>
<li>U+E0E0 : not included in any glyphset definition</li>
<li>U+E0E1 : not included in any glyphset definition</li>
<li>U+E0E2 : not included in any glyphset definition</li>
<li>U+E0E3 : not included in any glyphset definition</li>
<li>U+E0E4 : not included in any glyphset definition</li>
<li>U+E0E5 : not included in any glyphset definition</li>
<li>U+E0E6 : not included in any glyphset definition</li>
<li>U+E0E7 : not included in any glyphset definition</li>
<li>U+E0E8 : not included in any glyphset definition</li>
<li>U+E0E9 : not included in any glyphset definition</li>
<li>U+E0EA : not included in any glyphset definition</li>
<li>U+E0EB : not included in any glyphset definition</li>
<li>U+E0EC : not included in any glyphset definition</li>
<li>U+E0ED : not included in any glyphset definition</li>
<li>U+E0EE : not included in any glyphset definition</li>
<li>U+E0EF : not included in any glyphset definition</li>
<li>U+E0F0 : not included in any glyphset definition</li>
<li>U+E381 : not included in any glyphset definition</li>
<li>U+E383 : not included in any glyphset definition</li>
<li>U+E405 : not included in any glyphset definition</li>
<li>U+E612 : not included in any glyphset definition</li>
<li>U+E714 : not included in any glyphset definition</li>
<li>U+E800 : not included in any glyphset definition</li>
<li>U+E814 : not included in any glyphset definition</li>
<li>U+E8E5 : not included in any glyphset definition</li>
<li>U+E8E8 : not included in any glyphset definition</li>
<li>U+E8E9 : not included in any glyphset definition</li>
<li>U+E8EA : not included in any glyphset definition</li>
<li>U+E8EB : not included in any glyphset definition</li>
<li>U+E8ED : not included in any glyphset definition</li>
<li>U+E8F0 : not included in any glyphset definition</li>
<li>U+E900 : not included in any glyphset definition</li>
<li>U+E901 : not included in any glyphset definition</li>
<li>U+E902 : not included in any glyphset definition</li>
<li>U+E904 : not included in any glyphset definition</li>
<li>U+E906 : not included in any glyphset definition</li>
<li>U+E907 : not included in any glyphset definition</li>
<li>U+E90C : not included in any glyphset definition</li>
<li>U+E90D : not included in any glyphset definition</li>
<li>U+E90E : not included in any glyphset definition</li>
<li>U+E920 : not included in any glyphset definition</li>
<li>U+E921 : not included in any glyphset definition</li>
<li>U+E922 : not included in any glyphset definition</li>
<li>U+E923 : not included in any glyphset definition</li>
<li>U+E924 : not included in any glyphset definition</li>
<li>U+E925 : not included in any glyphset definition</li>
<li>U+E926 : not included in any glyphset definition</li>
<li>U+E92A : not included in any glyphset definition</li>
<li>U+E92B : not included in any glyphset definition</li>
<li>U+E930 : not included in any glyphset definition</li>
<li>U+E931 : not included in any glyphset definition</li>
<li>U+F4E0 : not included in any glyphset definition</li>
<li>U+F4E1 : not included in any glyphset definition</li>
<li>U+F4E2 : not included in any glyphset definition</li>
<li>U+F4E3 : not included in any glyphset definition</li>
<li>U+F4E4 : not included in any glyphset definition</li>
<li>U+F4E5 : not included in any glyphset definition</li>
<li>U+F4E6 : not included in any glyphset definition</li>
<li>U+F4E7 : not included in any glyphset definition</li>
<li>U+F4E8 : not included in any glyphset definition</li>
<li>U+F4E9 : not included in any glyphset definition</li>
<li>U+F4EA : not included in any glyphset definition</li>
<li>U+F4EB : not included in any glyphset definition</li>
<li>U+F4EC : not included in any glyphset definition</li>
<li>U+F4ED : not included in any glyphset definition</li>
<li>U+F4EE : not included in any glyphset definition</li>
<li>U+F4EF : not included in any glyphset definition</li>
<li>U+F4F0 : not included in any glyphset definition</li>
<li>U+F4F1 : not included in any glyphset definition</li>
<li>U+F4F2 : not included in any glyphset definition</li>
<li>U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
<li>U+FB04 LATIN SMALL LIGATURE FFL: not included in any glyphset definition</li>
<li>U+FB05 LATIN SMALL LIGATURE LONG S T: not included in any glyphset definition</li>
<li>U+FB06 LATIN SMALL LIGATURE ST: not included in any glyphset definition</li>
<li>U+1F311 NEW MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F312 WAXING CRESCENT MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F313 FIRST QUARTER MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F314 WAXING GIBBOUS MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F315 FULL MOON SYMBOL: try adding symbols</li>
<li>U+1F316 WANING GIBBOUS MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F317 LAST QUARTER MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F318 WANING CRESCENT MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F319 CRESCENT MOON: not included in any glyphset definition</li>
<li>U+1F347 GRAPES: not included in any glyphset definition</li>
<li>U+1F377 WINE GLASS: not included in any glyphset definition</li>
<li>U+1F41F FISH: try adding symbols</li>
<li>U+1F540 CIRCLED CROSS POMMEE: try adding symbols</li>
<li>U+1F541 CROSS POMMEE WITH HALF-CIRCLE BELOW: try adding symbols</li>
<li>U+1F542 CROSS POMMEE: try adding symbols</li>
<li>U+1F543 NOTCHED LEFT SEMICIRCLE WITH THREE DOTS: try adding symbols</li>
<li>U+1F544 NOTCHED RIGHT SEMICIRCLE WITH THREE DOTS: try adding symbols</li>
<li>U+1F545 SYMBOL FOR MARKS CHAPTER: try adding symbols</li>
<li>U+F0022 : not included in any glyphset definition</li>
<li>U+F0023 : not included in any glyphset definition</li>
<li>U+F0025 : not included in any glyphset definition</li>
<li>U+F0027 : not included in any glyphset definition</li>
<li>U+F0120 : not included in any glyphset definition</li>
<li>U+F0121 : not included in any glyphset definition</li>
<li>U+F0122 : not included in any glyphset definition</li>
<li>U+F0123 : not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic</code>, <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̋ j̀ j́ j̃ j̄ j̈ j̑ į̀ į́ į̂ į̃ į̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̅ i̇ ȉ ȋ i̾ i҃ i҄ i҅ i҆ i҇ i᷀ i᷁ iⷠ iⷡ iⷢ iⷣ iⷤ iⷥ iⷦ iⷧ</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* exclam (U+0021): L&lt;&lt;70.0,424.0&gt;--&lt;66.0,457.0&gt;&gt; -&gt; L&lt;&lt;66.0,457.0&gt;--&lt;60.0,491.0&gt;&gt;

* uF0025 (U+F0025): L&lt;&lt;-226.0,689.0&gt;--&lt;-244.0,729.0&gt;&gt; -&gt; L&lt;&lt;-244.0,729.0&gt;--&lt;-265.0,769.0&gt;&gt;

* uF0025 (U+F0025): L&lt;&lt;-384.0,947.0&gt;--&lt;-406.0,945.0&gt;&gt; -&gt; L&lt;&lt;-406.0,945.0&gt;--&lt;-427.0,942.0&gt;&gt;

* uni0412 (U+0412): L&lt;&lt;271.0,178.0&gt;--&lt;271.0,177.0&gt;&gt; -&gt; L&lt;&lt;271.0,177.0&gt;--&lt;270.0,97.0&gt;&gt;

* uni042F (U+042F): L&lt;&lt;379.0,97.0&gt;--&lt;381.0,177.0&gt;&gt; -&gt; L&lt;&lt;381.0,177.0&gt;--&lt;381.0,178.0&gt;&gt;

* uni0487 (U+0487): L&lt;&lt;-336.0,847.0&gt;--&lt;-299.0,869.0&gt;&gt; -&gt; L&lt;&lt;-299.0,869.0&gt;--&lt;-262.0,887.0&gt;&gt;

* uni2DF9 (U+2DF9): L&lt;&lt;-124.0,924.0&gt;--&lt;-114.0,945.0&gt;&gt; -&gt; L&lt;&lt;-114.0,945.0&gt;--&lt;-101.0,968.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* afii10058 (U+0409): B&lt;&lt;562.0,39.0&gt;-&lt;549.0,62.0&gt;-&lt;543.0,94.0&gt;&gt;/L&lt;&lt;543.0,94.0&gt;--&lt;535.0,-430.0&gt;&gt; = 11.494332047276455

* afii10058 (U+0409): L&lt;&lt;403.0,-430.0&gt;--&lt;418.0,105.0&gt;&gt;/B&lt;&lt;418.0,105.0&gt;-&lt;412.0,80.0&gt;-&lt;401.0,57.0&gt;&gt; = 11.889730291513542

* u1F312 (U+1F312): B&lt;&lt;468.0,49.0&gt;-&lt;442.0,33.0&gt;-&lt;425.0,33.0&gt;&gt;/B&lt;&lt;425.0,33.0&gt;-&lt;432.0,32.0&gt;-&lt;435.0,32.0&gt;&gt; = 8.13010235415596

* u1F318 (U+1F318): B&lt;&lt;376.5,763.0&gt;-&lt;384.0,766.0&gt;-&lt;393.0,768.0&gt;&gt;/L&lt;&lt;393.0,768.0&gt;--&lt;379.0,768.0&gt;&gt; = 12.528807709151492

* u1F377 (U+1F377): B&lt;&lt;466.5,415.5&gt;-&lt;489.0,424.0&gt;-&lt;507.0,431.0&gt;&gt;/B&lt;&lt;507.0,431.0&gt;-&lt;499.0,430.0&gt;-&lt;487.5,430.0&gt;&gt; = 14.12548915823142

* u1F41F (U+1F41F): B&lt;&lt;516.0,308.0&gt;-&lt;543.0,314.0&gt;-&lt;730.0,332.0&gt;&gt;/B&lt;&lt;730.0,332.0&gt;-&lt;702.0,336.0&gt;-&lt;675.5,337.5&gt;&gt; = 13.62826507913694

* u1F41F (U+1F41F): L&lt;&lt;833.0,445.0&gt;--&lt;914.0,405.0&gt;&gt;/B&lt;&lt;914.0,405.0&gt;-&lt;900.0,416.0&gt;-&lt;900.0,434.0&gt;&gt; = 11.875815566048908

* uni0410 (U+0410): L&lt;&lt;363.0,-35.0&gt;--&lt;357.0,249.0&gt;&gt;/B&lt;&lt;357.0,249.0&gt;-&lt;354.0,234.0&gt;-&lt;348.0,219.0&gt;&gt; = 12.520226642941422

* uni0414 (U+0414): L&lt;&lt;397.0,-430.0&gt;--&lt;387.0,26.0&gt;&gt;/B&lt;&lt;387.0,26.0&gt;-&lt;380.0,-22.0&gt;-&lt;369.0,-70.0&gt;&gt; = 9.553429998793161

* uni041B (U+041B): L&lt;&lt;402.0,-430.0&gt;--&lt;389.0,169.0&gt;&gt;/B&lt;&lt;389.0,169.0&gt;-&lt;388.0,164.0&gt;-&lt;387.0,159.5&gt;&gt; = 12.553218321682799

* uni041C (U+041C): B&lt;&lt;381.0,84.5&gt;-&lt;377.0,128.0&gt;-&lt;377.0,172.0&gt;&gt;/B&lt;&lt;377.0,172.0&gt;-&lt;346.0,19.0&gt;-&lt;312.0,-131.5&gt;&gt; = 11.453891416092194

* uni041C (U+041C): L&lt;&lt;766.0,113.0&gt;--&lt;754.0,172.0&gt;&gt;/B&lt;&lt;754.0,172.0&gt;-&lt;754.0,76.0&gt;-&lt;742.5,-6.0&gt;&gt; = 11.496563017585768

* uni043B (U+043B): B&lt;&lt;238.0,206.5&gt;-&lt;233.0,248.0&gt;-&lt;228.0,290.0&gt;&gt;/B&lt;&lt;228.0,290.0&gt;-&lt;227.0,282.0&gt;-&lt;222.5,270.0&gt;&gt; = 13.913990923340561

* uni0470 (U+0470): L&lt;&lt;449.0,284.0&gt;--&lt;449.0,-273.0&gt;&gt;/L&lt;&lt;449.0,-273.0&gt;--&lt;558.0,346.0&gt;&gt; = 9.98685693437503

* uni2DFA (U+2DFA): B&lt;&lt;-105.0,901.0&gt;-&lt;-105.0,898.0&gt;-&lt;-106.0,898.0&gt;&gt;/L&lt;&lt;-106.0,898.0&gt;--&lt;84.0,899.0&gt;&gt; = 0.30155394986727113
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* Ebreve (U+0114): L&lt;&lt;127.0,126.0&gt;--&lt;126.0,521.0&gt;&gt;

* Edotaccent (U+0116): L&lt;&lt;126.0,126.0&gt;--&lt;127.0,521.0&gt;&gt;

* M (U+004D): L&lt;&lt;675.0,147.0&gt;--&lt;672.0,550.0&gt;&gt;

* ij (U+0133): L&lt;&lt;449.0,451.0&gt;--&lt;450.0,115.0&gt;&gt;

* k (U+006B): L&lt;&lt;517.0,0.0&gt;--&lt;373.0,-1.0&gt;&gt;

* kcommaaccent (U+0137): L&lt;&lt;517.0,0.0&gt;--&lt;373.0,-1.0&gt;&gt;

* onequarter (U+00BC): L&lt;&lt;216.0,635.0&gt;--&lt;215.0,361.0&gt;&gt;

* u1F541 (U+1F541): L&lt;&lt;628.0,0.0&gt;--&lt;464.0,1.0&gt;&gt;

* u1F545 (U+1F545): L&lt;&lt;212.0,534.0&gt;--&lt;214.0,125.0&gt;&gt;

* u1F545 (U+1F545): L&lt;&lt;214.0,65.0&gt;--&lt;216.0,-466.0&gt;&gt;

* u1F545 (U+1F545): L&lt;&lt;892.0,534.0&gt;--&lt;896.0,-466.0&gt;&gt;

* uni040D (U+040D): L&lt;&lt;467.0,208.0&gt;--&lt;465.0,495.0&gt;&gt;

* uni040D (U+040D): L&lt;&lt;472.0,-430.0&gt;--&lt;467.0,179.0&gt;&gt;

* uni0418 (U+0418): L&lt;&lt;467.0,208.0&gt;--&lt;465.0,495.0&gt;&gt;

* uni0418 (U+0418): L&lt;&lt;472.0,-430.0&gt;--&lt;467.0,179.0&gt;&gt;

* uni0419 (U+0419): L&lt;&lt;467.0,208.0&gt;--&lt;465.0,495.0&gt;&gt;

* uni0419 (U+0419): L&lt;&lt;472.0,-430.0&gt;--&lt;467.0,179.0&gt;&gt;

* uni041F (U+041F): L&lt;&lt;472.0,-430.0&gt;--&lt;465.0,495.0&gt;&gt;

* uni0426 (U+0426): L&lt;&lt;471.0,-430.0&gt;--&lt;465.0,495.0&gt;&gt;

* uni0426 (U+0426): L&lt;&lt;473.0,-724.0&gt;--&lt;471.0,-455.0&gt;&gt;

* uni0428 (U+0428): L&lt;&lt;400.0,-430.0&gt;--&lt;406.0,495.0&gt;&gt;

* uni0428 (U+0428): L&lt;&lt;526.0,495.0&gt;--&lt;532.0,-430.0&gt;&gt;

* uni0428 (U+0428): L&lt;&lt;682.0,-430.0&gt;--&lt;675.0,495.0&gt;&gt;

* uni0429 (U+0429): L&lt;&lt;399.0,-430.0&gt;--&lt;406.0,495.0&gt;&gt;

* uni0429 (U+0429): L&lt;&lt;526.0,495.0&gt;--&lt;532.0,-430.0&gt;&gt;

* uni0429 (U+0429): L&lt;&lt;682.0,-430.0&gt;--&lt;675.0,495.0&gt;&gt;

* uni042B (U+042B): L&lt;&lt;622.0,-430.0&gt;--&lt;615.0,495.0&gt;&gt;

* uni2DF9 (U+2DF9): L&lt;&lt;-67.0,601.0&gt;--&lt;-299.0,599.0&gt;&gt;

* uni2DFA (U+2DFA): L&lt;&lt;-106.0,898.0&gt;--&lt;84.0,899.0&gt;&gt;

* uni2DFA (U+2DFA): L&lt;&lt;-210.0,870.0&gt;--&lt;-350.0,869.0&gt;&gt;

* uniA650 (U+A650): L&lt;&lt;384.0,-430.0&gt;--&lt;382.0,-3.0&gt;&gt;

* uniA656 (U+A656): L&lt;&lt;575.0,-36.0&gt;--&lt;573.0,232.0&gt;&gt;

* uniFB04 (U+FB04): L&lt;&lt;459.0,397.0&gt;--&lt;458.0,101.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value '    ' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics">googlefonts/vertical_metrics</a></summary>
    <div>







* ⚠️ **WARN** <p>We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.984x (1984)</p>
 [code: bad-hhea-range]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 6 | 17 | 108 | 6 | 99 | 0 | 
| 0% | 0% | 3% | 7% | 46% | 3% | 42% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
