## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[16] Panamera-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** Best SubFamily name is 'Bold'. Expected OS/2 usWeightClass is 700, got 400. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1263, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 414, but got 200 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.0 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̇ ǐ i̒ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ i̮̇ i̮̊ i̮̋ ǐ̮ i̮̒ i̱̇ i̱̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJacute

	- uni01CE.ss01

	- uni030C.alt 

	- whiteCtircle
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 600 among a set of 11 math glyphs.
The following math glyphs have a different width, though:

Width = 667:
logicalnot

Width = 820:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* numbersign (U+0023): X=523.0,Y=-2.0 (should be at baseline 0?)

	* numbersign (U+0023): X=366.0,Y=-2.0 (should be at baseline 0?)

	* numbersign (U+0023): X=218.0,Y=-2.0 (should be at baseline 0?)

	* numbersign (U+0023): X=62.0,Y=-2.0 (should be at baseline 0?)

	* dollar (U+0024): X=385.0,Y=702.0 (should be at cap-height 700?)

	* ampersand (U+0026): X=636.5,Y=2.0 (should be at baseline 0?)

	* ampersand (U+0026): X=457.0,Y=1.5 (should be at baseline 0?)

	* colon (U+003A): X=45.0,Y=-1.0 (should be at baseline 0?)

	* colon (U+003A): X=225.0,Y=-1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=133.0,Y=2.0 (should be at baseline 0?)

	* semicolon (U+003B): X=71.0,Y=2.0 (should be at baseline 0?)

	* semicolon (U+003B): X=249.0,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=172.5,Y=701.5 (should be at cap-height 700?)

	* M (U+004D): X=243.0,Y=701.0 (should be at cap-height 700?)

	* M (U+004D): X=691.0,Y=701.0 (should be at cap-height 700?)

	* f (U+0066): X=7.0,Y=501.0 (should be at x-height 500?)

	* f (U+0066): X=93.0,Y=501.0 (should be at x-height 500?)

	* f (U+0066): X=274.0,Y=501.0 (should be at x-height 500?)

	* f (U+0066): X=402.0,Y=501.0 (should be at x-height 500?)

	* sterling (U+00A3): X=250.0,Y=700.5 (should be at cap-height 700?)

	* section (U+00A7): X=148.0,Y=-199.5 (should be at descender -200?)

	* plusminus (U+00B1): X=36.0,Y=-1.0 (should be at baseline 0?)

	* plusminus (U+00B1): X=563.0,Y=-1.0 (should be at baseline 0?)

	* uni00B2 (U+00B2): X=119.0,Y=698.0 (should be at cap-height 700?)

	* cedilla (U+00B8): X=200.0,Y=-198.0 (should be at descender -200?)

	* questiondown (U+00BF): X=340.5,Y=-198.5 (should be at descender -200?)

	* Ccedilla (U+00C7): X=297.0,Y=-198.0 (should be at descender -200?)

	* ccedilla (U+00E7): X=195.0,Y=-198.0 (should be at descender -200?)

	* eth (U+00F0): X=346.0,Y=698.0 (should be at cap-height 700?)

	* divide (U+00F7): X=207.0,Y=-1.0 (should be at baseline 0?)

	* divide (U+00F7): X=387.0,Y=-1.0 (should be at baseline 0?)

	* Lcaron (U+013D): X=430.0,Y=701.0 (should be at cap-height 700?)

	* Scedilla (U+015E): X=204.0,Y=-198.0 (should be at descender -200?)

	* scedilla (U+015F): X=150.0,Y=-198.0 (should be at descender -200?)

	* uni0162 (U+0162): X=242.0,Y=-198.0 (should be at descender -200?)

	* uni0163 (U+0163): X=161.0,Y=-198.0 (should be at descender -200?)

	* uni0327 (U+0327): X=200.0,Y=-198.0 (should be at descender -200?)

	* uni1E08 (U+1E08): X=297.0,Y=-198.0 (should be at descender -200?)

	* uni1E09 (U+1E09): X=195.0,Y=-198.0 (should be at descender -200?)

	* uni1E1C (U+1E1C): X=236.0,Y=-198.0 (should be at descender -200?)

	* uni1E1D (U+1E1D): X=185.0,Y=-198.0 (should be at descender -200?)

	* uni1E42 (U+1E42): X=243.0,Y=701.0 (should be at cap-height 700?)

	* uni1E42 (U+1E42): X=691.0,Y=701.0 (should be at cap-height 700?)

	* uni2088 (U+2088): X=173.0,Y=-2.0 (should be at baseline 0?)

	* uni2088 (U+2088): X=173.0,Y=-2.0 (should be at baseline 0?)

	* uni2105 (U+2105): X=335.5,Y=701.5 (should be at cap-height 700?)

	* uni2106 (U+2106): X=335.5,Y=701.5 (should be at cap-height 700?)

	* trademark (U+2122): X=405.0,Y=698.0 (should be at cap-height 700?)

	* trademark (U+2122): X=515.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=702.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=811.0,Y=698.0 (should be at cap-height 700?)

	* trademark (U+2122): X=65.0,Y=698.0 (should be at cap-height 700?)

	* trademark (U+2122): X=352.0,Y=698.0 (should be at cap-height 700?)

	* partialdiff (U+2202): X=169.0,Y=-0.5 (should be at baseline 0?)

	* product (U+220F): X=1.0,Y=699.0 (should be at cap-height 700?)

	* product (U+220F): X=687.0,Y=699.0 (should be at cap-height 700?)

	* summation (U+2211): X=60.0,Y=699.0 (should be at cap-height 700?) 

	* summation (U+2211): X=678.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<183.0,83.0>--<188.0,26.0>> -> L<<188.0,26.0>--<188.0,0.0>>

	* b (U+0062): L<<188.0,700.0>--<188.0,490.0>> -> L<<188.0,490.0>--<181.0,409.0>>

	* d (U+0064): L<<450.0,0.0>--<450.0,26.0>> -> L<<450.0,26.0>--<455.0,83.0>>

	* d (U+0064): L<<457.0,409.0>--<450.0,490.0>> -> L<<450.0,490.0>--<450.0,700.0>>

	* dcaron (U+010F): L<<450.0,0.0>--<450.0,26.0>> -> L<<450.0,26.0>--<455.0,83.0>>

	* dcaron (U+010F): L<<457.0,409.0>--<450.0,490.0>> -> L<<450.0,490.0>--<450.0,700.0>>

	* dcroat (U+0111): L<<450.0,0.0>--<450.0,26.0>> -> L<<450.0,26.0>--<455.0,83.0>>

	* dcroat (U+0111): L<<457.0,409.0>--<450.0,490.0>> -> L<<450.0,490.0>--<450.0,538.0>>

	* dmacronbelow (U+1E0F): L<<450.0,0.0>--<450.0,26.0>> -> L<<450.0,26.0>--<455.0,83.0>>

	* dmacronbelow (U+1E0F): L<<457.0,409.0>--<450.0,490.0>> -> L<<450.0,490.0>--<450.0,700.0>>

	* eng (U+014B): L<<570.0,294.0>--<570.0,0.0>> -> L<<570.0,0.0>--<570.0,-65.0>>

	* exclam (U+0021): L<<244.0,730.0>--<243.0,577.0>> -> L<<243.0,577.0>--<223.0,218.0>>

	* exclam (U+0021): L<<87.0,218.0>--<66.0,577.0>> -> L<<66.0,577.0>--<66.0,730.0>>

	* exclamdown (U+00A1): L<<223.0,322.0>--<243.0,-37.0>> -> L<<243.0,-37.0>--<244.0,-190.0>>

	* exclamdown (U+00A1): L<<66.0,-190.0>--<66.0,-37.0>> -> L<<66.0,-37.0>--<87.0,322.0>>

	* g (U+0067): L<<450.0,8.0>--<450.0,43.0>> -> L<<450.0,43.0>--<454.0,84.0>>

	* g (U+0067): L<<455.0,417.0>--<450.0,474.0>> -> L<<450.0,474.0>--<450.0,500.0>>

	* gbreve (U+011F): L<<450.0,8.0>--<450.0,43.0>> -> L<<450.0,43.0>--<454.0,84.0>>

	* gbreve (U+011F): L<<455.0,417.0>--<450.0,474.0>> -> L<<450.0,474.0>--<450.0,500.0>>

	* gcaron (U+01E7): L<<450.0,8.0>--<450.0,43.0>> -> L<<450.0,43.0>--<454.0,84.0>>

	* gcaron (U+01E7): L<<455.0,417.0>--<450.0,474.0>> -> L<<450.0,474.0>--<450.0,500.0>>

	* gcircumflex (U+011D): L<<450.0,8.0>--<450.0,43.0>> -> L<<450.0,43.0>--<454.0,84.0>>

	* gcircumflex (U+011D): L<<455.0,417.0>--<450.0,474.0>> -> L<<450.0,474.0>--<450.0,500.0>>

	* gdotaccent (U+0121): L<<450.0,8.0>--<450.0,43.0>> -> L<<450.0,43.0>--<454.0,84.0>>

	* gdotaccent (U+0121): L<<455.0,417.0>--<450.0,474.0>> -> L<<450.0,474.0>--<450.0,500.0>>

	* p (U+0070): L<<181.0,91.0>--<188.0,10.0>> -> L<<188.0,10.0>--<188.0,-200.0>>

	* p (U+0070): L<<188.0,500.0>--<188.0,474.0>> -> L<<188.0,474.0>--<183.0,417.0>>

	* q (U+0071): L<<450.0,-200.0>--<450.0,10.0>> -> L<<450.0,10.0>--<457.0,91.0>>

	* q (U+0071): L<<455.0,417.0>--<450.0,474.0>> -> L<<450.0,474.0>--<450.0,500.0>>

	* uni0123 (U+0123): L<<450.0,8.0>--<450.0,43.0>> -> L<<450.0,43.0>--<454.0,84.0>>

	* uni0123 (U+0123): L<<455.0,417.0>--<450.0,474.0>> -> L<<450.0,474.0>--<450.0,500.0>>

	* uni1E0D (U+1E0D): L<<450.0,0.0>--<450.0,26.0>> -> L<<450.0,26.0>--<455.0,83.0>>

	* uni1E0D (U+1E0D): L<<457.0,409.0>--<450.0,490.0>> -> L<<450.0,490.0>--<450.0,700.0>>

	* uni1E21 (U+1E21): L<<450.0,8.0>--<450.0,43.0>> -> L<<450.0,43.0>--<454.0,84.0>> 

	* uni1E21 (U+1E21): L<<455.0,417.0>--<450.0,474.0>> -> L<<450.0,474.0>--<450.0,500.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Ccedilla (U+00C7): L<<423.0,7.0>--<391.0,-49.0>>/B<<391.0,-49.0>-<398.0,-40.0>-<412.5,-33.5>> = 8.13010235415596

	* Scedilla (U+015E): L<<330.0,7.0>--<298.0,-49.0>>/B<<298.0,-49.0>-<305.0,-40.0>-<319.5,-33.5>> = 8.13010235415596

	* ccedilla (U+00E7): L<<321.0,7.0>--<289.0,-49.0>>/B<<289.0,-49.0>-<296.0,-40.0>-<310.5,-33.5>> = 8.13010235415596

	* cedilla (U+00B8): L<<326.0,7.0>--<294.0,-49.0>>/B<<294.0,-49.0>-<301.0,-40.0>-<315.5,-33.5>> = 8.13010235415596

	* scedilla (U+015F): L<<276.0,7.0>--<244.0,-49.0>>/B<<244.0,-49.0>-<251.0,-40.0>-<265.5,-33.5>> = 8.13010235415596

	* uni0162 (U+0162): L<<368.0,7.0>--<336.0,-49.0>>/B<<336.0,-49.0>-<343.0,-40.0>-<357.5,-33.5>> = 8.13010235415596

	* uni0163 (U+0163): L<<287.0,7.0>--<255.0,-49.0>>/B<<255.0,-49.0>-<262.0,-40.0>-<276.5,-33.5>> = 8.13010235415596

	* uni0327 (U+0327): L<<326.0,7.0>--<294.0,-49.0>>/B<<294.0,-49.0>-<301.0,-40.0>-<315.5,-33.5>> = 8.13010235415596

	* uni1E08 (U+1E08): L<<423.0,7.0>--<391.0,-49.0>>/B<<391.0,-49.0>-<398.0,-40.0>-<412.5,-33.5>> = 8.13010235415596

	* uni1E09 (U+1E09): L<<321.0,7.0>--<289.0,-49.0>>/B<<289.0,-49.0>-<296.0,-40.0>-<310.5,-33.5>> = 8.13010235415596

	* uni1E1C (U+1E1C): L<<362.0,7.0>--<330.0,-49.0>>/B<<330.0,-49.0>-<337.0,-40.0>-<351.5,-33.5>> = 8.13010235415596 

	* uni1E1D (U+1E1D): L<<311.0,7.0>--<279.0,-49.0>>/B<<279.0,-49.0>-<286.0,-40.0>-<300.5,-33.5>> = 8.13010235415596 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* IJ (U+0132): L<<830.0,700.0>--<831.0,257.0>>

	* J (U+004A): L<<536.0,700.0>--<537.0,257.0>>

	* Jcircumflex (U+0134): L<<536.0,700.0>--<537.0,257.0>>

	* Lslash (U+0141): L<<35.0,283.0>--<34.0,408.0>>

	* M (U+004D): L<<50.0,700.0>--<243.0,701.0>>

	* M (U+004D): L<<691.0,701.0>--<884.0,700.0>>

	* U (U+0055): L<<33.0,228.0>--<34.0,700.0>>

	* U (U+0055): L<<588.0,700.0>--<589.0,228.0>>

	* Uacute (U+00DA): L<<33.0,228.0>--<34.0,700.0>>

	* Uacute (U+00DA): L<<588.0,700.0>--<589.0,228.0>>

	* Ubreve (U+016C): L<<33.0,228.0>--<34.0,700.0>>

	* Ubreve (U+016C): L<<588.0,700.0>--<589.0,228.0>>

	* Ucircumflex (U+00DB): L<<33.0,228.0>--<34.0,700.0>>

	* Ucircumflex (U+00DB): L<<588.0,700.0>--<589.0,228.0>>

	* Udieresis (U+00DC): L<<33.0,228.0>--<34.0,700.0>>

	* Udieresis (U+00DC): L<<588.0,700.0>--<589.0,228.0>>

	* Ugrave (U+00D9): L<<33.0,228.0>--<34.0,700.0>>

	* Ugrave (U+00D9): L<<588.0,700.0>--<589.0,228.0>>

	* Uhungarumlaut (U+0170): L<<33.0,228.0>--<34.0,700.0>>

	* Uhungarumlaut (U+0170): L<<588.0,700.0>--<589.0,228.0>>

	* Umacron (U+016A): L<<33.0,228.0>--<34.0,700.0>>

	* Umacron (U+016A): L<<588.0,700.0>--<589.0,228.0>>

	* Uogonek (U+0172): L<<33.0,228.0>--<34.0,700.0>>

	* Uogonek (U+0172): L<<588.0,700.0>--<589.0,228.0>>

	* Uring (U+016E): L<<33.0,228.0>--<34.0,700.0>>

	* Uring (U+016E): L<<588.0,700.0>--<589.0,228.0>>

	* Utilde (U+0168): L<<33.0,228.0>--<34.0,700.0>>

	* Utilde (U+0168): L<<588.0,700.0>--<589.0,228.0>>

	* at (U+0040): L<<431.0,325.0>--<271.0,326.0>>

	* b (U+0062): L<<36.0,0.0>--<35.0,700.0>>

	* d (U+0064): L<<603.0,700.0>--<602.0,0.0>>

	* dcaron (U+010F): L<<603.0,700.0>--<602.0,0.0>>

	* dcroat (U+0111): L<<603.0,538.0>--<602.0,0.0>>

	* dmacronbelow (U+1E0F): L<<603.0,700.0>--<602.0,0.0>>

	* exclam (U+0021): L<<244.0,730.0>--<243.0,577.0>>

	* exclamdown (U+00A1): L<<243.0,-37.0>--<244.0,-190.0>>

	* f (U+0066): L<<94.0,0.0>--<95.0,385.0>>

	* fi (U+FB01): L<<94.0,0.0>--<95.0,385.0>>

	* four (U+0034): L<<333.0,186.0>--<30.0,187.0>>

	* g (U+0067): L<<602.0,500.0>--<603.0,8.0>>

	* gbreve (U+011F): L<<602.0,500.0>--<603.0,8.0>>

	* gcaron (U+01E7): L<<602.0,500.0>--<603.0,8.0>>

	* gcircumflex (U+011D): L<<602.0,500.0>--<603.0,8.0>>

	* gdotaccent (U+0121): L<<602.0,500.0>--<603.0,8.0>>

	* lslash (U+0142): L<<419.0,512.0>--<420.0,389.0>>

	* lslash (U+0142): L<<53.0,284.0>--<52.0,407.0>>

	* p (U+0070): L<<35.0,-200.0>--<36.0,500.0>>

	* q (U+0071): L<<602.0,500.0>--<603.0,-200.0>>

	* thorn (U+00FE): L<<25.0,-191.0>--<26.0,761.0>>

	* uni0123 (U+0123): L<<602.0,500.0>--<603.0,8.0>>

	* uni1E0D (U+1E0D): L<<603.0,700.0>--<602.0,0.0>>

	* uni1E21 (U+1E21): L<<602.0,500.0>--<603.0,8.0>>

	* uni1E42 (U+1E42): L<<50.0,700.0>--<243.0,701.0>>

	* uni1E42 (U+1E42): L<<691.0,701.0>--<884.0,700.0>>

	* uni1E78 (U+1E78): L<<33.0,228.0>--<34.0,700.0>>

	* uni1E78 (U+1E78): L<<588.0,700.0>--<589.0,228.0>>

	* uni1E7A (U+1E7A): L<<33.0,228.0>--<34.0,700.0>>

	* uni1E7A (U+1E7A): L<<588.0,700.0>--<589.0,228.0>>

	* uni1EE4 (U+1EE4): L<<33.0,228.0>--<34.0,700.0>> 

	* uni1EE4 (U+1EE4): L<<588.0,700.0>--<589.0,228.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] Panamera-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** Best SubFamily name is 'Light'. Expected OS/2 usWeightClass is 300, got 400. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1263, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 414, but got 200 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.0 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̇ ǐ i̒ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ i̮̇ i̮̊ i̮̋ ǐ̮ i̮̒ i̱̇ i̱̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJacute

	- uni01CE.ss01

	- uni030C.alt 

	- whiteCtircle
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 600 among a set of 11 math glyphs.
The following math glyphs have a different width, though:

Width = 667:
logicalnot

Width = 820:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* exclam (U+0021): L<<142.0,214.0>--<123.0,608.0>> -> L<<123.0,608.0>--<123.0,731.0>>

	* exclam (U+0021): L<<187.0,731.0>--<187.0,608.0>> -> L<<187.0,608.0>--<168.0,214.0>>

	* exclamdown (U+00A1): L<<123.0,-191.0>--<123.0,-68.0>> -> L<<123.0,-68.0>--<142.0,326.0>>

	* exclamdown (U+00A1): L<<168.0,326.0>--<187.0,-68.0>> -> L<<187.0,-68.0>--<187.0,-191.0>> 

	* thorn (U+00FE): L<<74.0,177.0>--<81.0,96.0>> -> L<<81.0,96.0>--<81.0,-238.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* G (U+0047): L<<661.0,0.0>--<661.0,248.0>>/B<<661.0,248.0>-<651.0,173.0>-<617.0,116.0>> = 7.594643368591447

	* Gbreve (U+011E): L<<661.0,0.0>--<661.0,248.0>>/B<<661.0,248.0>-<651.0,173.0>-<617.0,116.0>> = 7.594643368591447

	* Gcaron (U+01E6): L<<661.0,0.0>--<661.0,248.0>>/B<<661.0,248.0>-<651.0,173.0>-<617.0,116.0>> = 7.594643368591447

	* Gcircumflex (U+011C): L<<661.0,0.0>--<661.0,248.0>>/B<<661.0,248.0>-<651.0,173.0>-<617.0,116.0>> = 7.594643368591447

	* Gdotaccent (U+0120): L<<661.0,0.0>--<661.0,248.0>>/B<<661.0,248.0>-<651.0,173.0>-<617.0,116.0>> = 7.594643368591447

	* at (U+0040): B<<680.0,32.0>-<644.0,64.0>-<644.0,150.0>>/B<<644.0,150.0>-<635.0,88.0>-<607.5,51.5>> = 8.259437979878793

	* b (U+0062): B<<128.5,80.0>-<101.0,121.0>-<89.0,168.0>>/L<<89.0,168.0>--<95.0,118.0>> = 7.479946565572559

	* b (U+0062): L<<95.0,398.0>--<87.0,327.0>>/B<<87.0,327.0>-<99.0,375.0>-<126.5,417.5>> = 7.607495719096593

	* d (U+0064): B<<456.5,417.5>-<484.0,375.0>-<496.0,327.0>>/L<<496.0,327.0>--<488.0,398.0>> = 7.607495719096593

	* d (U+0064): L<<488.0,118.0>--<494.0,168.0>>/B<<494.0,168.0>-<482.0,121.0>-<454.5,80.0>> = 7.479946565572559

	* dcaron (U+010F): B<<456.5,417.5>-<484.0,375.0>-<496.0,327.0>>/L<<496.0,327.0>--<488.0,398.0>> = 7.607495719096593

	* dcaron (U+010F): L<<488.0,118.0>--<494.0,168.0>>/B<<494.0,168.0>-<482.0,121.0>-<454.5,80.0>> = 7.479946565572559

	* dcroat (U+0111): B<<456.5,417.5>-<484.0,375.0>-<496.0,327.0>>/L<<496.0,327.0>--<488.0,398.0>> = 7.607495719096593

	* dcroat (U+0111): L<<488.0,118.0>--<494.0,168.0>>/B<<494.0,168.0>-<482.0,121.0>-<454.5,80.0>> = 7.479946565572559

	* dmacronbelow (U+1E0F): B<<456.5,417.5>-<484.0,375.0>-<496.0,327.0>>/L<<496.0,327.0>--<488.0,398.0>> = 7.607495719096593

	* dmacronbelow (U+1E0F): L<<488.0,118.0>--<494.0,168.0>>/B<<494.0,168.0>-<482.0,121.0>-<454.5,80.0>> = 7.479946565572559

	* f (U+0066): L<<9.0,501.0>--<176.0,501.0>>/B<<176.0,501.0>-<115.0,511.0>-<86.5,547.5>> = 9.30994017498601

	* g (U+0067): B<<454.5,420.0>-<482.0,379.0>-<494.0,332.0>>/L<<494.0,332.0>--<488.0,382.0>> = 7.479946565572559

	* g (U+0067): L<<488.0,116.0>--<494.0,167.0>>/B<<494.0,167.0>-<482.0,120.0>-<454.0,79.0>> = 7.6128831704466275

	* gbreve (U+011F): B<<454.5,420.0>-<482.0,379.0>-<494.0,332.0>>/L<<494.0,332.0>--<488.0,382.0>> = 7.479946565572559

	* gbreve (U+011F): L<<488.0,116.0>--<494.0,167.0>>/B<<494.0,167.0>-<482.0,120.0>-<454.0,79.0>> = 7.6128831704466275

	* gcaron (U+01E7): B<<454.5,420.0>-<482.0,379.0>-<494.0,332.0>>/L<<494.0,332.0>--<488.0,382.0>> = 7.479946565572559

	* gcaron (U+01E7): L<<488.0,116.0>--<494.0,167.0>>/B<<494.0,167.0>-<482.0,120.0>-<454.0,79.0>> = 7.6128831704466275

	* gcircumflex (U+011D): B<<454.5,420.0>-<482.0,379.0>-<494.0,332.0>>/L<<494.0,332.0>--<488.0,382.0>> = 7.479946565572559

	* gcircumflex (U+011D): L<<488.0,116.0>--<494.0,167.0>>/B<<494.0,167.0>-<482.0,120.0>-<454.0,79.0>> = 7.6128831704466275

	* gdotaccent (U+0121): B<<454.5,420.0>-<482.0,379.0>-<494.0,332.0>>/L<<494.0,332.0>--<488.0,382.0>> = 7.479946565572559

	* gdotaccent (U+0121): L<<488.0,116.0>--<494.0,167.0>>/B<<494.0,167.0>-<482.0,120.0>-<454.0,79.0>> = 7.6128831704466275

	* p (U+0070): B<<126.5,82.5>-<99.0,125.0>-<87.0,173.0>>/L<<87.0,173.0>--<95.0,102.0>> = 7.607495719096593

	* p (U+0070): L<<95.0,382.0>--<89.0,332.0>>/B<<89.0,332.0>-<101.0,379.0>-<128.5,420.0>> = 7.479946565572559

	* q (U+0071): B<<454.5,420.0>-<482.0,379.0>-<494.0,332.0>>/L<<494.0,332.0>--<488.0,382.0>> = 7.479946565572559

	* q (U+0071): L<<488.0,102.0>--<496.0,173.0>>/B<<496.0,173.0>-<484.0,125.0>-<456.5,82.5>> = 7.607495719096593

	* r (U+0072): L<<94.0,500.0>--<94.0,331.0>>/B<<94.0,331.0>-<105.0,387.0>-<135.5,426.0>> = 11.113040535948294

	* racute (U+0155): L<<94.0,500.0>--<94.0,331.0>>/B<<94.0,331.0>-<105.0,387.0>-<135.5,426.0>> = 11.113040535948294

	* rcaron (U+0159): L<<94.0,500.0>--<94.0,331.0>>/B<<94.0,331.0>-<105.0,387.0>-<135.5,426.0>> = 11.113040535948294

	* rmacronbelow (U+1E5F): L<<94.0,500.0>--<94.0,331.0>>/B<<94.0,331.0>-<105.0,387.0>-<135.5,426.0>> = 11.113040535948294

	* thorn (U+00FE): B<<112.5,82.5>-<85.0,127.0>-<74.0,177.0>>/L<<74.0,177.0>--<81.0,96.0>> = 7.468202985274523

	* thorn (U+00FE): L<<81.0,376.0>--<74.0,307.0>>/B<<74.0,307.0>-<84.0,357.0>-<111.5,402.5>> = 5.517135978988034

	* u (U+0075): L<<476.0,1.0>--<476.0,146.0>>/B<<476.0,146.0>-<463.0,95.0>-<428.5,61.0>> = 14.300277449185575

	* uacute (U+00FA): L<<476.0,1.0>--<476.0,146.0>>/B<<476.0,146.0>-<463.0,95.0>-<428.5,61.0>> = 14.300277449185575

	* ubreve (U+016D): L<<476.0,1.0>--<476.0,146.0>>/B<<476.0,146.0>-<463.0,95.0>-<428.5,61.0>> = 14.300277449185575

	* ucircumflex (U+00FB): L<<476.0,1.0>--<476.0,146.0>>/B<<476.0,146.0>-<463.0,95.0>-<428.5,61.0>> = 14.300277449185575

	* udieresis (U+00FC): L<<476.0,1.0>--<476.0,146.0>>/B<<476.0,146.0>-<463.0,95.0>-<428.5,61.0>> = 14.300277449185575

	* ugrave (U+00F9): L<<476.0,1.0>--<476.0,146.0>>/B<<476.0,146.0>-<463.0,95.0>-<428.5,61.0>> = 14.300277449185575

	* uhungarumlaut (U+0171): L<<476.0,1.0>--<476.0,146.0>>/B<<476.0,146.0>-<463.0,95.0>-<428.5,61.0>> = 14.300277449185575

	* umacron (U+016B): L<<476.0,1.0>--<476.0,146.0>>/B<<476.0,146.0>-<463.0,95.0>-<428.5,61.0>> = 14.300277449185575

	* uni0122 (U+0122): L<<661.0,0.0>--<661.0,248.0>>/B<<661.0,248.0>-<651.0,173.0>-<617.0,116.0>> = 7.594643368591447

	* uni0123 (U+0123): B<<454.5,420.0>-<482.0,379.0>-<494.0,332.0>>/L<<494.0,332.0>--<488.0,382.0>> = 7.479946565572559

	* uni0123 (U+0123): L<<488.0,116.0>--<494.0,167.0>>/B<<494.0,167.0>-<482.0,120.0>-<454.0,79.0>> = 7.6128831704466275

	* uni0157 (U+0157): L<<94.0,500.0>--<94.0,331.0>>/B<<94.0,331.0>-<105.0,387.0>-<135.5,426.0>> = 11.113040535948294

	* uni03A9 (U+03A9): B<<627.0,88.5>-<594.0,55.0>-<550.0,44.0>>/L<<550.0,44.0>--<742.0,44.0>> = 14.036243467926484

	* uni1E0D (U+1E0D): B<<456.5,417.5>-<484.0,375.0>-<496.0,327.0>>/L<<496.0,327.0>--<488.0,398.0>> = 7.607495719096593

	* uni1E0D (U+1E0D): L<<488.0,118.0>--<494.0,168.0>>/B<<494.0,168.0>-<482.0,121.0>-<454.5,80.0>> = 7.479946565572559

	* uni1E20 (U+1E20): L<<661.0,0.0>--<661.0,248.0>>/B<<661.0,248.0>-<651.0,173.0>-<617.0,116.0>> = 7.594643368591447

	* uni1E21 (U+1E21): B<<454.5,420.0>-<482.0,379.0>-<494.0,332.0>>/L<<494.0,332.0>--<488.0,382.0>> = 7.479946565572559

	* uni1E21 (U+1E21): L<<488.0,116.0>--<494.0,167.0>>/B<<494.0,167.0>-<482.0,120.0>-<454.0,79.0>> = 7.6128831704466275

	* uni1E5B (U+1E5B): L<<94.0,500.0>--<94.0,331.0>>/B<<94.0,331.0>-<105.0,387.0>-<135.5,426.0>> = 11.113040535948294

	* uni1E79 (U+1E79): L<<476.0,1.0>--<476.0,146.0>>/B<<476.0,146.0>-<463.0,95.0>-<428.5,61.0>> = 14.300277449185575

	* uni1E7B (U+1E7B): L<<476.0,1.0>--<476.0,146.0>>/B<<476.0,146.0>-<463.0,95.0>-<428.5,61.0>> = 14.300277449185575

	* uni1EE5 (U+1EE5): L<<476.0,1.0>--<476.0,146.0>>/B<<476.0,146.0>-<463.0,95.0>-<428.5,61.0>> = 14.300277449185575

	* uni2126 (U+2126): B<<627.0,88.5>-<594.0,55.0>-<550.0,44.0>>/L<<550.0,44.0>--<742.0,44.0>> = 14.036243467926484

	* uogonek (U+0173): L<<476.0,1.0>--<476.0,146.0>>/B<<476.0,146.0>-<463.0,95.0>-<428.5,61.0>> = 14.300277449185575

	* uring (U+016F): L<<476.0,1.0>--<476.0,146.0>>/B<<476.0,146.0>-<463.0,95.0>-<428.5,61.0>> = 14.300277449185575 

	* utilde (U+0169): L<<476.0,1.0>--<476.0,146.0>>/B<<476.0,146.0>-<463.0,95.0>-<428.5,61.0>> = 14.300277449185575 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* D (U+0044): L<<217.0,659.0>--<98.0,658.0>>

	* Dcaron (U+010E): L<<217.0,659.0>--<98.0,658.0>>

	* Dcroat (U+0110): L<<327.0,659.0>--<208.0,658.0>>

	* Dmacronbelow (U+1E0E): L<<217.0,659.0>--<98.0,658.0>>

	* Eth (U+00D0): L<<327.0,659.0>--<208.0,658.0>>

	* IJ (U+0132): L<<695.0,700.0>--<696.0,195.0>>

	* J (U+004A): L<<487.0,700.0>--<488.0,195.0>>

	* Jcircumflex (U+0134): L<<487.0,700.0>--<488.0,195.0>>

	* R (U+0052): L<<233.0,390.0>--<99.0,389.0>>

	* Racute (U+0154): L<<233.0,390.0>--<99.0,389.0>>

	* Rcaron (U+0158): L<<233.0,390.0>--<99.0,389.0>>

	* Rmacronbelow (U+1E5E): L<<233.0,390.0>--<99.0,389.0>>

	* U (U+0055): L<<561.0,700.0>--<562.0,212.0>>

	* U (U+0055): L<<60.0,212.0>--<61.0,700.0>>

	* Uacute (U+00DA): L<<561.0,700.0>--<562.0,212.0>>

	* Uacute (U+00DA): L<<60.0,212.0>--<61.0,700.0>>

	* Ubreve (U+016C): L<<561.0,700.0>--<562.0,212.0>>

	* Ubreve (U+016C): L<<60.0,212.0>--<61.0,700.0>>

	* Ucircumflex (U+00DB): L<<561.0,700.0>--<562.0,212.0>>

	* Ucircumflex (U+00DB): L<<60.0,212.0>--<61.0,700.0>>

	* Udieresis (U+00DC): L<<561.0,700.0>--<562.0,212.0>>

	* Udieresis (U+00DC): L<<60.0,212.0>--<61.0,700.0>>

	* Ugrave (U+00D9): L<<561.0,700.0>--<562.0,212.0>>

	* Ugrave (U+00D9): L<<60.0,212.0>--<61.0,700.0>>

	* Uhungarumlaut (U+0170): L<<561.0,700.0>--<562.0,212.0>>

	* Uhungarumlaut (U+0170): L<<60.0,212.0>--<61.0,700.0>>

	* Umacron (U+016A): L<<561.0,700.0>--<562.0,212.0>>

	* Umacron (U+016A): L<<60.0,212.0>--<61.0,700.0>>

	* Uogonek (U+0172): L<<561.0,700.0>--<562.0,212.0>>

	* Uogonek (U+0172): L<<60.0,212.0>--<61.0,700.0>>

	* Uring (U+016E): L<<561.0,700.0>--<562.0,212.0>>

	* Uring (U+016E): L<<60.0,212.0>--<61.0,700.0>>

	* Utilde (U+0168): L<<561.0,700.0>--<562.0,212.0>>

	* Utilde (U+0168): L<<60.0,212.0>--<61.0,700.0>>

	* b (U+0062): L<<51.0,0.0>--<50.0,700.0>>

	* d (U+0064): L<<533.0,700.0>--<532.0,0.0>>

	* dcaron (U+010F): L<<533.0,700.0>--<532.0,0.0>>

	* dcroat (U+0111): L<<533.0,598.0>--<532.0,0.0>>

	* dmacronbelow (U+1E0F): L<<533.0,700.0>--<532.0,0.0>>

	* f (U+0066): L<<114.0,1.0>--<115.0,466.0>>

	* fi (U+FB01): L<<114.0,1.0>--<115.0,466.0>>

	* fi (U+FB01): L<<190.0,501.0>--<485.0,500.0>>

	* four (U+0034): L<<380.0,242.0>--<34.0,243.0>>

	* g (U+0067): L<<532.0,500.0>--<533.0,-1.0>>

	* gbreve (U+011F): L<<532.0,500.0>--<533.0,-1.0>>

	* gcaron (U+01E7): L<<532.0,500.0>--<533.0,-1.0>>

	* gcircumflex (U+011D): L<<532.0,500.0>--<533.0,-1.0>>

	* gdotaccent (U+0121): L<<532.0,500.0>--<533.0,-1.0>>

	* p (U+0070): L<<50.0,-200.0>--<51.0,500.0>>

	* q (U+0071): L<<532.0,500.0>--<533.0,-200.0>>

	* thorn (U+00FE): L<<36.0,-238.0>--<37.0,808.0>>

	* uni0123 (U+0123): L<<532.0,500.0>--<533.0,-1.0>>

	* uni0156 (U+0156): L<<233.0,390.0>--<99.0,389.0>>

	* uni1E0C (U+1E0C): L<<217.0,659.0>--<98.0,658.0>>

	* uni1E0D (U+1E0D): L<<533.0,700.0>--<532.0,0.0>>

	* uni1E21 (U+1E21): L<<532.0,500.0>--<533.0,-1.0>>

	* uni1E5A (U+1E5A): L<<233.0,390.0>--<99.0,389.0>>

	* uni1E78 (U+1E78): L<<561.0,700.0>--<562.0,212.0>>

	* uni1E78 (U+1E78): L<<60.0,212.0>--<61.0,700.0>>

	* uni1E7A (U+1E7A): L<<561.0,700.0>--<562.0,212.0>>

	* uni1E7A (U+1E7A): L<<60.0,212.0>--<61.0,700.0>>

	* uni1EE4 (U+1EE4): L<<561.0,700.0>--<562.0,212.0>> 

	* uni1EE4 (U+1EE4): L<<60.0,212.0>--<61.0,700.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 8 | 23 | 236 | 13 | 195 | 0 |
| 0% | 2% | 5% | 50% | 3% | 41% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
