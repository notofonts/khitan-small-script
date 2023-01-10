## Fontbakery report

Fontbakery version: 0.8.11a8

<details><summary><b>[18] NotoFangsongKSSVertical-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/line_breaks">com.google.fonts/check/name/line_breaks</a>)</summary><div>


* 🔥 **FAIL** Name entry DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts CJK vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics">com.google.fonts/check/cjk_vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoAscender is "800" it should be 880 [code: bad-OS/2.sTypoAscender]
* 🔥 **FAIL** OS/2.sTypoDescender is "-200" it should be -120 [code: bad-OS/2.sTypoDescender]
* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.1-1.4x of the font's upm. This font has 2.0x [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table records must not have trailing spaces. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/name/trailing_spaces">com.google.fonts/check/name/trailing_spaces</a>)</summary><div>


* 🔥 **FAIL** Name table record with key = (3, 1, 1033, 10) has trailing spaces that must be removed: 'The typefa[...]im JIANG.
' [code: trailing-space]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 600 font units wide, non-breaking space named (uni00A0) is 260 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/example.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoFangsongKSSVertical-Regular/googlefonts/ttf/NotoFangsongKSSVertical-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/example.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">๰</span></li>


<pre>Expected: None</pre>



<pre>Got     : .notdef=0+500</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 500 3000" transform="matrix(1 0 0 -1 0 0)">
<path d="M410.0,800.0L410.0,-200.0L93.0,-200.0L93.0,800.0L410.0,800.0ZM333.0,663.0L267.0,663.0L267.0,700.0L333.0,700.0L333.0,733.0L168.0,733.0L168.0,700.0L233.0,700.0L233.0,663.0L167.0,663.0L167.0,630.0L333.0,630.0L333.0,663.0ZM167.0,500.0L333.0,500.0L333.0,534.0L267.0,534.0L267.0,604.0L167.0,604.0L167.0,500.0ZM233.0,570.0L233.0,534.0L200.0,534.0L200.0,570.0L233.0,570.0ZM167.0,370.0L267.0,370.0L267.0,440.0L333.0,440.0L333.0,473.0L167.0,473.0L167.0,440.0L233.0,440.0L233.0,403.0L167.0,403.0L167.0,370.0ZM300.0,347.0L167.0,347.0L167.0,313.0L333.0,313.0L333.0,413.0L300.0,413.0L300.0,347.0ZM200.0,291.0L167.0,291.0L167.0,178.0L333.0,178.0L333.0,291.0L233.0,291.0L233.0,235.0L267.0,235.0L267.0,258.0L300.0,258.0L300.0,211.0L200.0,211.0L200.0,291.0ZM333.0,118.0L167.0,118.0L167.0,5.0L333.0,5.0L333.0,118.0ZM300.0,85.0L300.0,38.0L200.0,38.0L200.0,85.0L300.0,85.0ZM333.0,-98.0L231.0,-98.0L301.0,-51.0L333.0,-51.0L333.0,-18.0L167.0,-18.0L167.0,-51.0L237.0,-51.0L167.0,-98.0L167.0,-131.0L333.0,-131.0L333.0,-98.0Z"  transform="translate(0, 1200)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Fangsong KSS Vertical' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain less than 40 CJK characters? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_not_enough_glyphs">com.google.fonts/check/cjk_not_enough_glyphs</a>)</summary><div>


* ⚠ **WARN** There are only 9 CJK glyphs when there needs to be at least 40 in order to support the smallest CJK writing system, Hangul.
The following CJK glyphs were found:
['uni4E39', 'uni4EFF', 'uni4F53', 'uni5951', 'uni5B57', 'uni5B8B', 'uni5C0F', 'uni6B4C', 'uni8C37']
Please check that these glyphs have the correct unicodes. [code: cjk-not-enough-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain chws and vchw features? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/cjk_chws_feature">com.google.fonts/check/cjk_chws_feature</a>)</summary><div>


* ⚠ **WARN** chws feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-chws-feature]
* ⚠ **WARN** vchw feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-vchw-feature]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u18B07 (U+18B07): L<<358.0,-3.0>--<429.0,-32.0>> -> L<<429.0,-32.0>--<474.0,-48.0>>

	* u18B07 (U+18B07): L<<496.0,597.0>--<496.0,608.0>> -> L<<496.0,608.0>--<496.0,613.0>>

	* u18B07 (U+18B07): L<<497.0,338.0>--<496.0,597.0>> -> L<<496.0,597.0>--<496.0,608.0>>

	* u18B38 (U+18B38): L<<490.0,-32.0>--<490.0,28.0>> -> L<<490.0,28.0>--<491.0,344.0>>

	* u18B39 (U+18B39): L<<470.0,-49.0>--<470.0,28.0>> -> L<<470.0,28.0>--<471.0,344.0>>

	* u18B3E (U+18B3E): L<<190.0,-2.0>--<191.0,131.0>> -> L<<191.0,131.0>--<190.0,262.0>>

	* u18B41 (U+18B41): L<<719.0,396.0>--<605.0,384.0>> -> L<<605.0,384.0>--<533.0,376.0>>

	* u18B57 (U+18B57): L<<419.0,93.0>--<394.0,70.0>> -> L<<394.0,70.0>--<369.0,46.0>>

	* u18B5A (U+18B5A): L<<253.0,335.0>--<444.0,347.0>> -> L<<444.0,347.0>--<448.0,347.0>>

	* u18B60 (U+18B60): L<<846.0,402.0>--<668.0,392.0>> -> L<<668.0,392.0>--<600.0,388.0>> 

	* And 80 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* u18B10 (U+18B10): B<<780.0,481.0>-<741.0,439.0>-<742.0,440.0>>/B<<742.0,440.0>-<708.0,407.0>-<673.5,378.5>> = 0.8550973962662667

	* u18B3C (U+18B3C): B<<209.0,307.0>-<250.0,266.0>-<294.0,237.0>>/B<<294.0,237.0>-<293.0,238.0>-<420.0,152.0>> = 11.611486423888481

	* u18B81 (U+18B81): B<<838.0,326.0>-<799.0,284.0>-<800.0,285.0>>/B<<800.0,285.0>-<716.0,203.0>-<644.0,155.0>> = 0.6902771978645523

	* u18BB1 (U+18BB1): B<<455.0,362.0>-<431.0,360.0>-<435.0,360.0>>/B<<435.0,360.0>-<380.0,355.0>-<313.0,341.0>> = 5.1944289077348

	* u18BEA (U+18BEA): B<<598.0,608.0>-<508.0,600.0>-<524.0,601.0>>/B<<524.0,601.0>-<390.0,588.0>-<347.0,583.0>> = 1.9648704030421524

	* u18BEB (U+18BEB): B<<599.0,608.0>-<502.0,600.0>-<522.0,601.0>>/B<<522.0,601.0>-<493.0,598.0>-<427.0,592.0>> = 3.0437358876587015

	* u18C0A (U+18C0A): B<<899.0,514.0>-<801.0,505.0>-<807.0,506.0>>/B<<807.0,506.0>-<688.0,496.0>-<578.0,485.0>> = 4.6588364489565155

	* u18C0B (U+18C0B): B<<859.0,514.0>-<761.0,505.0>-<767.0,506.0>>/B<<767.0,506.0>-<641.0,496.0>-<524.0,484.0>> = 4.924549700118923

	* u18C65 (U+18C65): B<<773.0,592.0>-<755.0,571.0>-<757.0,573.0>>/B<<757.0,573.0>-<706.0,512.0>-<660.0,464.0>> = 5.102165252358147

	* u18CB2 (U+18CB2): B<<371.0,355.0>-<458.0,365.0>-<453.0,364.0>>/B<<453.0,364.0>-<478.0,367.0>-<492.5,375.0>> = 4.46715906138917 

	* And u18CB3 (U+18CB3): B<<377.0,617.0>-<328.0,611.0>-<333.0,612.0>>/B<<333.0,612.0>-<303.0,610.0>-<254.0,602.0>> = 7.495857639729836 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* u18B03 (U+18B03): L<<531.0,182.0>--<530.0,-136.0>>

	* u18B07 (U+18B07): L<<497.0,338.0>--<496.0,597.0>>

	* u18B0B (U+18B0B): L<<527.0,175.0>--<526.0,-149.0>>

	* u18B14 (U+18B14): L<<551.0,485.0>--<550.0,168.0>>

	* u18B15 (U+18B15): L<<531.0,485.0>--<530.0,168.0>>

	* u18B17 (U+18B17): L<<545.0,378.0>--<544.0,175.0>>

	* u18B18 (U+18B18): L<<535.0,391.0>--<534.0,224.0>>

	* u18B19 (U+18B19): L<<534.0,426.0>--<533.0,303.0>>

	* u18B1E (U+18B1E): L<<529.0,154.0>--<528.0,-113.0>>

	* u18B1F (U+18B1F): L<<827.0,128.0>--<826.0,-148.0>> 

	* And 81 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 7 | 11 | 117 | 7 | 91 | 0 |
| 0% | 3% | 5% | 50% | 3% | 39% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
