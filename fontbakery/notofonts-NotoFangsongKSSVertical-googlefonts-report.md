## FontBakery report

fontbakery version: 0.12.10



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoFangsongKSSVertical-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoAscender value should be greater than 931, but got 880 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[16] NotoFangsongKSSVertical-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1777, but got 1300 instead</p>
 [code: ascent]



* 🔥 **FAIL** <p>OS/2.usWinDescent value 700 is too large. It should be less than double the yMin. Current absolute yMin value is 240</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (880) and hhea ascent (1300) must be equal.</p>
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
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to uni0237</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to J</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), u16FE4 (U+16FE4), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C), uni0326 (U+0326), uni0327 (U+0327) and uni0328 (U+0328)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 579:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoFangsongKSSVertical/googlefonts/ttf does not have an article.</p>
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
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, old-permic, tai-le, tifinagh, todhri, duployan, syriac, canadian-aboriginal, malayalam, coptic, hebrew</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+25A1 WHITE SQUARE: try adding symbols</li>
<li>U+2B1A DOTTED SQUARE: try adding symbols</li>
<li>U+4E39 CJK UNIFIED IDEOGRAPH-4E39: try adding one of: chinese-hongkong, japanese, chinese-traditional, chinese-simplified</li>
<li>U+4EFF CJK UNIFIED IDEOGRAPH-4EFF: try adding one of: chinese-hongkong, chinese-traditional, chinese-simplified</li>
<li>U+4F53 CJK UNIFIED IDEOGRAPH-4F53: try adding one of: chinese-hongkong, japanese, chinese-traditional, chinese-simplified</li>
<li>U+5951 CJK UNIFIED IDEOGRAPH-5951: try adding one of: chinese-hongkong, japanese, chinese-traditional, chinese-simplified</li>
<li>U+5B57 CJK UNIFIED IDEOGRAPH-5B57: try adding one of: chinese-hongkong, japanese, chinese-traditional, chinese-simplified</li>
<li>U+5B8B CJK UNIFIED IDEOGRAPH-5B8B: try adding one of: chinese-hongkong, japanese, chinese-traditional, chinese-simplified</li>
<li>U+5C0F CJK UNIFIED IDEOGRAPH-5C0F: try adding one of: chinese-hongkong, japanese, chinese-traditional, chinese-simplified</li>
<li>U+6B4C CJK UNIFIED IDEOGRAPH-6B4C: try adding one of: chinese-hongkong, japanese, chinese-traditional, chinese-simplified</li>
<li>U+8C37 CJK UNIFIED IDEOGRAPH-8C37: try adding one of: chinese-hongkong, japanese, chinese-traditional, chinese-simplified</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>khitan-small-script</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Name ID 6 'NotoFangsongKSSVertical-Regular' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms.</p>
 [code: nameid6-too-long]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Lugbara (Latn, 2,200,000 speakers), Dii (Latn, 71,000 speakers), Vute (Latn, 21,000 speakers), Han (Latn, 6 speakers), Southern Kisi (Latn, 360,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mfumte (Latn, 79,000 speakers), Mundani (Latn, 34,000 speakers), Makaa (Latn, 221,000 speakers), Yala (Latn, 200,000 speakers), Kom (Latn, 360,685 speakers), Ejagham (Latn, 120,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Aghem (Latn, 38,843 speakers), Teke-Ebo (Latn, 260,000 speakers), Sar (Latn, 500,000 speakers), Avokaya (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers), Dutch (Latn, 31,709,104 speakers), Dan (Latn, 1,099,244 speakers), Bafut (Latn, 158,146 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Navajo (Latn, 166,319 speakers), Mango (Latn, 77,000 speakers), Basaa (Latn, 332,940 speakers), Nateni (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Zapotec (Latn, 490,000 speakers), Heiltsuk (Latn, 300 speakers), Ma’di (Latn, 584,000 speakers), Ekpeye (Latn, 226,000 speakers), Koonzime (Latn, 40,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Igbo (Latn, 27,823,640 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Fur (Latn, 1,230,163 speakers), Gulay (Latn, 250,478 speakers), Nzakara (Latn, 50,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Kaska (Latn, 125 speakers), Cicipu (Latn, 44,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* u18B10 (U+18B10): B&lt;&lt;780.0,481.0&gt;-&lt;741.0,439.0&gt;-&lt;742.0,440.0&gt;&gt;/B&lt;&lt;742.0,440.0&gt;-&lt;708.0,407.0&gt;-&lt;673.5,378.5&gt;&gt; = 0.8550973962662667

* u18B10.001: B&lt;&lt;280.0,481.0&gt;-&lt;241.0,439.0&gt;-&lt;242.0,440.0&gt;&gt;/B&lt;&lt;242.0,440.0&gt;-&lt;208.0,407.0&gt;-&lt;173.5,378.5&gt;&gt; = 0.8550973962662667

* u18B10.002: B&lt;&lt;780.0,481.0&gt;-&lt;741.0,439.0&gt;-&lt;742.0,440.0&gt;&gt;/B&lt;&lt;742.0,440.0&gt;-&lt;708.0,407.0&gt;-&lt;673.5,378.5&gt;&gt; = 0.8550973962662667

* u18B10.003: B&lt;&lt;780.0,1481.0&gt;-&lt;741.0,1439.0&gt;-&lt;742.0,1440.0&gt;&gt;/B&lt;&lt;742.0,1440.0&gt;-&lt;708.0,1407.0&gt;-&lt;673.5,1378.5&gt;&gt; = 0.8550973962662667

* u18B3C (U+18B3C): B&lt;&lt;209.0,307.0&gt;-&lt;250.0,266.0&gt;-&lt;294.0,237.0&gt;&gt;/B&lt;&lt;294.0,237.0&gt;-&lt;293.0,238.0&gt;-&lt;420.0,152.0&gt;&gt; = 11.611486423888481

* u18B3C.001: B&lt;&lt;-291.0,307.0&gt;-&lt;-250.0,266.0&gt;-&lt;-206.0,237.0&gt;&gt;/B&lt;&lt;-206.0,237.0&gt;-&lt;-207.0,238.0&gt;-&lt;-80.0,152.0&gt;&gt; = 11.611486423888481

* u18B3C.002: B&lt;&lt;209.0,307.0&gt;-&lt;250.0,266.0&gt;-&lt;294.0,237.0&gt;&gt;/B&lt;&lt;294.0,237.0&gt;-&lt;293.0,238.0&gt;-&lt;420.0,152.0&gt;&gt; = 11.611486423888481

* u18B3C.003: B&lt;&lt;209.0,1307.0&gt;-&lt;250.0,1266.0&gt;-&lt;294.0,1237.0&gt;&gt;/B&lt;&lt;294.0,1237.0&gt;-&lt;293.0,1238.0&gt;-&lt;420.0,1152.0&gt;&gt; = 11.611486423888481

* u18B81 (U+18B81): B&lt;&lt;838.0,326.0&gt;-&lt;799.0,284.0&gt;-&lt;800.0,285.0&gt;&gt;/B&lt;&lt;800.0,285.0&gt;-&lt;716.0,203.0&gt;-&lt;644.0,155.0&gt;&gt; = 0.6902771978645523

* u18B81.001: B&lt;&lt;338.0,326.0&gt;-&lt;299.0,284.0&gt;-&lt;300.0,285.0&gt;&gt;/B&lt;&lt;300.0,285.0&gt;-&lt;216.0,203.0&gt;-&lt;144.0,155.0&gt;&gt; = 0.6902771978645523

* u18B81.002: B&lt;&lt;838.0,326.0&gt;-&lt;799.0,284.0&gt;-&lt;800.0,285.0&gt;&gt;/B&lt;&lt;800.0,285.0&gt;-&lt;716.0,203.0&gt;-&lt;644.0,155.0&gt;&gt; = 0.6902771978645523

* u18B81.003: B&lt;&lt;838.0,1326.0&gt;-&lt;799.0,1284.0&gt;-&lt;800.0,1285.0&gt;&gt;/B&lt;&lt;800.0,1285.0&gt;-&lt;716.0,1203.0&gt;-&lt;644.0,1155.0&gt;&gt; = 0.6902771978645523

* u18BB1 (U+18BB1): B&lt;&lt;455.0,362.0&gt;-&lt;431.0,360.0&gt;-&lt;435.0,360.0&gt;&gt;/B&lt;&lt;435.0,360.0&gt;-&lt;380.0,355.0&gt;-&lt;313.0,341.0&gt;&gt; = 5.1944289077348

* u18BB1.001: B&lt;&lt;-45.0,362.0&gt;-&lt;-69.0,360.0&gt;-&lt;-65.0,360.0&gt;&gt;/B&lt;&lt;-65.0,360.0&gt;-&lt;-120.0,355.0&gt;-&lt;-187.0,341.0&gt;&gt; = 5.1944289077348

* u18BB1.002: B&lt;&lt;455.0,362.0&gt;-&lt;431.0,360.0&gt;-&lt;435.0,360.0&gt;&gt;/B&lt;&lt;435.0,360.0&gt;-&lt;380.0,355.0&gt;-&lt;313.0,341.0&gt;&gt; = 5.1944289077348

* u18BB1.003: B&lt;&lt;455.0,1362.0&gt;-&lt;431.0,1360.0&gt;-&lt;435.0,1360.0&gt;&gt;/B&lt;&lt;435.0,1360.0&gt;-&lt;380.0,1355.0&gt;-&lt;313.0,1341.0&gt;&gt; = 5.1944289077348

* u18BEA (U+18BEA): B&lt;&lt;598.0,608.0&gt;-&lt;508.0,600.0&gt;-&lt;524.0,601.0&gt;&gt;/B&lt;&lt;524.0,601.0&gt;-&lt;390.0,588.0&gt;-&lt;347.0,583.0&gt;&gt; = 1.9648704030421524

* u18BEA.001: B&lt;&lt;98.0,608.0&gt;-&lt;8.0,600.0&gt;-&lt;24.0,601.0&gt;&gt;/B&lt;&lt;24.0,601.0&gt;-&lt;-110.0,588.0&gt;-&lt;-153.0,583.0&gt;&gt; = 1.9648704030421524

* u18BEA.002: B&lt;&lt;598.0,608.0&gt;-&lt;508.0,600.0&gt;-&lt;524.0,601.0&gt;&gt;/B&lt;&lt;524.0,601.0&gt;-&lt;390.0,588.0&gt;-&lt;347.0,583.0&gt;&gt; = 1.9648704030421524

* u18BEA.003: B&lt;&lt;598.0,1608.0&gt;-&lt;508.0,1600.0&gt;-&lt;524.0,1601.0&gt;&gt;/B&lt;&lt;524.0,1601.0&gt;-&lt;390.0,1588.0&gt;-&lt;347.0,1583.0&gt;&gt; = 1.9648704030421524

* u18BEB (U+18BEB): B&lt;&lt;599.0,608.0&gt;-&lt;502.0,600.0&gt;-&lt;522.0,601.0&gt;&gt;/B&lt;&lt;522.0,601.0&gt;-&lt;493.0,598.0&gt;-&lt;427.0,592.0&gt;&gt; = 3.0437358876587015

* u18BEB.001: B&lt;&lt;99.0,608.0&gt;-&lt;2.0,600.0&gt;-&lt;22.0,601.0&gt;&gt;/B&lt;&lt;22.0,601.0&gt;-&lt;-7.0,598.0&gt;-&lt;-73.0,592.0&gt;&gt; = 3.0437358876587015

* u18BEB.002: B&lt;&lt;599.0,608.0&gt;-&lt;502.0,600.0&gt;-&lt;522.0,601.0&gt;&gt;/B&lt;&lt;522.0,601.0&gt;-&lt;493.0,598.0&gt;-&lt;427.0,592.0&gt;&gt; = 3.0437358876587015

* u18BEB.003: B&lt;&lt;599.0,1608.0&gt;-&lt;502.0,1600.0&gt;-&lt;522.0,1601.0&gt;&gt;/B&lt;&lt;522.0,1601.0&gt;-&lt;493.0,1598.0&gt;-&lt;427.0,1592.0&gt;&gt; = 3.0437358876587015

* u18C0A (U+18C0A): B&lt;&lt;899.0,514.0&gt;-&lt;801.0,505.0&gt;-&lt;807.0,506.0&gt;&gt;/B&lt;&lt;807.0,506.0&gt;-&lt;688.0,496.0&gt;-&lt;578.0,485.0&gt;&gt; = 4.6588364489565155

* u18C0A.001: B&lt;&lt;399.0,514.0&gt;-&lt;301.0,505.0&gt;-&lt;307.0,506.0&gt;&gt;/B&lt;&lt;307.0,506.0&gt;-&lt;188.0,496.0&gt;-&lt;78.0,485.0&gt;&gt; = 4.6588364489565155

* u18C0A.002: B&lt;&lt;899.0,514.0&gt;-&lt;801.0,505.0&gt;-&lt;807.0,506.0&gt;&gt;/B&lt;&lt;807.0,506.0&gt;-&lt;688.0,496.0&gt;-&lt;578.0,485.0&gt;&gt; = 4.6588364489565155

* u18C0A.003: B&lt;&lt;899.0,1514.0&gt;-&lt;801.0,1505.0&gt;-&lt;807.0,1506.0&gt;&gt;/B&lt;&lt;807.0,1506.0&gt;-&lt;688.0,1496.0&gt;-&lt;578.0,1485.0&gt;&gt; = 4.6588364489565155

* u18C0B (U+18C0B): B&lt;&lt;859.0,514.0&gt;-&lt;761.0,505.0&gt;-&lt;767.0,506.0&gt;&gt;/B&lt;&lt;767.0,506.0&gt;-&lt;641.0,496.0&gt;-&lt;524.0,484.0&gt;&gt; = 4.924549700118923

* u18C0B.001: B&lt;&lt;359.0,514.0&gt;-&lt;261.0,505.0&gt;-&lt;267.0,506.0&gt;&gt;/B&lt;&lt;267.0,506.0&gt;-&lt;141.0,496.0&gt;-&lt;24.0,484.0&gt;&gt; = 4.924549700118923

* u18C0B.002: B&lt;&lt;859.0,514.0&gt;-&lt;761.0,505.0&gt;-&lt;767.0,506.0&gt;&gt;/B&lt;&lt;767.0,506.0&gt;-&lt;641.0,496.0&gt;-&lt;524.0,484.0&gt;&gt; = 4.924549700118923

* u18C0B.003: B&lt;&lt;859.0,1514.0&gt;-&lt;761.0,1505.0&gt;-&lt;767.0,1506.0&gt;&gt;/B&lt;&lt;767.0,1506.0&gt;-&lt;641.0,1496.0&gt;-&lt;524.0,1484.0&gt;&gt; = 4.924549700118923

* u18C65 (U+18C65): B&lt;&lt;773.0,592.0&gt;-&lt;755.0,571.0&gt;-&lt;757.0,573.0&gt;&gt;/B&lt;&lt;757.0,573.0&gt;-&lt;706.0,512.0&gt;-&lt;660.0,464.0&gt;&gt; = 5.102165252358147

* u18C65.001: B&lt;&lt;273.0,592.0&gt;-&lt;255.0,571.0&gt;-&lt;257.0,573.0&gt;&gt;/B&lt;&lt;257.0,573.0&gt;-&lt;206.0,512.0&gt;-&lt;160.0,464.0&gt;&gt; = 5.102165252358147

* u18C65.002: B&lt;&lt;773.0,592.0&gt;-&lt;755.0,571.0&gt;-&lt;757.0,573.0&gt;&gt;/B&lt;&lt;757.0,573.0&gt;-&lt;706.0,512.0&gt;-&lt;660.0,464.0&gt;&gt; = 5.102165252358147

* u18C65.003: B&lt;&lt;773.0,1592.0&gt;-&lt;755.0,1571.0&gt;-&lt;757.0,1573.0&gt;&gt;/B&lt;&lt;757.0,1573.0&gt;-&lt;706.0,1512.0&gt;-&lt;660.0,1464.0&gt;&gt; = 5.102165252358147

* u18CB2 (U+18CB2): B&lt;&lt;371.0,355.0&gt;-&lt;458.0,365.0&gt;-&lt;453.0,364.0&gt;&gt;/B&lt;&lt;453.0,364.0&gt;-&lt;478.0,367.0&gt;-&lt;492.5,375.0&gt;&gt; = 4.46715906138917

* u18CB2.001: B&lt;&lt;-129.0,355.0&gt;-&lt;-42.0,365.0&gt;-&lt;-47.0,364.0&gt;&gt;/B&lt;&lt;-47.0,364.0&gt;-&lt;-22.0,367.0&gt;-&lt;-7.5,375.0&gt;&gt; = 4.46715906138917

* u18CB2.002: B&lt;&lt;371.0,355.0&gt;-&lt;458.0,365.0&gt;-&lt;453.0,364.0&gt;&gt;/B&lt;&lt;453.0,364.0&gt;-&lt;478.0,367.0&gt;-&lt;492.5,375.0&gt;&gt; = 4.46715906138917

* u18CB2.003: B&lt;&lt;371.0,1355.0&gt;-&lt;458.0,1365.0&gt;-&lt;453.0,1364.0&gt;&gt;/B&lt;&lt;453.0,1364.0&gt;-&lt;478.0,1367.0&gt;-&lt;492.5,1375.0&gt;&gt; = 4.46715906138917

* u18CB3 (U+18CB3): B&lt;&lt;377.0,617.0&gt;-&lt;328.0,611.0&gt;-&lt;333.0,612.0&gt;&gt;/B&lt;&lt;333.0,612.0&gt;-&lt;303.0,610.0&gt;-&lt;254.0,602.0&gt;&gt; = 7.495857639729836

* u18CB3.001: B&lt;&lt;-123.0,617.0&gt;-&lt;-172.0,611.0&gt;-&lt;-167.0,612.0&gt;&gt;/B&lt;&lt;-167.0,612.0&gt;-&lt;-197.0,610.0&gt;-&lt;-246.0,602.0&gt;&gt; = 7.495857639729836

* u18CB3.002: B&lt;&lt;377.0,617.0&gt;-&lt;328.0,611.0&gt;-&lt;333.0,612.0&gt;&gt;/B&lt;&lt;333.0,612.0&gt;-&lt;303.0,610.0&gt;-&lt;254.0,602.0&gt;&gt; = 7.495857639729836

* u18CB3.003: B&lt;&lt;377.0,1617.0&gt;-&lt;328.0,1611.0&gt;-&lt;333.0,1612.0&gt;&gt;/B&lt;&lt;333.0,1612.0&gt;-&lt;303.0,1610.0&gt;-&lt;254.0,1602.0&gt;&gt; = 7.495857639729836
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* u18B03 (U+18B03): L&lt;&lt;531.0,182.0&gt;--&lt;530.0,-136.0&gt;&gt;

* u18B03.001: L&lt;&lt;31.0,182.0&gt;--&lt;30.0,-136.0&gt;&gt;

* u18B03.002: L&lt;&lt;531.0,182.0&gt;--&lt;530.0,-136.0&gt;&gt;

* u18B03.003: L&lt;&lt;531.0,1182.0&gt;--&lt;530.0,864.0&gt;&gt;

* u18B07 (U+18B07): L&lt;&lt;497.0,338.0&gt;--&lt;496.0,597.0&gt;&gt;

* u18B07.001: L&lt;&lt;-3.0,338.0&gt;--&lt;-4.0,597.0&gt;&gt;

* u18B07.002: L&lt;&lt;497.0,338.0&gt;--&lt;496.0,597.0&gt;&gt;

* u18B07.003: L&lt;&lt;497.0,1338.0&gt;--&lt;496.0,1597.0&gt;&gt;

* u18B0B (U+18B0B): L&lt;&lt;527.0,175.0&gt;--&lt;526.0,-149.0&gt;&gt;

* u18B0B.001: L&lt;&lt;27.0,175.0&gt;--&lt;26.0,-149.0&gt;&gt;

* u18B0B.002: L&lt;&lt;527.0,175.0&gt;--&lt;526.0,-149.0&gt;&gt;

* u18B0B.003: L&lt;&lt;527.0,1175.0&gt;--&lt;526.0,851.0&gt;&gt;

* u18B14 (U+18B14): L&lt;&lt;551.0,485.0&gt;--&lt;550.0,168.0&gt;&gt;

* u18B14.001: L&lt;&lt;51.0,485.0&gt;--&lt;50.0,168.0&gt;&gt;

* u18B14.002: L&lt;&lt;551.0,485.0&gt;--&lt;550.0,168.0&gt;&gt;

* u18B14.003: L&lt;&lt;551.0,1485.0&gt;--&lt;550.0,1168.0&gt;&gt;

* u18B15 (U+18B15): L&lt;&lt;531.0,485.0&gt;--&lt;530.0,168.0&gt;&gt;

* u18B15.001: L&lt;&lt;31.0,485.0&gt;--&lt;30.0,168.0&gt;&gt;

* u18B15.002: L&lt;&lt;531.0,485.0&gt;--&lt;530.0,168.0&gt;&gt;

* u18B15.003: L&lt;&lt;531.0,1485.0&gt;--&lt;530.0,1168.0&gt;&gt;

* u18B17 (U+18B17): L&lt;&lt;545.0,378.0&gt;--&lt;544.0,175.0&gt;&gt;

* u18B17.001: L&lt;&lt;45.0,378.0&gt;--&lt;44.0,175.0&gt;&gt;

* u18B17.002: L&lt;&lt;545.0,378.0&gt;--&lt;544.0,175.0&gt;&gt;

* u18B17.003: L&lt;&lt;545.0,1378.0&gt;--&lt;544.0,1175.0&gt;&gt;

* u18B18 (U+18B18): L&lt;&lt;535.0,391.0&gt;--&lt;534.0,224.0&gt;&gt;

* u18B18.001: L&lt;&lt;35.0,391.0&gt;--&lt;34.0,224.0&gt;&gt;

* u18B18.002: L&lt;&lt;535.0,391.0&gt;--&lt;534.0,224.0&gt;&gt;

* u18B18.003: L&lt;&lt;535.0,1391.0&gt;--&lt;534.0,1224.0&gt;&gt;

* u18B19 (U+18B19): L&lt;&lt;534.0,426.0&gt;--&lt;533.0,303.0&gt;&gt;

* u18B19.001: L&lt;&lt;34.0,426.0&gt;--&lt;33.0,303.0&gt;&gt;

* u18B19.002: L&lt;&lt;534.0,426.0&gt;--&lt;533.0,303.0&gt;&gt;

* u18B19.003: L&lt;&lt;534.0,1426.0&gt;--&lt;533.0,1303.0&gt;&gt;

* u18B1E (U+18B1E): L&lt;&lt;529.0,154.0&gt;--&lt;528.0,-113.0&gt;&gt;

* u18B1E.001: L&lt;&lt;29.0,154.0&gt;--&lt;28.0,-113.0&gt;&gt;

* u18B1E.002: L&lt;&lt;529.0,154.0&gt;--&lt;528.0,-113.0&gt;&gt;

* u18B1E.003: L&lt;&lt;529.0,1154.0&gt;--&lt;528.0,887.0&gt;&gt;

* u18B1F (U+18B1F): L&lt;&lt;827.0,128.0&gt;--&lt;826.0,-148.0&gt;&gt;

* u18B1F.001: L&lt;&lt;327.0,128.0&gt;--&lt;326.0,-148.0&gt;&gt;

* u18B1F.002: L&lt;&lt;827.0,128.0&gt;--&lt;826.0,-148.0&gt;&gt;

* u18B1F.003: L&lt;&lt;827.0,1128.0&gt;--&lt;826.0,852.0&gt;&gt;

* u18B22 (U+18B22): L&lt;&lt;367.0,-25.0&gt;--&lt;365.0,341.0&gt;&gt;

* u18B22.001: L&lt;&lt;-133.0,-25.0&gt;--&lt;-135.0,341.0&gt;&gt;

* u18B22.002: L&lt;&lt;367.0,-25.0&gt;--&lt;365.0,341.0&gt;&gt;

* u18B22.003: L&lt;&lt;367.0,975.0&gt;--&lt;365.0,1341.0&gt;&gt;

* u18B36 (U+18B36): L&lt;&lt;528.0,579.0&gt;--&lt;527.0,394.0&gt;&gt;

* u18B36.001: L&lt;&lt;28.0,579.0&gt;--&lt;27.0,394.0&gt;&gt;

* u18B36.002: L&lt;&lt;528.0,579.0&gt;--&lt;527.0,394.0&gt;&gt;

* u18B36.003: L&lt;&lt;528.0,1579.0&gt;--&lt;527.0,1394.0&gt;&gt;

* u18B38 (U+18B38): L&lt;&lt;490.0,28.0&gt;--&lt;491.0,344.0&gt;&gt;

* u18B38.001: L&lt;&lt;-10.0,28.0&gt;--&lt;-9.0,344.0&gt;&gt;

* u18B38.002: L&lt;&lt;490.0,28.0&gt;--&lt;491.0,344.0&gt;&gt;

* u18B38.003: L&lt;&lt;490.0,1028.0&gt;--&lt;491.0,1344.0&gt;&gt;

* u18B39 (U+18B39): L&lt;&lt;470.0,28.0&gt;--&lt;471.0,344.0&gt;&gt;

* u18B39.001: L&lt;&lt;-30.0,28.0&gt;--&lt;-29.0,344.0&gt;&gt;

* u18B39.002: L&lt;&lt;470.0,28.0&gt;--&lt;471.0,344.0&gt;&gt;

* u18B39.003: L&lt;&lt;470.0,1028.0&gt;--&lt;471.0,1344.0&gt;&gt;

* u18B3A (U+18B3A): L&lt;&lt;527.0,508.0&gt;--&lt;526.0,210.0&gt;&gt;

* u18B3A.001: L&lt;&lt;27.0,508.0&gt;--&lt;26.0,210.0&gt;&gt;

* u18B3A.002: L&lt;&lt;527.0,508.0&gt;--&lt;526.0,210.0&gt;&gt;

* u18B3A.003: L&lt;&lt;527.0,1508.0&gt;--&lt;526.0,1210.0&gt;&gt;

* u18B3E (U+18B3E): L&lt;&lt;190.0,-2.0&gt;--&lt;191.0,131.0&gt;&gt;

* u18B3E (U+18B3E): L&lt;&lt;191.0,131.0&gt;--&lt;190.0,262.0&gt;&gt;

* u18B3E.001: L&lt;&lt;-309.0,131.0&gt;--&lt;-310.0,262.0&gt;&gt;

* u18B3E.001: L&lt;&lt;-310.0,-2.0&gt;--&lt;-309.0,131.0&gt;&gt;

* u18B3E.002: L&lt;&lt;190.0,-2.0&gt;--&lt;191.0,131.0&gt;&gt;

* u18B3E.002: L&lt;&lt;191.0,131.0&gt;--&lt;190.0,262.0&gt;&gt;

* u18B3E.003: L&lt;&lt;190.0,998.0&gt;--&lt;191.0,1131.0&gt;&gt;

* u18B3E.003: L&lt;&lt;191.0,1131.0&gt;--&lt;190.0,1262.0&gt;&gt;

* u18B3F (U+18B3F): L&lt;&lt;537.0,488.0&gt;--&lt;536.0,211.0&gt;&gt;

* u18B3F.001: L&lt;&lt;37.0,488.0&gt;--&lt;36.0,211.0&gt;&gt;

* u18B3F.002: L&lt;&lt;537.0,488.0&gt;--&lt;536.0,211.0&gt;&gt;

* u18B3F.003: L&lt;&lt;537.0,1488.0&gt;--&lt;536.0,1211.0&gt;&gt;

* u18B40 (U+18B40): L&lt;&lt;524.0,536.0&gt;--&lt;523.0,365.0&gt;&gt;

* u18B40.001: L&lt;&lt;24.0,536.0&gt;--&lt;23.0,365.0&gt;&gt;

* u18B40.002: L&lt;&lt;524.0,536.0&gt;--&lt;523.0,365.0&gt;&gt;

* u18B40.003: L&lt;&lt;524.0,1536.0&gt;--&lt;523.0,1365.0&gt;&gt;

* u18B46 (U+18B46): L&lt;&lt;535.0,411.0&gt;--&lt;534.0,215.0&gt;&gt;

* u18B46.001: L&lt;&lt;35.0,411.0&gt;--&lt;34.0,215.0&gt;&gt;

* u18B46.002: L&lt;&lt;535.0,411.0&gt;--&lt;534.0,215.0&gt;&gt;

* u18B46.003: L&lt;&lt;535.0,1411.0&gt;--&lt;534.0,1215.0&gt;&gt;

* u18B47 (U+18B47): L&lt;&lt;524.0,413.0&gt;--&lt;525.0,-43.0&gt;&gt;

* u18B47.001: L&lt;&lt;24.0,413.0&gt;--&lt;25.0,-43.0&gt;&gt;

* u18B47.002: L&lt;&lt;524.0,413.0&gt;--&lt;525.0,-43.0&gt;&gt;

* u18B47.003: L&lt;&lt;524.0,1413.0&gt;--&lt;525.0,957.0&gt;&gt;

* u18B4B (U+18B4B): L&lt;&lt;876.0,581.0&gt;--&lt;875.0,211.0&gt;&gt;

* u18B4B.001: L&lt;&lt;376.0,581.0&gt;--&lt;375.0,211.0&gt;&gt;

* u18B4B.002: L&lt;&lt;876.0,581.0&gt;--&lt;875.0,211.0&gt;&gt;

* u18B4B.003: L&lt;&lt;876.0,1581.0&gt;--&lt;875.0,1211.0&gt;&gt;

* u18B53 (U+18B53): L&lt;&lt;437.0,571.0&gt;--&lt;436.0,349.0&gt;&gt;

* u18B53.001: L&lt;&lt;-63.0,571.0&gt;--&lt;-64.0,349.0&gt;&gt;

* u18B53.002: L&lt;&lt;437.0,571.0&gt;--&lt;436.0,349.0&gt;&gt;

* u18B53.003: L&lt;&lt;437.0,1571.0&gt;--&lt;436.0,1349.0&gt;&gt;

* u18B54 (U+18B54): L&lt;&lt;464.0,-25.0&gt;--&lt;465.0,315.0&gt;&gt;

* u18B54.001: L&lt;&lt;-36.0,-25.0&gt;--&lt;-35.0,315.0&gt;&gt;

* u18B54.002: L&lt;&lt;464.0,-25.0&gt;--&lt;465.0,315.0&gt;&gt;

* u18B54.003: L&lt;&lt;464.0,975.0&gt;--&lt;465.0,1315.0&gt;&gt;

* u18B55 (U+18B55): L&lt;&lt;464.0,23.0&gt;--&lt;465.0,335.0&gt;&gt;

* u18B55.001: L&lt;&lt;-36.0,23.0&gt;--&lt;-35.0,335.0&gt;&gt;

* u18B55.002: L&lt;&lt;464.0,23.0&gt;--&lt;465.0,335.0&gt;&gt;

* u18B55.003: L&lt;&lt;464.0,1023.0&gt;--&lt;465.0,1335.0&gt;&gt;

* u18B5C (U+18B5C): L&lt;&lt;539.0,538.0&gt;--&lt;538.0,193.0&gt;&gt;

* u18B5C.001: L&lt;&lt;39.0,538.0&gt;--&lt;38.0,193.0&gt;&gt;

* u18B5C.002: L&lt;&lt;539.0,538.0&gt;--&lt;538.0,193.0&gt;&gt;

* u18B5C.003: L&lt;&lt;539.0,1538.0&gt;--&lt;538.0,1193.0&gt;&gt;

* u18B64 (U+18B64): L&lt;&lt;370.0,516.0&gt;--&lt;369.0,360.0&gt;&gt;

* u18B64 (U+18B64): L&lt;&lt;661.0,543.0&gt;--&lt;660.0,389.0&gt;&gt;

* u18B64.001: L&lt;&lt;-130.0,516.0&gt;--&lt;-131.0,360.0&gt;&gt;

* u18B64.001: L&lt;&lt;161.0,543.0&gt;--&lt;160.0,389.0&gt;&gt;

* u18B64.002: L&lt;&lt;370.0,516.0&gt;--&lt;369.0,360.0&gt;&gt;

* u18B64.002: L&lt;&lt;661.0,543.0&gt;--&lt;660.0,389.0&gt;&gt;

* u18B64.003: L&lt;&lt;370.0,1516.0&gt;--&lt;369.0,1360.0&gt;&gt;

* u18B64.003: L&lt;&lt;661.0,1543.0&gt;--&lt;660.0,1389.0&gt;&gt;

* u18B69 (U+18B69): L&lt;&lt;349.0,387.0&gt;--&lt;347.0,46.0&gt;&gt;

* u18B69 (U+18B69): L&lt;&lt;689.0,414.0&gt;--&lt;686.0,-23.0&gt;&gt;

* u18B69.001: L&lt;&lt;-151.0,387.0&gt;--&lt;-153.0,46.0&gt;&gt;

* u18B69.001: L&lt;&lt;189.0,414.0&gt;--&lt;186.0,-23.0&gt;&gt;

* u18B69.002: L&lt;&lt;349.0,387.0&gt;--&lt;347.0,46.0&gt;&gt;

* u18B69.002: L&lt;&lt;689.0,414.0&gt;--&lt;686.0,-23.0&gt;&gt;

* u18B69.003: L&lt;&lt;349.0,1387.0&gt;--&lt;347.0,1046.0&gt;&gt;

* u18B69.003: L&lt;&lt;689.0,1414.0&gt;--&lt;686.0,977.0&gt;&gt;

* u18B80 (U+18B80): L&lt;&lt;814.0,177.0&gt;--&lt;813.0,62.0&gt;&gt;

* u18B80.001: L&lt;&lt;314.0,177.0&gt;--&lt;313.0,62.0&gt;&gt;

* u18B80.002: L&lt;&lt;814.0,177.0&gt;--&lt;813.0,62.0&gt;&gt;

* u18B80.003: L&lt;&lt;814.0,1177.0&gt;--&lt;813.0,1062.0&gt;&gt;

* u18B95 (U+18B95): L&lt;&lt;448.0,517.0&gt;--&lt;447.0,-26.0&gt;&gt;

* u18B95 (U+18B95): L&lt;&lt;589.0,-16.0&gt;--&lt;590.0,436.0&gt;&gt;

* u18B95 (U+18B95): L&lt;&lt;652.0,567.0&gt;--&lt;651.0,-11.0&gt;&gt;

* u18B95.001: L&lt;&lt;-52.0,517.0&gt;--&lt;-53.0,-26.0&gt;&gt;

* u18B95.001: L&lt;&lt;152.0,567.0&gt;--&lt;151.0,-11.0&gt;&gt;

* u18B95.001: L&lt;&lt;89.0,-16.0&gt;--&lt;90.0,436.0&gt;&gt;

* u18B95.002: L&lt;&lt;448.0,517.0&gt;--&lt;447.0,-26.0&gt;&gt;

* u18B95.002: L&lt;&lt;589.0,-16.0&gt;--&lt;590.0,436.0&gt;&gt;

* u18B95.002: L&lt;&lt;652.0,567.0&gt;--&lt;651.0,-11.0&gt;&gt;

* u18B95.003: L&lt;&lt;448.0,1517.0&gt;--&lt;447.0,974.0&gt;&gt;

* u18B95.003: L&lt;&lt;589.0,984.0&gt;--&lt;590.0,1436.0&gt;&gt;

* u18B95.003: L&lt;&lt;652.0,1567.0&gt;--&lt;651.0,989.0&gt;&gt;

* u18B98 (U+18B98): L&lt;&lt;426.0,573.0&gt;--&lt;425.0,-43.0&gt;&gt;

* u18B98 (U+18B98): L&lt;&lt;568.0,-32.0&gt;--&lt;569.0,444.0&gt;&gt;

* u18B98 (U+18B98): L&lt;&lt;631.0,275.0&gt;--&lt;630.0,-27.0&gt;&gt;

* u18B98.001: L&lt;&lt;-74.0,573.0&gt;--&lt;-75.0,-43.0&gt;&gt;

* u18B98.001: L&lt;&lt;131.0,275.0&gt;--&lt;130.0,-27.0&gt;&gt;

* u18B98.001: L&lt;&lt;68.0,-32.0&gt;--&lt;69.0,444.0&gt;&gt;

* u18B98.002: L&lt;&lt;426.0,573.0&gt;--&lt;425.0,-43.0&gt;&gt;

* u18B98.002: L&lt;&lt;568.0,-32.0&gt;--&lt;569.0,444.0&gt;&gt;

* u18B98.002: L&lt;&lt;631.0,275.0&gt;--&lt;630.0,-27.0&gt;&gt;

* u18B98.003: L&lt;&lt;426.0,1573.0&gt;--&lt;425.0,957.0&gt;&gt;

* u18B98.003: L&lt;&lt;568.0,968.0&gt;--&lt;569.0,1444.0&gt;&gt;

* u18B98.003: L&lt;&lt;631.0,1275.0&gt;--&lt;630.0,973.0&gt;&gt;

* u18B9C (U+18B9C): L&lt;&lt;467.0,-25.0&gt;--&lt;468.0,436.0&gt;&gt;

* u18B9C (U+18B9C): L&lt;&lt;530.0,567.0&gt;--&lt;529.0,-21.0&gt;&gt;

* u18B9C.001: L&lt;&lt;-33.0,-25.0&gt;--&lt;-32.0,436.0&gt;&gt;

* u18B9C.001: L&lt;&lt;30.0,567.0&gt;--&lt;29.0,-21.0&gt;&gt;

* u18B9C.002: L&lt;&lt;467.0,-25.0&gt;--&lt;468.0,436.0&gt;&gt;

* u18B9C.002: L&lt;&lt;530.0,567.0&gt;--&lt;529.0,-21.0&gt;&gt;

* u18B9C.003: L&lt;&lt;467.0,975.0&gt;--&lt;468.0,1436.0&gt;&gt;

* u18B9C.003: L&lt;&lt;530.0,1567.0&gt;--&lt;529.0,979.0&gt;&gt;

* u18B9D (U+18B9D): L&lt;&lt;477.0,-14.0&gt;--&lt;478.0,439.0&gt;&gt;

* u18B9D (U+18B9D): L&lt;&lt;540.0,569.0&gt;--&lt;539.0,-9.0&gt;&gt;

* u18B9D.001: L&lt;&lt;-23.0,-14.0&gt;--&lt;-22.0,439.0&gt;&gt;

* u18B9D.001: L&lt;&lt;40.0,569.0&gt;--&lt;39.0,-9.0&gt;&gt;

* u18B9D.002: L&lt;&lt;477.0,-14.0&gt;--&lt;478.0,439.0&gt;&gt;

* u18B9D.002: L&lt;&lt;540.0,569.0&gt;--&lt;539.0,-9.0&gt;&gt;

* u18B9D.003: L&lt;&lt;477.0,986.0&gt;--&lt;478.0,1439.0&gt;&gt;

* u18B9D.003: L&lt;&lt;540.0,1569.0&gt;--&lt;539.0,991.0&gt;&gt;

* u18B9E (U+18B9E): L&lt;&lt;477.0,-13.0&gt;--&lt;478.0,439.0&gt;&gt;

* u18B9E (U+18B9E): L&lt;&lt;540.0,569.0&gt;--&lt;539.0,-8.0&gt;&gt;

* u18B9E.001: L&lt;&lt;-23.0,-13.0&gt;--&lt;-22.0,439.0&gt;&gt;

* u18B9E.001: L&lt;&lt;40.0,569.0&gt;--&lt;39.0,-8.0&gt;&gt;

* u18B9E.002: L&lt;&lt;477.0,-13.0&gt;--&lt;478.0,439.0&gt;&gt;

* u18B9E.002: L&lt;&lt;540.0,569.0&gt;--&lt;539.0,-8.0&gt;&gt;

* u18B9E.003: L&lt;&lt;477.0,987.0&gt;--&lt;478.0,1439.0&gt;&gt;

* u18B9E.003: L&lt;&lt;540.0,1569.0&gt;--&lt;539.0,992.0&gt;&gt;

* u18B9F (U+18B9F): L&lt;&lt;493.0,-24.0&gt;--&lt;494.0,383.0&gt;&gt;

* u18B9F (U+18B9F): L&lt;&lt;556.0,387.0&gt;--&lt;555.0,-19.0&gt;&gt;

* u18B9F.001: L&lt;&lt;-7.0,-24.0&gt;--&lt;-6.0,383.0&gt;&gt;

* u18B9F.001: L&lt;&lt;56.0,387.0&gt;--&lt;55.0,-19.0&gt;&gt;

* u18B9F.002: L&lt;&lt;493.0,-24.0&gt;--&lt;494.0,383.0&gt;&gt;

* u18B9F.002: L&lt;&lt;556.0,387.0&gt;--&lt;555.0,-19.0&gt;&gt;

* u18B9F.003: L&lt;&lt;493.0,976.0&gt;--&lt;494.0,1383.0&gt;&gt;

* u18B9F.003: L&lt;&lt;556.0,1387.0&gt;--&lt;555.0,981.0&gt;&gt;

* u18BA2 (U+18BA2): L&lt;&lt;469.0,-51.0&gt;--&lt;470.0,292.0&gt;&gt;

* u18BA2 (U+18BA2): L&lt;&lt;532.0,296.0&gt;--&lt;531.0,-46.0&gt;&gt;

* u18BA2.001: L&lt;&lt;-31.0,-51.0&gt;--&lt;-30.0,292.0&gt;&gt;

* u18BA2.001: L&lt;&lt;32.0,296.0&gt;--&lt;31.0,-46.0&gt;&gt;

* u18BA2.002: L&lt;&lt;469.0,-51.0&gt;--&lt;470.0,292.0&gt;&gt;

* u18BA2.002: L&lt;&lt;532.0,296.0&gt;--&lt;531.0,-46.0&gt;&gt;

* u18BA2.003: L&lt;&lt;469.0,949.0&gt;--&lt;470.0,1292.0&gt;&gt;

* u18BA2.003: L&lt;&lt;532.0,1296.0&gt;--&lt;531.0,954.0&gt;&gt;

* u18BA7 (U+18BA7): L&lt;&lt;467.0,-25.0&gt;--&lt;468.0,436.0&gt;&gt;

* u18BA7 (U+18BA7): L&lt;&lt;530.0,567.0&gt;--&lt;529.0,177.0&gt;&gt;

* u18BA7.001: L&lt;&lt;-33.0,-25.0&gt;--&lt;-32.0,436.0&gt;&gt;

* u18BA7.001: L&lt;&lt;30.0,567.0&gt;--&lt;29.0,177.0&gt;&gt;

* u18BA7.002: L&lt;&lt;467.0,-25.0&gt;--&lt;468.0,436.0&gt;&gt;

* u18BA7.002: L&lt;&lt;530.0,567.0&gt;--&lt;529.0,177.0&gt;&gt;

* u18BA7.003: L&lt;&lt;467.0,975.0&gt;--&lt;468.0,1436.0&gt;&gt;

* u18BA7.003: L&lt;&lt;530.0,1567.0&gt;--&lt;529.0,1177.0&gt;&gt;

* u18BA8 (U+18BA8): L&lt;&lt;459.0,20.0&gt;--&lt;460.0,450.0&gt;&gt;

* u18BA8 (U+18BA8): L&lt;&lt;522.0,572.0&gt;--&lt;521.0,206.0&gt;&gt;

* u18BA8.001: L&lt;&lt;-41.0,20.0&gt;--&lt;-40.0,450.0&gt;&gt;

* u18BA8.001: L&lt;&lt;22.0,572.0&gt;--&lt;21.0,206.0&gt;&gt;

* u18BA8.002: L&lt;&lt;459.0,20.0&gt;--&lt;460.0,450.0&gt;&gt;

* u18BA8.002: L&lt;&lt;522.0,572.0&gt;--&lt;521.0,206.0&gt;&gt;

* u18BA8.003: L&lt;&lt;459.0,1020.0&gt;--&lt;460.0,1450.0&gt;&gt;

* u18BA8.003: L&lt;&lt;522.0,1572.0&gt;--&lt;521.0,1206.0&gt;&gt;

* u18BAA (U+18BAA): L&lt;&lt;477.0,-14.0&gt;--&lt;478.0,439.0&gt;&gt;

* u18BAA (U+18BAA): L&lt;&lt;540.0,569.0&gt;--&lt;539.0,191.0&gt;&gt;

* u18BAA.001: L&lt;&lt;-23.0,-14.0&gt;--&lt;-22.0,439.0&gt;&gt;

* u18BAA.001: L&lt;&lt;40.0,569.0&gt;--&lt;39.0,191.0&gt;&gt;

* u18BAA.002: L&lt;&lt;477.0,-14.0&gt;--&lt;478.0,439.0&gt;&gt;

* u18BAA.002: L&lt;&lt;540.0,569.0&gt;--&lt;539.0,191.0&gt;&gt;

* u18BAA.003: L&lt;&lt;477.0,986.0&gt;--&lt;478.0,1439.0&gt;&gt;

* u18BAA.003: L&lt;&lt;540.0,1569.0&gt;--&lt;539.0,1191.0&gt;&gt;

* u18BAB (U+18BAB): L&lt;&lt;145.0,29.0&gt;--&lt;146.0,148.0&gt;&gt;

* u18BAB (U+18BAB): L&lt;&lt;146.0,148.0&gt;--&lt;145.0,268.0&gt;&gt;

* u18BAB.001: L&lt;&lt;-354.0,148.0&gt;--&lt;-355.0,268.0&gt;&gt;

* u18BAB.001: L&lt;&lt;-355.0,29.0&gt;--&lt;-354.0,148.0&gt;&gt;

* u18BAB.002: L&lt;&lt;145.0,29.0&gt;--&lt;146.0,148.0&gt;&gt;

* u18BAB.002: L&lt;&lt;146.0,148.0&gt;--&lt;145.0,268.0&gt;&gt;

* u18BAB.003: L&lt;&lt;145.0,1029.0&gt;--&lt;146.0,1148.0&gt;&gt;

* u18BAB.003: L&lt;&lt;146.0,1148.0&gt;--&lt;145.0,1268.0&gt;&gt;

* u18BC4 (U+18BC4): L&lt;&lt;208.0,555.0&gt;--&lt;207.0,424.0&gt;&gt;

* u18BC4.001: L&lt;&lt;-292.0,555.0&gt;--&lt;-293.0,424.0&gt;&gt;

* u18BC4.002: L&lt;&lt;208.0,555.0&gt;--&lt;207.0,424.0&gt;&gt;

* u18BC4.003: L&lt;&lt;208.0,1555.0&gt;--&lt;207.0,1424.0&gt;&gt;

* u18BC5 (U+18BC5): L&lt;&lt;208.0,555.0&gt;--&lt;207.0,424.0&gt;&gt;

* u18BC5.001: L&lt;&lt;-292.0,555.0&gt;--&lt;-293.0,424.0&gt;&gt;

* u18BC5.002: L&lt;&lt;208.0,555.0&gt;--&lt;207.0,424.0&gt;&gt;

* u18BC5.003: L&lt;&lt;208.0,1555.0&gt;--&lt;207.0,1424.0&gt;&gt;

* u18BC7 (U+18BC7): L&lt;&lt;530.0,475.0&gt;--&lt;529.0,211.0&gt;&gt;

* u18BC7.001: L&lt;&lt;30.0,475.0&gt;--&lt;29.0,211.0&gt;&gt;

* u18BC7.002: L&lt;&lt;530.0,475.0&gt;--&lt;529.0,211.0&gt;&gt;

* u18BC7.003: L&lt;&lt;530.0,1475.0&gt;--&lt;529.0,1211.0&gt;&gt;

* u18BC9 (U+18BC9): L&lt;&lt;530.0,459.0&gt;--&lt;529.0,211.0&gt;&gt;

* u18BC9.001: L&lt;&lt;30.0,459.0&gt;--&lt;29.0,211.0&gt;&gt;

* u18BC9.002: L&lt;&lt;530.0,459.0&gt;--&lt;529.0,211.0&gt;&gt;

* u18BC9.003: L&lt;&lt;530.0,1459.0&gt;--&lt;529.0,1211.0&gt;&gt;

* u18BCA (U+18BCA): L&lt;&lt;261.0,357.0&gt;--&lt;260.0,197.0&gt;&gt;

* u18BCA.001: L&lt;&lt;-239.0,357.0&gt;--&lt;-240.0,197.0&gt;&gt;

* u18BCA.002: L&lt;&lt;261.0,357.0&gt;--&lt;260.0,197.0&gt;&gt;

* u18BCA.003: L&lt;&lt;261.0,1357.0&gt;--&lt;260.0,1197.0&gt;&gt;

* u18BCC (U+18BCC): L&lt;&lt;229.0,345.0&gt;--&lt;230.0,182.0&gt;&gt;

* u18BCC.001: L&lt;&lt;-271.0,345.0&gt;--&lt;-270.0,182.0&gt;&gt;

* u18BCC.002: L&lt;&lt;229.0,345.0&gt;--&lt;230.0,182.0&gt;&gt;

* u18BCC.003: L&lt;&lt;229.0,1345.0&gt;--&lt;230.0,1182.0&gt;&gt;

* u18BD0 (U+18BD0): L&lt;&lt;184.0,332.0&gt;--&lt;183.0,177.0&gt;&gt;

* u18BD0 (U+18BD0): L&lt;&lt;467.0,-38.0&gt;--&lt;468.0,445.0&gt;&gt;

* u18BD0 (U+18BD0): L&lt;&lt;530.0,585.0&gt;--&lt;529.0,-34.0&gt;&gt;

* u18BD0 (U+18BD0): L&lt;&lt;698.0,353.0&gt;--&lt;697.0,205.0&gt;&gt;

* u18BD0.001: L&lt;&lt;-316.0,332.0&gt;--&lt;-317.0,177.0&gt;&gt;

* u18BD0.001: L&lt;&lt;-33.0,-38.0&gt;--&lt;-32.0,445.0&gt;&gt;

* u18BD0.001: L&lt;&lt;198.0,353.0&gt;--&lt;197.0,205.0&gt;&gt;

* u18BD0.001: L&lt;&lt;30.0,585.0&gt;--&lt;29.0,-34.0&gt;&gt;

* u18BD0.002: L&lt;&lt;184.0,332.0&gt;--&lt;183.0,177.0&gt;&gt;

* u18BD0.002: L&lt;&lt;467.0,-38.0&gt;--&lt;468.0,445.0&gt;&gt;

* u18BD0.002: L&lt;&lt;530.0,585.0&gt;--&lt;529.0,-34.0&gt;&gt;

* u18BD0.002: L&lt;&lt;698.0,353.0&gt;--&lt;697.0,205.0&gt;&gt;

* u18BD0.003: L&lt;&lt;184.0,1332.0&gt;--&lt;183.0,1177.0&gt;&gt;

* u18BD0.003: L&lt;&lt;467.0,962.0&gt;--&lt;468.0,1445.0&gt;&gt;

* u18BD0.003: L&lt;&lt;530.0,1585.0&gt;--&lt;529.0,966.0&gt;&gt;

* u18BD0.003: L&lt;&lt;698.0,1353.0&gt;--&lt;697.0,1205.0&gt;&gt;

* u18BD3 (U+18BD3): L&lt;&lt;531.0,114.0&gt;--&lt;530.0,-154.0&gt;&gt;

* u18BD3.001: L&lt;&lt;31.0,114.0&gt;--&lt;30.0,-154.0&gt;&gt;

* u18BD3.002: L&lt;&lt;531.0,114.0&gt;--&lt;530.0,-154.0&gt;&gt;

* u18BD3.003: L&lt;&lt;531.0,1114.0&gt;--&lt;530.0,846.0&gt;&gt;

* u18BD4 (U+18BD4): L&lt;&lt;269.0,281.0&gt;--&lt;268.0,148.0&gt;&gt;

* u18BD4.001: L&lt;&lt;-231.0,281.0&gt;--&lt;-232.0,148.0&gt;&gt;

* u18BD4.002: L&lt;&lt;269.0,281.0&gt;--&lt;268.0,148.0&gt;&gt;

* u18BD4.003: L&lt;&lt;269.0,1281.0&gt;--&lt;268.0,1148.0&gt;&gt;

* u18BD5 (U+18BD5): L&lt;&lt;284.0,345.0&gt;--&lt;285.0,208.0&gt;&gt;

* u18BD5.001: L&lt;&lt;-216.0,345.0&gt;--&lt;-215.0,208.0&gt;&gt;

* u18BD5.002: L&lt;&lt;284.0,345.0&gt;--&lt;285.0,208.0&gt;&gt;

* u18BD5.003: L&lt;&lt;284.0,1345.0&gt;--&lt;285.0,1208.0&gt;&gt;

* u18BD9 (U+18BD9): L&lt;&lt;784.0,207.0&gt;--&lt;783.0,49.0&gt;&gt;

* u18BD9.001: L&lt;&lt;284.0,207.0&gt;--&lt;283.0,49.0&gt;&gt;

* u18BD9.002: L&lt;&lt;784.0,207.0&gt;--&lt;783.0,49.0&gt;&gt;

* u18BD9.003: L&lt;&lt;784.0,1207.0&gt;--&lt;783.0,1049.0&gt;&gt;

* u18BDA (U+18BDA): L&lt;&lt;724.0,282.0&gt;--&lt;723.0,49.0&gt;&gt;

* u18BDA.001: L&lt;&lt;224.0,282.0&gt;--&lt;223.0,49.0&gt;&gt;

* u18BDA.002: L&lt;&lt;724.0,282.0&gt;--&lt;723.0,49.0&gt;&gt;

* u18BDA.003: L&lt;&lt;724.0,1282.0&gt;--&lt;723.0,1049.0&gt;&gt;

* u18C0E (U+18C0E): L&lt;&lt;565.0,547.0&gt;--&lt;564.0,394.0&gt;&gt;

* u18C0E.001: L&lt;&lt;65.0,547.0&gt;--&lt;64.0,394.0&gt;&gt;

* u18C0E.002: L&lt;&lt;565.0,547.0&gt;--&lt;564.0,394.0&gt;&gt;

* u18C0E.003: L&lt;&lt;565.0,1547.0&gt;--&lt;564.0,1394.0&gt;&gt;

* u18C60 (U+18C60): L&lt;&lt;447.0,23.0&gt;--&lt;448.0,173.0&gt;&gt;

* u18C60 (U+18C60): L&lt;&lt;448.0,173.0&gt;--&lt;447.0,325.0&gt;&gt;

* u18C60.001: L&lt;&lt;-52.0,173.0&gt;--&lt;-53.0,325.0&gt;&gt;

* u18C60.001: L&lt;&lt;-53.0,23.0&gt;--&lt;-52.0,173.0&gt;&gt;

* u18C60.002: L&lt;&lt;447.0,23.0&gt;--&lt;448.0,173.0&gt;&gt;

* u18C60.002: L&lt;&lt;448.0,173.0&gt;--&lt;447.0,325.0&gt;&gt;

* u18C60.003: L&lt;&lt;447.0,1023.0&gt;--&lt;448.0,1173.0&gt;&gt;

* u18C60.003: L&lt;&lt;448.0,1173.0&gt;--&lt;447.0,1325.0&gt;&gt;

* u18C67 (U+18C67): L&lt;&lt;210.0,17.0&gt;--&lt;211.0,163.0&gt;&gt;

* u18C67 (U+18C67): L&lt;&lt;211.0,163.0&gt;--&lt;210.0,312.0&gt;&gt;

* u18C67 (U+18C67): L&lt;&lt;824.0,135.0&gt;--&lt;825.0,-18.0&gt;&gt;

* u18C67.001: L&lt;&lt;-289.0,163.0&gt;--&lt;-290.0,312.0&gt;&gt;

* u18C67.001: L&lt;&lt;-290.0,17.0&gt;--&lt;-289.0,163.0&gt;&gt;

* u18C67.001: L&lt;&lt;324.0,135.0&gt;--&lt;325.0,-18.0&gt;&gt;

* u18C67.002: L&lt;&lt;210.0,17.0&gt;--&lt;211.0,163.0&gt;&gt;

* u18C67.002: L&lt;&lt;211.0,163.0&gt;--&lt;210.0,312.0&gt;&gt;

* u18C67.002: L&lt;&lt;824.0,135.0&gt;--&lt;825.0,-18.0&gt;&gt;

* u18C67.003: L&lt;&lt;210.0,1017.0&gt;--&lt;211.0,1163.0&gt;&gt;

* u18C67.003: L&lt;&lt;211.0,1163.0&gt;--&lt;210.0,1312.0&gt;&gt;

* u18C67.003: L&lt;&lt;824.0,1135.0&gt;--&lt;825.0,982.0&gt;&gt;

* u18C81 (U+18C81): L&lt;&lt;554.0,272.0&gt;--&lt;553.0,-20.0&gt;&gt;

* u18C81.001: L&lt;&lt;54.0,272.0&gt;--&lt;53.0,-20.0&gt;&gt;

* u18C81.002: L&lt;&lt;554.0,272.0&gt;--&lt;553.0,-20.0&gt;&gt;

* u18C81.003: L&lt;&lt;554.0,1272.0&gt;--&lt;553.0,980.0&gt;&gt;

* u18C89 (U+18C89): L&lt;&lt;146.0,20.0&gt;--&lt;147.0,169.0&gt;&gt;

* u18C89 (U+18C89): L&lt;&lt;147.0,169.0&gt;--&lt;146.0,319.0&gt;&gt;

* u18C89 (U+18C89): L&lt;&lt;854.0,145.0&gt;--&lt;855.0,-11.0&gt;&gt;

* u18C89.001: L&lt;&lt;-353.0,169.0&gt;--&lt;-354.0,319.0&gt;&gt;

* u18C89.001: L&lt;&lt;-354.0,20.0&gt;--&lt;-353.0,169.0&gt;&gt;

* u18C89.001: L&lt;&lt;354.0,145.0&gt;--&lt;355.0,-11.0&gt;&gt;

* u18C89.002: L&lt;&lt;146.0,20.0&gt;--&lt;147.0,169.0&gt;&gt;

* u18C89.002: L&lt;&lt;147.0,169.0&gt;--&lt;146.0,319.0&gt;&gt;

* u18C89.002: L&lt;&lt;854.0,145.0&gt;--&lt;855.0,-11.0&gt;&gt;

* u18C89.003: L&lt;&lt;146.0,1020.0&gt;--&lt;147.0,1169.0&gt;&gt;

* u18C89.003: L&lt;&lt;147.0,1169.0&gt;--&lt;146.0,1319.0&gt;&gt;

* u18C89.003: L&lt;&lt;854.0,1145.0&gt;--&lt;855.0,989.0&gt;&gt;

* u18C8B (U+18C8B): L&lt;&lt;463.0,67.0&gt;--&lt;464.0,214.0&gt;&gt;

* u18C8B (U+18C8B): L&lt;&lt;525.0,218.0&gt;--&lt;524.0,-21.0&gt;&gt;

* u18C8B.001: L&lt;&lt;-37.0,67.0&gt;--&lt;-36.0,214.0&gt;&gt;

* u18C8B.001: L&lt;&lt;25.0,218.0&gt;--&lt;24.0,-21.0&gt;&gt;

* u18C8B.002: L&lt;&lt;463.0,67.0&gt;--&lt;464.0,214.0&gt;&gt;

* u18C8B.002: L&lt;&lt;525.0,218.0&gt;--&lt;524.0,-21.0&gt;&gt;

* u18C8B.003: L&lt;&lt;463.0,1067.0&gt;--&lt;464.0,1214.0&gt;&gt;

* u18C8B.003: L&lt;&lt;525.0,1218.0&gt;--&lt;524.0,979.0&gt;&gt;

* u18C8D (U+18C8D): L&lt;&lt;535.0,263.0&gt;--&lt;534.0,-35.0&gt;&gt;

* u18C8D.001: L&lt;&lt;35.0,263.0&gt;--&lt;34.0,-35.0&gt;&gt;

* u18C8D.002: L&lt;&lt;535.0,263.0&gt;--&lt;534.0,-35.0&gt;&gt;

* u18C8D.003: L&lt;&lt;535.0,1263.0&gt;--&lt;534.0,965.0&gt;&gt;

* u18C8F (U+18C8F): L&lt;&lt;595.0,523.0&gt;--&lt;596.0,222.0&gt;&gt;

* u18C8F.001: L&lt;&lt;95.0,523.0&gt;--&lt;96.0,222.0&gt;&gt;

* u18C8F.002: L&lt;&lt;595.0,523.0&gt;--&lt;596.0,222.0&gt;&gt;

* u18C8F.003: L&lt;&lt;595.0,1523.0&gt;--&lt;596.0,1222.0&gt;&gt;

* u18C94 (U+18C94): L&lt;&lt;614.0,116.0&gt;--&lt;615.0,481.0&gt;&gt;

* u18C94 (U+18C94): L&lt;&lt;679.0,566.0&gt;--&lt;677.0,-10.0&gt;&gt;

* u18C94.001: L&lt;&lt;114.0,116.0&gt;--&lt;115.0,481.0&gt;&gt;

* u18C94.001: L&lt;&lt;179.0,566.0&gt;--&lt;177.0,-10.0&gt;&gt;

* u18C94.002: L&lt;&lt;614.0,116.0&gt;--&lt;615.0,481.0&gt;&gt;

* u18C94.002: L&lt;&lt;679.0,566.0&gt;--&lt;677.0,-10.0&gt;&gt;

* u18C94.003: L&lt;&lt;614.0,1116.0&gt;--&lt;615.0,1481.0&gt;&gt;

* u18C94.003: L&lt;&lt;679.0,1566.0&gt;--&lt;677.0,990.0&gt;&gt;

* u18C99 (U+18C99): L&lt;&lt;301.0,201.0&gt;--&lt;302.0,56.0&gt;&gt;

* u18C99.001: L&lt;&lt;-199.0,201.0&gt;--&lt;-198.0,56.0&gt;&gt;

* u18C99.002: L&lt;&lt;301.0,201.0&gt;--&lt;302.0,56.0&gt;&gt;

* u18C99.003: L&lt;&lt;301.0,1201.0&gt;--&lt;302.0,1056.0&gt;&gt;

* u18CD0 (U+18CD0): L&lt;&lt;522.0,-36.0&gt;--&lt;523.0,-151.0&gt;&gt;

* u18CD0.001: L&lt;&lt;22.0,-36.0&gt;--&lt;23.0,-151.0&gt;&gt;

* u18CD0.002: L&lt;&lt;522.0,-36.0&gt;--&lt;523.0,-151.0&gt;&gt;

* u18CD0.003: L&lt;&lt;522.0,964.0&gt;--&lt;523.0,849.0&gt;&gt;

* uni4F53 (U+4F53): L&lt;&lt;646.0,448.0&gt;--&lt;645.0,212.0&gt;&gt;

* uni5B8B (U+5B8B): L&lt;&lt;530.0,239.0&gt;--&lt;529.0,87.0&gt;&gt;

* uni6B4C (U+6B4C): L&lt;&lt;462.0,516.0&gt;--&lt;461.0,362.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain less than 150 CJK characters? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>There are only 9 CJK glyphs when there needs to be at least 150 in order to support the smallest CJK writing system, Kana.
The following CJK glyphs were found:
['uni4E39', 'uni4EFF', 'uni4F53', 'uni5951', 'uni5B57', 'uni5B8B', 'uni5C0F', 'uni6B4C', 'uni8C37']
Please check that these glyphs have the correct unicodes.</p>
 [code: cjk-not-enough-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 2.0x (2000)</p>
 [code: bad-hhea-range]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoFangsongKSSVertical/googlefonts/ttf/NotoFangsongKSSVertical-Regular.ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 6 | 12 | 117 | 6 | 110 | 0 | 
| 0% | 0% | 2% | 5% | 47% | 2% | 44% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
