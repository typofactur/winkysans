## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[11] WinkySans[wght].ttf</summary>
<div>
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
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to j</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 point 20 in glyph 'a.salt' has a kink between location wght=300 and location wght=900

- Contour 0 point 26 in glyph 'numbersign' has a kink between location wght=300 and location wght=900

- Contour 1 point 18 in glyph 'ampersand' has a kink between location wght=300 and location wght=900

- Contour 0 point 61 in glyph 'g.salt' has a kink between location wght=300 and location wght=900

- Contour 0 point 67 in glyph 'three' has a kink between location wght=300 and location wght=900

- Contour 1 point 26 in glyph 'eth' has a kink between location wght=300 and location wght=900

- Contour 0 point 71 in glyph 'k' has a kink between location wght=300 and location wght=900

- Contour 0 point 20 in glyph 'six' has a kink between location wght=300 and location wght=900
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- commaturnedabove
</code></pre>
 [code: unreachable-glyphs]



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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, canadian-aboriginal, malayalam, duployan, old-permic, tai-le, syriac, todhri, coptic, math, hebrew</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
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
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: grantha, siddham, tirhuta, warang-citi, lao, bengali, hanunoo, kannada, limbu, balinese, mandaic, devanagari, javanese, newa, myanmar, tagbanwa, gujarati, meetei-mayek, saurashtra, kharoshthi, new-tai-lue, mongolian, takri, gunjala-gondi, tifinagh, telugu, kayah-li, modi, yi, rejang, tai-tham, tai-le, brahmi, bhaiksuki, khudawadi, hebrew, psalter-pahlavi, sharada, nko, arabic, phags-pa, sogdian, lepcha, dogra, kaithi, zanabazar-square, hatran, khojki, masaram-gondi, duployan, gurmukhi, manichaean, oriya, sundanese, syloti-nagri, syriac, thaana, avestan, sinhala, buhid, khmer, tai-viet, tamil, malayalam, chakma, batak, buginese, hanifi-rohingya, pahawh-hmong, thai, mahajani, cham, tibetan, tagalog</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: grantha, siddham, tirhuta, warang-citi, lao, bengali, hanunoo, kannada, limbu, balinese, mandaic, devanagari, javanese, newa, myanmar, tagbanwa, gujarati, meetei-mayek, saurashtra, kharoshthi, new-tai-lue, mongolian, takri, gunjala-gondi, tifinagh, telugu, kayah-li, modi, yi, rejang, tai-tham, tai-le, brahmi, bhaiksuki, khudawadi, hebrew, psalter-pahlavi, sharada, nko, arabic, phags-pa, sogdian, lepcha, dogra, kaithi, zanabazar-square, masaram-gondi, khojki, sundanese, duployan, gurmukhi, manichaean, oriya, syloti-nagri, syriac, thaana, old-hungarian, avestan, sinhala, buhid, khmer, tai-viet, tamil, malayalam, chakma, batak, buginese, hanifi-rohingya, pahawh-hmong, thai, mahajani, cham, tibetan, tagalog</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: thaana, syriac, nko, phags-pa, arabic, hebrew</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: thaana, syriac, nko, phags-pa, hebrew</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, japanese, chinese-traditional, chinese-simplified, nushu, phags-pa</li>
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
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ j̆ j̇ j̊</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Kom (Latn, 360,685 speakers), Sar (Latn, 500,000 speakers), Dan (Latn, 1,099,244 speakers), Mundani (Latn, 34,000 speakers), Navajo (Latn, 166,319 speakers), Lugbara (Latn, 2,200,000 speakers), Basaa (Latn, 332,940 speakers), South Central Banda (Latn, 244,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Fur (Latn, 1,230,163 speakers), Bafut (Latn, 158,146 speakers), Mango (Latn, 77,000 speakers), Avokaya (Latn, 100,000 speakers), Southern Kisi (Latn, 360,000 speakers), Kaska (Latn, 125 speakers), Ekpeye (Latn, 226,000 speakers), Nzakara (Latn, 50,000 speakers), Dii (Latn, 71,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Gulay (Latn, 250,478 speakers), Heiltsuk (Latn, 300 speakers), Ebira (Latn, 2,200,000 speakers), Igbo (Latn, 27,823,640 speakers), Makaa (Latn, 221,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Han (Latn, 6 speakers), Teke-Ebo (Latn, 260,000 speakers), Ma’di (Latn, 584,000 speakers), Aghem (Latn, 38,843 speakers), Koonzime (Latn, 40,000 speakers), Dutch (Latn, 31,709,104 speakers), Ejagham (Latn, 120,000 speakers), Vute (Latn, 21,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Zapotec (Latn, 490,000 speakers).</p>
 [code: soft-dotted]



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
| 0 | 0 | 1 | 10 | 96 | 8 | 136 | 0 | 
| 0% | 0% | 0% | 4% | 38% | 3% | 54% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
