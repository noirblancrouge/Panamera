## FontBakery report

fontbakery version: 0.9.0

<details><summary><b>[10] Panamera-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1120 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1277, but got 853 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 434, but got 267 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
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

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 600 among a set of 11 math glyphs.
The following math glyphs have a different width, though:

Width = 667:
logicalnot

Width = 820:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** Lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<113.0,146.0>--<118.0,95.0>> -> L<<118.0,95.0>--<118.0,0.0>>

	* b (U+0062): L<<118.0,700.0>--<118.0,421.0>> -> L<<118.0,421.0>--<111.0,348.0>>

	* d (U+0064): L<<479.0,0.0>--<479.0,95.0>> -> L<<479.0,95.0>--<484.0,146.0>>

	* d (U+0064): L<<486.0,348.0>--<479.0,421.0>> -> L<<479.0,421.0>--<479.0,700.0>>

	* dcaron (U+010F): L<<479.0,0.0>--<479.0,95.0>> -> L<<479.0,95.0>--<484.0,146.0>>

	* dcaron (U+010F): L<<486.0,348.0>--<479.0,421.0>> -> L<<479.0,421.0>--<479.0,700.0>>

	* dcroat (U+0111): L<<479.0,0.0>--<479.0,95.0>> -> L<<479.0,95.0>--<484.0,146.0>>

	* dcroat (U+0111): L<<486.0,348.0>--<479.0,421.0>> -> L<<479.0,421.0>--<479.0,583.0>>

	* dmacronbelow (U+1E0F): L<<479.0,0.0>--<479.0,95.0>> -> L<<479.0,95.0>--<484.0,146.0>>

	* dmacronbelow (U+1E0F): L<<486.0,348.0>--<479.0,421.0>> -> L<<479.0,421.0>--<479.0,700.0>>

	* exclam (U+0021): L<<128.0,215.0>--<109.0,600.0>> -> L<<109.0,600.0>--<109.0,731.0>>

	* exclam (U+0021): L<<201.0,731.0>--<201.0,600.0>> -> L<<201.0,600.0>--<182.0,215.0>>

	* exclamdown (U+00A1): L<<109.0,-191.0>--<109.0,-60.0>> -> L<<109.0,-60.0>--<128.0,325.0>>

	* exclamdown (U+00A1): L<<182.0,325.0>--<201.0,-60.0>> -> L<<201.0,-60.0>--<201.0,-191.0>>

	* g (U+0067): L<<484.0,354.0>--<479.0,405.0>> -> L<<479.0,405.0>--<479.0,500.0>>

	* gbreve (U+011F): L<<484.0,354.0>--<479.0,405.0>> -> L<<479.0,405.0>--<479.0,500.0>>

	* gcaron (U+01E7): L<<484.0,354.0>--<479.0,405.0>> -> L<<479.0,405.0>--<479.0,500.0>>

	* gcircumflex (U+011D): L<<484.0,354.0>--<479.0,405.0>> -> L<<479.0,405.0>--<479.0,500.0>>

	* gdotaccent (U+0121): L<<484.0,354.0>--<479.0,405.0>> -> L<<479.0,405.0>--<479.0,500.0>>

	* p (U+0070): L<<111.0,152.0>--<118.0,79.0>> -> L<<118.0,79.0>--<118.0,-200.0>>

	* p (U+0070): L<<118.0,500.0>--<118.0,405.0>> -> L<<118.0,405.0>--<113.0,354.0>>

	* q (U+0071): L<<479.0,-200.0>--<479.0,79.0>> -> L<<479.0,79.0>--<486.0,152.0>>

	* q (U+0071): L<<484.0,354.0>--<479.0,405.0>> -> L<<479.0,405.0>--<479.0,500.0>>

	* thorn (U+00FE): L<<100.0,138.0>--<105.0,71.0>> -> L<<105.0,71.0>--<105.0,-226.0>>

	* thorn (U+00FE): L<<105.0,796.0>--<105.0,412.0>> -> L<<105.0,412.0>--<100.0,351.0>>

	* uni0123 (U+0123): L<<484.0,354.0>--<479.0,405.0>> -> L<<479.0,405.0>--<479.0,500.0>>

	* uni1E0D (U+1E0D): L<<479.0,0.0>--<479.0,95.0>> -> L<<479.0,95.0>--<484.0,146.0>>

	* uni1E0D (U+1E0D): L<<486.0,348.0>--<479.0,421.0>> -> L<<479.0,421.0>--<479.0,700.0>>

	* uni1E21 (U+1E21): L<<484.0,354.0>--<479.0,405.0>> -> L<<479.0,405.0>--<479.0,500.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* G (U+0047): L<<646.0,0.0>--<646.0,227.0>>/B<<646.0,227.0>-<639.0,159.0>-<607.5,107.0>> = 5.8773926066431

	* Gbreve (U+011E): L<<646.0,0.0>--<646.0,227.0>>/B<<646.0,227.0>-<639.0,159.0>-<607.5,107.0>> = 5.8773926066431

	* Gcaron (U+01E6): L<<646.0,0.0>--<646.0,227.0>>/B<<646.0,227.0>-<639.0,159.0>-<607.5,107.0>> = 5.8773926066431

	* Gcircumflex (U+011C): L<<646.0,0.0>--<646.0,227.0>>/B<<646.0,227.0>-<639.0,159.0>-<607.5,107.0>> = 5.8773926066431

	* Gdotaccent (U+0120): L<<646.0,0.0>--<646.0,227.0>>/B<<646.0,227.0>-<639.0,159.0>-<607.5,107.0>> = 5.8773926066431

	* b (U+0062): B<<180.5,34.5>-<132.0,80.0>-<113.0,146.0>>/L<<113.0,146.0>--<118.0,95.0>> = 10.460647970640071

	* b (U+0062): L<<118.0,421.0>--<111.0,348.0>>/B<<111.0,348.0>-<123.0,394.0>-<149.5,431.5>> = 9.143505259802732

	* d (U+0064): B<<447.0,431.5>-<473.0,394.0>-<486.0,348.0>>/L<<486.0,348.0>--<479.0,421.0>> = 10.30338458068646

	* d (U+0064): L<<479.0,95.0>--<484.0,146.0>>/B<<484.0,146.0>-<465.0,80.0>-<416.5,34.5>> = 10.460647970640071

	* dcaron (U+010F): B<<447.0,431.5>-<473.0,394.0>-<486.0,348.0>>/L<<486.0,348.0>--<479.0,421.0>> = 10.30338458068646

	* dcaron (U+010F): L<<479.0,95.0>--<484.0,146.0>>/B<<484.0,146.0>-<465.0,80.0>-<416.5,34.5>> = 10.460647970640071

	* dcroat (U+0111): B<<447.0,431.5>-<473.0,394.0>-<486.0,348.0>>/L<<486.0,348.0>--<479.0,421.0>> = 10.30338458068646

	* dcroat (U+0111): L<<479.0,95.0>--<484.0,146.0>>/B<<484.0,146.0>-<465.0,80.0>-<416.5,34.5>> = 10.460647970640071

	* dmacronbelow (U+1E0F): B<<447.0,431.5>-<473.0,394.0>-<486.0,348.0>>/L<<486.0,348.0>--<479.0,421.0>> = 10.30338458068646

	* dmacronbelow (U+1E0F): L<<479.0,95.0>--<484.0,146.0>>/B<<484.0,146.0>-<465.0,80.0>-<416.5,34.5>> = 10.460647970640071

	* f (U+0066): L<<9.0,501.0>--<155.0,501.0>>/B<<155.0,501.0>-<107.0,510.0>-<81.5,542.0>> = 10.61965527615514

	* g (U+0067): B<<416.5,465.5>-<465.0,420.0>-<484.0,354.0>>/L<<484.0,354.0>--<479.0,405.0>> = 10.460647970640071

	* g (U+0067): L<<479.0,98.0>--<484.0,145.0>>/B<<484.0,145.0>-<464.0,79.0>-<414.5,33.0>> = 10.785942360530578

	* gbreve (U+011F): B<<416.5,465.5>-<465.0,420.0>-<484.0,354.0>>/L<<484.0,354.0>--<479.0,405.0>> = 10.460647970640071

	* gbreve (U+011F): L<<479.0,98.0>--<484.0,145.0>>/B<<484.0,145.0>-<464.0,79.0>-<414.5,33.0>> = 10.785942360530578

	* gcaron (U+01E7): B<<416.5,465.5>-<465.0,420.0>-<484.0,354.0>>/L<<484.0,354.0>--<479.0,405.0>> = 10.460647970640071

	* gcaron (U+01E7): L<<479.0,98.0>--<484.0,145.0>>/B<<484.0,145.0>-<464.0,79.0>-<414.5,33.0>> = 10.785942360530578

	* gcircumflex (U+011D): B<<416.5,465.5>-<465.0,420.0>-<484.0,354.0>>/L<<484.0,354.0>--<479.0,405.0>> = 10.460647970640071

	* gcircumflex (U+011D): L<<479.0,98.0>--<484.0,145.0>>/B<<484.0,145.0>-<464.0,79.0>-<414.5,33.0>> = 10.785942360530578

	* gdotaccent (U+0121): B<<416.5,465.5>-<465.0,420.0>-<484.0,354.0>>/L<<484.0,354.0>--<479.0,405.0>> = 10.460647970640071

	* gdotaccent (U+0121): L<<479.0,98.0>--<484.0,145.0>>/B<<484.0,145.0>-<464.0,79.0>-<414.5,33.0>> = 10.785942360530578

	* p (U+0070): B<<149.5,68.5>-<123.0,106.0>-<111.0,152.0>>/L<<111.0,152.0>--<118.0,79.0>> = 9.143505259802732

	* p (U+0070): L<<118.0,405.0>--<113.0,354.0>>/B<<113.0,354.0>-<132.0,420.0>-<180.5,465.5>> = 10.460647970640071

	* q (U+0071): B<<416.5,465.5>-<465.0,420.0>-<484.0,354.0>>/L<<484.0,354.0>--<479.0,405.0>> = 10.460647970640071

	* q (U+0071): L<<479.0,79.0>--<486.0,152.0>>/B<<486.0,152.0>-<473.0,106.0>-<447.0,68.5>> = 10.30338458068646

	* r (U+0072): L<<120.0,500.0>--<120.0,357.0>>/B<<120.0,357.0>-<131.0,404.0>-<160.0,438.0>> = 13.172553423326871

	* racute (U+0155): L<<120.0,500.0>--<120.0,357.0>>/B<<120.0,357.0>-<131.0,404.0>-<160.0,438.0>> = 13.172553423326871

	* rcaron (U+0159): L<<120.0,500.0>--<120.0,357.0>>/B<<120.0,357.0>-<131.0,404.0>-<160.0,438.0>> = 13.172553423326871

	* rmacronbelow (U+1E5F): L<<120.0,500.0>--<120.0,357.0>>/B<<120.0,357.0>-<131.0,404.0>-<160.0,438.0>> = 13.172553423326871

	* thorn (U+00FE): B<<137.0,63.0>-<112.0,98.0>-<100.0,138.0>>/L<<100.0,138.0>--<105.0,71.0>> = 12.431350933702774

	* thorn (U+00FE): L<<105.0,412.0>--<100.0,351.0>>/B<<100.0,351.0>-<112.0,391.0>-<137.0,426.5>> = 12.013344394490904

	* uni0122 (U+0122): L<<646.0,0.0>--<646.0,227.0>>/B<<646.0,227.0>-<639.0,159.0>-<607.5,107.0>> = 5.8773926066431

	* uni0123 (U+0123): B<<416.5,465.5>-<465.0,420.0>-<484.0,354.0>>/L<<484.0,354.0>--<479.0,405.0>> = 10.460647970640071

	* uni0123 (U+0123): L<<479.0,98.0>--<484.0,145.0>>/B<<484.0,145.0>-<464.0,79.0>-<414.5,33.0>> = 10.785942360530578

	* uni0157 (U+0157): L<<120.0,500.0>--<120.0,357.0>>/B<<120.0,357.0>-<131.0,404.0>-<160.0,438.0>> = 13.172553423326871

	* uni1E0D (U+1E0D): B<<447.0,431.5>-<473.0,394.0>-<486.0,348.0>>/L<<486.0,348.0>--<479.0,421.0>> = 10.30338458068646

	* uni1E0D (U+1E0D): L<<479.0,95.0>--<484.0,146.0>>/B<<484.0,146.0>-<465.0,80.0>-<416.5,34.5>> = 10.460647970640071

	* uni1E20 (U+1E20): L<<646.0,0.0>--<646.0,227.0>>/B<<646.0,227.0>-<639.0,159.0>-<607.5,107.0>> = 5.8773926066431

	* uni1E21 (U+1E21): B<<416.5,465.5>-<465.0,420.0>-<484.0,354.0>>/L<<484.0,354.0>--<479.0,405.0>> = 10.460647970640071

	* uni1E21 (U+1E21): L<<479.0,98.0>--<484.0,145.0>>/B<<484.0,145.0>-<464.0,79.0>-<414.5,33.0>> = 10.785942360530578

	* uni1E5B (U+1E5B): L<<120.0,500.0>--<120.0,357.0>>/B<<120.0,357.0>-<131.0,404.0>-<160.0,438.0>> = 13.172553423326871 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* D (U+0044): L<<125.0,640.0>--<124.0,60.0>>

	* Dcaron (U+010E): L<<125.0,640.0>--<124.0,60.0>>

	* Dmacronbelow (U+1E0E): L<<125.0,640.0>--<124.0,60.0>>

	* IJ (U+0132): L<<729.0,700.0>--<730.0,211.0>>

	* J (U+004A): L<<499.0,700.0>--<500.0,211.0>>

	* Jcircumflex (U+0134): L<<499.0,700.0>--<500.0,211.0>>

	* R (U+0052): L<<247.0,372.0>--<125.0,371.0>>

	* Racute (U+0154): L<<247.0,372.0>--<125.0,371.0>>

	* Rcaron (U+0158): L<<247.0,372.0>--<125.0,371.0>>

	* Rmacronbelow (U+1E5E): L<<247.0,372.0>--<125.0,371.0>>

	* U (U+0055): L<<53.0,216.0>--<54.0,700.0>>

	* U (U+0055): L<<568.0,700.0>--<569.0,216.0>>

	* Uacute (U+00DA): L<<53.0,216.0>--<54.0,700.0>>

	* Uacute (U+00DA): L<<568.0,700.0>--<569.0,216.0>>

	* Ubreve (U+016C): L<<53.0,216.0>--<54.0,700.0>>

	* Ubreve (U+016C): L<<568.0,700.0>--<569.0,216.0>>

	* Ucircumflex (U+00DB): L<<53.0,216.0>--<54.0,700.0>>

	* Ucircumflex (U+00DB): L<<568.0,700.0>--<569.0,216.0>>

	* Udieresis (U+00DC): L<<53.0,216.0>--<54.0,700.0>>

	* Udieresis (U+00DC): L<<568.0,700.0>--<569.0,216.0>>

	* Ugrave (U+00D9): L<<53.0,216.0>--<54.0,700.0>>

	* Ugrave (U+00D9): L<<568.0,700.0>--<569.0,216.0>>

	* Uhungarumlaut (U+0170): L<<53.0,216.0>--<54.0,700.0>>

	* Uhungarumlaut (U+0170): L<<568.0,700.0>--<569.0,216.0>>

	* Umacron (U+016A): L<<53.0,216.0>--<54.0,700.0>>

	* Umacron (U+016A): L<<568.0,700.0>--<569.0,216.0>>

	* Uogonek (U+0172): L<<53.0,216.0>--<54.0,700.0>>

	* Uogonek (U+0172): L<<568.0,700.0>--<569.0,216.0>>

	* Uring (U+016E): L<<53.0,216.0>--<54.0,700.0>>

	* Uring (U+016E): L<<568.0,700.0>--<569.0,216.0>>

	* Utilde (U+0168): L<<53.0,216.0>--<54.0,700.0>>

	* Utilde (U+0168): L<<568.0,700.0>--<569.0,216.0>>

	* b (U+0062): L<<47.0,0.0>--<46.0,700.0>>

	* d (U+0064): L<<551.0,700.0>--<550.0,0.0>>

	* dcaron (U+010F): L<<551.0,700.0>--<550.0,0.0>>

	* dmacronbelow (U+1E0F): L<<551.0,700.0>--<550.0,0.0>>

	* four (U+0034): L<<368.0,228.0>--<33.0,229.0>>

	* g (U+0067): L<<550.0,500.0>--<551.0,1.0>>

	* gbreve (U+011F): L<<550.0,500.0>--<551.0,1.0>>

	* gcaron (U+01E7): L<<550.0,500.0>--<551.0,1.0>>

	* gcircumflex (U+011D): L<<550.0,500.0>--<551.0,1.0>>

	* gdotaccent (U+0121): L<<550.0,500.0>--<551.0,1.0>>

	* onequarter (U+00BC): L<<610.0,138.0>--<407.0,139.0>>

	* p (U+0070): L<<46.0,-200.0>--<47.0,500.0>>

	* q (U+0071): L<<550.0,500.0>--<551.0,-200.0>>

	* thorn (U+00FE): L<<33.0,-226.0>--<34.0,796.0>>

	* threequarters (U+00BE): L<<610.0,138.0>--<407.0,139.0>>

	* uni0123 (U+0123): L<<550.0,500.0>--<551.0,1.0>>

	* uni0156 (U+0156): L<<247.0,372.0>--<125.0,371.0>>

	* uni018F (U+018F): L<<42.0,360.0>--<644.0,361.0>>

	* uni1E0C (U+1E0C): L<<125.0,640.0>--<124.0,60.0>>

	* uni1E0D (U+1E0D): L<<551.0,700.0>--<550.0,0.0>>

	* uni1E21 (U+1E21): L<<550.0,500.0>--<551.0,1.0>>

	* uni1E5A (U+1E5A): L<<247.0,372.0>--<125.0,371.0>>

	* uni1E78 (U+1E78): L<<53.0,216.0>--<54.0,700.0>>

	* uni1E78 (U+1E78): L<<568.0,700.0>--<569.0,216.0>>

	* uni1E7A (U+1E7A): L<<53.0,216.0>--<54.0,700.0>>

	* uni1E7A (U+1E7A): L<<568.0,700.0>--<569.0,216.0>>

	* uni1EE4 (U+1EE4): L<<53.0,216.0>--<54.0,700.0>>

	* uni1EE4 (U+1EE4): L<<568.0,700.0>--<569.0,216.0>>

	* uni2074 (U+2074): L<<223.0,533.0>--<20.0,534.0>>

	* uni2084 (U+2084): L<<223.0,138.0>--<20.0,139.0>>

	* yen (U+00A5): L<<107.0,341.0>--<250.0,342.0>>

	* yen (U+00A5): L<<354.0,342.0>--<493.0,341.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] Panamera-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1120 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1277, but got 853 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 434, but got 267 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
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

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 600 among a set of 11 math glyphs.
The following math glyphs have a different width, though:

Width = 667:
logicalnot

Width = 820:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** Lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
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

	* plusminus (U+00B1): X=36.0,Y=-1.0 (should be at baseline 0?)

	* plusminus (U+00B1): X=563.0,Y=-1.0 (should be at baseline 0?)

	* uni00B2 (U+00B2): X=119.0,Y=698.0 (should be at cap-height 700?)

	* Agrave (U+00C0): X=218.0,Y=855.0 (should be at ascender 853?)

	* Aacute (U+00C1): X=630.0,Y=855.0 (should be at ascender 853?)

	* Atilde (U+00C3): X=358.5,Y=852.0 (should be at ascender 853?)

	* Egrave (U+00C8): X=164.0,Y=855.0 (should be at ascender 853?)

	* Eacute (U+00C9): X=576.0,Y=855.0 (should be at ascender 853?)

	* Igrave (U+00CC): X=-42.0,Y=855.0 (should be at ascender 853?)

	* Ntilde (U+00D1): X=291.5,Y=852.0 (should be at ascender 853?)

	* Ograve (U+00D2): X=225.0,Y=855.0 (should be at ascender 853?)

	* Oacute (U+00D3): X=637.0,Y=855.0 (should be at ascender 853?)

	* Otilde (U+00D5): X=365.5,Y=852.0 (should be at ascender 853?)

	* Ugrave (U+00D9): X=122.0,Y=855.0 (should be at ascender 853?)

	* Uacute (U+00DA): X=534.0,Y=855.0 (should be at ascender 853?)

	* Yacute (U+00DD): X=575.0,Y=855.0 (should be at ascender 853?)

	* eth (U+00F0): X=345.0,Y=698.0 (should be at cap-height 700?)

	* divide (U+00F7): X=207.0,Y=-1.0 (should be at baseline 0?)

	* divide (U+00F7): X=387.0,Y=-1.0 (should be at baseline 0?)

	* thorn (U+00FE): X=229.5,Y=-2.0 (should be at baseline 0?)

	* Cacute (U+0106): X=637.0,Y=855.0 (should be at ascender 853?)

	* Itilde (U+0128): X=98.5,Y=852.0 (should be at ascender 853?)

	* Lacute (U+0139): X=559.0,Y=855.0 (should be at ascender 853?)

	* lacute (U+013A): X=379.0,Y=855.0 (should be at ascender 853?)

	* Lcaron (U+013D): X=430.0,Y=701.0 (should be at cap-height 700?)

	* Nacute (U+0143): X=563.0,Y=855.0 (should be at ascender 853?)

	* Racute (U+0154): X=531.0,Y=855.0 (should be at ascender 853?)

	* Sacute (U+015A): X=545.0,Y=855.0 (should be at ascender 853?)

	* Utilde (U+0168): X=262.5,Y=852.0 (should be at ascender 853?)

	* Zacute (U+0179): X=518.0,Y=855.0 (should be at ascender 853?)

	* AEacute (U+01FC): X=897.0,Y=855.0 (should be at ascender 853?)

	* Oslashacute (U+01FE): X=637.0,Y=855.0 (should be at ascender 853?)

	* uni1E08 (U+1E08): X=637.0,Y=855.0 (should be at ascender 853?)

	* uni1E42 (U+1E42): X=243.0,Y=701.0 (should be at cap-height 700?)

	* uni1E42 (U+1E42): X=691.0,Y=701.0 (should be at cap-height 700?)

	* uni1E4C (U+1E4C): X=365.5,Y=852.0 (should be at ascender 853?)

	* uni1E4E (U+1E4E): X=365.5,Y=852.0 (should be at ascender 853?)

	* uni1E64 (U+1E64): X=660.0,Y=855.0 (should be at ascender 853?)

	* uni1E78 (U+1E78): X=262.5,Y=852.0 (should be at ascender 853?)

	* Wgrave (U+1E80): X=255.0,Y=855.0 (should be at ascender 853?)

	* Wacute (U+1E82): X=667.0,Y=855.0 (should be at ascender 853?)

	* uni1EBC (U+1EBC): X=304.5,Y=852.0 (should be at ascender 853?)

	* Ygrave (U+1EF2): X=163.0,Y=855.0 (should be at ascender 853?)

	* uni1EF8 (U+1EF8): X=303.5,Y=852.0 (should be at ascender 853?)

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

	* summation (U+2211): X=678.0,Y=699.0 (should be at cap-height 700?)

	* uni25CF (U+25CF): X=210.5,Y=-0.5 (should be at baseline 0?) [code: found-misalignments]
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

	* D (U+0044): L<<204.0,585.0>--<203.0,115.0>>

	* Dcaron (U+010E): L<<204.0,585.0>--<203.0,115.0>>

	* Dcroat (U+0110): L<<340.0,250.0>--<339.0,115.0>>

	* Dmacronbelow (U+1E0E): L<<204.0,585.0>--<203.0,115.0>>

	* Eth (U+00D0): L<<340.0,250.0>--<339.0,115.0>>

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

	* uni1E0C (U+1E0C): L<<204.0,585.0>--<203.0,115.0>>

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
</div></details><br></div></details><details><summary><b>[10] Panamera-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1120 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1277, but got 853 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 434, but got 267 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
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

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 600 among a set of 11 math glyphs.
The following math glyphs have a different width, though:

Width = 667:
logicalnot

Width = 820:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** Lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* exclam (U+0021): L<<142.0,214.0>--<123.0,608.0>> -> L<<123.0,608.0>--<123.0,731.0>>

	* exclam (U+0021): L<<187.0,731.0>--<187.0,608.0>> -> L<<187.0,608.0>--<168.0,214.0>>

	* exclamdown (U+00A1): L<<123.0,-191.0>--<123.0,-68.0>> -> L<<123.0,-68.0>--<142.0,326.0>>

	* exclamdown (U+00A1): L<<168.0,326.0>--<187.0,-68.0>> -> L<<187.0,-68.0>--<187.0,-191.0>>

	* thorn (U+00FE): L<<74.0,177.0>--<81.0,96.0>> -> L<<81.0,96.0>--<81.0,-238.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* G (U+0047): L<<661.0,0.0>--<661.0,248.0>>/B<<661.0,248.0>-<646.0,135.0>-<577.0,65.0>> = 7.5614284276669235

	* Gbreve (U+011E): L<<661.0,0.0>--<661.0,248.0>>/B<<661.0,248.0>-<646.0,135.0>-<577.0,65.0>> = 7.5614284276669235

	* Gcaron (U+01E6): L<<661.0,0.0>--<661.0,248.0>>/B<<661.0,248.0>-<646.0,135.0>-<577.0,65.0>> = 7.5614284276669235

	* Gcircumflex (U+011C): L<<661.0,0.0>--<661.0,248.0>>/B<<661.0,248.0>-<646.0,135.0>-<577.0,65.0>> = 7.5614284276669235

	* Gdotaccent (U+0120): L<<661.0,0.0>--<661.0,248.0>>/B<<661.0,248.0>-<646.0,135.0>-<577.0,65.0>> = 7.5614284276669235

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

	* thorn (U+00FE): B<<112.5,83.0>-<85.0,128.0>-<74.0,177.0>>/L<<74.0,177.0>--<81.0,96.0>> = 7.713340958431738

	* thorn (U+00FE): L<<81.0,376.0>--<74.0,307.0>>/B<<74.0,307.0>-<85.0,357.0>-<112.0,402.5>> = 6.614622032368609

	* uni0122 (U+0122): L<<661.0,0.0>--<661.0,248.0>>/B<<661.0,248.0>-<646.0,135.0>-<577.0,65.0>> = 7.5614284276669235

	* uni0123 (U+0123): B<<454.5,420.0>-<482.0,379.0>-<494.0,332.0>>/L<<494.0,332.0>--<488.0,382.0>> = 7.479946565572559

	* uni0123 (U+0123): L<<488.0,116.0>--<494.0,167.0>>/B<<494.0,167.0>-<482.0,120.0>-<454.0,79.0>> = 7.6128831704466275

	* uni0157 (U+0157): L<<94.0,500.0>--<94.0,331.0>>/B<<94.0,331.0>-<105.0,387.0>-<135.5,426.0>> = 11.113040535948294

	* uni03A9 (U+03A9): B<<627.0,88.5>-<594.0,55.0>-<550.0,44.0>>/L<<550.0,44.0>--<742.0,44.0>> = 14.036243467926484

	* uni1E0D (U+1E0D): B<<456.5,417.5>-<484.0,375.0>-<496.0,327.0>>/L<<496.0,327.0>--<488.0,398.0>> = 7.607495719096593

	* uni1E0D (U+1E0D): L<<488.0,118.0>--<494.0,168.0>>/B<<494.0,168.0>-<482.0,121.0>-<454.5,80.0>> = 7.479946565572559

	* uni1E20 (U+1E20): L<<661.0,0.0>--<661.0,248.0>>/B<<661.0,248.0>-<646.0,135.0>-<577.0,65.0>> = 7.5614284276669235

	* uni1E21 (U+1E21): B<<454.5,420.0>-<482.0,379.0>-<494.0,332.0>>/L<<494.0,332.0>--<488.0,382.0>> = 7.479946565572559

	* uni1E21 (U+1E21): L<<488.0,116.0>--<494.0,167.0>>/B<<494.0,167.0>-<482.0,120.0>-<454.0,79.0>> = 7.6128831704466275

	* uni1E5B (U+1E5B): L<<94.0,500.0>--<94.0,331.0>>/B<<94.0,331.0>-<105.0,387.0>-<135.5,426.0>> = 11.113040535948294

	* uni2126 (U+2126): B<<627.0,88.5>-<594.0,55.0>-<550.0,44.0>>/L<<550.0,44.0>--<742.0,44.0>> = 14.036243467926484 [code: found-jaggy-segments]
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

	* uni1EE4 (U+1EE4): L<<60.0,212.0>--<61.0,700.0>>

	* yen (U+00A5): L<<316.0,332.0>--<473.0,331.0>>

	* yen (U+00A5): L<<97.0,331.0>--<256.0,332.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] Panamera-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** Best SubFamily name is 'Thin'. Expected OS/2 usWeightClass is 100, got 220. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1120 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1277, but got 853 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 434, but got 267 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
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

	- Glyph name: ordmasculine	Contours detected: 1	Expected: 2or3

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

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: ordmasculine	Contours detected: 1	Expected: 2or3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 600 among a set of 11 math glyphs.
The following math glyphs have a different width, though:

Width = 667:
logicalnot

Width = 820:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** Lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* exclam (U+0021): L<<151.0,213.0>--<132.0,613.0>> -> L<<132.0,613.0>--<132.0,731.0>>

	* exclam (U+0021): L<<177.0,731.0>--<178.0,613.0>> -> L<<178.0,613.0>--<159.0,213.0>>

	* exclamdown (U+00A1): L<<132.0,-191.0>--<132.0,-73.0>> -> L<<132.0,-73.0>--<151.0,327.0>>

	* exclamdown (U+00A1): L<<159.0,327.0>--<178.0,-73.0>> -> L<<178.0,-73.0>--<177.0,-191.0>>

	* thorn (U+00FE): L<<58.0,202.0>--<65.0,112.0>> -> L<<65.0,112.0>--<65.0,-246.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* B (U+0042): B<<379.0,456.0>-<344.0,422.0>-<288.0,411.0>>/B<<288.0,411.0>-<412.0,410.0>-<478.0,359.0>> = 11.575093257379093

	* G (U+0047): L<<670.0,0.0>--<670.0,261.0>>/B<<670.0,261.0>-<653.0,141.0>-<581.0,68.0>> = 8.063246165697231

	* Gbreve (U+011E): L<<670.0,0.0>--<670.0,261.0>>/B<<670.0,261.0>-<653.0,141.0>-<581.0,68.0>> = 8.063246165697231

	* Gcaron (U+01E6): L<<670.0,0.0>--<670.0,261.0>>/B<<670.0,261.0>-<653.0,141.0>-<581.0,68.0>> = 8.063246165697231

	* Gcircumflex (U+011C): L<<670.0,0.0>--<670.0,261.0>>/B<<670.0,261.0>-<653.0,141.0>-<581.0,68.0>> = 8.063246165697231

	* Gdotaccent (U+0120): L<<670.0,0.0>--<670.0,261.0>>/B<<670.0,261.0>-<653.0,141.0>-<581.0,68.0>> = 8.063246165697231

	* at (U+0040): B<<665.5,67.0>-<650.0,103.0>-<652.0,166.0>>/B<<652.0,166.0>-<644.0,97.0>-<616.0,57.0>> = 4.795157517862949

	* b (U+0062): B<<113.0,90.5>-<85.0,135.0>-<74.0,183.0>>/L<<74.0,183.0>--<80.0,133.0>> = 6.064635258634921

	* b (U+0062): L<<80.0,383.0>--<72.0,311.0>>/B<<72.0,311.0>-<83.0,360.0>-<111.0,406.5>> = 6.312364754648055

	* d (U+0064): B<<463.0,406.5>-<491.0,360.0>-<502.0,312.0>>/L<<502.0,312.0>--<494.0,383.0>> = 6.4786609224359895

	* d (U+0064): L<<494.0,133.0>--<500.0,183.0>>/B<<500.0,183.0>-<489.0,135.0>-<461.0,90.5>> = 6.064635258634921

	* dcaron (U+010F): B<<463.0,406.5>-<491.0,360.0>-<502.0,312.0>>/L<<502.0,312.0>--<494.0,383.0>> = 6.4786609224359895

	* dcaron (U+010F): L<<494.0,133.0>--<500.0,183.0>>/B<<500.0,183.0>-<489.0,135.0>-<461.0,90.5>> = 6.064635258634921

	* dcroat (U+0111): B<<463.0,406.5>-<491.0,360.0>-<502.0,312.0>>/L<<502.0,312.0>--<494.0,383.0>> = 6.4786609224359895

	* dcroat (U+0111): L<<494.0,133.0>--<500.0,183.0>>/B<<500.0,183.0>-<489.0,135.0>-<461.0,90.5>> = 6.064635258634921

	* dmacronbelow (U+1E0F): B<<463.0,406.5>-<491.0,360.0>-<502.0,312.0>>/L<<502.0,312.0>--<494.0,383.0>> = 6.4786609224359895

	* dmacronbelow (U+1E0F): L<<494.0,133.0>--<500.0,183.0>>/B<<500.0,183.0>-<489.0,135.0>-<461.0,90.5>> = 6.064635258634921

	* f (U+0066): L<<9.0,501.0>--<189.0,501.0>>/B<<189.0,501.0>-<143.0,508.0>-<114.5,528.5>> = 8.652541791114704

	* g (U+0067): B<<461.0,409.5>-<489.0,365.0>-<500.0,317.0>>/L<<500.0,317.0>--<494.0,367.0>> = 6.064635258634921

	* g (U+0067): L<<494.0,128.0>--<501.0,182.0>>/B<<501.0,182.0>-<489.0,135.0>-<460.5,90.0>> = 6.936676826936219

	* gbreve (U+011F): B<<461.0,409.5>-<489.0,365.0>-<500.0,317.0>>/L<<500.0,317.0>--<494.0,367.0>> = 6.064635258634921

	* gbreve (U+011F): L<<494.0,128.0>--<501.0,182.0>>/B<<501.0,182.0>-<489.0,135.0>-<460.5,90.0>> = 6.936676826936219

	* gcaron (U+01E7): B<<461.0,409.5>-<489.0,365.0>-<500.0,317.0>>/L<<500.0,317.0>--<494.0,367.0>> = 6.064635258634921

	* gcaron (U+01E7): L<<494.0,128.0>--<501.0,182.0>>/B<<501.0,182.0>-<489.0,135.0>-<460.5,90.0>> = 6.936676826936219

	* gcircumflex (U+011D): B<<461.0,409.5>-<489.0,365.0>-<500.0,317.0>>/L<<500.0,317.0>--<494.0,367.0>> = 6.064635258634921

	* gcircumflex (U+011D): L<<494.0,128.0>--<501.0,182.0>>/B<<501.0,182.0>-<489.0,135.0>-<460.5,90.0>> = 6.936676826936219

	* gdotaccent (U+0121): B<<461.0,409.5>-<489.0,365.0>-<500.0,317.0>>/L<<500.0,317.0>--<494.0,367.0>> = 6.064635258634921

	* gdotaccent (U+0121): L<<494.0,128.0>--<501.0,182.0>>/B<<501.0,182.0>-<489.0,135.0>-<460.5,90.0>> = 6.936676826936219

	* p (U+0070): B<<111.0,93.5>-<83.0,140.0>-<72.0,189.0>>/L<<72.0,189.0>--<80.0,117.0>> = 6.312364754648055

	* p (U+0070): L<<80.0,367.0>--<74.0,317.0>>/B<<74.0,317.0>-<85.0,365.0>-<113.0,409.5>> = 6.064635258634921

	* partialdiff (U+2202): B<<455.0,419.5>-<495.0,382.0>-<517.0,319.0>>/B<<517.0,319.0>-<502.0,452.0>-<459.0,546.0>> = 12.814786721644987

	* q (U+0071): B<<461.0,409.5>-<489.0,365.0>-<500.0,317.0>>/L<<500.0,317.0>--<494.0,367.0>> = 6.064635258634921

	* q (U+0071): L<<494.0,117.0>--<502.0,188.0>>/B<<502.0,188.0>-<491.0,140.0>-<463.0,93.5>> = 6.4786609224359895

	* r (U+0072): L<<78.0,500.0>--<78.0,315.0>>/B<<78.0,315.0>-<88.0,376.0>-<119.5,418.5>> = 9.30994017498601

	* racute (U+0155): L<<78.0,500.0>--<78.0,315.0>>/B<<78.0,315.0>-<88.0,376.0>-<119.5,418.5>> = 9.30994017498601

	* rcaron (U+0159): L<<78.0,500.0>--<78.0,315.0>>/B<<78.0,315.0>-<88.0,376.0>-<119.5,418.5>> = 9.30994017498601

	* rmacronbelow (U+1E5F): L<<78.0,500.0>--<78.0,315.0>>/B<<78.0,315.0>-<88.0,376.0>-<119.5,418.5>> = 9.30994017498601

	* thorn (U+00FE): B<<97.0,95.0>-<68.0,146.0>-<58.0,202.0>>/L<<58.0,202.0>--<65.0,112.0>> = 5.677286805307305

	* thorn (U+00FE): L<<65.0,353.0>--<57.0,279.0>>/B<<57.0,279.0>-<67.0,336.0>-<96.0,387.5>> = 3.780451592921863

	* u (U+0075): L<<488.0,1.0>--<488.0,161.0>>/B<<488.0,161.0>-<475.0,106.0>-<438.5,68.5>> = 13.298570330494275

	* uacute (U+00FA): L<<488.0,1.0>--<488.0,161.0>>/B<<488.0,161.0>-<475.0,106.0>-<438.5,68.5>> = 13.298570330494275

	* ubreve (U+016D): L<<488.0,1.0>--<488.0,161.0>>/B<<488.0,161.0>-<475.0,106.0>-<438.5,68.5>> = 13.298570330494275

	* ucircumflex (U+00FB): L<<488.0,1.0>--<488.0,161.0>>/B<<488.0,161.0>-<475.0,106.0>-<438.5,68.5>> = 13.298570330494275

	* udieresis (U+00FC): L<<488.0,1.0>--<488.0,161.0>>/B<<488.0,161.0>-<475.0,106.0>-<438.5,68.5>> = 13.298570330494275

	* ugrave (U+00F9): L<<488.0,1.0>--<488.0,161.0>>/B<<488.0,161.0>-<475.0,106.0>-<438.5,68.5>> = 13.298570330494275

	* uhungarumlaut (U+0171): L<<488.0,1.0>--<488.0,161.0>>/B<<488.0,161.0>-<475.0,106.0>-<438.5,68.5>> = 13.298570330494275

	* umacron (U+016B): L<<488.0,1.0>--<488.0,161.0>>/B<<488.0,161.0>-<475.0,106.0>-<438.5,68.5>> = 13.298570330494275

	* uni0122 (U+0122): L<<670.0,0.0>--<670.0,261.0>>/B<<670.0,261.0>-<653.0,141.0>-<581.0,68.0>> = 8.063246165697231

	* uni0123 (U+0123): B<<461.0,409.5>-<489.0,365.0>-<500.0,317.0>>/L<<500.0,317.0>--<494.0,367.0>> = 6.064635258634921

	* uni0123 (U+0123): L<<494.0,128.0>--<501.0,182.0>>/B<<501.0,182.0>-<489.0,135.0>-<460.5,90.0>> = 6.936676826936219

	* uni0157 (U+0157): L<<78.0,500.0>--<78.0,315.0>>/B<<78.0,315.0>-<88.0,376.0>-<119.5,418.5>> = 9.30994017498601

	* uni03A9 (U+03A9): B<<619.0,76.5>-<584.0,42.0>-<538.0,33.0>>/L<<538.0,33.0>--<742.0,33.0>> = 11.070202577939344

	* uni03A9 (U+03A9): L<<15.0,33.0>--<225.0,33.0>>/B<<225.0,33.0>-<179.0,44.0>-<146.5,72.5>> = 13.448615051686527

	* uni1E0D (U+1E0D): B<<463.0,406.5>-<491.0,360.0>-<502.0,312.0>>/L<<502.0,312.0>--<494.0,383.0>> = 6.4786609224359895

	* uni1E0D (U+1E0D): L<<494.0,133.0>--<500.0,183.0>>/B<<500.0,183.0>-<489.0,135.0>-<461.0,90.5>> = 6.064635258634921

	* uni1E20 (U+1E20): L<<670.0,0.0>--<670.0,261.0>>/B<<670.0,261.0>-<653.0,141.0>-<581.0,68.0>> = 8.063246165697231

	* uni1E21 (U+1E21): B<<461.0,409.5>-<489.0,365.0>-<500.0,317.0>>/L<<500.0,317.0>--<494.0,367.0>> = 6.064635258634921

	* uni1E21 (U+1E21): L<<494.0,128.0>--<501.0,182.0>>/B<<501.0,182.0>-<489.0,135.0>-<460.5,90.0>> = 6.936676826936219

	* uni1E5B (U+1E5B): L<<78.0,500.0>--<78.0,315.0>>/B<<78.0,315.0>-<88.0,376.0>-<119.5,418.5>> = 9.30994017498601

	* uni1E79 (U+1E79): L<<488.0,1.0>--<488.0,161.0>>/B<<488.0,161.0>-<475.0,106.0>-<438.5,68.5>> = 13.298570330494275

	* uni1E7B (U+1E7B): L<<488.0,1.0>--<488.0,161.0>>/B<<488.0,161.0>-<475.0,106.0>-<438.5,68.5>> = 13.298570330494275

	* uni1EE5 (U+1EE5): L<<488.0,1.0>--<488.0,161.0>>/B<<488.0,161.0>-<475.0,106.0>-<438.5,68.5>> = 13.298570330494275

	* uni2106 (U+2106): L<<934.0,1.0>--<934.0,135.0>>/B<<934.0,135.0>-<923.0,88.0>-<892.5,57.0>> = 13.172553423326871

	* uni2126 (U+2126): B<<619.0,76.5>-<584.0,42.0>-<538.0,33.0>>/L<<538.0,33.0>--<742.0,33.0>> = 11.070202577939344

	* uni2126 (U+2126): L<<15.0,33.0>--<225.0,33.0>>/B<<225.0,33.0>-<179.0,44.0>-<146.5,72.5>> = 13.448615051686527

	* uogonek (U+0173): L<<488.0,1.0>--<488.0,161.0>>/B<<488.0,161.0>-<475.0,106.0>-<438.5,68.5>> = 13.298570330494275

	* uring (U+016F): L<<488.0,1.0>--<488.0,161.0>>/B<<488.0,161.0>-<475.0,106.0>-<438.5,68.5>> = 13.298570330494275

	* utilde (U+0169): L<<488.0,1.0>--<488.0,161.0>>/B<<488.0,161.0>-<475.0,106.0>-<438.5,68.5>> = 13.298570330494275 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* D (U+0044): L<<210.0,671.0>--<81.0,670.0>>

	* Dcaron (U+010E): L<<210.0,671.0>--<81.0,670.0>>

	* Dcroat (U+0110): L<<316.0,671.0>--<187.0,670.0>>

	* Dmacronbelow (U+1E0E): L<<210.0,671.0>--<81.0,670.0>>

	* Eth (U+00D0): L<<316.0,671.0>--<187.0,670.0>>

	* IJ (U+0132): L<<673.0,700.0>--<674.0,185.0>>

	* J (U+004A): L<<479.0,700.0>--<480.0,185.0>>

	* Jcircumflex (U+0134): L<<479.0,700.0>--<480.0,185.0>>

	* R (U+0052): L<<224.0,402.0>--<82.0,401.0>>

	* Racute (U+0154): L<<224.0,402.0>--<82.0,401.0>>

	* Rcaron (U+0158): L<<224.0,402.0>--<82.0,401.0>>

	* Rmacronbelow (U+1E5E): L<<224.0,402.0>--<82.0,401.0>>

	* U (U+0055): L<<557.0,700.0>--<558.0,209.0>>

	* U (U+0055): L<<64.0,209.0>--<65.0,700.0>>

	* Uacute (U+00DA): L<<557.0,700.0>--<558.0,209.0>>

	* Uacute (U+00DA): L<<64.0,209.0>--<65.0,700.0>>

	* Ubreve (U+016C): L<<557.0,700.0>--<558.0,209.0>>

	* Ubreve (U+016C): L<<64.0,209.0>--<65.0,700.0>>

	* Ucircumflex (U+00DB): L<<557.0,700.0>--<558.0,209.0>>

	* Ucircumflex (U+00DB): L<<64.0,209.0>--<65.0,700.0>>

	* Udieresis (U+00DC): L<<557.0,700.0>--<558.0,209.0>>

	* Udieresis (U+00DC): L<<64.0,209.0>--<65.0,700.0>>

	* Ugrave (U+00D9): L<<557.0,700.0>--<558.0,209.0>>

	* Ugrave (U+00D9): L<<64.0,209.0>--<65.0,700.0>>

	* Uhungarumlaut (U+0170): L<<557.0,700.0>--<558.0,209.0>>

	* Uhungarumlaut (U+0170): L<<64.0,209.0>--<65.0,700.0>>

	* Umacron (U+016A): L<<557.0,700.0>--<558.0,209.0>>

	* Umacron (U+016A): L<<64.0,209.0>--<65.0,700.0>>

	* Uogonek (U+0172): L<<557.0,700.0>--<558.0,209.0>>

	* Uogonek (U+0172): L<<64.0,209.0>--<65.0,700.0>>

	* Uring (U+016E): L<<557.0,700.0>--<558.0,209.0>>

	* Uring (U+016E): L<<64.0,209.0>--<65.0,700.0>>

	* Utilde (U+0168): L<<557.0,700.0>--<558.0,209.0>>

	* Utilde (U+0168): L<<64.0,209.0>--<65.0,700.0>>

	* b (U+0062): L<<53.0,0.0>--<52.0,700.0>>

	* d (U+0064): L<<522.0,700.0>--<521.0,0.0>>

	* dcaron (U+010F): L<<522.0,700.0>--<521.0,0.0>>

	* dcroat (U+0111): L<<522.0,608.0>--<521.0,0.0>>

	* dmacronbelow (U+1E0F): L<<522.0,700.0>--<521.0,0.0>>

	* exclam (U+0021): L<<177.0,731.0>--<178.0,613.0>>

	* exclamdown (U+00A1): L<<178.0,-73.0>--<177.0,-191.0>>

	* four (U+0034): L<<388.0,251.0>--<35.0,252.0>>

	* g (U+0067): L<<521.0,500.0>--<522.0,-2.0>>

	* gbreve (U+011F): L<<521.0,500.0>--<522.0,-2.0>>

	* gcaron (U+01E7): L<<521.0,500.0>--<522.0,-2.0>>

	* gcircumflex (U+011D): L<<521.0,500.0>--<522.0,-2.0>>

	* gdotaccent (U+0121): L<<521.0,500.0>--<522.0,-2.0>>

	* onequarter (U+00BC): L<<622.0,152.0>--<408.0,153.0>>

	* p (U+0070): L<<52.0,-200.0>--<53.0,500.0>>

	* q (U+0071): L<<521.0,500.0>--<522.0,-200.0>>

	* thorn (U+00FE): L<<38.0,-246.0>--<39.0,816.0>>

	* threequarters (U+00BE): L<<622.0,152.0>--<408.0,153.0>>

	* uni0123 (U+0123): L<<521.0,500.0>--<522.0,-2.0>>

	* uni0156 (U+0156): L<<224.0,402.0>--<82.0,401.0>>

	* uni018F (U+018F): L<<28.0,339.0>--<666.0,338.0>>

	* uni1E0C (U+1E0C): L<<210.0,671.0>--<81.0,670.0>>

	* uni1E0D (U+1E0D): L<<522.0,700.0>--<521.0,0.0>>

	* uni1E21 (U+1E21): L<<521.0,500.0>--<522.0,-2.0>>

	* uni1E5A (U+1E5A): L<<224.0,402.0>--<82.0,401.0>>

	* uni1E78 (U+1E78): L<<557.0,700.0>--<558.0,209.0>>

	* uni1E78 (U+1E78): L<<64.0,209.0>--<65.0,700.0>>

	* uni1E7A (U+1E7A): L<<557.0,700.0>--<558.0,209.0>>

	* uni1E7A (U+1E7A): L<<64.0,209.0>--<65.0,700.0>>

	* uni1EE4 (U+1EE4): L<<557.0,700.0>--<558.0,209.0>>

	* uni1EE4 (U+1EE4): L<<64.0,209.0>--<65.0,700.0>>

	* uni2074 (U+2074): L<<235.0,547.0>--<21.0,548.0>>

	* uni2084 (U+2084): L<<235.0,152.0>--<21.0,153.0>>

	* yen (U+00A5): L<<292.0,326.0>--<460.0,325.0>>

	* yen (U+00A5): L<<90.0,325.0>--<260.0,326.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] Panamera-Heavy.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** Best SubFamily name is 'Heavy'. Expected OS/2 usWeightClass is 400, got 800. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Panamera Heavy | Panamera Heavy |
| Subfamily Name | Regular | Regular |
| Full Name | Panamera Heavy | Panamera Heavy Regular |
| Poscript Name | Panamera-Heavy | PanameraHeavy-Regular |
| Typographic Family Name | Panamera | N/A |
| Typographic Subfamily Name | Heavy | N/A | [code: bad-names]
* ⚠ **WARN** Regular missing from full name [code: lacks-regular]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1120 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1277, but got 853 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 434, but got 267 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
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

	- Glyph name: ampersand	Contours detected: 5	Expected: 1, 2or3

	- Glyph name: question	Contours detected: 3	Expected: 2

	- Glyph name: at	Contours detected: 4	Expected: 2

	- Glyph name: s	Contours detected: 3	Expected: 1

	- Glyph name: questiondown	Contours detected: 3	Expected: 2

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: scedilla	Contours detected: 4	Expected: 1or2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni0219	Contours detected: 4	Expected: 2

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E61	Contours detected: 4	Expected: 2

	- Glyph name: uni1E63	Contours detected: 4	Expected: 2

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E69	Contours detected: 5	Expected: 3

	- Glyph name: lessequal	Contours detected: 1	Expected: 2

	- Glyph name: greaterequal	Contours detected: 1	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: ampersand	Contours detected: 5	Expected: 1, 2or3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: at	Contours detected: 4	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: greaterequal	Contours detected: 1	Expected: 2

	- Glyph name: lessequal	Contours detected: 1	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: question	Contours detected: 3	Expected: 2

	- Glyph name: questiondown	Contours detected: 3	Expected: 2

	- Glyph name: s	Contours detected: 3	Expected: 1

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: uni0219	Contours detected: 4	Expected: 2

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E61	Contours detected: 4	Expected: 2

	- Glyph name: uni1E63	Contours detected: 4	Expected: 2

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E69	Contours detected: 5	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 600 among a set of 11 math glyphs.
The following math glyphs have a different width, though:

Width = 667:
logicalnot

Width = 820:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** Lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* numbersign (U+0023): X=532.0,Y=-1.0 (should be at baseline 0?)

	* numbersign (U+0023): X=347.0,Y=-1.0 (should be at baseline 0?)

	* numbersign (U+0023): X=238.0,Y=-1.0 (should be at baseline 0?)

	* numbersign (U+0023): X=53.0,Y=-1.0 (should be at baseline 0?)

	* dollar (U+0024): X=389.0,Y=702.0 (should be at cap-height 700?)

	* ampersand (U+0026): X=632.5,Y=0.5 (should be at baseline 0?)

	* parenleft (U+0028): X=347.5,Y=701.5 (should be at cap-height 700?)

	* parenright (U+0029): X=25.5,Y=701.5 (should be at cap-height 700?)

	* asterisk (U+002A): X=212.0,Y=698.0 (should be at cap-height 700?)

	* asterisk (U+002A): X=365.0,Y=698.0 (should be at cap-height 700?)

	* comma (U+002C): X=262.0,Y=2.0 (should be at baseline 0?)

	* colon (U+003A): X=32.0,Y=-1.0 (should be at baseline 0?)

	* colon (U+003A): X=238.0,Y=-1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=128.0,Y=-2.0 (should be at baseline 0?)

	* semicolon (U+003B): X=128.0,Y=2.0 (should be at baseline 0?)

	* semicolon (U+003B): X=62.0,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=171.5,Y=701.0 (should be at cap-height 700?)

	* at (U+0040): X=333.5,Y=-0.5 (should be at baseline 0?)

	* at (U+0040): X=519.5,Y=-2.0 (should be at baseline 0?)

	* M (U+004D): X=275.0,Y=701.0 (should be at cap-height 700?)

	* M (U+004D): X=694.0,Y=701.0 (should be at cap-height 700?)

	* a (U+0061): X=300.0,Y=1.5 (should be at baseline 0?)

	* f (U+0066): X=7.0,Y=501.0 (should be at x-height 500?)

	* f (U+0066): X=73.0,Y=501.0 (should be at x-height 500?)

	* f (U+0066): X=285.0,Y=501.0 (should be at x-height 500?)

	* f (U+0066): X=416.0,Y=501.0 (should be at x-height 500?)

	* h (U+0068): X=275.5,Y=498.5 (should be at x-height 500?)

	* cent (U+00A2): X=303.0,Y=-1.0 (should be at baseline 0?)

	* cent (U+00A2): X=348.0,Y=-1.0 (should be at baseline 0?)

	* plusminus (U+00B1): X=29.0,Y=-2.0 (should be at baseline 0?)

	* plusminus (U+00B1): X=570.0,Y=-2.0 (should be at baseline 0?)

	* uni00B5 (U+00B5): X=361.0,Y=1.0 (should be at baseline 0?)

	* agrave (U+00E0): X=300.0,Y=1.5 (should be at baseline 0?)

	* aacute (U+00E1): X=300.0,Y=1.5 (should be at baseline 0?)

	* acircumflex (U+00E2): X=300.0,Y=1.5 (should be at baseline 0?)

	* atilde (U+00E3): X=300.0,Y=1.5 (should be at baseline 0?)

	* adieresis (U+00E4): X=300.0,Y=1.5 (should be at baseline 0?)

	* aring (U+00E5): X=300.0,Y=1.5 (should be at baseline 0?)

	* ae (U+00E6): X=300.0,Y=1.5 (should be at baseline 0?)

	* divide (U+00F7): X=193.0,Y=-1.0 (should be at baseline 0?)

	* divide (U+00F7): X=400.0,Y=-1.0 (should be at baseline 0?)

	* amacron (U+0101): X=300.0,Y=1.5 (should be at baseline 0?)

	* abreve (U+0103): X=300.0,Y=1.5 (should be at baseline 0?)

	* abreve (U+0103): X=302.0,Y=698.0 (should be at cap-height 700?)

	* aogonek (U+0105): X=300.0,Y=1.5 (should be at baseline 0?)

	* ebreve (U+0115): X=308.0,Y=698.0 (should be at cap-height 700?)

	* gbreve (U+011F): X=333.0,Y=698.0 (should be at cap-height 700?)

	* uni0122 (U+0122): X=390.0,Y=-265.0 (should be at descender -267?)

	* ibreve (U+012D): X=170.0,Y=698.0 (should be at cap-height 700?)

	* uni0136 (U+0136): X=334.0,Y=-265.0 (should be at descender -267?)

	* uni0137 (U+0137): X=286.0,Y=-265.0 (should be at descender -267?)

	* uni013B (U+013B): X=313.0,Y=-265.0 (should be at descender -267?)

	* uni013C (U+013C): X=137.0,Y=-265.0 (should be at descender -267?)

	* uni0145 (U+0145): X=317.0,Y=-265.0 (should be at descender -267?)

	* uni0146 (U+0146): X=270.0,Y=-265.0 (should be at descender -267?)

	* obreve (U+014F): X=306.0,Y=698.0 (should be at cap-height 700?)

	* uni0156 (U+0156): X=349.0,Y=-265.0 (should be at descender -267?)

	* uni0157 (U+0157): X=270.0,Y=-265.0 (should be at descender -267?)

	* ubreve (U+016D): X=293.0,Y=698.0 (should be at cap-height 700?)

	* aringacute (U+01FB): X=300.0,Y=1.5 (should be at baseline 0?)

	* aeacute (U+01FD): X=300.0,Y=1.5 (should be at baseline 0?)

	* uni0218 (U+0218): X=292.0,Y=-265.0 (should be at descender -267?)

	* uni0219 (U+0219): X=240.0,Y=-265.0 (should be at descender -267?)

	* uni021A (U+021A): X=333.0,Y=-265.0 (should be at descender -267?)

	* uni021B (U+021B): X=249.0,Y=-265.0 (should be at descender -267?)

	* breve (U+02D8): X=402.0,Y=698.0 (should be at cap-height 700?)

	* uni0306 (U+0306): X=402.0,Y=698.0 (should be at cap-height 700?)

	* uni0326 (U+0326): X=269.0,Y=-265.0 (should be at descender -267?)

	* uni0330 (U+0330): X=108.0,Y=-266.0 (should be at descender -267?)

	* uni0330 (U+0330): X=361.0,Y=-266.0 (should be at descender -267?)

	* uni0330 (U+0330): X=247.0,Y=-266.0 (should be at descender -267?)

	* uni03BC (U+03BC): X=361.0,Y=1.0 (should be at baseline 0?)

	* uni1E1D (U+1E1D): X=308.0,Y=698.0 (should be at cap-height 700?)

	* uni1E2D (U+1E2D): X=7.0,Y=-266.0 (should be at descender -267?)

	* uni1E2D (U+1E2D): X=260.0,Y=-266.0 (should be at descender -267?)

	* uni1E2D (U+1E2D): X=146.0,Y=-266.0 (should be at descender -267?)

	* uni1E42 (U+1E42): X=275.0,Y=701.0 (should be at cap-height 700?)

	* uni1E42 (U+1E42): X=694.0,Y=701.0 (should be at cap-height 700?)

	* uni1EA1 (U+1EA1): X=300.0,Y=1.5 (should be at baseline 0?)

	* quotesinglbase (U+201A): X=262.0,Y=2.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=525.0,Y=2.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=262.0,Y=2.0 (should be at baseline 0?)

	* uni2088 (U+2088): X=176.0,Y=-2.0 (should be at baseline 0?)

	* uni2088 (U+2088): X=176.0,Y=-2.0 (should be at baseline 0?)

	* trademark (U+2122): X=405.0,Y=698.0 (should be at cap-height 700?)

	* trademark (U+2122): X=515.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=702.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=811.0,Y=698.0 (should be at cap-height 700?)

	* trademark (U+2122): X=65.0,Y=698.0 (should be at cap-height 700?)

	* trademark (U+2122): X=352.0,Y=698.0 (should be at cap-height 700?)

	* estimated (U+212E): X=394.0,Y=-1.0 (should be at baseline 0?)

	* estimated (U+212E): X=261.0,Y=702.0 (should be at cap-height 700?)

	* estimated (U+212E): X=526.5,Y=700.5 (should be at cap-height 700?)

	* partialdiff (U+2202): X=167.5,Y=-2.0 (should be at baseline 0?)

	* summation (U+2211): X=51.0,Y=698.0 (should be at cap-height 700?)

	* summation (U+2211): X=687.0,Y=698.0 (should be at cap-height 700?)

	* integral (U+222B): X=495.0,Y=698.5 (should be at cap-height 700?)

	* uni25CF (U+25CF): X=210.5,Y=-0.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<206.0,64.0>--<211.0,3.0>> -> L<<211.0,3.0>--<211.0,0.0>>

	* b (U+0062): L<<211.0,700.0>--<211.0,513.0>> -> L<<211.0,513.0>--<204.0,429.0>>

	* d (U+0064): L<<441.0,0.0>--<441.0,3.0>> -> L<<441.0,3.0>--<446.0,66.0>>

	* d (U+0064): L<<448.0,427.0>--<441.0,513.0>> -> L<<441.0,513.0>--<441.0,700.0>>

	* dcaron (U+010F): L<<441.0,0.0>--<441.0,3.0>> -> L<<441.0,3.0>--<446.0,66.0>>

	* dcaron (U+010F): L<<448.0,427.0>--<441.0,513.0>> -> L<<441.0,513.0>--<441.0,700.0>>

	* dcroat (U+0111): L<<441.0,0.0>--<441.0,3.0>> -> L<<441.0,3.0>--<446.0,66.0>>

	* dcroat (U+0111): L<<448.0,427.0>--<441.0,513.0>> -> L<<441.0,513.0>--<441.0,523.0>>

	* dmacronbelow (U+1E0F): L<<441.0,0.0>--<441.0,3.0>> -> L<<441.0,3.0>--<446.0,66.0>>

	* dmacronbelow (U+1E0F): L<<448.0,427.0>--<441.0,513.0>> -> L<<441.0,513.0>--<441.0,700.0>>

	* exclam (U+0021): L<<258.0,730.0>--<257.0,569.0>> -> L<<257.0,569.0>--<237.0,219.0>>

	* exclam (U+0021): L<<73.0,219.0>--<52.0,569.0>> -> L<<52.0,569.0>--<52.0,730.0>>

	* exclamdown (U+00A1): L<<237.0,321.0>--<257.0,-29.0>> -> L<<257.0,-29.0>--<258.0,-190.0>>

	* exclamdown (U+00A1): L<<52.0,-190.0>--<52.0,-29.0>> -> L<<52.0,-29.0>--<73.0,321.0>>

	* g (U+0067): L<<441.0,10.0>--<441.0,25.0>> -> L<<441.0,25.0>--<445.0,66.0>>

	* g (U+0067): L<<446.0,434.0>--<441.0,497.0>> -> L<<441.0,497.0>--<441.0,500.0>>

	* gbreve (U+011F): L<<441.0,10.0>--<441.0,25.0>> -> L<<441.0,25.0>--<445.0,66.0>>

	* gbreve (U+011F): L<<446.0,434.0>--<441.0,497.0>> -> L<<441.0,497.0>--<441.0,500.0>>

	* gcaron (U+01E7): L<<441.0,10.0>--<441.0,25.0>> -> L<<441.0,25.0>--<445.0,66.0>>

	* gcaron (U+01E7): L<<446.0,434.0>--<441.0,497.0>> -> L<<441.0,497.0>--<441.0,500.0>>

	* gcircumflex (U+011D): L<<441.0,10.0>--<441.0,25.0>> -> L<<441.0,25.0>--<445.0,66.0>>

	* gcircumflex (U+011D): L<<446.0,434.0>--<441.0,497.0>> -> L<<441.0,497.0>--<441.0,500.0>>

	* gdotaccent (U+0121): L<<441.0,10.0>--<441.0,25.0>> -> L<<441.0,25.0>--<445.0,66.0>>

	* gdotaccent (U+0121): L<<446.0,434.0>--<441.0,497.0>> -> L<<441.0,497.0>--<441.0,500.0>>

	* p (U+0070): L<<204.0,71.0>--<211.0,-13.0>> -> L<<211.0,-13.0>--<211.0,-200.0>>

	* p (U+0070): L<<211.0,500.0>--<211.0,497.0>> -> L<<211.0,497.0>--<206.0,436.0>>

	* q (U+0071): L<<441.0,-200.0>--<441.0,-13.0>> -> L<<441.0,-13.0>--<448.0,73.0>>

	* q (U+0071): L<<446.0,434.0>--<441.0,497.0>> -> L<<441.0,497.0>--<441.0,500.0>>

	* thorn (U+00FE): L<<202.0,749.0>--<202.0,554.0>> -> L<<202.0,554.0>--<204.0,525.0>>

	* uni0123 (U+0123): L<<441.0,10.0>--<441.0,25.0>> -> L<<441.0,25.0>--<445.0,66.0>>

	* uni0123 (U+0123): L<<446.0,434.0>--<441.0,497.0>> -> L<<441.0,497.0>--<441.0,500.0>>

	* uni1E0D (U+1E0D): L<<441.0,0.0>--<441.0,3.0>> -> L<<441.0,3.0>--<446.0,66.0>>

	* uni1E0D (U+1E0D): L<<448.0,427.0>--<441.0,513.0>> -> L<<441.0,513.0>--<441.0,700.0>>

	* uni1E21 (U+1E21): L<<441.0,10.0>--<441.0,25.0>> -> L<<441.0,25.0>--<445.0,66.0>>

	* uni1E21 (U+1E21): L<<446.0,434.0>--<441.0,497.0>> -> L<<441.0,497.0>--<441.0,500.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Ccedilla (U+00C7): L<<431.0,7.0>--<401.0,-42.0>>/B<<401.0,-42.0>-<407.0,-32.0>-<423.0,-24.5>> = 0.5130828175110471

	* G (U+0047): L<<588.0,0.0>--<588.0,130.0>>/B<<588.0,130.0>-<586.0,96.0>-<565.5,65.0>> = 3.3664606634298315

	* Gbreve (U+011E): L<<588.0,0.0>--<588.0,130.0>>/B<<588.0,130.0>-<586.0,96.0>-<565.5,65.0>> = 3.3664606634298315

	* Gcaron (U+01E6): L<<588.0,0.0>--<588.0,130.0>>/B<<588.0,130.0>-<586.0,96.0>-<565.5,65.0>> = 3.3664606634298315

	* Gcircumflex (U+011C): L<<588.0,0.0>--<588.0,130.0>>/B<<588.0,130.0>-<586.0,96.0>-<565.5,65.0>> = 3.3664606634298315

	* Gdotaccent (U+0120): L<<588.0,0.0>--<588.0,130.0>>/B<<588.0,130.0>-<586.0,96.0>-<565.5,65.0>> = 3.3664606634298315

	* Scedilla (U+015E): L<<334.0,7.0>--<304.0,-42.0>>/B<<304.0,-42.0>-<310.0,-32.0>-<326.0,-24.5>> = 0.5130828175110471

	* at (U+0040): B<<333.5,-0.5>-<292.0,14.0>-<266.0,39.0>>/B<<266.0,39.0>-<301.0,-15.0>-<357.0,-45.5>> = 13.174087597484956

	* ccedilla (U+00E7): L<<324.0,7.0>--<294.0,-42.0>>/B<<294.0,-42.0>-<300.0,-32.0>-<316.0,-24.5>> = 0.5130828175110471

	* cedilla (U+00B8): L<<331.0,7.0>--<301.0,-42.0>>/B<<301.0,-42.0>-<307.0,-32.0>-<323.0,-24.5>> = 0.5130828175110471

	* nine (U+0039): B<<276.5,257.5>-<279.0,261.0>-<283.0,261.0>>/B<<283.0,261.0>-<222.0,269.0>-<169.0,298.5>> = 7.471559176592385

	* scedilla (U+015F): L<<282.0,7.0>--<252.0,-42.0>>/B<<252.0,-42.0>-<258.0,-32.0>-<274.0,-24.5>> = 0.5130828175110471

	* uni0122 (U+0122): L<<588.0,0.0>--<588.0,130.0>>/B<<588.0,130.0>-<586.0,96.0>-<565.5,65.0>> = 3.3664606634298315

	* uni0162 (U+0162): L<<375.0,7.0>--<345.0,-42.0>>/B<<345.0,-42.0>-<351.0,-32.0>-<367.0,-24.5>> = 0.5130828175110471

	* uni0163 (U+0163): L<<291.0,7.0>--<261.0,-42.0>>/B<<261.0,-42.0>-<267.0,-32.0>-<283.0,-24.5>> = 0.5130828175110471

	* uni0327 (U+0327): L<<331.0,7.0>--<301.0,-42.0>>/B<<301.0,-42.0>-<307.0,-32.0>-<323.0,-24.5>> = 0.5130828175110471

	* uni1E08 (U+1E08): L<<431.0,7.0>--<401.0,-42.0>>/B<<401.0,-42.0>-<407.0,-32.0>-<423.0,-24.5>> = 0.5130828175110471

	* uni1E09 (U+1E09): L<<324.0,7.0>--<294.0,-42.0>>/B<<294.0,-42.0>-<300.0,-32.0>-<316.0,-24.5>> = 0.5130828175110471

	* uni1E1C (U+1E1C): L<<367.0,7.0>--<337.0,-42.0>>/B<<337.0,-42.0>-<343.0,-32.0>-<359.0,-24.5>> = 0.5130828175110471

	* uni1E1D (U+1E1D): L<<311.0,7.0>--<281.0,-42.0>>/B<<281.0,-42.0>-<287.0,-32.0>-<303.0,-24.5>> = 0.5130828175110471

	* uni1E20 (U+1E20): L<<588.0,0.0>--<588.0,130.0>>/B<<588.0,130.0>-<586.0,96.0>-<565.5,65.0>> = 3.3664606634298315

	* uni2079 (U+2079): B<<167.5,551.0>-<169.0,553.0>-<172.0,553.0>>/B<<172.0,553.0>-<135.0,558.0>-<102.5,576.0>> = 7.696051722016556

	* uni2089 (U+2089): B<<167.5,156.0>-<169.0,158.0>-<172.0,158.0>>/B<<172.0,158.0>-<135.0,163.0>-<102.5,181.0>> = 7.696051722016556 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* IJ (U+0132): L<<863.0,700.0>--<864.0,272.0>>

	* J (U+004A): L<<548.0,700.0>--<549.0,272.0>>

	* Jcircumflex (U+0134): L<<548.0,700.0>--<549.0,272.0>>

	* Lslash (U+0141): L<<30.0,268.0>--<29.0,414.0>>

	* M (U+004D): L<<49.0,700.0>--<275.0,701.0>>

	* M (U+004D): L<<694.0,701.0>--<920.0,700.0>>

	* U (U+0055): L<<26.0,232.0>--<27.0,700.0>>

	* U (U+0055): L<<595.0,700.0>--<596.0,232.0>>

	* Uacute (U+00DA): L<<26.0,232.0>--<27.0,700.0>>

	* Uacute (U+00DA): L<<595.0,700.0>--<596.0,232.0>>

	* Ubreve (U+016C): L<<26.0,232.0>--<27.0,700.0>>

	* Ubreve (U+016C): L<<595.0,700.0>--<596.0,232.0>>

	* Ucircumflex (U+00DB): L<<26.0,232.0>--<27.0,700.0>>

	* Ucircumflex (U+00DB): L<<595.0,700.0>--<596.0,232.0>>

	* Udieresis (U+00DC): L<<26.0,232.0>--<27.0,700.0>>

	* Udieresis (U+00DC): L<<595.0,700.0>--<596.0,232.0>>

	* Ugrave (U+00D9): L<<26.0,232.0>--<27.0,700.0>>

	* Ugrave (U+00D9): L<<595.0,700.0>--<596.0,232.0>>

	* Uhungarumlaut (U+0170): L<<26.0,232.0>--<27.0,700.0>>

	* Uhungarumlaut (U+0170): L<<595.0,700.0>--<596.0,232.0>>

	* Umacron (U+016A): L<<26.0,232.0>--<27.0,700.0>>

	* Umacron (U+016A): L<<595.0,700.0>--<596.0,232.0>>

	* Uogonek (U+0172): L<<26.0,232.0>--<27.0,700.0>>

	* Uogonek (U+0172): L<<595.0,700.0>--<596.0,232.0>>

	* Uring (U+016E): L<<26.0,232.0>--<27.0,700.0>>

	* Uring (U+016E): L<<595.0,700.0>--<596.0,232.0>>

	* Utilde (U+0168): L<<26.0,232.0>--<27.0,700.0>>

	* Utilde (U+0168): L<<595.0,700.0>--<596.0,232.0>>

	* a (U+0061): L<<244.0,314.0>--<76.0,313.0>>

	* aacute (U+00E1): L<<244.0,314.0>--<76.0,313.0>>

	* abreve (U+0103): L<<244.0,314.0>--<76.0,313.0>>

	* acircumflex (U+00E2): L<<244.0,314.0>--<76.0,313.0>>

	* adieresis (U+00E4): L<<244.0,314.0>--<76.0,313.0>>

	* ae (U+00E6): L<<244.0,314.0>--<76.0,313.0>>

	* aeacute (U+01FD): L<<244.0,314.0>--<76.0,313.0>>

	* agrave (U+00E0): L<<244.0,314.0>--<76.0,313.0>>

	* amacron (U+0101): L<<244.0,314.0>--<76.0,313.0>>

	* aogonek (U+0105): L<<244.0,314.0>--<76.0,313.0>>

	* aring (U+00E5): L<<244.0,314.0>--<76.0,313.0>>

	* aringacute (U+01FB): L<<244.0,314.0>--<76.0,313.0>>

	* at (U+0040): L<<448.0,310.0>--<263.0,311.0>>

	* atilde (U+00E3): L<<244.0,314.0>--<76.0,313.0>>

	* b (U+0062): L<<32.0,0.0>--<31.0,700.0>>

	* d (U+0064): L<<620.0,700.0>--<619.0,0.0>>

	* dcaron (U+010F): L<<620.0,700.0>--<619.0,0.0>>

	* dcroat (U+0111): L<<620.0,523.0>--<619.0,0.0>>

	* dmacronbelow (U+1E0F): L<<620.0,700.0>--<619.0,0.0>>

	* eng (U+014B): L<<399.0,0.0>--<400.0,292.0>>

	* exclam (U+0021): L<<258.0,730.0>--<257.0,569.0>>

	* exclamdown (U+00A1): L<<257.0,-29.0>--<258.0,-190.0>>

	* four (U+0034): L<<29.0,173.0>--<30.0,295.0>>

	* g (U+0067): L<<619.0,500.0>--<620.0,10.0>>

	* gbreve (U+011F): L<<619.0,500.0>--<620.0,10.0>>

	* gcaron (U+01E7): L<<619.0,500.0>--<620.0,10.0>>

	* gcircumflex (U+011D): L<<619.0,500.0>--<620.0,10.0>>

	* gdotaccent (U+0121): L<<619.0,500.0>--<620.0,10.0>>

	* lslash (U+0142): L<<427.0,522.0>--<428.0,378.0>>

	* lslash (U+0142): L<<45.0,269.0>--<44.0,413.0>>

	* n (U+006E): L<<399.0,0.0>--<400.0,292.0>>

	* nacute (U+0144): L<<399.0,0.0>--<400.0,292.0>>

	* napostrophe (U+0149): L<<690.0,0.0>--<691.0,292.0>>

	* ncaron (U+0148): L<<399.0,0.0>--<400.0,292.0>>

	* nmacronbelow (U+1E49): L<<399.0,0.0>--<400.0,292.0>>

	* ntilde (U+00F1): L<<399.0,0.0>--<400.0,292.0>>

	* p (U+0070): L<<31.0,-200.0>--<32.0,500.0>>

	* q (U+0071): L<<619.0,500.0>--<620.0,-200.0>>

	* thorn (U+00FE): L<<22.0,-179.0>--<23.0,749.0>>

	* two (U+0032): L<<17.0,0.0>--<18.0,116.0>>

	* uni0123 (U+0123): L<<619.0,500.0>--<620.0,10.0>>

	* uni0146 (U+0146): L<<399.0,0.0>--<400.0,292.0>>

	* uni0272 (U+0272): L<<399.0,0.0>--<400.0,292.0>>

	* uni1E0D (U+1E0D): L<<620.0,700.0>--<619.0,0.0>>

	* uni1E21 (U+1E21): L<<619.0,500.0>--<620.0,10.0>>

	* uni1E42 (U+1E42): L<<49.0,700.0>--<275.0,701.0>>

	* uni1E42 (U+1E42): L<<694.0,701.0>--<920.0,700.0>>

	* uni1E45 (U+1E45): L<<399.0,0.0>--<400.0,292.0>>

	* uni1E47 (U+1E47): L<<399.0,0.0>--<400.0,292.0>>

	* uni1E78 (U+1E78): L<<26.0,232.0>--<27.0,700.0>>

	* uni1E78 (U+1E78): L<<595.0,700.0>--<596.0,232.0>>

	* uni1E7A (U+1E7A): L<<26.0,232.0>--<27.0,700.0>>

	* uni1E7A (U+1E7A): L<<595.0,700.0>--<596.0,232.0>>

	* uni1EA1 (U+1EA1): L<<244.0,314.0>--<76.0,313.0>>

	* uni1EE4 (U+1EE4): L<<26.0,232.0>--<27.0,700.0>>

	* uni1EE4 (U+1EE4): L<<595.0,700.0>--<596.0,232.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[10] Panamera-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1120 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1277, but got 853 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 434, but got 267 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
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

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 600 among a set of 11 math glyphs.
The following math glyphs have a different width, though:

Width = 667:
logicalnot

Width = 820:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** Lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* d (U+0064): L<<469.0,0.0>--<469.0,72.0>> -> L<<469.0,72.0>--<474.0,125.0>>

	* d (U+0064): L<<476.0,368.0>--<469.0,444.0>> -> L<<469.0,444.0>--<469.0,700.0>>

	* dcaron (U+010F): L<<469.0,0.0>--<469.0,72.0>> -> L<<469.0,72.0>--<474.0,125.0>>

	* dcaron (U+010F): L<<476.0,368.0>--<469.0,444.0>> -> L<<469.0,444.0>--<469.0,700.0>>

	* dcroat (U+0111): L<<469.0,0.0>--<469.0,72.0>> -> L<<469.0,72.0>--<474.0,125.0>>

	* dcroat (U+0111): L<<476.0,368.0>--<469.0,444.0>> -> L<<469.0,444.0>--<469.0,568.0>>

	* dmacronbelow (U+1E0F): L<<469.0,0.0>--<469.0,72.0>> -> L<<469.0,72.0>--<474.0,125.0>>

	* dmacronbelow (U+1E0F): L<<476.0,368.0>--<469.0,444.0>> -> L<<469.0,444.0>--<469.0,700.0>>

	* exclam (U+0021): L<<115.0,216.0>--<95.0,593.0>> -> L<<95.0,593.0>--<95.0,731.0>>

	* exclam (U+0021): L<<216.0,731.0>--<215.0,593.0>> -> L<<215.0,593.0>--<196.0,216.0>>

	* exclamdown (U+00A1): L<<196.0,324.0>--<215.0,-52.0>> -> L<<215.0,-52.0>--<216.0,-190.0>>

	* exclamdown (U+00A1): L<<95.0,-190.0>--<95.0,-52.0>> -> L<<95.0,-52.0>--<115.0,324.0>>

	* g (U+0067): L<<474.0,375.0>--<469.0,428.0>> -> L<<469.0,428.0>--<469.0,500.0>>

	* gbreve (U+011F): L<<474.0,375.0>--<469.0,428.0>> -> L<<469.0,428.0>--<469.0,500.0>>

	* gcaron (U+01E7): L<<474.0,375.0>--<469.0,428.0>> -> L<<469.0,428.0>--<469.0,500.0>>

	* gcircumflex (U+011D): L<<474.0,375.0>--<469.0,428.0>> -> L<<469.0,428.0>--<469.0,500.0>>

	* gdotaccent (U+0121): L<<474.0,375.0>--<469.0,428.0>> -> L<<469.0,428.0>--<469.0,500.0>>

	* q (U+0071): L<<469.0,-200.0>--<469.0,56.0>> -> L<<469.0,56.0>--<476.0,132.0>>

	* q (U+0071): L<<474.0,375.0>--<469.0,428.0>> -> L<<469.0,428.0>--<469.0,500.0>>

	* thorn (U+00FE): L<<126.0,98.0>--<130.0,46.0>> -> L<<130.0,46.0>--<130.0,-214.0>>

	* thorn (U+00FE): L<<130.0,785.0>--<130.0,448.0>> -> L<<130.0,448.0>--<126.0,395.0>>

	* uni0123 (U+0123): L<<474.0,375.0>--<469.0,428.0>> -> L<<469.0,428.0>--<469.0,500.0>>

	* uni1E0D (U+1E0D): L<<469.0,0.0>--<469.0,72.0>> -> L<<469.0,72.0>--<474.0,125.0>>

	* uni1E0D (U+1E0D): L<<476.0,368.0>--<469.0,444.0>> -> L<<469.0,444.0>--<469.0,700.0>>

	* uni1E21 (U+1E21): L<<474.0,375.0>--<469.0,428.0>> -> L<<469.0,428.0>--<469.0,500.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* G (U+0047): L<<632.0,0.0>--<632.0,206.0>>/B<<632.0,206.0>-<627.0,146.0>-<598.5,98.5>> = 4.763641690726143

	* Gbreve (U+011E): L<<632.0,0.0>--<632.0,206.0>>/B<<632.0,206.0>-<627.0,146.0>-<598.5,98.5>> = 4.763641690726143

	* Gcaron (U+01E6): L<<632.0,0.0>--<632.0,206.0>>/B<<632.0,206.0>-<627.0,146.0>-<598.5,98.5>> = 4.763641690726143

	* Gcircumflex (U+011C): L<<632.0,0.0>--<632.0,206.0>>/B<<632.0,206.0>-<627.0,146.0>-<598.5,98.5>> = 4.763641690726143

	* Gdotaccent (U+0120): L<<632.0,0.0>--<632.0,206.0>>/B<<632.0,206.0>-<627.0,146.0>-<598.5,98.5>> = 4.763641690726143

	* b (U+0062): B<<201.0,26.5>-<155.0,64.0>-<136.0,125.0>>/L<<136.0,125.0>--<142.0,72.0>> = 10.841710813226324

	* b (U+0062): L<<142.0,444.0>--<134.0,368.0>>/B<<134.0,368.0>-<153.0,433.0>-<200.0,473.0>> = 10.285041499104333

	* d (U+0064): B<<410.5,473.0>-<457.0,433.0>-<476.0,368.0>>/L<<476.0,368.0>--<469.0,444.0>> = 11.031652057003772

	* d (U+0064): L<<469.0,72.0>--<474.0,125.0>>/B<<474.0,125.0>-<455.0,64.0>-<409.5,27.0>> = 11.911215431971549

	* dcaron (U+010F): B<<410.5,473.0>-<457.0,433.0>-<476.0,368.0>>/L<<476.0,368.0>--<469.0,444.0>> = 11.031652057003772

	* dcaron (U+010F): L<<469.0,72.0>--<474.0,125.0>>/B<<474.0,125.0>-<455.0,64.0>-<409.5,27.0>> = 11.911215431971549

	* dcroat (U+0111): B<<410.5,473.0>-<457.0,433.0>-<476.0,368.0>>/L<<476.0,368.0>--<469.0,444.0>> = 11.031652057003772

	* dcroat (U+0111): L<<469.0,72.0>--<474.0,125.0>>/B<<474.0,125.0>-<455.0,64.0>-<409.5,27.0>> = 11.911215431971549

	* dmacronbelow (U+1E0F): B<<410.5,473.0>-<457.0,433.0>-<476.0,368.0>>/L<<476.0,368.0>--<469.0,444.0>> = 11.031652057003772

	* dmacronbelow (U+1E0F): L<<469.0,72.0>--<474.0,125.0>>/B<<474.0,125.0>-<455.0,64.0>-<409.5,27.0>> = 11.911215431971549

	* f (U+0066): L<<8.0,501.0>--<135.0,501.0>>/B<<135.0,501.0>-<99.0,509.0>-<76.0,537.0>> = 12.528807709151492

	* g (U+0067): B<<409.5,473.5>-<455.0,436.0>-<474.0,375.0>>/L<<474.0,375.0>--<469.0,428.0>> = 11.91121543197158

	* g (U+0067): L<<469.0,80.0>--<474.0,124.0>>/B<<474.0,124.0>-<454.0,63.0>-<407.5,25.5>> = 11.669632193753891

	* gbreve (U+011F): B<<409.5,473.5>-<455.0,436.0>-<474.0,375.0>>/L<<474.0,375.0>--<469.0,428.0>> = 11.91121543197158

	* gbreve (U+011F): L<<469.0,80.0>--<474.0,124.0>>/B<<474.0,124.0>-<454.0,63.0>-<407.5,25.5>> = 11.669632193753891

	* gcaron (U+01E7): B<<409.5,473.5>-<455.0,436.0>-<474.0,375.0>>/L<<474.0,375.0>--<469.0,428.0>> = 11.91121543197158

	* gcaron (U+01E7): L<<469.0,80.0>--<474.0,124.0>>/B<<474.0,124.0>-<454.0,63.0>-<407.5,25.5>> = 11.669632193753891

	* gcircumflex (U+011D): B<<409.5,473.5>-<455.0,436.0>-<474.0,375.0>>/L<<474.0,375.0>--<469.0,428.0>> = 11.91121543197158

	* gcircumflex (U+011D): L<<469.0,80.0>--<474.0,124.0>>/B<<474.0,124.0>-<454.0,63.0>-<407.5,25.5>> = 11.669632193753891

	* gdotaccent (U+0121): B<<409.5,473.5>-<455.0,436.0>-<474.0,375.0>>/L<<474.0,375.0>--<469.0,428.0>> = 11.91121543197158

	* gdotaccent (U+0121): L<<469.0,80.0>--<474.0,124.0>>/B<<474.0,124.0>-<454.0,63.0>-<407.5,25.5>> = 11.669632193753891

	* p (U+0070): B<<200.0,27.0>-<153.0,67.0>-<134.0,132.0>>/L<<134.0,132.0>--<142.0,56.0>> = 10.28504149910437

	* p (U+0070): L<<142.0,428.0>--<136.0,375.0>>/B<<136.0,375.0>-<155.0,436.0>-<201.0,473.5>> = 10.841710813226358

	* q (U+0071): B<<409.5,473.5>-<455.0,436.0>-<474.0,375.0>>/L<<474.0,375.0>--<469.0,428.0>> = 11.91121543197158

	* q (U+0071): L<<469.0,56.0>--<476.0,132.0>>/B<<476.0,132.0>-<457.0,67.0>-<410.5,27.5>> = 11.031652057003805

	* uni0122 (U+0122): L<<632.0,0.0>--<632.0,206.0>>/B<<632.0,206.0>-<627.0,146.0>-<598.5,98.5>> = 4.763641690726143

	* uni0123 (U+0123): B<<409.5,473.5>-<455.0,436.0>-<474.0,375.0>>/L<<474.0,375.0>--<469.0,428.0>> = 11.91121543197158

	* uni0123 (U+0123): L<<469.0,80.0>--<474.0,124.0>>/B<<474.0,124.0>-<454.0,63.0>-<407.5,25.5>> = 11.669632193753891

	* uni1E0D (U+1E0D): B<<410.5,473.0>-<457.0,433.0>-<476.0,368.0>>/L<<476.0,368.0>--<469.0,444.0>> = 11.031652057003772

	* uni1E0D (U+1E0D): L<<469.0,72.0>--<474.0,125.0>>/B<<474.0,125.0>-<455.0,64.0>-<409.5,27.0>> = 11.911215431971549

	* uni1E20 (U+1E20): L<<632.0,0.0>--<632.0,206.0>>/B<<632.0,206.0>-<627.0,146.0>-<598.5,98.5>> = 4.763641690726143

	* uni1E21 (U+1E21): B<<409.5,473.5>-<455.0,436.0>-<474.0,375.0>>/L<<474.0,375.0>--<469.0,428.0>> = 11.91121543197158

	* uni1E21 (U+1E21): L<<469.0,80.0>--<474.0,124.0>>/B<<474.0,124.0>-<454.0,63.0>-<407.5,25.5>> = 11.669632193753891 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* IJ (U+0132): L<<763.0,700.0>--<764.0,226.0>>

	* J (U+004A): L<<512.0,700.0>--<513.0,226.0>>

	* Jcircumflex (U+0134): L<<512.0,700.0>--<513.0,226.0>>

	* M (U+004D): L<<53.0,700.0>--<178.0,701.0>>

	* M (U+004D): L<<686.0,701.0>--<811.0,700.0>>

	* U (U+0055): L<<47.0,220.0>--<48.0,700.0>>

	* U (U+0055): L<<575.0,700.0>--<576.0,220.0>>

	* Uacute (U+00DA): L<<47.0,220.0>--<48.0,700.0>>

	* Uacute (U+00DA): L<<575.0,700.0>--<576.0,220.0>>

	* Ubreve (U+016C): L<<47.0,220.0>--<48.0,700.0>>

	* Ubreve (U+016C): L<<575.0,700.0>--<576.0,220.0>>

	* Ucircumflex (U+00DB): L<<47.0,220.0>--<48.0,700.0>>

	* Ucircumflex (U+00DB): L<<575.0,700.0>--<576.0,220.0>>

	* Udieresis (U+00DC): L<<47.0,220.0>--<48.0,700.0>>

	* Udieresis (U+00DC): L<<575.0,700.0>--<576.0,220.0>>

	* Ugrave (U+00D9): L<<47.0,220.0>--<48.0,700.0>>

	* Ugrave (U+00D9): L<<575.0,700.0>--<576.0,220.0>>

	* Uhungarumlaut (U+0170): L<<47.0,220.0>--<48.0,700.0>>

	* Uhungarumlaut (U+0170): L<<575.0,700.0>--<576.0,220.0>>

	* Umacron (U+016A): L<<47.0,220.0>--<48.0,700.0>>

	* Umacron (U+016A): L<<575.0,700.0>--<576.0,220.0>>

	* Uogonek (U+0172): L<<47.0,220.0>--<48.0,700.0>>

	* Uogonek (U+0172): L<<575.0,700.0>--<576.0,220.0>>

	* Uring (U+016E): L<<47.0,220.0>--<48.0,700.0>>

	* Uring (U+016E): L<<575.0,700.0>--<576.0,220.0>>

	* Utilde (U+0168): L<<47.0,220.0>--<48.0,700.0>>

	* Utilde (U+0168): L<<575.0,700.0>--<576.0,220.0>>

	* b (U+0062): L<<44.0,0.0>--<43.0,700.0>>

	* d (U+0064): L<<568.0,700.0>--<567.0,0.0>>

	* dcaron (U+010F): L<<568.0,700.0>--<567.0,0.0>>

	* dcroat (U+0111): L<<568.0,568.0>--<567.0,0.0>>

	* dmacronbelow (U+1E0F): L<<568.0,700.0>--<567.0,0.0>>

	* exclam (U+0021): L<<216.0,731.0>--<215.0,593.0>>

	* exclamdown (U+00A1): L<<215.0,-52.0>--<216.0,-190.0>>

	* g (U+0067): L<<567.0,500.0>--<568.0,4.0>>

	* gbreve (U+011F): L<<567.0,500.0>--<568.0,4.0>>

	* gcaron (U+01E7): L<<567.0,500.0>--<568.0,4.0>>

	* gcircumflex (U+011D): L<<567.0,500.0>--<568.0,4.0>>

	* gdotaccent (U+0121): L<<567.0,500.0>--<568.0,4.0>>

	* p (U+0070): L<<43.0,-200.0>--<44.0,500.0>>

	* q (U+0071): L<<567.0,500.0>--<568.0,-200.0>>

	* thorn (U+00FE): L<<30.0,-214.0>--<31.0,785.0>>

	* uni0123 (U+0123): L<<567.0,500.0>--<568.0,4.0>>

	* uni018F (U+018F): L<<52.0,372.0>--<630.0,375.0>>

	* uni1E0D (U+1E0D): L<<568.0,700.0>--<567.0,0.0>>

	* uni1E21 (U+1E21): L<<567.0,500.0>--<568.0,4.0>>

	* uni1E42 (U+1E42): L<<53.0,700.0>--<178.0,701.0>>

	* uni1E42 (U+1E42): L<<686.0,701.0>--<811.0,700.0>>

	* uni1E78 (U+1E78): L<<47.0,220.0>--<48.0,700.0>>

	* uni1E78 (U+1E78): L<<575.0,700.0>--<576.0,220.0>>

	* uni1E7A (U+1E7A): L<<47.0,220.0>--<48.0,700.0>>

	* uni1E7A (U+1E7A): L<<575.0,700.0>--<576.0,220.0>>

	* uni1EE4 (U+1EE4): L<<47.0,220.0>--<48.0,700.0>>

	* uni1EE4 (U+1EE4): L<<575.0,700.0>--<576.0,220.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 15 | 50 | 721 | 43 | 586 | 0 |
| 0% | 1% | 4% | 51% | 3% | 41% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
