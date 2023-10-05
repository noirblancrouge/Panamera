## FontBakery report

fontbakery version: 0.9.0

<details><summary><b>[6] Panamera-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
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
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<127.0,133.0>--<132.0,81.0>> -> L<<132.0,81.0>--<132.0,0.0>>

	* b (U+0062): L<<132.0,700.0>--<132.0,435.0>> -> L<<132.0,435.0>--<125.0,360.0>>

	* d (U+0064): L<<473.0,0.0>--<473.0,81.0>> -> L<<473.0,81.0>--<478.0,133.0>>

	* d (U+0064): L<<480.0,360.0>--<473.0,435.0>> -> L<<473.0,435.0>--<473.0,700.0>>

	* dcaron (U+010F): L<<473.0,0.0>--<473.0,81.0>> -> L<<473.0,81.0>--<478.0,133.0>>

	* dcaron (U+010F): L<<480.0,360.0>--<473.0,435.0>> -> L<<473.0,435.0>--<473.0,700.0>>

	* dcroat (U+0111): L<<473.0,0.0>--<473.0,81.0>> -> L<<473.0,81.0>--<478.0,133.0>>

	* dcroat (U+0111): L<<480.0,360.0>--<473.0,435.0>> -> L<<473.0,435.0>--<473.0,574.0>>

	* dmacronbelow (U+1E0F): L<<473.0,0.0>--<473.0,81.0>> -> L<<473.0,81.0>--<478.0,133.0>>

	* dmacronbelow (U+1E0F): L<<480.0,360.0>--<473.0,435.0>> -> L<<473.0,435.0>--<473.0,700.0>>

	* exclam (U+0021): L<<120.0,216.0>--<100.0,596.0>> -> L<<100.0,596.0>--<100.0,731.0>>

	* exclam (U+0021): L<<210.0,731.0>--<209.0,596.0>> -> L<<209.0,596.0>--<190.0,216.0>>

	* exclamdown (U+00A1): L<<100.0,-191.0>--<100.0,-56.0>> -> L<<100.0,-56.0>--<120.0,324.0>>

	* exclamdown (U+00A1): L<<190.0,324.0>--<209.0,-56.0>> -> L<<209.0,-56.0>--<210.0,-191.0>>

	* g (U+0067): L<<478.0,367.0>--<473.0,419.0>> -> L<<473.0,419.0>--<473.0,500.0>>

	* gbreve (U+011F): L<<478.0,367.0>--<473.0,419.0>> -> L<<473.0,419.0>--<473.0,500.0>>

	* gcaron (U+01E7): L<<478.0,367.0>--<473.0,419.0>> -> L<<473.0,419.0>--<473.0,500.0>>

	* gcircumflex (U+011D): L<<478.0,367.0>--<473.0,419.0>> -> L<<473.0,419.0>--<473.0,500.0>>

	* gdotaccent (U+0121): L<<478.0,367.0>--<473.0,419.0>> -> L<<473.0,419.0>--<473.0,500.0>>

	* p (U+0070): L<<125.0,140.0>--<132.0,65.0>> -> L<<132.0,65.0>--<132.0,-200.0>>

	* p (U+0070): L<<132.0,500.0>--<132.0,419.0>> -> L<<132.0,419.0>--<127.0,367.0>>

	* q (U+0071): L<<473.0,-200.0>--<473.0,65.0>> -> L<<473.0,65.0>--<480.0,140.0>>

	* q (U+0071): L<<478.0,367.0>--<473.0,419.0>> -> L<<473.0,419.0>--<473.0,500.0>>

	* thorn (U+00FE): L<<116.0,114.0>--<120.0,56.0>> -> L<<120.0,56.0>--<120.0,-219.0>>

	* thorn (U+00FE): L<<120.0,789.0>--<120.0,433.0>> -> L<<120.0,433.0>--<116.0,377.0>>

	* uni0123 (U+0123): L<<478.0,367.0>--<473.0,419.0>> -> L<<473.0,419.0>--<473.0,500.0>>

	* uni1E0D (U+1E0D): L<<473.0,0.0>--<473.0,81.0>> -> L<<473.0,81.0>--<478.0,133.0>>

	* uni1E0D (U+1E0D): L<<480.0,360.0>--<473.0,435.0>> -> L<<473.0,435.0>--<473.0,700.0>>

	* uni1E21 (U+1E21): L<<478.0,367.0>--<473.0,419.0>> -> L<<473.0,419.0>--<473.0,500.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* G (U+0047): L<<637.0,0.0>--<637.0,214.0>>/B<<637.0,214.0>-<631.0,151.0>-<601.5,101.5>> = 5.4403320310054815

	* Gbreve (U+011E): L<<637.0,0.0>--<637.0,214.0>>/B<<637.0,214.0>-<631.0,151.0>-<601.5,101.5>> = 5.4403320310054815

	* Gcaron (U+01E6): L<<637.0,0.0>--<637.0,214.0>>/B<<637.0,214.0>-<631.0,151.0>-<601.5,101.5>> = 5.4403320310054815

	* Gcircumflex (U+011C): L<<637.0,0.0>--<637.0,214.0>>/B<<637.0,214.0>-<631.0,151.0>-<601.5,101.5>> = 5.4403320310054815

	* Gdotaccent (U+0120): L<<637.0,0.0>--<637.0,214.0>>/B<<637.0,214.0>-<631.0,151.0>-<601.5,101.5>> = 5.4403320310054815

	* b (U+0062): B<<193.0,29.5>-<146.0,70.0>-<127.0,133.0>>/L<<127.0,133.0>--<132.0,81.0>> = 11.290319588143252

	* b (U+0062): L<<132.0,435.0>--<125.0,360.0>>/B<<125.0,360.0>-<144.0,427.0>-<192.0,470.0>> = 10.500227738762598

	* d (U+0064): B<<413.0,470.0>-<461.0,427.0>-<480.0,360.0>>/L<<480.0,360.0>--<473.0,435.0>> = 10.500227738762598

	* d (U+0064): L<<473.0,81.0>--<478.0,133.0>>/B<<478.0,133.0>-<459.0,70.0>-<412.0,29.5>> = 11.290319588143252

	* dcaron (U+010F): B<<413.0,470.0>-<461.0,427.0>-<480.0,360.0>>/L<<480.0,360.0>--<473.0,435.0>> = 10.500227738762598

	* dcaron (U+010F): L<<473.0,81.0>--<478.0,133.0>>/B<<478.0,133.0>-<459.0,70.0>-<412.0,29.5>> = 11.290319588143252

	* dcroat (U+0111): B<<413.0,470.0>-<461.0,427.0>-<480.0,360.0>>/L<<480.0,360.0>--<473.0,435.0>> = 10.500227738762598

	* dcroat (U+0111): L<<473.0,81.0>--<478.0,133.0>>/B<<478.0,133.0>-<459.0,70.0>-<412.0,29.5>> = 11.290319588143252

	* dmacronbelow (U+1E0F): B<<413.0,470.0>-<461.0,427.0>-<480.0,360.0>>/L<<480.0,360.0>--<473.0,435.0>> = 10.500227738762598

	* dmacronbelow (U+1E0F): L<<473.0,81.0>--<478.0,133.0>>/B<<478.0,133.0>-<459.0,70.0>-<412.0,29.5>> = 11.290319588143252

	* f (U+0066): L<<8.0,501.0>--<143.0,501.0>>/B<<143.0,501.0>-<102.0,509.0>-<78.0,539.0>> = 11.04094018032372

	* g (U+0067): B<<412.0,470.5>-<459.0,430.0>-<478.0,367.0>>/L<<478.0,367.0>--<473.0,419.0>> = 11.29031958814322

	* g (U+0067): L<<473.0,87.0>--<478.0,133.0>>/B<<478.0,133.0>-<458.0,69.0>-<410.5,28.0>> = 11.150576734569476

	* gbreve (U+011F): B<<412.0,470.5>-<459.0,430.0>-<478.0,367.0>>/L<<478.0,367.0>--<473.0,419.0>> = 11.29031958814322

	* gbreve (U+011F): L<<473.0,87.0>--<478.0,133.0>>/B<<478.0,133.0>-<458.0,69.0>-<410.5,28.0>> = 11.150576734569476

	* gcaron (U+01E7): B<<412.0,470.5>-<459.0,430.0>-<478.0,367.0>>/L<<478.0,367.0>--<473.0,419.0>> = 11.29031958814322

	* gcaron (U+01E7): L<<473.0,87.0>--<478.0,133.0>>/B<<478.0,133.0>-<458.0,69.0>-<410.5,28.0>> = 11.150576734569476

	* gcircumflex (U+011D): B<<412.0,470.5>-<459.0,430.0>-<478.0,367.0>>/L<<478.0,367.0>--<473.0,419.0>> = 11.29031958814322

	* gcircumflex (U+011D): L<<473.0,87.0>--<478.0,133.0>>/B<<478.0,133.0>-<458.0,69.0>-<410.5,28.0>> = 11.150576734569476

	* gdotaccent (U+0121): B<<412.0,470.5>-<459.0,430.0>-<478.0,367.0>>/L<<478.0,367.0>--<473.0,419.0>> = 11.29031958814322

	* gdotaccent (U+0121): L<<473.0,87.0>--<478.0,133.0>>/B<<478.0,133.0>-<458.0,69.0>-<410.5,28.0>> = 11.150576734569476

	* p (U+0070): B<<192.0,30.0>-<144.0,73.0>-<125.0,140.0>>/L<<125.0,140.0>--<132.0,65.0>> = 10.500227738762634

	* p (U+0070): L<<132.0,419.0>--<127.0,367.0>>/B<<127.0,367.0>-<146.0,430.0>-<193.0,470.5>> = 11.29031958814322

	* q (U+0071): B<<412.0,470.5>-<459.0,430.0>-<478.0,367.0>>/L<<478.0,367.0>--<473.0,419.0>> = 11.29031958814322

	* q (U+0071): L<<473.0,65.0>--<480.0,140.0>>/B<<480.0,140.0>-<461.0,73.0>-<413.0,30.0>> = 10.500227738762634

	* uni0122 (U+0122): L<<637.0,0.0>--<637.0,214.0>>/B<<637.0,214.0>-<631.0,151.0>-<601.5,101.5>> = 5.4403320310054815

	* uni0123 (U+0123): B<<412.0,470.5>-<459.0,430.0>-<478.0,367.0>>/L<<478.0,367.0>--<473.0,419.0>> = 11.29031958814322

	* uni0123 (U+0123): L<<473.0,87.0>--<478.0,133.0>>/B<<478.0,133.0>-<458.0,69.0>-<410.5,28.0>> = 11.150576734569476

	* uni1E0D (U+1E0D): B<<413.0,470.0>-<461.0,427.0>-<480.0,360.0>>/L<<480.0,360.0>--<473.0,435.0>> = 10.500227738762598

	* uni1E0D (U+1E0D): L<<473.0,81.0>--<478.0,133.0>>/B<<478.0,133.0>-<459.0,70.0>-<412.0,29.5>> = 11.290319588143252

	* uni1E20 (U+1E20): L<<637.0,0.0>--<637.0,214.0>>/B<<637.0,214.0>-<631.0,151.0>-<601.5,101.5>> = 5.4403320310054815

	* uni1E21 (U+1E21): B<<412.0,470.5>-<459.0,430.0>-<478.0,367.0>>/L<<478.0,367.0>--<473.0,419.0>> = 11.29031958814322

	* uni1E21 (U+1E21): L<<473.0,87.0>--<478.0,133.0>>/B<<478.0,133.0>-<458.0,69.0>-<410.5,28.0>> = 11.150576734569476 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Dcroat (U+0110): L<<261.0,275.0>--<260.0,71.0>>

	* Eth (U+00D0): L<<261.0,275.0>--<260.0,71.0>>

	* IJ (U+0132): L<<749.0,700.0>--<750.0,220.0>>

	* IJacute (U+E133): L<<749.0,700.0>--<750.0,220.0>>

	* J (U+004A): L<<507.0,700.0>--<508.0,220.0>>

	* Jcircumflex (U+0134): L<<507.0,700.0>--<508.0,220.0>>

	* U (U+0055): L<<49.0,218.0>--<50.0,700.0>>

	* U (U+0055): L<<572.0,700.0>--<573.0,218.0>>

	* Uacute (U+00DA): L<<49.0,218.0>--<50.0,700.0>>

	* Uacute (U+00DA): L<<572.0,700.0>--<573.0,218.0>>

	* Ubreve (U+016C): L<<49.0,218.0>--<50.0,700.0>>

	* Ubreve (U+016C): L<<572.0,700.0>--<573.0,218.0>>

	* Ucircumflex (U+00DB): L<<49.0,218.0>--<50.0,700.0>>

	* Ucircumflex (U+00DB): L<<572.0,700.0>--<573.0,218.0>>

	* Udieresis (U+00DC): L<<49.0,218.0>--<50.0,700.0>>

	* Udieresis (U+00DC): L<<572.0,700.0>--<573.0,218.0>>

	* Ugrave (U+00D9): L<<49.0,218.0>--<50.0,700.0>>

	* Ugrave (U+00D9): L<<572.0,700.0>--<573.0,218.0>>

	* Uhungarumlaut (U+0170): L<<49.0,218.0>--<50.0,700.0>>

	* Uhungarumlaut (U+0170): L<<572.0,700.0>--<573.0,218.0>>

	* Umacron (U+016A): L<<49.0,218.0>--<50.0,700.0>>

	* Umacron (U+016A): L<<572.0,700.0>--<573.0,218.0>>

	* Uogonek (U+0172): L<<49.0,218.0>--<50.0,700.0>>

	* Uogonek (U+0172): L<<572.0,700.0>--<573.0,218.0>>

	* Uring (U+016E): L<<49.0,218.0>--<50.0,700.0>>

	* Uring (U+016E): L<<572.0,700.0>--<573.0,218.0>>

	* Utilde (U+0168): L<<49.0,218.0>--<50.0,700.0>>

	* Utilde (U+0168): L<<572.0,700.0>--<573.0,218.0>>

	* b (U+0062): L<<45.0,0.0>--<44.0,700.0>>

	* exclam (U+0021): L<<210.0,731.0>--<209.0,596.0>>

	* exclamdown (U+00A1): L<<209.0,-56.0>--<210.0,-191.0>>

	* four (U+0034): L<<361.0,220.0>--<32.0,221.0>>

	* g (U+0067): L<<560.0,500.0>--<561.0,3.0>>

	* gbreve (U+011F): L<<560.0,500.0>--<561.0,3.0>>

	* gcaron (U+01E7): L<<560.0,500.0>--<561.0,3.0>>

	* gcircumflex (U+011D): L<<560.0,500.0>--<561.0,3.0>>

	* gdotaccent (U+0121): L<<560.0,500.0>--<561.0,3.0>>

	* onequarter (U+00BC): L<<606.0,133.0>--<407.0,134.0>>

	* p (U+0070): L<<44.0,-200.0>--<45.0,500.0>>

	* q (U+0071): L<<560.0,500.0>--<561.0,-200.0>>

	* thorn (U+00FE): L<<32.0,-219.0>--<33.0,789.0>>

	* threequarters (U+00BE): L<<606.0,133.0>--<407.0,134.0>>

	* uni0123 (U+0123): L<<560.0,500.0>--<561.0,3.0>>

	* uni018F (U+018F): L<<48.0,367.0>--<635.0,369.0>>

	* uni1E21 (U+1E21): L<<560.0,500.0>--<561.0,3.0>>

	* uni1E78 (U+1E78): L<<49.0,218.0>--<50.0,700.0>>

	* uni1E78 (U+1E78): L<<572.0,700.0>--<573.0,218.0>>

	* uni1E7A (U+1E7A): L<<49.0,218.0>--<50.0,700.0>>

	* uni1E7A (U+1E7A): L<<572.0,700.0>--<573.0,218.0>>

	* uni1EE4 (U+1EE4): L<<49.0,218.0>--<50.0,700.0>>

	* uni1EE4 (U+1EE4): L<<572.0,700.0>--<573.0,218.0>>

	* uni2074 (U+2074): L<<219.0,528.0>--<20.0,529.0>>

	* uni2084 (U+2084): L<<219.0,133.0>--<20.0,134.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[6] Panamera-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
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

	* IJacute (U+E133): L<<695.0,700.0>--<696.0,195.0>>

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
</div></details><br></div></details><details><summary><b>[7] Panamera-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
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
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dollar (U+0024): X=389.0,Y=702.0 (should be at cap-height 700?)

	* ampersand (U+0026): X=197.5,Y=699.5 (should be at cap-height 700?)

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

	* plusminus (U+00B1): X=130.0,Y=-2.0 (should be at baseline 0?)

	* plusminus (U+00B1): X=671.0,Y=-2.0 (should be at baseline 0?)

	* uni00B5 (U+00B5): X=361.0,Y=1.0 (should be at baseline 0?)

	* agrave (U+00E0): X=300.0,Y=1.5 (should be at baseline 0?)

	* aacute (U+00E1): X=300.0,Y=1.5 (should be at baseline 0?)

	* acircumflex (U+00E2): X=300.0,Y=1.5 (should be at baseline 0?)

	* atilde (U+00E3): X=300.0,Y=1.5 (should be at baseline 0?)

	* adieresis (U+00E4): X=300.0,Y=1.5 (should be at baseline 0?)

	* aring (U+00E5): X=300.0,Y=1.5 (should be at baseline 0?)

	* ae (U+00E6): X=300.0,Y=1.5 (should be at baseline 0?)

	* divide (U+00F7): X=296.0,Y=-1.0 (should be at baseline 0?)

	* divide (U+00F7): X=503.0,Y=-1.0 (should be at baseline 0?)

	* amacron (U+0101): X=300.0,Y=1.5 (should be at baseline 0?)

	* abreve (U+0103): X=300.0,Y=1.5 (should be at baseline 0?)

	* abreve (U+0103): X=301.0,Y=698.0 (should be at cap-height 700?)

	* aogonek (U+0105): X=300.0,Y=1.5 (should be at baseline 0?)

	* ebreve (U+0115): X=298.0,Y=698.0 (should be at cap-height 700?)

	* gbreve (U+011F): X=333.0,Y=698.0 (should be at cap-height 700?)

	* ibreve (U+012D): X=169.0,Y=698.0 (should be at cap-height 700?)

	* obreve (U+014F): X=305.0,Y=698.0 (should be at cap-height 700?)

	* ubreve (U+016D): X=293.0,Y=698.0 (should be at cap-height 700?)

	* aringacute (U+01FB): X=300.0,Y=1.5 (should be at baseline 0?)

	* aeacute (U+01FD): X=300.0,Y=1.5 (should be at baseline 0?)

	* breve (U+02D8): X=402.0,Y=698.0 (should be at cap-height 700?)

	* uni0306 (U+0306): X=402.0,Y=698.0 (should be at cap-height 700?)

	* uni03BC (U+03BC): X=361.0,Y=1.0 (should be at baseline 0?)

	* uni1E1D (U+1E1D): X=298.0,Y=698.0 (should be at cap-height 700?)

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

	* circle (U+25CB): X=210.5,Y=-0.5 (should be at baseline 0?)

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

	* uni0162 (U+0162): L<<374.0,7.0>--<344.0,-42.0>>/B<<344.0,-42.0>-<350.0,-32.0>-<366.0,-24.5>> = 0.5130828175110471

	* uni0163 (U+0163): L<<290.0,7.0>--<260.0,-42.0>>/B<<260.0,-42.0>-<266.0,-32.0>-<282.0,-24.5>> = 0.5130828175110471

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

	* IJacute (U+E133): L<<863.0,700.0>--<864.0,272.0>>

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

	* napostrophe (U+0149): L<<399.0,0.0>--<400.0,292.0>>

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
</div></details><br></div></details><details><summary><b>[6] Panamera-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
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

	* eng (U+014B): L<<78.0,500.0>--<78.0,291.0>>/B<<78.0,291.0>-<89.0,354.0>-<121.5,403.0>> = 9.904183212973862

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

	* m (U+006D): L<<503.0,306.0>--<503.0,303.0>>/B<<503.0,303.0>-<515.0,361.0>-<542.0,400.5>> = 11.689369175439202

	* m (U+006D): L<<78.0,500.0>--<78.0,294.0>>/B<<78.0,294.0>-<90.0,368.0>-<127.5,415.0>> = 9.211026540816649

	* n (U+006E): L<<78.0,500.0>--<78.0,291.0>>/B<<78.0,291.0>-<89.0,354.0>-<121.5,403.0>> = 9.904183212973862

	* nacute (U+0144): L<<78.0,500.0>--<78.0,291.0>>/B<<78.0,291.0>-<89.0,354.0>-<121.5,403.0>> = 9.904183212973862

	* napostrophe (U+0149): L<<78.0,500.0>--<78.0,291.0>>/B<<78.0,291.0>-<89.0,354.0>-<121.5,403.0>> = 9.904183212973862

	* ncaron (U+0148): L<<78.0,500.0>--<78.0,291.0>>/B<<78.0,291.0>-<89.0,354.0>-<121.5,403.0>> = 9.904183212973862

	* nmacronbelow (U+1E49): L<<78.0,500.0>--<78.0,291.0>>/B<<78.0,291.0>-<89.0,354.0>-<121.5,403.0>> = 9.904183212973862

	* ntilde (U+00F1): L<<78.0,500.0>--<78.0,291.0>>/B<<78.0,291.0>-<89.0,354.0>-<121.5,403.0>> = 9.904183212973862

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

	* uni0146 (U+0146): L<<78.0,500.0>--<78.0,291.0>>/B<<78.0,291.0>-<89.0,354.0>-<121.5,403.0>> = 9.904183212973862

	* uni0157 (U+0157): L<<78.0,500.0>--<78.0,315.0>>/B<<78.0,315.0>-<88.0,376.0>-<119.5,418.5>> = 9.30994017498601

	* uni0272 (U+0272): L<<78.0,500.0>--<78.0,291.0>>/B<<78.0,291.0>-<89.0,354.0>-<121.5,403.0>> = 9.904183212973862

	* uni03A9 (U+03A9): B<<619.0,76.5>-<584.0,42.0>-<538.0,33.0>>/L<<538.0,33.0>--<742.0,33.0>> = 11.070202577939344

	* uni03A9 (U+03A9): L<<15.0,33.0>--<225.0,33.0>>/B<<225.0,33.0>-<179.0,44.0>-<146.5,72.5>> = 13.448615051686527

	* uni1E0D (U+1E0D): B<<463.0,406.5>-<491.0,360.0>-<502.0,312.0>>/L<<502.0,312.0>--<494.0,383.0>> = 6.4786609224359895

	* uni1E0D (U+1E0D): L<<494.0,133.0>--<500.0,183.0>>/B<<500.0,183.0>-<489.0,135.0>-<461.0,90.5>> = 6.064635258634921

	* uni1E20 (U+1E20): L<<670.0,0.0>--<670.0,261.0>>/B<<670.0,261.0>-<653.0,141.0>-<581.0,68.0>> = 8.063246165697231

	* uni1E21 (U+1E21): B<<461.0,409.5>-<489.0,365.0>-<500.0,317.0>>/L<<500.0,317.0>--<494.0,367.0>> = 6.064635258634921

	* uni1E21 (U+1E21): L<<494.0,128.0>--<501.0,182.0>>/B<<501.0,182.0>-<489.0,135.0>-<460.5,90.0>> = 6.936676826936219

	* uni1E43 (U+1E43): L<<503.0,306.0>--<503.0,303.0>>/B<<503.0,303.0>-<515.0,361.0>-<542.0,400.5>> = 11.689369175439202

	* uni1E43 (U+1E43): L<<78.0,500.0>--<78.0,294.0>>/B<<78.0,294.0>-<90.0,368.0>-<127.5,415.0>> = 9.211026540816649

	* uni1E45 (U+1E45): L<<78.0,500.0>--<78.0,291.0>>/B<<78.0,291.0>-<89.0,354.0>-<121.5,403.0>> = 9.904183212973862

	* uni1E47 (U+1E47): L<<78.0,500.0>--<78.0,291.0>>/B<<78.0,291.0>-<89.0,354.0>-<121.5,403.0>> = 9.904183212973862

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

	* IJacute (U+E133): L<<673.0,700.0>--<674.0,185.0>>

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
</div></details><br></div></details><details><summary><b>[7] Panamera-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
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
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dollar (U+0024): X=382.0,Y=702.0 (should be at cap-height 700?)

	* ampersand (U+0026): X=396.0,Y=699.0 (should be at cap-height 700?)

	* comma (U+002C): X=229.0,Y=-2.0 (should be at baseline 0?)

	* eight (U+0038): X=281.0,Y=-2.0 (should be at baseline 0?)

	* eight (U+0038): X=281.0,Y=-2.0 (should be at baseline 0?)

	* colon (U+003A): X=56.0,Y=-1.0 (should be at baseline 0?)

	* colon (U+003A): X=214.0,Y=-1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=137.0,Y=2.0 (should be at baseline 0?)

	* semicolon (U+003B): X=78.0,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=174.0,Y=702.0 (should be at cap-height 700?)

	* M (U+004D): X=217.0,Y=701.0 (should be at cap-height 700?)

	* M (U+004D): X=689.0,Y=701.0 (should be at cap-height 700?)

	* f (U+0066): X=7.0,Y=501.0 (should be at x-height 500?)

	* f (U+0066): X=110.0,Y=501.0 (should be at x-height 500?)

	* f (U+0066): X=265.0,Y=501.0 (should be at x-height 500?)

	* f (U+0066): X=391.0,Y=501.0 (should be at x-height 500?)

	* braceleft (U+007B): X=170.0,Y=-1.0 (should be at baseline 0?)

	* braceleft (U+007B): X=350.0,Y=699.0 (should be at cap-height 700?)

	* braceleft (U+007B): X=296.0,Y=-1.0 (should be at baseline 0?)

	* braceright (U+007D): X=199.0,Y=-1.0 (should be at baseline 0?)

	* braceright (U+007D): X=145.0,Y=699.0 (should be at cap-height 700?)

	* braceright (U+007D): X=324.0,Y=-1.0 (should be at baseline 0?)

	* cent (U+00A2): X=290.0,Y=1.0 (should be at baseline 0?)

	* cent (U+00A2): X=333.0,Y=1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=255.5,Y=701.0 (should be at cap-height 700?)

	* uni00B2 (U+00B2): X=229.0,Y=698.0 (should be at cap-height 700?)

	* uni00B2 (U+00B2): X=29.0,Y=698.0 (should be at cap-height 700?)

	* uni00B2 (U+00B2): X=309.0,Y=698.0 (should be at cap-height 700?)

	* uni00B5 (U+00B5): X=331.5,Y=1.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=353.0,Y=-2.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=459.0,Y=702.0 (should be at cap-height 700?)

	* divide (U+00F7): X=271.0,Y=-1.0 (should be at baseline 0?)

	* divide (U+00F7): X=429.0,Y=-1.0 (should be at baseline 0?)

	* florin (U+0192): X=274.0,Y=701.0 (should be at cap-height 700?)

	* Oslashacute (U+01FE): X=353.0,Y=-2.0 (should be at baseline 0?)

	* Oslashacute (U+01FE): X=459.0,Y=702.0 (should be at cap-height 700?)

	* uni03BC (U+03BC): X=331.5,Y=1.0 (should be at baseline 0?)

	* pi (U+03C0): X=95.0,Y=-2.0 (should be at baseline 0?)

	* pi (U+03C0): X=506.0,Y=-2.0 (should be at baseline 0?)

	* pi (U+03C0): X=368.0,Y=-2.0 (should be at baseline 0?)

	* pi (U+03C0): X=233.0,Y=-2.0 (should be at baseline 0?)

	* uni1E42 (U+1E42): X=217.0,Y=701.0 (should be at cap-height 700?)

	* uni1E42 (U+1E42): X=689.0,Y=701.0 (should be at cap-height 700?)

	* quotesinglbase (U+201A): X=229.0,Y=-2.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=492.0,Y=-2.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=229.0,Y=-2.0 (should be at baseline 0?)

	* uni2088 (U+2088): X=170.0,Y=-1.0 (should be at baseline 0?)

	* uni2088 (U+2088): X=170.0,Y=-1.0 (should be at baseline 0?)

	* uni2105 (U+2105): X=465.0,Y=698.0 (should be at cap-height 700?)

	* uni2105 (U+2105): X=171.5,Y=699.5 (should be at cap-height 700?)

	* uni2106 (U+2106): X=465.0,Y=698.0 (should be at cap-height 700?)

	* uni2106 (U+2106): X=171.5,Y=699.5 (should be at cap-height 700?)

	* uni2116 (U+2116): X=909.0,Y=698.0 (should be at cap-height 700?)

	* trademark (U+2122): X=405.0,Y=698.0 (should be at cap-height 700?)

	* trademark (U+2122): X=515.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=702.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=811.0,Y=698.0 (should be at cap-height 700?)

	* trademark (U+2122): X=65.0,Y=698.0 (should be at cap-height 700?)

	* trademark (U+2122): X=352.0,Y=698.0 (should be at cap-height 700?)

	* uni21E7 (U+21E7): X=288.0,Y=1.0 (should be at baseline 0?)

	* uni21E7 (U+21E7): X=482.0,Y=1.0 (should be at baseline 0?)

	* partialdiff (U+2202): X=170.0,Y=1.0 (should be at baseline 0?)

	* circle (U+25CB): X=210.5,Y=-0.5 (should be at baseline 0?)

	* uni25CC (U+25CC): X=295.0,Y=-2.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=295.0,Y=-2.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=532.0,Y=-2.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=532.0,Y=-2.0 (should be at baseline 0?)

	* uni25CF (U+25CF): X=210.5,Y=-0.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<164.0,100.0>--<169.0,44.0>> -> L<<169.0,44.0>--<169.0,0.0>>

	* b (U+0062): L<<169.0,700.0>--<169.0,472.0>> -> L<<169.0,472.0>--<163.0,393.0>>

	* d (U+0064): L<<458.0,0.0>--<458.0,44.0>> -> L<<458.0,44.0>--<463.0,100.0>>

	* d (U+0064): L<<464.0,393.0>--<458.0,472.0>> -> L<<458.0,472.0>--<458.0,700.0>>

	* dcaron (U+010F): L<<458.0,0.0>--<458.0,44.0>> -> L<<458.0,44.0>--<463.0,100.0>>

	* dcaron (U+010F): L<<464.0,393.0>--<458.0,472.0>> -> L<<458.0,472.0>--<458.0,700.0>>

	* dcroat (U+0111): L<<458.0,0.0>--<458.0,44.0>> -> L<<458.0,44.0>--<463.0,100.0>>

	* dcroat (U+0111): L<<464.0,393.0>--<458.0,472.0>> -> L<<458.0,472.0>--<458.0,550.0>>

	* dmacronbelow (U+1E0F): L<<458.0,0.0>--<458.0,44.0>> -> L<<458.0,44.0>--<463.0,100.0>>

	* dmacronbelow (U+1E0F): L<<464.0,393.0>--<458.0,472.0>> -> L<<458.0,472.0>--<458.0,700.0>>

	* exclam (U+0021): L<<233.0,730.0>--<232.0,583.0>> -> L<<232.0,583.0>--<212.0,217.0>>

	* exclam (U+0021): L<<98.0,217.0>--<77.0,583.0>> -> L<<77.0,583.0>--<77.0,730.0>>

	* exclamdown (U+00A1): L<<212.0,323.0>--<232.0,-43.0>> -> L<<232.0,-43.0>--<233.0,-190.0>>

	* exclamdown (U+00A1): L<<77.0,-190.0>--<77.0,-43.0>> -> L<<77.0,-43.0>--<98.0,323.0>>

	* g (U+0067): L<<458.0,6.0>--<458.0,58.0>> -> L<<458.0,58.0>--<462.0,100.0>>

	* g (U+0067): L<<463.0,400.0>--<458.0,456.0>> -> L<<458.0,456.0>--<458.0,500.0>>

	* gbreve (U+011F): L<<458.0,6.0>--<458.0,58.0>> -> L<<458.0,58.0>--<462.0,100.0>>

	* gbreve (U+011F): L<<463.0,400.0>--<458.0,456.0>> -> L<<458.0,456.0>--<458.0,500.0>>

	* gcaron (U+01E7): L<<458.0,6.0>--<458.0,58.0>> -> L<<458.0,58.0>--<462.0,100.0>>

	* gcaron (U+01E7): L<<463.0,400.0>--<458.0,456.0>> -> L<<458.0,456.0>--<458.0,500.0>>

	* gcircumflex (U+011D): L<<458.0,6.0>--<458.0,58.0>> -> L<<458.0,58.0>--<462.0,100.0>>

	* gcircumflex (U+011D): L<<463.0,400.0>--<458.0,456.0>> -> L<<458.0,456.0>--<458.0,500.0>>

	* gdotaccent (U+0121): L<<458.0,6.0>--<458.0,58.0>> -> L<<458.0,58.0>--<462.0,100.0>>

	* gdotaccent (U+0121): L<<463.0,400.0>--<458.0,456.0>> -> L<<458.0,456.0>--<458.0,500.0>>

	* p (U+0070): L<<163.0,107.0>--<169.0,28.0>> -> L<<169.0,28.0>--<169.0,-200.0>>

	* p (U+0070): L<<169.0,500.0>--<169.0,456.0>> -> L<<169.0,456.0>--<164.0,400.0>>

	* q (U+0071): L<<458.0,-200.0>--<458.0,28.0>> -> L<<458.0,28.0>--<464.0,107.0>>

	* q (U+0071): L<<463.0,400.0>--<458.0,456.0>> -> L<<458.0,456.0>--<458.0,500.0>>

	* thorn (U+00FE): L<<157.0,51.0>--<159.0,16.0>> -> L<<159.0,16.0>--<159.0,-200.0>>

	* thorn (U+00FE): L<<159.0,770.0>--<159.0,490.0>> -> L<<159.0,490.0>--<157.0,447.0>>

	* uni0123 (U+0123): L<<458.0,6.0>--<458.0,58.0>> -> L<<458.0,58.0>--<462.0,100.0>>

	* uni0123 (U+0123): L<<463.0,400.0>--<458.0,456.0>> -> L<<458.0,456.0>--<458.0,500.0>>

	* uni1E0D (U+1E0D): L<<458.0,0.0>--<458.0,44.0>> -> L<<458.0,44.0>--<463.0,100.0>>

	* uni1E0D (U+1E0D): L<<464.0,393.0>--<458.0,472.0>> -> L<<458.0,472.0>--<458.0,700.0>>

	* uni1E21 (U+1E21): L<<458.0,6.0>--<458.0,58.0>> -> L<<458.0,58.0>--<462.0,100.0>>

	* uni1E21 (U+1E21): L<<463.0,400.0>--<458.0,456.0>> -> L<<458.0,456.0>--<458.0,500.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* G (U+0047): L<<614.0,0.0>--<614.0,180.0>>/B<<614.0,180.0>-<612.0,130.0>-<587.0,88.0>> = 2.2906100426384346

	* Gbreve (U+011E): L<<614.0,0.0>--<614.0,180.0>>/B<<614.0,180.0>-<612.0,130.0>-<587.0,88.0>> = 2.2906100426384346

	* Gcaron (U+01E6): L<<614.0,0.0>--<614.0,180.0>>/B<<614.0,180.0>-<612.0,130.0>-<587.0,88.0>> = 2.2906100426384346

	* Gcircumflex (U+011C): L<<614.0,0.0>--<614.0,180.0>>/B<<614.0,180.0>-<612.0,130.0>-<587.0,88.0>> = 2.2906100426384346

	* Gdotaccent (U+0120): L<<614.0,0.0>--<614.0,180.0>>/B<<614.0,180.0>-<612.0,130.0>-<587.0,88.0>> = 2.2906100426384346

	* b (U+0062): L<<169.0,472.0>--<163.0,393.0>>/B<<163.0,393.0>-<181.0,450.0>-<224.5,481.0>> = 13.18232842203343

	* d (U+0064): B<<402.5,481.0>-<446.0,450.0>-<464.0,393.0>>/L<<464.0,393.0>--<458.0,472.0>> = 13.18232842203343

	* dcaron (U+010F): B<<402.5,481.0>-<446.0,450.0>-<464.0,393.0>>/L<<464.0,393.0>--<458.0,472.0>> = 13.18232842203343

	* dcroat (U+0111): B<<402.5,481.0>-<446.0,450.0>-<464.0,393.0>>/L<<464.0,393.0>--<458.0,472.0>> = 13.18232842203343

	* dmacronbelow (U+1E0F): B<<402.5,481.0>-<446.0,450.0>-<464.0,393.0>>/L<<464.0,393.0>--<458.0,472.0>> = 13.18232842203343

	* p (U+0070): B<<224.5,19.0>-<181.0,50.0>-<163.0,107.0>>/L<<163.0,107.0>--<169.0,28.0>> = 13.182328422033459

	* q (U+0071): L<<458.0,28.0>--<464.0,107.0>>/B<<464.0,107.0>-<446.0,50.0>-<402.5,19.0>> = 13.182328422033459

	* uni0122 (U+0122): L<<614.0,0.0>--<614.0,180.0>>/B<<614.0,180.0>-<612.0,130.0>-<587.0,88.0>> = 2.2906100426384346

	* uni1E0D (U+1E0D): B<<402.5,481.0>-<446.0,450.0>-<464.0,393.0>>/L<<464.0,393.0>--<458.0,472.0>> = 13.18232842203343

	* uni1E20 (U+1E20): L<<614.0,0.0>--<614.0,180.0>>/B<<614.0,180.0>-<612.0,130.0>-<587.0,88.0>> = 2.2906100426384346 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* D (U+0044): L<<183.0,600.0>--<182.0,100.0>>

	* Dcaron (U+010E): L<<183.0,600.0>--<182.0,100.0>>

	* Dcroat (U+0110): L<<314.0,258.0>--<313.0,100.0>>

	* Dmacronbelow (U+1E0E): L<<183.0,600.0>--<182.0,100.0>>

	* Eth (U+00D0): L<<314.0,258.0>--<313.0,100.0>>

	* IJ (U+0132): L<<803.0,700.0>--<804.0,245.0>>

	* IJacute (U+E133): L<<803.0,700.0>--<804.0,245.0>>

	* J (U+004A): L<<526.0,700.0>--<527.0,245.0>>

	* Jcircumflex (U+0134): L<<526.0,700.0>--<527.0,245.0>>

	* M (U+004D): L<<51.0,700.0>--<217.0,701.0>>

	* M (U+004D): L<<689.0,701.0>--<855.0,700.0>>

	* U (U+0055): L<<38.0,225.0>--<39.0,700.0>>

	* U (U+0055): L<<583.0,700.0>--<584.0,225.0>>

	* Uacute (U+00DA): L<<38.0,225.0>--<39.0,700.0>>

	* Uacute (U+00DA): L<<583.0,700.0>--<584.0,225.0>>

	* Ubreve (U+016C): L<<38.0,225.0>--<39.0,700.0>>

	* Ubreve (U+016C): L<<583.0,700.0>--<584.0,225.0>>

	* Ucircumflex (U+00DB): L<<38.0,225.0>--<39.0,700.0>>

	* Ucircumflex (U+00DB): L<<583.0,700.0>--<584.0,225.0>>

	* Udieresis (U+00DC): L<<38.0,225.0>--<39.0,700.0>>

	* Udieresis (U+00DC): L<<583.0,700.0>--<584.0,225.0>>

	* Ugrave (U+00D9): L<<38.0,225.0>--<39.0,700.0>>

	* Ugrave (U+00D9): L<<583.0,700.0>--<584.0,225.0>>

	* Uhungarumlaut (U+0170): L<<38.0,225.0>--<39.0,700.0>>

	* Uhungarumlaut (U+0170): L<<583.0,700.0>--<584.0,225.0>>

	* Umacron (U+016A): L<<38.0,225.0>--<39.0,700.0>>

	* Umacron (U+016A): L<<583.0,700.0>--<584.0,225.0>>

	* Uogonek (U+0172): L<<38.0,225.0>--<39.0,700.0>>

	* Uogonek (U+0172): L<<583.0,700.0>--<584.0,225.0>>

	* Uring (U+016E): L<<38.0,225.0>--<39.0,700.0>>

	* Uring (U+016E): L<<583.0,700.0>--<584.0,225.0>>

	* Utilde (U+0168): L<<38.0,225.0>--<39.0,700.0>>

	* Utilde (U+0168): L<<583.0,700.0>--<584.0,225.0>>

	* at (U+0040): L<<417.0,337.0>--<277.0,338.0>>

	* b (U+0062): L<<39.0,0.0>--<38.0,700.0>>

	* exclam (U+0021): L<<233.0,730.0>--<232.0,583.0>>

	* exclamdown (U+00A1): L<<232.0,-43.0>--<233.0,-190.0>>

	* g (U+0067): L<<588.0,500.0>--<589.0,6.0>>

	* gbreve (U+011F): L<<588.0,500.0>--<589.0,6.0>>

	* gcaron (U+01E7): L<<588.0,500.0>--<589.0,6.0>>

	* gcircumflex (U+011D): L<<588.0,500.0>--<589.0,6.0>>

	* gdotaccent (U+0121): L<<588.0,500.0>--<589.0,6.0>>

	* p (U+0070): L<<38.0,-200.0>--<39.0,500.0>>

	* q (U+0071): L<<588.0,500.0>--<589.0,-200.0>>

	* thorn (U+00FE): L<<27.0,-200.0>--<28.0,770.0>>

	* uni0123 (U+0123): L<<588.0,500.0>--<589.0,6.0>>

	* uni1E0C (U+1E0C): L<<183.0,600.0>--<182.0,100.0>>

	* uni1E21 (U+1E21): L<<588.0,500.0>--<589.0,6.0>>

	* uni1E42 (U+1E42): L<<51.0,700.0>--<217.0,701.0>>

	* uni1E42 (U+1E42): L<<689.0,701.0>--<855.0,700.0>>

	* uni1E78 (U+1E78): L<<38.0,225.0>--<39.0,700.0>>

	* uni1E78 (U+1E78): L<<583.0,700.0>--<584.0,225.0>>

	* uni1E7A (U+1E7A): L<<38.0,225.0>--<39.0,700.0>>

	* uni1E7A (U+1E7A): L<<583.0,700.0>--<584.0,225.0>>

	* uni1EE4 (U+1EE4): L<<38.0,225.0>--<39.0,700.0>>

	* uni1EE4 (U+1EE4): L<<583.0,700.0>--<584.0,225.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[6] Panamera-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
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
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* exclam (U+0021): L<<131.0,215.0>--<112.0,602.0>> -> L<<112.0,602.0>--<112.0,731.0>>

	* exclam (U+0021): L<<198.0,731.0>--<198.0,602.0>> -> L<<198.0,602.0>--<179.0,215.0>>

	* exclamdown (U+00A1): L<<112.0,-191.0>--<112.0,-62.0>> -> L<<112.0,-62.0>--<131.0,325.0>>

	* exclamdown (U+00A1): L<<179.0,325.0>--<198.0,-62.0>> -> L<<198.0,-62.0>--<198.0,-191.0>>

	* thorn (U+00FE): L<<100.0,799.0>--<100.0,405.0>> -> L<<100.0,405.0>--<95.0,342.0>>

	* thorn (U+00FE): L<<95.0,145.0>--<100.0,76.0>> -> L<<100.0,76.0>--<100.0,-229.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* G (U+0047): L<<649.0,0.0>--<649.0,231.0>>/B<<649.0,231.0>-<641.0,162.0>-<609.5,108.5>> = 6.613460482314774

	* Gbreve (U+011E): L<<649.0,0.0>--<649.0,231.0>>/B<<649.0,231.0>-<641.0,162.0>-<609.5,108.5>> = 6.613460482314774

	* Gcaron (U+01E6): L<<649.0,0.0>--<649.0,231.0>>/B<<649.0,231.0>-<641.0,162.0>-<609.5,108.5>> = 6.613460482314774

	* Gcircumflex (U+011C): L<<649.0,0.0>--<649.0,231.0>>/B<<649.0,231.0>-<641.0,162.0>-<609.5,108.5>> = 6.613460482314774

	* Gdotaccent (U+0120): L<<649.0,0.0>--<649.0,231.0>>/B<<649.0,231.0>-<641.0,162.0>-<609.5,108.5>> = 6.613460482314774

	* b (U+0062): B<<146.5,69.0>-<121.0,106.0>-<108.0,151.0>>/L<<108.0,151.0>--<114.0,100.0>> = 9.403581425332323

	* b (U+0062): L<<114.0,416.0>--<106.0,344.0>>/B<<106.0,344.0>-<119.0,390.0>-<145.0,428.5>> = 9.440561563605446

	* d (U+0064): B<<449.0,428.5>-<475.0,390.0>-<488.0,343.0>>/L<<488.0,343.0>--<480.0,416.0>> = 9.207184996525397

	* d (U+0064): L<<480.0,100.0>--<486.0,151.0>>/B<<486.0,151.0>-<473.0,106.0>-<447.5,69.0>> = 9.403581425332323

	* dcaron (U+010F): B<<449.0,428.5>-<475.0,390.0>-<488.0,343.0>>/L<<488.0,343.0>--<480.0,416.0>> = 9.207184996525397

	* dcaron (U+010F): L<<480.0,100.0>--<486.0,151.0>>/B<<486.0,151.0>-<473.0,106.0>-<447.5,69.0>> = 9.403581425332323

	* dcroat (U+0111): B<<449.0,428.5>-<475.0,390.0>-<488.0,343.0>>/L<<488.0,343.0>--<480.0,416.0>> = 9.207184996525397

	* dcroat (U+0111): L<<480.0,100.0>--<486.0,151.0>>/B<<486.0,151.0>-<473.0,106.0>-<447.5,69.0>> = 9.403581425332323

	* dmacronbelow (U+1E0F): B<<449.0,428.5>-<475.0,390.0>-<488.0,343.0>>/L<<488.0,343.0>--<480.0,416.0>> = 9.207184996525397

	* dmacronbelow (U+1E0F): L<<480.0,100.0>--<486.0,151.0>>/B<<486.0,151.0>-<473.0,106.0>-<447.5,69.0>> = 9.403581425332323

	* f (U+0066): L<<9.0,501.0>--<159.0,501.0>>/B<<159.0,501.0>-<108.0,510.0>-<82.0,543.0>> = 10.00797980144135

	* g (U+0067): B<<447.5,431.0>-<473.0,394.0>-<486.0,349.0>>/L<<486.0,349.0>--<480.0,400.0>> = 9.403581425332323

	* g (U+0067): L<<480.0,101.0>--<486.0,150.0>>/B<<486.0,150.0>-<473.0,105.0>-<446.5,68.0>> = 9.132360826259475

	* gbreve (U+011F): B<<447.5,431.0>-<473.0,394.0>-<486.0,349.0>>/L<<486.0,349.0>--<480.0,400.0>> = 9.403581425332323

	* gbreve (U+011F): L<<480.0,101.0>--<486.0,150.0>>/B<<486.0,150.0>-<473.0,105.0>-<446.5,68.0>> = 9.132360826259475

	* gcaron (U+01E7): B<<447.5,431.0>-<473.0,394.0>-<486.0,349.0>>/L<<486.0,349.0>--<480.0,400.0>> = 9.403581425332323

	* gcaron (U+01E7): L<<480.0,101.0>--<486.0,150.0>>/B<<486.0,150.0>-<473.0,105.0>-<446.5,68.0>> = 9.132360826259475

	* gcircumflex (U+011D): B<<447.5,431.0>-<473.0,394.0>-<486.0,349.0>>/L<<486.0,349.0>--<480.0,400.0>> = 9.403581425332323

	* gcircumflex (U+011D): L<<480.0,101.0>--<486.0,150.0>>/B<<486.0,150.0>-<473.0,105.0>-<446.5,68.0>> = 9.132360826259475

	* gdotaccent (U+0121): B<<447.5,431.0>-<473.0,394.0>-<486.0,349.0>>/L<<486.0,349.0>--<480.0,400.0>> = 9.403581425332323

	* gdotaccent (U+0121): L<<480.0,101.0>--<486.0,150.0>>/B<<486.0,150.0>-<473.0,105.0>-<446.5,68.0>> = 9.132360826259475

	* p (U+0070): B<<145.0,71.5>-<119.0,110.0>-<106.0,157.0>>/L<<106.0,157.0>--<114.0,84.0>> = 9.207184996525397

	* p (U+0070): L<<114.0,400.0>--<108.0,349.0>>/B<<108.0,349.0>-<121.0,394.0>-<146.5,431.0>> = 9.403581425332323

	* q (U+0071): B<<447.5,431.0>-<473.0,394.0>-<486.0,349.0>>/L<<486.0,349.0>--<480.0,400.0>> = 9.403581425332323

	* q (U+0071): L<<480.0,84.0>--<488.0,156.0>>/B<<488.0,156.0>-<475.0,110.0>-<449.0,71.5>> = 9.440561563605407

	* r (U+0072): L<<115.0,500.0>--<115.0,351.0>>/B<<115.0,351.0>-<126.0,401.0>-<155.5,435.5>> = 12.407418527400745

	* racute (U+0155): L<<115.0,500.0>--<115.0,351.0>>/B<<115.0,351.0>-<126.0,401.0>-<155.5,435.5>> = 12.407418527400745

	* rcaron (U+0159): L<<115.0,500.0>--<115.0,351.0>>/B<<115.0,351.0>-<126.0,401.0>-<155.5,435.5>> = 12.407418527400745

	* rmacronbelow (U+1E5F): L<<115.0,500.0>--<115.0,351.0>>/B<<115.0,351.0>-<126.0,401.0>-<155.5,435.5>> = 12.407418527400745

	* thorn (U+00FE): B<<132.5,67.0>-<107.0,104.0>-<95.0,145.0>>/L<<95.0,145.0>--<100.0,76.0>> = 12.169228685156268

	* thorn (U+00FE): L<<100.0,405.0>--<95.0,342.0>>/B<<95.0,342.0>-<106.0,384.0>-<131.5,421.5>> = 10.13862062954336

	* uni0122 (U+0122): L<<649.0,0.0>--<649.0,231.0>>/B<<649.0,231.0>-<641.0,162.0>-<609.5,108.5>> = 6.613460482314774

	* uni0123 (U+0123): B<<447.5,431.0>-<473.0,394.0>-<486.0,349.0>>/L<<486.0,349.0>--<480.0,400.0>> = 9.403581425332323

	* uni0123 (U+0123): L<<480.0,101.0>--<486.0,150.0>>/B<<486.0,150.0>-<473.0,105.0>-<446.5,68.0>> = 9.132360826259475

	* uni0157 (U+0157): L<<115.0,500.0>--<115.0,351.0>>/B<<115.0,351.0>-<126.0,401.0>-<155.5,435.5>> = 12.407418527400745

	* uni1E0D (U+1E0D): B<<449.0,428.5>-<475.0,390.0>-<488.0,343.0>>/L<<488.0,343.0>--<480.0,416.0>> = 9.207184996525397

	* uni1E0D (U+1E0D): L<<480.0,100.0>--<486.0,151.0>>/B<<486.0,151.0>-<473.0,106.0>-<447.5,69.0>> = 9.403581425332323

	* uni1E20 (U+1E20): L<<649.0,0.0>--<649.0,231.0>>/B<<649.0,231.0>-<641.0,162.0>-<609.5,108.5>> = 6.613460482314774

	* uni1E21 (U+1E21): B<<447.5,431.0>-<473.0,394.0>-<486.0,349.0>>/L<<486.0,349.0>--<480.0,400.0>> = 9.403581425332323

	* uni1E21 (U+1E21): L<<480.0,101.0>--<486.0,150.0>>/B<<486.0,150.0>-<473.0,105.0>-<446.5,68.0>> = 9.132360826259475

	* uni1E5B (U+1E5B): L<<115.0,500.0>--<115.0,351.0>>/B<<115.0,351.0>-<126.0,401.0>-<155.5,435.5>> = 12.407418527400745 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* IJ (U+0132): L<<722.0,700.0>--<723.0,207.0>>

	* IJacute (U+E133): L<<722.0,700.0>--<723.0,207.0>>

	* J (U+004A): L<<497.0,700.0>--<498.0,207.0>>

	* Jcircumflex (U+0134): L<<497.0,700.0>--<498.0,207.0>>

	* R (U+0052): L<<244.0,375.0>--<120.0,374.0>>

	* Racute (U+0154): L<<244.0,375.0>--<120.0,374.0>>

	* Rcaron (U+0158): L<<244.0,375.0>--<120.0,374.0>>

	* Rmacronbelow (U+1E5E): L<<244.0,375.0>--<120.0,374.0>>

	* U (U+0055): L<<55.0,215.0>--<56.0,700.0>>

	* U (U+0055): L<<566.0,700.0>--<567.0,215.0>>

	* Uacute (U+00DA): L<<55.0,215.0>--<56.0,700.0>>

	* Uacute (U+00DA): L<<566.0,700.0>--<567.0,215.0>>

	* Ubreve (U+016C): L<<55.0,215.0>--<56.0,700.0>>

	* Ubreve (U+016C): L<<566.0,700.0>--<567.0,215.0>>

	* Ucircumflex (U+00DB): L<<55.0,215.0>--<56.0,700.0>>

	* Ucircumflex (U+00DB): L<<566.0,700.0>--<567.0,215.0>>

	* Udieresis (U+00DC): L<<55.0,215.0>--<56.0,700.0>>

	* Udieresis (U+00DC): L<<566.0,700.0>--<567.0,215.0>>

	* Ugrave (U+00D9): L<<55.0,215.0>--<56.0,700.0>>

	* Ugrave (U+00D9): L<<566.0,700.0>--<567.0,215.0>>

	* Uhungarumlaut (U+0170): L<<55.0,215.0>--<56.0,700.0>>

	* Uhungarumlaut (U+0170): L<<566.0,700.0>--<567.0,215.0>>

	* Umacron (U+016A): L<<55.0,215.0>--<56.0,700.0>>

	* Umacron (U+016A): L<<566.0,700.0>--<567.0,215.0>>

	* Uogonek (U+0172): L<<55.0,215.0>--<56.0,700.0>>

	* Uogonek (U+0172): L<<566.0,700.0>--<567.0,215.0>>

	* Uring (U+016E): L<<55.0,215.0>--<56.0,700.0>>

	* Uring (U+016E): L<<566.0,700.0>--<567.0,215.0>>

	* Utilde (U+0168): L<<55.0,215.0>--<56.0,700.0>>

	* Utilde (U+0168): L<<566.0,700.0>--<567.0,215.0>>

	* b (U+0062): L<<48.0,0.0>--<47.0,700.0>>

	* four (U+0034): L<<371.0,231.0>--<33.0,232.0>>

	* g (U+0067): L<<546.0,500.0>--<547.0,1.0>>

	* gbreve (U+011F): L<<546.0,500.0>--<547.0,1.0>>

	* gcaron (U+01E7): L<<546.0,500.0>--<547.0,1.0>>

	* gcircumflex (U+011D): L<<546.0,500.0>--<547.0,1.0>>

	* gdotaccent (U+0121): L<<546.0,500.0>--<547.0,1.0>>

	* p (U+0070): L<<47.0,-200.0>--<48.0,500.0>>

	* q (U+0071): L<<546.0,500.0>--<547.0,-200.0>>

	* thorn (U+00FE): L<<34.0,-229.0>--<35.0,799.0>>

	* uni0123 (U+0123): L<<546.0,500.0>--<547.0,1.0>>

	* uni0156 (U+0156): L<<244.0,375.0>--<120.0,374.0>>

	* uni018F (U+018F): L<<40.0,357.0>--<646.0,358.0>>

	* uni1E21 (U+1E21): L<<546.0,500.0>--<547.0,1.0>>

	* uni1E5A (U+1E5A): L<<244.0,375.0>--<120.0,374.0>>

	* uni1E78 (U+1E78): L<<55.0,215.0>--<56.0,700.0>>

	* uni1E78 (U+1E78): L<<566.0,700.0>--<567.0,215.0>>

	* uni1E7A (U+1E7A): L<<55.0,215.0>--<56.0,700.0>>

	* uni1E7A (U+1E7A): L<<566.0,700.0>--<567.0,215.0>>

	* uni1EE4 (U+1EE4): L<<55.0,215.0>--<56.0,700.0>>

	* uni1EE4 (U+1EE4): L<<566.0,700.0>--<567.0,215.0>>

	* yen (U+00A5): L<<105.0,339.0>--<251.0,340.0>>

	* yen (U+00A5): L<<347.0,340.0>--<489.0,339.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 6 | 32 | 716 | 43 | 618 | 0 |
| 0% | 0% | 2% | 51% | 3% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
