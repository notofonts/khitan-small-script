## FontBakery report

fontbakery version: 0.12.10



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoSerifKhitanSmallScript-Regular.ttf</summary>
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



<details><summary>[15] NotoSerifKhitanSmallScript-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (880) and hhea ascent (2300) must be equal.</p>
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
    <summary>🔥 <b>FAIL</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Noto Serif Khitan Small Script Regular: OS/2 sTypoAscender is 880 when it should be 2300</p>
 [code: bad-typo-ascender]



* 🔥 **FAIL** <p>Noto Serif Khitan Small Script Regular: OS/2 sTypoDescender is -120 when it should be -1700</p>
 [code: bad-typo-descender]



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







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSerifKhitanSmallScript/googlefonts/ttf does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, coptic, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, coptic, syriac, todhri, tai-le, old-permic, malayalam, duployan, math, hebrew, tifinagh</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+25A1 WHITE SQUARE: try adding symbols</li>
<li>U+2B1A DOTTED SQUARE: try adding symbols</li>
<li>U+4E39 CJK UNIFIED IDEOGRAPH-4E39: try adding one of: japanese, chinese-simplified, chinese-hongkong, chinese-traditional</li>
<li>U+4EFF CJK UNIFIED IDEOGRAPH-4EFF: try adding one of: chinese-simplified, chinese-hongkong, chinese-traditional</li>
<li>U+4F53 CJK UNIFIED IDEOGRAPH-4F53: try adding one of: japanese, chinese-simplified, chinese-hongkong, chinese-traditional</li>
<li>U+5951 CJK UNIFIED IDEOGRAPH-5951: try adding one of: japanese, chinese-simplified, chinese-hongkong, chinese-traditional</li>
<li>U+5B57 CJK UNIFIED IDEOGRAPH-5B57: try adding one of: japanese, chinese-simplified, chinese-hongkong, chinese-traditional</li>
<li>U+5B8B CJK UNIFIED IDEOGRAPH-5B8B: try adding one of: japanese, chinese-simplified, chinese-hongkong, chinese-traditional</li>
<li>U+5C0F CJK UNIFIED IDEOGRAPH-5C0F: try adding one of: japanese, chinese-simplified, chinese-hongkong, chinese-traditional</li>
<li>U+6B4C CJK UNIFIED IDEOGRAPH-6B4C: try adding one of: japanese, chinese-simplified, chinese-hongkong, chinese-traditional</li>
<li>U+8C37 CJK UNIFIED IDEOGRAPH-8C37: try adding one of: japanese, chinese-simplified, chinese-hongkong, chinese-traditional</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>khitan-small-script</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Name ID 6 'NotoSerifKhitanSmallScript-Regular' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms.</p>
 [code: nameid6-too-long]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Han (Latn, 6 speakers), Belarusian (Cyrl, 10,064,517 speakers), Mundani (Latn, 34,000 speakers), Nzakara (Latn, 50,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Heiltsuk (Latn, 300 speakers), Ngbaka (Latn, 1,020,000 speakers), Kom (Latn, 360,685 speakers), Dii (Latn, 71,000 speakers), Kaska (Latn, 125 speakers), Basaa (Latn, 332,940 speakers), Zapotec (Latn, 490,000 speakers), Koonzime (Latn, 40,000 speakers), Mango (Latn, 77,000 speakers), Navajo (Latn, 166,319 speakers), Teke-Ebo (Latn, 260,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Nateni (Latn, 100,000 speakers), Dan (Latn, 1,099,244 speakers), Lugbara (Latn, 2,200,000 speakers), Igbo (Latn, 27,823,640 speakers), Makaa (Latn, 221,000 speakers), Aghem (Latn, 38,843 speakers), South Central Banda (Latn, 244,000 speakers), Fur (Latn, 1,230,163 speakers), Dutch (Latn, 31,709,104 speakers), Ejagham (Latn, 120,000 speakers), Yala (Latn, 200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mfumte (Latn, 79,000 speakers), Southern Kisi (Latn, 360,000 speakers), Vute (Latn, 21,000 speakers), Gulay (Latn, 250,478 speakers), Cicipu (Latn, 44,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Bafut (Latn, 158,146 speakers), Sar (Latn, 500,000 speakers), Ekpeye (Latn, 226,000 speakers), Avokaya (Latn, 100,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* u18B10 (U+18B10): B&lt;&lt;780.0,481.0&gt;-&lt;741.0,439.0&gt;-&lt;742.0,440.0&gt;&gt;/B&lt;&lt;742.0,440.0&gt;-&lt;708.0,407.0&gt;-&lt;673.5,378.5&gt;&gt; = 0.8550973962662667

* u18B10.001: B&lt;&lt;780.0,1981.0&gt;-&lt;741.0,1939.0&gt;-&lt;742.0,1940.0&gt;&gt;/B&lt;&lt;742.0,1940.0&gt;-&lt;708.0,1907.0&gt;-&lt;673.5,1878.5&gt;&gt; = 0.8550973962662667

* u18B10.002: B&lt;&lt;1280.0,1981.0&gt;-&lt;1241.0,1939.0&gt;-&lt;1242.0,1940.0&gt;&gt;/B&lt;&lt;1242.0,1940.0&gt;-&lt;1208.0,1907.0&gt;-&lt;1173.5,1878.5&gt;&gt; = 0.8550973962662667

* u18B10.003: B&lt;&lt;-220.0,1981.0&gt;-&lt;-259.0,1939.0&gt;-&lt;-258.0,1940.0&gt;&gt;/B&lt;&lt;-258.0,1940.0&gt;-&lt;-292.0,1907.0&gt;-&lt;-326.5,1878.5&gt;&gt; = 0.8550973962662667

* u18B10.004: B&lt;&lt;780.0,1481.0&gt;-&lt;741.0,1439.0&gt;-&lt;742.0,1440.0&gt;&gt;/B&lt;&lt;742.0,1440.0&gt;-&lt;708.0,1407.0&gt;-&lt;673.5,1378.5&gt;&gt; = 0.8550973962662667

* u18B10.005: B&lt;&lt;1280.0,1481.0&gt;-&lt;1241.0,1439.0&gt;-&lt;1242.0,1440.0&gt;&gt;/B&lt;&lt;1242.0,1440.0&gt;-&lt;1208.0,1407.0&gt;-&lt;1173.5,1378.5&gt;&gt; = 0.8550973962662667

* u18B10.006: B&lt;&lt;-220.0,1481.0&gt;-&lt;-259.0,1439.0&gt;-&lt;-258.0,1440.0&gt;&gt;/B&lt;&lt;-258.0,1440.0&gt;-&lt;-292.0,1407.0&gt;-&lt;-326.5,1378.5&gt;&gt; = 0.8550973962662667

* u18B10.007: B&lt;&lt;-1220.0,981.0&gt;-&lt;-1259.0,939.0&gt;-&lt;-1258.0,940.0&gt;&gt;/B&lt;&lt;-1258.0,940.0&gt;-&lt;-1292.0,907.0&gt;-&lt;-1326.5,878.5&gt;&gt; = 0.8550973962662667

* u18B10.008: B&lt;&lt;1280.0,981.0&gt;-&lt;1241.0,939.0&gt;-&lt;1242.0,940.0&gt;&gt;/B&lt;&lt;1242.0,940.0&gt;-&lt;1208.0,907.0&gt;-&lt;1173.5,878.5&gt;&gt; = 0.8550973962662667

* u18B10.009: B&lt;&lt;-220.0,981.0&gt;-&lt;-259.0,939.0&gt;-&lt;-258.0,940.0&gt;&gt;/B&lt;&lt;-258.0,940.0&gt;-&lt;-292.0,907.0&gt;-&lt;-326.5,878.5&gt;&gt; = 0.8550973962662667

* u18B10.010: B&lt;&lt;-1220.0,481.0&gt;-&lt;-1259.0,439.0&gt;-&lt;-1258.0,440.0&gt;&gt;/B&lt;&lt;-1258.0,440.0&gt;-&lt;-1292.0,407.0&gt;-&lt;-1326.5,378.5&gt;&gt; = 0.8550973962662667

* u18B10.011: B&lt;&lt;1280.0,481.0&gt;-&lt;1241.0,439.0&gt;-&lt;1242.0,440.0&gt;&gt;/B&lt;&lt;1242.0,440.0&gt;-&lt;1208.0,407.0&gt;-&lt;1173.5,378.5&gt;&gt; = 0.8550973962662667

* u18B10.012: B&lt;&lt;-220.0,481.0&gt;-&lt;-259.0,439.0&gt;-&lt;-258.0,440.0&gt;&gt;/B&lt;&lt;-258.0,440.0&gt;-&lt;-292.0,407.0&gt;-&lt;-326.5,378.5&gt;&gt; = 0.8550973962662667

* u18B10.013: B&lt;&lt;-1220.0,-19.0&gt;-&lt;-1259.0,-61.0&gt;-&lt;-1258.0,-60.0&gt;&gt;/B&lt;&lt;-1258.0,-60.0&gt;-&lt;-1292.0,-93.0&gt;-&lt;-1326.5,-121.5&gt;&gt; = 0.8550973962662667

* u18B10.014: B&lt;&lt;-720.0,-19.0&gt;-&lt;-759.0,-61.0&gt;-&lt;-758.0,-60.0&gt;&gt;/B&lt;&lt;-758.0,-60.0&gt;-&lt;-792.0,-93.0&gt;-&lt;-826.5,-121.5&gt;&gt; = 0.8550973962662667

* u18B10.015: B&lt;&lt;-220.0,-19.0&gt;-&lt;-259.0,-61.0&gt;-&lt;-258.0,-60.0&gt;&gt;/B&lt;&lt;-258.0,-60.0&gt;-&lt;-292.0,-93.0&gt;-&lt;-326.5,-121.5&gt;&gt; = 0.8550973962662667

* u18B10.016: B&lt;&lt;-1220.0,-519.0&gt;-&lt;-1259.0,-561.0&gt;-&lt;-1258.0,-560.0&gt;&gt;/B&lt;&lt;-1258.0,-560.0&gt;-&lt;-1292.0,-593.0&gt;-&lt;-1326.5,-621.5&gt;&gt; = 0.8550973962662667

* u18B10.017: B&lt;&lt;-720.0,-519.0&gt;-&lt;-759.0,-561.0&gt;-&lt;-758.0,-560.0&gt;&gt;/B&lt;&lt;-758.0,-560.0&gt;-&lt;-792.0,-593.0&gt;-&lt;-826.5,-621.5&gt;&gt; = 0.8550973962662667

* u18B10.018: B&lt;&lt;-220.0,-519.0&gt;-&lt;-259.0,-561.0&gt;-&lt;-258.0,-560.0&gt;&gt;/B&lt;&lt;-258.0,-560.0&gt;-&lt;-292.0,-593.0&gt;-&lt;-326.5,-621.5&gt;&gt; = 0.8550973962662667

* u18B10.019: B&lt;&lt;-1220.0,-1019.0&gt;-&lt;-1259.0,-1061.0&gt;-&lt;-1258.0,-1060.0&gt;&gt;/B&lt;&lt;-1258.0,-1060.0&gt;-&lt;-1292.0,-1093.0&gt;-&lt;-1326.5,-1121.5&gt;&gt; = 0.8550973962662667

* u18B10.020: B&lt;&lt;-720.0,-1019.0&gt;-&lt;-759.0,-1061.0&gt;-&lt;-758.0,-1060.0&gt;&gt;/B&lt;&lt;-758.0,-1060.0&gt;-&lt;-792.0,-1093.0&gt;-&lt;-826.5,-1121.5&gt;&gt; = 0.8550973962662667

* u18B10.021: B&lt;&lt;-220.0,-1019.0&gt;-&lt;-259.0,-1061.0&gt;-&lt;-258.0,-1060.0&gt;&gt;/B&lt;&lt;-258.0,-1060.0&gt;-&lt;-292.0,-1093.0&gt;-&lt;-326.5,-1121.5&gt;&gt; = 0.8550973962662667

* u18B10.022: B&lt;&lt;780.0,981.0&gt;-&lt;741.0,939.0&gt;-&lt;742.0,940.0&gt;&gt;/B&lt;&lt;742.0,940.0&gt;-&lt;708.0,907.0&gt;-&lt;673.5,878.5&gt;&gt; = 0.8550973962662667

* u18B10.023: B&lt;&lt;780.0,481.0&gt;-&lt;741.0,439.0&gt;-&lt;742.0,440.0&gt;&gt;/B&lt;&lt;742.0,440.0&gt;-&lt;708.0,407.0&gt;-&lt;673.5,378.5&gt;&gt; = 0.8550973962662667

* u18B3C (U+18B3C): B&lt;&lt;209.0,307.0&gt;-&lt;250.0,266.0&gt;-&lt;294.0,237.0&gt;&gt;/B&lt;&lt;294.0,237.0&gt;-&lt;293.0,238.0&gt;-&lt;420.0,152.0&gt;&gt; = 11.611486423888481

* u18B3C.001: B&lt;&lt;209.0,1807.0&gt;-&lt;250.0,1766.0&gt;-&lt;294.0,1737.0&gt;&gt;/B&lt;&lt;294.0,1737.0&gt;-&lt;293.0,1738.0&gt;-&lt;420.0,1652.0&gt;&gt; = 11.611486423888481

* u18B3C.002: B&lt;&lt;709.0,1807.0&gt;-&lt;750.0,1766.0&gt;-&lt;794.0,1737.0&gt;&gt;/B&lt;&lt;794.0,1737.0&gt;-&lt;793.0,1738.0&gt;-&lt;920.0,1652.0&gt;&gt; = 11.611486423888481

* u18B3C.003: B&lt;&lt;-791.0,1807.0&gt;-&lt;-750.0,1766.0&gt;-&lt;-706.0,1737.0&gt;&gt;/B&lt;&lt;-706.0,1737.0&gt;-&lt;-707.0,1738.0&gt;-&lt;-580.0,1652.0&gt;&gt; = 11.611486423888481

* u18B3C.004: B&lt;&lt;209.0,1307.0&gt;-&lt;250.0,1266.0&gt;-&lt;294.0,1237.0&gt;&gt;/B&lt;&lt;294.0,1237.0&gt;-&lt;293.0,1238.0&gt;-&lt;420.0,1152.0&gt;&gt; = 11.611486423888481

* u18B3C.005: B&lt;&lt;709.0,1307.0&gt;-&lt;750.0,1266.0&gt;-&lt;794.0,1237.0&gt;&gt;/B&lt;&lt;794.0,1237.0&gt;-&lt;793.0,1238.0&gt;-&lt;920.0,1152.0&gt;&gt; = 11.611486423888481

* u18B3C.006: B&lt;&lt;-791.0,1307.0&gt;-&lt;-750.0,1266.0&gt;-&lt;-706.0,1237.0&gt;&gt;/B&lt;&lt;-706.0,1237.0&gt;-&lt;-707.0,1238.0&gt;-&lt;-580.0,1152.0&gt;&gt; = 11.611486423888481

* u18B3C.007: B&lt;&lt;-1791.0,807.0&gt;-&lt;-1750.0,766.0&gt;-&lt;-1706.0,737.0&gt;&gt;/B&lt;&lt;-1706.0,737.0&gt;-&lt;-1707.0,738.0&gt;-&lt;-1580.0,652.0&gt;&gt; = 11.611486423888481

* u18B3C.008: B&lt;&lt;709.0,807.0&gt;-&lt;750.0,766.0&gt;-&lt;794.0,737.0&gt;&gt;/B&lt;&lt;794.0,737.0&gt;-&lt;793.0,738.0&gt;-&lt;920.0,652.0&gt;&gt; = 11.611486423888481

* u18B3C.009: B&lt;&lt;-791.0,807.0&gt;-&lt;-750.0,766.0&gt;-&lt;-706.0,737.0&gt;&gt;/B&lt;&lt;-706.0,737.0&gt;-&lt;-707.0,738.0&gt;-&lt;-580.0,652.0&gt;&gt; = 11.611486423888481

* u18B3C.010: B&lt;&lt;-1791.0,307.0&gt;-&lt;-1750.0,266.0&gt;-&lt;-1706.0,237.0&gt;&gt;/B&lt;&lt;-1706.0,237.0&gt;-&lt;-1707.0,238.0&gt;-&lt;-1580.0,152.0&gt;&gt; = 11.611486423888481

* u18B3C.011: B&lt;&lt;709.0,307.0&gt;-&lt;750.0,266.0&gt;-&lt;794.0,237.0&gt;&gt;/B&lt;&lt;794.0,237.0&gt;-&lt;793.0,238.0&gt;-&lt;920.0,152.0&gt;&gt; = 11.611486423888481

* u18B3C.012: B&lt;&lt;-791.0,307.0&gt;-&lt;-750.0,266.0&gt;-&lt;-706.0,237.0&gt;&gt;/B&lt;&lt;-706.0,237.0&gt;-&lt;-707.0,238.0&gt;-&lt;-580.0,152.0&gt;&gt; = 11.611486423888481

* u18B3C.013: B&lt;&lt;-1791.0,-193.0&gt;-&lt;-1750.0,-234.0&gt;-&lt;-1706.0,-263.0&gt;&gt;/B&lt;&lt;-1706.0,-263.0&gt;-&lt;-1707.0,-262.0&gt;-&lt;-1580.0,-348.0&gt;&gt; = 11.611486423888481

* u18B3C.014: B&lt;&lt;-1291.0,-193.0&gt;-&lt;-1250.0,-234.0&gt;-&lt;-1206.0,-263.0&gt;&gt;/B&lt;&lt;-1206.0,-263.0&gt;-&lt;-1207.0,-262.0&gt;-&lt;-1080.0,-348.0&gt;&gt; = 11.611486423888481

* u18B3C.015: B&lt;&lt;-791.0,-193.0&gt;-&lt;-750.0,-234.0&gt;-&lt;-706.0,-263.0&gt;&gt;/B&lt;&lt;-706.0,-263.0&gt;-&lt;-707.0,-262.0&gt;-&lt;-580.0,-348.0&gt;&gt; = 11.611486423888481

* u18B3C.016: B&lt;&lt;-1791.0,-693.0&gt;-&lt;-1750.0,-734.0&gt;-&lt;-1706.0,-763.0&gt;&gt;/B&lt;&lt;-1706.0,-763.0&gt;-&lt;-1707.0,-762.0&gt;-&lt;-1580.0,-848.0&gt;&gt; = 11.611486423888481

* u18B3C.017: B&lt;&lt;-1291.0,-693.0&gt;-&lt;-1250.0,-734.0&gt;-&lt;-1206.0,-763.0&gt;&gt;/B&lt;&lt;-1206.0,-763.0&gt;-&lt;-1207.0,-762.0&gt;-&lt;-1080.0,-848.0&gt;&gt; = 11.611486423888481

* u18B3C.018: B&lt;&lt;-791.0,-693.0&gt;-&lt;-750.0,-734.0&gt;-&lt;-706.0,-763.0&gt;&gt;/B&lt;&lt;-706.0,-763.0&gt;-&lt;-707.0,-762.0&gt;-&lt;-580.0,-848.0&gt;&gt; = 11.611486423888481

* u18B3C.019: B&lt;&lt;-1791.0,-1193.0&gt;-&lt;-1750.0,-1234.0&gt;-&lt;-1706.0,-1263.0&gt;&gt;/B&lt;&lt;-1706.0,-1263.0&gt;-&lt;-1707.0,-1262.0&gt;-&lt;-1580.0,-1348.0&gt;&gt; = 11.611486423888481

* u18B3C.020: B&lt;&lt;-1291.0,-1193.0&gt;-&lt;-1250.0,-1234.0&gt;-&lt;-1206.0,-1263.0&gt;&gt;/B&lt;&lt;-1206.0,-1263.0&gt;-&lt;-1207.0,-1262.0&gt;-&lt;-1080.0,-1348.0&gt;&gt; = 11.611486423888481

* u18B3C.021: B&lt;&lt;-791.0,-1193.0&gt;-&lt;-750.0,-1234.0&gt;-&lt;-706.0,-1263.0&gt;&gt;/B&lt;&lt;-706.0,-1263.0&gt;-&lt;-707.0,-1262.0&gt;-&lt;-580.0,-1348.0&gt;&gt; = 11.611486423888481

* u18B3C.022: B&lt;&lt;209.0,807.0&gt;-&lt;250.0,766.0&gt;-&lt;294.0,737.0&gt;&gt;/B&lt;&lt;294.0,737.0&gt;-&lt;293.0,738.0&gt;-&lt;420.0,652.0&gt;&gt; = 11.611486423888481

* u18B3C.023: B&lt;&lt;209.0,307.0&gt;-&lt;250.0,266.0&gt;-&lt;294.0,237.0&gt;&gt;/B&lt;&lt;294.0,237.0&gt;-&lt;293.0,238.0&gt;-&lt;420.0,152.0&gt;&gt; = 11.611486423888481

* u18B81 (U+18B81): B&lt;&lt;838.0,326.0&gt;-&lt;799.0,284.0&gt;-&lt;800.0,285.0&gt;&gt;/B&lt;&lt;800.0,285.0&gt;-&lt;716.0,203.0&gt;-&lt;644.0,155.0&gt;&gt; = 0.6902771978645523

* u18B81.001: B&lt;&lt;838.0,1826.0&gt;-&lt;799.0,1784.0&gt;-&lt;800.0,1785.0&gt;&gt;/B&lt;&lt;800.0,1785.0&gt;-&lt;716.0,1703.0&gt;-&lt;644.0,1655.0&gt;&gt; = 0.6902771978645523

* u18B81.002: B&lt;&lt;1338.0,1826.0&gt;-&lt;1299.0,1784.0&gt;-&lt;1300.0,1785.0&gt;&gt;/B&lt;&lt;1300.0,1785.0&gt;-&lt;1216.0,1703.0&gt;-&lt;1144.0,1655.0&gt;&gt; = 0.6902771978645523

* u18B81.003: B&lt;&lt;-162.0,1826.0&gt;-&lt;-201.0,1784.0&gt;-&lt;-200.0,1785.0&gt;&gt;/B&lt;&lt;-200.0,1785.0&gt;-&lt;-284.0,1703.0&gt;-&lt;-356.0,1655.0&gt;&gt; = 0.6902771978645523

* u18B81.004: B&lt;&lt;838.0,1326.0&gt;-&lt;799.0,1284.0&gt;-&lt;800.0,1285.0&gt;&gt;/B&lt;&lt;800.0,1285.0&gt;-&lt;716.0,1203.0&gt;-&lt;644.0,1155.0&gt;&gt; = 0.6902771978645523

* u18B81.005: B&lt;&lt;1338.0,1326.0&gt;-&lt;1299.0,1284.0&gt;-&lt;1300.0,1285.0&gt;&gt;/B&lt;&lt;1300.0,1285.0&gt;-&lt;1216.0,1203.0&gt;-&lt;1144.0,1155.0&gt;&gt; = 0.6902771978645523

* u18B81.006: B&lt;&lt;-162.0,1326.0&gt;-&lt;-201.0,1284.0&gt;-&lt;-200.0,1285.0&gt;&gt;/B&lt;&lt;-200.0,1285.0&gt;-&lt;-284.0,1203.0&gt;-&lt;-356.0,1155.0&gt;&gt; = 0.6902771978645523

* u18B81.007: B&lt;&lt;-1162.0,826.0&gt;-&lt;-1201.0,784.0&gt;-&lt;-1200.0,785.0&gt;&gt;/B&lt;&lt;-1200.0,785.0&gt;-&lt;-1284.0,703.0&gt;-&lt;-1356.0,655.0&gt;&gt; = 0.6902771978645523

* u18B81.008: B&lt;&lt;1338.0,826.0&gt;-&lt;1299.0,784.0&gt;-&lt;1300.0,785.0&gt;&gt;/B&lt;&lt;1300.0,785.0&gt;-&lt;1216.0,703.0&gt;-&lt;1144.0,655.0&gt;&gt; = 0.6902771978645523

* u18B81.009: B&lt;&lt;-162.0,826.0&gt;-&lt;-201.0,784.0&gt;-&lt;-200.0,785.0&gt;&gt;/B&lt;&lt;-200.0,785.0&gt;-&lt;-284.0,703.0&gt;-&lt;-356.0,655.0&gt;&gt; = 0.6902771978645523

* u18B81.010: B&lt;&lt;-1162.0,326.0&gt;-&lt;-1201.0,284.0&gt;-&lt;-1200.0,285.0&gt;&gt;/B&lt;&lt;-1200.0,285.0&gt;-&lt;-1284.0,203.0&gt;-&lt;-1356.0,155.0&gt;&gt; = 0.6902771978645523

* u18B81.011: B&lt;&lt;1338.0,326.0&gt;-&lt;1299.0,284.0&gt;-&lt;1300.0,285.0&gt;&gt;/B&lt;&lt;1300.0,285.0&gt;-&lt;1216.0,203.0&gt;-&lt;1144.0,155.0&gt;&gt; = 0.6902771978645523

* u18B81.012: B&lt;&lt;-162.0,326.0&gt;-&lt;-201.0,284.0&gt;-&lt;-200.0,285.0&gt;&gt;/B&lt;&lt;-200.0,285.0&gt;-&lt;-284.0,203.0&gt;-&lt;-356.0,155.0&gt;&gt; = 0.6902771978645523

* u18B81.013: B&lt;&lt;-1162.0,-174.0&gt;-&lt;-1201.0,-216.0&gt;-&lt;-1200.0,-215.0&gt;&gt;/B&lt;&lt;-1200.0,-215.0&gt;-&lt;-1284.0,-297.0&gt;-&lt;-1356.0,-345.0&gt;&gt; = 0.6902771978645523

* u18B81.014: B&lt;&lt;-662.0,-174.0&gt;-&lt;-701.0,-216.0&gt;-&lt;-700.0,-215.0&gt;&gt;/B&lt;&lt;-700.0,-215.0&gt;-&lt;-784.0,-297.0&gt;-&lt;-856.0,-345.0&gt;&gt; = 0.6902771978645523

* u18B81.015: B&lt;&lt;-162.0,-174.0&gt;-&lt;-201.0,-216.0&gt;-&lt;-200.0,-215.0&gt;&gt;/B&lt;&lt;-200.0,-215.0&gt;-&lt;-284.0,-297.0&gt;-&lt;-356.0,-345.0&gt;&gt; = 0.6902771978645523

* u18B81.016: B&lt;&lt;-1162.0,-674.0&gt;-&lt;-1201.0,-716.0&gt;-&lt;-1200.0,-715.0&gt;&gt;/B&lt;&lt;-1200.0,-715.0&gt;-&lt;-1284.0,-797.0&gt;-&lt;-1356.0,-845.0&gt;&gt; = 0.6902771978645523

* u18B81.017: B&lt;&lt;-662.0,-674.0&gt;-&lt;-701.0,-716.0&gt;-&lt;-700.0,-715.0&gt;&gt;/B&lt;&lt;-700.0,-715.0&gt;-&lt;-784.0,-797.0&gt;-&lt;-856.0,-845.0&gt;&gt; = 0.6902771978645523

* u18B81.018: B&lt;&lt;-162.0,-674.0&gt;-&lt;-201.0,-716.0&gt;-&lt;-200.0,-715.0&gt;&gt;/B&lt;&lt;-200.0,-715.0&gt;-&lt;-284.0,-797.0&gt;-&lt;-356.0,-845.0&gt;&gt; = 0.6902771978645523

* u18B81.019: B&lt;&lt;-1162.0,-1174.0&gt;-&lt;-1201.0,-1216.0&gt;-&lt;-1200.0,-1215.0&gt;&gt;/B&lt;&lt;-1200.0,-1215.0&gt;-&lt;-1284.0,-1297.0&gt;-&lt;-1356.0,-1345.0&gt;&gt; = 0.6902771978645523

* u18B81.020: B&lt;&lt;-662.0,-1174.0&gt;-&lt;-701.0,-1216.0&gt;-&lt;-700.0,-1215.0&gt;&gt;/B&lt;&lt;-700.0,-1215.0&gt;-&lt;-784.0,-1297.0&gt;-&lt;-856.0,-1345.0&gt;&gt; = 0.6902771978645523

* u18B81.021: B&lt;&lt;-162.0,-1174.0&gt;-&lt;-201.0,-1216.0&gt;-&lt;-200.0,-1215.0&gt;&gt;/B&lt;&lt;-200.0,-1215.0&gt;-&lt;-284.0,-1297.0&gt;-&lt;-356.0,-1345.0&gt;&gt; = 0.6902771978645523

* u18B81.022: B&lt;&lt;838.0,826.0&gt;-&lt;799.0,784.0&gt;-&lt;800.0,785.0&gt;&gt;/B&lt;&lt;800.0,785.0&gt;-&lt;716.0,703.0&gt;-&lt;644.0,655.0&gt;&gt; = 0.6902771978645523

* u18B81.023: B&lt;&lt;838.0,326.0&gt;-&lt;799.0,284.0&gt;-&lt;800.0,285.0&gt;&gt;/B&lt;&lt;800.0,285.0&gt;-&lt;716.0,203.0&gt;-&lt;644.0,155.0&gt;&gt; = 0.6902771978645523

* u18BB1 (U+18BB1): B&lt;&lt;455.0,362.0&gt;-&lt;431.0,360.0&gt;-&lt;435.0,360.0&gt;&gt;/B&lt;&lt;435.0,360.0&gt;-&lt;380.0,355.0&gt;-&lt;313.0,341.0&gt;&gt; = 5.1944289077348

* u18BB1.001: B&lt;&lt;455.0,1862.0&gt;-&lt;431.0,1860.0&gt;-&lt;435.0,1860.0&gt;&gt;/B&lt;&lt;435.0,1860.0&gt;-&lt;380.0,1855.0&gt;-&lt;313.0,1841.0&gt;&gt; = 5.1944289077348

* u18BB1.002: B&lt;&lt;955.0,1862.0&gt;-&lt;931.0,1860.0&gt;-&lt;935.0,1860.0&gt;&gt;/B&lt;&lt;935.0,1860.0&gt;-&lt;880.0,1855.0&gt;-&lt;813.0,1841.0&gt;&gt; = 5.1944289077348

* u18BB1.003: B&lt;&lt;-545.0,1862.0&gt;-&lt;-569.0,1860.0&gt;-&lt;-565.0,1860.0&gt;&gt;/B&lt;&lt;-565.0,1860.0&gt;-&lt;-620.0,1855.0&gt;-&lt;-687.0,1841.0&gt;&gt; = 5.1944289077348

* u18BB1.004: B&lt;&lt;455.0,1362.0&gt;-&lt;431.0,1360.0&gt;-&lt;435.0,1360.0&gt;&gt;/B&lt;&lt;435.0,1360.0&gt;-&lt;380.0,1355.0&gt;-&lt;313.0,1341.0&gt;&gt; = 5.1944289077348

* u18BB1.005: B&lt;&lt;955.0,1362.0&gt;-&lt;931.0,1360.0&gt;-&lt;935.0,1360.0&gt;&gt;/B&lt;&lt;935.0,1360.0&gt;-&lt;880.0,1355.0&gt;-&lt;813.0,1341.0&gt;&gt; = 5.1944289077348

* u18BB1.006: B&lt;&lt;-545.0,1362.0&gt;-&lt;-569.0,1360.0&gt;-&lt;-565.0,1360.0&gt;&gt;/B&lt;&lt;-565.0,1360.0&gt;-&lt;-620.0,1355.0&gt;-&lt;-687.0,1341.0&gt;&gt; = 5.1944289077348

* u18BB1.007: B&lt;&lt;-1545.0,862.0&gt;-&lt;-1569.0,860.0&gt;-&lt;-1565.0,860.0&gt;&gt;/B&lt;&lt;-1565.0,860.0&gt;-&lt;-1620.0,855.0&gt;-&lt;-1687.0,841.0&gt;&gt; = 5.1944289077348

* u18BB1.008: B&lt;&lt;955.0,862.0&gt;-&lt;931.0,860.0&gt;-&lt;935.0,860.0&gt;&gt;/B&lt;&lt;935.0,860.0&gt;-&lt;880.0,855.0&gt;-&lt;813.0,841.0&gt;&gt; = 5.1944289077348

* u18BB1.009: B&lt;&lt;-545.0,862.0&gt;-&lt;-569.0,860.0&gt;-&lt;-565.0,860.0&gt;&gt;/B&lt;&lt;-565.0,860.0&gt;-&lt;-620.0,855.0&gt;-&lt;-687.0,841.0&gt;&gt; = 5.1944289077348

* u18BB1.010: B&lt;&lt;-1545.0,362.0&gt;-&lt;-1569.0,360.0&gt;-&lt;-1565.0,360.0&gt;&gt;/B&lt;&lt;-1565.0,360.0&gt;-&lt;-1620.0,355.0&gt;-&lt;-1687.0,341.0&gt;&gt; = 5.1944289077348

* u18BB1.011: B&lt;&lt;955.0,362.0&gt;-&lt;931.0,360.0&gt;-&lt;935.0,360.0&gt;&gt;/B&lt;&lt;935.0,360.0&gt;-&lt;880.0,355.0&gt;-&lt;813.0,341.0&gt;&gt; = 5.1944289077348

* u18BB1.012: B&lt;&lt;-545.0,362.0&gt;-&lt;-569.0,360.0&gt;-&lt;-565.0,360.0&gt;&gt;/B&lt;&lt;-565.0,360.0&gt;-&lt;-620.0,355.0&gt;-&lt;-687.0,341.0&gt;&gt; = 5.1944289077348

* u18BB1.013: B&lt;&lt;-1545.0,-138.0&gt;-&lt;-1569.0,-140.0&gt;-&lt;-1565.0,-140.0&gt;&gt;/B&lt;&lt;-1565.0,-140.0&gt;-&lt;-1620.0,-145.0&gt;-&lt;-1687.0,-159.0&gt;&gt; = 5.1944289077348

* u18BB1.014: B&lt;&lt;-1045.0,-138.0&gt;-&lt;-1069.0,-140.0&gt;-&lt;-1065.0,-140.0&gt;&gt;/B&lt;&lt;-1065.0,-140.0&gt;-&lt;-1120.0,-145.0&gt;-&lt;-1187.0,-159.0&gt;&gt; = 5.1944289077348

* u18BB1.015: B&lt;&lt;-545.0,-138.0&gt;-&lt;-569.0,-140.0&gt;-&lt;-565.0,-140.0&gt;&gt;/B&lt;&lt;-565.0,-140.0&gt;-&lt;-620.0,-145.0&gt;-&lt;-687.0,-159.0&gt;&gt; = 5.1944289077348

* u18BB1.016: B&lt;&lt;-1545.0,-638.0&gt;-&lt;-1569.0,-640.0&gt;-&lt;-1565.0,-640.0&gt;&gt;/B&lt;&lt;-1565.0,-640.0&gt;-&lt;-1620.0,-645.0&gt;-&lt;-1687.0,-659.0&gt;&gt; = 5.1944289077348

* u18BB1.017: B&lt;&lt;-1045.0,-638.0&gt;-&lt;-1069.0,-640.0&gt;-&lt;-1065.0,-640.0&gt;&gt;/B&lt;&lt;-1065.0,-640.0&gt;-&lt;-1120.0,-645.0&gt;-&lt;-1187.0,-659.0&gt;&gt; = 5.1944289077348

* u18BB1.018: B&lt;&lt;-545.0,-638.0&gt;-&lt;-569.0,-640.0&gt;-&lt;-565.0,-640.0&gt;&gt;/B&lt;&lt;-565.0,-640.0&gt;-&lt;-620.0,-645.0&gt;-&lt;-687.0,-659.0&gt;&gt; = 5.1944289077348

* u18BB1.019: B&lt;&lt;-1545.0,-1138.0&gt;-&lt;-1569.0,-1140.0&gt;-&lt;-1565.0,-1140.0&gt;&gt;/B&lt;&lt;-1565.0,-1140.0&gt;-&lt;-1620.0,-1145.0&gt;-&lt;-1687.0,-1159.0&gt;&gt; = 5.1944289077348

* u18BB1.020: B&lt;&lt;-1045.0,-1138.0&gt;-&lt;-1069.0,-1140.0&gt;-&lt;-1065.0,-1140.0&gt;&gt;/B&lt;&lt;-1065.0,-1140.0&gt;-&lt;-1120.0,-1145.0&gt;-&lt;-1187.0,-1159.0&gt;&gt; = 5.1944289077348

* u18BB1.021: B&lt;&lt;-545.0,-1138.0&gt;-&lt;-569.0,-1140.0&gt;-&lt;-565.0,-1140.0&gt;&gt;/B&lt;&lt;-565.0,-1140.0&gt;-&lt;-620.0,-1145.0&gt;-&lt;-687.0,-1159.0&gt;&gt; = 5.1944289077348

* u18BB1.022: B&lt;&lt;455.0,862.0&gt;-&lt;431.0,860.0&gt;-&lt;435.0,860.0&gt;&gt;/B&lt;&lt;435.0,860.0&gt;-&lt;380.0,855.0&gt;-&lt;313.0,841.0&gt;&gt; = 5.1944289077348

* u18BB1.023: B&lt;&lt;455.0,362.0&gt;-&lt;431.0,360.0&gt;-&lt;435.0,360.0&gt;&gt;/B&lt;&lt;435.0,360.0&gt;-&lt;380.0,355.0&gt;-&lt;313.0,341.0&gt;&gt; = 5.1944289077348

* u18BEA (U+18BEA): B&lt;&lt;598.0,608.0&gt;-&lt;508.0,600.0&gt;-&lt;524.0,601.0&gt;&gt;/B&lt;&lt;524.0,601.0&gt;-&lt;390.0,588.0&gt;-&lt;347.0,583.0&gt;&gt; = 1.9648704030421524

* u18BEA.001: B&lt;&lt;598.0,2108.0&gt;-&lt;508.0,2100.0&gt;-&lt;524.0,2101.0&gt;&gt;/B&lt;&lt;524.0,2101.0&gt;-&lt;390.0,2088.0&gt;-&lt;347.0,2083.0&gt;&gt; = 1.9648704030421524

* u18BEA.002: B&lt;&lt;1098.0,2108.0&gt;-&lt;1008.0,2100.0&gt;-&lt;1024.0,2101.0&gt;&gt;/B&lt;&lt;1024.0,2101.0&gt;-&lt;890.0,2088.0&gt;-&lt;847.0,2083.0&gt;&gt; = 1.9648704030421524

* u18BEA.003: B&lt;&lt;-402.0,2108.0&gt;-&lt;-492.0,2100.0&gt;-&lt;-476.0,2101.0&gt;&gt;/B&lt;&lt;-476.0,2101.0&gt;-&lt;-610.0,2088.0&gt;-&lt;-653.0,2083.0&gt;&gt; = 1.9648704030421524

* u18BEA.004: B&lt;&lt;598.0,1608.0&gt;-&lt;508.0,1600.0&gt;-&lt;524.0,1601.0&gt;&gt;/B&lt;&lt;524.0,1601.0&gt;-&lt;390.0,1588.0&gt;-&lt;347.0,1583.0&gt;&gt; = 1.9648704030421524

* u18BEA.005: B&lt;&lt;1098.0,1608.0&gt;-&lt;1008.0,1600.0&gt;-&lt;1024.0,1601.0&gt;&gt;/B&lt;&lt;1024.0,1601.0&gt;-&lt;890.0,1588.0&gt;-&lt;847.0,1583.0&gt;&gt; = 1.9648704030421524

* u18BEA.006: B&lt;&lt;-402.0,1608.0&gt;-&lt;-492.0,1600.0&gt;-&lt;-476.0,1601.0&gt;&gt;/B&lt;&lt;-476.0,1601.0&gt;-&lt;-610.0,1588.0&gt;-&lt;-653.0,1583.0&gt;&gt; = 1.9648704030421524

* u18BEA.007: B&lt;&lt;-1402.0,1108.0&gt;-&lt;-1492.0,1100.0&gt;-&lt;-1476.0,1101.0&gt;&gt;/B&lt;&lt;-1476.0,1101.0&gt;-&lt;-1610.0,1088.0&gt;-&lt;-1653.0,1083.0&gt;&gt; = 1.9648704030421524

* u18BEA.008: B&lt;&lt;1098.0,1108.0&gt;-&lt;1008.0,1100.0&gt;-&lt;1024.0,1101.0&gt;&gt;/B&lt;&lt;1024.0,1101.0&gt;-&lt;890.0,1088.0&gt;-&lt;847.0,1083.0&gt;&gt; = 1.9648704030421524

* u18BEA.009: B&lt;&lt;-402.0,1108.0&gt;-&lt;-492.0,1100.0&gt;-&lt;-476.0,1101.0&gt;&gt;/B&lt;&lt;-476.0,1101.0&gt;-&lt;-610.0,1088.0&gt;-&lt;-653.0,1083.0&gt;&gt; = 1.9648704030421524

* u18BEA.010: B&lt;&lt;-1402.0,608.0&gt;-&lt;-1492.0,600.0&gt;-&lt;-1476.0,601.0&gt;&gt;/B&lt;&lt;-1476.0,601.0&gt;-&lt;-1610.0,588.0&gt;-&lt;-1653.0,583.0&gt;&gt; = 1.9648704030421524

* u18BEA.011: B&lt;&lt;1098.0,608.0&gt;-&lt;1008.0,600.0&gt;-&lt;1024.0,601.0&gt;&gt;/B&lt;&lt;1024.0,601.0&gt;-&lt;890.0,588.0&gt;-&lt;847.0,583.0&gt;&gt; = 1.9648704030421524

* u18BEA.012: B&lt;&lt;-402.0,608.0&gt;-&lt;-492.0,600.0&gt;-&lt;-476.0,601.0&gt;&gt;/B&lt;&lt;-476.0,601.0&gt;-&lt;-610.0,588.0&gt;-&lt;-653.0,583.0&gt;&gt; = 1.9648704030421524

* u18BEA.013: B&lt;&lt;-1402.0,108.0&gt;-&lt;-1492.0,100.0&gt;-&lt;-1476.0,101.0&gt;&gt;/B&lt;&lt;-1476.0,101.0&gt;-&lt;-1610.0,88.0&gt;-&lt;-1653.0,83.0&gt;&gt; = 1.9648704030421524

* u18BEA.014: B&lt;&lt;-902.0,108.0&gt;-&lt;-992.0,100.0&gt;-&lt;-976.0,101.0&gt;&gt;/B&lt;&lt;-976.0,101.0&gt;-&lt;-1110.0,88.0&gt;-&lt;-1153.0,83.0&gt;&gt; = 1.9648704030421524

* u18BEA.015: B&lt;&lt;-402.0,108.0&gt;-&lt;-492.0,100.0&gt;-&lt;-476.0,101.0&gt;&gt;/B&lt;&lt;-476.0,101.0&gt;-&lt;-610.0,88.0&gt;-&lt;-653.0,83.0&gt;&gt; = 1.9648704030421524

* u18BEA.016: B&lt;&lt;-1402.0,-392.0&gt;-&lt;-1492.0,-400.0&gt;-&lt;-1476.0,-399.0&gt;&gt;/B&lt;&lt;-1476.0,-399.0&gt;-&lt;-1610.0,-412.0&gt;-&lt;-1653.0,-417.0&gt;&gt; = 1.9648704030421524

* u18BEA.017: B&lt;&lt;-902.0,-392.0&gt;-&lt;-992.0,-400.0&gt;-&lt;-976.0,-399.0&gt;&gt;/B&lt;&lt;-976.0,-399.0&gt;-&lt;-1110.0,-412.0&gt;-&lt;-1153.0,-417.0&gt;&gt; = 1.9648704030421524

* u18BEA.018: B&lt;&lt;-402.0,-392.0&gt;-&lt;-492.0,-400.0&gt;-&lt;-476.0,-399.0&gt;&gt;/B&lt;&lt;-476.0,-399.0&gt;-&lt;-610.0,-412.0&gt;-&lt;-653.0,-417.0&gt;&gt; = 1.9648704030421524

* u18BEA.019: B&lt;&lt;-1402.0,-892.0&gt;-&lt;-1492.0,-900.0&gt;-&lt;-1476.0,-899.0&gt;&gt;/B&lt;&lt;-1476.0,-899.0&gt;-&lt;-1610.0,-912.0&gt;-&lt;-1653.0,-917.0&gt;&gt; = 1.9648704030421524

* u18BEA.020: B&lt;&lt;-902.0,-892.0&gt;-&lt;-992.0,-900.0&gt;-&lt;-976.0,-899.0&gt;&gt;/B&lt;&lt;-976.0,-899.0&gt;-&lt;-1110.0,-912.0&gt;-&lt;-1153.0,-917.0&gt;&gt; = 1.9648704030421524

* u18BEA.021: B&lt;&lt;-402.0,-892.0&gt;-&lt;-492.0,-900.0&gt;-&lt;-476.0,-899.0&gt;&gt;/B&lt;&lt;-476.0,-899.0&gt;-&lt;-610.0,-912.0&gt;-&lt;-653.0,-917.0&gt;&gt; = 1.9648704030421524

* u18BEA.022: B&lt;&lt;598.0,1108.0&gt;-&lt;508.0,1100.0&gt;-&lt;524.0,1101.0&gt;&gt;/B&lt;&lt;524.0,1101.0&gt;-&lt;390.0,1088.0&gt;-&lt;347.0,1083.0&gt;&gt; = 1.9648704030421524

* u18BEA.023: B&lt;&lt;598.0,608.0&gt;-&lt;508.0,600.0&gt;-&lt;524.0,601.0&gt;&gt;/B&lt;&lt;524.0,601.0&gt;-&lt;390.0,588.0&gt;-&lt;347.0,583.0&gt;&gt; = 1.9648704030421524

* u18BEB (U+18BEB): B&lt;&lt;599.0,608.0&gt;-&lt;502.0,600.0&gt;-&lt;522.0,601.0&gt;&gt;/B&lt;&lt;522.0,601.0&gt;-&lt;493.0,598.0&gt;-&lt;427.0,592.0&gt;&gt; = 3.0437358876587015

* u18BEB.001: B&lt;&lt;599.0,2108.0&gt;-&lt;502.0,2100.0&gt;-&lt;522.0,2101.0&gt;&gt;/B&lt;&lt;522.0,2101.0&gt;-&lt;493.0,2098.0&gt;-&lt;427.0,2092.0&gt;&gt; = 3.0437358876587015

* u18BEB.002: B&lt;&lt;1099.0,2108.0&gt;-&lt;1002.0,2100.0&gt;-&lt;1022.0,2101.0&gt;&gt;/B&lt;&lt;1022.0,2101.0&gt;-&lt;993.0,2098.0&gt;-&lt;927.0,2092.0&gt;&gt; = 3.0437358876587015

* u18BEB.003: B&lt;&lt;-401.0,2108.0&gt;-&lt;-498.0,2100.0&gt;-&lt;-478.0,2101.0&gt;&gt;/B&lt;&lt;-478.0,2101.0&gt;-&lt;-507.0,2098.0&gt;-&lt;-573.0,2092.0&gt;&gt; = 3.0437358876587015

* u18BEB.004: B&lt;&lt;599.0,1608.0&gt;-&lt;502.0,1600.0&gt;-&lt;522.0,1601.0&gt;&gt;/B&lt;&lt;522.0,1601.0&gt;-&lt;493.0,1598.0&gt;-&lt;427.0,1592.0&gt;&gt; = 3.0437358876587015

* u18BEB.005: B&lt;&lt;1099.0,1608.0&gt;-&lt;1002.0,1600.0&gt;-&lt;1022.0,1601.0&gt;&gt;/B&lt;&lt;1022.0,1601.0&gt;-&lt;993.0,1598.0&gt;-&lt;927.0,1592.0&gt;&gt; = 3.0437358876587015

* u18BEB.006: B&lt;&lt;-401.0,1608.0&gt;-&lt;-498.0,1600.0&gt;-&lt;-478.0,1601.0&gt;&gt;/B&lt;&lt;-478.0,1601.0&gt;-&lt;-507.0,1598.0&gt;-&lt;-573.0,1592.0&gt;&gt; = 3.0437358876587015

* u18BEB.007: B&lt;&lt;-1401.0,1108.0&gt;-&lt;-1498.0,1100.0&gt;-&lt;-1478.0,1101.0&gt;&gt;/B&lt;&lt;-1478.0,1101.0&gt;-&lt;-1507.0,1098.0&gt;-&lt;-1573.0,1092.0&gt;&gt; = 3.0437358876587015

* u18BEB.008: B&lt;&lt;1099.0,1108.0&gt;-&lt;1002.0,1100.0&gt;-&lt;1022.0,1101.0&gt;&gt;/B&lt;&lt;1022.0,1101.0&gt;-&lt;993.0,1098.0&gt;-&lt;927.0,1092.0&gt;&gt; = 3.0437358876587015

* u18BEB.009: B&lt;&lt;-401.0,1108.0&gt;-&lt;-498.0,1100.0&gt;-&lt;-478.0,1101.0&gt;&gt;/B&lt;&lt;-478.0,1101.0&gt;-&lt;-507.0,1098.0&gt;-&lt;-573.0,1092.0&gt;&gt; = 3.0437358876587015

* u18BEB.010: B&lt;&lt;-1401.0,608.0&gt;-&lt;-1498.0,600.0&gt;-&lt;-1478.0,601.0&gt;&gt;/B&lt;&lt;-1478.0,601.0&gt;-&lt;-1507.0,598.0&gt;-&lt;-1573.0,592.0&gt;&gt; = 3.0437358876587015

* u18BEB.011: B&lt;&lt;1099.0,608.0&gt;-&lt;1002.0,600.0&gt;-&lt;1022.0,601.0&gt;&gt;/B&lt;&lt;1022.0,601.0&gt;-&lt;993.0,598.0&gt;-&lt;927.0,592.0&gt;&gt; = 3.0437358876587015

* u18BEB.012: B&lt;&lt;-401.0,608.0&gt;-&lt;-498.0,600.0&gt;-&lt;-478.0,601.0&gt;&gt;/B&lt;&lt;-478.0,601.0&gt;-&lt;-507.0,598.0&gt;-&lt;-573.0,592.0&gt;&gt; = 3.0437358876587015

* u18BEB.013: B&lt;&lt;-1401.0,108.0&gt;-&lt;-1498.0,100.0&gt;-&lt;-1478.0,101.0&gt;&gt;/B&lt;&lt;-1478.0,101.0&gt;-&lt;-1507.0,98.0&gt;-&lt;-1573.0,92.0&gt;&gt; = 3.0437358876587015

* u18BEB.014: B&lt;&lt;-901.0,108.0&gt;-&lt;-998.0,100.0&gt;-&lt;-978.0,101.0&gt;&gt;/B&lt;&lt;-978.0,101.0&gt;-&lt;-1007.0,98.0&gt;-&lt;-1073.0,92.0&gt;&gt; = 3.0437358876587015

* u18BEB.015: B&lt;&lt;-401.0,108.0&gt;-&lt;-498.0,100.0&gt;-&lt;-478.0,101.0&gt;&gt;/B&lt;&lt;-478.0,101.0&gt;-&lt;-507.0,98.0&gt;-&lt;-573.0,92.0&gt;&gt; = 3.0437358876587015

* u18BEB.016: B&lt;&lt;-1401.0,-392.0&gt;-&lt;-1498.0,-400.0&gt;-&lt;-1478.0,-399.0&gt;&gt;/B&lt;&lt;-1478.0,-399.0&gt;-&lt;-1507.0,-402.0&gt;-&lt;-1573.0,-408.0&gt;&gt; = 3.0437358876587015

* u18BEB.017: B&lt;&lt;-901.0,-392.0&gt;-&lt;-998.0,-400.0&gt;-&lt;-978.0,-399.0&gt;&gt;/B&lt;&lt;-978.0,-399.0&gt;-&lt;-1007.0,-402.0&gt;-&lt;-1073.0,-408.0&gt;&gt; = 3.0437358876587015

* u18BEB.018: B&lt;&lt;-401.0,-392.0&gt;-&lt;-498.0,-400.0&gt;-&lt;-478.0,-399.0&gt;&gt;/B&lt;&lt;-478.0,-399.0&gt;-&lt;-507.0,-402.0&gt;-&lt;-573.0,-408.0&gt;&gt; = 3.0437358876587015

* u18BEB.019: B&lt;&lt;-1401.0,-892.0&gt;-&lt;-1498.0,-900.0&gt;-&lt;-1478.0,-899.0&gt;&gt;/B&lt;&lt;-1478.0,-899.0&gt;-&lt;-1507.0,-902.0&gt;-&lt;-1573.0,-908.0&gt;&gt; = 3.0437358876587015

* u18BEB.020: B&lt;&lt;-901.0,-892.0&gt;-&lt;-998.0,-900.0&gt;-&lt;-978.0,-899.0&gt;&gt;/B&lt;&lt;-978.0,-899.0&gt;-&lt;-1007.0,-902.0&gt;-&lt;-1073.0,-908.0&gt;&gt; = 3.0437358876587015

* u18BEB.021: B&lt;&lt;-401.0,-892.0&gt;-&lt;-498.0,-900.0&gt;-&lt;-478.0,-899.0&gt;&gt;/B&lt;&lt;-478.0,-899.0&gt;-&lt;-507.0,-902.0&gt;-&lt;-573.0,-908.0&gt;&gt; = 3.0437358876587015

* u18BEB.022: B&lt;&lt;599.0,1108.0&gt;-&lt;502.0,1100.0&gt;-&lt;522.0,1101.0&gt;&gt;/B&lt;&lt;522.0,1101.0&gt;-&lt;493.0,1098.0&gt;-&lt;427.0,1092.0&gt;&gt; = 3.0437358876587015

* u18BEB.023: B&lt;&lt;599.0,608.0&gt;-&lt;502.0,600.0&gt;-&lt;522.0,601.0&gt;&gt;/B&lt;&lt;522.0,601.0&gt;-&lt;493.0,598.0&gt;-&lt;427.0,592.0&gt;&gt; = 3.0437358876587015

* u18C0A (U+18C0A): B&lt;&lt;899.0,514.0&gt;-&lt;801.0,505.0&gt;-&lt;807.0,506.0&gt;&gt;/B&lt;&lt;807.0,506.0&gt;-&lt;688.0,496.0&gt;-&lt;578.0,485.0&gt;&gt; = 4.6588364489565155

* u18C0A.001: B&lt;&lt;899.0,2014.0&gt;-&lt;801.0,2005.0&gt;-&lt;807.0,2006.0&gt;&gt;/B&lt;&lt;807.0,2006.0&gt;-&lt;688.0,1996.0&gt;-&lt;578.0,1985.0&gt;&gt; = 4.6588364489565155

* u18C0A.002: B&lt;&lt;1399.0,2014.0&gt;-&lt;1301.0,2005.0&gt;-&lt;1307.0,2006.0&gt;&gt;/B&lt;&lt;1307.0,2006.0&gt;-&lt;1188.0,1996.0&gt;-&lt;1078.0,1985.0&gt;&gt; = 4.6588364489565155

* u18C0A.003: B&lt;&lt;-101.0,2014.0&gt;-&lt;-199.0,2005.0&gt;-&lt;-193.0,2006.0&gt;&gt;/B&lt;&lt;-193.0,2006.0&gt;-&lt;-312.0,1996.0&gt;-&lt;-422.0,1985.0&gt;&gt; = 4.6588364489565155

* u18C0A.004: B&lt;&lt;899.0,1514.0&gt;-&lt;801.0,1505.0&gt;-&lt;807.0,1506.0&gt;&gt;/B&lt;&lt;807.0,1506.0&gt;-&lt;688.0,1496.0&gt;-&lt;578.0,1485.0&gt;&gt; = 4.6588364489565155

* u18C0A.005: B&lt;&lt;1399.0,1514.0&gt;-&lt;1301.0,1505.0&gt;-&lt;1307.0,1506.0&gt;&gt;/B&lt;&lt;1307.0,1506.0&gt;-&lt;1188.0,1496.0&gt;-&lt;1078.0,1485.0&gt;&gt; = 4.6588364489565155

* u18C0A.006: B&lt;&lt;-101.0,1514.0&gt;-&lt;-199.0,1505.0&gt;-&lt;-193.0,1506.0&gt;&gt;/B&lt;&lt;-193.0,1506.0&gt;-&lt;-312.0,1496.0&gt;-&lt;-422.0,1485.0&gt;&gt; = 4.6588364489565155

* u18C0A.007: B&lt;&lt;-1101.0,1014.0&gt;-&lt;-1199.0,1005.0&gt;-&lt;-1193.0,1006.0&gt;&gt;/B&lt;&lt;-1193.0,1006.0&gt;-&lt;-1312.0,996.0&gt;-&lt;-1422.0,985.0&gt;&gt; = 4.6588364489565155

* u18C0A.008: B&lt;&lt;1399.0,1014.0&gt;-&lt;1301.0,1005.0&gt;-&lt;1307.0,1006.0&gt;&gt;/B&lt;&lt;1307.0,1006.0&gt;-&lt;1188.0,996.0&gt;-&lt;1078.0,985.0&gt;&gt; = 4.6588364489565155

* u18C0A.009: B&lt;&lt;-101.0,1014.0&gt;-&lt;-199.0,1005.0&gt;-&lt;-193.0,1006.0&gt;&gt;/B&lt;&lt;-193.0,1006.0&gt;-&lt;-312.0,996.0&gt;-&lt;-422.0,985.0&gt;&gt; = 4.6588364489565155

* u18C0A.010: B&lt;&lt;-1101.0,514.0&gt;-&lt;-1199.0,505.0&gt;-&lt;-1193.0,506.0&gt;&gt;/B&lt;&lt;-1193.0,506.0&gt;-&lt;-1312.0,496.0&gt;-&lt;-1422.0,485.0&gt;&gt; = 4.6588364489565155

* u18C0A.011: B&lt;&lt;1399.0,514.0&gt;-&lt;1301.0,505.0&gt;-&lt;1307.0,506.0&gt;&gt;/B&lt;&lt;1307.0,506.0&gt;-&lt;1188.0,496.0&gt;-&lt;1078.0,485.0&gt;&gt; = 4.6588364489565155

* u18C0A.012: B&lt;&lt;-101.0,514.0&gt;-&lt;-199.0,505.0&gt;-&lt;-193.0,506.0&gt;&gt;/B&lt;&lt;-193.0,506.0&gt;-&lt;-312.0,496.0&gt;-&lt;-422.0,485.0&gt;&gt; = 4.6588364489565155

* u18C0A.013: B&lt;&lt;-1101.0,14.0&gt;-&lt;-1199.0,5.0&gt;-&lt;-1193.0,6.0&gt;&gt;/B&lt;&lt;-1193.0,6.0&gt;-&lt;-1312.0,-4.0&gt;-&lt;-1422.0,-15.0&gt;&gt; = 4.6588364489565155

* u18C0A.014: B&lt;&lt;-601.0,14.0&gt;-&lt;-699.0,5.0&gt;-&lt;-693.0,6.0&gt;&gt;/B&lt;&lt;-693.0,6.0&gt;-&lt;-812.0,-4.0&gt;-&lt;-922.0,-15.0&gt;&gt; = 4.6588364489565155

* u18C0A.015: B&lt;&lt;-101.0,14.0&gt;-&lt;-199.0,5.0&gt;-&lt;-193.0,6.0&gt;&gt;/B&lt;&lt;-193.0,6.0&gt;-&lt;-312.0,-4.0&gt;-&lt;-422.0,-15.0&gt;&gt; = 4.6588364489565155

* u18C0A.016: B&lt;&lt;-1101.0,-486.0&gt;-&lt;-1199.0,-495.0&gt;-&lt;-1193.0,-494.0&gt;&gt;/B&lt;&lt;-1193.0,-494.0&gt;-&lt;-1312.0,-504.0&gt;-&lt;-1422.0,-515.0&gt;&gt; = 4.6588364489565155

* u18C0A.017: B&lt;&lt;-601.0,-486.0&gt;-&lt;-699.0,-495.0&gt;-&lt;-693.0,-494.0&gt;&gt;/B&lt;&lt;-693.0,-494.0&gt;-&lt;-812.0,-504.0&gt;-&lt;-922.0,-515.0&gt;&gt; = 4.6588364489565155

* u18C0A.018: B&lt;&lt;-101.0,-486.0&gt;-&lt;-199.0,-495.0&gt;-&lt;-193.0,-494.0&gt;&gt;/B&lt;&lt;-193.0,-494.0&gt;-&lt;-312.0,-504.0&gt;-&lt;-422.0,-515.0&gt;&gt; = 4.6588364489565155

* u18C0A.019: B&lt;&lt;-1101.0,-986.0&gt;-&lt;-1199.0,-995.0&gt;-&lt;-1193.0,-994.0&gt;&gt;/B&lt;&lt;-1193.0,-994.0&gt;-&lt;-1312.0,-1004.0&gt;-&lt;-1422.0,-1015.0&gt;&gt; = 4.6588364489565155

* u18C0A.020: B&lt;&lt;-601.0,-986.0&gt;-&lt;-699.0,-995.0&gt;-&lt;-693.0,-994.0&gt;&gt;/B&lt;&lt;-693.0,-994.0&gt;-&lt;-812.0,-1004.0&gt;-&lt;-922.0,-1015.0&gt;&gt; = 4.6588364489565155

* u18C0A.021: B&lt;&lt;-101.0,-986.0&gt;-&lt;-199.0,-995.0&gt;-&lt;-193.0,-994.0&gt;&gt;/B&lt;&lt;-193.0,-994.0&gt;-&lt;-312.0,-1004.0&gt;-&lt;-422.0,-1015.0&gt;&gt; = 4.6588364489565155

* u18C0A.022: B&lt;&lt;899.0,1014.0&gt;-&lt;801.0,1005.0&gt;-&lt;807.0,1006.0&gt;&gt;/B&lt;&lt;807.0,1006.0&gt;-&lt;688.0,996.0&gt;-&lt;578.0,985.0&gt;&gt; = 4.6588364489565155

* u18C0A.023: B&lt;&lt;899.0,514.0&gt;-&lt;801.0,505.0&gt;-&lt;807.0,506.0&gt;&gt;/B&lt;&lt;807.0,506.0&gt;-&lt;688.0,496.0&gt;-&lt;578.0,485.0&gt;&gt; = 4.6588364489565155

* u18C0B (U+18C0B): B&lt;&lt;859.0,514.0&gt;-&lt;761.0,505.0&gt;-&lt;767.0,506.0&gt;&gt;/B&lt;&lt;767.0,506.0&gt;-&lt;641.0,496.0&gt;-&lt;524.0,484.0&gt;&gt; = 4.924549700118923

* u18C0B.001: B&lt;&lt;859.0,2014.0&gt;-&lt;761.0,2005.0&gt;-&lt;767.0,2006.0&gt;&gt;/B&lt;&lt;767.0,2006.0&gt;-&lt;641.0,1996.0&gt;-&lt;524.0,1984.0&gt;&gt; = 4.924549700118923

* u18C0B.002: B&lt;&lt;1359.0,2014.0&gt;-&lt;1261.0,2005.0&gt;-&lt;1267.0,2006.0&gt;&gt;/B&lt;&lt;1267.0,2006.0&gt;-&lt;1141.0,1996.0&gt;-&lt;1024.0,1984.0&gt;&gt; = 4.924549700118923

* u18C0B.003: B&lt;&lt;-141.0,2014.0&gt;-&lt;-239.0,2005.0&gt;-&lt;-233.0,2006.0&gt;&gt;/B&lt;&lt;-233.0,2006.0&gt;-&lt;-359.0,1996.0&gt;-&lt;-476.0,1984.0&gt;&gt; = 4.924549700118923

* u18C0B.004: B&lt;&lt;859.0,1514.0&gt;-&lt;761.0,1505.0&gt;-&lt;767.0,1506.0&gt;&gt;/B&lt;&lt;767.0,1506.0&gt;-&lt;641.0,1496.0&gt;-&lt;524.0,1484.0&gt;&gt; = 4.924549700118923

* u18C0B.005: B&lt;&lt;1359.0,1514.0&gt;-&lt;1261.0,1505.0&gt;-&lt;1267.0,1506.0&gt;&gt;/B&lt;&lt;1267.0,1506.0&gt;-&lt;1141.0,1496.0&gt;-&lt;1024.0,1484.0&gt;&gt; = 4.924549700118923

* u18C0B.006: B&lt;&lt;-141.0,1514.0&gt;-&lt;-239.0,1505.0&gt;-&lt;-233.0,1506.0&gt;&gt;/B&lt;&lt;-233.0,1506.0&gt;-&lt;-359.0,1496.0&gt;-&lt;-476.0,1484.0&gt;&gt; = 4.924549700118923

* u18C0B.007: B&lt;&lt;-1141.0,1014.0&gt;-&lt;-1239.0,1005.0&gt;-&lt;-1233.0,1006.0&gt;&gt;/B&lt;&lt;-1233.0,1006.0&gt;-&lt;-1359.0,996.0&gt;-&lt;-1476.0,984.0&gt;&gt; = 4.924549700118923

* u18C0B.008: B&lt;&lt;1359.0,1014.0&gt;-&lt;1261.0,1005.0&gt;-&lt;1267.0,1006.0&gt;&gt;/B&lt;&lt;1267.0,1006.0&gt;-&lt;1141.0,996.0&gt;-&lt;1024.0,984.0&gt;&gt; = 4.924549700118923

* u18C0B.009: B&lt;&lt;-141.0,1014.0&gt;-&lt;-239.0,1005.0&gt;-&lt;-233.0,1006.0&gt;&gt;/B&lt;&lt;-233.0,1006.0&gt;-&lt;-359.0,996.0&gt;-&lt;-476.0,984.0&gt;&gt; = 4.924549700118923

* u18C0B.010: B&lt;&lt;-1141.0,514.0&gt;-&lt;-1239.0,505.0&gt;-&lt;-1233.0,506.0&gt;&gt;/B&lt;&lt;-1233.0,506.0&gt;-&lt;-1359.0,496.0&gt;-&lt;-1476.0,484.0&gt;&gt; = 4.924549700118923

* u18C0B.011: B&lt;&lt;1359.0,514.0&gt;-&lt;1261.0,505.0&gt;-&lt;1267.0,506.0&gt;&gt;/B&lt;&lt;1267.0,506.0&gt;-&lt;1141.0,496.0&gt;-&lt;1024.0,484.0&gt;&gt; = 4.924549700118923

* u18C0B.012: B&lt;&lt;-141.0,514.0&gt;-&lt;-239.0,505.0&gt;-&lt;-233.0,506.0&gt;&gt;/B&lt;&lt;-233.0,506.0&gt;-&lt;-359.0,496.0&gt;-&lt;-476.0,484.0&gt;&gt; = 4.924549700118923

* u18C0B.013: B&lt;&lt;-1141.0,14.0&gt;-&lt;-1239.0,5.0&gt;-&lt;-1233.0,6.0&gt;&gt;/B&lt;&lt;-1233.0,6.0&gt;-&lt;-1359.0,-4.0&gt;-&lt;-1476.0,-16.0&gt;&gt; = 4.924549700118923

* u18C0B.014: B&lt;&lt;-641.0,14.0&gt;-&lt;-739.0,5.0&gt;-&lt;-733.0,6.0&gt;&gt;/B&lt;&lt;-733.0,6.0&gt;-&lt;-859.0,-4.0&gt;-&lt;-976.0,-16.0&gt;&gt; = 4.924549700118923

* u18C0B.015: B&lt;&lt;-141.0,14.0&gt;-&lt;-239.0,5.0&gt;-&lt;-233.0,6.0&gt;&gt;/B&lt;&lt;-233.0,6.0&gt;-&lt;-359.0,-4.0&gt;-&lt;-476.0,-16.0&gt;&gt; = 4.924549700118923

* u18C0B.016: B&lt;&lt;-1141.0,-486.0&gt;-&lt;-1239.0,-495.0&gt;-&lt;-1233.0,-494.0&gt;&gt;/B&lt;&lt;-1233.0,-494.0&gt;-&lt;-1359.0,-504.0&gt;-&lt;-1476.0,-516.0&gt;&gt; = 4.924549700118923

* u18C0B.017: B&lt;&lt;-641.0,-486.0&gt;-&lt;-739.0,-495.0&gt;-&lt;-733.0,-494.0&gt;&gt;/B&lt;&lt;-733.0,-494.0&gt;-&lt;-859.0,-504.0&gt;-&lt;-976.0,-516.0&gt;&gt; = 4.924549700118923

* u18C0B.018: B&lt;&lt;-141.0,-486.0&gt;-&lt;-239.0,-495.0&gt;-&lt;-233.0,-494.0&gt;&gt;/B&lt;&lt;-233.0,-494.0&gt;-&lt;-359.0,-504.0&gt;-&lt;-476.0,-516.0&gt;&gt; = 4.924549700118923

* u18C0B.019: B&lt;&lt;-1141.0,-986.0&gt;-&lt;-1239.0,-995.0&gt;-&lt;-1233.0,-994.0&gt;&gt;/B&lt;&lt;-1233.0,-994.0&gt;-&lt;-1359.0,-1004.0&gt;-&lt;-1476.0,-1016.0&gt;&gt; = 4.924549700118923

* u18C0B.020: B&lt;&lt;-641.0,-986.0&gt;-&lt;-739.0,-995.0&gt;-&lt;-733.0,-994.0&gt;&gt;/B&lt;&lt;-733.0,-994.0&gt;-&lt;-859.0,-1004.0&gt;-&lt;-976.0,-1016.0&gt;&gt; = 4.924549700118923

* u18C0B.021: B&lt;&lt;-141.0,-986.0&gt;-&lt;-239.0,-995.0&gt;-&lt;-233.0,-994.0&gt;&gt;/B&lt;&lt;-233.0,-994.0&gt;-&lt;-359.0,-1004.0&gt;-&lt;-476.0,-1016.0&gt;&gt; = 4.924549700118923

* u18C0B.022: B&lt;&lt;859.0,1014.0&gt;-&lt;761.0,1005.0&gt;-&lt;767.0,1006.0&gt;&gt;/B&lt;&lt;767.0,1006.0&gt;-&lt;641.0,996.0&gt;-&lt;524.0,984.0&gt;&gt; = 4.924549700118923

* u18C0B.023: B&lt;&lt;859.0,514.0&gt;-&lt;761.0,505.0&gt;-&lt;767.0,506.0&gt;&gt;/B&lt;&lt;767.0,506.0&gt;-&lt;641.0,496.0&gt;-&lt;524.0,484.0&gt;&gt; = 4.924549700118923

* u18C65 (U+18C65): B&lt;&lt;773.0,592.0&gt;-&lt;755.0,571.0&gt;-&lt;757.0,573.0&gt;&gt;/B&lt;&lt;757.0,573.0&gt;-&lt;706.0,512.0&gt;-&lt;660.0,464.0&gt;&gt; = 5.102165252358147

* u18C65.001: B&lt;&lt;773.0,2092.0&gt;-&lt;755.0,2071.0&gt;-&lt;757.0,2073.0&gt;&gt;/B&lt;&lt;757.0,2073.0&gt;-&lt;706.0,2012.0&gt;-&lt;660.0,1964.0&gt;&gt; = 5.102165252358147

* u18C65.002: B&lt;&lt;1273.0,2092.0&gt;-&lt;1255.0,2071.0&gt;-&lt;1257.0,2073.0&gt;&gt;/B&lt;&lt;1257.0,2073.0&gt;-&lt;1206.0,2012.0&gt;-&lt;1160.0,1964.0&gt;&gt; = 5.102165252358147

* u18C65.003: B&lt;&lt;-227.0,2092.0&gt;-&lt;-245.0,2071.0&gt;-&lt;-243.0,2073.0&gt;&gt;/B&lt;&lt;-243.0,2073.0&gt;-&lt;-294.0,2012.0&gt;-&lt;-340.0,1964.0&gt;&gt; = 5.102165252358147

* u18C65.004: B&lt;&lt;773.0,1592.0&gt;-&lt;755.0,1571.0&gt;-&lt;757.0,1573.0&gt;&gt;/B&lt;&lt;757.0,1573.0&gt;-&lt;706.0,1512.0&gt;-&lt;660.0,1464.0&gt;&gt; = 5.102165252358147

* u18C65.005: B&lt;&lt;1273.0,1592.0&gt;-&lt;1255.0,1571.0&gt;-&lt;1257.0,1573.0&gt;&gt;/B&lt;&lt;1257.0,1573.0&gt;-&lt;1206.0,1512.0&gt;-&lt;1160.0,1464.0&gt;&gt; = 5.102165252358147

* u18C65.006: B&lt;&lt;-227.0,1592.0&gt;-&lt;-245.0,1571.0&gt;-&lt;-243.0,1573.0&gt;&gt;/B&lt;&lt;-243.0,1573.0&gt;-&lt;-294.0,1512.0&gt;-&lt;-340.0,1464.0&gt;&gt; = 5.102165252358147

* u18C65.007: B&lt;&lt;-1227.0,1092.0&gt;-&lt;-1245.0,1071.0&gt;-&lt;-1243.0,1073.0&gt;&gt;/B&lt;&lt;-1243.0,1073.0&gt;-&lt;-1294.0,1012.0&gt;-&lt;-1340.0,964.0&gt;&gt; = 5.102165252358147

* u18C65.008: B&lt;&lt;1273.0,1092.0&gt;-&lt;1255.0,1071.0&gt;-&lt;1257.0,1073.0&gt;&gt;/B&lt;&lt;1257.0,1073.0&gt;-&lt;1206.0,1012.0&gt;-&lt;1160.0,964.0&gt;&gt; = 5.102165252358147

* u18C65.009: B&lt;&lt;-227.0,1092.0&gt;-&lt;-245.0,1071.0&gt;-&lt;-243.0,1073.0&gt;&gt;/B&lt;&lt;-243.0,1073.0&gt;-&lt;-294.0,1012.0&gt;-&lt;-340.0,964.0&gt;&gt; = 5.102165252358147

* u18C65.010: B&lt;&lt;-1227.0,592.0&gt;-&lt;-1245.0,571.0&gt;-&lt;-1243.0,573.0&gt;&gt;/B&lt;&lt;-1243.0,573.0&gt;-&lt;-1294.0,512.0&gt;-&lt;-1340.0,464.0&gt;&gt; = 5.102165252358147

* u18C65.011: B&lt;&lt;1273.0,592.0&gt;-&lt;1255.0,571.0&gt;-&lt;1257.0,573.0&gt;&gt;/B&lt;&lt;1257.0,573.0&gt;-&lt;1206.0,512.0&gt;-&lt;1160.0,464.0&gt;&gt; = 5.102165252358147

* u18C65.012: B&lt;&lt;-227.0,592.0&gt;-&lt;-245.0,571.0&gt;-&lt;-243.0,573.0&gt;&gt;/B&lt;&lt;-243.0,573.0&gt;-&lt;-294.0,512.0&gt;-&lt;-340.0,464.0&gt;&gt; = 5.102165252358147

* u18C65.013: B&lt;&lt;-1227.0,92.0&gt;-&lt;-1245.0,71.0&gt;-&lt;-1243.0,73.0&gt;&gt;/B&lt;&lt;-1243.0,73.0&gt;-&lt;-1294.0,12.0&gt;-&lt;-1340.0,-36.0&gt;&gt; = 5.102165252358147

* u18C65.014: B&lt;&lt;-727.0,92.0&gt;-&lt;-745.0,71.0&gt;-&lt;-743.0,73.0&gt;&gt;/B&lt;&lt;-743.0,73.0&gt;-&lt;-794.0,12.0&gt;-&lt;-840.0,-36.0&gt;&gt; = 5.102165252358147

* u18C65.015: B&lt;&lt;-227.0,92.0&gt;-&lt;-245.0,71.0&gt;-&lt;-243.0,73.0&gt;&gt;/B&lt;&lt;-243.0,73.0&gt;-&lt;-294.0,12.0&gt;-&lt;-340.0,-36.0&gt;&gt; = 5.102165252358147

* u18C65.016: B&lt;&lt;-1227.0,-408.0&gt;-&lt;-1245.0,-429.0&gt;-&lt;-1243.0,-427.0&gt;&gt;/B&lt;&lt;-1243.0,-427.0&gt;-&lt;-1294.0,-488.0&gt;-&lt;-1340.0,-536.0&gt;&gt; = 5.102165252358147

* u18C65.017: B&lt;&lt;-727.0,-408.0&gt;-&lt;-745.0,-429.0&gt;-&lt;-743.0,-427.0&gt;&gt;/B&lt;&lt;-743.0,-427.0&gt;-&lt;-794.0,-488.0&gt;-&lt;-840.0,-536.0&gt;&gt; = 5.102165252358147

* u18C65.018: B&lt;&lt;-227.0,-408.0&gt;-&lt;-245.0,-429.0&gt;-&lt;-243.0,-427.0&gt;&gt;/B&lt;&lt;-243.0,-427.0&gt;-&lt;-294.0,-488.0&gt;-&lt;-340.0,-536.0&gt;&gt; = 5.102165252358147

* u18C65.019: B&lt;&lt;-1227.0,-908.0&gt;-&lt;-1245.0,-929.0&gt;-&lt;-1243.0,-927.0&gt;&gt;/B&lt;&lt;-1243.0,-927.0&gt;-&lt;-1294.0,-988.0&gt;-&lt;-1340.0,-1036.0&gt;&gt; = 5.102165252358147

* u18C65.020: B&lt;&lt;-727.0,-908.0&gt;-&lt;-745.0,-929.0&gt;-&lt;-743.0,-927.0&gt;&gt;/B&lt;&lt;-743.0,-927.0&gt;-&lt;-794.0,-988.0&gt;-&lt;-840.0,-1036.0&gt;&gt; = 5.102165252358147

* u18C65.021: B&lt;&lt;-227.0,-908.0&gt;-&lt;-245.0,-929.0&gt;-&lt;-243.0,-927.0&gt;&gt;/B&lt;&lt;-243.0,-927.0&gt;-&lt;-294.0,-988.0&gt;-&lt;-340.0,-1036.0&gt;&gt; = 5.102165252358147

* u18C65.022: B&lt;&lt;773.0,1092.0&gt;-&lt;755.0,1071.0&gt;-&lt;757.0,1073.0&gt;&gt;/B&lt;&lt;757.0,1073.0&gt;-&lt;706.0,1012.0&gt;-&lt;660.0,964.0&gt;&gt; = 5.102165252358147

* u18C65.023: B&lt;&lt;773.0,592.0&gt;-&lt;755.0,571.0&gt;-&lt;757.0,573.0&gt;&gt;/B&lt;&lt;757.0,573.0&gt;-&lt;706.0,512.0&gt;-&lt;660.0,464.0&gt;&gt; = 5.102165252358147

* u18CB2 (U+18CB2): B&lt;&lt;371.0,355.0&gt;-&lt;458.0,365.0&gt;-&lt;453.0,364.0&gt;&gt;/B&lt;&lt;453.0,364.0&gt;-&lt;478.0,367.0&gt;-&lt;492.5,375.0&gt;&gt; = 4.46715906138917

* u18CB2.001: B&lt;&lt;371.0,1855.0&gt;-&lt;458.0,1865.0&gt;-&lt;453.0,1864.0&gt;&gt;/B&lt;&lt;453.0,1864.0&gt;-&lt;478.0,1867.0&gt;-&lt;492.5,1875.0&gt;&gt; = 4.46715906138917

* u18CB2.002: B&lt;&lt;871.0,1855.0&gt;-&lt;958.0,1865.0&gt;-&lt;953.0,1864.0&gt;&gt;/B&lt;&lt;953.0,1864.0&gt;-&lt;978.0,1867.0&gt;-&lt;992.5,1875.0&gt;&gt; = 4.46715906138917

* u18CB2.003: B&lt;&lt;-629.0,1855.0&gt;-&lt;-542.0,1865.0&gt;-&lt;-547.0,1864.0&gt;&gt;/B&lt;&lt;-547.0,1864.0&gt;-&lt;-522.0,1867.0&gt;-&lt;-507.5,1875.0&gt;&gt; = 4.46715906138917

* u18CB2.004: B&lt;&lt;371.0,1355.0&gt;-&lt;458.0,1365.0&gt;-&lt;453.0,1364.0&gt;&gt;/B&lt;&lt;453.0,1364.0&gt;-&lt;478.0,1367.0&gt;-&lt;492.5,1375.0&gt;&gt; = 4.46715906138917

* u18CB2.005: B&lt;&lt;871.0,1355.0&gt;-&lt;958.0,1365.0&gt;-&lt;953.0,1364.0&gt;&gt;/B&lt;&lt;953.0,1364.0&gt;-&lt;978.0,1367.0&gt;-&lt;992.5,1375.0&gt;&gt; = 4.46715906138917

* u18CB2.006: B&lt;&lt;-629.0,1355.0&gt;-&lt;-542.0,1365.0&gt;-&lt;-547.0,1364.0&gt;&gt;/B&lt;&lt;-547.0,1364.0&gt;-&lt;-522.0,1367.0&gt;-&lt;-507.5,1375.0&gt;&gt; = 4.46715906138917

* u18CB2.007: B&lt;&lt;-1629.0,855.0&gt;-&lt;-1542.0,865.0&gt;-&lt;-1547.0,864.0&gt;&gt;/B&lt;&lt;-1547.0,864.0&gt;-&lt;-1522.0,867.0&gt;-&lt;-1507.5,875.0&gt;&gt; = 4.46715906138917

* u18CB2.008: B&lt;&lt;871.0,855.0&gt;-&lt;958.0,865.0&gt;-&lt;953.0,864.0&gt;&gt;/B&lt;&lt;953.0,864.0&gt;-&lt;978.0,867.0&gt;-&lt;992.5,875.0&gt;&gt; = 4.46715906138917

* u18CB2.009: B&lt;&lt;-629.0,855.0&gt;-&lt;-542.0,865.0&gt;-&lt;-547.0,864.0&gt;&gt;/B&lt;&lt;-547.0,864.0&gt;-&lt;-522.0,867.0&gt;-&lt;-507.5,875.0&gt;&gt; = 4.46715906138917

* u18CB2.010: B&lt;&lt;-1629.0,355.0&gt;-&lt;-1542.0,365.0&gt;-&lt;-1547.0,364.0&gt;&gt;/B&lt;&lt;-1547.0,364.0&gt;-&lt;-1522.0,367.0&gt;-&lt;-1507.5,375.0&gt;&gt; = 4.46715906138917

* u18CB2.011: B&lt;&lt;871.0,355.0&gt;-&lt;958.0,365.0&gt;-&lt;953.0,364.0&gt;&gt;/B&lt;&lt;953.0,364.0&gt;-&lt;978.0,367.0&gt;-&lt;992.5,375.0&gt;&gt; = 4.46715906138917

* u18CB2.012: B&lt;&lt;-629.0,355.0&gt;-&lt;-542.0,365.0&gt;-&lt;-547.0,364.0&gt;&gt;/B&lt;&lt;-547.0,364.0&gt;-&lt;-522.0,367.0&gt;-&lt;-507.5,375.0&gt;&gt; = 4.46715906138917

* u18CB2.013: B&lt;&lt;-1629.0,-145.0&gt;-&lt;-1542.0,-135.0&gt;-&lt;-1547.0,-136.0&gt;&gt;/B&lt;&lt;-1547.0,-136.0&gt;-&lt;-1522.0,-133.0&gt;-&lt;-1507.5,-125.0&gt;&gt; = 4.46715906138917

* u18CB2.014: B&lt;&lt;-1129.0,-145.0&gt;-&lt;-1042.0,-135.0&gt;-&lt;-1047.0,-136.0&gt;&gt;/B&lt;&lt;-1047.0,-136.0&gt;-&lt;-1022.0,-133.0&gt;-&lt;-1007.5,-125.0&gt;&gt; = 4.46715906138917

* u18CB2.015: B&lt;&lt;-629.0,-145.0&gt;-&lt;-542.0,-135.0&gt;-&lt;-547.0,-136.0&gt;&gt;/B&lt;&lt;-547.0,-136.0&gt;-&lt;-522.0,-133.0&gt;-&lt;-507.5,-125.0&gt;&gt; = 4.46715906138917

* u18CB2.016: B&lt;&lt;-1629.0,-645.0&gt;-&lt;-1542.0,-635.0&gt;-&lt;-1547.0,-636.0&gt;&gt;/B&lt;&lt;-1547.0,-636.0&gt;-&lt;-1522.0,-633.0&gt;-&lt;-1507.5,-625.0&gt;&gt; = 4.46715906138917

* u18CB2.017: B&lt;&lt;-1129.0,-645.0&gt;-&lt;-1042.0,-635.0&gt;-&lt;-1047.0,-636.0&gt;&gt;/B&lt;&lt;-1047.0,-636.0&gt;-&lt;-1022.0,-633.0&gt;-&lt;-1007.5,-625.0&gt;&gt; = 4.46715906138917

* u18CB2.018: B&lt;&lt;-629.0,-645.0&gt;-&lt;-542.0,-635.0&gt;-&lt;-547.0,-636.0&gt;&gt;/B&lt;&lt;-547.0,-636.0&gt;-&lt;-522.0,-633.0&gt;-&lt;-507.5,-625.0&gt;&gt; = 4.46715906138917

* u18CB2.019: B&lt;&lt;-1629.0,-1145.0&gt;-&lt;-1542.0,-1135.0&gt;-&lt;-1547.0,-1136.0&gt;&gt;/B&lt;&lt;-1547.0,-1136.0&gt;-&lt;-1522.0,-1133.0&gt;-&lt;-1507.5,-1125.0&gt;&gt; = 4.46715906138917

* u18CB2.020: B&lt;&lt;-1129.0,-1145.0&gt;-&lt;-1042.0,-1135.0&gt;-&lt;-1047.0,-1136.0&gt;&gt;/B&lt;&lt;-1047.0,-1136.0&gt;-&lt;-1022.0,-1133.0&gt;-&lt;-1007.5,-1125.0&gt;&gt; = 4.46715906138917

* u18CB2.021: B&lt;&lt;-629.0,-1145.0&gt;-&lt;-542.0,-1135.0&gt;-&lt;-547.0,-1136.0&gt;&gt;/B&lt;&lt;-547.0,-1136.0&gt;-&lt;-522.0,-1133.0&gt;-&lt;-507.5,-1125.0&gt;&gt; = 4.46715906138917

* u18CB2.022: B&lt;&lt;371.0,855.0&gt;-&lt;458.0,865.0&gt;-&lt;453.0,864.0&gt;&gt;/B&lt;&lt;453.0,864.0&gt;-&lt;478.0,867.0&gt;-&lt;492.5,875.0&gt;&gt; = 4.46715906138917

* u18CB2.023: B&lt;&lt;371.0,355.0&gt;-&lt;458.0,365.0&gt;-&lt;453.0,364.0&gt;&gt;/B&lt;&lt;453.0,364.0&gt;-&lt;478.0,367.0&gt;-&lt;492.5,375.0&gt;&gt; = 4.46715906138917

* u18CB3 (U+18CB3): B&lt;&lt;377.0,617.0&gt;-&lt;328.0,611.0&gt;-&lt;333.0,612.0&gt;&gt;/B&lt;&lt;333.0,612.0&gt;-&lt;303.0,610.0&gt;-&lt;254.0,602.0&gt;&gt; = 7.495857639729836

* u18CB3.001: B&lt;&lt;377.0,2117.0&gt;-&lt;328.0,2111.0&gt;-&lt;333.0,2112.0&gt;&gt;/B&lt;&lt;333.0,2112.0&gt;-&lt;303.0,2110.0&gt;-&lt;254.0,2102.0&gt;&gt; = 7.495857639729836

* u18CB3.002: B&lt;&lt;877.0,2117.0&gt;-&lt;828.0,2111.0&gt;-&lt;833.0,2112.0&gt;&gt;/B&lt;&lt;833.0,2112.0&gt;-&lt;803.0,2110.0&gt;-&lt;754.0,2102.0&gt;&gt; = 7.495857639729836

* u18CB3.003: B&lt;&lt;-623.0,2117.0&gt;-&lt;-672.0,2111.0&gt;-&lt;-667.0,2112.0&gt;&gt;/B&lt;&lt;-667.0,2112.0&gt;-&lt;-697.0,2110.0&gt;-&lt;-746.0,2102.0&gt;&gt; = 7.495857639729836

* u18CB3.004: B&lt;&lt;377.0,1617.0&gt;-&lt;328.0,1611.0&gt;-&lt;333.0,1612.0&gt;&gt;/B&lt;&lt;333.0,1612.0&gt;-&lt;303.0,1610.0&gt;-&lt;254.0,1602.0&gt;&gt; = 7.495857639729836

* u18CB3.005: B&lt;&lt;877.0,1617.0&gt;-&lt;828.0,1611.0&gt;-&lt;833.0,1612.0&gt;&gt;/B&lt;&lt;833.0,1612.0&gt;-&lt;803.0,1610.0&gt;-&lt;754.0,1602.0&gt;&gt; = 7.495857639729836

* u18CB3.006: B&lt;&lt;-623.0,1617.0&gt;-&lt;-672.0,1611.0&gt;-&lt;-667.0,1612.0&gt;&gt;/B&lt;&lt;-667.0,1612.0&gt;-&lt;-697.0,1610.0&gt;-&lt;-746.0,1602.0&gt;&gt; = 7.495857639729836

* u18CB3.007: B&lt;&lt;-1623.0,1117.0&gt;-&lt;-1672.0,1111.0&gt;-&lt;-1667.0,1112.0&gt;&gt;/B&lt;&lt;-1667.0,1112.0&gt;-&lt;-1697.0,1110.0&gt;-&lt;-1746.0,1102.0&gt;&gt; = 7.495857639729836

* u18CB3.008: B&lt;&lt;877.0,1117.0&gt;-&lt;828.0,1111.0&gt;-&lt;833.0,1112.0&gt;&gt;/B&lt;&lt;833.0,1112.0&gt;-&lt;803.0,1110.0&gt;-&lt;754.0,1102.0&gt;&gt; = 7.495857639729836

* u18CB3.009: B&lt;&lt;-623.0,1117.0&gt;-&lt;-672.0,1111.0&gt;-&lt;-667.0,1112.0&gt;&gt;/B&lt;&lt;-667.0,1112.0&gt;-&lt;-697.0,1110.0&gt;-&lt;-746.0,1102.0&gt;&gt; = 7.495857639729836

* u18CB3.010: B&lt;&lt;-1623.0,617.0&gt;-&lt;-1672.0,611.0&gt;-&lt;-1667.0,612.0&gt;&gt;/B&lt;&lt;-1667.0,612.0&gt;-&lt;-1697.0,610.0&gt;-&lt;-1746.0,602.0&gt;&gt; = 7.495857639729836

* u18CB3.011: B&lt;&lt;877.0,617.0&gt;-&lt;828.0,611.0&gt;-&lt;833.0,612.0&gt;&gt;/B&lt;&lt;833.0,612.0&gt;-&lt;803.0,610.0&gt;-&lt;754.0,602.0&gt;&gt; = 7.495857639729836

* u18CB3.012: B&lt;&lt;-623.0,617.0&gt;-&lt;-672.0,611.0&gt;-&lt;-667.0,612.0&gt;&gt;/B&lt;&lt;-667.0,612.0&gt;-&lt;-697.0,610.0&gt;-&lt;-746.0,602.0&gt;&gt; = 7.495857639729836

* u18CB3.013: B&lt;&lt;-1623.0,117.0&gt;-&lt;-1672.0,111.0&gt;-&lt;-1667.0,112.0&gt;&gt;/B&lt;&lt;-1667.0,112.0&gt;-&lt;-1697.0,110.0&gt;-&lt;-1746.0,102.0&gt;&gt; = 7.495857639729836

* u18CB3.014: B&lt;&lt;-1123.0,117.0&gt;-&lt;-1172.0,111.0&gt;-&lt;-1167.0,112.0&gt;&gt;/B&lt;&lt;-1167.0,112.0&gt;-&lt;-1197.0,110.0&gt;-&lt;-1246.0,102.0&gt;&gt; = 7.495857639729836

* u18CB3.015: B&lt;&lt;-623.0,117.0&gt;-&lt;-672.0,111.0&gt;-&lt;-667.0,112.0&gt;&gt;/B&lt;&lt;-667.0,112.0&gt;-&lt;-697.0,110.0&gt;-&lt;-746.0,102.0&gt;&gt; = 7.495857639729836

* u18CB3.016: B&lt;&lt;-1623.0,-383.0&gt;-&lt;-1672.0,-389.0&gt;-&lt;-1667.0,-388.0&gt;&gt;/B&lt;&lt;-1667.0,-388.0&gt;-&lt;-1697.0,-390.0&gt;-&lt;-1746.0,-398.0&gt;&gt; = 7.495857639729836

* u18CB3.017: B&lt;&lt;-1123.0,-383.0&gt;-&lt;-1172.0,-389.0&gt;-&lt;-1167.0,-388.0&gt;&gt;/B&lt;&lt;-1167.0,-388.0&gt;-&lt;-1197.0,-390.0&gt;-&lt;-1246.0,-398.0&gt;&gt; = 7.495857639729836

* u18CB3.018: B&lt;&lt;-623.0,-383.0&gt;-&lt;-672.0,-389.0&gt;-&lt;-667.0,-388.0&gt;&gt;/B&lt;&lt;-667.0,-388.0&gt;-&lt;-697.0,-390.0&gt;-&lt;-746.0,-398.0&gt;&gt; = 7.495857639729836

* u18CB3.019: B&lt;&lt;-1623.0,-883.0&gt;-&lt;-1672.0,-889.0&gt;-&lt;-1667.0,-888.0&gt;&gt;/B&lt;&lt;-1667.0,-888.0&gt;-&lt;-1697.0,-890.0&gt;-&lt;-1746.0,-898.0&gt;&gt; = 7.495857639729836

* u18CB3.020: B&lt;&lt;-1123.0,-883.0&gt;-&lt;-1172.0,-889.0&gt;-&lt;-1167.0,-888.0&gt;&gt;/B&lt;&lt;-1167.0,-888.0&gt;-&lt;-1197.0,-890.0&gt;-&lt;-1246.0,-898.0&gt;&gt; = 7.495857639729836

* u18CB3.021: B&lt;&lt;-623.0,-883.0&gt;-&lt;-672.0,-889.0&gt;-&lt;-667.0,-888.0&gt;&gt;/B&lt;&lt;-667.0,-888.0&gt;-&lt;-697.0,-890.0&gt;-&lt;-746.0,-898.0&gt;&gt; = 7.495857639729836

* u18CB3.022: B&lt;&lt;377.0,1117.0&gt;-&lt;328.0,1111.0&gt;-&lt;333.0,1112.0&gt;&gt;/B&lt;&lt;333.0,1112.0&gt;-&lt;303.0,1110.0&gt;-&lt;254.0,1102.0&gt;&gt; = 7.495857639729836

* u18CB3.023: B&lt;&lt;377.0,617.0&gt;-&lt;328.0,611.0&gt;-&lt;333.0,612.0&gt;&gt;/B&lt;&lt;333.0,612.0&gt;-&lt;303.0,610.0&gt;-&lt;254.0,602.0&gt;&gt; = 7.495857639729836
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* u18B03 (U+18B03): L&lt;&lt;531.0,182.0&gt;--&lt;530.0,-136.0&gt;&gt;

* u18B03.001: L&lt;&lt;531.0,1682.0&gt;--&lt;530.0,1364.0&gt;&gt;

* u18B03.002: L&lt;&lt;1031.0,1682.0&gt;--&lt;1030.0,1364.0&gt;&gt;

* u18B03.003: L&lt;&lt;-469.0,1682.0&gt;--&lt;-470.0,1364.0&gt;&gt;

* u18B03.004: L&lt;&lt;531.0,1182.0&gt;--&lt;530.0,864.0&gt;&gt;

* u18B03.005: L&lt;&lt;1031.0,1182.0&gt;--&lt;1030.0,864.0&gt;&gt;

* u18B03.006: L&lt;&lt;-469.0,1182.0&gt;--&lt;-470.0,864.0&gt;&gt;

* u18B03.007: L&lt;&lt;-1469.0,682.0&gt;--&lt;-1470.0,364.0&gt;&gt;

* u18B03.008: L&lt;&lt;1031.0,682.0&gt;--&lt;1030.0,364.0&gt;&gt;

* u18B03.009: L&lt;&lt;-469.0,682.0&gt;--&lt;-470.0,364.0&gt;&gt;

* u18B03.010: L&lt;&lt;-1469.0,182.0&gt;--&lt;-1470.0,-136.0&gt;&gt;

* u18B03.011: L&lt;&lt;1031.0,182.0&gt;--&lt;1030.0,-136.0&gt;&gt;

* u18B03.012: L&lt;&lt;-469.0,182.0&gt;--&lt;-470.0,-136.0&gt;&gt;

* u18B03.013: L&lt;&lt;-1469.0,-318.0&gt;--&lt;-1470.0,-636.0&gt;&gt;

* u18B03.014: L&lt;&lt;-969.0,-318.0&gt;--&lt;-970.0,-636.0&gt;&gt;

* u18B03.015: L&lt;&lt;-469.0,-318.0&gt;--&lt;-470.0,-636.0&gt;&gt;

* u18B03.016: L&lt;&lt;-1469.0,-818.0&gt;--&lt;-1470.0,-1136.0&gt;&gt;

* u18B03.017: L&lt;&lt;-969.0,-818.0&gt;--&lt;-970.0,-1136.0&gt;&gt;

* u18B03.018: L&lt;&lt;-469.0,-818.0&gt;--&lt;-470.0,-1136.0&gt;&gt;

* u18B03.019: L&lt;&lt;-1469.0,-1318.0&gt;--&lt;-1470.0,-1636.0&gt;&gt;

* u18B03.020: L&lt;&lt;-969.0,-1318.0&gt;--&lt;-970.0,-1636.0&gt;&gt;

* u18B03.021: L&lt;&lt;-469.0,-1318.0&gt;--&lt;-470.0,-1636.0&gt;&gt;

* u18B03.022: L&lt;&lt;531.0,682.0&gt;--&lt;530.0,364.0&gt;&gt;

* u18B03.023: L&lt;&lt;531.0,182.0&gt;--&lt;530.0,-136.0&gt;&gt;

* u18B07 (U+18B07): L&lt;&lt;497.0,338.0&gt;--&lt;496.0,597.0&gt;&gt;

* u18B07.001: L&lt;&lt;497.0,1838.0&gt;--&lt;496.0,2097.0&gt;&gt;

* u18B07.002: L&lt;&lt;997.0,1838.0&gt;--&lt;996.0,2097.0&gt;&gt;

* u18B07.003: L&lt;&lt;-503.0,1838.0&gt;--&lt;-504.0,2097.0&gt;&gt;

* u18B07.004: L&lt;&lt;497.0,1338.0&gt;--&lt;496.0,1597.0&gt;&gt;

* u18B07.005: L&lt;&lt;997.0,1338.0&gt;--&lt;996.0,1597.0&gt;&gt;

* u18B07.006: L&lt;&lt;-503.0,1338.0&gt;--&lt;-504.0,1597.0&gt;&gt;

* u18B07.007: L&lt;&lt;-1503.0,838.0&gt;--&lt;-1504.0,1097.0&gt;&gt;

* u18B07.008: L&lt;&lt;997.0,838.0&gt;--&lt;996.0,1097.0&gt;&gt;

* u18B07.009: L&lt;&lt;-503.0,838.0&gt;--&lt;-504.0,1097.0&gt;&gt;

* u18B07.010: L&lt;&lt;-1503.0,338.0&gt;--&lt;-1504.0,597.0&gt;&gt;

* u18B07.011: L&lt;&lt;997.0,338.0&gt;--&lt;996.0,597.0&gt;&gt;

* u18B07.012: L&lt;&lt;-503.0,338.0&gt;--&lt;-504.0,597.0&gt;&gt;

* u18B07.013: L&lt;&lt;-1503.0,-162.0&gt;--&lt;-1504.0,97.0&gt;&gt;

* u18B07.014: L&lt;&lt;-1003.0,-162.0&gt;--&lt;-1004.0,97.0&gt;&gt;

* u18B07.015: L&lt;&lt;-503.0,-162.0&gt;--&lt;-504.0,97.0&gt;&gt;

* u18B07.016: L&lt;&lt;-1503.0,-662.0&gt;--&lt;-1504.0,-403.0&gt;&gt;

* u18B07.017: L&lt;&lt;-1003.0,-662.0&gt;--&lt;-1004.0,-403.0&gt;&gt;

* u18B07.018: L&lt;&lt;-503.0,-662.0&gt;--&lt;-504.0,-403.0&gt;&gt;

* u18B07.019: L&lt;&lt;-1503.0,-1162.0&gt;--&lt;-1504.0,-903.0&gt;&gt;

* u18B07.020: L&lt;&lt;-1003.0,-1162.0&gt;--&lt;-1004.0,-903.0&gt;&gt;

* u18B07.021: L&lt;&lt;-503.0,-1162.0&gt;--&lt;-504.0,-903.0&gt;&gt;

* u18B07.022: L&lt;&lt;497.0,838.0&gt;--&lt;496.0,1097.0&gt;&gt;

* u18B07.023: L&lt;&lt;497.0,338.0&gt;--&lt;496.0,597.0&gt;&gt;

* u18B0B (U+18B0B): L&lt;&lt;527.0,175.0&gt;--&lt;526.0,-149.0&gt;&gt;

* u18B0B.001: L&lt;&lt;527.0,1675.0&gt;--&lt;526.0,1351.0&gt;&gt;

* u18B0B.002: L&lt;&lt;1027.0,1675.0&gt;--&lt;1026.0,1351.0&gt;&gt;

* u18B0B.003: L&lt;&lt;-473.0,1675.0&gt;--&lt;-474.0,1351.0&gt;&gt;

* u18B0B.004: L&lt;&lt;527.0,1175.0&gt;--&lt;526.0,851.0&gt;&gt;

* u18B0B.005: L&lt;&lt;1027.0,1175.0&gt;--&lt;1026.0,851.0&gt;&gt;

* u18B0B.006: L&lt;&lt;-473.0,1175.0&gt;--&lt;-474.0,851.0&gt;&gt;

* u18B0B.007: L&lt;&lt;-1473.0,675.0&gt;--&lt;-1474.0,351.0&gt;&gt;

* u18B0B.008: L&lt;&lt;1027.0,675.0&gt;--&lt;1026.0,351.0&gt;&gt;

* u18B0B.009: L&lt;&lt;-473.0,675.0&gt;--&lt;-474.0,351.0&gt;&gt;

* u18B0B.010: L&lt;&lt;-1473.0,175.0&gt;--&lt;-1474.0,-149.0&gt;&gt;

* u18B0B.011: L&lt;&lt;1027.0,175.0&gt;--&lt;1026.0,-149.0&gt;&gt;

* u18B0B.012: L&lt;&lt;-473.0,175.0&gt;--&lt;-474.0,-149.0&gt;&gt;

* u18B0B.013: L&lt;&lt;-1473.0,-325.0&gt;--&lt;-1474.0,-649.0&gt;&gt;

* u18B0B.014: L&lt;&lt;-973.0,-325.0&gt;--&lt;-974.0,-649.0&gt;&gt;

* u18B0B.015: L&lt;&lt;-473.0,-325.0&gt;--&lt;-474.0,-649.0&gt;&gt;

* u18B0B.016: L&lt;&lt;-1473.0,-825.0&gt;--&lt;-1474.0,-1149.0&gt;&gt;

* u18B0B.017: L&lt;&lt;-973.0,-825.0&gt;--&lt;-974.0,-1149.0&gt;&gt;

* u18B0B.018: L&lt;&lt;-473.0,-825.0&gt;--&lt;-474.0,-1149.0&gt;&gt;

* u18B0B.019: L&lt;&lt;-1473.0,-1325.0&gt;--&lt;-1474.0,-1649.0&gt;&gt;

* u18B0B.020: L&lt;&lt;-973.0,-1325.0&gt;--&lt;-974.0,-1649.0&gt;&gt;

* u18B0B.021: L&lt;&lt;-473.0,-1325.0&gt;--&lt;-474.0,-1649.0&gt;&gt;

* u18B0B.022: L&lt;&lt;527.0,675.0&gt;--&lt;526.0,351.0&gt;&gt;

* u18B0B.023: L&lt;&lt;527.0,175.0&gt;--&lt;526.0,-149.0&gt;&gt;

* u18B14 (U+18B14): L&lt;&lt;551.0,485.0&gt;--&lt;550.0,168.0&gt;&gt;

* u18B14.001: L&lt;&lt;551.0,1985.0&gt;--&lt;550.0,1668.0&gt;&gt;

* u18B14.002: L&lt;&lt;1051.0,1985.0&gt;--&lt;1050.0,1668.0&gt;&gt;

* u18B14.003: L&lt;&lt;-449.0,1985.0&gt;--&lt;-450.0,1668.0&gt;&gt;

* u18B14.004: L&lt;&lt;551.0,1485.0&gt;--&lt;550.0,1168.0&gt;&gt;

* u18B14.005: L&lt;&lt;1051.0,1485.0&gt;--&lt;1050.0,1168.0&gt;&gt;

* u18B14.006: L&lt;&lt;-449.0,1485.0&gt;--&lt;-450.0,1168.0&gt;&gt;

* u18B14.007: L&lt;&lt;-1449.0,985.0&gt;--&lt;-1450.0,668.0&gt;&gt;

* u18B14.008: L&lt;&lt;1051.0,985.0&gt;--&lt;1050.0,668.0&gt;&gt;

* u18B14.009: L&lt;&lt;-449.0,985.0&gt;--&lt;-450.0,668.0&gt;&gt;

* u18B14.010: L&lt;&lt;-1449.0,485.0&gt;--&lt;-1450.0,168.0&gt;&gt;

* u18B14.011: L&lt;&lt;1051.0,485.0&gt;--&lt;1050.0,168.0&gt;&gt;

* u18B14.012: L&lt;&lt;-449.0,485.0&gt;--&lt;-450.0,168.0&gt;&gt;

* u18B14.013: L&lt;&lt;-1449.0,-15.0&gt;--&lt;-1450.0,-332.0&gt;&gt;

* u18B14.014: L&lt;&lt;-949.0,-15.0&gt;--&lt;-950.0,-332.0&gt;&gt;

* u18B14.015: L&lt;&lt;-449.0,-15.0&gt;--&lt;-450.0,-332.0&gt;&gt;

* u18B14.016: L&lt;&lt;-1449.0,-515.0&gt;--&lt;-1450.0,-832.0&gt;&gt;

* u18B14.017: L&lt;&lt;-949.0,-515.0&gt;--&lt;-950.0,-832.0&gt;&gt;

* u18B14.018: L&lt;&lt;-449.0,-515.0&gt;--&lt;-450.0,-832.0&gt;&gt;

* u18B14.019: L&lt;&lt;-1449.0,-1015.0&gt;--&lt;-1450.0,-1332.0&gt;&gt;

* u18B14.020: L&lt;&lt;-949.0,-1015.0&gt;--&lt;-950.0,-1332.0&gt;&gt;

* u18B14.021: L&lt;&lt;-449.0,-1015.0&gt;--&lt;-450.0,-1332.0&gt;&gt;

* u18B14.022: L&lt;&lt;551.0,985.0&gt;--&lt;550.0,668.0&gt;&gt;

* u18B14.023: L&lt;&lt;551.0,485.0&gt;--&lt;550.0,168.0&gt;&gt;

* u18B15 (U+18B15): L&lt;&lt;531.0,485.0&gt;--&lt;530.0,168.0&gt;&gt;

* u18B15.001: L&lt;&lt;531.0,1985.0&gt;--&lt;530.0,1668.0&gt;&gt;

* u18B15.002: L&lt;&lt;1031.0,1985.0&gt;--&lt;1030.0,1668.0&gt;&gt;

* u18B15.003: L&lt;&lt;-469.0,1985.0&gt;--&lt;-470.0,1668.0&gt;&gt;

* u18B15.004: L&lt;&lt;531.0,1485.0&gt;--&lt;530.0,1168.0&gt;&gt;

* u18B15.005: L&lt;&lt;1031.0,1485.0&gt;--&lt;1030.0,1168.0&gt;&gt;

* u18B15.006: L&lt;&lt;-469.0,1485.0&gt;--&lt;-470.0,1168.0&gt;&gt;

* u18B15.007: L&lt;&lt;-1469.0,985.0&gt;--&lt;-1470.0,668.0&gt;&gt;

* u18B15.008: L&lt;&lt;1031.0,985.0&gt;--&lt;1030.0,668.0&gt;&gt;

* u18B15.009: L&lt;&lt;-469.0,985.0&gt;--&lt;-470.0,668.0&gt;&gt;

* u18B15.010: L&lt;&lt;-1469.0,485.0&gt;--&lt;-1470.0,168.0&gt;&gt;

* u18B15.011: L&lt;&lt;1031.0,485.0&gt;--&lt;1030.0,168.0&gt;&gt;

* u18B15.012: L&lt;&lt;-469.0,485.0&gt;--&lt;-470.0,168.0&gt;&gt;

* u18B15.013: L&lt;&lt;-1469.0,-15.0&gt;--&lt;-1470.0,-332.0&gt;&gt;

* u18B15.014: L&lt;&lt;-969.0,-15.0&gt;--&lt;-970.0,-332.0&gt;&gt;

* u18B15.015: L&lt;&lt;-469.0,-15.0&gt;--&lt;-470.0,-332.0&gt;&gt;

* u18B15.016: L&lt;&lt;-1469.0,-515.0&gt;--&lt;-1470.0,-832.0&gt;&gt;

* u18B15.017: L&lt;&lt;-969.0,-515.0&gt;--&lt;-970.0,-832.0&gt;&gt;

* u18B15.018: L&lt;&lt;-469.0,-515.0&gt;--&lt;-470.0,-832.0&gt;&gt;

* u18B15.019: L&lt;&lt;-1469.0,-1015.0&gt;--&lt;-1470.0,-1332.0&gt;&gt;

* u18B15.020: L&lt;&lt;-969.0,-1015.0&gt;--&lt;-970.0,-1332.0&gt;&gt;

* u18B15.021: L&lt;&lt;-469.0,-1015.0&gt;--&lt;-470.0,-1332.0&gt;&gt;

* u18B15.022: L&lt;&lt;531.0,985.0&gt;--&lt;530.0,668.0&gt;&gt;

* u18B15.023: L&lt;&lt;531.0,485.0&gt;--&lt;530.0,168.0&gt;&gt;

* u18B17 (U+18B17): L&lt;&lt;545.0,378.0&gt;--&lt;544.0,175.0&gt;&gt;

* u18B17.001: L&lt;&lt;545.0,1878.0&gt;--&lt;544.0,1675.0&gt;&gt;

* u18B17.002: L&lt;&lt;1045.0,1878.0&gt;--&lt;1044.0,1675.0&gt;&gt;

* u18B17.003: L&lt;&lt;-455.0,1878.0&gt;--&lt;-456.0,1675.0&gt;&gt;

* u18B17.004: L&lt;&lt;545.0,1378.0&gt;--&lt;544.0,1175.0&gt;&gt;

* u18B17.005: L&lt;&lt;1045.0,1378.0&gt;--&lt;1044.0,1175.0&gt;&gt;

* u18B17.006: L&lt;&lt;-455.0,1378.0&gt;--&lt;-456.0,1175.0&gt;&gt;

* u18B17.007: L&lt;&lt;-1455.0,878.0&gt;--&lt;-1456.0,675.0&gt;&gt;

* u18B17.008: L&lt;&lt;1045.0,878.0&gt;--&lt;1044.0,675.0&gt;&gt;

* u18B17.009: L&lt;&lt;-455.0,878.0&gt;--&lt;-456.0,675.0&gt;&gt;

* u18B17.010: L&lt;&lt;-1455.0,378.0&gt;--&lt;-1456.0,175.0&gt;&gt;

* u18B17.011: L&lt;&lt;1045.0,378.0&gt;--&lt;1044.0,175.0&gt;&gt;

* u18B17.012: L&lt;&lt;-455.0,378.0&gt;--&lt;-456.0,175.0&gt;&gt;

* u18B17.013: L&lt;&lt;-1455.0,-122.0&gt;--&lt;-1456.0,-325.0&gt;&gt;

* u18B17.014: L&lt;&lt;-955.0,-122.0&gt;--&lt;-956.0,-325.0&gt;&gt;

* u18B17.015: L&lt;&lt;-455.0,-122.0&gt;--&lt;-456.0,-325.0&gt;&gt;

* u18B17.016: L&lt;&lt;-1455.0,-622.0&gt;--&lt;-1456.0,-825.0&gt;&gt;

* u18B17.017: L&lt;&lt;-955.0,-622.0&gt;--&lt;-956.0,-825.0&gt;&gt;

* u18B17.018: L&lt;&lt;-455.0,-622.0&gt;--&lt;-456.0,-825.0&gt;&gt;

* u18B17.019: L&lt;&lt;-1455.0,-1122.0&gt;--&lt;-1456.0,-1325.0&gt;&gt;

* u18B17.020: L&lt;&lt;-955.0,-1122.0&gt;--&lt;-956.0,-1325.0&gt;&gt;

* u18B17.021: L&lt;&lt;-455.0,-1122.0&gt;--&lt;-456.0,-1325.0&gt;&gt;

* u18B17.022: L&lt;&lt;545.0,878.0&gt;--&lt;544.0,675.0&gt;&gt;

* u18B17.023: L&lt;&lt;545.0,378.0&gt;--&lt;544.0,175.0&gt;&gt;

* u18B18 (U+18B18): L&lt;&lt;535.0,391.0&gt;--&lt;534.0,224.0&gt;&gt;

* u18B18.001: L&lt;&lt;535.0,1891.0&gt;--&lt;534.0,1724.0&gt;&gt;

* u18B18.002: L&lt;&lt;1035.0,1891.0&gt;--&lt;1034.0,1724.0&gt;&gt;

* u18B18.003: L&lt;&lt;-465.0,1891.0&gt;--&lt;-466.0,1724.0&gt;&gt;

* u18B18.004: L&lt;&lt;535.0,1391.0&gt;--&lt;534.0,1224.0&gt;&gt;

* u18B18.005: L&lt;&lt;1035.0,1391.0&gt;--&lt;1034.0,1224.0&gt;&gt;

* u18B18.006: L&lt;&lt;-465.0,1391.0&gt;--&lt;-466.0,1224.0&gt;&gt;

* u18B18.007: L&lt;&lt;-1465.0,891.0&gt;--&lt;-1466.0,724.0&gt;&gt;

* u18B18.008: L&lt;&lt;1035.0,891.0&gt;--&lt;1034.0,724.0&gt;&gt;

* u18B18.009: L&lt;&lt;-465.0,891.0&gt;--&lt;-466.0,724.0&gt;&gt;

* u18B18.010: L&lt;&lt;-1465.0,391.0&gt;--&lt;-1466.0,224.0&gt;&gt;

* u18B18.011: L&lt;&lt;1035.0,391.0&gt;--&lt;1034.0,224.0&gt;&gt;

* u18B18.012: L&lt;&lt;-465.0,391.0&gt;--&lt;-466.0,224.0&gt;&gt;

* u18B18.013: L&lt;&lt;-1465.0,-109.0&gt;--&lt;-1466.0,-276.0&gt;&gt;

* u18B18.014: L&lt;&lt;-965.0,-109.0&gt;--&lt;-966.0,-276.0&gt;&gt;

* u18B18.015: L&lt;&lt;-465.0,-109.0&gt;--&lt;-466.0,-276.0&gt;&gt;

* u18B18.016: L&lt;&lt;-1465.0,-609.0&gt;--&lt;-1466.0,-776.0&gt;&gt;

* u18B18.017: L&lt;&lt;-965.0,-609.0&gt;--&lt;-966.0,-776.0&gt;&gt;

* u18B18.018: L&lt;&lt;-465.0,-609.0&gt;--&lt;-466.0,-776.0&gt;&gt;

* u18B18.019: L&lt;&lt;-1465.0,-1109.0&gt;--&lt;-1466.0,-1276.0&gt;&gt;

* u18B18.020: L&lt;&lt;-965.0,-1109.0&gt;--&lt;-966.0,-1276.0&gt;&gt;

* u18B18.021: L&lt;&lt;-465.0,-1109.0&gt;--&lt;-466.0,-1276.0&gt;&gt;

* u18B18.022: L&lt;&lt;535.0,891.0&gt;--&lt;534.0,724.0&gt;&gt;

* u18B18.023: L&lt;&lt;535.0,391.0&gt;--&lt;534.0,224.0&gt;&gt;

* u18B19 (U+18B19): L&lt;&lt;534.0,426.0&gt;--&lt;533.0,303.0&gt;&gt;

* u18B19.001: L&lt;&lt;534.0,1926.0&gt;--&lt;533.0,1803.0&gt;&gt;

* u18B19.002: L&lt;&lt;1034.0,1926.0&gt;--&lt;1033.0,1803.0&gt;&gt;

* u18B19.003: L&lt;&lt;-466.0,1926.0&gt;--&lt;-467.0,1803.0&gt;&gt;

* u18B19.004: L&lt;&lt;534.0,1426.0&gt;--&lt;533.0,1303.0&gt;&gt;

* u18B19.005: L&lt;&lt;1034.0,1426.0&gt;--&lt;1033.0,1303.0&gt;&gt;

* u18B19.006: L&lt;&lt;-466.0,1426.0&gt;--&lt;-467.0,1303.0&gt;&gt;

* u18B19.007: L&lt;&lt;-1466.0,926.0&gt;--&lt;-1467.0,803.0&gt;&gt;

* u18B19.008: L&lt;&lt;1034.0,926.0&gt;--&lt;1033.0,803.0&gt;&gt;

* u18B19.009: L&lt;&lt;-466.0,926.0&gt;--&lt;-467.0,803.0&gt;&gt;

* u18B19.010: L&lt;&lt;-1466.0,426.0&gt;--&lt;-1467.0,303.0&gt;&gt;

* u18B19.011: L&lt;&lt;1034.0,426.0&gt;--&lt;1033.0,303.0&gt;&gt;

* u18B19.012: L&lt;&lt;-466.0,426.0&gt;--&lt;-467.0,303.0&gt;&gt;

* u18B19.013: L&lt;&lt;-1466.0,-74.0&gt;--&lt;-1467.0,-197.0&gt;&gt;

* u18B19.014: L&lt;&lt;-966.0,-74.0&gt;--&lt;-967.0,-197.0&gt;&gt;

* u18B19.015: L&lt;&lt;-466.0,-74.0&gt;--&lt;-467.0,-197.0&gt;&gt;

* u18B19.016: L&lt;&lt;-1466.0,-574.0&gt;--&lt;-1467.0,-697.0&gt;&gt;

* u18B19.017: L&lt;&lt;-966.0,-574.0&gt;--&lt;-967.0,-697.0&gt;&gt;

* u18B19.018: L&lt;&lt;-466.0,-574.0&gt;--&lt;-467.0,-697.0&gt;&gt;

* u18B19.019: L&lt;&lt;-1466.0,-1074.0&gt;--&lt;-1467.0,-1197.0&gt;&gt;

* u18B19.020: L&lt;&lt;-966.0,-1074.0&gt;--&lt;-967.0,-1197.0&gt;&gt;

* u18B19.021: L&lt;&lt;-466.0,-1074.0&gt;--&lt;-467.0,-1197.0&gt;&gt;

* u18B19.022: L&lt;&lt;534.0,926.0&gt;--&lt;533.0,803.0&gt;&gt;

* u18B19.023: L&lt;&lt;534.0,426.0&gt;--&lt;533.0,303.0&gt;&gt;

* u18B1E (U+18B1E): L&lt;&lt;529.0,154.0&gt;--&lt;528.0,-113.0&gt;&gt;

* u18B1E.001: L&lt;&lt;529.0,1654.0&gt;--&lt;528.0,1387.0&gt;&gt;

* u18B1E.002: L&lt;&lt;1029.0,1654.0&gt;--&lt;1028.0,1387.0&gt;&gt;

* u18B1E.003: L&lt;&lt;-471.0,1654.0&gt;--&lt;-472.0,1387.0&gt;&gt;

* u18B1E.004: L&lt;&lt;529.0,1154.0&gt;--&lt;528.0,887.0&gt;&gt;

* u18B1E.005: L&lt;&lt;1029.0,1154.0&gt;--&lt;1028.0,887.0&gt;&gt;

* u18B1E.006: L&lt;&lt;-471.0,1154.0&gt;--&lt;-472.0,887.0&gt;&gt;

* u18B1E.007: L&lt;&lt;-1471.0,654.0&gt;--&lt;-1472.0,387.0&gt;&gt;

* u18B1E.008: L&lt;&lt;1029.0,654.0&gt;--&lt;1028.0,387.0&gt;&gt;

* u18B1E.009: L&lt;&lt;-471.0,654.0&gt;--&lt;-472.0,387.0&gt;&gt;

* u18B1E.010: L&lt;&lt;-1471.0,154.0&gt;--&lt;-1472.0,-113.0&gt;&gt;

* u18B1E.011: L&lt;&lt;1029.0,154.0&gt;--&lt;1028.0,-113.0&gt;&gt;

* u18B1E.012: L&lt;&lt;-471.0,154.0&gt;--&lt;-472.0,-113.0&gt;&gt;

* u18B1E.013: L&lt;&lt;-1471.0,-346.0&gt;--&lt;-1472.0,-613.0&gt;&gt;

* u18B1E.014: L&lt;&lt;-971.0,-346.0&gt;--&lt;-972.0,-613.0&gt;&gt;

* u18B1E.015: L&lt;&lt;-471.0,-346.0&gt;--&lt;-472.0,-613.0&gt;&gt;

* u18B1E.016: L&lt;&lt;-1471.0,-846.0&gt;--&lt;-1472.0,-1113.0&gt;&gt;

* u18B1E.017: L&lt;&lt;-971.0,-846.0&gt;--&lt;-972.0,-1113.0&gt;&gt;

* u18B1E.018: L&lt;&lt;-471.0,-846.0&gt;--&lt;-472.0,-1113.0&gt;&gt;

* u18B1E.019: L&lt;&lt;-1471.0,-1346.0&gt;--&lt;-1472.0,-1613.0&gt;&gt;

* u18B1E.020: L&lt;&lt;-971.0,-1346.0&gt;--&lt;-972.0,-1613.0&gt;&gt;

* u18B1E.021: L&lt;&lt;-471.0,-1346.0&gt;--&lt;-472.0,-1613.0&gt;&gt;

* u18B1E.022: L&lt;&lt;529.0,654.0&gt;--&lt;528.0,387.0&gt;&gt;

* u18B1E.023: L&lt;&lt;529.0,154.0&gt;--&lt;528.0,-113.0&gt;&gt;

* u18B1F (U+18B1F): L&lt;&lt;827.0,128.0&gt;--&lt;826.0,-148.0&gt;&gt;

* u18B1F.001: L&lt;&lt;827.0,1628.0&gt;--&lt;826.0,1352.0&gt;&gt;

* u18B1F.002: L&lt;&lt;1327.0,1628.0&gt;--&lt;1326.0,1352.0&gt;&gt;

* u18B1F.003: L&lt;&lt;-173.0,1628.0&gt;--&lt;-174.0,1352.0&gt;&gt;

* u18B1F.004: L&lt;&lt;827.0,1128.0&gt;--&lt;826.0,852.0&gt;&gt;

* u18B1F.005: L&lt;&lt;1327.0,1128.0&gt;--&lt;1326.0,852.0&gt;&gt;

* u18B1F.006: L&lt;&lt;-173.0,1128.0&gt;--&lt;-174.0,852.0&gt;&gt;

* u18B1F.007: L&lt;&lt;-1173.0,628.0&gt;--&lt;-1174.0,352.0&gt;&gt;

* u18B1F.008: L&lt;&lt;1327.0,628.0&gt;--&lt;1326.0,352.0&gt;&gt;

* u18B1F.009: L&lt;&lt;-173.0,628.0&gt;--&lt;-174.0,352.0&gt;&gt;

* u18B1F.010: L&lt;&lt;-1173.0,128.0&gt;--&lt;-1174.0,-148.0&gt;&gt;

* u18B1F.011: L&lt;&lt;1327.0,128.0&gt;--&lt;1326.0,-148.0&gt;&gt;

* u18B1F.012: L&lt;&lt;-173.0,128.0&gt;--&lt;-174.0,-148.0&gt;&gt;

* u18B1F.013: L&lt;&lt;-1173.0,-372.0&gt;--&lt;-1174.0,-648.0&gt;&gt;

* u18B1F.014: L&lt;&lt;-673.0,-372.0&gt;--&lt;-674.0,-648.0&gt;&gt;

* u18B1F.015: L&lt;&lt;-173.0,-372.0&gt;--&lt;-174.0,-648.0&gt;&gt;

* u18B1F.016: L&lt;&lt;-1173.0,-872.0&gt;--&lt;-1174.0,-1148.0&gt;&gt;

* u18B1F.017: L&lt;&lt;-673.0,-872.0&gt;--&lt;-674.0,-1148.0&gt;&gt;

* u18B1F.018: L&lt;&lt;-173.0,-872.0&gt;--&lt;-174.0,-1148.0&gt;&gt;

* u18B1F.019: L&lt;&lt;-1173.0,-1372.0&gt;--&lt;-1174.0,-1648.0&gt;&gt;

* u18B1F.020: L&lt;&lt;-673.0,-1372.0&gt;--&lt;-674.0,-1648.0&gt;&gt;

* u18B1F.021: L&lt;&lt;-173.0,-1372.0&gt;--&lt;-174.0,-1648.0&gt;&gt;

* u18B1F.022: L&lt;&lt;827.0,628.0&gt;--&lt;826.0,352.0&gt;&gt;

* u18B1F.023: L&lt;&lt;827.0,128.0&gt;--&lt;826.0,-148.0&gt;&gt;

* u18B22 (U+18B22): L&lt;&lt;367.0,-25.0&gt;--&lt;365.0,341.0&gt;&gt;

* u18B22.001: L&lt;&lt;367.0,1475.0&gt;--&lt;365.0,1841.0&gt;&gt;

* u18B22.002: L&lt;&lt;867.0,1475.0&gt;--&lt;865.0,1841.0&gt;&gt;

* u18B22.003: L&lt;&lt;-633.0,1475.0&gt;--&lt;-635.0,1841.0&gt;&gt;

* u18B22.004: L&lt;&lt;367.0,975.0&gt;--&lt;365.0,1341.0&gt;&gt;

* u18B22.005: L&lt;&lt;867.0,975.0&gt;--&lt;865.0,1341.0&gt;&gt;

* u18B22.006: L&lt;&lt;-633.0,975.0&gt;--&lt;-635.0,1341.0&gt;&gt;

* u18B22.007: L&lt;&lt;-1633.0,475.0&gt;--&lt;-1635.0,841.0&gt;&gt;

* u18B22.008: L&lt;&lt;867.0,475.0&gt;--&lt;865.0,841.0&gt;&gt;

* u18B22.009: L&lt;&lt;-633.0,475.0&gt;--&lt;-635.0,841.0&gt;&gt;

* u18B22.010: L&lt;&lt;-1633.0,-25.0&gt;--&lt;-1635.0,341.0&gt;&gt;

* u18B22.011: L&lt;&lt;867.0,-25.0&gt;--&lt;865.0,341.0&gt;&gt;

* u18B22.012: L&lt;&lt;-633.0,-25.0&gt;--&lt;-635.0,341.0&gt;&gt;

* u18B22.013: L&lt;&lt;-1633.0,-525.0&gt;--&lt;-1635.0,-159.0&gt;&gt;

* u18B22.014: L&lt;&lt;-1133.0,-525.0&gt;--&lt;-1135.0,-159.0&gt;&gt;

* u18B22.015: L&lt;&lt;-633.0,-525.0&gt;--&lt;-635.0,-159.0&gt;&gt;

* u18B22.016: L&lt;&lt;-1633.0,-1025.0&gt;--&lt;-1635.0,-659.0&gt;&gt;

* u18B22.017: L&lt;&lt;-1133.0,-1025.0&gt;--&lt;-1135.0,-659.0&gt;&gt;

* u18B22.018: L&lt;&lt;-633.0,-1025.0&gt;--&lt;-635.0,-659.0&gt;&gt;

* u18B22.019: L&lt;&lt;-1633.0,-1525.0&gt;--&lt;-1635.0,-1159.0&gt;&gt;

* u18B22.020: L&lt;&lt;-1133.0,-1525.0&gt;--&lt;-1135.0,-1159.0&gt;&gt;

* u18B22.021: L&lt;&lt;-633.0,-1525.0&gt;--&lt;-635.0,-1159.0&gt;&gt;

* u18B22.022: L&lt;&lt;367.0,475.0&gt;--&lt;365.0,841.0&gt;&gt;

* u18B22.023: L&lt;&lt;367.0,-25.0&gt;--&lt;365.0,341.0&gt;&gt;

* u18B36 (U+18B36): L&lt;&lt;528.0,579.0&gt;--&lt;527.0,394.0&gt;&gt;

* u18B36.001: L&lt;&lt;528.0,2079.0&gt;--&lt;527.0,1894.0&gt;&gt;

* u18B36.002: L&lt;&lt;1028.0,2079.0&gt;--&lt;1027.0,1894.0&gt;&gt;

* u18B36.003: L&lt;&lt;-472.0,2079.0&gt;--&lt;-473.0,1894.0&gt;&gt;

* u18B36.004: L&lt;&lt;528.0,1579.0&gt;--&lt;527.0,1394.0&gt;&gt;

* u18B36.005: L&lt;&lt;1028.0,1579.0&gt;--&lt;1027.0,1394.0&gt;&gt;

* u18B36.006: L&lt;&lt;-472.0,1579.0&gt;--&lt;-473.0,1394.0&gt;&gt;

* u18B36.007: L&lt;&lt;-1472.0,1079.0&gt;--&lt;-1473.0,894.0&gt;&gt;

* u18B36.008: L&lt;&lt;1028.0,1079.0&gt;--&lt;1027.0,894.0&gt;&gt;

* u18B36.009: L&lt;&lt;-472.0,1079.0&gt;--&lt;-473.0,894.0&gt;&gt;

* u18B36.010: L&lt;&lt;-1472.0,579.0&gt;--&lt;-1473.0,394.0&gt;&gt;

* u18B36.011: L&lt;&lt;1028.0,579.0&gt;--&lt;1027.0,394.0&gt;&gt;

* u18B36.012: L&lt;&lt;-472.0,579.0&gt;--&lt;-473.0,394.0&gt;&gt;

* u18B36.013: L&lt;&lt;-1472.0,79.0&gt;--&lt;-1473.0,-106.0&gt;&gt;

* u18B36.014: L&lt;&lt;-972.0,79.0&gt;--&lt;-973.0,-106.0&gt;&gt;

* u18B36.015: L&lt;&lt;-472.0,79.0&gt;--&lt;-473.0,-106.0&gt;&gt;

* u18B36.016: L&lt;&lt;-1472.0,-421.0&gt;--&lt;-1473.0,-606.0&gt;&gt;

* u18B36.017: L&lt;&lt;-972.0,-421.0&gt;--&lt;-973.0,-606.0&gt;&gt;

* u18B36.018: L&lt;&lt;-472.0,-421.0&gt;--&lt;-473.0,-606.0&gt;&gt;

* u18B36.019: L&lt;&lt;-1472.0,-921.0&gt;--&lt;-1473.0,-1106.0&gt;&gt;

* u18B36.020: L&lt;&lt;-972.0,-921.0&gt;--&lt;-973.0,-1106.0&gt;&gt;

* u18B36.021: L&lt;&lt;-472.0,-921.0&gt;--&lt;-473.0,-1106.0&gt;&gt;

* u18B36.022: L&lt;&lt;528.0,1079.0&gt;--&lt;527.0,894.0&gt;&gt;

* u18B36.023: L&lt;&lt;528.0,579.0&gt;--&lt;527.0,394.0&gt;&gt;

* u18B38 (U+18B38): L&lt;&lt;490.0,28.0&gt;--&lt;491.0,344.0&gt;&gt;

* u18B38.001: L&lt;&lt;490.0,1528.0&gt;--&lt;491.0,1844.0&gt;&gt;

* u18B38.002: L&lt;&lt;990.0,1528.0&gt;--&lt;991.0,1844.0&gt;&gt;

* u18B38.003: L&lt;&lt;-510.0,1528.0&gt;--&lt;-509.0,1844.0&gt;&gt;

* u18B38.004: L&lt;&lt;490.0,1028.0&gt;--&lt;491.0,1344.0&gt;&gt;

* u18B38.005: L&lt;&lt;990.0,1028.0&gt;--&lt;991.0,1344.0&gt;&gt;

* u18B38.006: L&lt;&lt;-510.0,1028.0&gt;--&lt;-509.0,1344.0&gt;&gt;

* u18B38.007: L&lt;&lt;-1510.0,528.0&gt;--&lt;-1509.0,844.0&gt;&gt;

* u18B38.008: L&lt;&lt;990.0,528.0&gt;--&lt;991.0,844.0&gt;&gt;

* u18B38.009: L&lt;&lt;-510.0,528.0&gt;--&lt;-509.0,844.0&gt;&gt;

* u18B38.010: L&lt;&lt;-1510.0,28.0&gt;--&lt;-1509.0,344.0&gt;&gt;

* u18B38.011: L&lt;&lt;990.0,28.0&gt;--&lt;991.0,344.0&gt;&gt;

* u18B38.012: L&lt;&lt;-510.0,28.0&gt;--&lt;-509.0,344.0&gt;&gt;

* u18B38.013: L&lt;&lt;-1510.0,-472.0&gt;--&lt;-1509.0,-156.0&gt;&gt;

* u18B38.014: L&lt;&lt;-1010.0,-472.0&gt;--&lt;-1009.0,-156.0&gt;&gt;

* u18B38.015: L&lt;&lt;-510.0,-472.0&gt;--&lt;-509.0,-156.0&gt;&gt;

* u18B38.016: L&lt;&lt;-1510.0,-972.0&gt;--&lt;-1509.0,-656.0&gt;&gt;

* u18B38.017: L&lt;&lt;-1010.0,-972.0&gt;--&lt;-1009.0,-656.0&gt;&gt;

* u18B38.018: L&lt;&lt;-510.0,-972.0&gt;--&lt;-509.0,-656.0&gt;&gt;

* u18B38.019: L&lt;&lt;-1510.0,-1472.0&gt;--&lt;-1509.0,-1156.0&gt;&gt;

* u18B38.020: L&lt;&lt;-1010.0,-1472.0&gt;--&lt;-1009.0,-1156.0&gt;&gt;

* u18B38.021: L&lt;&lt;-510.0,-1472.0&gt;--&lt;-509.0,-1156.0&gt;&gt;

* u18B38.022: L&lt;&lt;490.0,528.0&gt;--&lt;491.0,844.0&gt;&gt;

* u18B38.023: L&lt;&lt;490.0,28.0&gt;--&lt;491.0,344.0&gt;&gt;

* u18B39 (U+18B39): L&lt;&lt;470.0,28.0&gt;--&lt;471.0,344.0&gt;&gt;

* u18B39.001: L&lt;&lt;470.0,1528.0&gt;--&lt;471.0,1844.0&gt;&gt;

* u18B39.002: L&lt;&lt;970.0,1528.0&gt;--&lt;971.0,1844.0&gt;&gt;

* u18B39.003: L&lt;&lt;-530.0,1528.0&gt;--&lt;-529.0,1844.0&gt;&gt;

* u18B39.004: L&lt;&lt;470.0,1028.0&gt;--&lt;471.0,1344.0&gt;&gt;

* u18B39.005: L&lt;&lt;970.0,1028.0&gt;--&lt;971.0,1344.0&gt;&gt;

* u18B39.006: L&lt;&lt;-530.0,1028.0&gt;--&lt;-529.0,1344.0&gt;&gt;

* u18B39.007: L&lt;&lt;-1530.0,528.0&gt;--&lt;-1529.0,844.0&gt;&gt;

* u18B39.008: L&lt;&lt;970.0,528.0&gt;--&lt;971.0,844.0&gt;&gt;

* u18B39.009: L&lt;&lt;-530.0,528.0&gt;--&lt;-529.0,844.0&gt;&gt;

* u18B39.010: L&lt;&lt;-1530.0,28.0&gt;--&lt;-1529.0,344.0&gt;&gt;

* u18B39.011: L&lt;&lt;970.0,28.0&gt;--&lt;971.0,344.0&gt;&gt;

* u18B39.012: L&lt;&lt;-530.0,28.0&gt;--&lt;-529.0,344.0&gt;&gt;

* u18B39.013: L&lt;&lt;-1530.0,-472.0&gt;--&lt;-1529.0,-156.0&gt;&gt;

* u18B39.014: L&lt;&lt;-1030.0,-472.0&gt;--&lt;-1029.0,-156.0&gt;&gt;

* u18B39.015: L&lt;&lt;-530.0,-472.0&gt;--&lt;-529.0,-156.0&gt;&gt;

* u18B39.016: L&lt;&lt;-1530.0,-972.0&gt;--&lt;-1529.0,-656.0&gt;&gt;

* u18B39.017: L&lt;&lt;-1030.0,-972.0&gt;--&lt;-1029.0,-656.0&gt;&gt;

* u18B39.018: L&lt;&lt;-530.0,-972.0&gt;--&lt;-529.0,-656.0&gt;&gt;

* u18B39.019: L&lt;&lt;-1530.0,-1472.0&gt;--&lt;-1529.0,-1156.0&gt;&gt;

* u18B39.020: L&lt;&lt;-1030.0,-1472.0&gt;--&lt;-1029.0,-1156.0&gt;&gt;

* u18B39.021: L&lt;&lt;-530.0,-1472.0&gt;--&lt;-529.0,-1156.0&gt;&gt;

* u18B39.022: L&lt;&lt;470.0,528.0&gt;--&lt;471.0,844.0&gt;&gt;

* u18B39.023: L&lt;&lt;470.0,28.0&gt;--&lt;471.0,344.0&gt;&gt;

* u18B3A (U+18B3A): L&lt;&lt;527.0,508.0&gt;--&lt;526.0,210.0&gt;&gt;

* u18B3A.001: L&lt;&lt;527.0,2008.0&gt;--&lt;526.0,1710.0&gt;&gt;

* u18B3A.002: L&lt;&lt;1027.0,2008.0&gt;--&lt;1026.0,1710.0&gt;&gt;

* u18B3A.003: L&lt;&lt;-473.0,2008.0&gt;--&lt;-474.0,1710.0&gt;&gt;

* u18B3A.004: L&lt;&lt;527.0,1508.0&gt;--&lt;526.0,1210.0&gt;&gt;

* u18B3A.005: L&lt;&lt;1027.0,1508.0&gt;--&lt;1026.0,1210.0&gt;&gt;

* u18B3A.006: L&lt;&lt;-473.0,1508.0&gt;--&lt;-474.0,1210.0&gt;&gt;

* u18B3A.007: L&lt;&lt;-1473.0,1008.0&gt;--&lt;-1474.0,710.0&gt;&gt;

* u18B3A.008: L&lt;&lt;1027.0,1008.0&gt;--&lt;1026.0,710.0&gt;&gt;

* u18B3A.009: L&lt;&lt;-473.0,1008.0&gt;--&lt;-474.0,710.0&gt;&gt;

* u18B3A.010: L&lt;&lt;-1473.0,508.0&gt;--&lt;-1474.0,210.0&gt;&gt;

* u18B3A.011: L&lt;&lt;1027.0,508.0&gt;--&lt;1026.0,210.0&gt;&gt;

* u18B3A.012: L&lt;&lt;-473.0,508.0&gt;--&lt;-474.0,210.0&gt;&gt;

* u18B3A.013: L&lt;&lt;-1473.0,8.0&gt;--&lt;-1474.0,-290.0&gt;&gt;

* u18B3A.014: L&lt;&lt;-973.0,8.0&gt;--&lt;-974.0,-290.0&gt;&gt;

* u18B3A.015: L&lt;&lt;-473.0,8.0&gt;--&lt;-474.0,-290.0&gt;&gt;

* u18B3A.016: L&lt;&lt;-1473.0,-492.0&gt;--&lt;-1474.0,-790.0&gt;&gt;

* u18B3A.017: L&lt;&lt;-973.0,-492.0&gt;--&lt;-974.0,-790.0&gt;&gt;

* u18B3A.018: L&lt;&lt;-473.0,-492.0&gt;--&lt;-474.0,-790.0&gt;&gt;

* u18B3A.019: L&lt;&lt;-1473.0,-992.0&gt;--&lt;-1474.0,-1290.0&gt;&gt;

* u18B3A.020: L&lt;&lt;-973.0,-992.0&gt;--&lt;-974.0,-1290.0&gt;&gt;

* u18B3A.021: L&lt;&lt;-473.0,-992.0&gt;--&lt;-474.0,-1290.0&gt;&gt;

* u18B3A.022: L&lt;&lt;527.0,1008.0&gt;--&lt;526.0,710.0&gt;&gt;

* u18B3A.023: L&lt;&lt;527.0,508.0&gt;--&lt;526.0,210.0&gt;&gt;

* u18B3E (U+18B3E): L&lt;&lt;190.0,-2.0&gt;--&lt;191.0,131.0&gt;&gt;

* u18B3E (U+18B3E): L&lt;&lt;191.0,131.0&gt;--&lt;190.0,262.0&gt;&gt;

* u18B3E.001: L&lt;&lt;190.0,1498.0&gt;--&lt;191.0,1631.0&gt;&gt;

* u18B3E.001: L&lt;&lt;191.0,1631.0&gt;--&lt;190.0,1762.0&gt;&gt;

* u18B3E.002: L&lt;&lt;690.0,1498.0&gt;--&lt;691.0,1631.0&gt;&gt;

* u18B3E.002: L&lt;&lt;691.0,1631.0&gt;--&lt;690.0,1762.0&gt;&gt;

* u18B3E.003: L&lt;&lt;-809.0,1631.0&gt;--&lt;-810.0,1762.0&gt;&gt;

* u18B3E.003: L&lt;&lt;-810.0,1498.0&gt;--&lt;-809.0,1631.0&gt;&gt;

* u18B3E.004: L&lt;&lt;190.0,998.0&gt;--&lt;191.0,1131.0&gt;&gt;

* u18B3E.004: L&lt;&lt;191.0,1131.0&gt;--&lt;190.0,1262.0&gt;&gt;

* u18B3E.005: L&lt;&lt;690.0,998.0&gt;--&lt;691.0,1131.0&gt;&gt;

* u18B3E.005: L&lt;&lt;691.0,1131.0&gt;--&lt;690.0,1262.0&gt;&gt;

* u18B3E.006: L&lt;&lt;-809.0,1131.0&gt;--&lt;-810.0,1262.0&gt;&gt;

* u18B3E.006: L&lt;&lt;-810.0,998.0&gt;--&lt;-809.0,1131.0&gt;&gt;

* u18B3E.007: L&lt;&lt;-1809.0,631.0&gt;--&lt;-1810.0,762.0&gt;&gt;

* u18B3E.007: L&lt;&lt;-1810.0,498.0&gt;--&lt;-1809.0,631.0&gt;&gt;

* u18B3E.008: L&lt;&lt;690.0,498.0&gt;--&lt;691.0,631.0&gt;&gt;

* u18B3E.008: L&lt;&lt;691.0,631.0&gt;--&lt;690.0,762.0&gt;&gt;

* u18B3E.009: L&lt;&lt;-809.0,631.0&gt;--&lt;-810.0,762.0&gt;&gt;

* u18B3E.009: L&lt;&lt;-810.0,498.0&gt;--&lt;-809.0,631.0&gt;&gt;

* u18B3E.010: L&lt;&lt;-1809.0,131.0&gt;--&lt;-1810.0,262.0&gt;&gt;

* u18B3E.010: L&lt;&lt;-1810.0,-2.0&gt;--&lt;-1809.0,131.0&gt;&gt;

* u18B3E.011: L&lt;&lt;690.0,-2.0&gt;--&lt;691.0,131.0&gt;&gt;

* u18B3E.011: L&lt;&lt;691.0,131.0&gt;--&lt;690.0,262.0&gt;&gt;

* u18B3E.012: L&lt;&lt;-809.0,131.0&gt;--&lt;-810.0,262.0&gt;&gt;

* u18B3E.012: L&lt;&lt;-810.0,-2.0&gt;--&lt;-809.0,131.0&gt;&gt;

* u18B3E.013: L&lt;&lt;-1809.0,-369.0&gt;--&lt;-1810.0,-238.0&gt;&gt;

* u18B3E.013: L&lt;&lt;-1810.0,-502.0&gt;--&lt;-1809.0,-369.0&gt;&gt;

* u18B3E.014: L&lt;&lt;-1309.0,-369.0&gt;--&lt;-1310.0,-238.0&gt;&gt;

* u18B3E.014: L&lt;&lt;-1310.0,-502.0&gt;--&lt;-1309.0,-369.0&gt;&gt;

* u18B3E.015: L&lt;&lt;-809.0,-369.0&gt;--&lt;-810.0,-238.0&gt;&gt;

* u18B3E.015: L&lt;&lt;-810.0,-502.0&gt;--&lt;-809.0,-369.0&gt;&gt;

* u18B3E.016: L&lt;&lt;-1809.0,-869.0&gt;--&lt;-1810.0,-738.0&gt;&gt;

* u18B3E.016: L&lt;&lt;-1810.0,-1002.0&gt;--&lt;-1809.0,-869.0&gt;&gt;

* u18B3E.017: L&lt;&lt;-1309.0,-869.0&gt;--&lt;-1310.0,-738.0&gt;&gt;

* u18B3E.017: L&lt;&lt;-1310.0,-1002.0&gt;--&lt;-1309.0,-869.0&gt;&gt;

* u18B3E.018: L&lt;&lt;-809.0,-869.0&gt;--&lt;-810.0,-738.0&gt;&gt;

* u18B3E.018: L&lt;&lt;-810.0,-1002.0&gt;--&lt;-809.0,-869.0&gt;&gt;

* u18B3E.019: L&lt;&lt;-1809.0,-1369.0&gt;--&lt;-1810.0,-1238.0&gt;&gt;

* u18B3E.019: L&lt;&lt;-1810.0,-1502.0&gt;--&lt;-1809.0,-1369.0&gt;&gt;

* u18B3E.020: L&lt;&lt;-1309.0,-1369.0&gt;--&lt;-1310.0,-1238.0&gt;&gt;

* u18B3E.020: L&lt;&lt;-1310.0,-1502.0&gt;--&lt;-1309.0,-1369.0&gt;&gt;

* u18B3E.021: L&lt;&lt;-809.0,-1369.0&gt;--&lt;-810.0,-1238.0&gt;&gt;

* u18B3E.021: L&lt;&lt;-810.0,-1502.0&gt;--&lt;-809.0,-1369.0&gt;&gt;

* u18B3E.022: L&lt;&lt;190.0,498.0&gt;--&lt;191.0,631.0&gt;&gt;

* u18B3E.022: L&lt;&lt;191.0,631.0&gt;--&lt;190.0,762.0&gt;&gt;

* u18B3E.023: L&lt;&lt;190.0,-2.0&gt;--&lt;191.0,131.0&gt;&gt;

* u18B3E.023: L&lt;&lt;191.0,131.0&gt;--&lt;190.0,262.0&gt;&gt;

* u18B3F (U+18B3F): L&lt;&lt;537.0,488.0&gt;--&lt;536.0,211.0&gt;&gt;

* u18B3F.001: L&lt;&lt;537.0,1988.0&gt;--&lt;536.0,1711.0&gt;&gt;

* u18B3F.002: L&lt;&lt;1037.0,1988.0&gt;--&lt;1036.0,1711.0&gt;&gt;

* u18B3F.003: L&lt;&lt;-463.0,1988.0&gt;--&lt;-464.0,1711.0&gt;&gt;

* u18B3F.004: L&lt;&lt;537.0,1488.0&gt;--&lt;536.0,1211.0&gt;&gt;

* u18B3F.005: L&lt;&lt;1037.0,1488.0&gt;--&lt;1036.0,1211.0&gt;&gt;

* u18B3F.006: L&lt;&lt;-463.0,1488.0&gt;--&lt;-464.0,1211.0&gt;&gt;

* u18B3F.007: L&lt;&lt;-1463.0,988.0&gt;--&lt;-1464.0,711.0&gt;&gt;

* u18B3F.008: L&lt;&lt;1037.0,988.0&gt;--&lt;1036.0,711.0&gt;&gt;

* u18B3F.009: L&lt;&lt;-463.0,988.0&gt;--&lt;-464.0,711.0&gt;&gt;

* u18B3F.010: L&lt;&lt;-1463.0,488.0&gt;--&lt;-1464.0,211.0&gt;&gt;

* u18B3F.011: L&lt;&lt;1037.0,488.0&gt;--&lt;1036.0,211.0&gt;&gt;

* u18B3F.012: L&lt;&lt;-463.0,488.0&gt;--&lt;-464.0,211.0&gt;&gt;

* u18B3F.013: L&lt;&lt;-1463.0,-12.0&gt;--&lt;-1464.0,-289.0&gt;&gt;

* u18B3F.014: L&lt;&lt;-963.0,-12.0&gt;--&lt;-964.0,-289.0&gt;&gt;

* u18B3F.015: L&lt;&lt;-463.0,-12.0&gt;--&lt;-464.0,-289.0&gt;&gt;

* u18B3F.016: L&lt;&lt;-1463.0,-512.0&gt;--&lt;-1464.0,-789.0&gt;&gt;

* u18B3F.017: L&lt;&lt;-963.0,-512.0&gt;--&lt;-964.0,-789.0&gt;&gt;

* u18B3F.018: L&lt;&lt;-463.0,-512.0&gt;--&lt;-464.0,-789.0&gt;&gt;

* u18B3F.019: L&lt;&lt;-1463.0,-1012.0&gt;--&lt;-1464.0,-1289.0&gt;&gt;

* u18B3F.020: L&lt;&lt;-963.0,-1012.0&gt;--&lt;-964.0,-1289.0&gt;&gt;

* u18B3F.021: L&lt;&lt;-463.0,-1012.0&gt;--&lt;-464.0,-1289.0&gt;&gt;

* u18B3F.022: L&lt;&lt;537.0,988.0&gt;--&lt;536.0,711.0&gt;&gt;

* u18B3F.023: L&lt;&lt;537.0,488.0&gt;--&lt;536.0,211.0&gt;&gt;

* u18B40 (U+18B40): L&lt;&lt;524.0,536.0&gt;--&lt;523.0,365.0&gt;&gt;

* u18B40.001: L&lt;&lt;524.0,2036.0&gt;--&lt;523.0,1865.0&gt;&gt;

* u18B40.002: L&lt;&lt;1024.0,2036.0&gt;--&lt;1023.0,1865.0&gt;&gt;

* u18B40.003: L&lt;&lt;-476.0,2036.0&gt;--&lt;-477.0,1865.0&gt;&gt;

* u18B40.004: L&lt;&lt;524.0,1536.0&gt;--&lt;523.0,1365.0&gt;&gt;

* u18B40.005: L&lt;&lt;1024.0,1536.0&gt;--&lt;1023.0,1365.0&gt;&gt;

* u18B40.006: L&lt;&lt;-476.0,1536.0&gt;--&lt;-477.0,1365.0&gt;&gt;

* u18B40.007: L&lt;&lt;-1476.0,1036.0&gt;--&lt;-1477.0,865.0&gt;&gt;

* u18B40.008: L&lt;&lt;1024.0,1036.0&gt;--&lt;1023.0,865.0&gt;&gt;

* u18B40.009: L&lt;&lt;-476.0,1036.0&gt;--&lt;-477.0,865.0&gt;&gt;

* u18B40.010: L&lt;&lt;-1476.0,536.0&gt;--&lt;-1477.0,365.0&gt;&gt;

* u18B40.011: L&lt;&lt;1024.0,536.0&gt;--&lt;1023.0,365.0&gt;&gt;

* u18B40.012: L&lt;&lt;-476.0,536.0&gt;--&lt;-477.0,365.0&gt;&gt;

* u18B40.013: L&lt;&lt;-1476.0,36.0&gt;--&lt;-1477.0,-135.0&gt;&gt;

* u18B40.014: L&lt;&lt;-976.0,36.0&gt;--&lt;-977.0,-135.0&gt;&gt;

* u18B40.015: L&lt;&lt;-476.0,36.0&gt;--&lt;-477.0,-135.0&gt;&gt;

* u18B40.016: L&lt;&lt;-1476.0,-464.0&gt;--&lt;-1477.0,-635.0&gt;&gt;

* u18B40.017: L&lt;&lt;-976.0,-464.0&gt;--&lt;-977.0,-635.0&gt;&gt;

* u18B40.018: L&lt;&lt;-476.0,-464.0&gt;--&lt;-477.0,-635.0&gt;&gt;

* u18B40.019: L&lt;&lt;-1476.0,-964.0&gt;--&lt;-1477.0,-1135.0&gt;&gt;

* u18B40.020: L&lt;&lt;-976.0,-964.0&gt;--&lt;-977.0,-1135.0&gt;&gt;

* u18B40.021: L&lt;&lt;-476.0,-964.0&gt;--&lt;-477.0,-1135.0&gt;&gt;

* u18B40.022: L&lt;&lt;524.0,1036.0&gt;--&lt;523.0,865.0&gt;&gt;

* u18B40.023: L&lt;&lt;524.0,536.0&gt;--&lt;523.0,365.0&gt;&gt;

* u18B46 (U+18B46): L&lt;&lt;535.0,411.0&gt;--&lt;534.0,215.0&gt;&gt;

* u18B46.001: L&lt;&lt;535.0,1911.0&gt;--&lt;534.0,1715.0&gt;&gt;

* u18B46.002: L&lt;&lt;1035.0,1911.0&gt;--&lt;1034.0,1715.0&gt;&gt;

* u18B46.003: L&lt;&lt;-465.0,1911.0&gt;--&lt;-466.0,1715.0&gt;&gt;

* u18B46.004: L&lt;&lt;535.0,1411.0&gt;--&lt;534.0,1215.0&gt;&gt;

* u18B46.005: L&lt;&lt;1035.0,1411.0&gt;--&lt;1034.0,1215.0&gt;&gt;

* u18B46.006: L&lt;&lt;-465.0,1411.0&gt;--&lt;-466.0,1215.0&gt;&gt;

* u18B46.007: L&lt;&lt;-1465.0,911.0&gt;--&lt;-1466.0,715.0&gt;&gt;

* u18B46.008: L&lt;&lt;1035.0,911.0&gt;--&lt;1034.0,715.0&gt;&gt;

* u18B46.009: L&lt;&lt;-465.0,911.0&gt;--&lt;-466.0,715.0&gt;&gt;

* u18B46.010: L&lt;&lt;-1465.0,411.0&gt;--&lt;-1466.0,215.0&gt;&gt;

* u18B46.011: L&lt;&lt;1035.0,411.0&gt;--&lt;1034.0,215.0&gt;&gt;

* u18B46.012: L&lt;&lt;-465.0,411.0&gt;--&lt;-466.0,215.0&gt;&gt;

* u18B46.013: L&lt;&lt;-1465.0,-89.0&gt;--&lt;-1466.0,-285.0&gt;&gt;

* u18B46.014: L&lt;&lt;-965.0,-89.0&gt;--&lt;-966.0,-285.0&gt;&gt;

* u18B46.015: L&lt;&lt;-465.0,-89.0&gt;--&lt;-466.0,-285.0&gt;&gt;

* u18B46.016: L&lt;&lt;-1465.0,-589.0&gt;--&lt;-1466.0,-785.0&gt;&gt;

* u18B46.017: L&lt;&lt;-965.0,-589.0&gt;--&lt;-966.0,-785.0&gt;&gt;

* u18B46.018: L&lt;&lt;-465.0,-589.0&gt;--&lt;-466.0,-785.0&gt;&gt;

* u18B46.019: L&lt;&lt;-1465.0,-1089.0&gt;--&lt;-1466.0,-1285.0&gt;&gt;

* u18B46.020: L&lt;&lt;-965.0,-1089.0&gt;--&lt;-966.0,-1285.0&gt;&gt;

* u18B46.021: L&lt;&lt;-465.0,-1089.0&gt;--&lt;-466.0,-1285.0&gt;&gt;

* u18B46.022: L&lt;&lt;535.0,911.0&gt;--&lt;534.0,715.0&gt;&gt;

* u18B46.023: L&lt;&lt;535.0,411.0&gt;--&lt;534.0,215.0&gt;&gt;

* u18B47 (U+18B47): L&lt;&lt;524.0,413.0&gt;--&lt;525.0,-43.0&gt;&gt;

* u18B47.001: L&lt;&lt;524.0,1913.0&gt;--&lt;525.0,1457.0&gt;&gt;

* u18B47.002: L&lt;&lt;1024.0,1913.0&gt;--&lt;1025.0,1457.0&gt;&gt;

* u18B47.003: L&lt;&lt;-476.0,1913.0&gt;--&lt;-475.0,1457.0&gt;&gt;

* u18B47.004: L&lt;&lt;524.0,1413.0&gt;--&lt;525.0,957.0&gt;&gt;

* u18B47.005: L&lt;&lt;1024.0,1413.0&gt;--&lt;1025.0,957.0&gt;&gt;

* u18B47.006: L&lt;&lt;-476.0,1413.0&gt;--&lt;-475.0,957.0&gt;&gt;

* u18B47.007: L&lt;&lt;-1476.0,913.0&gt;--&lt;-1475.0,457.0&gt;&gt;

* u18B47.008: L&lt;&lt;1024.0,913.0&gt;--&lt;1025.0,457.0&gt;&gt;

* u18B47.009: L&lt;&lt;-476.0,913.0&gt;--&lt;-475.0,457.0&gt;&gt;

* u18B47.010: L&lt;&lt;-1476.0,413.0&gt;--&lt;-1475.0,-43.0&gt;&gt;

* u18B47.011: L&lt;&lt;1024.0,413.0&gt;--&lt;1025.0,-43.0&gt;&gt;

* u18B47.012: L&lt;&lt;-476.0,413.0&gt;--&lt;-475.0,-43.0&gt;&gt;

* u18B47.013: L&lt;&lt;-1476.0,-87.0&gt;--&lt;-1475.0,-543.0&gt;&gt;

* u18B47.014: L&lt;&lt;-976.0,-87.0&gt;--&lt;-975.0,-543.0&gt;&gt;

* u18B47.015: L&lt;&lt;-476.0,-87.0&gt;--&lt;-475.0,-543.0&gt;&gt;

* u18B47.016: L&lt;&lt;-1476.0,-587.0&gt;--&lt;-1475.0,-1043.0&gt;&gt;

* u18B47.017: L&lt;&lt;-976.0,-587.0&gt;--&lt;-975.0,-1043.0&gt;&gt;

* u18B47.018: L&lt;&lt;-476.0,-587.0&gt;--&lt;-475.0,-1043.0&gt;&gt;

* u18B47.019: L&lt;&lt;-1476.0,-1087.0&gt;--&lt;-1475.0,-1543.0&gt;&gt;

* u18B47.020: L&lt;&lt;-976.0,-1087.0&gt;--&lt;-975.0,-1543.0&gt;&gt;

* u18B47.021: L&lt;&lt;-476.0,-1087.0&gt;--&lt;-475.0,-1543.0&gt;&gt;

* u18B47.022: L&lt;&lt;524.0,913.0&gt;--&lt;525.0,457.0&gt;&gt;

* u18B47.023: L&lt;&lt;524.0,413.0&gt;--&lt;525.0,-43.0&gt;&gt;

* u18B4B (U+18B4B): L&lt;&lt;876.0,581.0&gt;--&lt;875.0,211.0&gt;&gt;

* u18B4B.001: L&lt;&lt;876.0,2081.0&gt;--&lt;875.0,1711.0&gt;&gt;

* u18B4B.002: L&lt;&lt;1376.0,2081.0&gt;--&lt;1375.0,1711.0&gt;&gt;

* u18B4B.003: L&lt;&lt;-124.0,2081.0&gt;--&lt;-125.0,1711.0&gt;&gt;

* u18B4B.004: L&lt;&lt;876.0,1581.0&gt;--&lt;875.0,1211.0&gt;&gt;

* u18B4B.005: L&lt;&lt;1376.0,1581.0&gt;--&lt;1375.0,1211.0&gt;&gt;

* u18B4B.006: L&lt;&lt;-124.0,1581.0&gt;--&lt;-125.0,1211.0&gt;&gt;

* u18B4B.007: L&lt;&lt;-1124.0,1081.0&gt;--&lt;-1125.0,711.0&gt;&gt;

* u18B4B.008: L&lt;&lt;1376.0,1081.0&gt;--&lt;1375.0,711.0&gt;&gt;

* u18B4B.009: L&lt;&lt;-124.0,1081.0&gt;--&lt;-125.0,711.0&gt;&gt;

* u18B4B.010: L&lt;&lt;-1124.0,581.0&gt;--&lt;-1125.0,211.0&gt;&gt;

* u18B4B.011: L&lt;&lt;1376.0,581.0&gt;--&lt;1375.0,211.0&gt;&gt;

* u18B4B.012: L&lt;&lt;-124.0,581.0&gt;--&lt;-125.0,211.0&gt;&gt;

* u18B4B.013: L&lt;&lt;-1124.0,81.0&gt;--&lt;-1125.0,-289.0&gt;&gt;

* u18B4B.014: L&lt;&lt;-624.0,81.0&gt;--&lt;-625.0,-289.0&gt;&gt;

* u18B4B.015: L&lt;&lt;-124.0,81.0&gt;--&lt;-125.0,-289.0&gt;&gt;

* u18B4B.016: L&lt;&lt;-1124.0,-419.0&gt;--&lt;-1125.0,-789.0&gt;&gt;

* u18B4B.017: L&lt;&lt;-624.0,-419.0&gt;--&lt;-625.0,-789.0&gt;&gt;

* u18B4B.018: L&lt;&lt;-124.0,-419.0&gt;--&lt;-125.0,-789.0&gt;&gt;

* u18B4B.019: L&lt;&lt;-1124.0,-919.0&gt;--&lt;-1125.0,-1289.0&gt;&gt;

* u18B4B.020: L&lt;&lt;-624.0,-919.0&gt;--&lt;-625.0,-1289.0&gt;&gt;

* u18B4B.021: L&lt;&lt;-124.0,-919.0&gt;--&lt;-125.0,-1289.0&gt;&gt;

* u18B4B.022: L&lt;&lt;876.0,1081.0&gt;--&lt;875.0,711.0&gt;&gt;

* u18B4B.023: L&lt;&lt;876.0,581.0&gt;--&lt;875.0,211.0&gt;&gt;

* u18B53 (U+18B53): L&lt;&lt;437.0,571.0&gt;--&lt;436.0,349.0&gt;&gt;

* u18B53.001: L&lt;&lt;437.0,2071.0&gt;--&lt;436.0,1849.0&gt;&gt;

* u18B53.002: L&lt;&lt;937.0,2071.0&gt;--&lt;936.0,1849.0&gt;&gt;

* u18B53.003: L&lt;&lt;-563.0,2071.0&gt;--&lt;-564.0,1849.0&gt;&gt;

* u18B53.004: L&lt;&lt;437.0,1571.0&gt;--&lt;436.0,1349.0&gt;&gt;

* u18B53.005: L&lt;&lt;937.0,1571.0&gt;--&lt;936.0,1349.0&gt;&gt;

* u18B53.006: L&lt;&lt;-563.0,1571.0&gt;--&lt;-564.0,1349.0&gt;&gt;

* u18B53.007: L&lt;&lt;-1563.0,1071.0&gt;--&lt;-1564.0,849.0&gt;&gt;

* u18B53.008: L&lt;&lt;937.0,1071.0&gt;--&lt;936.0,849.0&gt;&gt;

* u18B53.009: L&lt;&lt;-563.0,1071.0&gt;--&lt;-564.0,849.0&gt;&gt;

* u18B53.010: L&lt;&lt;-1563.0,571.0&gt;--&lt;-1564.0,349.0&gt;&gt;

* u18B53.011: L&lt;&lt;937.0,571.0&gt;--&lt;936.0,349.0&gt;&gt;

* u18B53.012: L&lt;&lt;-563.0,571.0&gt;--&lt;-564.0,349.0&gt;&gt;

* u18B53.013: L&lt;&lt;-1563.0,71.0&gt;--&lt;-1564.0,-151.0&gt;&gt;

* u18B53.014: L&lt;&lt;-1063.0,71.0&gt;--&lt;-1064.0,-151.0&gt;&gt;

* u18B53.015: L&lt;&lt;-563.0,71.0&gt;--&lt;-564.0,-151.0&gt;&gt;

* u18B53.016: L&lt;&lt;-1563.0,-429.0&gt;--&lt;-1564.0,-651.0&gt;&gt;

* u18B53.017: L&lt;&lt;-1063.0,-429.0&gt;--&lt;-1064.0,-651.0&gt;&gt;

* u18B53.018: L&lt;&lt;-563.0,-429.0&gt;--&lt;-564.0,-651.0&gt;&gt;

* u18B53.019: L&lt;&lt;-1563.0,-929.0&gt;--&lt;-1564.0,-1151.0&gt;&gt;

* u18B53.020: L&lt;&lt;-1063.0,-929.0&gt;--&lt;-1064.0,-1151.0&gt;&gt;

* u18B53.021: L&lt;&lt;-563.0,-929.0&gt;--&lt;-564.0,-1151.0&gt;&gt;

* u18B53.022: L&lt;&lt;437.0,1071.0&gt;--&lt;436.0,849.0&gt;&gt;

* u18B53.023: L&lt;&lt;437.0,571.0&gt;--&lt;436.0,349.0&gt;&gt;

* u18B54 (U+18B54): L&lt;&lt;464.0,-25.0&gt;--&lt;465.0,315.0&gt;&gt;

* u18B54.001: L&lt;&lt;464.0,1475.0&gt;--&lt;465.0,1815.0&gt;&gt;

* u18B54.002: L&lt;&lt;964.0,1475.0&gt;--&lt;965.0,1815.0&gt;&gt;

* u18B54.003: L&lt;&lt;-536.0,1475.0&gt;--&lt;-535.0,1815.0&gt;&gt;

* u18B54.004: L&lt;&lt;464.0,975.0&gt;--&lt;465.0,1315.0&gt;&gt;

* u18B54.005: L&lt;&lt;964.0,975.0&gt;--&lt;965.0,1315.0&gt;&gt;

* u18B54.006: L&lt;&lt;-536.0,975.0&gt;--&lt;-535.0,1315.0&gt;&gt;

* u18B54.007: L&lt;&lt;-1536.0,475.0&gt;--&lt;-1535.0,815.0&gt;&gt;

* u18B54.008: L&lt;&lt;964.0,475.0&gt;--&lt;965.0,815.0&gt;&gt;

* u18B54.009: L&lt;&lt;-536.0,475.0&gt;--&lt;-535.0,815.0&gt;&gt;

* u18B54.010: L&lt;&lt;-1536.0,-25.0&gt;--&lt;-1535.0,315.0&gt;&gt;

* u18B54.011: L&lt;&lt;964.0,-25.0&gt;--&lt;965.0,315.0&gt;&gt;

* u18B54.012: L&lt;&lt;-536.0,-25.0&gt;--&lt;-535.0,315.0&gt;&gt;

* u18B54.013: L&lt;&lt;-1536.0,-525.0&gt;--&lt;-1535.0,-185.0&gt;&gt;

* u18B54.014: L&lt;&lt;-1036.0,-525.0&gt;--&lt;-1035.0,-185.0&gt;&gt;

* u18B54.015: L&lt;&lt;-536.0,-525.0&gt;--&lt;-535.0,-185.0&gt;&gt;

* u18B54.016: L&lt;&lt;-1536.0,-1025.0&gt;--&lt;-1535.0,-685.0&gt;&gt;

* u18B54.017: L&lt;&lt;-1036.0,-1025.0&gt;--&lt;-1035.0,-685.0&gt;&gt;

* u18B54.018: L&lt;&lt;-536.0,-1025.0&gt;--&lt;-535.0,-685.0&gt;&gt;

* u18B54.019: L&lt;&lt;-1536.0,-1525.0&gt;--&lt;-1535.0,-1185.0&gt;&gt;

* u18B54.020: L&lt;&lt;-1036.0,-1525.0&gt;--&lt;-1035.0,-1185.0&gt;&gt;

* u18B54.021: L&lt;&lt;-536.0,-1525.0&gt;--&lt;-535.0,-1185.0&gt;&gt;

* u18B54.022: L&lt;&lt;464.0,475.0&gt;--&lt;465.0,815.0&gt;&gt;

* u18B54.023: L&lt;&lt;464.0,-25.0&gt;--&lt;465.0,315.0&gt;&gt;

* u18B55 (U+18B55): L&lt;&lt;464.0,23.0&gt;--&lt;465.0,335.0&gt;&gt;

* u18B55.001: L&lt;&lt;464.0,1523.0&gt;--&lt;465.0,1835.0&gt;&gt;

* u18B55.002: L&lt;&lt;964.0,1523.0&gt;--&lt;965.0,1835.0&gt;&gt;

* u18B55.003: L&lt;&lt;-536.0,1523.0&gt;--&lt;-535.0,1835.0&gt;&gt;

* u18B55.004: L&lt;&lt;464.0,1023.0&gt;--&lt;465.0,1335.0&gt;&gt;

* u18B55.005: L&lt;&lt;964.0,1023.0&gt;--&lt;965.0,1335.0&gt;&gt;

* u18B55.006: L&lt;&lt;-536.0,1023.0&gt;--&lt;-535.0,1335.0&gt;&gt;

* u18B55.007: L&lt;&lt;-1536.0,523.0&gt;--&lt;-1535.0,835.0&gt;&gt;

* u18B55.008: L&lt;&lt;964.0,523.0&gt;--&lt;965.0,835.0&gt;&gt;

* u18B55.009: L&lt;&lt;-536.0,523.0&gt;--&lt;-535.0,835.0&gt;&gt;

* u18B55.010: L&lt;&lt;-1536.0,23.0&gt;--&lt;-1535.0,335.0&gt;&gt;

* u18B55.011: L&lt;&lt;964.0,23.0&gt;--&lt;965.0,335.0&gt;&gt;

* u18B55.012: L&lt;&lt;-536.0,23.0&gt;--&lt;-535.0,335.0&gt;&gt;

* u18B55.013: L&lt;&lt;-1536.0,-477.0&gt;--&lt;-1535.0,-165.0&gt;&gt;

* u18B55.014: L&lt;&lt;-1036.0,-477.0&gt;--&lt;-1035.0,-165.0&gt;&gt;

* u18B55.015: L&lt;&lt;-536.0,-477.0&gt;--&lt;-535.0,-165.0&gt;&gt;

* u18B55.016: L&lt;&lt;-1536.0,-977.0&gt;--&lt;-1535.0,-665.0&gt;&gt;

* u18B55.017: L&lt;&lt;-1036.0,-977.0&gt;--&lt;-1035.0,-665.0&gt;&gt;

* u18B55.018: L&lt;&lt;-536.0,-977.0&gt;--&lt;-535.0,-665.0&gt;&gt;

* u18B55.019: L&lt;&lt;-1536.0,-1477.0&gt;--&lt;-1535.0,-1165.0&gt;&gt;

* u18B55.020: L&lt;&lt;-1036.0,-1477.0&gt;--&lt;-1035.0,-1165.0&gt;&gt;

* u18B55.021: L&lt;&lt;-536.0,-1477.0&gt;--&lt;-535.0,-1165.0&gt;&gt;

* u18B55.022: L&lt;&lt;464.0,523.0&gt;--&lt;465.0,835.0&gt;&gt;

* u18B55.023: L&lt;&lt;464.0,23.0&gt;--&lt;465.0,335.0&gt;&gt;

* u18B5C (U+18B5C): L&lt;&lt;539.0,538.0&gt;--&lt;538.0,193.0&gt;&gt;

* u18B5C.001: L&lt;&lt;539.0,2038.0&gt;--&lt;538.0,1693.0&gt;&gt;

* u18B5C.002: L&lt;&lt;1039.0,2038.0&gt;--&lt;1038.0,1693.0&gt;&gt;

* u18B5C.003: L&lt;&lt;-461.0,2038.0&gt;--&lt;-462.0,1693.0&gt;&gt;

* u18B5C.004: L&lt;&lt;539.0,1538.0&gt;--&lt;538.0,1193.0&gt;&gt;

* u18B5C.005: L&lt;&lt;1039.0,1538.0&gt;--&lt;1038.0,1193.0&gt;&gt;

* u18B5C.006: L&lt;&lt;-461.0,1538.0&gt;--&lt;-462.0,1193.0&gt;&gt;

* u18B5C.007: L&lt;&lt;-1461.0,1038.0&gt;--&lt;-1462.0,693.0&gt;&gt;

* u18B5C.008: L&lt;&lt;1039.0,1038.0&gt;--&lt;1038.0,693.0&gt;&gt;

* u18B5C.009: L&lt;&lt;-461.0,1038.0&gt;--&lt;-462.0,693.0&gt;&gt;

* u18B5C.010: L&lt;&lt;-1461.0,538.0&gt;--&lt;-1462.0,193.0&gt;&gt;

* u18B5C.011: L&lt;&lt;1039.0,538.0&gt;--&lt;1038.0,193.0&gt;&gt;

* u18B5C.012: L&lt;&lt;-461.0,538.0&gt;--&lt;-462.0,193.0&gt;&gt;

* u18B5C.013: L&lt;&lt;-1461.0,38.0&gt;--&lt;-1462.0,-307.0&gt;&gt;

* u18B5C.014: L&lt;&lt;-961.0,38.0&gt;--&lt;-962.0,-307.0&gt;&gt;

* u18B5C.015: L&lt;&lt;-461.0,38.0&gt;--&lt;-462.0,-307.0&gt;&gt;

* u18B5C.016: L&lt;&lt;-1461.0,-462.0&gt;--&lt;-1462.0,-807.0&gt;&gt;

* u18B5C.017: L&lt;&lt;-961.0,-462.0&gt;--&lt;-962.0,-807.0&gt;&gt;

* u18B5C.018: L&lt;&lt;-461.0,-462.0&gt;--&lt;-462.0,-807.0&gt;&gt;

* u18B5C.019: L&lt;&lt;-1461.0,-962.0&gt;--&lt;-1462.0,-1307.0&gt;&gt;

* u18B5C.020: L&lt;&lt;-961.0,-962.0&gt;--&lt;-962.0,-1307.0&gt;&gt;

* u18B5C.021: L&lt;&lt;-461.0,-962.0&gt;--&lt;-462.0,-1307.0&gt;&gt;

* u18B5C.022: L&lt;&lt;539.0,1038.0&gt;--&lt;538.0,693.0&gt;&gt;

* u18B5C.023: L&lt;&lt;539.0,538.0&gt;--&lt;538.0,193.0&gt;&gt;

* u18B64 (U+18B64): L&lt;&lt;370.0,516.0&gt;--&lt;369.0,360.0&gt;&gt;

* u18B64 (U+18B64): L&lt;&lt;661.0,543.0&gt;--&lt;660.0,389.0&gt;&gt;

* u18B64.001: L&lt;&lt;370.0,2016.0&gt;--&lt;369.0,1860.0&gt;&gt;

* u18B64.001: L&lt;&lt;661.0,2043.0&gt;--&lt;660.0,1889.0&gt;&gt;

* u18B64.002: L&lt;&lt;1161.0,2043.0&gt;--&lt;1160.0,1889.0&gt;&gt;

* u18B64.002: L&lt;&lt;870.0,2016.0&gt;--&lt;869.0,1860.0&gt;&gt;

* u18B64.003: L&lt;&lt;-339.0,2043.0&gt;--&lt;-340.0,1889.0&gt;&gt;

* u18B64.003: L&lt;&lt;-630.0,2016.0&gt;--&lt;-631.0,1860.0&gt;&gt;

* u18B64.004: L&lt;&lt;370.0,1516.0&gt;--&lt;369.0,1360.0&gt;&gt;

* u18B64.004: L&lt;&lt;661.0,1543.0&gt;--&lt;660.0,1389.0&gt;&gt;

* u18B64.005: L&lt;&lt;1161.0,1543.0&gt;--&lt;1160.0,1389.0&gt;&gt;

* u18B64.005: L&lt;&lt;870.0,1516.0&gt;--&lt;869.0,1360.0&gt;&gt;

* u18B64.006: L&lt;&lt;-339.0,1543.0&gt;--&lt;-340.0,1389.0&gt;&gt;

* u18B64.006: L&lt;&lt;-630.0,1516.0&gt;--&lt;-631.0,1360.0&gt;&gt;

* u18B64.007: L&lt;&lt;-1339.0,1043.0&gt;--&lt;-1340.0,889.0&gt;&gt;

* u18B64.007: L&lt;&lt;-1630.0,1016.0&gt;--&lt;-1631.0,860.0&gt;&gt;

* u18B64.008: L&lt;&lt;1161.0,1043.0&gt;--&lt;1160.0,889.0&gt;&gt;

* u18B64.008: L&lt;&lt;870.0,1016.0&gt;--&lt;869.0,860.0&gt;&gt;

* u18B64.009: L&lt;&lt;-339.0,1043.0&gt;--&lt;-340.0,889.0&gt;&gt;

* u18B64.009: L&lt;&lt;-630.0,1016.0&gt;--&lt;-631.0,860.0&gt;&gt;

* u18B64.010: L&lt;&lt;-1339.0,543.0&gt;--&lt;-1340.0,389.0&gt;&gt;

* u18B64.010: L&lt;&lt;-1630.0,516.0&gt;--&lt;-1631.0,360.0&gt;&gt;

* u18B64.011: L&lt;&lt;1161.0,543.0&gt;--&lt;1160.0,389.0&gt;&gt;

* u18B64.011: L&lt;&lt;870.0,516.0&gt;--&lt;869.0,360.0&gt;&gt;

* u18B64.012: L&lt;&lt;-339.0,543.0&gt;--&lt;-340.0,389.0&gt;&gt;

* u18B64.012: L&lt;&lt;-630.0,516.0&gt;--&lt;-631.0,360.0&gt;&gt;

* u18B64.013: L&lt;&lt;-1339.0,43.0&gt;--&lt;-1340.0,-111.0&gt;&gt;

* u18B64.013: L&lt;&lt;-1630.0,16.0&gt;--&lt;-1631.0,-140.0&gt;&gt;

* u18B64.014: L&lt;&lt;-1130.0,16.0&gt;--&lt;-1131.0,-140.0&gt;&gt;

* u18B64.014: L&lt;&lt;-839.0,43.0&gt;--&lt;-840.0,-111.0&gt;&gt;

* u18B64.015: L&lt;&lt;-339.0,43.0&gt;--&lt;-340.0,-111.0&gt;&gt;

* u18B64.015: L&lt;&lt;-630.0,16.0&gt;--&lt;-631.0,-140.0&gt;&gt;

* u18B64.016: L&lt;&lt;-1339.0,-457.0&gt;--&lt;-1340.0,-611.0&gt;&gt;

* u18B64.016: L&lt;&lt;-1630.0,-484.0&gt;--&lt;-1631.0,-640.0&gt;&gt;

* u18B64.017: L&lt;&lt;-1130.0,-484.0&gt;--&lt;-1131.0,-640.0&gt;&gt;

* u18B64.017: L&lt;&lt;-839.0,-457.0&gt;--&lt;-840.0,-611.0&gt;&gt;

* u18B64.018: L&lt;&lt;-339.0,-457.0&gt;--&lt;-340.0,-611.0&gt;&gt;

* u18B64.018: L&lt;&lt;-630.0,-484.0&gt;--&lt;-631.0,-640.0&gt;&gt;

* u18B64.019: L&lt;&lt;-1339.0,-957.0&gt;--&lt;-1340.0,-1111.0&gt;&gt;

* u18B64.019: L&lt;&lt;-1630.0,-984.0&gt;--&lt;-1631.0,-1140.0&gt;&gt;

* u18B64.020: L&lt;&lt;-1130.0,-984.0&gt;--&lt;-1131.0,-1140.0&gt;&gt;

* u18B64.020: L&lt;&lt;-839.0,-957.0&gt;--&lt;-840.0,-1111.0&gt;&gt;

* u18B64.021: L&lt;&lt;-339.0,-957.0&gt;--&lt;-340.0,-1111.0&gt;&gt;

* u18B64.021: L&lt;&lt;-630.0,-984.0&gt;--&lt;-631.0,-1140.0&gt;&gt;

* u18B64.022: L&lt;&lt;370.0,1016.0&gt;--&lt;369.0,860.0&gt;&gt;

* u18B64.022: L&lt;&lt;661.0,1043.0&gt;--&lt;660.0,889.0&gt;&gt;

* u18B64.023: L&lt;&lt;370.0,516.0&gt;--&lt;369.0,360.0&gt;&gt;

* u18B64.023: L&lt;&lt;661.0,543.0&gt;--&lt;660.0,389.0&gt;&gt;

* u18B69 (U+18B69): L&lt;&lt;349.0,387.0&gt;--&lt;347.0,46.0&gt;&gt;

* u18B69 (U+18B69): L&lt;&lt;689.0,414.0&gt;--&lt;686.0,-23.0&gt;&gt;

* u18B69.001: L&lt;&lt;349.0,1887.0&gt;--&lt;347.0,1546.0&gt;&gt;

* u18B69.001: L&lt;&lt;689.0,1914.0&gt;--&lt;686.0,1477.0&gt;&gt;

* u18B69.002: L&lt;&lt;1189.0,1914.0&gt;--&lt;1186.0,1477.0&gt;&gt;

* u18B69.002: L&lt;&lt;849.0,1887.0&gt;--&lt;847.0,1546.0&gt;&gt;

* u18B69.003: L&lt;&lt;-311.0,1914.0&gt;--&lt;-314.0,1477.0&gt;&gt;

* u18B69.003: L&lt;&lt;-651.0,1887.0&gt;--&lt;-653.0,1546.0&gt;&gt;

* u18B69.004: L&lt;&lt;349.0,1387.0&gt;--&lt;347.0,1046.0&gt;&gt;

* u18B69.004: L&lt;&lt;689.0,1414.0&gt;--&lt;686.0,977.0&gt;&gt;

* u18B69.005: L&lt;&lt;1189.0,1414.0&gt;--&lt;1186.0,977.0&gt;&gt;

* u18B69.005: L&lt;&lt;849.0,1387.0&gt;--&lt;847.0,1046.0&gt;&gt;

* u18B69.006: L&lt;&lt;-311.0,1414.0&gt;--&lt;-314.0,977.0&gt;&gt;

* u18B69.006: L&lt;&lt;-651.0,1387.0&gt;--&lt;-653.0,1046.0&gt;&gt;

* u18B69.007: L&lt;&lt;-1311.0,914.0&gt;--&lt;-1314.0,477.0&gt;&gt;

* u18B69.007: L&lt;&lt;-1651.0,887.0&gt;--&lt;-1653.0,546.0&gt;&gt;

* u18B69.008: L&lt;&lt;1189.0,914.0&gt;--&lt;1186.0,477.0&gt;&gt;

* u18B69.008: L&lt;&lt;849.0,887.0&gt;--&lt;847.0,546.0&gt;&gt;

* u18B69.009: L&lt;&lt;-311.0,914.0&gt;--&lt;-314.0,477.0&gt;&gt;

* u18B69.009: L&lt;&lt;-651.0,887.0&gt;--&lt;-653.0,546.0&gt;&gt;

* u18B69.010: L&lt;&lt;-1311.0,414.0&gt;--&lt;-1314.0,-23.0&gt;&gt;

* u18B69.010: L&lt;&lt;-1651.0,387.0&gt;--&lt;-1653.0,46.0&gt;&gt;

* u18B69.011: L&lt;&lt;1189.0,414.0&gt;--&lt;1186.0,-23.0&gt;&gt;

* u18B69.011: L&lt;&lt;849.0,387.0&gt;--&lt;847.0,46.0&gt;&gt;

* u18B69.012: L&lt;&lt;-311.0,414.0&gt;--&lt;-314.0,-23.0&gt;&gt;

* u18B69.012: L&lt;&lt;-651.0,387.0&gt;--&lt;-653.0,46.0&gt;&gt;

* u18B69.013: L&lt;&lt;-1311.0,-86.0&gt;--&lt;-1314.0,-523.0&gt;&gt;

* u18B69.013: L&lt;&lt;-1651.0,-113.0&gt;--&lt;-1653.0,-454.0&gt;&gt;

* u18B69.014: L&lt;&lt;-1151.0,-113.0&gt;--&lt;-1153.0,-454.0&gt;&gt;

* u18B69.014: L&lt;&lt;-811.0,-86.0&gt;--&lt;-814.0,-523.0&gt;&gt;

* u18B69.015: L&lt;&lt;-311.0,-86.0&gt;--&lt;-314.0,-523.0&gt;&gt;

* u18B69.015: L&lt;&lt;-651.0,-113.0&gt;--&lt;-653.0,-454.0&gt;&gt;

* u18B69.016: L&lt;&lt;-1311.0,-586.0&gt;--&lt;-1314.0,-1023.0&gt;&gt;

* u18B69.016: L&lt;&lt;-1651.0,-613.0&gt;--&lt;-1653.0,-954.0&gt;&gt;

* u18B69.017: L&lt;&lt;-1151.0,-613.0&gt;--&lt;-1153.0,-954.0&gt;&gt;

* u18B69.017: L&lt;&lt;-811.0,-586.0&gt;--&lt;-814.0,-1023.0&gt;&gt;

* u18B69.018: L&lt;&lt;-311.0,-586.0&gt;--&lt;-314.0,-1023.0&gt;&gt;

* u18B69.018: L&lt;&lt;-651.0,-613.0&gt;--&lt;-653.0,-954.0&gt;&gt;

* u18B69.019: L&lt;&lt;-1311.0,-1086.0&gt;--&lt;-1314.0,-1523.0&gt;&gt;

* u18B69.019: L&lt;&lt;-1651.0,-1113.0&gt;--&lt;-1653.0,-1454.0&gt;&gt;

* u18B69.020: L&lt;&lt;-1151.0,-1113.0&gt;--&lt;-1153.0,-1454.0&gt;&gt;

* u18B69.020: L&lt;&lt;-811.0,-1086.0&gt;--&lt;-814.0,-1523.0&gt;&gt;

* u18B69.021: L&lt;&lt;-311.0,-1086.0&gt;--&lt;-314.0,-1523.0&gt;&gt;

* u18B69.021: L&lt;&lt;-651.0,-1113.0&gt;--&lt;-653.0,-1454.0&gt;&gt;

* u18B69.022: L&lt;&lt;349.0,887.0&gt;--&lt;347.0,546.0&gt;&gt;

* u18B69.022: L&lt;&lt;689.0,914.0&gt;--&lt;686.0,477.0&gt;&gt;

* u18B69.023: L&lt;&lt;349.0,387.0&gt;--&lt;347.0,46.0&gt;&gt;

* u18B69.023: L&lt;&lt;689.0,414.0&gt;--&lt;686.0,-23.0&gt;&gt;

* u18B80 (U+18B80): L&lt;&lt;814.0,177.0&gt;--&lt;813.0,62.0&gt;&gt;

* u18B80.001: L&lt;&lt;814.0,1677.0&gt;--&lt;813.0,1562.0&gt;&gt;

* u18B80.002: L&lt;&lt;1314.0,1677.0&gt;--&lt;1313.0,1562.0&gt;&gt;

* u18B80.003: L&lt;&lt;-186.0,1677.0&gt;--&lt;-187.0,1562.0&gt;&gt;

* u18B80.004: L&lt;&lt;814.0,1177.0&gt;--&lt;813.0,1062.0&gt;&gt;

* u18B80.005: L&lt;&lt;1314.0,1177.0&gt;--&lt;1313.0,1062.0&gt;&gt;

* u18B80.006: L&lt;&lt;-186.0,1177.0&gt;--&lt;-187.0,1062.0&gt;&gt;

* u18B80.007: L&lt;&lt;-1186.0,677.0&gt;--&lt;-1187.0,562.0&gt;&gt;

* u18B80.008: L&lt;&lt;1314.0,677.0&gt;--&lt;1313.0,562.0&gt;&gt;

* u18B80.009: L&lt;&lt;-186.0,677.0&gt;--&lt;-187.0,562.0&gt;&gt;

* u18B80.010: L&lt;&lt;-1186.0,177.0&gt;--&lt;-1187.0,62.0&gt;&gt;

* u18B80.011: L&lt;&lt;1314.0,177.0&gt;--&lt;1313.0,62.0&gt;&gt;

* u18B80.012: L&lt;&lt;-186.0,177.0&gt;--&lt;-187.0,62.0&gt;&gt;

* u18B80.013: L&lt;&lt;-1186.0,-323.0&gt;--&lt;-1187.0,-438.0&gt;&gt;

* u18B80.014: L&lt;&lt;-686.0,-323.0&gt;--&lt;-687.0,-438.0&gt;&gt;

* u18B80.015: L&lt;&lt;-186.0,-323.0&gt;--&lt;-187.0,-438.0&gt;&gt;

* u18B80.016: L&lt;&lt;-1186.0,-823.0&gt;--&lt;-1187.0,-938.0&gt;&gt;

* u18B80.017: L&lt;&lt;-686.0,-823.0&gt;--&lt;-687.0,-938.0&gt;&gt;

* u18B80.018: L&lt;&lt;-186.0,-823.0&gt;--&lt;-187.0,-938.0&gt;&gt;

* u18B80.019: L&lt;&lt;-1186.0,-1323.0&gt;--&lt;-1187.0,-1438.0&gt;&gt;

* u18B80.020: L&lt;&lt;-686.0,-1323.0&gt;--&lt;-687.0,-1438.0&gt;&gt;

* u18B80.021: L&lt;&lt;-186.0,-1323.0&gt;--&lt;-187.0,-1438.0&gt;&gt;

* u18B80.022: L&lt;&lt;814.0,677.0&gt;--&lt;813.0,562.0&gt;&gt;

* u18B80.023: L&lt;&lt;814.0,177.0&gt;--&lt;813.0,62.0&gt;&gt;

* u18B95 (U+18B95): L&lt;&lt;448.0,517.0&gt;--&lt;447.0,-26.0&gt;&gt;

* u18B95 (U+18B95): L&lt;&lt;589.0,-16.0&gt;--&lt;590.0,436.0&gt;&gt;

* u18B95 (U+18B95): L&lt;&lt;652.0,567.0&gt;--&lt;651.0,-11.0&gt;&gt;

* u18B95.001: L&lt;&lt;448.0,2017.0&gt;--&lt;447.0,1474.0&gt;&gt;

* u18B95.001: L&lt;&lt;589.0,1484.0&gt;--&lt;590.0,1936.0&gt;&gt;

* u18B95.001: L&lt;&lt;652.0,2067.0&gt;--&lt;651.0,1489.0&gt;&gt;

* u18B95.002: L&lt;&lt;1089.0,1484.0&gt;--&lt;1090.0,1936.0&gt;&gt;

* u18B95.002: L&lt;&lt;1152.0,2067.0&gt;--&lt;1151.0,1489.0&gt;&gt;

* u18B95.002: L&lt;&lt;948.0,2017.0&gt;--&lt;947.0,1474.0&gt;&gt;

* u18B95.003: L&lt;&lt;-348.0,2067.0&gt;--&lt;-349.0,1489.0&gt;&gt;

* u18B95.003: L&lt;&lt;-411.0,1484.0&gt;--&lt;-410.0,1936.0&gt;&gt;

* u18B95.003: L&lt;&lt;-552.0,2017.0&gt;--&lt;-553.0,1474.0&gt;&gt;

* u18B95.004: L&lt;&lt;448.0,1517.0&gt;--&lt;447.0,974.0&gt;&gt;

* u18B95.004: L&lt;&lt;589.0,984.0&gt;--&lt;590.0,1436.0&gt;&gt;

* u18B95.004: L&lt;&lt;652.0,1567.0&gt;--&lt;651.0,989.0&gt;&gt;

* u18B95.005: L&lt;&lt;1089.0,984.0&gt;--&lt;1090.0,1436.0&gt;&gt;

* u18B95.005: L&lt;&lt;1152.0,1567.0&gt;--&lt;1151.0,989.0&gt;&gt;

* u18B95.005: L&lt;&lt;948.0,1517.0&gt;--&lt;947.0,974.0&gt;&gt;

* u18B95.006: L&lt;&lt;-348.0,1567.0&gt;--&lt;-349.0,989.0&gt;&gt;

* u18B95.006: L&lt;&lt;-411.0,984.0&gt;--&lt;-410.0,1436.0&gt;&gt;

* u18B95.006: L&lt;&lt;-552.0,1517.0&gt;--&lt;-553.0,974.0&gt;&gt;

* u18B95.007: L&lt;&lt;-1348.0,1067.0&gt;--&lt;-1349.0,489.0&gt;&gt;

* u18B95.007: L&lt;&lt;-1411.0,484.0&gt;--&lt;-1410.0,936.0&gt;&gt;

* u18B95.007: L&lt;&lt;-1552.0,1017.0&gt;--&lt;-1553.0,474.0&gt;&gt;

* u18B95.008: L&lt;&lt;1089.0,484.0&gt;--&lt;1090.0,936.0&gt;&gt;

* u18B95.008: L&lt;&lt;1152.0,1067.0&gt;--&lt;1151.0,489.0&gt;&gt;

* u18B95.008: L&lt;&lt;948.0,1017.0&gt;--&lt;947.0,474.0&gt;&gt;

* u18B95.009: L&lt;&lt;-348.0,1067.0&gt;--&lt;-349.0,489.0&gt;&gt;

* u18B95.009: L&lt;&lt;-411.0,484.0&gt;--&lt;-410.0,936.0&gt;&gt;

* u18B95.009: L&lt;&lt;-552.0,1017.0&gt;--&lt;-553.0,474.0&gt;&gt;

* u18B95.010: L&lt;&lt;-1348.0,567.0&gt;--&lt;-1349.0,-11.0&gt;&gt;

* u18B95.010: L&lt;&lt;-1411.0,-16.0&gt;--&lt;-1410.0,436.0&gt;&gt;

* u18B95.010: L&lt;&lt;-1552.0,517.0&gt;--&lt;-1553.0,-26.0&gt;&gt;

* u18B95.011: L&lt;&lt;1089.0,-16.0&gt;--&lt;1090.0,436.0&gt;&gt;

* u18B95.011: L&lt;&lt;1152.0,567.0&gt;--&lt;1151.0,-11.0&gt;&gt;

* u18B95.011: L&lt;&lt;948.0,517.0&gt;--&lt;947.0,-26.0&gt;&gt;

* u18B95.012: L&lt;&lt;-348.0,567.0&gt;--&lt;-349.0,-11.0&gt;&gt;

* u18B95.012: L&lt;&lt;-411.0,-16.0&gt;--&lt;-410.0,436.0&gt;&gt;

* u18B95.012: L&lt;&lt;-552.0,517.0&gt;--&lt;-553.0,-26.0&gt;&gt;

* u18B95.013: L&lt;&lt;-1348.0,67.0&gt;--&lt;-1349.0,-511.0&gt;&gt;

* u18B95.013: L&lt;&lt;-1411.0,-516.0&gt;--&lt;-1410.0,-64.0&gt;&gt;

* u18B95.013: L&lt;&lt;-1552.0,17.0&gt;--&lt;-1553.0,-526.0&gt;&gt;

* u18B95.014: L&lt;&lt;-1052.0,17.0&gt;--&lt;-1053.0,-526.0&gt;&gt;

* u18B95.014: L&lt;&lt;-848.0,67.0&gt;--&lt;-849.0,-511.0&gt;&gt;

* u18B95.014: L&lt;&lt;-911.0,-516.0&gt;--&lt;-910.0,-64.0&gt;&gt;

* u18B95.015: L&lt;&lt;-348.0,67.0&gt;--&lt;-349.0,-511.0&gt;&gt;

* u18B95.015: L&lt;&lt;-411.0,-516.0&gt;--&lt;-410.0,-64.0&gt;&gt;

* u18B95.015: L&lt;&lt;-552.0,17.0&gt;--&lt;-553.0,-526.0&gt;&gt;

* u18B95.016: L&lt;&lt;-1348.0,-433.0&gt;--&lt;-1349.0,-1011.0&gt;&gt;

* u18B95.016: L&lt;&lt;-1411.0,-1016.0&gt;--&lt;-1410.0,-564.0&gt;&gt;

* u18B95.016: L&lt;&lt;-1552.0,-483.0&gt;--&lt;-1553.0,-1026.0&gt;&gt;

* u18B95.017: L&lt;&lt;-1052.0,-483.0&gt;--&lt;-1053.0,-1026.0&gt;&gt;

* u18B95.017: L&lt;&lt;-848.0,-433.0&gt;--&lt;-849.0,-1011.0&gt;&gt;

* u18B95.017: L&lt;&lt;-911.0,-1016.0&gt;--&lt;-910.0,-564.0&gt;&gt;

* u18B95.018: L&lt;&lt;-348.0,-433.0&gt;--&lt;-349.0,-1011.0&gt;&gt;

* u18B95.018: L&lt;&lt;-411.0,-1016.0&gt;--&lt;-410.0,-564.0&gt;&gt;

* u18B95.018: L&lt;&lt;-552.0,-483.0&gt;--&lt;-553.0,-1026.0&gt;&gt;

* u18B95.019: L&lt;&lt;-1348.0,-933.0&gt;--&lt;-1349.0,-1511.0&gt;&gt;

* u18B95.019: L&lt;&lt;-1411.0,-1516.0&gt;--&lt;-1410.0,-1064.0&gt;&gt;

* u18B95.019: L&lt;&lt;-1552.0,-983.0&gt;--&lt;-1553.0,-1526.0&gt;&gt;

* u18B95.020: L&lt;&lt;-1052.0,-983.0&gt;--&lt;-1053.0,-1526.0&gt;&gt;

* u18B95.020: L&lt;&lt;-848.0,-933.0&gt;--&lt;-849.0,-1511.0&gt;&gt;

* u18B95.020: L&lt;&lt;-911.0,-1516.0&gt;--&lt;-910.0,-1064.0&gt;&gt;

* u18B95.021: L&lt;&lt;-348.0,-933.0&gt;--&lt;-349.0,-1511.0&gt;&gt;

* u18B95.021: L&lt;&lt;-411.0,-1516.0&gt;--&lt;-410.0,-1064.0&gt;&gt;

* u18B95.021: L&lt;&lt;-552.0,-983.0&gt;--&lt;-553.0,-1526.0&gt;&gt;

* u18B95.022: L&lt;&lt;448.0,1017.0&gt;--&lt;447.0,474.0&gt;&gt;

* u18B95.022: L&lt;&lt;589.0,484.0&gt;--&lt;590.0,936.0&gt;&gt;

* u18B95.022: L&lt;&lt;652.0,1067.0&gt;--&lt;651.0,489.0&gt;&gt;

* u18B95.023: L&lt;&lt;448.0,517.0&gt;--&lt;447.0,-26.0&gt;&gt;

* u18B95.023: L&lt;&lt;589.0,-16.0&gt;--&lt;590.0,436.0&gt;&gt;

* u18B95.023: L&lt;&lt;652.0,567.0&gt;--&lt;651.0,-11.0&gt;&gt;

* u18B98 (U+18B98): L&lt;&lt;426.0,573.0&gt;--&lt;425.0,-43.0&gt;&gt;

* u18B98 (U+18B98): L&lt;&lt;568.0,-32.0&gt;--&lt;569.0,444.0&gt;&gt;

* u18B98 (U+18B98): L&lt;&lt;631.0,275.0&gt;--&lt;630.0,-27.0&gt;&gt;

* u18B98.001: L&lt;&lt;426.0,2073.0&gt;--&lt;425.0,1457.0&gt;&gt;

* u18B98.001: L&lt;&lt;568.0,1468.0&gt;--&lt;569.0,1944.0&gt;&gt;

* u18B98.001: L&lt;&lt;631.0,1775.0&gt;--&lt;630.0,1473.0&gt;&gt;

* u18B98.002: L&lt;&lt;1068.0,1468.0&gt;--&lt;1069.0,1944.0&gt;&gt;

* u18B98.002: L&lt;&lt;1131.0,1775.0&gt;--&lt;1130.0,1473.0&gt;&gt;

* u18B98.002: L&lt;&lt;926.0,2073.0&gt;--&lt;925.0,1457.0&gt;&gt;

* u18B98.003: L&lt;&lt;-369.0,1775.0&gt;--&lt;-370.0,1473.0&gt;&gt;

* u18B98.003: L&lt;&lt;-432.0,1468.0&gt;--&lt;-431.0,1944.0&gt;&gt;

* u18B98.003: L&lt;&lt;-574.0,2073.0&gt;--&lt;-575.0,1457.0&gt;&gt;

* u18B98.004: L&lt;&lt;426.0,1573.0&gt;--&lt;425.0,957.0&gt;&gt;

* u18B98.004: L&lt;&lt;568.0,968.0&gt;--&lt;569.0,1444.0&gt;&gt;

* u18B98.004: L&lt;&lt;631.0,1275.0&gt;--&lt;630.0,973.0&gt;&gt;

* u18B98.005: L&lt;&lt;1068.0,968.0&gt;--&lt;1069.0,1444.0&gt;&gt;

* u18B98.005: L&lt;&lt;1131.0,1275.0&gt;--&lt;1130.0,973.0&gt;&gt;

* u18B98.005: L&lt;&lt;926.0,1573.0&gt;--&lt;925.0,957.0&gt;&gt;

* u18B98.006: L&lt;&lt;-369.0,1275.0&gt;--&lt;-370.0,973.0&gt;&gt;

* u18B98.006: L&lt;&lt;-432.0,968.0&gt;--&lt;-431.0,1444.0&gt;&gt;

* u18B98.006: L&lt;&lt;-574.0,1573.0&gt;--&lt;-575.0,957.0&gt;&gt;

* u18B98.007: L&lt;&lt;-1369.0,775.0&gt;--&lt;-1370.0,473.0&gt;&gt;

* u18B98.007: L&lt;&lt;-1432.0,468.0&gt;--&lt;-1431.0,944.0&gt;&gt;

* u18B98.007: L&lt;&lt;-1574.0,1073.0&gt;--&lt;-1575.0,457.0&gt;&gt;

* u18B98.008: L&lt;&lt;1068.0,468.0&gt;--&lt;1069.0,944.0&gt;&gt;

* u18B98.008: L&lt;&lt;1131.0,775.0&gt;--&lt;1130.0,473.0&gt;&gt;

* u18B98.008: L&lt;&lt;926.0,1073.0&gt;--&lt;925.0,457.0&gt;&gt;

* u18B98.009: L&lt;&lt;-369.0,775.0&gt;--&lt;-370.0,473.0&gt;&gt;

* u18B98.009: L&lt;&lt;-432.0,468.0&gt;--&lt;-431.0,944.0&gt;&gt;

* u18B98.009: L&lt;&lt;-574.0,1073.0&gt;--&lt;-575.0,457.0&gt;&gt;

* u18B98.010: L&lt;&lt;-1369.0,275.0&gt;--&lt;-1370.0,-27.0&gt;&gt;

* u18B98.010: L&lt;&lt;-1432.0,-32.0&gt;--&lt;-1431.0,444.0&gt;&gt;

* u18B98.010: L&lt;&lt;-1574.0,573.0&gt;--&lt;-1575.0,-43.0&gt;&gt;

* u18B98.011: L&lt;&lt;1068.0,-32.0&gt;--&lt;1069.0,444.0&gt;&gt;

* u18B98.011: L&lt;&lt;1131.0,275.0&gt;--&lt;1130.0,-27.0&gt;&gt;

* u18B98.011: L&lt;&lt;926.0,573.0&gt;--&lt;925.0,-43.0&gt;&gt;

* u18B98.012: L&lt;&lt;-369.0,275.0&gt;--&lt;-370.0,-27.0&gt;&gt;

* u18B98.012: L&lt;&lt;-432.0,-32.0&gt;--&lt;-431.0,444.0&gt;&gt;

* u18B98.012: L&lt;&lt;-574.0,573.0&gt;--&lt;-575.0,-43.0&gt;&gt;

* u18B98.013: L&lt;&lt;-1369.0,-225.0&gt;--&lt;-1370.0,-527.0&gt;&gt;

* u18B98.013: L&lt;&lt;-1432.0,-532.0&gt;--&lt;-1431.0,-56.0&gt;&gt;

* u18B98.013: L&lt;&lt;-1574.0,73.0&gt;--&lt;-1575.0,-543.0&gt;&gt;

* u18B98.014: L&lt;&lt;-1074.0,73.0&gt;--&lt;-1075.0,-543.0&gt;&gt;

* u18B98.014: L&lt;&lt;-869.0,-225.0&gt;--&lt;-870.0,-527.0&gt;&gt;

* u18B98.014: L&lt;&lt;-932.0,-532.0&gt;--&lt;-931.0,-56.0&gt;&gt;

* u18B98.015: L&lt;&lt;-369.0,-225.0&gt;--&lt;-370.0,-527.0&gt;&gt;

* u18B98.015: L&lt;&lt;-432.0,-532.0&gt;--&lt;-431.0,-56.0&gt;&gt;

* u18B98.015: L&lt;&lt;-574.0,73.0&gt;--&lt;-575.0,-543.0&gt;&gt;

* u18B98.016: L&lt;&lt;-1369.0,-725.0&gt;--&lt;-1370.0,-1027.0&gt;&gt;

* u18B98.016: L&lt;&lt;-1432.0,-1032.0&gt;--&lt;-1431.0,-556.0&gt;&gt;

* u18B98.016: L&lt;&lt;-1574.0,-427.0&gt;--&lt;-1575.0,-1043.0&gt;&gt;

* u18B98.017: L&lt;&lt;-1074.0,-427.0&gt;--&lt;-1075.0,-1043.0&gt;&gt;

* u18B98.017: L&lt;&lt;-869.0,-725.0&gt;--&lt;-870.0,-1027.0&gt;&gt;

* u18B98.017: L&lt;&lt;-932.0,-1032.0&gt;--&lt;-931.0,-556.0&gt;&gt;

* u18B98.018: L&lt;&lt;-369.0,-725.0&gt;--&lt;-370.0,-1027.0&gt;&gt;

* u18B98.018: L&lt;&lt;-432.0,-1032.0&gt;--&lt;-431.0,-556.0&gt;&gt;

* u18B98.018: L&lt;&lt;-574.0,-427.0&gt;--&lt;-575.0,-1043.0&gt;&gt;

* u18B98.019: L&lt;&lt;-1369.0,-1225.0&gt;--&lt;-1370.0,-1527.0&gt;&gt;

* u18B98.019: L&lt;&lt;-1432.0,-1532.0&gt;--&lt;-1431.0,-1056.0&gt;&gt;

* u18B98.019: L&lt;&lt;-1574.0,-927.0&gt;--&lt;-1575.0,-1543.0&gt;&gt;

* u18B98.020: L&lt;&lt;-1074.0,-927.0&gt;--&lt;-1075.0,-1543.0&gt;&gt;

* u18B98.020: L&lt;&lt;-869.0,-1225.0&gt;--&lt;-870.0,-1527.0&gt;&gt;

* u18B98.020: L&lt;&lt;-932.0,-1532.0&gt;--&lt;-931.0,-1056.0&gt;&gt;

* u18B98.021: L&lt;&lt;-369.0,-1225.0&gt;--&lt;-370.0,-1527.0&gt;&gt;

* u18B98.021: L&lt;&lt;-432.0,-1532.0&gt;--&lt;-431.0,-1056.0&gt;&gt;

* u18B98.021: L&lt;&lt;-574.0,-927.0&gt;--&lt;-575.0,-1543.0&gt;&gt;

* u18B98.022: L&lt;&lt;426.0,1073.0&gt;--&lt;425.0,457.0&gt;&gt;

* u18B98.022: L&lt;&lt;568.0,468.0&gt;--&lt;569.0,944.0&gt;&gt;

* u18B98.022: L&lt;&lt;631.0,775.0&gt;--&lt;630.0,473.0&gt;&gt;

* u18B98.023: L&lt;&lt;426.0,573.0&gt;--&lt;425.0,-43.0&gt;&gt;

* u18B98.023: L&lt;&lt;568.0,-32.0&gt;--&lt;569.0,444.0&gt;&gt;

* u18B98.023: L&lt;&lt;631.0,275.0&gt;--&lt;630.0,-27.0&gt;&gt;

* u18B9C (U+18B9C): L&lt;&lt;467.0,-25.0&gt;--&lt;468.0,436.0&gt;&gt;

* u18B9C (U+18B9C): L&lt;&lt;530.0,567.0&gt;--&lt;529.0,-21.0&gt;&gt;

* u18B9C.001: L&lt;&lt;467.0,1475.0&gt;--&lt;468.0,1936.0&gt;&gt;

* u18B9C.001: L&lt;&lt;530.0,2067.0&gt;--&lt;529.0,1479.0&gt;&gt;

* u18B9C.002: L&lt;&lt;1030.0,2067.0&gt;--&lt;1029.0,1479.0&gt;&gt;

* u18B9C.002: L&lt;&lt;967.0,1475.0&gt;--&lt;968.0,1936.0&gt;&gt;

* u18B9C.003: L&lt;&lt;-470.0,2067.0&gt;--&lt;-471.0,1479.0&gt;&gt;

* u18B9C.003: L&lt;&lt;-533.0,1475.0&gt;--&lt;-532.0,1936.0&gt;&gt;

* u18B9C.004: L&lt;&lt;467.0,975.0&gt;--&lt;468.0,1436.0&gt;&gt;

* u18B9C.004: L&lt;&lt;530.0,1567.0&gt;--&lt;529.0,979.0&gt;&gt;

* u18B9C.005: L&lt;&lt;1030.0,1567.0&gt;--&lt;1029.0,979.0&gt;&gt;

* u18B9C.005: L&lt;&lt;967.0,975.0&gt;--&lt;968.0,1436.0&gt;&gt;

* u18B9C.006: L&lt;&lt;-470.0,1567.0&gt;--&lt;-471.0,979.0&gt;&gt;

* u18B9C.006: L&lt;&lt;-533.0,975.0&gt;--&lt;-532.0,1436.0&gt;&gt;

* u18B9C.007: L&lt;&lt;-1470.0,1067.0&gt;--&lt;-1471.0,479.0&gt;&gt;

* u18B9C.007: L&lt;&lt;-1533.0,475.0&gt;--&lt;-1532.0,936.0&gt;&gt;

* u18B9C.008: L&lt;&lt;1030.0,1067.0&gt;--&lt;1029.0,479.0&gt;&gt;

* u18B9C.008: L&lt;&lt;967.0,475.0&gt;--&lt;968.0,936.0&gt;&gt;

* u18B9C.009: L&lt;&lt;-470.0,1067.0&gt;--&lt;-471.0,479.0&gt;&gt;

* u18B9C.009: L&lt;&lt;-533.0,475.0&gt;--&lt;-532.0,936.0&gt;&gt;

* u18B9C.010: L&lt;&lt;-1470.0,567.0&gt;--&lt;-1471.0,-21.0&gt;&gt;

* u18B9C.010: L&lt;&lt;-1533.0,-25.0&gt;--&lt;-1532.0,436.0&gt;&gt;

* u18B9C.011: L&lt;&lt;1030.0,567.0&gt;--&lt;1029.0,-21.0&gt;&gt;

* u18B9C.011: L&lt;&lt;967.0,-25.0&gt;--&lt;968.0,436.0&gt;&gt;

* u18B9C.012: L&lt;&lt;-470.0,567.0&gt;--&lt;-471.0,-21.0&gt;&gt;

* u18B9C.012: L&lt;&lt;-533.0,-25.0&gt;--&lt;-532.0,436.0&gt;&gt;

* u18B9C.013: L&lt;&lt;-1470.0,67.0&gt;--&lt;-1471.0,-521.0&gt;&gt;

* u18B9C.013: L&lt;&lt;-1533.0,-525.0&gt;--&lt;-1532.0,-64.0&gt;&gt;

* u18B9C.014: L&lt;&lt;-1033.0,-525.0&gt;--&lt;-1032.0,-64.0&gt;&gt;

* u18B9C.014: L&lt;&lt;-970.0,67.0&gt;--&lt;-971.0,-521.0&gt;&gt;

* u18B9C.015: L&lt;&lt;-470.0,67.0&gt;--&lt;-471.0,-521.0&gt;&gt;

* u18B9C.015: L&lt;&lt;-533.0,-525.0&gt;--&lt;-532.0,-64.0&gt;&gt;

* u18B9C.016: L&lt;&lt;-1470.0,-433.0&gt;--&lt;-1471.0,-1021.0&gt;&gt;

* u18B9C.016: L&lt;&lt;-1533.0,-1025.0&gt;--&lt;-1532.0,-564.0&gt;&gt;

* u18B9C.017: L&lt;&lt;-1033.0,-1025.0&gt;--&lt;-1032.0,-564.0&gt;&gt;

* u18B9C.017: L&lt;&lt;-970.0,-433.0&gt;--&lt;-971.0,-1021.0&gt;&gt;

* u18B9C.018: L&lt;&lt;-470.0,-433.0&gt;--&lt;-471.0,-1021.0&gt;&gt;

* u18B9C.018: L&lt;&lt;-533.0,-1025.0&gt;--&lt;-532.0,-564.0&gt;&gt;

* u18B9C.019: L&lt;&lt;-1470.0,-933.0&gt;--&lt;-1471.0,-1521.0&gt;&gt;

* u18B9C.019: L&lt;&lt;-1533.0,-1525.0&gt;--&lt;-1532.0,-1064.0&gt;&gt;

* u18B9C.020: L&lt;&lt;-1033.0,-1525.0&gt;--&lt;-1032.0,-1064.0&gt;&gt;

* u18B9C.020: L&lt;&lt;-970.0,-933.0&gt;--&lt;-971.0,-1521.0&gt;&gt;

* u18B9C.021: L&lt;&lt;-470.0,-933.0&gt;--&lt;-471.0,-1521.0&gt;&gt;

* u18B9C.021: L&lt;&lt;-533.0,-1525.0&gt;--&lt;-532.0,-1064.0&gt;&gt;

* u18B9C.022: L&lt;&lt;467.0,475.0&gt;--&lt;468.0,936.0&gt;&gt;

* u18B9C.022: L&lt;&lt;530.0,1067.0&gt;--&lt;529.0,479.0&gt;&gt;

* u18B9C.023: L&lt;&lt;467.0,-25.0&gt;--&lt;468.0,436.0&gt;&gt;

* u18B9C.023: L&lt;&lt;530.0,567.0&gt;--&lt;529.0,-21.0&gt;&gt;

* u18B9D (U+18B9D): L&lt;&lt;477.0,-14.0&gt;--&lt;478.0,439.0&gt;&gt;

* u18B9D (U+18B9D): L&lt;&lt;540.0,569.0&gt;--&lt;539.0,-9.0&gt;&gt;

* u18B9D.001: L&lt;&lt;477.0,1486.0&gt;--&lt;478.0,1939.0&gt;&gt;

* u18B9D.001: L&lt;&lt;540.0,2069.0&gt;--&lt;539.0,1491.0&gt;&gt;

* u18B9D.002: L&lt;&lt;1040.0,2069.0&gt;--&lt;1039.0,1491.0&gt;&gt;

* u18B9D.002: L&lt;&lt;977.0,1486.0&gt;--&lt;978.0,1939.0&gt;&gt;

* u18B9D.003: L&lt;&lt;-460.0,2069.0&gt;--&lt;-461.0,1491.0&gt;&gt;

* u18B9D.003: L&lt;&lt;-523.0,1486.0&gt;--&lt;-522.0,1939.0&gt;&gt;

* u18B9D.004: L&lt;&lt;477.0,986.0&gt;--&lt;478.0,1439.0&gt;&gt;

* u18B9D.004: L&lt;&lt;540.0,1569.0&gt;--&lt;539.0,991.0&gt;&gt;

* u18B9D.005: L&lt;&lt;1040.0,1569.0&gt;--&lt;1039.0,991.0&gt;&gt;

* u18B9D.005: L&lt;&lt;977.0,986.0&gt;--&lt;978.0,1439.0&gt;&gt;

* u18B9D.006: L&lt;&lt;-460.0,1569.0&gt;--&lt;-461.0,991.0&gt;&gt;

* u18B9D.006: L&lt;&lt;-523.0,986.0&gt;--&lt;-522.0,1439.0&gt;&gt;

* u18B9D.007: L&lt;&lt;-1460.0,1069.0&gt;--&lt;-1461.0,491.0&gt;&gt;

* u18B9D.007: L&lt;&lt;-1523.0,486.0&gt;--&lt;-1522.0,939.0&gt;&gt;

* u18B9D.008: L&lt;&lt;1040.0,1069.0&gt;--&lt;1039.0,491.0&gt;&gt;

* u18B9D.008: L&lt;&lt;977.0,486.0&gt;--&lt;978.0,939.0&gt;&gt;

* u18B9D.009: L&lt;&lt;-460.0,1069.0&gt;--&lt;-461.0,491.0&gt;&gt;

* u18B9D.009: L&lt;&lt;-523.0,486.0&gt;--&lt;-522.0,939.0&gt;&gt;

* u18B9D.010: L&lt;&lt;-1460.0,569.0&gt;--&lt;-1461.0,-9.0&gt;&gt;

* u18B9D.010: L&lt;&lt;-1523.0,-14.0&gt;--&lt;-1522.0,439.0&gt;&gt;

* u18B9D.011: L&lt;&lt;1040.0,569.0&gt;--&lt;1039.0,-9.0&gt;&gt;

* u18B9D.011: L&lt;&lt;977.0,-14.0&gt;--&lt;978.0,439.0&gt;&gt;

* u18B9D.012: L&lt;&lt;-460.0,569.0&gt;--&lt;-461.0,-9.0&gt;&gt;

* u18B9D.012: L&lt;&lt;-523.0,-14.0&gt;--&lt;-522.0,439.0&gt;&gt;

* u18B9D.013: L&lt;&lt;-1460.0,69.0&gt;--&lt;-1461.0,-509.0&gt;&gt;

* u18B9D.013: L&lt;&lt;-1523.0,-514.0&gt;--&lt;-1522.0,-61.0&gt;&gt;

* u18B9D.014: L&lt;&lt;-1023.0,-514.0&gt;--&lt;-1022.0,-61.0&gt;&gt;

* u18B9D.014: L&lt;&lt;-960.0,69.0&gt;--&lt;-961.0,-509.0&gt;&gt;

* u18B9D.015: L&lt;&lt;-460.0,69.0&gt;--&lt;-461.0,-509.0&gt;&gt;

* u18B9D.015: L&lt;&lt;-523.0,-514.0&gt;--&lt;-522.0,-61.0&gt;&gt;

* u18B9D.016: L&lt;&lt;-1460.0,-431.0&gt;--&lt;-1461.0,-1009.0&gt;&gt;

* u18B9D.016: L&lt;&lt;-1523.0,-1014.0&gt;--&lt;-1522.0,-561.0&gt;&gt;

* u18B9D.017: L&lt;&lt;-1023.0,-1014.0&gt;--&lt;-1022.0,-561.0&gt;&gt;

* u18B9D.017: L&lt;&lt;-960.0,-431.0&gt;--&lt;-961.0,-1009.0&gt;&gt;

* u18B9D.018: L&lt;&lt;-460.0,-431.0&gt;--&lt;-461.0,-1009.0&gt;&gt;

* u18B9D.018: L&lt;&lt;-523.0,-1014.0&gt;--&lt;-522.0,-561.0&gt;&gt;

* u18B9D.019: L&lt;&lt;-1460.0,-931.0&gt;--&lt;-1461.0,-1509.0&gt;&gt;

* u18B9D.019: L&lt;&lt;-1523.0,-1514.0&gt;--&lt;-1522.0,-1061.0&gt;&gt;

* u18B9D.020: L&lt;&lt;-1023.0,-1514.0&gt;--&lt;-1022.0,-1061.0&gt;&gt;

* u18B9D.020: L&lt;&lt;-960.0,-931.0&gt;--&lt;-961.0,-1509.0&gt;&gt;

* u18B9D.021: L&lt;&lt;-460.0,-931.0&gt;--&lt;-461.0,-1509.0&gt;&gt;

* u18B9D.021: L&lt;&lt;-523.0,-1514.0&gt;--&lt;-522.0,-1061.0&gt;&gt;

* u18B9D.022: L&lt;&lt;477.0,486.0&gt;--&lt;478.0,939.0&gt;&gt;

* u18B9D.022: L&lt;&lt;540.0,1069.0&gt;--&lt;539.0,491.0&gt;&gt;

* u18B9D.023: L&lt;&lt;477.0,-14.0&gt;--&lt;478.0,439.0&gt;&gt;

* u18B9D.023: L&lt;&lt;540.0,569.0&gt;--&lt;539.0,-9.0&gt;&gt;

* u18B9E (U+18B9E): L&lt;&lt;477.0,-13.0&gt;--&lt;478.0,439.0&gt;&gt;

* u18B9E (U+18B9E): L&lt;&lt;540.0,569.0&gt;--&lt;539.0,-8.0&gt;&gt;

* u18B9E.001: L&lt;&lt;477.0,1487.0&gt;--&lt;478.0,1939.0&gt;&gt;

* u18B9E.001: L&lt;&lt;540.0,2069.0&gt;--&lt;539.0,1492.0&gt;&gt;

* u18B9E.002: L&lt;&lt;1040.0,2069.0&gt;--&lt;1039.0,1492.0&gt;&gt;

* u18B9E.002: L&lt;&lt;977.0,1487.0&gt;--&lt;978.0,1939.0&gt;&gt;

* u18B9E.003: L&lt;&lt;-460.0,2069.0&gt;--&lt;-461.0,1492.0&gt;&gt;

* u18B9E.003: L&lt;&lt;-523.0,1487.0&gt;--&lt;-522.0,1939.0&gt;&gt;

* u18B9E.004: L&lt;&lt;477.0,987.0&gt;--&lt;478.0,1439.0&gt;&gt;

* u18B9E.004: L&lt;&lt;540.0,1569.0&gt;--&lt;539.0,992.0&gt;&gt;

* u18B9E.005: L&lt;&lt;1040.0,1569.0&gt;--&lt;1039.0,992.0&gt;&gt;

* u18B9E.005: L&lt;&lt;977.0,987.0&gt;--&lt;978.0,1439.0&gt;&gt;

* u18B9E.006: L&lt;&lt;-460.0,1569.0&gt;--&lt;-461.0,992.0&gt;&gt;

* u18B9E.006: L&lt;&lt;-523.0,987.0&gt;--&lt;-522.0,1439.0&gt;&gt;

* u18B9E.007: L&lt;&lt;-1460.0,1069.0&gt;--&lt;-1461.0,492.0&gt;&gt;

* u18B9E.007: L&lt;&lt;-1523.0,487.0&gt;--&lt;-1522.0,939.0&gt;&gt;

* u18B9E.008: L&lt;&lt;1040.0,1069.0&gt;--&lt;1039.0,492.0&gt;&gt;

* u18B9E.008: L&lt;&lt;977.0,487.0&gt;--&lt;978.0,939.0&gt;&gt;

* u18B9E.009: L&lt;&lt;-460.0,1069.0&gt;--&lt;-461.0,492.0&gt;&gt;

* u18B9E.009: L&lt;&lt;-523.0,487.0&gt;--&lt;-522.0,939.0&gt;&gt;

* u18B9E.010: L&lt;&lt;-1460.0,569.0&gt;--&lt;-1461.0,-8.0&gt;&gt;

* u18B9E.010: L&lt;&lt;-1523.0,-13.0&gt;--&lt;-1522.0,439.0&gt;&gt;

* u18B9E.011: L&lt;&lt;1040.0,569.0&gt;--&lt;1039.0,-8.0&gt;&gt;

* u18B9E.011: L&lt;&lt;977.0,-13.0&gt;--&lt;978.0,439.0&gt;&gt;

* u18B9E.012: L&lt;&lt;-460.0,569.0&gt;--&lt;-461.0,-8.0&gt;&gt;

* u18B9E.012: L&lt;&lt;-523.0,-13.0&gt;--&lt;-522.0,439.0&gt;&gt;

* u18B9E.013: L&lt;&lt;-1460.0,69.0&gt;--&lt;-1461.0,-508.0&gt;&gt;

* u18B9E.013: L&lt;&lt;-1523.0,-513.0&gt;--&lt;-1522.0,-61.0&gt;&gt;

* u18B9E.014: L&lt;&lt;-1023.0,-513.0&gt;--&lt;-1022.0,-61.0&gt;&gt;

* u18B9E.014: L&lt;&lt;-960.0,69.0&gt;--&lt;-961.0,-508.0&gt;&gt;

* u18B9E.015: L&lt;&lt;-460.0,69.0&gt;--&lt;-461.0,-508.0&gt;&gt;

* u18B9E.015: L&lt;&lt;-523.0,-513.0&gt;--&lt;-522.0,-61.0&gt;&gt;

* u18B9E.016: L&lt;&lt;-1460.0,-431.0&gt;--&lt;-1461.0,-1008.0&gt;&gt;

* u18B9E.016: L&lt;&lt;-1523.0,-1013.0&gt;--&lt;-1522.0,-561.0&gt;&gt;

* u18B9E.017: L&lt;&lt;-1023.0,-1013.0&gt;--&lt;-1022.0,-561.0&gt;&gt;

* u18B9E.017: L&lt;&lt;-960.0,-431.0&gt;--&lt;-961.0,-1008.0&gt;&gt;

* u18B9E.018: L&lt;&lt;-460.0,-431.0&gt;--&lt;-461.0,-1008.0&gt;&gt;

* u18B9E.018: L&lt;&lt;-523.0,-1013.0&gt;--&lt;-522.0,-561.0&gt;&gt;

* u18B9E.019: L&lt;&lt;-1460.0,-931.0&gt;--&lt;-1461.0,-1508.0&gt;&gt;

* u18B9E.019: L&lt;&lt;-1523.0,-1513.0&gt;--&lt;-1522.0,-1061.0&gt;&gt;

* u18B9E.020: L&lt;&lt;-1023.0,-1513.0&gt;--&lt;-1022.0,-1061.0&gt;&gt;

* u18B9E.020: L&lt;&lt;-960.0,-931.0&gt;--&lt;-961.0,-1508.0&gt;&gt;

* u18B9E.021: L&lt;&lt;-460.0,-931.0&gt;--&lt;-461.0,-1508.0&gt;&gt;

* u18B9E.021: L&lt;&lt;-523.0,-1513.0&gt;--&lt;-522.0,-1061.0&gt;&gt;

* u18B9E.022: L&lt;&lt;477.0,487.0&gt;--&lt;478.0,939.0&gt;&gt;

* u18B9E.022: L&lt;&lt;540.0,1069.0&gt;--&lt;539.0,492.0&gt;&gt;

* u18B9E.023: L&lt;&lt;477.0,-13.0&gt;--&lt;478.0,439.0&gt;&gt;

* u18B9E.023: L&lt;&lt;540.0,569.0&gt;--&lt;539.0,-8.0&gt;&gt;

* u18B9F (U+18B9F): L&lt;&lt;493.0,-24.0&gt;--&lt;494.0,383.0&gt;&gt;

* u18B9F (U+18B9F): L&lt;&lt;556.0,387.0&gt;--&lt;555.0,-19.0&gt;&gt;

* u18B9F.001: L&lt;&lt;493.0,1476.0&gt;--&lt;494.0,1883.0&gt;&gt;

* u18B9F.001: L&lt;&lt;556.0,1887.0&gt;--&lt;555.0,1481.0&gt;&gt;

* u18B9F.002: L&lt;&lt;1056.0,1887.0&gt;--&lt;1055.0,1481.0&gt;&gt;

* u18B9F.002: L&lt;&lt;993.0,1476.0&gt;--&lt;994.0,1883.0&gt;&gt;

* u18B9F.003: L&lt;&lt;-444.0,1887.0&gt;--&lt;-445.0,1481.0&gt;&gt;

* u18B9F.003: L&lt;&lt;-507.0,1476.0&gt;--&lt;-506.0,1883.0&gt;&gt;

* u18B9F.004: L&lt;&lt;493.0,976.0&gt;--&lt;494.0,1383.0&gt;&gt;

* u18B9F.004: L&lt;&lt;556.0,1387.0&gt;--&lt;555.0,981.0&gt;&gt;

* u18B9F.005: L&lt;&lt;1056.0,1387.0&gt;--&lt;1055.0,981.0&gt;&gt;

* u18B9F.005: L&lt;&lt;993.0,976.0&gt;--&lt;994.0,1383.0&gt;&gt;

* u18B9F.006: L&lt;&lt;-444.0,1387.0&gt;--&lt;-445.0,981.0&gt;&gt;

* u18B9F.006: L&lt;&lt;-507.0,976.0&gt;--&lt;-506.0,1383.0&gt;&gt;

* u18B9F.007: L&lt;&lt;-1444.0,887.0&gt;--&lt;-1445.0,481.0&gt;&gt;

* u18B9F.007: L&lt;&lt;-1507.0,476.0&gt;--&lt;-1506.0,883.0&gt;&gt;

* u18B9F.008: L&lt;&lt;1056.0,887.0&gt;--&lt;1055.0,481.0&gt;&gt;

* u18B9F.008: L&lt;&lt;993.0,476.0&gt;--&lt;994.0,883.0&gt;&gt;

* u18B9F.009: L&lt;&lt;-444.0,887.0&gt;--&lt;-445.0,481.0&gt;&gt;

* u18B9F.009: L&lt;&lt;-507.0,476.0&gt;--&lt;-506.0,883.0&gt;&gt;

* u18B9F.010: L&lt;&lt;-1444.0,387.0&gt;--&lt;-1445.0,-19.0&gt;&gt;

* u18B9F.010: L&lt;&lt;-1507.0,-24.0&gt;--&lt;-1506.0,383.0&gt;&gt;

* u18B9F.011: L&lt;&lt;1056.0,387.0&gt;--&lt;1055.0,-19.0&gt;&gt;

* u18B9F.011: L&lt;&lt;993.0,-24.0&gt;--&lt;994.0,383.0&gt;&gt;

* u18B9F.012: L&lt;&lt;-444.0,387.0&gt;--&lt;-445.0,-19.0&gt;&gt;

* u18B9F.012: L&lt;&lt;-507.0,-24.0&gt;--&lt;-506.0,383.0&gt;&gt;

* u18B9F.013: L&lt;&lt;-1444.0,-113.0&gt;--&lt;-1445.0,-519.0&gt;&gt;

* u18B9F.013: L&lt;&lt;-1507.0,-524.0&gt;--&lt;-1506.0,-117.0&gt;&gt;

* u18B9F.014: L&lt;&lt;-1007.0,-524.0&gt;--&lt;-1006.0,-117.0&gt;&gt;

* u18B9F.014: L&lt;&lt;-944.0,-113.0&gt;--&lt;-945.0,-519.0&gt;&gt;

* u18B9F.015: L&lt;&lt;-444.0,-113.0&gt;--&lt;-445.0,-519.0&gt;&gt;

* u18B9F.015: L&lt;&lt;-507.0,-524.0&gt;--&lt;-506.0,-117.0&gt;&gt;

* u18B9F.016: L&lt;&lt;-1444.0,-613.0&gt;--&lt;-1445.0,-1019.0&gt;&gt;

* u18B9F.016: L&lt;&lt;-1507.0,-1024.0&gt;--&lt;-1506.0,-617.0&gt;&gt;

* u18B9F.017: L&lt;&lt;-1007.0,-1024.0&gt;--&lt;-1006.0,-617.0&gt;&gt;

* u18B9F.017: L&lt;&lt;-944.0,-613.0&gt;--&lt;-945.0,-1019.0&gt;&gt;

* u18B9F.018: L&lt;&lt;-444.0,-613.0&gt;--&lt;-445.0,-1019.0&gt;&gt;

* u18B9F.018: L&lt;&lt;-507.0,-1024.0&gt;--&lt;-506.0,-617.0&gt;&gt;

* u18B9F.019: L&lt;&lt;-1444.0,-1113.0&gt;--&lt;-1445.0,-1519.0&gt;&gt;

* u18B9F.019: L&lt;&lt;-1507.0,-1524.0&gt;--&lt;-1506.0,-1117.0&gt;&gt;

* u18B9F.020: L&lt;&lt;-1007.0,-1524.0&gt;--&lt;-1006.0,-1117.0&gt;&gt;

* u18B9F.020: L&lt;&lt;-944.0,-1113.0&gt;--&lt;-945.0,-1519.0&gt;&gt;

* u18B9F.021: L&lt;&lt;-444.0,-1113.0&gt;--&lt;-445.0,-1519.0&gt;&gt;

* u18B9F.021: L&lt;&lt;-507.0,-1524.0&gt;--&lt;-506.0,-1117.0&gt;&gt;

* u18B9F.022: L&lt;&lt;493.0,476.0&gt;--&lt;494.0,883.0&gt;&gt;

* u18B9F.022: L&lt;&lt;556.0,887.0&gt;--&lt;555.0,481.0&gt;&gt;

* u18B9F.023: L&lt;&lt;493.0,-24.0&gt;--&lt;494.0,383.0&gt;&gt;

* u18B9F.023: L&lt;&lt;556.0,387.0&gt;--&lt;555.0,-19.0&gt;&gt;

* u18BA2 (U+18BA2): L&lt;&lt;469.0,-51.0&gt;--&lt;470.0,292.0&gt;&gt;

* u18BA2 (U+18BA2): L&lt;&lt;532.0,296.0&gt;--&lt;531.0,-46.0&gt;&gt;

* u18BA2.001: L&lt;&lt;469.0,1449.0&gt;--&lt;470.0,1792.0&gt;&gt;

* u18BA2.001: L&lt;&lt;532.0,1796.0&gt;--&lt;531.0,1454.0&gt;&gt;

* u18BA2.002: L&lt;&lt;1032.0,1796.0&gt;--&lt;1031.0,1454.0&gt;&gt;

* u18BA2.002: L&lt;&lt;969.0,1449.0&gt;--&lt;970.0,1792.0&gt;&gt;

* u18BA2.003: L&lt;&lt;-468.0,1796.0&gt;--&lt;-469.0,1454.0&gt;&gt;

* u18BA2.003: L&lt;&lt;-531.0,1449.0&gt;--&lt;-530.0,1792.0&gt;&gt;

* u18BA2.004: L&lt;&lt;469.0,949.0&gt;--&lt;470.0,1292.0&gt;&gt;

* u18BA2.004: L&lt;&lt;532.0,1296.0&gt;--&lt;531.0,954.0&gt;&gt;

* u18BA2.005: L&lt;&lt;1032.0,1296.0&gt;--&lt;1031.0,954.0&gt;&gt;

* u18BA2.005: L&lt;&lt;969.0,949.0&gt;--&lt;970.0,1292.0&gt;&gt;

* u18BA2.006: L&lt;&lt;-468.0,1296.0&gt;--&lt;-469.0,954.0&gt;&gt;

* u18BA2.006: L&lt;&lt;-531.0,949.0&gt;--&lt;-530.0,1292.0&gt;&gt;

* u18BA2.007: L&lt;&lt;-1468.0,796.0&gt;--&lt;-1469.0,454.0&gt;&gt;

* u18BA2.007: L&lt;&lt;-1531.0,449.0&gt;--&lt;-1530.0,792.0&gt;&gt;

* u18BA2.008: L&lt;&lt;1032.0,796.0&gt;--&lt;1031.0,454.0&gt;&gt;

* u18BA2.008: L&lt;&lt;969.0,449.0&gt;--&lt;970.0,792.0&gt;&gt;

* u18BA2.009: L&lt;&lt;-468.0,796.0&gt;--&lt;-469.0,454.0&gt;&gt;

* u18BA2.009: L&lt;&lt;-531.0,449.0&gt;--&lt;-530.0,792.0&gt;&gt;

* u18BA2.010: L&lt;&lt;-1468.0,296.0&gt;--&lt;-1469.0,-46.0&gt;&gt;

* u18BA2.010: L&lt;&lt;-1531.0,-51.0&gt;--&lt;-1530.0,292.0&gt;&gt;

* u18BA2.011: L&lt;&lt;1032.0,296.0&gt;--&lt;1031.0,-46.0&gt;&gt;

* u18BA2.011: L&lt;&lt;969.0,-51.0&gt;--&lt;970.0,292.0&gt;&gt;

* u18BA2.012: L&lt;&lt;-468.0,296.0&gt;--&lt;-469.0,-46.0&gt;&gt;

* u18BA2.012: L&lt;&lt;-531.0,-51.0&gt;--&lt;-530.0,292.0&gt;&gt;

* u18BA2.013: L&lt;&lt;-1468.0,-204.0&gt;--&lt;-1469.0,-546.0&gt;&gt;

* u18BA2.013: L&lt;&lt;-1531.0,-551.0&gt;--&lt;-1530.0,-208.0&gt;&gt;

* u18BA2.014: L&lt;&lt;-1031.0,-551.0&gt;--&lt;-1030.0,-208.0&gt;&gt;

* u18BA2.014: L&lt;&lt;-968.0,-204.0&gt;--&lt;-969.0,-546.0&gt;&gt;

* u18BA2.015: L&lt;&lt;-468.0,-204.0&gt;--&lt;-469.0,-546.0&gt;&gt;

* u18BA2.015: L&lt;&lt;-531.0,-551.0&gt;--&lt;-530.0,-208.0&gt;&gt;

* u18BA2.016: L&lt;&lt;-1468.0,-704.0&gt;--&lt;-1469.0,-1046.0&gt;&gt;

* u18BA2.016: L&lt;&lt;-1531.0,-1051.0&gt;--&lt;-1530.0,-708.0&gt;&gt;

* u18BA2.017: L&lt;&lt;-1031.0,-1051.0&gt;--&lt;-1030.0,-708.0&gt;&gt;

* u18BA2.017: L&lt;&lt;-968.0,-704.0&gt;--&lt;-969.0,-1046.0&gt;&gt;

* u18BA2.018: L&lt;&lt;-468.0,-704.0&gt;--&lt;-469.0,-1046.0&gt;&gt;

* u18BA2.018: L&lt;&lt;-531.0,-1051.0&gt;--&lt;-530.0,-708.0&gt;&gt;

* u18BA2.019: L&lt;&lt;-1468.0,-1204.0&gt;--&lt;-1469.0,-1546.0&gt;&gt;

* u18BA2.019: L&lt;&lt;-1531.0,-1551.0&gt;--&lt;-1530.0,-1208.0&gt;&gt;

* u18BA2.020: L&lt;&lt;-1031.0,-1551.0&gt;--&lt;-1030.0,-1208.0&gt;&gt;

* u18BA2.020: L&lt;&lt;-968.0,-1204.0&gt;--&lt;-969.0,-1546.0&gt;&gt;

* u18BA2.021: L&lt;&lt;-468.0,-1204.0&gt;--&lt;-469.0,-1546.0&gt;&gt;

* u18BA2.021: L&lt;&lt;-531.0,-1551.0&gt;--&lt;-530.0,-1208.0&gt;&gt;

* u18BA2.022: L&lt;&lt;469.0,449.0&gt;--&lt;470.0,792.0&gt;&gt;

* u18BA2.022: L&lt;&lt;532.0,796.0&gt;--&lt;531.0,454.0&gt;&gt;

* u18BA2.023: L&lt;&lt;469.0,-51.0&gt;--&lt;470.0,292.0&gt;&gt;

* u18BA2.023: L&lt;&lt;532.0,296.0&gt;--&lt;531.0,-46.0&gt;&gt;

* u18BA7 (U+18BA7): L&lt;&lt;467.0,-25.0&gt;--&lt;468.0,436.0&gt;&gt;

* u18BA7 (U+18BA7): L&lt;&lt;530.0,567.0&gt;--&lt;529.0,177.0&gt;&gt;

* u18BA7.001: L&lt;&lt;467.0,1475.0&gt;--&lt;468.0,1936.0&gt;&gt;

* u18BA7.001: L&lt;&lt;530.0,2067.0&gt;--&lt;529.0,1677.0&gt;&gt;

* u18BA7.002: L&lt;&lt;1030.0,2067.0&gt;--&lt;1029.0,1677.0&gt;&gt;

* u18BA7.002: L&lt;&lt;967.0,1475.0&gt;--&lt;968.0,1936.0&gt;&gt;

* u18BA7.003: L&lt;&lt;-470.0,2067.0&gt;--&lt;-471.0,1677.0&gt;&gt;

* u18BA7.003: L&lt;&lt;-533.0,1475.0&gt;--&lt;-532.0,1936.0&gt;&gt;

* u18BA7.004: L&lt;&lt;467.0,975.0&gt;--&lt;468.0,1436.0&gt;&gt;

* u18BA7.004: L&lt;&lt;530.0,1567.0&gt;--&lt;529.0,1177.0&gt;&gt;

* u18BA7.005: L&lt;&lt;1030.0,1567.0&gt;--&lt;1029.0,1177.0&gt;&gt;

* u18BA7.005: L&lt;&lt;967.0,975.0&gt;--&lt;968.0,1436.0&gt;&gt;

* u18BA7.006: L&lt;&lt;-470.0,1567.0&gt;--&lt;-471.0,1177.0&gt;&gt;

* u18BA7.006: L&lt;&lt;-533.0,975.0&gt;--&lt;-532.0,1436.0&gt;&gt;

* u18BA7.007: L&lt;&lt;-1470.0,1067.0&gt;--&lt;-1471.0,677.0&gt;&gt;

* u18BA7.007: L&lt;&lt;-1533.0,475.0&gt;--&lt;-1532.0,936.0&gt;&gt;

* u18BA7.008: L&lt;&lt;1030.0,1067.0&gt;--&lt;1029.0,677.0&gt;&gt;

* u18BA7.008: L&lt;&lt;967.0,475.0&gt;--&lt;968.0,936.0&gt;&gt;

* u18BA7.009: L&lt;&lt;-470.0,1067.0&gt;--&lt;-471.0,677.0&gt;&gt;

* u18BA7.009: L&lt;&lt;-533.0,475.0&gt;--&lt;-532.0,936.0&gt;&gt;

* u18BA7.010: L&lt;&lt;-1470.0,567.0&gt;--&lt;-1471.0,177.0&gt;&gt;

* u18BA7.010: L&lt;&lt;-1533.0,-25.0&gt;--&lt;-1532.0,436.0&gt;&gt;

* u18BA7.011: L&lt;&lt;1030.0,567.0&gt;--&lt;1029.0,177.0&gt;&gt;

* u18BA7.011: L&lt;&lt;967.0,-25.0&gt;--&lt;968.0,436.0&gt;&gt;

* u18BA7.012: L&lt;&lt;-470.0,567.0&gt;--&lt;-471.0,177.0&gt;&gt;

* u18BA7.012: L&lt;&lt;-533.0,-25.0&gt;--&lt;-532.0,436.0&gt;&gt;

* u18BA7.013: L&lt;&lt;-1470.0,67.0&gt;--&lt;-1471.0,-323.0&gt;&gt;

* u18BA7.013: L&lt;&lt;-1533.0,-525.0&gt;--&lt;-1532.0,-64.0&gt;&gt;

* u18BA7.014: L&lt;&lt;-1033.0,-525.0&gt;--&lt;-1032.0,-64.0&gt;&gt;

* u18BA7.014: L&lt;&lt;-970.0,67.0&gt;--&lt;-971.0,-323.0&gt;&gt;

* u18BA7.015: L&lt;&lt;-470.0,67.0&gt;--&lt;-471.0,-323.0&gt;&gt;

* u18BA7.015: L&lt;&lt;-533.0,-525.0&gt;--&lt;-532.0,-64.0&gt;&gt;

* u18BA7.016: L&lt;&lt;-1470.0,-433.0&gt;--&lt;-1471.0,-823.0&gt;&gt;

* u18BA7.016: L&lt;&lt;-1533.0,-1025.0&gt;--&lt;-1532.0,-564.0&gt;&gt;

* u18BA7.017: L&lt;&lt;-1033.0,-1025.0&gt;--&lt;-1032.0,-564.0&gt;&gt;

* u18BA7.017: L&lt;&lt;-970.0,-433.0&gt;--&lt;-971.0,-823.0&gt;&gt;

* u18BA7.018: L&lt;&lt;-470.0,-433.0&gt;--&lt;-471.0,-823.0&gt;&gt;

* u18BA7.018: L&lt;&lt;-533.0,-1025.0&gt;--&lt;-532.0,-564.0&gt;&gt;

* u18BA7.019: L&lt;&lt;-1470.0,-933.0&gt;--&lt;-1471.0,-1323.0&gt;&gt;

* u18BA7.019: L&lt;&lt;-1533.0,-1525.0&gt;--&lt;-1532.0,-1064.0&gt;&gt;

* u18BA7.020: L&lt;&lt;-1033.0,-1525.0&gt;--&lt;-1032.0,-1064.0&gt;&gt;

* u18BA7.020: L&lt;&lt;-970.0,-933.0&gt;--&lt;-971.0,-1323.0&gt;&gt;

* u18BA7.021: L&lt;&lt;-470.0,-933.0&gt;--&lt;-471.0,-1323.0&gt;&gt;

* u18BA7.021: L&lt;&lt;-533.0,-1525.0&gt;--&lt;-532.0,-1064.0&gt;&gt;

* u18BA7.022: L&lt;&lt;467.0,475.0&gt;--&lt;468.0,936.0&gt;&gt;

* u18BA7.022: L&lt;&lt;530.0,1067.0&gt;--&lt;529.0,677.0&gt;&gt;

* u18BA7.023: L&lt;&lt;467.0,-25.0&gt;--&lt;468.0,436.0&gt;&gt;

* u18BA7.023: L&lt;&lt;530.0,567.0&gt;--&lt;529.0,177.0&gt;&gt;

* u18BA8 (U+18BA8): L&lt;&lt;459.0,20.0&gt;--&lt;460.0,450.0&gt;&gt;

* u18BA8 (U+18BA8): L&lt;&lt;522.0,572.0&gt;--&lt;521.0,206.0&gt;&gt;

* u18BA8.001: L&lt;&lt;459.0,1520.0&gt;--&lt;460.0,1950.0&gt;&gt;

* u18BA8.001: L&lt;&lt;522.0,2072.0&gt;--&lt;521.0,1706.0&gt;&gt;

* u18BA8.002: L&lt;&lt;1022.0,2072.0&gt;--&lt;1021.0,1706.0&gt;&gt;

* u18BA8.002: L&lt;&lt;959.0,1520.0&gt;--&lt;960.0,1950.0&gt;&gt;

* u18BA8.003: L&lt;&lt;-478.0,2072.0&gt;--&lt;-479.0,1706.0&gt;&gt;

* u18BA8.003: L&lt;&lt;-541.0,1520.0&gt;--&lt;-540.0,1950.0&gt;&gt;

* u18BA8.004: L&lt;&lt;459.0,1020.0&gt;--&lt;460.0,1450.0&gt;&gt;

* u18BA8.004: L&lt;&lt;522.0,1572.0&gt;--&lt;521.0,1206.0&gt;&gt;

* u18BA8.005: L&lt;&lt;1022.0,1572.0&gt;--&lt;1021.0,1206.0&gt;&gt;

* u18BA8.005: L&lt;&lt;959.0,1020.0&gt;--&lt;960.0,1450.0&gt;&gt;

* u18BA8.006: L&lt;&lt;-478.0,1572.0&gt;--&lt;-479.0,1206.0&gt;&gt;

* u18BA8.006: L&lt;&lt;-541.0,1020.0&gt;--&lt;-540.0,1450.0&gt;&gt;

* u18BA8.007: L&lt;&lt;-1478.0,1072.0&gt;--&lt;-1479.0,706.0&gt;&gt;

* u18BA8.007: L&lt;&lt;-1541.0,520.0&gt;--&lt;-1540.0,950.0&gt;&gt;

* u18BA8.008: L&lt;&lt;1022.0,1072.0&gt;--&lt;1021.0,706.0&gt;&gt;

* u18BA8.008: L&lt;&lt;959.0,520.0&gt;--&lt;960.0,950.0&gt;&gt;

* u18BA8.009: L&lt;&lt;-478.0,1072.0&gt;--&lt;-479.0,706.0&gt;&gt;

* u18BA8.009: L&lt;&lt;-541.0,520.0&gt;--&lt;-540.0,950.0&gt;&gt;

* u18BA8.010: L&lt;&lt;-1478.0,572.0&gt;--&lt;-1479.0,206.0&gt;&gt;

* u18BA8.010: L&lt;&lt;-1541.0,20.0&gt;--&lt;-1540.0,450.0&gt;&gt;

* u18BA8.011: L&lt;&lt;1022.0,572.0&gt;--&lt;1021.0,206.0&gt;&gt;

* u18BA8.011: L&lt;&lt;959.0,20.0&gt;--&lt;960.0,450.0&gt;&gt;

* u18BA8.012: L&lt;&lt;-478.0,572.0&gt;--&lt;-479.0,206.0&gt;&gt;

* u18BA8.012: L&lt;&lt;-541.0,20.0&gt;--&lt;-540.0,450.0&gt;&gt;

* u18BA8.013: L&lt;&lt;-1478.0,72.0&gt;--&lt;-1479.0,-294.0&gt;&gt;

* u18BA8.013: L&lt;&lt;-1541.0,-480.0&gt;--&lt;-1540.0,-50.0&gt;&gt;

* u18BA8.014: L&lt;&lt;-1041.0,-480.0&gt;--&lt;-1040.0,-50.0&gt;&gt;

* u18BA8.014: L&lt;&lt;-978.0,72.0&gt;--&lt;-979.0,-294.0&gt;&gt;

* u18BA8.015: L&lt;&lt;-478.0,72.0&gt;--&lt;-479.0,-294.0&gt;&gt;

* u18BA8.015: L&lt;&lt;-541.0,-480.0&gt;--&lt;-540.0,-50.0&gt;&gt;

* u18BA8.016: L&lt;&lt;-1478.0,-428.0&gt;--&lt;-1479.0,-794.0&gt;&gt;

* u18BA8.016: L&lt;&lt;-1541.0,-980.0&gt;--&lt;-1540.0,-550.0&gt;&gt;

* u18BA8.017: L&lt;&lt;-1041.0,-980.0&gt;--&lt;-1040.0,-550.0&gt;&gt;

* u18BA8.017: L&lt;&lt;-978.0,-428.0&gt;--&lt;-979.0,-794.0&gt;&gt;

* u18BA8.018: L&lt;&lt;-478.0,-428.0&gt;--&lt;-479.0,-794.0&gt;&gt;

* u18BA8.018: L&lt;&lt;-541.0,-980.0&gt;--&lt;-540.0,-550.0&gt;&gt;

* u18BA8.019: L&lt;&lt;-1478.0,-928.0&gt;--&lt;-1479.0,-1294.0&gt;&gt;

* u18BA8.019: L&lt;&lt;-1541.0,-1480.0&gt;--&lt;-1540.0,-1050.0&gt;&gt;

* u18BA8.020: L&lt;&lt;-1041.0,-1480.0&gt;--&lt;-1040.0,-1050.0&gt;&gt;

* u18BA8.020: L&lt;&lt;-978.0,-928.0&gt;--&lt;-979.0,-1294.0&gt;&gt;

* u18BA8.021: L&lt;&lt;-478.0,-928.0&gt;--&lt;-479.0,-1294.0&gt;&gt;

* u18BA8.021: L&lt;&lt;-541.0,-1480.0&gt;--&lt;-540.0,-1050.0&gt;&gt;

* u18BA8.022: L&lt;&lt;459.0,520.0&gt;--&lt;460.0,950.0&gt;&gt;

* u18BA8.022: L&lt;&lt;522.0,1072.0&gt;--&lt;521.0,706.0&gt;&gt;

* u18BA8.023: L&lt;&lt;459.0,20.0&gt;--&lt;460.0,450.0&gt;&gt;

* u18BA8.023: L&lt;&lt;522.0,572.0&gt;--&lt;521.0,206.0&gt;&gt;

* u18BAA (U+18BAA): L&lt;&lt;477.0,-14.0&gt;--&lt;478.0,439.0&gt;&gt;

* u18BAA (U+18BAA): L&lt;&lt;540.0,569.0&gt;--&lt;539.0,191.0&gt;&gt;

* u18BAA.001: L&lt;&lt;477.0,1486.0&gt;--&lt;478.0,1939.0&gt;&gt;

* u18BAA.001: L&lt;&lt;540.0,2069.0&gt;--&lt;539.0,1691.0&gt;&gt;

* u18BAA.002: L&lt;&lt;1040.0,2069.0&gt;--&lt;1039.0,1691.0&gt;&gt;

* u18BAA.002: L&lt;&lt;977.0,1486.0&gt;--&lt;978.0,1939.0&gt;&gt;

* u18BAA.003: L&lt;&lt;-460.0,2069.0&gt;--&lt;-461.0,1691.0&gt;&gt;

* u18BAA.003: L&lt;&lt;-523.0,1486.0&gt;--&lt;-522.0,1939.0&gt;&gt;

* u18BAA.004: L&lt;&lt;477.0,986.0&gt;--&lt;478.0,1439.0&gt;&gt;

* u18BAA.004: L&lt;&lt;540.0,1569.0&gt;--&lt;539.0,1191.0&gt;&gt;

* u18BAA.005: L&lt;&lt;1040.0,1569.0&gt;--&lt;1039.0,1191.0&gt;&gt;

* u18BAA.005: L&lt;&lt;977.0,986.0&gt;--&lt;978.0,1439.0&gt;&gt;

* u18BAA.006: L&lt;&lt;-460.0,1569.0&gt;--&lt;-461.0,1191.0&gt;&gt;

* u18BAA.006: L&lt;&lt;-523.0,986.0&gt;--&lt;-522.0,1439.0&gt;&gt;

* u18BAA.007: L&lt;&lt;-1460.0,1069.0&gt;--&lt;-1461.0,691.0&gt;&gt;

* u18BAA.007: L&lt;&lt;-1523.0,486.0&gt;--&lt;-1522.0,939.0&gt;&gt;

* u18BAA.008: L&lt;&lt;1040.0,1069.0&gt;--&lt;1039.0,691.0&gt;&gt;

* u18BAA.008: L&lt;&lt;977.0,486.0&gt;--&lt;978.0,939.0&gt;&gt;

* u18BAA.009: L&lt;&lt;-460.0,1069.0&gt;--&lt;-461.0,691.0&gt;&gt;

* u18BAA.009: L&lt;&lt;-523.0,486.0&gt;--&lt;-522.0,939.0&gt;&gt;

* u18BAA.010: L&lt;&lt;-1460.0,569.0&gt;--&lt;-1461.0,191.0&gt;&gt;

* u18BAA.010: L&lt;&lt;-1523.0,-14.0&gt;--&lt;-1522.0,439.0&gt;&gt;

* u18BAA.011: L&lt;&lt;1040.0,569.0&gt;--&lt;1039.0,191.0&gt;&gt;

* u18BAA.011: L&lt;&lt;977.0,-14.0&gt;--&lt;978.0,439.0&gt;&gt;

* u18BAA.012: L&lt;&lt;-460.0,569.0&gt;--&lt;-461.0,191.0&gt;&gt;

* u18BAA.012: L&lt;&lt;-523.0,-14.0&gt;--&lt;-522.0,439.0&gt;&gt;

* u18BAA.013: L&lt;&lt;-1460.0,69.0&gt;--&lt;-1461.0,-309.0&gt;&gt;

* u18BAA.013: L&lt;&lt;-1523.0,-514.0&gt;--&lt;-1522.0,-61.0&gt;&gt;

* u18BAA.014: L&lt;&lt;-1023.0,-514.0&gt;--&lt;-1022.0,-61.0&gt;&gt;

* u18BAA.014: L&lt;&lt;-960.0,69.0&gt;--&lt;-961.0,-309.0&gt;&gt;

* u18BAA.015: L&lt;&lt;-460.0,69.0&gt;--&lt;-461.0,-309.0&gt;&gt;

* u18BAA.015: L&lt;&lt;-523.0,-514.0&gt;--&lt;-522.0,-61.0&gt;&gt;

* u18BAA.016: L&lt;&lt;-1460.0,-431.0&gt;--&lt;-1461.0,-809.0&gt;&gt;

* u18BAA.016: L&lt;&lt;-1523.0,-1014.0&gt;--&lt;-1522.0,-561.0&gt;&gt;

* u18BAA.017: L&lt;&lt;-1023.0,-1014.0&gt;--&lt;-1022.0,-561.0&gt;&gt;

* u18BAA.017: L&lt;&lt;-960.0,-431.0&gt;--&lt;-961.0,-809.0&gt;&gt;

* u18BAA.018: L&lt;&lt;-460.0,-431.0&gt;--&lt;-461.0,-809.0&gt;&gt;

* u18BAA.018: L&lt;&lt;-523.0,-1014.0&gt;--&lt;-522.0,-561.0&gt;&gt;

* u18BAA.019: L&lt;&lt;-1460.0,-931.0&gt;--&lt;-1461.0,-1309.0&gt;&gt;

* u18BAA.019: L&lt;&lt;-1523.0,-1514.0&gt;--&lt;-1522.0,-1061.0&gt;&gt;

* u18BAA.020: L&lt;&lt;-1023.0,-1514.0&gt;--&lt;-1022.0,-1061.0&gt;&gt;

* u18BAA.020: L&lt;&lt;-960.0,-931.0&gt;--&lt;-961.0,-1309.0&gt;&gt;

* u18BAA.021: L&lt;&lt;-460.0,-931.0&gt;--&lt;-461.0,-1309.0&gt;&gt;

* u18BAA.021: L&lt;&lt;-523.0,-1514.0&gt;--&lt;-522.0,-1061.0&gt;&gt;

* u18BAA.022: L&lt;&lt;477.0,486.0&gt;--&lt;478.0,939.0&gt;&gt;

* u18BAA.022: L&lt;&lt;540.0,1069.0&gt;--&lt;539.0,691.0&gt;&gt;

* u18BAA.023: L&lt;&lt;477.0,-14.0&gt;--&lt;478.0,439.0&gt;&gt;

* u18BAA.023: L&lt;&lt;540.0,569.0&gt;--&lt;539.0,191.0&gt;&gt;

* u18BAB (U+18BAB): L&lt;&lt;145.0,29.0&gt;--&lt;146.0,148.0&gt;&gt;

* u18BAB (U+18BAB): L&lt;&lt;146.0,148.0&gt;--&lt;145.0,268.0&gt;&gt;

* u18BAB.001: L&lt;&lt;145.0,1529.0&gt;--&lt;146.0,1648.0&gt;&gt;

* u18BAB.001: L&lt;&lt;146.0,1648.0&gt;--&lt;145.0,1768.0&gt;&gt;

* u18BAB.002: L&lt;&lt;645.0,1529.0&gt;--&lt;646.0,1648.0&gt;&gt;

* u18BAB.002: L&lt;&lt;646.0,1648.0&gt;--&lt;645.0,1768.0&gt;&gt;

* u18BAB.003: L&lt;&lt;-854.0,1648.0&gt;--&lt;-855.0,1768.0&gt;&gt;

* u18BAB.003: L&lt;&lt;-855.0,1529.0&gt;--&lt;-854.0,1648.0&gt;&gt;

* u18BAB.004: L&lt;&lt;145.0,1029.0&gt;--&lt;146.0,1148.0&gt;&gt;

* u18BAB.004: L&lt;&lt;146.0,1148.0&gt;--&lt;145.0,1268.0&gt;&gt;

* u18BAB.005: L&lt;&lt;645.0,1029.0&gt;--&lt;646.0,1148.0&gt;&gt;

* u18BAB.005: L&lt;&lt;646.0,1148.0&gt;--&lt;645.0,1268.0&gt;&gt;

* u18BAB.006: L&lt;&lt;-854.0,1148.0&gt;--&lt;-855.0,1268.0&gt;&gt;

* u18BAB.006: L&lt;&lt;-855.0,1029.0&gt;--&lt;-854.0,1148.0&gt;&gt;

* u18BAB.007: L&lt;&lt;-1854.0,648.0&gt;--&lt;-1855.0,768.0&gt;&gt;

* u18BAB.007: L&lt;&lt;-1855.0,529.0&gt;--&lt;-1854.0,648.0&gt;&gt;

* u18BAB.008: L&lt;&lt;645.0,529.0&gt;--&lt;646.0,648.0&gt;&gt;

* u18BAB.008: L&lt;&lt;646.0,648.0&gt;--&lt;645.0,768.0&gt;&gt;

* u18BAB.009: L&lt;&lt;-854.0,648.0&gt;--&lt;-855.0,768.0&gt;&gt;

* u18BAB.009: L&lt;&lt;-855.0,529.0&gt;--&lt;-854.0,648.0&gt;&gt;

* u18BAB.010: L&lt;&lt;-1854.0,148.0&gt;--&lt;-1855.0,268.0&gt;&gt;

* u18BAB.010: L&lt;&lt;-1855.0,29.0&gt;--&lt;-1854.0,148.0&gt;&gt;

* u18BAB.011: L&lt;&lt;645.0,29.0&gt;--&lt;646.0,148.0&gt;&gt;

* u18BAB.011: L&lt;&lt;646.0,148.0&gt;--&lt;645.0,268.0&gt;&gt;

* u18BAB.012: L&lt;&lt;-854.0,148.0&gt;--&lt;-855.0,268.0&gt;&gt;

* u18BAB.012: L&lt;&lt;-855.0,29.0&gt;--&lt;-854.0,148.0&gt;&gt;

* u18BAB.013: L&lt;&lt;-1854.0,-352.0&gt;--&lt;-1855.0,-232.0&gt;&gt;

* u18BAB.013: L&lt;&lt;-1855.0,-471.0&gt;--&lt;-1854.0,-352.0&gt;&gt;

* u18BAB.014: L&lt;&lt;-1354.0,-352.0&gt;--&lt;-1355.0,-232.0&gt;&gt;

* u18BAB.014: L&lt;&lt;-1355.0,-471.0&gt;--&lt;-1354.0,-352.0&gt;&gt;

* u18BAB.015: L&lt;&lt;-854.0,-352.0&gt;--&lt;-855.0,-232.0&gt;&gt;

* u18BAB.015: L&lt;&lt;-855.0,-471.0&gt;--&lt;-854.0,-352.0&gt;&gt;

* u18BAB.016: L&lt;&lt;-1854.0,-852.0&gt;--&lt;-1855.0,-732.0&gt;&gt;

* u18BAB.016: L&lt;&lt;-1855.0,-971.0&gt;--&lt;-1854.0,-852.0&gt;&gt;

* u18BAB.017: L&lt;&lt;-1354.0,-852.0&gt;--&lt;-1355.0,-732.0&gt;&gt;

* u18BAB.017: L&lt;&lt;-1355.0,-971.0&gt;--&lt;-1354.0,-852.0&gt;&gt;

* u18BAB.018: L&lt;&lt;-854.0,-852.0&gt;--&lt;-855.0,-732.0&gt;&gt;

* u18BAB.018: L&lt;&lt;-855.0,-971.0&gt;--&lt;-854.0,-852.0&gt;&gt;

* u18BAB.019: L&lt;&lt;-1854.0,-1352.0&gt;--&lt;-1855.0,-1232.0&gt;&gt;

* u18BAB.019: L&lt;&lt;-1855.0,-1471.0&gt;--&lt;-1854.0,-1352.0&gt;&gt;

* u18BAB.020: L&lt;&lt;-1354.0,-1352.0&gt;--&lt;-1355.0,-1232.0&gt;&gt;

* u18BAB.020: L&lt;&lt;-1355.0,-1471.0&gt;--&lt;-1354.0,-1352.0&gt;&gt;

* u18BAB.021: L&lt;&lt;-854.0,-1352.0&gt;--&lt;-855.0,-1232.0&gt;&gt;

* u18BAB.021: L&lt;&lt;-855.0,-1471.0&gt;--&lt;-854.0,-1352.0&gt;&gt;

* u18BAB.022: L&lt;&lt;145.0,529.0&gt;--&lt;146.0,648.0&gt;&gt;

* u18BAB.022: L&lt;&lt;146.0,648.0&gt;--&lt;145.0,768.0&gt;&gt;

* u18BAB.023: L&lt;&lt;145.0,29.0&gt;--&lt;146.0,148.0&gt;&gt;

* u18BAB.023: L&lt;&lt;146.0,148.0&gt;--&lt;145.0,268.0&gt;&gt;

* u18BC4 (U+18BC4): L&lt;&lt;208.0,555.0&gt;--&lt;207.0,424.0&gt;&gt;

* u18BC4.001: L&lt;&lt;208.0,2055.0&gt;--&lt;207.0,1924.0&gt;&gt;

* u18BC4.002: L&lt;&lt;708.0,2055.0&gt;--&lt;707.0,1924.0&gt;&gt;

* u18BC4.003: L&lt;&lt;-792.0,2055.0&gt;--&lt;-793.0,1924.0&gt;&gt;

* u18BC4.004: L&lt;&lt;208.0,1555.0&gt;--&lt;207.0,1424.0&gt;&gt;

* u18BC4.005: L&lt;&lt;708.0,1555.0&gt;--&lt;707.0,1424.0&gt;&gt;

* u18BC4.006: L&lt;&lt;-792.0,1555.0&gt;--&lt;-793.0,1424.0&gt;&gt;

* u18BC4.007: L&lt;&lt;-1792.0,1055.0&gt;--&lt;-1793.0,924.0&gt;&gt;

* u18BC4.008: L&lt;&lt;708.0,1055.0&gt;--&lt;707.0,924.0&gt;&gt;

* u18BC4.009: L&lt;&lt;-792.0,1055.0&gt;--&lt;-793.0,924.0&gt;&gt;

* u18BC4.010: L&lt;&lt;-1792.0,555.0&gt;--&lt;-1793.0,424.0&gt;&gt;

* u18BC4.011: L&lt;&lt;708.0,555.0&gt;--&lt;707.0,424.0&gt;&gt;

* u18BC4.012: L&lt;&lt;-792.0,555.0&gt;--&lt;-793.0,424.0&gt;&gt;

* u18BC4.013: L&lt;&lt;-1792.0,55.0&gt;--&lt;-1793.0,-76.0&gt;&gt;

* u18BC4.014: L&lt;&lt;-1292.0,55.0&gt;--&lt;-1293.0,-76.0&gt;&gt;

* u18BC4.015: L&lt;&lt;-792.0,55.0&gt;--&lt;-793.0,-76.0&gt;&gt;

* u18BC4.016: L&lt;&lt;-1792.0,-445.0&gt;--&lt;-1793.0,-576.0&gt;&gt;

* u18BC4.017: L&lt;&lt;-1292.0,-445.0&gt;--&lt;-1293.0,-576.0&gt;&gt;

* u18BC4.018: L&lt;&lt;-792.0,-445.0&gt;--&lt;-793.0,-576.0&gt;&gt;

* u18BC4.019: L&lt;&lt;-1792.0,-945.0&gt;--&lt;-1793.0,-1076.0&gt;&gt;

* u18BC4.020: L&lt;&lt;-1292.0,-945.0&gt;--&lt;-1293.0,-1076.0&gt;&gt;

* u18BC4.021: L&lt;&lt;-792.0,-945.0&gt;--&lt;-793.0,-1076.0&gt;&gt;

* u18BC4.022: L&lt;&lt;208.0,1055.0&gt;--&lt;207.0,924.0&gt;&gt;

* u18BC4.023: L&lt;&lt;208.0,555.0&gt;--&lt;207.0,424.0&gt;&gt;

* u18BC5 (U+18BC5): L&lt;&lt;208.0,555.0&gt;--&lt;207.0,424.0&gt;&gt;

* u18BC5.001: L&lt;&lt;208.0,2055.0&gt;--&lt;207.0,1924.0&gt;&gt;

* u18BC5.002: L&lt;&lt;708.0,2055.0&gt;--&lt;707.0,1924.0&gt;&gt;

* u18BC5.003: L&lt;&lt;-792.0,2055.0&gt;--&lt;-793.0,1924.0&gt;&gt;

* u18BC5.004: L&lt;&lt;208.0,1555.0&gt;--&lt;207.0,1424.0&gt;&gt;

* u18BC5.005: L&lt;&lt;708.0,1555.0&gt;--&lt;707.0,1424.0&gt;&gt;

* u18BC5.006: L&lt;&lt;-792.0,1555.0&gt;--&lt;-793.0,1424.0&gt;&gt;

* u18BC5.007: L&lt;&lt;-1792.0,1055.0&gt;--&lt;-1793.0,924.0&gt;&gt;

* u18BC5.008: L&lt;&lt;708.0,1055.0&gt;--&lt;707.0,924.0&gt;&gt;

* u18BC5.009: L&lt;&lt;-792.0,1055.0&gt;--&lt;-793.0,924.0&gt;&gt;

* u18BC5.010: L&lt;&lt;-1792.0,555.0&gt;--&lt;-1793.0,424.0&gt;&gt;

* u18BC5.011: L&lt;&lt;708.0,555.0&gt;--&lt;707.0,424.0&gt;&gt;

* u18BC5.012: L&lt;&lt;-792.0,555.0&gt;--&lt;-793.0,424.0&gt;&gt;

* u18BC5.013: L&lt;&lt;-1792.0,55.0&gt;--&lt;-1793.0,-76.0&gt;&gt;

* u18BC5.014: L&lt;&lt;-1292.0,55.0&gt;--&lt;-1293.0,-76.0&gt;&gt;

* u18BC5.015: L&lt;&lt;-792.0,55.0&gt;--&lt;-793.0,-76.0&gt;&gt;

* u18BC5.016: L&lt;&lt;-1792.0,-445.0&gt;--&lt;-1793.0,-576.0&gt;&gt;

* u18BC5.017: L&lt;&lt;-1292.0,-445.0&gt;--&lt;-1293.0,-576.0&gt;&gt;

* u18BC5.018: L&lt;&lt;-792.0,-445.0&gt;--&lt;-793.0,-576.0&gt;&gt;

* u18BC5.019: L&lt;&lt;-1792.0,-945.0&gt;--&lt;-1793.0,-1076.0&gt;&gt;

* u18BC5.020: L&lt;&lt;-1292.0,-945.0&gt;--&lt;-1293.0,-1076.0&gt;&gt;

* u18BC5.021: L&lt;&lt;-792.0,-945.0&gt;--&lt;-793.0,-1076.0&gt;&gt;

* u18BC5.022: L&lt;&lt;208.0,1055.0&gt;--&lt;207.0,924.0&gt;&gt;

* u18BC5.023: L&lt;&lt;208.0,555.0&gt;--&lt;207.0,424.0&gt;&gt;

* u18BC7 (U+18BC7): L&lt;&lt;530.0,475.0&gt;--&lt;529.0,211.0&gt;&gt;

* u18BC7.001: L&lt;&lt;530.0,1975.0&gt;--&lt;529.0,1711.0&gt;&gt;

* u18BC7.002: L&lt;&lt;1030.0,1975.0&gt;--&lt;1029.0,1711.0&gt;&gt;

* u18BC7.003: L&lt;&lt;-470.0,1975.0&gt;--&lt;-471.0,1711.0&gt;&gt;

* u18BC7.004: L&lt;&lt;530.0,1475.0&gt;--&lt;529.0,1211.0&gt;&gt;

* u18BC7.005: L&lt;&lt;1030.0,1475.0&gt;--&lt;1029.0,1211.0&gt;&gt;

* u18BC7.006: L&lt;&lt;-470.0,1475.0&gt;--&lt;-471.0,1211.0&gt;&gt;

* u18BC7.007: L&lt;&lt;-1470.0,975.0&gt;--&lt;-1471.0,711.0&gt;&gt;

* u18BC7.008: L&lt;&lt;1030.0,975.0&gt;--&lt;1029.0,711.0&gt;&gt;

* u18BC7.009: L&lt;&lt;-470.0,975.0&gt;--&lt;-471.0,711.0&gt;&gt;

* u18BC7.010: L&lt;&lt;-1470.0,475.0&gt;--&lt;-1471.0,211.0&gt;&gt;

* u18BC7.011: L&lt;&lt;1030.0,475.0&gt;--&lt;1029.0,211.0&gt;&gt;

* u18BC7.012: L&lt;&lt;-470.0,475.0&gt;--&lt;-471.0,211.0&gt;&gt;

* u18BC7.013: L&lt;&lt;-1470.0,-25.0&gt;--&lt;-1471.0,-289.0&gt;&gt;

* u18BC7.014: L&lt;&lt;-970.0,-25.0&gt;--&lt;-971.0,-289.0&gt;&gt;

* u18BC7.015: L&lt;&lt;-470.0,-25.0&gt;--&lt;-471.0,-289.0&gt;&gt;

* u18BC7.016: L&lt;&lt;-1470.0,-525.0&gt;--&lt;-1471.0,-789.0&gt;&gt;

* u18BC7.017: L&lt;&lt;-970.0,-525.0&gt;--&lt;-971.0,-789.0&gt;&gt;

* u18BC7.018: L&lt;&lt;-470.0,-525.0&gt;--&lt;-471.0,-789.0&gt;&gt;

* u18BC7.019: L&lt;&lt;-1470.0,-1025.0&gt;--&lt;-1471.0,-1289.0&gt;&gt;

* u18BC7.020: L&lt;&lt;-970.0,-1025.0&gt;--&lt;-971.0,-1289.0&gt;&gt;

* u18BC7.021: L&lt;&lt;-470.0,-1025.0&gt;--&lt;-471.0,-1289.0&gt;&gt;

* u18BC7.022: L&lt;&lt;530.0,975.0&gt;--&lt;529.0,711.0&gt;&gt;

* u18BC7.023: L&lt;&lt;530.0,475.0&gt;--&lt;529.0,211.0&gt;&gt;

* u18BC9 (U+18BC9): L&lt;&lt;530.0,459.0&gt;--&lt;529.0,211.0&gt;&gt;

* u18BC9.001: L&lt;&lt;530.0,1959.0&gt;--&lt;529.0,1711.0&gt;&gt;

* u18BC9.002: L&lt;&lt;1030.0,1959.0&gt;--&lt;1029.0,1711.0&gt;&gt;

* u18BC9.003: L&lt;&lt;-470.0,1959.0&gt;--&lt;-471.0,1711.0&gt;&gt;

* u18BC9.004: L&lt;&lt;530.0,1459.0&gt;--&lt;529.0,1211.0&gt;&gt;

* u18BC9.005: L&lt;&lt;1030.0,1459.0&gt;--&lt;1029.0,1211.0&gt;&gt;

* u18BC9.006: L&lt;&lt;-470.0,1459.0&gt;--&lt;-471.0,1211.0&gt;&gt;

* u18BC9.007: L&lt;&lt;-1470.0,959.0&gt;--&lt;-1471.0,711.0&gt;&gt;

* u18BC9.008: L&lt;&lt;1030.0,959.0&gt;--&lt;1029.0,711.0&gt;&gt;

* u18BC9.009: L&lt;&lt;-470.0,959.0&gt;--&lt;-471.0,711.0&gt;&gt;

* u18BC9.010: L&lt;&lt;-1470.0,459.0&gt;--&lt;-1471.0,211.0&gt;&gt;

* u18BC9.011: L&lt;&lt;1030.0,459.0&gt;--&lt;1029.0,211.0&gt;&gt;

* u18BC9.012: L&lt;&lt;-470.0,459.0&gt;--&lt;-471.0,211.0&gt;&gt;

* u18BC9.013: L&lt;&lt;-1470.0,-41.0&gt;--&lt;-1471.0,-289.0&gt;&gt;

* u18BC9.014: L&lt;&lt;-970.0,-41.0&gt;--&lt;-971.0,-289.0&gt;&gt;

* u18BC9.015: L&lt;&lt;-470.0,-41.0&gt;--&lt;-471.0,-289.0&gt;&gt;

* u18BC9.016: L&lt;&lt;-1470.0,-541.0&gt;--&lt;-1471.0,-789.0&gt;&gt;

* u18BC9.017: L&lt;&lt;-970.0,-541.0&gt;--&lt;-971.0,-789.0&gt;&gt;

* u18BC9.018: L&lt;&lt;-470.0,-541.0&gt;--&lt;-471.0,-789.0&gt;&gt;

* u18BC9.019: L&lt;&lt;-1470.0,-1041.0&gt;--&lt;-1471.0,-1289.0&gt;&gt;

* u18BC9.020: L&lt;&lt;-970.0,-1041.0&gt;--&lt;-971.0,-1289.0&gt;&gt;

* u18BC9.021: L&lt;&lt;-470.0,-1041.0&gt;--&lt;-471.0,-1289.0&gt;&gt;

* u18BC9.022: L&lt;&lt;530.0,959.0&gt;--&lt;529.0,711.0&gt;&gt;

* u18BC9.023: L&lt;&lt;530.0,459.0&gt;--&lt;529.0,211.0&gt;&gt;

* u18BCA (U+18BCA): L&lt;&lt;261.0,357.0&gt;--&lt;260.0,197.0&gt;&gt;

* u18BCA.001: L&lt;&lt;261.0,1857.0&gt;--&lt;260.0,1697.0&gt;&gt;

* u18BCA.002: L&lt;&lt;761.0,1857.0&gt;--&lt;760.0,1697.0&gt;&gt;

* u18BCA.003: L&lt;&lt;-739.0,1857.0&gt;--&lt;-740.0,1697.0&gt;&gt;

* u18BCA.004: L&lt;&lt;261.0,1357.0&gt;--&lt;260.0,1197.0&gt;&gt;

* u18BCA.005: L&lt;&lt;761.0,1357.0&gt;--&lt;760.0,1197.0&gt;&gt;

* u18BCA.006: L&lt;&lt;-739.0,1357.0&gt;--&lt;-740.0,1197.0&gt;&gt;

* u18BCA.007: L&lt;&lt;-1739.0,857.0&gt;--&lt;-1740.0,697.0&gt;&gt;

* u18BCA.008: L&lt;&lt;761.0,857.0&gt;--&lt;760.0,697.0&gt;&gt;

* u18BCA.009: L&lt;&lt;-739.0,857.0&gt;--&lt;-740.0,697.0&gt;&gt;

* u18BCA.010: L&lt;&lt;-1739.0,357.0&gt;--&lt;-1740.0,197.0&gt;&gt;

* u18BCA.011: L&lt;&lt;761.0,357.0&gt;--&lt;760.0,197.0&gt;&gt;

* u18BCA.012: L&lt;&lt;-739.0,357.0&gt;--&lt;-740.0,197.0&gt;&gt;

* u18BCA.013: L&lt;&lt;-1739.0,-143.0&gt;--&lt;-1740.0,-303.0&gt;&gt;

* u18BCA.014: L&lt;&lt;-1239.0,-143.0&gt;--&lt;-1240.0,-303.0&gt;&gt;

* u18BCA.015: L&lt;&lt;-739.0,-143.0&gt;--&lt;-740.0,-303.0&gt;&gt;

* u18BCA.016: L&lt;&lt;-1739.0,-643.0&gt;--&lt;-1740.0,-803.0&gt;&gt;

* u18BCA.017: L&lt;&lt;-1239.0,-643.0&gt;--&lt;-1240.0,-803.0&gt;&gt;

* u18BCA.018: L&lt;&lt;-739.0,-643.0&gt;--&lt;-740.0,-803.0&gt;&gt;

* u18BCA.019: L&lt;&lt;-1739.0,-1143.0&gt;--&lt;-1740.0,-1303.0&gt;&gt;

* u18BCA.020: L&lt;&lt;-1239.0,-1143.0&gt;--&lt;-1240.0,-1303.0&gt;&gt;

* u18BCA.021: L&lt;&lt;-739.0,-1143.0&gt;--&lt;-740.0,-1303.0&gt;&gt;

* u18BCA.022: L&lt;&lt;261.0,857.0&gt;--&lt;260.0,697.0&gt;&gt;

* u18BCA.023: L&lt;&lt;261.0,357.0&gt;--&lt;260.0,197.0&gt;&gt;

* u18BCC (U+18BCC): L&lt;&lt;229.0,345.0&gt;--&lt;230.0,182.0&gt;&gt;

* u18BCC.001: L&lt;&lt;229.0,1845.0&gt;--&lt;230.0,1682.0&gt;&gt;

* u18BCC.002: L&lt;&lt;729.0,1845.0&gt;--&lt;730.0,1682.0&gt;&gt;

* u18BCC.003: L&lt;&lt;-771.0,1845.0&gt;--&lt;-770.0,1682.0&gt;&gt;

* u18BCC.004: L&lt;&lt;229.0,1345.0&gt;--&lt;230.0,1182.0&gt;&gt;

* u18BCC.005: L&lt;&lt;729.0,1345.0&gt;--&lt;730.0,1182.0&gt;&gt;

* u18BCC.006: L&lt;&lt;-771.0,1345.0&gt;--&lt;-770.0,1182.0&gt;&gt;

* u18BCC.007: L&lt;&lt;-1771.0,845.0&gt;--&lt;-1770.0,682.0&gt;&gt;

* u18BCC.008: L&lt;&lt;729.0,845.0&gt;--&lt;730.0,682.0&gt;&gt;

* u18BCC.009: L&lt;&lt;-771.0,845.0&gt;--&lt;-770.0,682.0&gt;&gt;

* u18BCC.010: L&lt;&lt;-1771.0,345.0&gt;--&lt;-1770.0,182.0&gt;&gt;

* u18BCC.011: L&lt;&lt;729.0,345.0&gt;--&lt;730.0,182.0&gt;&gt;

* u18BCC.012: L&lt;&lt;-771.0,345.0&gt;--&lt;-770.0,182.0&gt;&gt;

* u18BCC.013: L&lt;&lt;-1771.0,-155.0&gt;--&lt;-1770.0,-318.0&gt;&gt;

* u18BCC.014: L&lt;&lt;-1271.0,-155.0&gt;--&lt;-1270.0,-318.0&gt;&gt;

* u18BCC.015: L&lt;&lt;-771.0,-155.0&gt;--&lt;-770.0,-318.0&gt;&gt;

* u18BCC.016: L&lt;&lt;-1771.0,-655.0&gt;--&lt;-1770.0,-818.0&gt;&gt;

* u18BCC.017: L&lt;&lt;-1271.0,-655.0&gt;--&lt;-1270.0,-818.0&gt;&gt;

* u18BCC.018: L&lt;&lt;-771.0,-655.0&gt;--&lt;-770.0,-818.0&gt;&gt;

* u18BCC.019: L&lt;&lt;-1771.0,-1155.0&gt;--&lt;-1770.0,-1318.0&gt;&gt;

* u18BCC.020: L&lt;&lt;-1271.0,-1155.0&gt;--&lt;-1270.0,-1318.0&gt;&gt;

* u18BCC.021: L&lt;&lt;-771.0,-1155.0&gt;--&lt;-770.0,-1318.0&gt;&gt;

* u18BCC.022: L&lt;&lt;229.0,845.0&gt;--&lt;230.0,682.0&gt;&gt;

* u18BCC.023: L&lt;&lt;229.0,345.0&gt;--&lt;230.0,182.0&gt;&gt;

* u18BD0 (U+18BD0): L&lt;&lt;184.0,332.0&gt;--&lt;183.0,177.0&gt;&gt;

* u18BD0 (U+18BD0): L&lt;&lt;467.0,-38.0&gt;--&lt;468.0,445.0&gt;&gt;

* u18BD0 (U+18BD0): L&lt;&lt;530.0,585.0&gt;--&lt;529.0,-34.0&gt;&gt;

* u18BD0 (U+18BD0): L&lt;&lt;698.0,353.0&gt;--&lt;697.0,205.0&gt;&gt;

* u18BD0.001: L&lt;&lt;184.0,1832.0&gt;--&lt;183.0,1677.0&gt;&gt;

* u18BD0.001: L&lt;&lt;467.0,1462.0&gt;--&lt;468.0,1945.0&gt;&gt;

* u18BD0.001: L&lt;&lt;530.0,2085.0&gt;--&lt;529.0,1466.0&gt;&gt;

* u18BD0.001: L&lt;&lt;698.0,1853.0&gt;--&lt;697.0,1705.0&gt;&gt;

* u18BD0.002: L&lt;&lt;1030.0,2085.0&gt;--&lt;1029.0,1466.0&gt;&gt;

* u18BD0.002: L&lt;&lt;1198.0,1853.0&gt;--&lt;1197.0,1705.0&gt;&gt;

* u18BD0.002: L&lt;&lt;684.0,1832.0&gt;--&lt;683.0,1677.0&gt;&gt;

* u18BD0.002: L&lt;&lt;967.0,1462.0&gt;--&lt;968.0,1945.0&gt;&gt;

* u18BD0.003: L&lt;&lt;-302.0,1853.0&gt;--&lt;-303.0,1705.0&gt;&gt;

* u18BD0.003: L&lt;&lt;-470.0,2085.0&gt;--&lt;-471.0,1466.0&gt;&gt;

* u18BD0.003: L&lt;&lt;-533.0,1462.0&gt;--&lt;-532.0,1945.0&gt;&gt;

* u18BD0.003: L&lt;&lt;-816.0,1832.0&gt;--&lt;-817.0,1677.0&gt;&gt;

* u18BD0.004: L&lt;&lt;184.0,1332.0&gt;--&lt;183.0,1177.0&gt;&gt;

* u18BD0.004: L&lt;&lt;467.0,962.0&gt;--&lt;468.0,1445.0&gt;&gt;

* u18BD0.004: L&lt;&lt;530.0,1585.0&gt;--&lt;529.0,966.0&gt;&gt;

* u18BD0.004: L&lt;&lt;698.0,1353.0&gt;--&lt;697.0,1205.0&gt;&gt;

* u18BD0.005: L&lt;&lt;1030.0,1585.0&gt;--&lt;1029.0,966.0&gt;&gt;

* u18BD0.005: L&lt;&lt;1198.0,1353.0&gt;--&lt;1197.0,1205.0&gt;&gt;

* u18BD0.005: L&lt;&lt;684.0,1332.0&gt;--&lt;683.0,1177.0&gt;&gt;

* u18BD0.005: L&lt;&lt;967.0,962.0&gt;--&lt;968.0,1445.0&gt;&gt;

* u18BD0.006: L&lt;&lt;-302.0,1353.0&gt;--&lt;-303.0,1205.0&gt;&gt;

* u18BD0.006: L&lt;&lt;-470.0,1585.0&gt;--&lt;-471.0,966.0&gt;&gt;

* u18BD0.006: L&lt;&lt;-533.0,962.0&gt;--&lt;-532.0,1445.0&gt;&gt;

* u18BD0.006: L&lt;&lt;-816.0,1332.0&gt;--&lt;-817.0,1177.0&gt;&gt;

* u18BD0.007: L&lt;&lt;-1302.0,853.0&gt;--&lt;-1303.0,705.0&gt;&gt;

* u18BD0.007: L&lt;&lt;-1470.0,1085.0&gt;--&lt;-1471.0,466.0&gt;&gt;

* u18BD0.007: L&lt;&lt;-1533.0,462.0&gt;--&lt;-1532.0,945.0&gt;&gt;

* u18BD0.007: L&lt;&lt;-1816.0,832.0&gt;--&lt;-1817.0,677.0&gt;&gt;

* u18BD0.008: L&lt;&lt;1030.0,1085.0&gt;--&lt;1029.0,466.0&gt;&gt;

* u18BD0.008: L&lt;&lt;1198.0,853.0&gt;--&lt;1197.0,705.0&gt;&gt;

* u18BD0.008: L&lt;&lt;684.0,832.0&gt;--&lt;683.0,677.0&gt;&gt;

* u18BD0.008: L&lt;&lt;967.0,462.0&gt;--&lt;968.0,945.0&gt;&gt;

* u18BD0.009: L&lt;&lt;-302.0,853.0&gt;--&lt;-303.0,705.0&gt;&gt;

* u18BD0.009: L&lt;&lt;-470.0,1085.0&gt;--&lt;-471.0,466.0&gt;&gt;

* u18BD0.009: L&lt;&lt;-533.0,462.0&gt;--&lt;-532.0,945.0&gt;&gt;

* u18BD0.009: L&lt;&lt;-816.0,832.0&gt;--&lt;-817.0,677.0&gt;&gt;

* u18BD0.010: L&lt;&lt;-1302.0,353.0&gt;--&lt;-1303.0,205.0&gt;&gt;

* u18BD0.010: L&lt;&lt;-1470.0,585.0&gt;--&lt;-1471.0,-34.0&gt;&gt;

* u18BD0.010: L&lt;&lt;-1533.0,-38.0&gt;--&lt;-1532.0,445.0&gt;&gt;

* u18BD0.010: L&lt;&lt;-1816.0,332.0&gt;--&lt;-1817.0,177.0&gt;&gt;

* u18BD0.011: L&lt;&lt;1030.0,585.0&gt;--&lt;1029.0,-34.0&gt;&gt;

* u18BD0.011: L&lt;&lt;1198.0,353.0&gt;--&lt;1197.0,205.0&gt;&gt;

* u18BD0.011: L&lt;&lt;684.0,332.0&gt;--&lt;683.0,177.0&gt;&gt;

* u18BD0.011: L&lt;&lt;967.0,-38.0&gt;--&lt;968.0,445.0&gt;&gt;

* u18BD0.012: L&lt;&lt;-302.0,353.0&gt;--&lt;-303.0,205.0&gt;&gt;

* u18BD0.012: L&lt;&lt;-470.0,585.0&gt;--&lt;-471.0,-34.0&gt;&gt;

* u18BD0.012: L&lt;&lt;-533.0,-38.0&gt;--&lt;-532.0,445.0&gt;&gt;

* u18BD0.012: L&lt;&lt;-816.0,332.0&gt;--&lt;-817.0,177.0&gt;&gt;

* u18BD0.013: L&lt;&lt;-1302.0,-147.0&gt;--&lt;-1303.0,-295.0&gt;&gt;

* u18BD0.013: L&lt;&lt;-1470.0,85.0&gt;--&lt;-1471.0,-534.0&gt;&gt;

* u18BD0.013: L&lt;&lt;-1533.0,-538.0&gt;--&lt;-1532.0,-55.0&gt;&gt;

* u18BD0.013: L&lt;&lt;-1816.0,-168.0&gt;--&lt;-1817.0,-323.0&gt;&gt;

* u18BD0.014: L&lt;&lt;-1033.0,-538.0&gt;--&lt;-1032.0,-55.0&gt;&gt;

* u18BD0.014: L&lt;&lt;-1316.0,-168.0&gt;--&lt;-1317.0,-323.0&gt;&gt;

* u18BD0.014: L&lt;&lt;-802.0,-147.0&gt;--&lt;-803.0,-295.0&gt;&gt;

* u18BD0.014: L&lt;&lt;-970.0,85.0&gt;--&lt;-971.0,-534.0&gt;&gt;

* u18BD0.015: L&lt;&lt;-302.0,-147.0&gt;--&lt;-303.0,-295.0&gt;&gt;

* u18BD0.015: L&lt;&lt;-470.0,85.0&gt;--&lt;-471.0,-534.0&gt;&gt;

* u18BD0.015: L&lt;&lt;-533.0,-538.0&gt;--&lt;-532.0,-55.0&gt;&gt;

* u18BD0.015: L&lt;&lt;-816.0,-168.0&gt;--&lt;-817.0,-323.0&gt;&gt;

* u18BD0.016: L&lt;&lt;-1302.0,-647.0&gt;--&lt;-1303.0,-795.0&gt;&gt;

* u18BD0.016: L&lt;&lt;-1470.0,-415.0&gt;--&lt;-1471.0,-1034.0&gt;&gt;

* u18BD0.016: L&lt;&lt;-1533.0,-1038.0&gt;--&lt;-1532.0,-555.0&gt;&gt;

* u18BD0.016: L&lt;&lt;-1816.0,-668.0&gt;--&lt;-1817.0,-823.0&gt;&gt;

* u18BD0.017: L&lt;&lt;-1033.0,-1038.0&gt;--&lt;-1032.0,-555.0&gt;&gt;

* u18BD0.017: L&lt;&lt;-1316.0,-668.0&gt;--&lt;-1317.0,-823.0&gt;&gt;

* u18BD0.017: L&lt;&lt;-802.0,-647.0&gt;--&lt;-803.0,-795.0&gt;&gt;

* u18BD0.017: L&lt;&lt;-970.0,-415.0&gt;--&lt;-971.0,-1034.0&gt;&gt;

* u18BD0.018: L&lt;&lt;-302.0,-647.0&gt;--&lt;-303.0,-795.0&gt;&gt;

* u18BD0.018: L&lt;&lt;-470.0,-415.0&gt;--&lt;-471.0,-1034.0&gt;&gt;

* u18BD0.018: L&lt;&lt;-533.0,-1038.0&gt;--&lt;-532.0,-555.0&gt;&gt;

* u18BD0.018: L&lt;&lt;-816.0,-668.0&gt;--&lt;-817.0,-823.0&gt;&gt;

* u18BD0.019: L&lt;&lt;-1302.0,-1147.0&gt;--&lt;-1303.0,-1295.0&gt;&gt;

* u18BD0.019: L&lt;&lt;-1470.0,-915.0&gt;--&lt;-1471.0,-1534.0&gt;&gt;

* u18BD0.019: L&lt;&lt;-1533.0,-1538.0&gt;--&lt;-1532.0,-1055.0&gt;&gt;

* u18BD0.019: L&lt;&lt;-1816.0,-1168.0&gt;--&lt;-1817.0,-1323.0&gt;&gt;

* u18BD0.020: L&lt;&lt;-1033.0,-1538.0&gt;--&lt;-1032.0,-1055.0&gt;&gt;

* u18BD0.020: L&lt;&lt;-1316.0,-1168.0&gt;--&lt;-1317.0,-1323.0&gt;&gt;

* u18BD0.020: L&lt;&lt;-802.0,-1147.0&gt;--&lt;-803.0,-1295.0&gt;&gt;

* u18BD0.020: L&lt;&lt;-970.0,-915.0&gt;--&lt;-971.0,-1534.0&gt;&gt;

* u18BD0.021: L&lt;&lt;-302.0,-1147.0&gt;--&lt;-303.0,-1295.0&gt;&gt;

* u18BD0.021: L&lt;&lt;-470.0,-915.0&gt;--&lt;-471.0,-1534.0&gt;&gt;

* u18BD0.021: L&lt;&lt;-533.0,-1538.0&gt;--&lt;-532.0,-1055.0&gt;&gt;

* u18BD0.021: L&lt;&lt;-816.0,-1168.0&gt;--&lt;-817.0,-1323.0&gt;&gt;

* u18BD0.022: L&lt;&lt;184.0,832.0&gt;--&lt;183.0,677.0&gt;&gt;

* u18BD0.022: L&lt;&lt;467.0,462.0&gt;--&lt;468.0,945.0&gt;&gt;

* u18BD0.022: L&lt;&lt;530.0,1085.0&gt;--&lt;529.0,466.0&gt;&gt;

* u18BD0.022: L&lt;&lt;698.0,853.0&gt;--&lt;697.0,705.0&gt;&gt;

* u18BD0.023: L&lt;&lt;184.0,332.0&gt;--&lt;183.0,177.0&gt;&gt;

* u18BD0.023: L&lt;&lt;467.0,-38.0&gt;--&lt;468.0,445.0&gt;&gt;

* u18BD0.023: L&lt;&lt;530.0,585.0&gt;--&lt;529.0,-34.0&gt;&gt;

* u18BD0.023: L&lt;&lt;698.0,353.0&gt;--&lt;697.0,205.0&gt;&gt;

* u18BD3 (U+18BD3): L&lt;&lt;531.0,114.0&gt;--&lt;530.0,-154.0&gt;&gt;

* u18BD3.001: L&lt;&lt;531.0,1614.0&gt;--&lt;530.0,1346.0&gt;&gt;

* u18BD3.002: L&lt;&lt;1031.0,1614.0&gt;--&lt;1030.0,1346.0&gt;&gt;

* u18BD3.003: L&lt;&lt;-469.0,1614.0&gt;--&lt;-470.0,1346.0&gt;&gt;

* u18BD3.004: L&lt;&lt;531.0,1114.0&gt;--&lt;530.0,846.0&gt;&gt;

* u18BD3.005: L&lt;&lt;1031.0,1114.0&gt;--&lt;1030.0,846.0&gt;&gt;

* u18BD3.006: L&lt;&lt;-469.0,1114.0&gt;--&lt;-470.0,846.0&gt;&gt;

* u18BD3.007: L&lt;&lt;-1469.0,614.0&gt;--&lt;-1470.0,346.0&gt;&gt;

* u18BD3.008: L&lt;&lt;1031.0,614.0&gt;--&lt;1030.0,346.0&gt;&gt;

* u18BD3.009: L&lt;&lt;-469.0,614.0&gt;--&lt;-470.0,346.0&gt;&gt;

* u18BD3.010: L&lt;&lt;-1469.0,114.0&gt;--&lt;-1470.0,-154.0&gt;&gt;

* u18BD3.011: L&lt;&lt;1031.0,114.0&gt;--&lt;1030.0,-154.0&gt;&gt;

* u18BD3.012: L&lt;&lt;-469.0,114.0&gt;--&lt;-470.0,-154.0&gt;&gt;

* u18BD3.013: L&lt;&lt;-1469.0,-386.0&gt;--&lt;-1470.0,-654.0&gt;&gt;

* u18BD3.014: L&lt;&lt;-969.0,-386.0&gt;--&lt;-970.0,-654.0&gt;&gt;

* u18BD3.015: L&lt;&lt;-469.0,-386.0&gt;--&lt;-470.0,-654.0&gt;&gt;

* u18BD3.016: L&lt;&lt;-1469.0,-886.0&gt;--&lt;-1470.0,-1154.0&gt;&gt;

* u18BD3.017: L&lt;&lt;-969.0,-886.0&gt;--&lt;-970.0,-1154.0&gt;&gt;

* u18BD3.018: L&lt;&lt;-469.0,-886.0&gt;--&lt;-470.0,-1154.0&gt;&gt;

* u18BD3.019: L&lt;&lt;-1469.0,-1386.0&gt;--&lt;-1470.0,-1654.0&gt;&gt;

* u18BD3.020: L&lt;&lt;-969.0,-1386.0&gt;--&lt;-970.0,-1654.0&gt;&gt;

* u18BD3.021: L&lt;&lt;-469.0,-1386.0&gt;--&lt;-470.0,-1654.0&gt;&gt;

* u18BD3.022: L&lt;&lt;531.0,614.0&gt;--&lt;530.0,346.0&gt;&gt;

* u18BD3.023: L&lt;&lt;531.0,114.0&gt;--&lt;530.0,-154.0&gt;&gt;

* u18BD4 (U+18BD4): L&lt;&lt;269.0,281.0&gt;--&lt;268.0,148.0&gt;&gt;

* u18BD4.001: L&lt;&lt;269.0,1781.0&gt;--&lt;268.0,1648.0&gt;&gt;

* u18BD4.002: L&lt;&lt;769.0,1781.0&gt;--&lt;768.0,1648.0&gt;&gt;

* u18BD4.003: L&lt;&lt;-731.0,1781.0&gt;--&lt;-732.0,1648.0&gt;&gt;

* u18BD4.004: L&lt;&lt;269.0,1281.0&gt;--&lt;268.0,1148.0&gt;&gt;

* u18BD4.005: L&lt;&lt;769.0,1281.0&gt;--&lt;768.0,1148.0&gt;&gt;

* u18BD4.006: L&lt;&lt;-731.0,1281.0&gt;--&lt;-732.0,1148.0&gt;&gt;

* u18BD4.007: L&lt;&lt;-1731.0,781.0&gt;--&lt;-1732.0,648.0&gt;&gt;

* u18BD4.008: L&lt;&lt;769.0,781.0&gt;--&lt;768.0,648.0&gt;&gt;

* u18BD4.009: L&lt;&lt;-731.0,781.0&gt;--&lt;-732.0,648.0&gt;&gt;

* u18BD4.010: L&lt;&lt;-1731.0,281.0&gt;--&lt;-1732.0,148.0&gt;&gt;

* u18BD4.011: L&lt;&lt;769.0,281.0&gt;--&lt;768.0,148.0&gt;&gt;

* u18BD4.012: L&lt;&lt;-731.0,281.0&gt;--&lt;-732.0,148.0&gt;&gt;

* u18BD4.013: L&lt;&lt;-1731.0,-219.0&gt;--&lt;-1732.0,-352.0&gt;&gt;

* u18BD4.014: L&lt;&lt;-1231.0,-219.0&gt;--&lt;-1232.0,-352.0&gt;&gt;

* u18BD4.015: L&lt;&lt;-731.0,-219.0&gt;--&lt;-732.0,-352.0&gt;&gt;

* u18BD4.016: L&lt;&lt;-1731.0,-719.0&gt;--&lt;-1732.0,-852.0&gt;&gt;

* u18BD4.017: L&lt;&lt;-1231.0,-719.0&gt;--&lt;-1232.0,-852.0&gt;&gt;

* u18BD4.018: L&lt;&lt;-731.0,-719.0&gt;--&lt;-732.0,-852.0&gt;&gt;

* u18BD4.019: L&lt;&lt;-1731.0,-1219.0&gt;--&lt;-1732.0,-1352.0&gt;&gt;

* u18BD4.020: L&lt;&lt;-1231.0,-1219.0&gt;--&lt;-1232.0,-1352.0&gt;&gt;

* u18BD4.021: L&lt;&lt;-731.0,-1219.0&gt;--&lt;-732.0,-1352.0&gt;&gt;

* u18BD4.022: L&lt;&lt;269.0,781.0&gt;--&lt;268.0,648.0&gt;&gt;

* u18BD4.023: L&lt;&lt;269.0,281.0&gt;--&lt;268.0,148.0&gt;&gt;

* u18BD5 (U+18BD5): L&lt;&lt;284.0,345.0&gt;--&lt;285.0,208.0&gt;&gt;

* u18BD5.001: L&lt;&lt;284.0,1845.0&gt;--&lt;285.0,1708.0&gt;&gt;

* u18BD5.002: L&lt;&lt;784.0,1845.0&gt;--&lt;785.0,1708.0&gt;&gt;

* u18BD5.003: L&lt;&lt;-716.0,1845.0&gt;--&lt;-715.0,1708.0&gt;&gt;

* u18BD5.004: L&lt;&lt;284.0,1345.0&gt;--&lt;285.0,1208.0&gt;&gt;

* u18BD5.005: L&lt;&lt;784.0,1345.0&gt;--&lt;785.0,1208.0&gt;&gt;

* u18BD5.006: L&lt;&lt;-716.0,1345.0&gt;--&lt;-715.0,1208.0&gt;&gt;

* u18BD5.007: L&lt;&lt;-1716.0,845.0&gt;--&lt;-1715.0,708.0&gt;&gt;

* u18BD5.008: L&lt;&lt;784.0,845.0&gt;--&lt;785.0,708.0&gt;&gt;

* u18BD5.009: L&lt;&lt;-716.0,845.0&gt;--&lt;-715.0,708.0&gt;&gt;

* u18BD5.010: L&lt;&lt;-1716.0,345.0&gt;--&lt;-1715.0,208.0&gt;&gt;

* u18BD5.011: L&lt;&lt;784.0,345.0&gt;--&lt;785.0,208.0&gt;&gt;

* u18BD5.012: L&lt;&lt;-716.0,345.0&gt;--&lt;-715.0,208.0&gt;&gt;

* u18BD5.013: L&lt;&lt;-1716.0,-155.0&gt;--&lt;-1715.0,-292.0&gt;&gt;

* u18BD5.014: L&lt;&lt;-1216.0,-155.0&gt;--&lt;-1215.0,-292.0&gt;&gt;

* u18BD5.015: L&lt;&lt;-716.0,-155.0&gt;--&lt;-715.0,-292.0&gt;&gt;

* u18BD5.016: L&lt;&lt;-1716.0,-655.0&gt;--&lt;-1715.0,-792.0&gt;&gt;

* u18BD5.017: L&lt;&lt;-1216.0,-655.0&gt;--&lt;-1215.0,-792.0&gt;&gt;

* u18BD5.018: L&lt;&lt;-716.0,-655.0&gt;--&lt;-715.0,-792.0&gt;&gt;

* u18BD5.019: L&lt;&lt;-1716.0,-1155.0&gt;--&lt;-1715.0,-1292.0&gt;&gt;

* u18BD5.020: L&lt;&lt;-1216.0,-1155.0&gt;--&lt;-1215.0,-1292.0&gt;&gt;

* u18BD5.021: L&lt;&lt;-716.0,-1155.0&gt;--&lt;-715.0,-1292.0&gt;&gt;

* u18BD5.022: L&lt;&lt;284.0,845.0&gt;--&lt;285.0,708.0&gt;&gt;

* u18BD5.023: L&lt;&lt;284.0,345.0&gt;--&lt;285.0,208.0&gt;&gt;

* u18BD9 (U+18BD9): L&lt;&lt;784.0,207.0&gt;--&lt;783.0,49.0&gt;&gt;

* u18BD9.001: L&lt;&lt;784.0,1707.0&gt;--&lt;783.0,1549.0&gt;&gt;

* u18BD9.002: L&lt;&lt;1284.0,1707.0&gt;--&lt;1283.0,1549.0&gt;&gt;

* u18BD9.003: L&lt;&lt;-216.0,1707.0&gt;--&lt;-217.0,1549.0&gt;&gt;

* u18BD9.004: L&lt;&lt;784.0,1207.0&gt;--&lt;783.0,1049.0&gt;&gt;

* u18BD9.005: L&lt;&lt;1284.0,1207.0&gt;--&lt;1283.0,1049.0&gt;&gt;

* u18BD9.006: L&lt;&lt;-216.0,1207.0&gt;--&lt;-217.0,1049.0&gt;&gt;

* u18BD9.007: L&lt;&lt;-1216.0,707.0&gt;--&lt;-1217.0,549.0&gt;&gt;

* u18BD9.008: L&lt;&lt;1284.0,707.0&gt;--&lt;1283.0,549.0&gt;&gt;

* u18BD9.009: L&lt;&lt;-216.0,707.0&gt;--&lt;-217.0,549.0&gt;&gt;

* u18BD9.010: L&lt;&lt;-1216.0,207.0&gt;--&lt;-1217.0,49.0&gt;&gt;

* u18BD9.011: L&lt;&lt;1284.0,207.0&gt;--&lt;1283.0,49.0&gt;&gt;

* u18BD9.012: L&lt;&lt;-216.0,207.0&gt;--&lt;-217.0,49.0&gt;&gt;

* u18BD9.013: L&lt;&lt;-1216.0,-293.0&gt;--&lt;-1217.0,-451.0&gt;&gt;

* u18BD9.014: L&lt;&lt;-716.0,-293.0&gt;--&lt;-717.0,-451.0&gt;&gt;

* u18BD9.015: L&lt;&lt;-216.0,-293.0&gt;--&lt;-217.0,-451.0&gt;&gt;

* u18BD9.016: L&lt;&lt;-1216.0,-793.0&gt;--&lt;-1217.0,-951.0&gt;&gt;

* u18BD9.017: L&lt;&lt;-716.0,-793.0&gt;--&lt;-717.0,-951.0&gt;&gt;

* u18BD9.018: L&lt;&lt;-216.0,-793.0&gt;--&lt;-217.0,-951.0&gt;&gt;

* u18BD9.019: L&lt;&lt;-1216.0,-1293.0&gt;--&lt;-1217.0,-1451.0&gt;&gt;

* u18BD9.020: L&lt;&lt;-716.0,-1293.0&gt;--&lt;-717.0,-1451.0&gt;&gt;

* u18BD9.021: L&lt;&lt;-216.0,-1293.0&gt;--&lt;-217.0,-1451.0&gt;&gt;

* u18BD9.022: L&lt;&lt;784.0,707.0&gt;--&lt;783.0,549.0&gt;&gt;

* u18BD9.023: L&lt;&lt;784.0,207.0&gt;--&lt;783.0,49.0&gt;&gt;

* u18BDA (U+18BDA): L&lt;&lt;724.0,282.0&gt;--&lt;723.0,49.0&gt;&gt;

* u18BDA.001: L&lt;&lt;724.0,1782.0&gt;--&lt;723.0,1549.0&gt;&gt;

* u18BDA.002: L&lt;&lt;1224.0,1782.0&gt;--&lt;1223.0,1549.0&gt;&gt;

* u18BDA.003: L&lt;&lt;-276.0,1782.0&gt;--&lt;-277.0,1549.0&gt;&gt;

* u18BDA.004: L&lt;&lt;724.0,1282.0&gt;--&lt;723.0,1049.0&gt;&gt;

* u18BDA.005: L&lt;&lt;1224.0,1282.0&gt;--&lt;1223.0,1049.0&gt;&gt;

* u18BDA.006: L&lt;&lt;-276.0,1282.0&gt;--&lt;-277.0,1049.0&gt;&gt;

* u18BDA.007: L&lt;&lt;-1276.0,782.0&gt;--&lt;-1277.0,549.0&gt;&gt;

* u18BDA.008: L&lt;&lt;1224.0,782.0&gt;--&lt;1223.0,549.0&gt;&gt;

* u18BDA.009: L&lt;&lt;-276.0,782.0&gt;--&lt;-277.0,549.0&gt;&gt;

* u18BDA.010: L&lt;&lt;-1276.0,282.0&gt;--&lt;-1277.0,49.0&gt;&gt;

* u18BDA.011: L&lt;&lt;1224.0,282.0&gt;--&lt;1223.0,49.0&gt;&gt;

* u18BDA.012: L&lt;&lt;-276.0,282.0&gt;--&lt;-277.0,49.0&gt;&gt;

* u18BDA.013: L&lt;&lt;-1276.0,-218.0&gt;--&lt;-1277.0,-451.0&gt;&gt;

* u18BDA.014: L&lt;&lt;-776.0,-218.0&gt;--&lt;-777.0,-451.0&gt;&gt;

* u18BDA.015: L&lt;&lt;-276.0,-218.0&gt;--&lt;-277.0,-451.0&gt;&gt;

* u18BDA.016: L&lt;&lt;-1276.0,-718.0&gt;--&lt;-1277.0,-951.0&gt;&gt;

* u18BDA.017: L&lt;&lt;-776.0,-718.0&gt;--&lt;-777.0,-951.0&gt;&gt;

* u18BDA.018: L&lt;&lt;-276.0,-718.0&gt;--&lt;-277.0,-951.0&gt;&gt;

* u18BDA.019: L&lt;&lt;-1276.0,-1218.0&gt;--&lt;-1277.0,-1451.0&gt;&gt;

* u18BDA.020: L&lt;&lt;-776.0,-1218.0&gt;--&lt;-777.0,-1451.0&gt;&gt;

* u18BDA.021: L&lt;&lt;-276.0,-1218.0&gt;--&lt;-277.0,-1451.0&gt;&gt;

* u18BDA.022: L&lt;&lt;724.0,782.0&gt;--&lt;723.0,549.0&gt;&gt;

* u18BDA.023: L&lt;&lt;724.0,282.0&gt;--&lt;723.0,49.0&gt;&gt;

* u18C0E (U+18C0E): L&lt;&lt;565.0,547.0&gt;--&lt;564.0,394.0&gt;&gt;

* u18C0E.001: L&lt;&lt;565.0,2047.0&gt;--&lt;564.0,1894.0&gt;&gt;

* u18C0E.002: L&lt;&lt;1065.0,2047.0&gt;--&lt;1064.0,1894.0&gt;&gt;

* u18C0E.003: L&lt;&lt;-435.0,2047.0&gt;--&lt;-436.0,1894.0&gt;&gt;

* u18C0E.004: L&lt;&lt;565.0,1547.0&gt;--&lt;564.0,1394.0&gt;&gt;

* u18C0E.005: L&lt;&lt;1065.0,1547.0&gt;--&lt;1064.0,1394.0&gt;&gt;

* u18C0E.006: L&lt;&lt;-435.0,1547.0&gt;--&lt;-436.0,1394.0&gt;&gt;

* u18C0E.007: L&lt;&lt;-1435.0,1047.0&gt;--&lt;-1436.0,894.0&gt;&gt;

* u18C0E.008: L&lt;&lt;1065.0,1047.0&gt;--&lt;1064.0,894.0&gt;&gt;

* u18C0E.009: L&lt;&lt;-435.0,1047.0&gt;--&lt;-436.0,894.0&gt;&gt;

* u18C0E.010: L&lt;&lt;-1435.0,547.0&gt;--&lt;-1436.0,394.0&gt;&gt;

* u18C0E.011: L&lt;&lt;1065.0,547.0&gt;--&lt;1064.0,394.0&gt;&gt;

* u18C0E.012: L&lt;&lt;-435.0,547.0&gt;--&lt;-436.0,394.0&gt;&gt;

* u18C0E.013: L&lt;&lt;-1435.0,47.0&gt;--&lt;-1436.0,-106.0&gt;&gt;

* u18C0E.014: L&lt;&lt;-935.0,47.0&gt;--&lt;-936.0,-106.0&gt;&gt;

* u18C0E.015: L&lt;&lt;-435.0,47.0&gt;--&lt;-436.0,-106.0&gt;&gt;

* u18C0E.016: L&lt;&lt;-1435.0,-453.0&gt;--&lt;-1436.0,-606.0&gt;&gt;

* u18C0E.017: L&lt;&lt;-935.0,-453.0&gt;--&lt;-936.0,-606.0&gt;&gt;

* u18C0E.018: L&lt;&lt;-435.0,-453.0&gt;--&lt;-436.0,-606.0&gt;&gt;

* u18C0E.019: L&lt;&lt;-1435.0,-953.0&gt;--&lt;-1436.0,-1106.0&gt;&gt;

* u18C0E.020: L&lt;&lt;-935.0,-953.0&gt;--&lt;-936.0,-1106.0&gt;&gt;

* u18C0E.021: L&lt;&lt;-435.0,-953.0&gt;--&lt;-436.0,-1106.0&gt;&gt;

* u18C0E.022: L&lt;&lt;565.0,1047.0&gt;--&lt;564.0,894.0&gt;&gt;

* u18C0E.023: L&lt;&lt;565.0,547.0&gt;--&lt;564.0,394.0&gt;&gt;

* u18C60 (U+18C60): L&lt;&lt;447.0,23.0&gt;--&lt;448.0,173.0&gt;&gt;

* u18C60 (U+18C60): L&lt;&lt;448.0,173.0&gt;--&lt;447.0,325.0&gt;&gt;

* u18C60.001: L&lt;&lt;447.0,1523.0&gt;--&lt;448.0,1673.0&gt;&gt;

* u18C60.001: L&lt;&lt;448.0,1673.0&gt;--&lt;447.0,1825.0&gt;&gt;

* u18C60.002: L&lt;&lt;947.0,1523.0&gt;--&lt;948.0,1673.0&gt;&gt;

* u18C60.002: L&lt;&lt;948.0,1673.0&gt;--&lt;947.0,1825.0&gt;&gt;

* u18C60.003: L&lt;&lt;-552.0,1673.0&gt;--&lt;-553.0,1825.0&gt;&gt;

* u18C60.003: L&lt;&lt;-553.0,1523.0&gt;--&lt;-552.0,1673.0&gt;&gt;

* u18C60.004: L&lt;&lt;447.0,1023.0&gt;--&lt;448.0,1173.0&gt;&gt;

* u18C60.004: L&lt;&lt;448.0,1173.0&gt;--&lt;447.0,1325.0&gt;&gt;

* u18C60.005: L&lt;&lt;947.0,1023.0&gt;--&lt;948.0,1173.0&gt;&gt;

* u18C60.005: L&lt;&lt;948.0,1173.0&gt;--&lt;947.0,1325.0&gt;&gt;

* u18C60.006: L&lt;&lt;-552.0,1173.0&gt;--&lt;-553.0,1325.0&gt;&gt;

* u18C60.006: L&lt;&lt;-553.0,1023.0&gt;--&lt;-552.0,1173.0&gt;&gt;

* u18C60.007: L&lt;&lt;-1552.0,673.0&gt;--&lt;-1553.0,825.0&gt;&gt;

* u18C60.007: L&lt;&lt;-1553.0,523.0&gt;--&lt;-1552.0,673.0&gt;&gt;

* u18C60.008: L&lt;&lt;947.0,523.0&gt;--&lt;948.0,673.0&gt;&gt;

* u18C60.008: L&lt;&lt;948.0,673.0&gt;--&lt;947.0,825.0&gt;&gt;

* u18C60.009: L&lt;&lt;-552.0,673.0&gt;--&lt;-553.0,825.0&gt;&gt;

* u18C60.009: L&lt;&lt;-553.0,523.0&gt;--&lt;-552.0,673.0&gt;&gt;

* u18C60.010: L&lt;&lt;-1552.0,173.0&gt;--&lt;-1553.0,325.0&gt;&gt;

* u18C60.010: L&lt;&lt;-1553.0,23.0&gt;--&lt;-1552.0,173.0&gt;&gt;

* u18C60.011: L&lt;&lt;947.0,23.0&gt;--&lt;948.0,173.0&gt;&gt;

* u18C60.011: L&lt;&lt;948.0,173.0&gt;--&lt;947.0,325.0&gt;&gt;

* u18C60.012: L&lt;&lt;-552.0,173.0&gt;--&lt;-553.0,325.0&gt;&gt;

* u18C60.012: L&lt;&lt;-553.0,23.0&gt;--&lt;-552.0,173.0&gt;&gt;

* u18C60.013: L&lt;&lt;-1552.0,-327.0&gt;--&lt;-1553.0,-175.0&gt;&gt;

* u18C60.013: L&lt;&lt;-1553.0,-477.0&gt;--&lt;-1552.0,-327.0&gt;&gt;

* u18C60.014: L&lt;&lt;-1052.0,-327.0&gt;--&lt;-1053.0,-175.0&gt;&gt;

* u18C60.014: L&lt;&lt;-1053.0,-477.0&gt;--&lt;-1052.0,-327.0&gt;&gt;

* u18C60.015: L&lt;&lt;-552.0,-327.0&gt;--&lt;-553.0,-175.0&gt;&gt;

* u18C60.015: L&lt;&lt;-553.0,-477.0&gt;--&lt;-552.0,-327.0&gt;&gt;

* u18C60.016: L&lt;&lt;-1552.0,-827.0&gt;--&lt;-1553.0,-675.0&gt;&gt;

* u18C60.016: L&lt;&lt;-1553.0,-977.0&gt;--&lt;-1552.0,-827.0&gt;&gt;

* u18C60.017: L&lt;&lt;-1052.0,-827.0&gt;--&lt;-1053.0,-675.0&gt;&gt;

* u18C60.017: L&lt;&lt;-1053.0,-977.0&gt;--&lt;-1052.0,-827.0&gt;&gt;

* u18C60.018: L&lt;&lt;-552.0,-827.0&gt;--&lt;-553.0,-675.0&gt;&gt;

* u18C60.018: L&lt;&lt;-553.0,-977.0&gt;--&lt;-552.0,-827.0&gt;&gt;

* u18C60.019: L&lt;&lt;-1552.0,-1327.0&gt;--&lt;-1553.0,-1175.0&gt;&gt;

* u18C60.019: L&lt;&lt;-1553.0,-1477.0&gt;--&lt;-1552.0,-1327.0&gt;&gt;

* u18C60.020: L&lt;&lt;-1052.0,-1327.0&gt;--&lt;-1053.0,-1175.0&gt;&gt;

* u18C60.020: L&lt;&lt;-1053.0,-1477.0&gt;--&lt;-1052.0,-1327.0&gt;&gt;

* u18C60.021: L&lt;&lt;-552.0,-1327.0&gt;--&lt;-553.0,-1175.0&gt;&gt;

* u18C60.021: L&lt;&lt;-553.0,-1477.0&gt;--&lt;-552.0,-1327.0&gt;&gt;

* u18C60.022: L&lt;&lt;447.0,523.0&gt;--&lt;448.0,673.0&gt;&gt;

* u18C60.022: L&lt;&lt;448.0,673.0&gt;--&lt;447.0,825.0&gt;&gt;

* u18C60.023: L&lt;&lt;447.0,23.0&gt;--&lt;448.0,173.0&gt;&gt;

* u18C60.023: L&lt;&lt;448.0,173.0&gt;--&lt;447.0,325.0&gt;&gt;

* u18C67 (U+18C67): L&lt;&lt;210.0,17.0&gt;--&lt;211.0,163.0&gt;&gt;

* u18C67 (U+18C67): L&lt;&lt;211.0,163.0&gt;--&lt;210.0,312.0&gt;&gt;

* u18C67 (U+18C67): L&lt;&lt;824.0,135.0&gt;--&lt;825.0,-18.0&gt;&gt;

* u18C67.001: L&lt;&lt;210.0,1517.0&gt;--&lt;211.0,1663.0&gt;&gt;

* u18C67.001: L&lt;&lt;211.0,1663.0&gt;--&lt;210.0,1812.0&gt;&gt;

* u18C67.001: L&lt;&lt;824.0,1635.0&gt;--&lt;825.0,1482.0&gt;&gt;

* u18C67.002: L&lt;&lt;1324.0,1635.0&gt;--&lt;1325.0,1482.0&gt;&gt;

* u18C67.002: L&lt;&lt;710.0,1517.0&gt;--&lt;711.0,1663.0&gt;&gt;

* u18C67.002: L&lt;&lt;711.0,1663.0&gt;--&lt;710.0,1812.0&gt;&gt;

* u18C67.003: L&lt;&lt;-176.0,1635.0&gt;--&lt;-175.0,1482.0&gt;&gt;

* u18C67.003: L&lt;&lt;-789.0,1663.0&gt;--&lt;-790.0,1812.0&gt;&gt;

* u18C67.003: L&lt;&lt;-790.0,1517.0&gt;--&lt;-789.0,1663.0&gt;&gt;

* u18C67.004: L&lt;&lt;210.0,1017.0&gt;--&lt;211.0,1163.0&gt;&gt;

* u18C67.004: L&lt;&lt;211.0,1163.0&gt;--&lt;210.0,1312.0&gt;&gt;

* u18C67.004: L&lt;&lt;824.0,1135.0&gt;--&lt;825.0,982.0&gt;&gt;

* u18C67.005: L&lt;&lt;1324.0,1135.0&gt;--&lt;1325.0,982.0&gt;&gt;

* u18C67.005: L&lt;&lt;710.0,1017.0&gt;--&lt;711.0,1163.0&gt;&gt;

* u18C67.005: L&lt;&lt;711.0,1163.0&gt;--&lt;710.0,1312.0&gt;&gt;

* u18C67.006: L&lt;&lt;-176.0,1135.0&gt;--&lt;-175.0,982.0&gt;&gt;

* u18C67.006: L&lt;&lt;-789.0,1163.0&gt;--&lt;-790.0,1312.0&gt;&gt;

* u18C67.006: L&lt;&lt;-790.0,1017.0&gt;--&lt;-789.0,1163.0&gt;&gt;

* u18C67.007: L&lt;&lt;-1176.0,635.0&gt;--&lt;-1175.0,482.0&gt;&gt;

* u18C67.007: L&lt;&lt;-1789.0,663.0&gt;--&lt;-1790.0,812.0&gt;&gt;

* u18C67.007: L&lt;&lt;-1790.0,517.0&gt;--&lt;-1789.0,663.0&gt;&gt;

* u18C67.008: L&lt;&lt;1324.0,635.0&gt;--&lt;1325.0,482.0&gt;&gt;

* u18C67.008: L&lt;&lt;710.0,517.0&gt;--&lt;711.0,663.0&gt;&gt;

* u18C67.008: L&lt;&lt;711.0,663.0&gt;--&lt;710.0,812.0&gt;&gt;

* u18C67.009: L&lt;&lt;-176.0,635.0&gt;--&lt;-175.0,482.0&gt;&gt;

* u18C67.009: L&lt;&lt;-789.0,663.0&gt;--&lt;-790.0,812.0&gt;&gt;

* u18C67.009: L&lt;&lt;-790.0,517.0&gt;--&lt;-789.0,663.0&gt;&gt;

* u18C67.010: L&lt;&lt;-1176.0,135.0&gt;--&lt;-1175.0,-18.0&gt;&gt;

* u18C67.010: L&lt;&lt;-1789.0,163.0&gt;--&lt;-1790.0,312.0&gt;&gt;

* u18C67.010: L&lt;&lt;-1790.0,17.0&gt;--&lt;-1789.0,163.0&gt;&gt;

* u18C67.011: L&lt;&lt;1324.0,135.0&gt;--&lt;1325.0,-18.0&gt;&gt;

* u18C67.011: L&lt;&lt;710.0,17.0&gt;--&lt;711.0,163.0&gt;&gt;

* u18C67.011: L&lt;&lt;711.0,163.0&gt;--&lt;710.0,312.0&gt;&gt;

* u18C67.012: L&lt;&lt;-176.0,135.0&gt;--&lt;-175.0,-18.0&gt;&gt;

* u18C67.012: L&lt;&lt;-789.0,163.0&gt;--&lt;-790.0,312.0&gt;&gt;

* u18C67.012: L&lt;&lt;-790.0,17.0&gt;--&lt;-789.0,163.0&gt;&gt;

* u18C67.013: L&lt;&lt;-1176.0,-365.0&gt;--&lt;-1175.0,-518.0&gt;&gt;

* u18C67.013: L&lt;&lt;-1789.0,-337.0&gt;--&lt;-1790.0,-188.0&gt;&gt;

* u18C67.013: L&lt;&lt;-1790.0,-483.0&gt;--&lt;-1789.0,-337.0&gt;&gt;

* u18C67.014: L&lt;&lt;-1289.0,-337.0&gt;--&lt;-1290.0,-188.0&gt;&gt;

* u18C67.014: L&lt;&lt;-1290.0,-483.0&gt;--&lt;-1289.0,-337.0&gt;&gt;

* u18C67.014: L&lt;&lt;-676.0,-365.0&gt;--&lt;-675.0,-518.0&gt;&gt;

* u18C67.015: L&lt;&lt;-176.0,-365.0&gt;--&lt;-175.0,-518.0&gt;&gt;

* u18C67.015: L&lt;&lt;-789.0,-337.0&gt;--&lt;-790.0,-188.0&gt;&gt;

* u18C67.015: L&lt;&lt;-790.0,-483.0&gt;--&lt;-789.0,-337.0&gt;&gt;

* u18C67.016: L&lt;&lt;-1176.0,-865.0&gt;--&lt;-1175.0,-1018.0&gt;&gt;

* u18C67.016: L&lt;&lt;-1789.0,-837.0&gt;--&lt;-1790.0,-688.0&gt;&gt;

* u18C67.016: L&lt;&lt;-1790.0,-983.0&gt;--&lt;-1789.0,-837.0&gt;&gt;

* u18C67.017: L&lt;&lt;-1289.0,-837.0&gt;--&lt;-1290.0,-688.0&gt;&gt;

* u18C67.017: L&lt;&lt;-1290.0,-983.0&gt;--&lt;-1289.0,-837.0&gt;&gt;

* u18C67.017: L&lt;&lt;-676.0,-865.0&gt;--&lt;-675.0,-1018.0&gt;&gt;

* u18C67.018: L&lt;&lt;-176.0,-865.0&gt;--&lt;-175.0,-1018.0&gt;&gt;

* u18C67.018: L&lt;&lt;-789.0,-837.0&gt;--&lt;-790.0,-688.0&gt;&gt;

* u18C67.018: L&lt;&lt;-790.0,-983.0&gt;--&lt;-789.0,-837.0&gt;&gt;

* u18C67.019: L&lt;&lt;-1176.0,-1365.0&gt;--&lt;-1175.0,-1518.0&gt;&gt;

* u18C67.019: L&lt;&lt;-1789.0,-1337.0&gt;--&lt;-1790.0,-1188.0&gt;&gt;

* u18C67.019: L&lt;&lt;-1790.0,-1483.0&gt;--&lt;-1789.0,-1337.0&gt;&gt;

* u18C67.020: L&lt;&lt;-1289.0,-1337.0&gt;--&lt;-1290.0,-1188.0&gt;&gt;

* u18C67.020: L&lt;&lt;-1290.0,-1483.0&gt;--&lt;-1289.0,-1337.0&gt;&gt;

* u18C67.020: L&lt;&lt;-676.0,-1365.0&gt;--&lt;-675.0,-1518.0&gt;&gt;

* u18C67.021: L&lt;&lt;-176.0,-1365.0&gt;--&lt;-175.0,-1518.0&gt;&gt;

* u18C67.021: L&lt;&lt;-789.0,-1337.0&gt;--&lt;-790.0,-1188.0&gt;&gt;

* u18C67.021: L&lt;&lt;-790.0,-1483.0&gt;--&lt;-789.0,-1337.0&gt;&gt;

* u18C67.022: L&lt;&lt;210.0,517.0&gt;--&lt;211.0,663.0&gt;&gt;

* u18C67.022: L&lt;&lt;211.0,663.0&gt;--&lt;210.0,812.0&gt;&gt;

* u18C67.022: L&lt;&lt;824.0,635.0&gt;--&lt;825.0,482.0&gt;&gt;

* u18C67.023: L&lt;&lt;210.0,17.0&gt;--&lt;211.0,163.0&gt;&gt;

* u18C67.023: L&lt;&lt;211.0,163.0&gt;--&lt;210.0,312.0&gt;&gt;

* u18C67.023: L&lt;&lt;824.0,135.0&gt;--&lt;825.0,-18.0&gt;&gt;

* u18C81 (U+18C81): L&lt;&lt;554.0,272.0&gt;--&lt;553.0,-20.0&gt;&gt;

* u18C81.001: L&lt;&lt;554.0,1772.0&gt;--&lt;553.0,1480.0&gt;&gt;

* u18C81.002: L&lt;&lt;1054.0,1772.0&gt;--&lt;1053.0,1480.0&gt;&gt;

* u18C81.003: L&lt;&lt;-446.0,1772.0&gt;--&lt;-447.0,1480.0&gt;&gt;

* u18C81.004: L&lt;&lt;554.0,1272.0&gt;--&lt;553.0,980.0&gt;&gt;

* u18C81.005: L&lt;&lt;1054.0,1272.0&gt;--&lt;1053.0,980.0&gt;&gt;

* u18C81.006: L&lt;&lt;-446.0,1272.0&gt;--&lt;-447.0,980.0&gt;&gt;

* u18C81.007: L&lt;&lt;-1446.0,772.0&gt;--&lt;-1447.0,480.0&gt;&gt;

* u18C81.008: L&lt;&lt;1054.0,772.0&gt;--&lt;1053.0,480.0&gt;&gt;

* u18C81.009: L&lt;&lt;-446.0,772.0&gt;--&lt;-447.0,480.0&gt;&gt;

* u18C81.010: L&lt;&lt;-1446.0,272.0&gt;--&lt;-1447.0,-20.0&gt;&gt;

* u18C81.011: L&lt;&lt;1054.0,272.0&gt;--&lt;1053.0,-20.0&gt;&gt;

* u18C81.012: L&lt;&lt;-446.0,272.0&gt;--&lt;-447.0,-20.0&gt;&gt;

* u18C81.013: L&lt;&lt;-1446.0,-228.0&gt;--&lt;-1447.0,-520.0&gt;&gt;

* u18C81.014: L&lt;&lt;-946.0,-228.0&gt;--&lt;-947.0,-520.0&gt;&gt;

* u18C81.015: L&lt;&lt;-446.0,-228.0&gt;--&lt;-447.0,-520.0&gt;&gt;

* u18C81.016: L&lt;&lt;-1446.0,-728.0&gt;--&lt;-1447.0,-1020.0&gt;&gt;

* u18C81.017: L&lt;&lt;-946.0,-728.0&gt;--&lt;-947.0,-1020.0&gt;&gt;

* u18C81.018: L&lt;&lt;-446.0,-728.0&gt;--&lt;-447.0,-1020.0&gt;&gt;

* u18C81.019: L&lt;&lt;-1446.0,-1228.0&gt;--&lt;-1447.0,-1520.0&gt;&gt;

* u18C81.020: L&lt;&lt;-946.0,-1228.0&gt;--&lt;-947.0,-1520.0&gt;&gt;

* u18C81.021: L&lt;&lt;-446.0,-1228.0&gt;--&lt;-447.0,-1520.0&gt;&gt;

* u18C81.022: L&lt;&lt;554.0,772.0&gt;--&lt;553.0,480.0&gt;&gt;

* u18C81.023: L&lt;&lt;554.0,272.0&gt;--&lt;553.0,-20.0&gt;&gt;

* u18C89 (U+18C89): L&lt;&lt;146.0,20.0&gt;--&lt;147.0,169.0&gt;&gt;

* u18C89 (U+18C89): L&lt;&lt;147.0,169.0&gt;--&lt;146.0,319.0&gt;&gt;

* u18C89 (U+18C89): L&lt;&lt;854.0,145.0&gt;--&lt;855.0,-11.0&gt;&gt;

* u18C89.001: L&lt;&lt;146.0,1520.0&gt;--&lt;147.0,1669.0&gt;&gt;

* u18C89.001: L&lt;&lt;147.0,1669.0&gt;--&lt;146.0,1819.0&gt;&gt;

* u18C89.001: L&lt;&lt;854.0,1645.0&gt;--&lt;855.0,1489.0&gt;&gt;

* u18C89.002: L&lt;&lt;1354.0,1645.0&gt;--&lt;1355.0,1489.0&gt;&gt;

* u18C89.002: L&lt;&lt;646.0,1520.0&gt;--&lt;647.0,1669.0&gt;&gt;

* u18C89.002: L&lt;&lt;647.0,1669.0&gt;--&lt;646.0,1819.0&gt;&gt;

* u18C89.003: L&lt;&lt;-146.0,1645.0&gt;--&lt;-145.0,1489.0&gt;&gt;

* u18C89.003: L&lt;&lt;-853.0,1669.0&gt;--&lt;-854.0,1819.0&gt;&gt;

* u18C89.003: L&lt;&lt;-854.0,1520.0&gt;--&lt;-853.0,1669.0&gt;&gt;

* u18C89.004: L&lt;&lt;146.0,1020.0&gt;--&lt;147.0,1169.0&gt;&gt;

* u18C89.004: L&lt;&lt;147.0,1169.0&gt;--&lt;146.0,1319.0&gt;&gt;

* u18C89.004: L&lt;&lt;854.0,1145.0&gt;--&lt;855.0,989.0&gt;&gt;

* u18C89.005: L&lt;&lt;1354.0,1145.0&gt;--&lt;1355.0,989.0&gt;&gt;

* u18C89.005: L&lt;&lt;646.0,1020.0&gt;--&lt;647.0,1169.0&gt;&gt;

* u18C89.005: L&lt;&lt;647.0,1169.0&gt;--&lt;646.0,1319.0&gt;&gt;

* u18C89.006: L&lt;&lt;-146.0,1145.0&gt;--&lt;-145.0,989.0&gt;&gt;

* u18C89.006: L&lt;&lt;-853.0,1169.0&gt;--&lt;-854.0,1319.0&gt;&gt;

* u18C89.006: L&lt;&lt;-854.0,1020.0&gt;--&lt;-853.0,1169.0&gt;&gt;

* u18C89.007: L&lt;&lt;-1146.0,645.0&gt;--&lt;-1145.0,489.0&gt;&gt;

* u18C89.007: L&lt;&lt;-1853.0,669.0&gt;--&lt;-1854.0,819.0&gt;&gt;

* u18C89.007: L&lt;&lt;-1854.0,520.0&gt;--&lt;-1853.0,669.0&gt;&gt;

* u18C89.008: L&lt;&lt;1354.0,645.0&gt;--&lt;1355.0,489.0&gt;&gt;

* u18C89.008: L&lt;&lt;646.0,520.0&gt;--&lt;647.0,669.0&gt;&gt;

* u18C89.008: L&lt;&lt;647.0,669.0&gt;--&lt;646.0,819.0&gt;&gt;

* u18C89.009: L&lt;&lt;-146.0,645.0&gt;--&lt;-145.0,489.0&gt;&gt;

* u18C89.009: L&lt;&lt;-853.0,669.0&gt;--&lt;-854.0,819.0&gt;&gt;

* u18C89.009: L&lt;&lt;-854.0,520.0&gt;--&lt;-853.0,669.0&gt;&gt;

* u18C89.010: L&lt;&lt;-1146.0,145.0&gt;--&lt;-1145.0,-11.0&gt;&gt;

* u18C89.010: L&lt;&lt;-1853.0,169.0&gt;--&lt;-1854.0,319.0&gt;&gt;

* u18C89.010: L&lt;&lt;-1854.0,20.0&gt;--&lt;-1853.0,169.0&gt;&gt;

* u18C89.011: L&lt;&lt;1354.0,145.0&gt;--&lt;1355.0,-11.0&gt;&gt;

* u18C89.011: L&lt;&lt;646.0,20.0&gt;--&lt;647.0,169.0&gt;&gt;

* u18C89.011: L&lt;&lt;647.0,169.0&gt;--&lt;646.0,319.0&gt;&gt;

* u18C89.012: L&lt;&lt;-146.0,145.0&gt;--&lt;-145.0,-11.0&gt;&gt;

* u18C89.012: L&lt;&lt;-853.0,169.0&gt;--&lt;-854.0,319.0&gt;&gt;

* u18C89.012: L&lt;&lt;-854.0,20.0&gt;--&lt;-853.0,169.0&gt;&gt;

* u18C89.013: L&lt;&lt;-1146.0,-355.0&gt;--&lt;-1145.0,-511.0&gt;&gt;

* u18C89.013: L&lt;&lt;-1853.0,-331.0&gt;--&lt;-1854.0,-181.0&gt;&gt;

* u18C89.013: L&lt;&lt;-1854.0,-480.0&gt;--&lt;-1853.0,-331.0&gt;&gt;

* u18C89.014: L&lt;&lt;-1353.0,-331.0&gt;--&lt;-1354.0,-181.0&gt;&gt;

* u18C89.014: L&lt;&lt;-1354.0,-480.0&gt;--&lt;-1353.0,-331.0&gt;&gt;

* u18C89.014: L&lt;&lt;-646.0,-355.0&gt;--&lt;-645.0,-511.0&gt;&gt;

* u18C89.015: L&lt;&lt;-146.0,-355.0&gt;--&lt;-145.0,-511.0&gt;&gt;

* u18C89.015: L&lt;&lt;-853.0,-331.0&gt;--&lt;-854.0,-181.0&gt;&gt;

* u18C89.015: L&lt;&lt;-854.0,-480.0&gt;--&lt;-853.0,-331.0&gt;&gt;

* u18C89.016: L&lt;&lt;-1146.0,-855.0&gt;--&lt;-1145.0,-1011.0&gt;&gt;

* u18C89.016: L&lt;&lt;-1853.0,-831.0&gt;--&lt;-1854.0,-681.0&gt;&gt;

* u18C89.016: L&lt;&lt;-1854.0,-980.0&gt;--&lt;-1853.0,-831.0&gt;&gt;

* u18C89.017: L&lt;&lt;-1353.0,-831.0&gt;--&lt;-1354.0,-681.0&gt;&gt;

* u18C89.017: L&lt;&lt;-1354.0,-980.0&gt;--&lt;-1353.0,-831.0&gt;&gt;

* u18C89.017: L&lt;&lt;-646.0,-855.0&gt;--&lt;-645.0,-1011.0&gt;&gt;

* u18C89.018: L&lt;&lt;-146.0,-855.0&gt;--&lt;-145.0,-1011.0&gt;&gt;

* u18C89.018: L&lt;&lt;-853.0,-831.0&gt;--&lt;-854.0,-681.0&gt;&gt;

* u18C89.018: L&lt;&lt;-854.0,-980.0&gt;--&lt;-853.0,-831.0&gt;&gt;

* u18C89.019: L&lt;&lt;-1146.0,-1355.0&gt;--&lt;-1145.0,-1511.0&gt;&gt;

* u18C89.019: L&lt;&lt;-1853.0,-1331.0&gt;--&lt;-1854.0,-1181.0&gt;&gt;

* u18C89.019: L&lt;&lt;-1854.0,-1480.0&gt;--&lt;-1853.0,-1331.0&gt;&gt;

* u18C89.020: L&lt;&lt;-1353.0,-1331.0&gt;--&lt;-1354.0,-1181.0&gt;&gt;

* u18C89.020: L&lt;&lt;-1354.0,-1480.0&gt;--&lt;-1353.0,-1331.0&gt;&gt;

* u18C89.020: L&lt;&lt;-646.0,-1355.0&gt;--&lt;-645.0,-1511.0&gt;&gt;

* u18C89.021: L&lt;&lt;-146.0,-1355.0&gt;--&lt;-145.0,-1511.0&gt;&gt;

* u18C89.021: L&lt;&lt;-853.0,-1331.0&gt;--&lt;-854.0,-1181.0&gt;&gt;

* u18C89.021: L&lt;&lt;-854.0,-1480.0&gt;--&lt;-853.0,-1331.0&gt;&gt;

* u18C89.022: L&lt;&lt;146.0,520.0&gt;--&lt;147.0,669.0&gt;&gt;

* u18C89.022: L&lt;&lt;147.0,669.0&gt;--&lt;146.0,819.0&gt;&gt;

* u18C89.022: L&lt;&lt;854.0,645.0&gt;--&lt;855.0,489.0&gt;&gt;

* u18C89.023: L&lt;&lt;146.0,20.0&gt;--&lt;147.0,169.0&gt;&gt;

* u18C89.023: L&lt;&lt;147.0,169.0&gt;--&lt;146.0,319.0&gt;&gt;

* u18C89.023: L&lt;&lt;854.0,145.0&gt;--&lt;855.0,-11.0&gt;&gt;

* u18C8B (U+18C8B): L&lt;&lt;463.0,67.0&gt;--&lt;464.0,214.0&gt;&gt;

* u18C8B (U+18C8B): L&lt;&lt;525.0,218.0&gt;--&lt;524.0,-21.0&gt;&gt;

* u18C8B.001: L&lt;&lt;463.0,1567.0&gt;--&lt;464.0,1714.0&gt;&gt;

* u18C8B.001: L&lt;&lt;525.0,1718.0&gt;--&lt;524.0,1479.0&gt;&gt;

* u18C8B.002: L&lt;&lt;1025.0,1718.0&gt;--&lt;1024.0,1479.0&gt;&gt;

* u18C8B.002: L&lt;&lt;963.0,1567.0&gt;--&lt;964.0,1714.0&gt;&gt;

* u18C8B.003: L&lt;&lt;-475.0,1718.0&gt;--&lt;-476.0,1479.0&gt;&gt;

* u18C8B.003: L&lt;&lt;-537.0,1567.0&gt;--&lt;-536.0,1714.0&gt;&gt;

* u18C8B.004: L&lt;&lt;463.0,1067.0&gt;--&lt;464.0,1214.0&gt;&gt;

* u18C8B.004: L&lt;&lt;525.0,1218.0&gt;--&lt;524.0,979.0&gt;&gt;

* u18C8B.005: L&lt;&lt;1025.0,1218.0&gt;--&lt;1024.0,979.0&gt;&gt;

* u18C8B.005: L&lt;&lt;963.0,1067.0&gt;--&lt;964.0,1214.0&gt;&gt;

* u18C8B.006: L&lt;&lt;-475.0,1218.0&gt;--&lt;-476.0,979.0&gt;&gt;

* u18C8B.006: L&lt;&lt;-537.0,1067.0&gt;--&lt;-536.0,1214.0&gt;&gt;

* u18C8B.007: L&lt;&lt;-1475.0,718.0&gt;--&lt;-1476.0,479.0&gt;&gt;

* u18C8B.007: L&lt;&lt;-1537.0,567.0&gt;--&lt;-1536.0,714.0&gt;&gt;

* u18C8B.008: L&lt;&lt;1025.0,718.0&gt;--&lt;1024.0,479.0&gt;&gt;

* u18C8B.008: L&lt;&lt;963.0,567.0&gt;--&lt;964.0,714.0&gt;&gt;

* u18C8B.009: L&lt;&lt;-475.0,718.0&gt;--&lt;-476.0,479.0&gt;&gt;

* u18C8B.009: L&lt;&lt;-537.0,567.0&gt;--&lt;-536.0,714.0&gt;&gt;

* u18C8B.010: L&lt;&lt;-1475.0,218.0&gt;--&lt;-1476.0,-21.0&gt;&gt;

* u18C8B.010: L&lt;&lt;-1537.0,67.0&gt;--&lt;-1536.0,214.0&gt;&gt;

* u18C8B.011: L&lt;&lt;1025.0,218.0&gt;--&lt;1024.0,-21.0&gt;&gt;

* u18C8B.011: L&lt;&lt;963.0,67.0&gt;--&lt;964.0,214.0&gt;&gt;

* u18C8B.012: L&lt;&lt;-475.0,218.0&gt;--&lt;-476.0,-21.0&gt;&gt;

* u18C8B.012: L&lt;&lt;-537.0,67.0&gt;--&lt;-536.0,214.0&gt;&gt;

* u18C8B.013: L&lt;&lt;-1475.0,-282.0&gt;--&lt;-1476.0,-521.0&gt;&gt;

* u18C8B.013: L&lt;&lt;-1537.0,-433.0&gt;--&lt;-1536.0,-286.0&gt;&gt;

* u18C8B.014: L&lt;&lt;-1037.0,-433.0&gt;--&lt;-1036.0,-286.0&gt;&gt;

* u18C8B.014: L&lt;&lt;-975.0,-282.0&gt;--&lt;-976.0,-521.0&gt;&gt;

* u18C8B.015: L&lt;&lt;-475.0,-282.0&gt;--&lt;-476.0,-521.0&gt;&gt;

* u18C8B.015: L&lt;&lt;-537.0,-433.0&gt;--&lt;-536.0,-286.0&gt;&gt;

* u18C8B.016: L&lt;&lt;-1475.0,-782.0&gt;--&lt;-1476.0,-1021.0&gt;&gt;

* u18C8B.016: L&lt;&lt;-1537.0,-933.0&gt;--&lt;-1536.0,-786.0&gt;&gt;

* u18C8B.017: L&lt;&lt;-1037.0,-933.0&gt;--&lt;-1036.0,-786.0&gt;&gt;

* u18C8B.017: L&lt;&lt;-975.0,-782.0&gt;--&lt;-976.0,-1021.0&gt;&gt;

* u18C8B.018: L&lt;&lt;-475.0,-782.0&gt;--&lt;-476.0,-1021.0&gt;&gt;

* u18C8B.018: L&lt;&lt;-537.0,-933.0&gt;--&lt;-536.0,-786.0&gt;&gt;

* u18C8B.019: L&lt;&lt;-1475.0,-1282.0&gt;--&lt;-1476.0,-1521.0&gt;&gt;

* u18C8B.019: L&lt;&lt;-1537.0,-1433.0&gt;--&lt;-1536.0,-1286.0&gt;&gt;

* u18C8B.020: L&lt;&lt;-1037.0,-1433.0&gt;--&lt;-1036.0,-1286.0&gt;&gt;

* u18C8B.020: L&lt;&lt;-975.0,-1282.0&gt;--&lt;-976.0,-1521.0&gt;&gt;

* u18C8B.021: L&lt;&lt;-475.0,-1282.0&gt;--&lt;-476.0,-1521.0&gt;&gt;

* u18C8B.021: L&lt;&lt;-537.0,-1433.0&gt;--&lt;-536.0,-1286.0&gt;&gt;

* u18C8B.022: L&lt;&lt;463.0,567.0&gt;--&lt;464.0,714.0&gt;&gt;

* u18C8B.022: L&lt;&lt;525.0,718.0&gt;--&lt;524.0,479.0&gt;&gt;

* u18C8B.023: L&lt;&lt;463.0,67.0&gt;--&lt;464.0,214.0&gt;&gt;

* u18C8B.023: L&lt;&lt;525.0,218.0&gt;--&lt;524.0,-21.0&gt;&gt;

* u18C8D (U+18C8D): L&lt;&lt;535.0,263.0&gt;--&lt;534.0,-35.0&gt;&gt;

* u18C8D.001: L&lt;&lt;535.0,1763.0&gt;--&lt;534.0,1465.0&gt;&gt;

* u18C8D.002: L&lt;&lt;1035.0,1763.0&gt;--&lt;1034.0,1465.0&gt;&gt;

* u18C8D.003: L&lt;&lt;-465.0,1763.0&gt;--&lt;-466.0,1465.0&gt;&gt;

* u18C8D.004: L&lt;&lt;535.0,1263.0&gt;--&lt;534.0,965.0&gt;&gt;

* u18C8D.005: L&lt;&lt;1035.0,1263.0&gt;--&lt;1034.0,965.0&gt;&gt;

* u18C8D.006: L&lt;&lt;-465.0,1263.0&gt;--&lt;-466.0,965.0&gt;&gt;

* u18C8D.007: L&lt;&lt;-1465.0,763.0&gt;--&lt;-1466.0,465.0&gt;&gt;

* u18C8D.008: L&lt;&lt;1035.0,763.0&gt;--&lt;1034.0,465.0&gt;&gt;

* u18C8D.009: L&lt;&lt;-465.0,763.0&gt;--&lt;-466.0,465.0&gt;&gt;

* u18C8D.010: L&lt;&lt;-1465.0,263.0&gt;--&lt;-1466.0,-35.0&gt;&gt;

* u18C8D.011: L&lt;&lt;1035.0,263.0&gt;--&lt;1034.0,-35.0&gt;&gt;

* u18C8D.012: L&lt;&lt;-465.0,263.0&gt;--&lt;-466.0,-35.0&gt;&gt;

* u18C8D.013: L&lt;&lt;-1465.0,-237.0&gt;--&lt;-1466.0,-535.0&gt;&gt;

* u18C8D.014: L&lt;&lt;-965.0,-237.0&gt;--&lt;-966.0,-535.0&gt;&gt;

* u18C8D.015: L&lt;&lt;-465.0,-237.0&gt;--&lt;-466.0,-535.0&gt;&gt;

* u18C8D.016: L&lt;&lt;-1465.0,-737.0&gt;--&lt;-1466.0,-1035.0&gt;&gt;

* u18C8D.017: L&lt;&lt;-965.0,-737.0&gt;--&lt;-966.0,-1035.0&gt;&gt;

* u18C8D.018: L&lt;&lt;-465.0,-737.0&gt;--&lt;-466.0,-1035.0&gt;&gt;

* u18C8D.019: L&lt;&lt;-1465.0,-1237.0&gt;--&lt;-1466.0,-1535.0&gt;&gt;

* u18C8D.020: L&lt;&lt;-965.0,-1237.0&gt;--&lt;-966.0,-1535.0&gt;&gt;

* u18C8D.021: L&lt;&lt;-465.0,-1237.0&gt;--&lt;-466.0,-1535.0&gt;&gt;

* u18C8D.022: L&lt;&lt;535.0,763.0&gt;--&lt;534.0,465.0&gt;&gt;

* u18C8D.023: L&lt;&lt;535.0,263.0&gt;--&lt;534.0,-35.0&gt;&gt;

* u18C8F (U+18C8F): L&lt;&lt;595.0,523.0&gt;--&lt;596.0,222.0&gt;&gt;

* u18C8F.001: L&lt;&lt;595.0,2023.0&gt;--&lt;596.0,1722.0&gt;&gt;

* u18C8F.002: L&lt;&lt;1095.0,2023.0&gt;--&lt;1096.0,1722.0&gt;&gt;

* u18C8F.003: L&lt;&lt;-405.0,2023.0&gt;--&lt;-404.0,1722.0&gt;&gt;

* u18C8F.004: L&lt;&lt;595.0,1523.0&gt;--&lt;596.0,1222.0&gt;&gt;

* u18C8F.005: L&lt;&lt;1095.0,1523.0&gt;--&lt;1096.0,1222.0&gt;&gt;

* u18C8F.006: L&lt;&lt;-405.0,1523.0&gt;--&lt;-404.0,1222.0&gt;&gt;

* u18C8F.007: L&lt;&lt;-1405.0,1023.0&gt;--&lt;-1404.0,722.0&gt;&gt;

* u18C8F.008: L&lt;&lt;1095.0,1023.0&gt;--&lt;1096.0,722.0&gt;&gt;

* u18C8F.009: L&lt;&lt;-405.0,1023.0&gt;--&lt;-404.0,722.0&gt;&gt;

* u18C8F.010: L&lt;&lt;-1405.0,523.0&gt;--&lt;-1404.0,222.0&gt;&gt;

* u18C8F.011: L&lt;&lt;1095.0,523.0&gt;--&lt;1096.0,222.0&gt;&gt;

* u18C8F.012: L&lt;&lt;-405.0,523.0&gt;--&lt;-404.0,222.0&gt;&gt;

* u18C8F.013: L&lt;&lt;-1405.0,23.0&gt;--&lt;-1404.0,-278.0&gt;&gt;

* u18C8F.014: L&lt;&lt;-905.0,23.0&gt;--&lt;-904.0,-278.0&gt;&gt;

* u18C8F.015: L&lt;&lt;-405.0,23.0&gt;--&lt;-404.0,-278.0&gt;&gt;

* u18C8F.016: L&lt;&lt;-1405.0,-477.0&gt;--&lt;-1404.0,-778.0&gt;&gt;

* u18C8F.017: L&lt;&lt;-905.0,-477.0&gt;--&lt;-904.0,-778.0&gt;&gt;

* u18C8F.018: L&lt;&lt;-405.0,-477.0&gt;--&lt;-404.0,-778.0&gt;&gt;

* u18C8F.019: L&lt;&lt;-1405.0,-977.0&gt;--&lt;-1404.0,-1278.0&gt;&gt;

* u18C8F.020: L&lt;&lt;-905.0,-977.0&gt;--&lt;-904.0,-1278.0&gt;&gt;

* u18C8F.021: L&lt;&lt;-405.0,-977.0&gt;--&lt;-404.0,-1278.0&gt;&gt;

* u18C8F.022: L&lt;&lt;595.0,1023.0&gt;--&lt;596.0,722.0&gt;&gt;

* u18C8F.023: L&lt;&lt;595.0,523.0&gt;--&lt;596.0,222.0&gt;&gt;

* u18C94 (U+18C94): L&lt;&lt;614.0,116.0&gt;--&lt;615.0,481.0&gt;&gt;

* u18C94 (U+18C94): L&lt;&lt;679.0,566.0&gt;--&lt;677.0,-10.0&gt;&gt;

* u18C94.001: L&lt;&lt;614.0,1616.0&gt;--&lt;615.0,1981.0&gt;&gt;

* u18C94.001: L&lt;&lt;679.0,2066.0&gt;--&lt;677.0,1490.0&gt;&gt;

* u18C94.002: L&lt;&lt;1114.0,1616.0&gt;--&lt;1115.0,1981.0&gt;&gt;

* u18C94.002: L&lt;&lt;1179.0,2066.0&gt;--&lt;1177.0,1490.0&gt;&gt;

* u18C94.003: L&lt;&lt;-321.0,2066.0&gt;--&lt;-323.0,1490.0&gt;&gt;

* u18C94.003: L&lt;&lt;-386.0,1616.0&gt;--&lt;-385.0,1981.0&gt;&gt;

* u18C94.004: L&lt;&lt;614.0,1116.0&gt;--&lt;615.0,1481.0&gt;&gt;

* u18C94.004: L&lt;&lt;679.0,1566.0&gt;--&lt;677.0,990.0&gt;&gt;

* u18C94.005: L&lt;&lt;1114.0,1116.0&gt;--&lt;1115.0,1481.0&gt;&gt;

* u18C94.005: L&lt;&lt;1179.0,1566.0&gt;--&lt;1177.0,990.0&gt;&gt;

* u18C94.006: L&lt;&lt;-321.0,1566.0&gt;--&lt;-323.0,990.0&gt;&gt;

* u18C94.006: L&lt;&lt;-386.0,1116.0&gt;--&lt;-385.0,1481.0&gt;&gt;

* u18C94.007: L&lt;&lt;-1321.0,1066.0&gt;--&lt;-1323.0,490.0&gt;&gt;

* u18C94.007: L&lt;&lt;-1386.0,616.0&gt;--&lt;-1385.0,981.0&gt;&gt;

* u18C94.008: L&lt;&lt;1114.0,616.0&gt;--&lt;1115.0,981.0&gt;&gt;

* u18C94.008: L&lt;&lt;1179.0,1066.0&gt;--&lt;1177.0,490.0&gt;&gt;

* u18C94.009: L&lt;&lt;-321.0,1066.0&gt;--&lt;-323.0,490.0&gt;&gt;

* u18C94.009: L&lt;&lt;-386.0,616.0&gt;--&lt;-385.0,981.0&gt;&gt;

* u18C94.010: L&lt;&lt;-1321.0,566.0&gt;--&lt;-1323.0,-10.0&gt;&gt;

* u18C94.010: L&lt;&lt;-1386.0,116.0&gt;--&lt;-1385.0,481.0&gt;&gt;

* u18C94.011: L&lt;&lt;1114.0,116.0&gt;--&lt;1115.0,481.0&gt;&gt;

* u18C94.011: L&lt;&lt;1179.0,566.0&gt;--&lt;1177.0,-10.0&gt;&gt;

* u18C94.012: L&lt;&lt;-321.0,566.0&gt;--&lt;-323.0,-10.0&gt;&gt;

* u18C94.012: L&lt;&lt;-386.0,116.0&gt;--&lt;-385.0,481.0&gt;&gt;

* u18C94.013: L&lt;&lt;-1321.0,66.0&gt;--&lt;-1323.0,-510.0&gt;&gt;

* u18C94.013: L&lt;&lt;-1386.0,-384.0&gt;--&lt;-1385.0,-19.0&gt;&gt;

* u18C94.014: L&lt;&lt;-821.0,66.0&gt;--&lt;-823.0,-510.0&gt;&gt;

* u18C94.014: L&lt;&lt;-886.0,-384.0&gt;--&lt;-885.0,-19.0&gt;&gt;

* u18C94.015: L&lt;&lt;-321.0,66.0&gt;--&lt;-323.0,-510.0&gt;&gt;

* u18C94.015: L&lt;&lt;-386.0,-384.0&gt;--&lt;-385.0,-19.0&gt;&gt;

* u18C94.016: L&lt;&lt;-1321.0,-434.0&gt;--&lt;-1323.0,-1010.0&gt;&gt;

* u18C94.016: L&lt;&lt;-1386.0,-884.0&gt;--&lt;-1385.0,-519.0&gt;&gt;

* u18C94.017: L&lt;&lt;-821.0,-434.0&gt;--&lt;-823.0,-1010.0&gt;&gt;

* u18C94.017: L&lt;&lt;-886.0,-884.0&gt;--&lt;-885.0,-519.0&gt;&gt;

* u18C94.018: L&lt;&lt;-321.0,-434.0&gt;--&lt;-323.0,-1010.0&gt;&gt;

* u18C94.018: L&lt;&lt;-386.0,-884.0&gt;--&lt;-385.0,-519.0&gt;&gt;

* u18C94.019: L&lt;&lt;-1321.0,-934.0&gt;--&lt;-1323.0,-1510.0&gt;&gt;

* u18C94.019: L&lt;&lt;-1386.0,-1384.0&gt;--&lt;-1385.0,-1019.0&gt;&gt;

* u18C94.020: L&lt;&lt;-821.0,-934.0&gt;--&lt;-823.0,-1510.0&gt;&gt;

* u18C94.020: L&lt;&lt;-886.0,-1384.0&gt;--&lt;-885.0,-1019.0&gt;&gt;

* u18C94.021: L&lt;&lt;-321.0,-934.0&gt;--&lt;-323.0,-1510.0&gt;&gt;

* u18C94.021: L&lt;&lt;-386.0,-1384.0&gt;--&lt;-385.0,-1019.0&gt;&gt;

* u18C94.022: L&lt;&lt;614.0,616.0&gt;--&lt;615.0,981.0&gt;&gt;

* u18C94.022: L&lt;&lt;679.0,1066.0&gt;--&lt;677.0,490.0&gt;&gt;

* u18C94.023: L&lt;&lt;614.0,116.0&gt;--&lt;615.0,481.0&gt;&gt;

* u18C94.023: L&lt;&lt;679.0,566.0&gt;--&lt;677.0,-10.0&gt;&gt;

* u18C99 (U+18C99): L&lt;&lt;301.0,201.0&gt;--&lt;302.0,56.0&gt;&gt;

* u18C99.001: L&lt;&lt;301.0,1701.0&gt;--&lt;302.0,1556.0&gt;&gt;

* u18C99.002: L&lt;&lt;801.0,1701.0&gt;--&lt;802.0,1556.0&gt;&gt;

* u18C99.003: L&lt;&lt;-699.0,1701.0&gt;--&lt;-698.0,1556.0&gt;&gt;

* u18C99.004: L&lt;&lt;301.0,1201.0&gt;--&lt;302.0,1056.0&gt;&gt;

* u18C99.005: L&lt;&lt;801.0,1201.0&gt;--&lt;802.0,1056.0&gt;&gt;

* u18C99.006: L&lt;&lt;-699.0,1201.0&gt;--&lt;-698.0,1056.0&gt;&gt;

* u18C99.007: L&lt;&lt;-1699.0,701.0&gt;--&lt;-1698.0,556.0&gt;&gt;

* u18C99.008: L&lt;&lt;801.0,701.0&gt;--&lt;802.0,556.0&gt;&gt;

* u18C99.009: L&lt;&lt;-699.0,701.0&gt;--&lt;-698.0,556.0&gt;&gt;

* u18C99.010: L&lt;&lt;-1699.0,201.0&gt;--&lt;-1698.0,56.0&gt;&gt;

* u18C99.011: L&lt;&lt;801.0,201.0&gt;--&lt;802.0,56.0&gt;&gt;

* u18C99.012: L&lt;&lt;-699.0,201.0&gt;--&lt;-698.0,56.0&gt;&gt;

* u18C99.013: L&lt;&lt;-1699.0,-299.0&gt;--&lt;-1698.0,-444.0&gt;&gt;

* u18C99.014: L&lt;&lt;-1199.0,-299.0&gt;--&lt;-1198.0,-444.0&gt;&gt;

* u18C99.015: L&lt;&lt;-699.0,-299.0&gt;--&lt;-698.0,-444.0&gt;&gt;

* u18C99.016: L&lt;&lt;-1699.0,-799.0&gt;--&lt;-1698.0,-944.0&gt;&gt;

* u18C99.017: L&lt;&lt;-1199.0,-799.0&gt;--&lt;-1198.0,-944.0&gt;&gt;

* u18C99.018: L&lt;&lt;-699.0,-799.0&gt;--&lt;-698.0,-944.0&gt;&gt;

* u18C99.019: L&lt;&lt;-1699.0,-1299.0&gt;--&lt;-1698.0,-1444.0&gt;&gt;

* u18C99.020: L&lt;&lt;-1199.0,-1299.0&gt;--&lt;-1198.0,-1444.0&gt;&gt;

* u18C99.021: L&lt;&lt;-699.0,-1299.0&gt;--&lt;-698.0,-1444.0&gt;&gt;

* u18C99.022: L&lt;&lt;301.0,701.0&gt;--&lt;302.0,556.0&gt;&gt;

* u18C99.023: L&lt;&lt;301.0,201.0&gt;--&lt;302.0,56.0&gt;&gt;

* u18CD0 (U+18CD0): L&lt;&lt;522.0,-36.0&gt;--&lt;523.0,-151.0&gt;&gt;

* u18CD0.001: L&lt;&lt;522.0,1464.0&gt;--&lt;523.0,1349.0&gt;&gt;

* u18CD0.002: L&lt;&lt;1022.0,1464.0&gt;--&lt;1023.0,1349.0&gt;&gt;

* u18CD0.003: L&lt;&lt;-478.0,1464.0&gt;--&lt;-477.0,1349.0&gt;&gt;

* u18CD0.004: L&lt;&lt;522.0,964.0&gt;--&lt;523.0,849.0&gt;&gt;

* u18CD0.005: L&lt;&lt;1022.0,964.0&gt;--&lt;1023.0,849.0&gt;&gt;

* u18CD0.006: L&lt;&lt;-478.0,964.0&gt;--&lt;-477.0,849.0&gt;&gt;

* u18CD0.007: L&lt;&lt;-1478.0,464.0&gt;--&lt;-1477.0,349.0&gt;&gt;

* u18CD0.008: L&lt;&lt;1022.0,464.0&gt;--&lt;1023.0,349.0&gt;&gt;

* u18CD0.009: L&lt;&lt;-478.0,464.0&gt;--&lt;-477.0,349.0&gt;&gt;

* u18CD0.010: L&lt;&lt;-1478.0,-36.0&gt;--&lt;-1477.0,-151.0&gt;&gt;

* u18CD0.011: L&lt;&lt;1022.0,-36.0&gt;--&lt;1023.0,-151.0&gt;&gt;

* u18CD0.012: L&lt;&lt;-478.0,-36.0&gt;--&lt;-477.0,-151.0&gt;&gt;

* u18CD0.013: L&lt;&lt;-1478.0,-536.0&gt;--&lt;-1477.0,-651.0&gt;&gt;

* u18CD0.014: L&lt;&lt;-978.0,-536.0&gt;--&lt;-977.0,-651.0&gt;&gt;

* u18CD0.015: L&lt;&lt;-478.0,-536.0&gt;--&lt;-477.0,-651.0&gt;&gt;

* u18CD0.016: L&lt;&lt;-1478.0,-1036.0&gt;--&lt;-1477.0,-1151.0&gt;&gt;

* u18CD0.017: L&lt;&lt;-978.0,-1036.0&gt;--&lt;-977.0,-1151.0&gt;&gt;

* u18CD0.018: L&lt;&lt;-478.0,-1036.0&gt;--&lt;-477.0,-1151.0&gt;&gt;

* u18CD0.019: L&lt;&lt;-1478.0,-1536.0&gt;--&lt;-1477.0,-1651.0&gt;&gt;

* u18CD0.020: L&lt;&lt;-978.0,-1536.0&gt;--&lt;-977.0,-1651.0&gt;&gt;

* u18CD0.021: L&lt;&lt;-478.0,-1536.0&gt;--&lt;-477.0,-1651.0&gt;&gt;

* u18CD0.022: L&lt;&lt;522.0,464.0&gt;--&lt;523.0,349.0&gt;&gt;

* u18CD0.023: L&lt;&lt;522.0,-36.0&gt;--&lt;523.0,-151.0&gt;&gt;

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
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifKhitanSmallScript/googlefonts/ttf/NotoSerifKhitanSmallScript-Regular.ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 6 | 11 | 117 | 6 | 111 | 0 | 
| 0% | 0% | 2% | 4% | 47% | 2% | 44% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
