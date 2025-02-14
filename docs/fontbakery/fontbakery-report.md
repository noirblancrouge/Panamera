## FontBakery report

fontbakery version: 0.13.2







## Check results



<details><summary>[17] Panamera[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Validates subfamilyNameID and postScriptNameID for the default instance record <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-varfont-valid-default-instance-nameids">opentype/varfont/valid_default_instance_nameids</a></summary>
    <div>







* 🔥 **FAIL** <p>'Thin' instance has the same coordinates as the default instance; its postscript name should be 'Panamera-VF', instead of 'Panamera-Thin'.</p>
 [code: invalid-default-instance-postscript-name]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking if OS/2 usWeightClass matches fvar. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-weight-class-fvar">opentype/weight_class_fvar</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 usWeightClass is '400', but should match fvar default value '100.0'.</p>
 [code: bad-weight-class]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1140, but got 1135 instead</p>
 [code: ascent]



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
<td align="left">The following base characters are missing from the font: ɛ, ɔ, Ɔ, Ɛ</td>
<td align="left">bm_Latn (Bambara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɔ, Ɛ, Ɔ, ɛ</td>
<td align="left">dyu_Latn (Dyula)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɛ, Ɛ, ɔ, Ɔ</td>
<td align="left">fat_Latn (Fanti)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɓ, ɓ, Ƴ, ɗ, Ɗ, ƴ</td>
<td align="left">ff_Latn (Fulah)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ƙ, ɗ, Ɓ, Ƴ, ƴ, ƙ, ɓ, Ɗ</td>
<td align="left">ha_Latn (Hausa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɛ, Ɛ, Ɔ, ɔ</td>
<td align="left">tw_akuapem_Latn (Akuapem Twi)</td>
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
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
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
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
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
<td align="left">The following auxiliary characters are missing from the font: ɛ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɛ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɵ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɵ</td>
<td align="left">ig_Latn (Igbo)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- uni031B

- uni0328
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-names">googlefonts/font_names</a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left">Panamera Thin</td>
<td align="left">Panamera Thin</td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Regular</td>
<td align="left">Regular</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Panamera Thin</td>
<td align="left">Panamera Thin</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left"><strong>Panamera-VF</strong></td>
<td align="left"><strong>Panamera-Thin</strong></td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left">Panamera</td>
<td align="left">Panamera</td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left">Thin</td>
<td align="left">Thin</td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-weightclass">googlefonts/weightclass</a></summary>
    <div>







* 🔥 **FAIL** <p>Best SubFamily name is 'Thin'. Expected OS/2 usWeightClass is 100, got 400.</p>
 [code: bad-value]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#interpolation-issues">interpolation_issues</a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 1 start point differs in glyph 'uni21BA' between location wght=100 and location wght=300

- Contour 1 in glyph 'uni21BA': becomes underweight between wght=100 and wght=300.

- Contour 1 start point differs in glyph 'uni21BB' between location wght=100 and location wght=300

- Contour 1 in glyph 'uni21BB': becomes underweight between wght=100 and wght=300.
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#mandatory-avar-table">mandatory_avar_table</a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table. Most variable fonts should include an avar table to correctly define axes progression rates.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have overlapping path segments:</p>
<pre><code>* uni019D (U+019D): L&lt;&lt;77.0,0.0&gt;--&lt;54.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* Eng (U+014A): L&lt;&lt;499.0,0.0&gt;--&lt;472.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* W (U+0057): L&lt;&lt;428.0,662.0&gt;--&lt;448.0,662.0&gt;&gt; has the same coordinates as a previous segment.

* Wacute (U+1E82): L&lt;&lt;428.0,662.0&gt;--&lt;448.0,662.0&gt;&gt; has the same coordinates as a previous segment.

* Wcircumflex (U+0174): L&lt;&lt;428.0,662.0&gt;--&lt;448.0,662.0&gt;&gt; has the same coordinates as a previous segment.

* Wdieresis (U+1E84): L&lt;&lt;428.0,662.0&gt;--&lt;448.0,662.0&gt;&gt; has the same coordinates as a previous segment.

* Wgrave (U+1E80): L&lt;&lt;428.0,662.0&gt;--&lt;448.0,662.0&gt;&gt; has the same coordinates as a previous segment.

* g (U+0067): L&lt;&lt;492.0,-2.0&gt;--&lt;466.0,-2.0&gt;&gt; has the same coordinates as a previous segment.

* gbreve (U+011F): L&lt;&lt;492.0,-2.0&gt;--&lt;466.0,-2.0&gt;&gt; has the same coordinates as a previous segment.

* gcaron (U+01E7): L&lt;&lt;492.0,-2.0&gt;--&lt;466.0,-2.0&gt;&gt; has the same coordinates as a previous segment.

* gcircumflex (U+011D): L&lt;&lt;492.0,-2.0&gt;--&lt;466.0,-2.0&gt;&gt; has the same coordinates as a previous segment.

* uni0123 (U+0123): L&lt;&lt;492.0,-2.0&gt;--&lt;466.0,-2.0&gt;&gt; has the same coordinates as a previous segment.

* gdotaccent (U+0121): L&lt;&lt;492.0,-2.0&gt;--&lt;466.0,-2.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E21 (U+1E21): L&lt;&lt;492.0,-2.0&gt;--&lt;466.0,-2.0&gt;&gt; has the same coordinates as a previous segment.

* uni0272 (U+0272): L&lt;&lt;74.0,0.0&gt;--&lt;48.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* eng (U+014B): L&lt;&lt;484.0,0.0&gt;--&lt;459.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* f_f_i (U+FB03): L&lt;&lt;606.0,586.0&gt;--&lt;606.0,633.0&gt;&gt; has the same coordinates as a previous segment.

* f_f_ij: L&lt;&lt;606.0,586.0&gt;--&lt;606.0,633.0&gt;&gt; has the same coordinates as a previous segment.

* f_i (U+FB01): L&lt;&lt;363.0,586.0&gt;--&lt;363.0,633.0&gt;&gt; has the same coordinates as a previous segment.

* s_t (U+FB06): L&lt;&lt;556.0,518.0&gt;--&lt;531.0,518.0&gt;&gt; has the same coordinates as a previous segment.

* braceleft (U+007B): L&lt;&lt;121.0,294.0&gt;--&lt;121.0,309.0&gt;&gt; has the same coordinates as a previous segment.

* braceright (U+007D): L&lt;&lt;267.0,309.0&gt;--&lt;267.0,294.0&gt;&gt; has the same coordinates as a previous segment.

* braceleft.case: L&lt;&lt;121.0,322.0&gt;--&lt;121.0,337.0&gt;&gt; has the same coordinates as a previous segment.

* braceright.case: L&lt;&lt;267.0,338.0&gt;--&lt;267.0,323.0&gt;&gt; has the same coordinates as a previous segment.

* uni272F (U+272F): L&lt;&lt;906.0,499.0&gt;--&lt;639.0,306.0&gt;&gt; has the same coordinates as a previous segment.

* uni272F (U+272F): L&lt;&lt;753.0,-22.0&gt;--&lt;462.0,182.0&gt;&gt; has the same coordinates as a previous segment.

* uni272F (U+272F): L&lt;&lt;172.0,-22.0&gt;--&lt;286.0,306.0&gt;&gt; has the same coordinates as a previous segment.

* uni272F (U+272F): L&lt;&lt;19.0,499.0&gt;--&lt;351.0,499.0&gt;&gt; has the same coordinates as a previous segment.

* uni272F (U+272F): L&lt;&lt;462.0,816.0&gt;--&lt;574.0,499.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;497.0,251.0&gt;--&lt;732.0,100.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;377.0,251.0&gt;--&lt;437.0,-22.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;292.0,335.0&gt;--&lt;142.0,100.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;292.0,455.0&gt;--&lt;19.0,395.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;377.0,540.0&gt;--&lt;142.0,690.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;497.0,540.0&gt;--&lt;437.0,813.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;582.0,455.0&gt;--&lt;732.0,690.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;583.0,335.0&gt;--&lt;855.0,395.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;19.0,395.0&gt;--&lt;292.0,455.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;292.0,455.0&gt;--&lt;142.0,690.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;142.0,690.0&gt;--&lt;377.0,540.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;377.0,540.0&gt;--&lt;437.0,813.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;437.0,813.0&gt;--&lt;497.0,540.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;497.0,540.0&gt;--&lt;732.0,690.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;732.0,690.0&gt;--&lt;582.0,455.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;582.0,455.0&gt;--&lt;855.0,395.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;855.0,395.0&gt;--&lt;583.0,335.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;583.0,335.0&gt;--&lt;732.0,100.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;732.0,100.0&gt;--&lt;497.0,251.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;497.0,251.0&gt;--&lt;437.0,-22.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;437.0,-22.0&gt;--&lt;377.0,251.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;377.0,251.0&gt;--&lt;142.0,100.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;142.0,100.0&gt;--&lt;292.0,335.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7CF (U+1F7CF): L&lt;&lt;292.0,335.0&gt;--&lt;19.0,395.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7D3 (U+1F7D3): L&lt;&lt;153.0,472.0&gt;--&lt;80.0,601.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7D3 (U+1F7D3): L&lt;&lt;240.0,592.0&gt;--&lt;231.0,753.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7D3 (U+1F7D3): L&lt;&lt;360.0,679.0&gt;--&lt;437.0,813.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7D3 (U+1F7D3): L&lt;&lt;514.0,679.0&gt;--&lt;643.0,753.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7D3 (U+1F7D3): L&lt;&lt;634.0,592.0&gt;--&lt;794.0,601.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7D3 (U+1F7D3): L&lt;&lt;720.0,472.0&gt;--&lt;854.0,395.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7D3 (U+1F7D3): L&lt;&lt;720.0,318.0&gt;--&lt;794.0,189.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7D3 (U+1F7D3): L&lt;&lt;634.0,198.0&gt;--&lt;643.0,38.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7D3 (U+1F7D3): L&lt;&lt;514.0,112.0&gt;--&lt;437.0,-22.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7D3 (U+1F7D3): L&lt;&lt;360.0,112.0&gt;--&lt;231.0,38.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7D3 (U+1F7D3): L&lt;&lt;240.0,198.0&gt;--&lt;80.0,189.0&gt;&gt; has the same coordinates as a previous segment.

* u1F7D3 (U+1F7D3): L&lt;&lt;153.0,318.0&gt;--&lt;19.0,395.0&gt;&gt; has the same coordinates as a previous segment.

* uni20A9 (U+20A9): L&lt;&lt;517.0,662.0&gt;--&lt;537.0,662.0&gt;&gt; has the same coordinates as a previous segment.

* arrowup (U+2191): L&lt;&lt;321.0,716.0&gt;--&lt;331.0,716.0&gt;&gt; has the same coordinates as a previous segment.

* uni2197 (U+2197): L&lt;&lt;563.0,697.0&gt;--&lt;570.0,690.0&gt;&gt; has the same coordinates as a previous segment.

* arrowright (U+2192): L&lt;&lt;726.0,346.0&gt;--&lt;726.0,336.0&gt;&gt; has the same coordinates as a previous segment.

* uni2198 (U+2198): L&lt;&lt;553.0,-11.0&gt;--&lt;546.0,-18.0&gt;&gt; has the same coordinates as a previous segment.

* arrowdown (U+2193): L&lt;&lt;331.0,-34.0&gt;--&lt;321.0,-34.0&gt;&gt; has the same coordinates as a previous segment.

* uni2199 (U+2199): L&lt;&lt;42.0,-16.0&gt;--&lt;35.0,-9.0&gt;&gt; has the same coordinates as a previous segment.

* arrowleft (U+2190): L&lt;&lt;34.0,336.0&gt;--&lt;34.0,346.0&gt;&gt; has the same coordinates as a previous segment.

* uni2196 (U+2196): L&lt;&lt;34.0,690.0&gt;--&lt;41.0,697.0&gt;&gt; has the same coordinates as a previous segment.

* arrowboth (U+2194): L&lt;&lt;946.0,346.0&gt;--&lt;946.0,336.0&gt;&gt; has the same coordinates as a previous segment.

* arrowboth (U+2194): L&lt;&lt;485.0,344.0&gt;--&lt;485.0,338.0&gt;&gt; has the same coordinates as a previous segment.

* arrowboth (U+2194): L&lt;&lt;24.0,336.0&gt;--&lt;24.0,346.0&gt;&gt; has the same coordinates as a previous segment.

* arrowupdn (U+2195): L&lt;&lt;331.0,-114.0&gt;--&lt;321.0,-114.0&gt;&gt; has the same coordinates as a previous segment.

* arrowupdn (U+2195): L&lt;&lt;329.0,347.0&gt;--&lt;323.0,347.0&gt;&gt; has the same coordinates as a previous segment.

* arrowupdn (U+2195): L&lt;&lt;321.0,808.0&gt;--&lt;331.0,808.0&gt;&gt; has the same coordinates as a previous segment.

* uni21C4 (U+21C4): L&lt;&lt;736.0,500.0&gt;--&lt;736.0,490.0&gt;&gt; has the same coordinates as a previous segment.

* uni21C4 (U+21C4): L&lt;&lt;24.0,89.0&gt;--&lt;24.0,99.0&gt;&gt; has the same coordinates as a previous segment.

* uni21C5 (U+21C5): L&lt;&lt;321.0,641.0&gt;--&lt;331.0,641.0&gt;&gt; has the same coordinates as a previous segment.

* uni21C5 (U+21C5): L&lt;&lt;732.0,-71.0&gt;--&lt;722.0,-71.0&gt;&gt; has the same coordinates as a previous segment.
</code></pre>
 [code: overlapping-path-segments]



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
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- ampersand.001

- at.001
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, malayalam, hebrew, duployan, tai-le, syriac, old-permic, todhri, math, tifinagh, canadian-aboriginal</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: coptic, todhri</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: duployan, syriac, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: math, syriac, cherokee</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: thai, cherokee, sunuwar, syriac, gothic, caucasian-albanian, tifinagh</li>
<li>U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: greek, math, elbasan</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: greek, math, elbasan</li>
<li>U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, yi, math</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2010 HYPHEN: try adding one of: coptic, hebrew, kharoshthi, kayah-li, kaithi, sundanese, syloti-nagri, yi, lisu, armenian, cham, sora-sompeng, arabic</li>
<li>U+2012 FIGURE DASH: not included in any glyphset definition</li>
<li>U+2015 HORIZONTAL BAR: try adding adlam</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+203D INTERROBANG: not included in any glyphset definition</li>
<li>U+2042 ASTERISM: not included in any glyphset definition</li>
<li>U+2048 QUESTION EXCLAMATION MARK: try adding mongolian</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2105 CARE OF: try adding math</li>
<li>U+2106 CADA UNA: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math</li>
<li>U+2195 UP DOWN ARROW: try adding one of: symbols, math</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+21BA ANTICLOCKWISE OPEN CIRCLE ARROW: try adding math</li>
<li>U+21BB CLOCKWISE OPEN CIRCLE ARROW: try adding math</li>
<li>U+21C4 RIGHTWARDS ARROW OVER LEFTWARDS ARROW: try adding math</li>
<li>U+21C5 UPWARDS ARROW LEFTWARDS OF DOWNWARDS ARROW: try adding math</li>
<li>U+21E7 UPWARDS WHITE ARROW: try adding symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2205 EMPTY SET: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, symbols, yi, math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+2317 VIEWDATA SQUARE: try adding symbols</li>
<li>U+2318 PLACE OF INTEREST SIGN: try adding symbols</li>
<li>U+2325 OPTION KEY: try adding symbols</li>
<li>U+23CE RETURN SYMBOL: try adding symbols</li>
<li>U+23CF EJECT SYMBOL: try adding symbols</li>
<li>U+23E9 BLACK RIGHT-POINTING DOUBLE TRIANGLE: try adding symbols</li>
<li>U+23EA BLACK LEFT-POINTING DOUBLE TRIANGLE: try adding symbols</li>
<li>U+23ED BLACK RIGHT-POINTING DOUBLE TRIANGLE WITH VERTICAL BAR: try adding symbols</li>
<li>U+23EE BLACK LEFT-POINTING DOUBLE TRIANGLE WITH VERTICAL BAR: try adding symbols</li>
<li>U+23F5 BLACK MEDIUM RIGHT-POINTING TRIANGLE: try adding symbols</li>
<li>U+23F8 DOUBLE VERTICAL BAR: try adding symbols</li>
<li>U+23F9 BLACK SQUARE FOR STOP: try adding symbols</li>
<li>U+23FA BLACK CIRCLE FOR RECORD: try adding symbols</li>
<li>U+2460 CIRCLED DIGIT ONE: try adding one of: symbols, yi, mongolian</li>
<li>U+2461 CIRCLED DIGIT TWO: try adding one of: symbols, yi, mongolian</li>
<li>U+2462 CIRCLED DIGIT THREE: try adding one of: symbols, yi, mongolian</li>
<li>U+2463 CIRCLED DIGIT FOUR: try adding one of: symbols, yi, mongolian</li>
<li>U+2464 CIRCLED DIGIT FIVE: try adding one of: symbols, yi, mongolian</li>
<li>U+2465 CIRCLED DIGIT SIX: try adding one of: symbols, yi, mongolian</li>
<li>U+2466 CIRCLED DIGIT SEVEN: try adding one of: symbols, yi, mongolian</li>
<li>U+2467 CIRCLED DIGIT EIGHT: try adding one of: symbols, yi, mongolian</li>
<li>U+2468 CIRCLED DIGIT NINE: try adding one of: symbols, yi, mongolian</li>
<li>U+24B6 CIRCLED LATIN CAPITAL LETTER A: try adding symbols</li>
<li>U+24B7 CIRCLED LATIN CAPITAL LETTER B: try adding symbols</li>
<li>U+24B8 CIRCLED LATIN CAPITAL LETTER C: try adding symbols</li>
<li>U+24B9 CIRCLED LATIN CAPITAL LETTER D: try adding symbols</li>
<li>U+24BA CIRCLED LATIN CAPITAL LETTER E: try adding symbols</li>
<li>U+24BB CIRCLED LATIN CAPITAL LETTER F: try adding symbols</li>
<li>U+24BC CIRCLED LATIN CAPITAL LETTER G: try adding symbols</li>
<li>U+24BD CIRCLED LATIN CAPITAL LETTER H: try adding symbols</li>
<li>U+24BE CIRCLED LATIN CAPITAL LETTER I: try adding symbols</li>
<li>U+24BF CIRCLED LATIN CAPITAL LETTER J: try adding symbols</li>
<li>U+24C0 CIRCLED LATIN CAPITAL LETTER K: try adding symbols</li>
<li>U+24C1 CIRCLED LATIN CAPITAL LETTER L: try adding symbols</li>
<li>U+24C2 CIRCLED LATIN CAPITAL LETTER M: try adding symbols</li>
<li>U+24C3 CIRCLED LATIN CAPITAL LETTER N: try adding symbols</li>
<li>U+24C4 CIRCLED LATIN CAPITAL LETTER O: try adding symbols</li>
<li>U+24C5 CIRCLED LATIN CAPITAL LETTER P: try adding symbols</li>
<li>U+24C6 CIRCLED LATIN CAPITAL LETTER Q: try adding symbols</li>
<li>U+24C7 CIRCLED LATIN CAPITAL LETTER R: try adding symbols</li>
<li>U+24C8 CIRCLED LATIN CAPITAL LETTER S: try adding symbols</li>
<li>U+24C9 CIRCLED LATIN CAPITAL LETTER T: try adding symbols</li>
<li>U+24CA CIRCLED LATIN CAPITAL LETTER U: try adding symbols</li>
<li>U+24CB CIRCLED LATIN CAPITAL LETTER V: try adding symbols</li>
<li>U+24CC CIRCLED LATIN CAPITAL LETTER W: try adding symbols</li>
<li>U+24CD CIRCLED LATIN CAPITAL LETTER X: try adding symbols</li>
<li>U+24CE CIRCLED LATIN CAPITAL LETTER Y: try adding symbols</li>
<li>U+24CF CIRCLED LATIN CAPITAL LETTER Z: try adding symbols</li>
<li>U+24D0 CIRCLED LATIN SMALL LETTER A: try adding symbols</li>
<li>U+24D1 CIRCLED LATIN SMALL LETTER B: try adding symbols</li>
<li>U+24D2 CIRCLED LATIN SMALL LETTER C: try adding symbols</li>
<li>U+24D3 CIRCLED LATIN SMALL LETTER D: try adding symbols</li>
<li>U+24D4 CIRCLED LATIN SMALL LETTER E: try adding symbols</li>
<li>U+24D5 CIRCLED LATIN SMALL LETTER F: try adding symbols</li>
<li>U+24D6 CIRCLED LATIN SMALL LETTER G: try adding symbols</li>
<li>U+24D7 CIRCLED LATIN SMALL LETTER H: try adding symbols</li>
<li>U+24D8 CIRCLED LATIN SMALL LETTER I: try adding symbols</li>
<li>U+24D9 CIRCLED LATIN SMALL LETTER J: try adding symbols</li>
<li>U+24DA CIRCLED LATIN SMALL LETTER K: try adding symbols</li>
<li>U+24DB CIRCLED LATIN SMALL LETTER L: try adding symbols</li>
<li>U+24DC CIRCLED LATIN SMALL LETTER M: try adding symbols</li>
<li>U+24DD CIRCLED LATIN SMALL LETTER N: try adding symbols</li>
<li>U+24DE CIRCLED LATIN SMALL LETTER O: try adding symbols</li>
<li>U+24DF CIRCLED LATIN SMALL LETTER P: try adding symbols</li>
<li>U+24E0 CIRCLED LATIN SMALL LETTER Q: try adding symbols</li>
<li>U+24E1 CIRCLED LATIN SMALL LETTER R: try adding symbols</li>
<li>U+24E2 CIRCLED LATIN SMALL LETTER S: try adding symbols</li>
<li>U+24E3 CIRCLED LATIN SMALL LETTER T: try adding symbols</li>
<li>U+24E4 CIRCLED LATIN SMALL LETTER U: try adding symbols</li>
<li>U+24E5 CIRCLED LATIN SMALL LETTER V: try adding symbols</li>
<li>U+24E6 CIRCLED LATIN SMALL LETTER W: try adding symbols</li>
<li>U+24E7 CIRCLED LATIN SMALL LETTER X: try adding symbols</li>
<li>U+24E8 CIRCLED LATIN SMALL LETTER Y: try adding symbols</li>
<li>U+24E9 CIRCLED LATIN SMALL LETTER Z: try adding symbols</li>
<li>U+24EA CIRCLED DIGIT ZERO: try adding symbols</li>
<li>U+24FF NEGATIVE CIRCLED DIGIT ZERO: try adding symbols</li>
<li>U+25A0 BLACK SQUARE: try adding symbols</li>
<li>U+25A1 WHITE SQUARE: try adding symbols</li>
<li>U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols</li>
<li>U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding symbols</li>
<li>U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols</li>
<li>U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding symbols</li>
<li>U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25C6 BLACK DIAMOND: try adding symbols</li>
<li>U+25C7 WHITE DIAMOND: try adding symbols</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+25CB WHITE CIRCLE: try adding symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: coptic, wancho, psalter-pahlavi, grantha, math, gurmukhi, khojki, buginese, caucasian-albanian, lao, mende-kikakui, miao, kannada, soyombo, adlam, balinese, music, myanmar, khmer, sogdian, telugu, tai-le, khudawadi, syloti-nagri, manichaean, warang-citi, phags-pa, canadian-aboriginal, hanunoo, marchen, tai-viet, dogra, takri, hanifi-rohingya, tirhuta, newa, thai, duployan, syriac, ahom, masaram-gondi, elbasan, kharoshthi, cham, lepcha, tibetan, devanagari, tamil, modi, bhaiksuki, kaithi, chakma, brahmi, bengali, nko, sundanese, new-tai-lue, tifinagh, batak, hebrew, kayah-li, yi, armenian, symbols, tagbanwa, javanese, osage, oriya, mandaic, sinhala, old-permic, zanabazar-square, buhid, gunjala-gondi, saurashtra, rejang, malayalam, thaana, siddham, tai-tham, sharada, pahawh-hmong, meetei-mayek, tagalog, bassa-vah, gujarati, limbu, mahajani, mongolian</li>
<li>U+25CF BLACK CIRCLE: try adding symbols</li>
<li>U+2606 WHITE STAR: try adding symbols</li>
<li>U+261A BLACK LEFT POINTING INDEX: try adding symbols</li>
<li>U+261B BLACK RIGHT POINTING INDEX: try adding symbols</li>
<li>U+261C WHITE LEFT POINTING INDEX: try adding symbols</li>
<li>U+261D WHITE UP POINTING INDEX: try adding symbols</li>
<li>U+261E WHITE RIGHT POINTING INDEX: try adding symbols</li>
<li>U+261F WHITE DOWN POINTING INDEX: try adding symbols</li>
<li>U+262F YIN YANG: try adding symbols</li>
<li>U+2639 WHITE FROWNING FACE: try adding symbols</li>
<li>U+263A WHITE SMILING FACE: try adding symbols</li>
<li>U+263B BLACK SMILING FACE: try adding symbols</li>
<li>U+2660 BLACK SPADE SUIT: try adding symbols</li>
<li>U+2663 BLACK CLUB SUIT: try adding symbols</li>
<li>U+2665 BLACK HEART SUIT: try adding symbols</li>
<li>U+2666 BLACK DIAMOND SUIT: try adding symbols</li>
<li>U+2713 CHECK MARK: try adding symbols</li>
<li>U+272F PINWHEEL STAR: try adding symbols</li>
<li>U+2735 EIGHT POINTED PINWHEEL STAR: try adding symbols</li>
<li>U+273F BLACK FLORETTE: try adding symbols</li>
<li>U+2740 WHITE FLORETTE: try adding symbols</li>
<li>U+2766 FLORAL HEART: try adding symbols</li>
<li>U+2776 DINGBAT NEGATIVE CIRCLED DIGIT ONE: try adding symbols</li>
<li>U+2777 DINGBAT NEGATIVE CIRCLED DIGIT TWO: try adding symbols</li>
<li>U+2778 DINGBAT NEGATIVE CIRCLED DIGIT THREE: try adding symbols</li>
<li>U+2779 DINGBAT NEGATIVE CIRCLED DIGIT FOUR: try adding symbols</li>
<li>U+277A DINGBAT NEGATIVE CIRCLED DIGIT FIVE: try adding symbols</li>
<li>U+277B DINGBAT NEGATIVE CIRCLED DIGIT SIX: try adding symbols</li>
<li>U+277C DINGBAT NEGATIVE CIRCLED DIGIT SEVEN: try adding symbols</li>
<li>U+277D DINGBAT NEGATIVE CIRCLED DIGIT EIGHT: try adding symbols</li>
<li>U+277E DINGBAT NEGATIVE CIRCLED DIGIT NINE: try adding symbols</li>
<li>U+2B1B BLACK LARGE SQUARE: try adding symbols</li>
<li>U+2B1C WHITE LARGE SQUARE: try adding symbols</li>
<li>U+2B98 THREE-D TOP-LIGHTED LEFTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B99 THREE-D RIGHT-LIGHTED UPWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9A THREE-D TOP-LIGHTED RIGHTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9B THREE-D LEFT-LIGHTED DOWNWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9C BLACK LEFTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9D BLACK UPWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9E BLACK RIGHTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9F BLACK DOWNWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+E133 : not included in any glyphset definition</li>
<li>U+E134 : not included in any glyphset definition</li>
<li>U+E135 : not included in any glyphset definition</li>
<li>U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
<li>U+FB04 LATIN SMALL LIGATURE FFL: not included in any glyphset definition</li>
<li>U+FB06 LATIN SMALL LIGATURE ST: not included in any glyphset definition</li>
<li>U+FFFC OBJECT REPLACEMENT CHARACTER: not included in any glyphset definition</li>
<li>U+1F150 NEGATIVE CIRCLED LATIN CAPITAL LETTER A: try adding symbols</li>
<li>U+1F151 NEGATIVE CIRCLED LATIN CAPITAL LETTER B: try adding symbols</li>
<li>U+1F152 NEGATIVE CIRCLED LATIN CAPITAL LETTER C: try adding symbols</li>
<li>U+1F153 NEGATIVE CIRCLED LATIN CAPITAL LETTER D: try adding symbols</li>
<li>U+1F154 NEGATIVE CIRCLED LATIN CAPITAL LETTER E: try adding symbols</li>
<li>U+1F155 NEGATIVE CIRCLED LATIN CAPITAL LETTER F: try adding symbols</li>
<li>U+1F156 NEGATIVE CIRCLED LATIN CAPITAL LETTER G: try adding symbols</li>
<li>U+1F157 NEGATIVE CIRCLED LATIN CAPITAL LETTER H: try adding symbols</li>
<li>U+1F158 NEGATIVE CIRCLED LATIN CAPITAL LETTER I: try adding symbols</li>
<li>U+1F159 NEGATIVE CIRCLED LATIN CAPITAL LETTER J: try adding symbols</li>
<li>U+1F15A NEGATIVE CIRCLED LATIN CAPITAL LETTER K: try adding symbols</li>
<li>U+1F15B NEGATIVE CIRCLED LATIN CAPITAL LETTER L: try adding symbols</li>
<li>U+1F15C NEGATIVE CIRCLED LATIN CAPITAL LETTER M: try adding symbols</li>
<li>U+1F15D NEGATIVE CIRCLED LATIN CAPITAL LETTER N: try adding symbols</li>
<li>U+1F15E NEGATIVE CIRCLED LATIN CAPITAL LETTER O: try adding symbols</li>
<li>U+1F15F NEGATIVE CIRCLED LATIN CAPITAL LETTER P: try adding symbols</li>
<li>U+1F160 NEGATIVE CIRCLED LATIN CAPITAL LETTER Q: try adding symbols</li>
<li>U+1F161 NEGATIVE CIRCLED LATIN CAPITAL LETTER R: try adding symbols</li>
<li>U+1F162 NEGATIVE CIRCLED LATIN CAPITAL LETTER S: try adding symbols</li>
<li>U+1F163 NEGATIVE CIRCLED LATIN CAPITAL LETTER T: try adding symbols</li>
<li>U+1F164 NEGATIVE CIRCLED LATIN CAPITAL LETTER U: try adding symbols</li>
<li>U+1F165 NEGATIVE CIRCLED LATIN CAPITAL LETTER V: try adding symbols</li>
<li>U+1F166 NEGATIVE CIRCLED LATIN CAPITAL LETTER W: try adding symbols</li>
<li>U+1F167 NEGATIVE CIRCLED LATIN CAPITAL LETTER X: try adding symbols</li>
<li>U+1F168 NEGATIVE CIRCLED LATIN CAPITAL LETTER Y: try adding symbols</li>
<li>U+1F169 NEGATIVE CIRCLED LATIN CAPITAL LETTER Z: try adding symbols</li>
<li>U+1F500 TWISTED RIGHTWARDS ARROWS: not included in any glyphset definition</li>
<li>U+1F501 CLOCKWISE RIGHTWARDS AND LEFTWARDS OPEN CIRCLE ARROWS: not included in any glyphset definition</li>
<li>U+1F502 CLOCKWISE RIGHTWARDS AND LEFTWARDS OPEN CIRCLE ARROWS WITH CIRCLED ONE OVERLAY: not included in any glyphset definition</li>
<li>U+1F503 CLOCKWISE DOWNWARDS AND UPWARDS OPEN CIRCLE ARROWS: try adding symbols</li>
<li>U+1F504 ANTICLOCKWISE DOWNWARDS AND UPWARDS OPEN CIRCLE ARROWS: not included in any glyphset definition</li>
<li>U+1F5A2 BLACK UP POINTING BACKHAND INDEX: try adding symbols</li>
<li>U+1F5A3 BLACK DOWN POINTING BACKHAND INDEX: try adding symbols</li>
<li>U+1F7CF HEAVY EIGHT POINTED BLACK STAR: try adding symbols</li>
<li>U+1F7D3 HEAVY TWELVE POINTED BLACK STAR: try adding symbols</li>
<li>U+1F7D4 HEAVY TWELVE POINTED PINWHEEL STAR: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: j̑</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: j̉ j̏ j̛̉ j̛̏ j̛̑ j̣̉ j̣̏ j̣̑ j̤̉ j̤̏ j̤̑ j̦̉ j̦̏ j̦̑ j̧̉ j̧̏ j̧̑ j̨̉ j̨̏ j̨̑</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-direction">outline_direction</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* eight (U+0038) has a counter-clockwise outer contour

* eight.dnom has a counter-clockwise outer contour

* eight.lf has a counter-clockwise outer contour

* eight.numr has a counter-clockwise outer contour

* eight.osf has a counter-clockwise outer contour

* eight.tf has a counter-clockwise outer contour

* eight.tosf has a counter-clockwise outer contour

* five (U+0035) has a counter-clockwise outer contour

* five.dnom has a counter-clockwise outer contour

* five.lf has a counter-clockwise outer contour

* five.numr has a counter-clockwise outer contour

* five.osf has a counter-clockwise outer contour

* five.tf has a counter-clockwise outer contour

* five.tosf has a counter-clockwise outer contour

* fiveeighths (U+215D) has a counter-clockwise outer contour

* fiveeighths (U+215D) has a counter-clockwise outer contour

* four (U+0034) has a counter-clockwise outer contour

* four.dnom has a counter-clockwise outer contour

* four.lf has a counter-clockwise outer contour

* four.numr has a counter-clockwise outer contour

* heart (U+2665) has a counter-clockwise outer contour

* nine (U+0039) has a counter-clockwise outer contour

* nine.dnom has a counter-clockwise outer contour

* nine.lf has a counter-clockwise outer contour

* nine.numr has a counter-clockwise outer contour

* nine.osf has a counter-clockwise outer contour

* nine.tf has a counter-clockwise outer contour

* nine.tosf has a counter-clockwise outer contour

* one (U+0031) has a counter-clockwise outer contour

* one.dnom has a counter-clockwise outer contour

* one.lf has a counter-clockwise outer contour

* one.numr has a counter-clockwise outer contour

* oneeighth (U+215B) has a counter-clockwise outer contour

* oneeighth (U+215B) has a counter-clockwise outer contour

* onehalf (U+00BD) has a counter-clockwise outer contour

* onehalf (U+00BD) has a counter-clockwise outer contour

* onequarter (U+00BC) has a counter-clockwise outer contour

* onequarter (U+00BC) has a counter-clockwise outer contour

* seven (U+0037) has a counter-clockwise outer contour

* seven.dnom has a counter-clockwise outer contour

* seven.lf has a counter-clockwise outer contour

* seven.numr has a counter-clockwise outer contour

* seven.osf has a counter-clockwise outer contour

* seven.tf has a counter-clockwise outer contour

* seven.tosf has a counter-clockwise outer contour

* seveneighths (U+215E) has a counter-clockwise outer contour

* seveneighths (U+215E) has a counter-clockwise outer contour

* six (U+0036) has a counter-clockwise outer contour

* six.dnom has a counter-clockwise outer contour

* six.lf has a counter-clockwise outer contour

* six.numr has a counter-clockwise outer contour

* six.osf has a counter-clockwise outer contour

* six.tf has a counter-clockwise outer contour

* six.tosf has a counter-clockwise outer contour

* three (U+0033) has a counter-clockwise outer contour

* three.dnom has a counter-clockwise outer contour

* three.lf has a counter-clockwise outer contour

* three.numr has a counter-clockwise outer contour

* three.osf has a counter-clockwise outer contour

* three.tf has a counter-clockwise outer contour

* three.tosf has a counter-clockwise outer contour

* threeeighths (U+215C) has a counter-clockwise outer contour

* threeeighths (U+215C) has a counter-clockwise outer contour

* threequarters (U+00BE) has a counter-clockwise outer contour

* threequarters (U+00BE) has a counter-clockwise outer contour

* two (U+0032) has a counter-clockwise outer contour

* two.dnom has a counter-clockwise outer contour

* two.lf has a counter-clockwise outer contour

* two.numr has a counter-clockwise outer contour

* two.tf has a counter-clockwise outer contour

* uni00B2 (U+00B2) has a counter-clockwise outer contour

* uni00B3 (U+00B3) has a counter-clockwise outer contour

* uni00B9 (U+00B9) has a counter-clockwise outer contour

* uni2074 (U+2074) has a counter-clockwise outer contour

* uni2075 (U+2075) has a counter-clockwise outer contour

* uni2076 (U+2076) has a counter-clockwise outer contour

* uni2077 (U+2077) has a counter-clockwise outer contour

* uni2078 (U+2078) has a counter-clockwise outer contour

* uni2079 (U+2079) has a counter-clockwise outer contour

* uni2081 (U+2081) has a counter-clockwise outer contour

* uni2082 (U+2082) has a counter-clockwise outer contour

* uni2083 (U+2083) has a counter-clockwise outer contour

* uni2084 (U+2084) has a counter-clockwise outer contour

* uni2085 (U+2085) has a counter-clockwise outer contour

* uni2086 (U+2086) has a counter-clockwise outer contour

* uni2087 (U+2087) has a counter-clockwise outer contour

* uni2088 (U+2088) has a counter-clockwise outer contour

* uni2089 (U+2089) has a counter-clockwise outer contour

* uni2153 (U+2153) has a counter-clockwise outer contour

* uni2153 (U+2153) has a counter-clockwise outer contour

* uni2154 (U+2154) has a counter-clockwise outer contour

* uni2154 (U+2154) has a counter-clockwise outer contour

* uni2766 (U+2766) has a counter-clockwise outer contour

* uniFFFD (U+FFFD) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
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
| 0 | 0 | 7 | 10 | 88 | 7 | 124 | 0 | 
| 0% | 0% | 3% | 4% | 37% | 3% | 53% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
