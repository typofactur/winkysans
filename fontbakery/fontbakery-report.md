## FontBakery report

fontbakery version: 0.12.10



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] WinkySans[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoAscender value should be greater than 863.05, but got 700 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[14] WinkySans[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 249, but got 200 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoLineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: OS/2]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (700) and hhea ascent (1000) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ca_Latn (Catalan)</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̈, ◌̧</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">cs_Latn (Czech)</td>
<td align="left">Some mark glyphs were missing: ◌́, ◌̊, ◌̌</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">cy_Latn (Welsh)</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̂, ◌̈</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">da_Latn (Danish)</td>
<td align="left">Some mark glyphs were missing: ◌́, ◌̊</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">de_Latn (German)</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̈</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">en_Latn (English)</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̂, ◌̃, ◌̈, ◌̧</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">es_Latn (Spanish)</td>
<td align="left">Some mark glyphs were missing: ◌́, ◌̃, ◌̈</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fi_Latn (Finnish)</td>
<td align="left">Some mark glyphs were missing: ◌̃, ◌̈, ◌̊, ◌̌</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fr_Latn (French)</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̂, ◌̈, ◌̧</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">hr_Latn (Croatian)</td>
<td align="left">Some mark glyphs were missing: ◌́, ◌̌</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">hu_Latn (Hungarian)</td>
<td align="left">Some mark glyphs were missing: ◌́, ◌̈, ◌̋</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">is_Latn (Icelandic)</td>
<td align="left">Some mark glyphs were missing: ◌́, ◌̈, ◌̨</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">it_Latn (Italian)</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̂, ◌̈</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lt_Latn (Lithuanian)</td>
<td align="left">Some mark glyphs were missing: ◌̄, ◌̇, ◌̌, ◌̨</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lv_Latn (Latvian)</td>
<td align="left">Some mark glyphs were missing: ◌̄, ◌̌, ◌̧</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mt_Latn (Maltese)</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌̂, ◌̇</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̂, ◌̈, ◌̊</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Some base glyphs were missing: ÍJ́, íj́</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̂, ◌̈</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pl_Latn (Polish)</td>
<td align="left">Some mark glyphs were missing: ◌́, ◌̇, ◌̨</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pt_Latn (Portuguese)</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̂, ◌̃, ◌̈, ◌̧</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ro_Latn (Romanian)</td>
<td align="left">Some mark glyphs were missing: ◌̂, ◌̆, ◌̦, ◌̧</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sk_Latn (Slovak)</td>
<td align="left">Some mark glyphs were missing: ◌́, ◌̂, ◌̈, ◌̌</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sq_Latn (Albanian)</td>
<td align="left">Some mark glyphs were missing: ◌̈, ◌̧</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sv_Latn (Swedish)</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̈, ◌̊</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tr_Latn (Turkish)</td>
<td align="left">Some mark glyphs were missing: ◌̂, ◌̆, ◌̇, ◌̈, ◌̦, ◌̧</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Some auxiliary glyphs were missing: ÍJ́, íj́</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x00AA (FEMININE ORDINAL INDICATOR)


- 0x00BA (MASCULINE ORDINAL INDICATOR)


- 0x0300 (COMBINING GRAVE ACCENT)


- 0x0301 (COMBINING ACUTE ACCENT)


- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


- 0x0303 (COMBINING TILDE)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x0307 (COMBINING DOT ABOVE)


- 0x0308 (COMBINING DIAERESIS)


- 0x030A (COMBINING RING ABOVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0327 (COMBINING CEDILLA)


- 0x0328 (COMBINING OGONEK)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;300&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
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
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 point 20 in glyph 'a.salt' has a kink between location wght=300 and location wght=900

- Contour 1 point 71 in glyph 'uni0137' has a kink between location wght=300 and location wght=900

- Contour 1 point 26 in glyph 'eth' has a kink between location wght=300 and location wght=900

- Contour 0 point 67 in glyph 'three' has a kink between location wght=300 and location wght=900

- Contour 0 point 26 in glyph 'numbersign' has a kink between location wght=300 and location wght=900

- Contour 0 point 71 in glyph 'k' has a kink between location wght=300 and location wght=900

- Contour 1 point 18 in glyph 'ampersand' has a kink between location wght=300 and location wght=900

- Contour 0 point 61 in glyph 'g.salt' has a kink between location wght=300 and location wght=900

- Contour 0 point 20 in glyph 'six' has a kink between location wght=300 and location wght=900
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: gunjala-gondi, manichaean, gujarati, siddham, lepcha, thai, cham, nko, new-tai-lue, phags-pa, brahmi, chakma, kaithi, kannada, duployan, kharoshthi, buginese, mahajani, kayah-li, meetei-mayek, tirhuta, balinese, zanabazar-square, lao, rejang, saurashtra, warang-citi, telugu, buhid, mongolian, dogra, mandaic, psalter-pahlavi, hatran, khudawadi, khmer, sinhala, sundanese, tamil, yi, khojki, oriya, tifinagh, masaram-gondi, batak, gurmukhi, grantha, thaana, modi, syriac, hebrew, hanunoo, myanmar, avestan, tagalog, syloti-nagri, bhaiksuki, bengali, arabic, limbu, devanagari, sharada, takri, newa, javanese, malayalam, sogdian, tai-le, tai-tham, tai-viet, tibetan, pahawh-hmong, hanifi-rohingya, tagbanwa</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: gunjala-gondi, manichaean, gujarati, siddham, lepcha, thai, cham, nko, new-tai-lue, phags-pa, brahmi, chakma, kaithi, kannada, duployan, old-hungarian, kharoshthi, buginese, mahajani, kayah-li, meetei-mayek, tirhuta, balinese, zanabazar-square, lao, rejang, saurashtra, warang-citi, telugu, buhid, mongolian, dogra, mandaic, psalter-pahlavi, khudawadi, sinhala, khmer, sundanese, tamil, yi, khojki, oriya, tifinagh, masaram-gondi, batak, gurmukhi, grantha, thaana, modi, syriac, hebrew, hanunoo, myanmar, avestan, tagalog, syloti-nagri, bhaiksuki, bengali, arabic, limbu, devanagari, sharada, takri, newa, javanese, malayalam, sogdian, tai-le, tai-tham, tai-viet, tibetan, pahawh-hmong, hanifi-rohingya, tagbanwa</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: arabic, nko, thaana, phags-pa, syriac, hebrew</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, thaana, phags-pa, syriac, hebrew</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: phags-pa, yi, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-simplified, yi, phags-pa, chinese-traditional, nushu, chinese-hongkong, japanese</li>
<li>U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + f

- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 7 | 8 | 98 | 8 | 130 | 0 | 
| 0% | 0% | 3% | 3% | 39% | 3% | 52% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
