## FontBakery report

fontbakery version: 0.12.10



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoFangsongKSSRotated-Regular.ttf</summary>
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



<details><summary>[15] NotoFangsongKSSRotated-Regular.ttf</summary>
<div>
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







* ⚠️ **WARN** <p>Family metadata at fonts/NotoFangsongKSSRotated/googlefonts/ttf does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, math, malayalam, todhri, syriac, coptic, duployan, tifinagh, hebrew, canadian-aboriginal, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+25A1 WHITE SQUARE: try adding symbols</li>
<li>U+2B1A DOTTED SQUARE: try adding symbols</li>
<li>U+4E39 CJK UNIFIED IDEOGRAPH-4E39: try adding one of: chinese-traditional, chinese-simplified, chinese-hongkong, japanese</li>
<li>U+4EFF CJK UNIFIED IDEOGRAPH-4EFF: try adding one of: chinese-traditional, chinese-simplified, chinese-hongkong</li>
<li>U+4F53 CJK UNIFIED IDEOGRAPH-4F53: try adding one of: chinese-traditional, chinese-simplified, chinese-hongkong, japanese</li>
<li>U+5951 CJK UNIFIED IDEOGRAPH-5951: try adding one of: chinese-traditional, chinese-simplified, chinese-hongkong, japanese</li>
<li>U+5B57 CJK UNIFIED IDEOGRAPH-5B57: try adding one of: chinese-traditional, chinese-simplified, chinese-hongkong, japanese</li>
<li>U+5B8B CJK UNIFIED IDEOGRAPH-5B8B: try adding one of: chinese-traditional, chinese-simplified, chinese-hongkong, japanese</li>
<li>U+5C0F CJK UNIFIED IDEOGRAPH-5C0F: try adding one of: chinese-traditional, chinese-simplified, chinese-hongkong, japanese</li>
<li>U+6B4C CJK UNIFIED IDEOGRAPH-6B4C: try adding one of: chinese-traditional, chinese-simplified, chinese-hongkong, japanese</li>
<li>U+8C37 CJK UNIFIED IDEOGRAPH-8C37: try adding one of: chinese-traditional, chinese-simplified, chinese-hongkong, japanese</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>khitan-small-script</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Name ID 6 'NotoFangsongKSSRotated-Regular' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms.</p>
 [code: nameid6-too-long]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Navajo (Latn, 166,319 speakers), Yala (Latn, 200,000 speakers), Lugbara (Latn, 2,200,000 speakers), Dutch (Latn, 31,709,104 speakers), Heiltsuk (Latn, 300 speakers), Basaa (Latn, 332,940 speakers), Ma’di (Latn, 584,000 speakers), Sar (Latn, 500,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Aghem (Latn, 38,843 speakers), Han (Latn, 6 speakers), Avokaya (Latn, 100,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Mfumte (Latn, 79,000 speakers), Igbo (Latn, 27,823,640 speakers), Southern Kisi (Latn, 360,000 speakers), Zapotec (Latn, 490,000 speakers), Ekpeye (Latn, 226,000 speakers), Vute (Latn, 21,000 speakers), Nzakara (Latn, 50,000 speakers), Ebira (Latn, 2,200,000 speakers), Nateni (Latn, 100,000 speakers), Kaska (Latn, 125 speakers), Koonzime (Latn, 40,000 speakers), Cicipu (Latn, 44,000 speakers), Ejagham (Latn, 120,000 speakers), Dii (Latn, 71,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Gulay (Latn, 250,478 speakers), Fur (Latn, 1,230,163 speakers), Bafut (Latn, 158,146 speakers), Makaa (Latn, 221,000 speakers), Mango (Latn, 77,000 speakers), Mundani (Latn, 34,000 speakers), South Central Banda (Latn, 244,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Dan (Latn, 1,099,244 speakers), Ngbaka (Latn, 1,020,000 speakers), Kom (Latn, 360,685 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Kpelle, Guinea (Latn, 622,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* u18B10 (U+18B10): B&lt;&lt;780.0,481.0&gt;-&lt;741.0,439.0&gt;-&lt;742.0,440.0&gt;&gt;/B&lt;&lt;742.0,440.0&gt;-&lt;708.0,407.0&gt;-&lt;673.5,378.5&gt;&gt; = 0.8550973962662667

* u18B10.001: B&lt;&lt;-682.0,1080.0&gt;-&lt;-640.0,1041.0&gt;-&lt;-641.0,1042.0&gt;&gt;/B&lt;&lt;-641.0,1042.0&gt;-&lt;-608.0,1008.0&gt;-&lt;-579.5,973.5&gt;&gt; = 0.8550973962662667

* u18B10.002: B&lt;&lt;318.0,580.0&gt;-&lt;360.0,541.0&gt;-&lt;359.0,542.0&gt;&gt;/B&lt;&lt;359.0,542.0&gt;-&lt;392.0,508.0&gt;-&lt;420.5,473.5&gt;&gt; = 0.8550973962662667

* u18B10.003: B&lt;&lt;318.0,80.0&gt;-&lt;360.0,41.0&gt;-&lt;359.0,42.0&gt;&gt;/B&lt;&lt;359.0,42.0&gt;-&lt;392.0,8.0&gt;-&lt;420.5,-26.5&gt;&gt; = 0.8550973962662667

* u18B3C (U+18B3C): B&lt;&lt;209.0,307.0&gt;-&lt;250.0,266.0&gt;-&lt;294.0,237.0&gt;&gt;/B&lt;&lt;294.0,237.0&gt;-&lt;293.0,238.0&gt;-&lt;420.0,152.0&gt;&gt; = 11.611486423888481

* u18B3C.001: B&lt;&lt;-507.0,509.0&gt;-&lt;-466.0,550.0&gt;-&lt;-437.0,594.0&gt;&gt;/B&lt;&lt;-437.0,594.0&gt;-&lt;-438.0,593.0&gt;-&lt;-352.0,720.0&gt;&gt; = 11.611486423888481

* u18B3C.002: B&lt;&lt;493.0,9.0&gt;-&lt;534.0,50.0&gt;-&lt;563.0,94.0&gt;&gt;/B&lt;&lt;563.0,94.0&gt;-&lt;562.0,93.0&gt;-&lt;648.0,220.0&gt;&gt; = 11.611486423888481

* u18B3C.003: B&lt;&lt;493.0,-491.0&gt;-&lt;534.0,-450.0&gt;-&lt;563.0,-406.0&gt;&gt;/B&lt;&lt;563.0,-406.0&gt;-&lt;562.0,-407.0&gt;-&lt;648.0,-280.0&gt;&gt; = 11.611486423888481

* u18B81 (U+18B81): B&lt;&lt;838.0,326.0&gt;-&lt;799.0,284.0&gt;-&lt;800.0,285.0&gt;&gt;/B&lt;&lt;800.0,285.0&gt;-&lt;716.0,203.0&gt;-&lt;644.0,155.0&gt;&gt; = 0.6902771978645523

* u18B81.001: B&lt;&lt;-526.0,1138.0&gt;-&lt;-484.0,1099.0&gt;-&lt;-485.0,1100.0&gt;&gt;/B&lt;&lt;-485.0,1100.0&gt;-&lt;-403.0,1016.0&gt;-&lt;-355.0,944.0&gt;&gt; = 0.6902771978645523

* u18B81.002: B&lt;&lt;474.0,638.0&gt;-&lt;516.0,599.0&gt;-&lt;515.0,600.0&gt;&gt;/B&lt;&lt;515.0,600.0&gt;-&lt;597.0,516.0&gt;-&lt;645.0,444.0&gt;&gt; = 0.6902771978645523

* u18B81.003: B&lt;&lt;474.0,138.0&gt;-&lt;516.0,99.0&gt;-&lt;515.0,100.0&gt;&gt;/B&lt;&lt;515.0,100.0&gt;-&lt;597.0,16.0&gt;-&lt;645.0,-56.0&gt;&gt; = 0.6902771978645523

* u18BB1 (U+18BB1): B&lt;&lt;455.0,362.0&gt;-&lt;431.0,360.0&gt;-&lt;435.0,360.0&gt;&gt;/B&lt;&lt;435.0,360.0&gt;-&lt;380.0,355.0&gt;-&lt;313.0,341.0&gt;&gt; = 5.1944289077348

* u18BB1.001: B&lt;&lt;-564.0,755.0&gt;-&lt;-562.0,731.0&gt;-&lt;-562.0,735.0&gt;&gt;/B&lt;&lt;-562.0,735.0&gt;-&lt;-557.0,680.0&gt;-&lt;-543.0,613.0&gt;&gt; = 5.1944289077348

* u18BB1.002: B&lt;&lt;436.0,255.0&gt;-&lt;438.0,231.0&gt;-&lt;438.0,235.0&gt;&gt;/B&lt;&lt;438.0,235.0&gt;-&lt;443.0,180.0&gt;-&lt;457.0,113.0&gt;&gt; = 5.1944289077348

* u18BB1.003: B&lt;&lt;436.0,-245.0&gt;-&lt;438.0,-269.0&gt;-&lt;438.0,-265.0&gt;&gt;/B&lt;&lt;438.0,-265.0&gt;-&lt;443.0,-320.0&gt;-&lt;457.0,-387.0&gt;&gt; = 5.1944289077348

* u18BEA (U+18BEA): B&lt;&lt;598.0,608.0&gt;-&lt;508.0,600.0&gt;-&lt;524.0,601.0&gt;&gt;/B&lt;&lt;524.0,601.0&gt;-&lt;390.0,588.0&gt;-&lt;347.0,583.0&gt;&gt; = 1.9648704030421524

* u18BEA.001: B&lt;&lt;-808.0,898.0&gt;-&lt;-800.0,808.0&gt;-&lt;-801.0,824.0&gt;&gt;/B&lt;&lt;-801.0,824.0&gt;-&lt;-788.0,690.0&gt;-&lt;-783.0,647.0&gt;&gt; = 1.9648704030421524

* u18BEA.002: B&lt;&lt;192.0,398.0&gt;-&lt;200.0,308.0&gt;-&lt;199.0,324.0&gt;&gt;/B&lt;&lt;199.0,324.0&gt;-&lt;212.0,190.0&gt;-&lt;217.0,147.0&gt;&gt; = 1.9648704030421524

* u18BEA.003: B&lt;&lt;192.0,-102.0&gt;-&lt;200.0,-192.0&gt;-&lt;199.0,-176.0&gt;&gt;/B&lt;&lt;199.0,-176.0&gt;-&lt;212.0,-310.0&gt;-&lt;217.0,-353.0&gt;&gt; = 1.9648704030421524

* u18BEB (U+18BEB): B&lt;&lt;599.0,608.0&gt;-&lt;502.0,600.0&gt;-&lt;522.0,601.0&gt;&gt;/B&lt;&lt;522.0,601.0&gt;-&lt;493.0,598.0&gt;-&lt;427.0,592.0&gt;&gt; = 3.0437358876587015

* u18BEB.001: B&lt;&lt;-808.0,899.0&gt;-&lt;-800.0,802.0&gt;-&lt;-801.0,822.0&gt;&gt;/B&lt;&lt;-801.0,822.0&gt;-&lt;-798.0,793.0&gt;-&lt;-791.0,727.0&gt;&gt; = 3.0437358876587015

* u18BEB.002: B&lt;&lt;192.0,399.0&gt;-&lt;200.0,302.0&gt;-&lt;199.0,322.0&gt;&gt;/B&lt;&lt;199.0,322.0&gt;-&lt;202.0,293.0&gt;-&lt;209.0,227.0&gt;&gt; = 3.0437358876587015

* u18BEB.003: B&lt;&lt;192.0,-101.0&gt;-&lt;200.0,-198.0&gt;-&lt;199.0,-178.0&gt;&gt;/B&lt;&lt;199.0,-178.0&gt;-&lt;202.0,-207.0&gt;-&lt;209.0,-273.0&gt;&gt; = 3.0437358876587015

* u18C0A (U+18C0A): B&lt;&lt;899.0,514.0&gt;-&lt;801.0,505.0&gt;-&lt;807.0,506.0&gt;&gt;/B&lt;&lt;807.0,506.0&gt;-&lt;688.0,496.0&gt;-&lt;578.0,485.0&gt;&gt; = 4.6588364489565155

* u18C0A.001: B&lt;&lt;-714.0,1199.0&gt;-&lt;-705.0,1101.0&gt;-&lt;-706.0,1107.0&gt;&gt;/B&lt;&lt;-706.0,1107.0&gt;-&lt;-696.0,988.0&gt;-&lt;-685.0,878.0&gt;&gt; = 4.6588364489565155

* u18C0A.002: B&lt;&lt;286.0,699.0&gt;-&lt;295.0,601.0&gt;-&lt;294.0,607.0&gt;&gt;/B&lt;&lt;294.0,607.0&gt;-&lt;304.0,488.0&gt;-&lt;315.0,378.0&gt;&gt; = 4.6588364489565155

* u18C0A.003: B&lt;&lt;286.0,199.0&gt;-&lt;295.0,101.0&gt;-&lt;294.0,107.0&gt;&gt;/B&lt;&lt;294.0,107.0&gt;-&lt;304.0,-12.0&gt;-&lt;315.0,-122.0&gt;&gt; = 4.6588364489565155

* u18C0B (U+18C0B): B&lt;&lt;859.0,514.0&gt;-&lt;761.0,505.0&gt;-&lt;767.0,506.0&gt;&gt;/B&lt;&lt;767.0,506.0&gt;-&lt;641.0,496.0&gt;-&lt;524.0,484.0&gt;&gt; = 4.924549700118923

* u18C0B.001: B&lt;&lt;-714.0,1159.0&gt;-&lt;-705.0,1061.0&gt;-&lt;-706.0,1067.0&gt;&gt;/B&lt;&lt;-706.0,1067.0&gt;-&lt;-696.0,941.0&gt;-&lt;-684.0,824.0&gt;&gt; = 4.924549700118923

* u18C0B.002: B&lt;&lt;286.0,659.0&gt;-&lt;295.0,561.0&gt;-&lt;294.0,567.0&gt;&gt;/B&lt;&lt;294.0,567.0&gt;-&lt;304.0,441.0&gt;-&lt;316.0,324.0&gt;&gt; = 4.924549700118923

* u18C0B.003: B&lt;&lt;286.0,159.0&gt;-&lt;295.0,61.0&gt;-&lt;294.0,67.0&gt;&gt;/B&lt;&lt;294.0,67.0&gt;-&lt;304.0,-59.0&gt;-&lt;316.0,-176.0&gt;&gt; = 4.924549700118923

* u18C65 (U+18C65): B&lt;&lt;773.0,592.0&gt;-&lt;755.0,571.0&gt;-&lt;757.0,573.0&gt;&gt;/B&lt;&lt;757.0,573.0&gt;-&lt;706.0,512.0&gt;-&lt;660.0,464.0&gt;&gt; = 5.102165252358147

* u18C65.001: B&lt;&lt;-792.0,1073.0&gt;-&lt;-771.0,1055.0&gt;-&lt;-773.0,1057.0&gt;&gt;/B&lt;&lt;-773.0,1057.0&gt;-&lt;-712.0,1006.0&gt;-&lt;-664.0,960.0&gt;&gt; = 5.102165252358147

* u18C65.002: B&lt;&lt;208.0,573.0&gt;-&lt;229.0,555.0&gt;-&lt;227.0,557.0&gt;&gt;/B&lt;&lt;227.0,557.0&gt;-&lt;288.0,506.0&gt;-&lt;336.0,460.0&gt;&gt; = 5.102165252358147

* u18C65.003: B&lt;&lt;208.0,73.0&gt;-&lt;229.0,55.0&gt;-&lt;227.0,57.0&gt;&gt;/B&lt;&lt;227.0,57.0&gt;-&lt;288.0,6.0&gt;-&lt;336.0,-40.0&gt;&gt; = 5.102165252358147

* u18C71.001: L&lt;&lt;-327.0,769.0&gt;--&lt;-327.0,769.0&gt;&gt;/B&lt;&lt;-327.0,769.0&gt;-&lt;-378.0,771.0&gt;-&lt;-408.0,770.0&gt;&gt; = 2.245742565895049

* u18C71.002: L&lt;&lt;673.0,269.0&gt;--&lt;673.0,269.0&gt;&gt;/B&lt;&lt;673.0,269.0&gt;-&lt;622.0,271.0&gt;-&lt;592.0,270.0&gt;&gt; = 2.245742565895049

* u18C71.003: L&lt;&lt;673.0,-231.0&gt;--&lt;673.0,-231.0&gt;&gt;/B&lt;&lt;673.0,-231.0&gt;-&lt;622.0,-229.0&gt;-&lt;592.0,-230.0&gt;&gt; = 2.245742565895049

* u18CB2 (U+18CB2): B&lt;&lt;371.0,355.0&gt;-&lt;458.0,365.0&gt;-&lt;453.0,364.0&gt;&gt;/B&lt;&lt;453.0,364.0&gt;-&lt;478.0,367.0&gt;-&lt;492.5,375.0&gt;&gt; = 4.46715906138917

* u18CB2.001: B&lt;&lt;-556.0,671.0&gt;-&lt;-566.0,758.0&gt;-&lt;-565.0,753.0&gt;&gt;/B&lt;&lt;-565.0,753.0&gt;-&lt;-568.0,778.0&gt;-&lt;-576.0,792.5&gt;&gt; = 4.46715906138917

* u18CB2.002: B&lt;&lt;444.0,171.0&gt;-&lt;434.0,258.0&gt;-&lt;435.0,253.0&gt;&gt;/B&lt;&lt;435.0,253.0&gt;-&lt;432.0,278.0&gt;-&lt;424.0,292.5&gt;&gt; = 4.46715906138917

* u18CB2.003: B&lt;&lt;444.0,-329.0&gt;-&lt;434.0,-242.0&gt;-&lt;435.0,-247.0&gt;&gt;/B&lt;&lt;435.0,-247.0&gt;-&lt;432.0,-222.0&gt;-&lt;424.0,-207.5&gt;&gt; = 4.46715906138917

* u18CB3 (U+18CB3): B&lt;&lt;377.0,617.0&gt;-&lt;328.0,611.0&gt;-&lt;333.0,612.0&gt;&gt;/B&lt;&lt;333.0,612.0&gt;-&lt;303.0,610.0&gt;-&lt;254.0,602.0&gt;&gt; = 7.495857639729836

* u18CB3.001: B&lt;&lt;-819.0,677.0&gt;-&lt;-813.0,628.0&gt;-&lt;-814.0,633.0&gt;&gt;/B&lt;&lt;-814.0,633.0&gt;-&lt;-812.0,603.0&gt;-&lt;-804.0,554.0&gt;&gt; = 7.495857639729836

* u18CB3.002: B&lt;&lt;181.0,177.0&gt;-&lt;187.0,128.0&gt;-&lt;186.0,133.0&gt;&gt;/B&lt;&lt;186.0,133.0&gt;-&lt;188.0,103.0&gt;-&lt;196.0,54.0&gt;&gt; = 7.495857639729836

* u18CB3.003: B&lt;&lt;181.0,-323.0&gt;-&lt;187.0,-372.0&gt;-&lt;186.0,-367.0&gt;&gt;/B&lt;&lt;186.0,-367.0&gt;-&lt;188.0,-397.0&gt;-&lt;196.0,-446.0&gt;&gt; = 7.495857639729836
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* u18B03 (U+18B03): L&lt;&lt;531.0,182.0&gt;--&lt;530.0,-136.0&gt;&gt;

* u18B03.001: L&lt;&lt;-383.0,831.0&gt;--&lt;-65.0,830.0&gt;&gt;

* u18B03.002: L&lt;&lt;617.0,331.0&gt;--&lt;935.0,330.0&gt;&gt;

* u18B03.003: L&lt;&lt;617.0,-169.0&gt;--&lt;935.0,-170.0&gt;&gt;

* u18B07 (U+18B07): L&lt;&lt;497.0,338.0&gt;--&lt;496.0,597.0&gt;&gt;

* u18B07.001: L&lt;&lt;-539.0,797.0&gt;--&lt;-798.0,796.0&gt;&gt;

* u18B07.002: L&lt;&lt;461.0,297.0&gt;--&lt;202.0,296.0&gt;&gt;

* u18B07.003: L&lt;&lt;461.0,-203.0&gt;--&lt;202.0,-204.0&gt;&gt;

* u18B0B (U+18B0B): L&lt;&lt;527.0,175.0&gt;--&lt;526.0,-149.0&gt;&gt;

* u18B0B.001: L&lt;&lt;-376.0,827.0&gt;--&lt;-52.0,826.0&gt;&gt;

* u18B0B.002: L&lt;&lt;624.0,327.0&gt;--&lt;948.0,326.0&gt;&gt;

* u18B0B.003: L&lt;&lt;624.0,-173.0&gt;--&lt;948.0,-174.0&gt;&gt;

* u18B14 (U+18B14): L&lt;&lt;551.0,485.0&gt;--&lt;550.0,168.0&gt;&gt;

* u18B14.001: L&lt;&lt;-686.0,851.0&gt;--&lt;-369.0,850.0&gt;&gt;

* u18B14.002: L&lt;&lt;314.0,351.0&gt;--&lt;631.0,350.0&gt;&gt;

* u18B14.003: L&lt;&lt;314.0,-149.0&gt;--&lt;631.0,-150.0&gt;&gt;

* u18B15 (U+18B15): L&lt;&lt;531.0,485.0&gt;--&lt;530.0,168.0&gt;&gt;

* u18B15.001: L&lt;&lt;-686.0,831.0&gt;--&lt;-369.0,830.0&gt;&gt;

* u18B15.002: L&lt;&lt;314.0,331.0&gt;--&lt;631.0,330.0&gt;&gt;

* u18B15.003: L&lt;&lt;314.0,-169.0&gt;--&lt;631.0,-170.0&gt;&gt;

* u18B17 (U+18B17): L&lt;&lt;545.0,378.0&gt;--&lt;544.0,175.0&gt;&gt;

* u18B17.001: L&lt;&lt;-579.0,845.0&gt;--&lt;-376.0,844.0&gt;&gt;

* u18B17.002: L&lt;&lt;421.0,345.0&gt;--&lt;624.0,344.0&gt;&gt;

* u18B17.003: L&lt;&lt;421.0,-155.0&gt;--&lt;624.0,-156.0&gt;&gt;

* u18B18 (U+18B18): L&lt;&lt;535.0,391.0&gt;--&lt;534.0,224.0&gt;&gt;

* u18B18.001: L&lt;&lt;-592.0,835.0&gt;--&lt;-425.0,834.0&gt;&gt;

* u18B18.002: L&lt;&lt;408.0,335.0&gt;--&lt;575.0,334.0&gt;&gt;

* u18B18.003: L&lt;&lt;408.0,-165.0&gt;--&lt;575.0,-166.0&gt;&gt;

* u18B19 (U+18B19): L&lt;&lt;534.0,426.0&gt;--&lt;533.0,303.0&gt;&gt;

* u18B19.001: L&lt;&lt;-627.0,834.0&gt;--&lt;-504.0,833.0&gt;&gt;

* u18B19.002: L&lt;&lt;373.0,334.0&gt;--&lt;496.0,333.0&gt;&gt;

* u18B19.003: L&lt;&lt;373.0,-166.0&gt;--&lt;496.0,-167.0&gt;&gt;

* u18B1E (U+18B1E): L&lt;&lt;529.0,154.0&gt;--&lt;528.0,-113.0&gt;&gt;

* u18B1E.001: L&lt;&lt;-355.0,829.0&gt;--&lt;-88.0,828.0&gt;&gt;

* u18B1E.002: L&lt;&lt;645.0,329.0&gt;--&lt;912.0,328.0&gt;&gt;

* u18B1E.003: L&lt;&lt;645.0,-171.0&gt;--&lt;912.0,-172.0&gt;&gt;

* u18B1F (U+18B1F): L&lt;&lt;827.0,128.0&gt;--&lt;826.0,-148.0&gt;&gt;

* u18B1F.001: L&lt;&lt;-329.0,1127.0&gt;--&lt;-53.0,1126.0&gt;&gt;

* u18B1F.002: L&lt;&lt;671.0,627.0&gt;--&lt;947.0,626.0&gt;&gt;

* u18B1F.003: L&lt;&lt;671.0,127.0&gt;--&lt;947.0,126.0&gt;&gt;

* u18B22 (U+18B22): L&lt;&lt;367.0,-25.0&gt;--&lt;365.0,341.0&gt;&gt;

* u18B22.001: L&lt;&lt;-176.0,667.0&gt;--&lt;-542.0,665.0&gt;&gt;

* u18B22.002: L&lt;&lt;824.0,167.0&gt;--&lt;458.0,165.0&gt;&gt;

* u18B22.003: L&lt;&lt;824.0,-333.0&gt;--&lt;458.0,-335.0&gt;&gt;

* u18B36 (U+18B36): L&lt;&lt;528.0,579.0&gt;--&lt;527.0,394.0&gt;&gt;

* u18B36.001: L&lt;&lt;-779.0,828.0&gt;--&lt;-594.0,827.0&gt;&gt;

* u18B36.002: L&lt;&lt;221.0,328.0&gt;--&lt;406.0,327.0&gt;&gt;

* u18B36.003: L&lt;&lt;221.0,-172.0&gt;--&lt;406.0,-173.0&gt;&gt;

* u18B38 (U+18B38): L&lt;&lt;490.0,28.0&gt;--&lt;491.0,344.0&gt;&gt;

* u18B38.001: L&lt;&lt;-228.0,790.0&gt;--&lt;-544.0,791.0&gt;&gt;

* u18B38.002: L&lt;&lt;772.0,290.0&gt;--&lt;456.0,291.0&gt;&gt;

* u18B38.003: L&lt;&lt;772.0,-210.0&gt;--&lt;456.0,-209.0&gt;&gt;

* u18B39 (U+18B39): L&lt;&lt;470.0,28.0&gt;--&lt;471.0,344.0&gt;&gt;

* u18B39.001: L&lt;&lt;-228.0,770.0&gt;--&lt;-544.0,771.0&gt;&gt;

* u18B39.002: L&lt;&lt;772.0,270.0&gt;--&lt;456.0,271.0&gt;&gt;

* u18B39.003: L&lt;&lt;772.0,-230.0&gt;--&lt;456.0,-229.0&gt;&gt;

* u18B3A (U+18B3A): L&lt;&lt;527.0,508.0&gt;--&lt;526.0,210.0&gt;&gt;

* u18B3A.001: L&lt;&lt;-708.0,827.0&gt;--&lt;-410.0,826.0&gt;&gt;

* u18B3A.002: L&lt;&lt;292.0,327.0&gt;--&lt;590.0,326.0&gt;&gt;

* u18B3A.003: L&lt;&lt;292.0,-173.0&gt;--&lt;590.0,-174.0&gt;&gt;

* u18B3E (U+18B3E): L&lt;&lt;190.0,-2.0&gt;--&lt;191.0,131.0&gt;&gt;

* u18B3E (U+18B3E): L&lt;&lt;191.0,131.0&gt;--&lt;190.0,262.0&gt;&gt;

* u18B3E.001: L&lt;&lt;-198.0,490.0&gt;--&lt;-331.0,491.0&gt;&gt;

* u18B3E.001: L&lt;&lt;-331.0,491.0&gt;--&lt;-462.0,490.0&gt;&gt;

* u18B3E.002: L&lt;&lt;669.0,-9.0&gt;--&lt;538.0,-10.0&gt;&gt;

* u18B3E.002: L&lt;&lt;802.0,-10.0&gt;--&lt;669.0,-9.0&gt;&gt;

* u18B3E.003: L&lt;&lt;669.0,-509.0&gt;--&lt;538.0,-510.0&gt;&gt;

* u18B3E.003: L&lt;&lt;802.0,-510.0&gt;--&lt;669.0,-509.0&gt;&gt;

* u18B3F (U+18B3F): L&lt;&lt;537.0,488.0&gt;--&lt;536.0,211.0&gt;&gt;

* u18B3F.001: L&lt;&lt;-688.0,837.0&gt;--&lt;-411.0,836.0&gt;&gt;

* u18B3F.002: L&lt;&lt;312.0,337.0&gt;--&lt;589.0,336.0&gt;&gt;

* u18B3F.003: L&lt;&lt;312.0,-163.0&gt;--&lt;589.0,-164.0&gt;&gt;

* u18B40 (U+18B40): L&lt;&lt;524.0,536.0&gt;--&lt;523.0,365.0&gt;&gt;

* u18B40.001: L&lt;&lt;-736.0,824.0&gt;--&lt;-565.0,823.0&gt;&gt;

* u18B40.002: L&lt;&lt;264.0,324.0&gt;--&lt;435.0,323.0&gt;&gt;

* u18B40.003: L&lt;&lt;264.0,-176.0&gt;--&lt;435.0,-177.0&gt;&gt;

* u18B46 (U+18B46): L&lt;&lt;535.0,411.0&gt;--&lt;534.0,215.0&gt;&gt;

* u18B46.001: L&lt;&lt;-611.0,835.0&gt;--&lt;-415.0,834.0&gt;&gt;

* u18B46.002: L&lt;&lt;389.0,335.0&gt;--&lt;585.0,334.0&gt;&gt;

* u18B46.003: L&lt;&lt;389.0,-165.0&gt;--&lt;585.0,-166.0&gt;&gt;

* u18B47 (U+18B47): L&lt;&lt;524.0,413.0&gt;--&lt;525.0,-43.0&gt;&gt;

* u18B47.001: L&lt;&lt;-613.0,824.0&gt;--&lt;-157.0,825.0&gt;&gt;

* u18B47.002: L&lt;&lt;387.0,324.0&gt;--&lt;843.0,325.0&gt;&gt;

* u18B47.003: L&lt;&lt;387.0,-176.0&gt;--&lt;843.0,-175.0&gt;&gt;

* u18B4B (U+18B4B): L&lt;&lt;876.0,581.0&gt;--&lt;875.0,211.0&gt;&gt;

* u18B4B.001: L&lt;&lt;-781.0,1176.0&gt;--&lt;-411.0,1175.0&gt;&gt;

* u18B4B.002: L&lt;&lt;219.0,676.0&gt;--&lt;589.0,675.0&gt;&gt;

* u18B4B.003: L&lt;&lt;219.0,176.0&gt;--&lt;589.0,175.0&gt;&gt;

* u18B53 (U+18B53): L&lt;&lt;437.0,571.0&gt;--&lt;436.0,349.0&gt;&gt;

* u18B53.001: L&lt;&lt;-771.0,737.0&gt;--&lt;-549.0,736.0&gt;&gt;

* u18B53.002: L&lt;&lt;229.0,237.0&gt;--&lt;451.0,236.0&gt;&gt;

* u18B53.003: L&lt;&lt;229.0,-263.0&gt;--&lt;451.0,-264.0&gt;&gt;

* u18B54 (U+18B54): L&lt;&lt;464.0,-25.0&gt;--&lt;465.0,315.0&gt;&gt;

* u18B54.001: L&lt;&lt;-175.0,764.0&gt;--&lt;-515.0,765.0&gt;&gt;

* u18B54.002: L&lt;&lt;825.0,264.0&gt;--&lt;485.0,265.0&gt;&gt;

* u18B54.003: L&lt;&lt;825.0,-236.0&gt;--&lt;485.0,-235.0&gt;&gt;

* u18B55 (U+18B55): L&lt;&lt;464.0,23.0&gt;--&lt;465.0,335.0&gt;&gt;

* u18B55.001: L&lt;&lt;-223.0,764.0&gt;--&lt;-535.0,765.0&gt;&gt;

* u18B55.002: L&lt;&lt;777.0,264.0&gt;--&lt;465.0,265.0&gt;&gt;

* u18B55.003: L&lt;&lt;777.0,-236.0&gt;--&lt;465.0,-235.0&gt;&gt;

* u18B5C (U+18B5C): L&lt;&lt;539.0,538.0&gt;--&lt;538.0,193.0&gt;&gt;

* u18B5C.001: L&lt;&lt;-738.0,839.0&gt;--&lt;-393.0,838.0&gt;&gt;

* u18B5C.002: L&lt;&lt;262.0,339.0&gt;--&lt;607.0,338.0&gt;&gt;

* u18B5C.003: L&lt;&lt;262.0,-161.0&gt;--&lt;607.0,-162.0&gt;&gt;

* u18B64 (U+18B64): L&lt;&lt;370.0,516.0&gt;--&lt;369.0,360.0&gt;&gt;

* u18B64 (U+18B64): L&lt;&lt;661.0,543.0&gt;--&lt;660.0,389.0&gt;&gt;

* u18B64.001: L&lt;&lt;-716.0,670.0&gt;--&lt;-560.0,669.0&gt;&gt;

* u18B64.001: L&lt;&lt;-743.0,961.0&gt;--&lt;-589.0,960.0&gt;&gt;

* u18B64.002: L&lt;&lt;257.0,461.0&gt;--&lt;411.0,460.0&gt;&gt;

* u18B64.002: L&lt;&lt;284.0,170.0&gt;--&lt;440.0,169.0&gt;&gt;

* u18B64.003: L&lt;&lt;257.0,-39.0&gt;--&lt;411.0,-40.0&gt;&gt;

* u18B64.003: L&lt;&lt;284.0,-330.0&gt;--&lt;440.0,-331.0&gt;&gt;

* u18B69 (U+18B69): L&lt;&lt;349.0,387.0&gt;--&lt;347.0,46.0&gt;&gt;

* u18B69 (U+18B69): L&lt;&lt;689.0,414.0&gt;--&lt;686.0,-23.0&gt;&gt;

* u18B69.001: L&lt;&lt;-587.0,649.0&gt;--&lt;-246.0,647.0&gt;&gt;

* u18B69.001: L&lt;&lt;-614.0,989.0&gt;--&lt;-177.0,986.0&gt;&gt;

* u18B69.002: L&lt;&lt;386.0,489.0&gt;--&lt;823.0,486.0&gt;&gt;

* u18B69.002: L&lt;&lt;413.0,149.0&gt;--&lt;754.0,147.0&gt;&gt;

* u18B69.003: L&lt;&lt;386.0,-11.0&gt;--&lt;823.0,-14.0&gt;&gt;

* u18B69.003: L&lt;&lt;413.0,-351.0&gt;--&lt;754.0,-353.0&gt;&gt;

* u18B80 (U+18B80): L&lt;&lt;814.0,177.0&gt;--&lt;813.0,62.0&gt;&gt;

* u18B80.001: L&lt;&lt;-377.0,1114.0&gt;--&lt;-262.0,1113.0&gt;&gt;

* u18B80.002: L&lt;&lt;623.0,614.0&gt;--&lt;738.0,613.0&gt;&gt;

* u18B80.003: L&lt;&lt;623.0,114.0&gt;--&lt;738.0,113.0&gt;&gt;

* u18B95 (U+18B95): L&lt;&lt;448.0,517.0&gt;--&lt;447.0,-26.0&gt;&gt;

* u18B95 (U+18B95): L&lt;&lt;589.0,-16.0&gt;--&lt;590.0,436.0&gt;&gt;

* u18B95 (U+18B95): L&lt;&lt;652.0,567.0&gt;--&lt;651.0,-11.0&gt;&gt;

* u18B95.001: L&lt;&lt;-184.0,889.0&gt;--&lt;-636.0,890.0&gt;&gt;

* u18B95.001: L&lt;&lt;-717.0,748.0&gt;--&lt;-174.0,747.0&gt;&gt;

* u18B95.001: L&lt;&lt;-767.0,952.0&gt;--&lt;-189.0,951.0&gt;&gt;

* u18B95.002: L&lt;&lt;233.0,452.0&gt;--&lt;811.0,451.0&gt;&gt;

* u18B95.002: L&lt;&lt;283.0,248.0&gt;--&lt;826.0,247.0&gt;&gt;

* u18B95.002: L&lt;&lt;816.0,389.0&gt;--&lt;364.0,390.0&gt;&gt;

* u18B95.003: L&lt;&lt;233.0,-48.0&gt;--&lt;811.0,-49.0&gt;&gt;

* u18B95.003: L&lt;&lt;283.0,-252.0&gt;--&lt;826.0,-253.0&gt;&gt;

* u18B95.003: L&lt;&lt;816.0,-111.0&gt;--&lt;364.0,-110.0&gt;&gt;

* u18B98 (U+18B98): L&lt;&lt;426.0,573.0&gt;--&lt;425.0,-43.0&gt;&gt;

* u18B98 (U+18B98): L&lt;&lt;568.0,-32.0&gt;--&lt;569.0,444.0&gt;&gt;

* u18B98 (U+18B98): L&lt;&lt;631.0,275.0&gt;--&lt;630.0,-27.0&gt;&gt;

* u18B98.001: L&lt;&lt;-168.0,868.0&gt;--&lt;-644.0,869.0&gt;&gt;

* u18B98.001: L&lt;&lt;-475.0,931.0&gt;--&lt;-173.0,930.0&gt;&gt;

* u18B98.001: L&lt;&lt;-773.0,726.0&gt;--&lt;-157.0,725.0&gt;&gt;

* u18B98.002: L&lt;&lt;227.0,226.0&gt;--&lt;843.0,225.0&gt;&gt;

* u18B98.002: L&lt;&lt;525.0,431.0&gt;--&lt;827.0,430.0&gt;&gt;

* u18B98.002: L&lt;&lt;832.0,368.0&gt;--&lt;356.0,369.0&gt;&gt;

* u18B98.003: L&lt;&lt;227.0,-274.0&gt;--&lt;843.0,-275.0&gt;&gt;

* u18B98.003: L&lt;&lt;525.0,-69.0&gt;--&lt;827.0,-70.0&gt;&gt;

* u18B98.003: L&lt;&lt;832.0,-132.0&gt;--&lt;356.0,-131.0&gt;&gt;

* u18B9C (U+18B9C): L&lt;&lt;467.0,-25.0&gt;--&lt;468.0,436.0&gt;&gt;

* u18B9C (U+18B9C): L&lt;&lt;530.0,567.0&gt;--&lt;529.0,-21.0&gt;&gt;

* u18B9C.001: L&lt;&lt;-175.0,767.0&gt;--&lt;-636.0,768.0&gt;&gt;

* u18B9C.001: L&lt;&lt;-767.0,830.0&gt;--&lt;-179.0,829.0&gt;&gt;

* u18B9C.002: L&lt;&lt;233.0,330.0&gt;--&lt;821.0,329.0&gt;&gt;

* u18B9C.002: L&lt;&lt;825.0,267.0&gt;--&lt;364.0,268.0&gt;&gt;

* u18B9C.003: L&lt;&lt;233.0,-170.0&gt;--&lt;821.0,-171.0&gt;&gt;

* u18B9C.003: L&lt;&lt;825.0,-233.0&gt;--&lt;364.0,-232.0&gt;&gt;

* u18B9D (U+18B9D): L&lt;&lt;477.0,-14.0&gt;--&lt;478.0,439.0&gt;&gt;

* u18B9D (U+18B9D): L&lt;&lt;540.0,569.0&gt;--&lt;539.0,-9.0&gt;&gt;

* u18B9D.001: L&lt;&lt;-186.0,777.0&gt;--&lt;-639.0,778.0&gt;&gt;

* u18B9D.001: L&lt;&lt;-769.0,840.0&gt;--&lt;-191.0,839.0&gt;&gt;

* u18B9D.002: L&lt;&lt;231.0,340.0&gt;--&lt;809.0,339.0&gt;&gt;

* u18B9D.002: L&lt;&lt;814.0,277.0&gt;--&lt;361.0,278.0&gt;&gt;

* u18B9D.003: L&lt;&lt;231.0,-160.0&gt;--&lt;809.0,-161.0&gt;&gt;

* u18B9D.003: L&lt;&lt;814.0,-223.0&gt;--&lt;361.0,-222.0&gt;&gt;

* u18B9E (U+18B9E): L&lt;&lt;477.0,-13.0&gt;--&lt;478.0,439.0&gt;&gt;

* u18B9E (U+18B9E): L&lt;&lt;540.0,569.0&gt;--&lt;539.0,-8.0&gt;&gt;

* u18B9E.001: L&lt;&lt;-187.0,777.0&gt;--&lt;-639.0,778.0&gt;&gt;

* u18B9E.001: L&lt;&lt;-769.0,840.0&gt;--&lt;-192.0,839.0&gt;&gt;

* u18B9E.002: L&lt;&lt;231.0,340.0&gt;--&lt;808.0,339.0&gt;&gt;

* u18B9E.002: L&lt;&lt;813.0,277.0&gt;--&lt;361.0,278.0&gt;&gt;

* u18B9E.003: L&lt;&lt;231.0,-160.0&gt;--&lt;808.0,-161.0&gt;&gt;

* u18B9E.003: L&lt;&lt;813.0,-223.0&gt;--&lt;361.0,-222.0&gt;&gt;

* u18B9F (U+18B9F): L&lt;&lt;493.0,-24.0&gt;--&lt;494.0,383.0&gt;&gt;

* u18B9F (U+18B9F): L&lt;&lt;556.0,387.0&gt;--&lt;555.0,-19.0&gt;&gt;

* u18B9F.001: L&lt;&lt;-176.0,793.0&gt;--&lt;-583.0,794.0&gt;&gt;

* u18B9F.001: L&lt;&lt;-587.0,856.0&gt;--&lt;-181.0,855.0&gt;&gt;

* u18B9F.002: L&lt;&lt;413.0,356.0&gt;--&lt;819.0,355.0&gt;&gt;

* u18B9F.002: L&lt;&lt;824.0,293.0&gt;--&lt;417.0,294.0&gt;&gt;

* u18B9F.003: L&lt;&lt;413.0,-144.0&gt;--&lt;819.0,-145.0&gt;&gt;

* u18B9F.003: L&lt;&lt;824.0,-207.0&gt;--&lt;417.0,-206.0&gt;&gt;

* u18BA2 (U+18BA2): L&lt;&lt;469.0,-51.0&gt;--&lt;470.0,292.0&gt;&gt;

* u18BA2 (U+18BA2): L&lt;&lt;532.0,296.0&gt;--&lt;531.0,-46.0&gt;&gt;

* u18BA2.001: L&lt;&lt;-149.0,769.0&gt;--&lt;-492.0,770.0&gt;&gt;

* u18BA2.001: L&lt;&lt;-496.0,832.0&gt;--&lt;-154.0,831.0&gt;&gt;

* u18BA2.002: L&lt;&lt;504.0,332.0&gt;--&lt;846.0,331.0&gt;&gt;

* u18BA2.002: L&lt;&lt;851.0,269.0&gt;--&lt;508.0,270.0&gt;&gt;

* u18BA2.003: L&lt;&lt;504.0,-168.0&gt;--&lt;846.0,-169.0&gt;&gt;

* u18BA2.003: L&lt;&lt;851.0,-231.0&gt;--&lt;508.0,-230.0&gt;&gt;

* u18BA7 (U+18BA7): L&lt;&lt;467.0,-25.0&gt;--&lt;468.0,436.0&gt;&gt;

* u18BA7 (U+18BA7): L&lt;&lt;530.0,567.0&gt;--&lt;529.0,177.0&gt;&gt;

* u18BA7.001: L&lt;&lt;-175.0,767.0&gt;--&lt;-636.0,768.0&gt;&gt;

* u18BA7.001: L&lt;&lt;-767.0,830.0&gt;--&lt;-377.0,829.0&gt;&gt;

* u18BA7.002: L&lt;&lt;233.0,330.0&gt;--&lt;623.0,329.0&gt;&gt;

* u18BA7.002: L&lt;&lt;825.0,267.0&gt;--&lt;364.0,268.0&gt;&gt;

* u18BA7.003: L&lt;&lt;233.0,-170.0&gt;--&lt;623.0,-171.0&gt;&gt;

* u18BA7.003: L&lt;&lt;825.0,-233.0&gt;--&lt;364.0,-232.0&gt;&gt;

* u18BA8 (U+18BA8): L&lt;&lt;459.0,20.0&gt;--&lt;460.0,450.0&gt;&gt;

* u18BA8 (U+18BA8): L&lt;&lt;522.0,572.0&gt;--&lt;521.0,206.0&gt;&gt;

* u18BA8.001: L&lt;&lt;-220.0,759.0&gt;--&lt;-650.0,760.0&gt;&gt;

* u18BA8.001: L&lt;&lt;-772.0,822.0&gt;--&lt;-406.0,821.0&gt;&gt;

* u18BA8.002: L&lt;&lt;228.0,322.0&gt;--&lt;594.0,321.0&gt;&gt;

* u18BA8.002: L&lt;&lt;780.0,259.0&gt;--&lt;350.0,260.0&gt;&gt;

* u18BA8.003: L&lt;&lt;228.0,-178.0&gt;--&lt;594.0,-179.0&gt;&gt;

* u18BA8.003: L&lt;&lt;780.0,-241.0&gt;--&lt;350.0,-240.0&gt;&gt;

* u18BAA (U+18BAA): L&lt;&lt;477.0,-14.0&gt;--&lt;478.0,439.0&gt;&gt;

* u18BAA (U+18BAA): L&lt;&lt;540.0,569.0&gt;--&lt;539.0,191.0&gt;&gt;

* u18BAA.001: L&lt;&lt;-186.0,777.0&gt;--&lt;-639.0,778.0&gt;&gt;

* u18BAA.001: L&lt;&lt;-769.0,840.0&gt;--&lt;-391.0,839.0&gt;&gt;

* u18BAA.002: L&lt;&lt;231.0,340.0&gt;--&lt;609.0,339.0&gt;&gt;

* u18BAA.002: L&lt;&lt;814.0,277.0&gt;--&lt;361.0,278.0&gt;&gt;

* u18BAA.003: L&lt;&lt;231.0,-160.0&gt;--&lt;609.0,-161.0&gt;&gt;

* u18BAA.003: L&lt;&lt;814.0,-223.0&gt;--&lt;361.0,-222.0&gt;&gt;

* u18BAB (U+18BAB): L&lt;&lt;145.0,29.0&gt;--&lt;146.0,148.0&gt;&gt;

* u18BAB (U+18BAB): L&lt;&lt;146.0,148.0&gt;--&lt;145.0,268.0&gt;&gt;

* u18BAB.001: L&lt;&lt;-229.0,445.0&gt;--&lt;-348.0,446.0&gt;&gt;

* u18BAB.001: L&lt;&lt;-348.0,446.0&gt;--&lt;-468.0,445.0&gt;&gt;

* u18BAB.002: L&lt;&lt;652.0,-54.0&gt;--&lt;532.0,-55.0&gt;&gt;

* u18BAB.002: L&lt;&lt;771.0,-55.0&gt;--&lt;652.0,-54.0&gt;&gt;

* u18BAB.003: L&lt;&lt;652.0,-554.0&gt;--&lt;532.0,-555.0&gt;&gt;

* u18BAB.003: L&lt;&lt;771.0,-555.0&gt;--&lt;652.0,-554.0&gt;&gt;

* u18BC4 (U+18BC4): L&lt;&lt;208.0,555.0&gt;--&lt;207.0,424.0&gt;&gt;

* u18BC4.001: L&lt;&lt;-757.0,508.0&gt;--&lt;-626.0,507.0&gt;&gt;

* u18BC4.002: L&lt;&lt;243.0,8.0&gt;--&lt;374.0,7.0&gt;&gt;

* u18BC4.003: L&lt;&lt;243.0,-492.0&gt;--&lt;374.0,-493.0&gt;&gt;

* u18BC5 (U+18BC5): L&lt;&lt;208.0,555.0&gt;--&lt;207.0,424.0&gt;&gt;

* u18BC5.001: L&lt;&lt;-757.0,508.0&gt;--&lt;-626.0,507.0&gt;&gt;

* u18BC5.002: L&lt;&lt;243.0,8.0&gt;--&lt;374.0,7.0&gt;&gt;

* u18BC5.003: L&lt;&lt;243.0,-492.0&gt;--&lt;374.0,-493.0&gt;&gt;

* u18BC7 (U+18BC7): L&lt;&lt;530.0,475.0&gt;--&lt;529.0,211.0&gt;&gt;

* u18BC7.001: L&lt;&lt;-675.0,830.0&gt;--&lt;-411.0,829.0&gt;&gt;

* u18BC7.002: L&lt;&lt;325.0,330.0&gt;--&lt;589.0,329.0&gt;&gt;

* u18BC7.003: L&lt;&lt;325.0,-170.0&gt;--&lt;589.0,-171.0&gt;&gt;

* u18BC9 (U+18BC9): L&lt;&lt;530.0,459.0&gt;--&lt;529.0,211.0&gt;&gt;

* u18BC9.001: L&lt;&lt;-659.0,830.0&gt;--&lt;-411.0,829.0&gt;&gt;

* u18BC9.002: L&lt;&lt;341.0,330.0&gt;--&lt;589.0,329.0&gt;&gt;

* u18BC9.003: L&lt;&lt;341.0,-170.0&gt;--&lt;589.0,-171.0&gt;&gt;

* u18BCA (U+18BCA): L&lt;&lt;261.0,357.0&gt;--&lt;260.0,197.0&gt;&gt;

* u18BCA.001: L&lt;&lt;-557.0,561.0&gt;--&lt;-397.0,560.0&gt;&gt;

* u18BCA.002: L&lt;&lt;443.0,61.0&gt;--&lt;603.0,60.0&gt;&gt;

* u18BCA.003: L&lt;&lt;443.0,-439.0&gt;--&lt;603.0,-440.0&gt;&gt;

* u18BCC (U+18BCC): L&lt;&lt;229.0,345.0&gt;--&lt;230.0,182.0&gt;&gt;

* u18BCC.001: L&lt;&lt;-545.0,529.0&gt;--&lt;-382.0,530.0&gt;&gt;

* u18BCC.002: L&lt;&lt;455.0,29.0&gt;--&lt;618.0,30.0&gt;&gt;

* u18BCC.003: L&lt;&lt;455.0,-471.0&gt;--&lt;618.0,-470.0&gt;&gt;

* u18BD0 (U+18BD0): L&lt;&lt;184.0,332.0&gt;--&lt;183.0,177.0&gt;&gt;

* u18BD0 (U+18BD0): L&lt;&lt;467.0,-38.0&gt;--&lt;468.0,445.0&gt;&gt;

* u18BD0 (U+18BD0): L&lt;&lt;530.0,585.0&gt;--&lt;529.0,-34.0&gt;&gt;

* u18BD0 (U+18BD0): L&lt;&lt;698.0,353.0&gt;--&lt;697.0,205.0&gt;&gt;

* u18BD0.001: L&lt;&lt;-162.0,767.0&gt;--&lt;-645.0,768.0&gt;&gt;

* u18BD0.001: L&lt;&lt;-532.0,484.0&gt;--&lt;-377.0,483.0&gt;&gt;

* u18BD0.001: L&lt;&lt;-553.0,998.0&gt;--&lt;-405.0,997.0&gt;&gt;

* u18BD0.001: L&lt;&lt;-785.0,830.0&gt;--&lt;-166.0,829.0&gt;&gt;

* u18BD0.002: L&lt;&lt;215.0,330.0&gt;--&lt;834.0,329.0&gt;&gt;

* u18BD0.002: L&lt;&lt;447.0,498.0&gt;--&lt;595.0,497.0&gt;&gt;

* u18BD0.002: L&lt;&lt;468.0,-16.0&gt;--&lt;623.0,-17.0&gt;&gt;

* u18BD0.002: L&lt;&lt;838.0,267.0&gt;--&lt;355.0,268.0&gt;&gt;

* u18BD0.003: L&lt;&lt;215.0,-170.0&gt;--&lt;834.0,-171.0&gt;&gt;

* u18BD0.003: L&lt;&lt;447.0,-2.0&gt;--&lt;595.0,-3.0&gt;&gt;

* u18BD0.003: L&lt;&lt;468.0,-516.0&gt;--&lt;623.0,-517.0&gt;&gt;

* u18BD0.003: L&lt;&lt;838.0,-233.0&gt;--&lt;355.0,-232.0&gt;&gt;

* u18BD3 (U+18BD3): L&lt;&lt;531.0,114.0&gt;--&lt;530.0,-154.0&gt;&gt;

* u18BD3.001: L&lt;&lt;-314.0,831.0&gt;--&lt;-46.0,830.0&gt;&gt;

* u18BD3.002: L&lt;&lt;686.0,331.0&gt;--&lt;954.0,330.0&gt;&gt;

* u18BD3.003: L&lt;&lt;686.0,-169.0&gt;--&lt;954.0,-170.0&gt;&gt;

* u18BD4 (U+18BD4): L&lt;&lt;269.0,281.0&gt;--&lt;268.0,148.0&gt;&gt;

* u18BD4.001: L&lt;&lt;-481.0,569.0&gt;--&lt;-348.0,568.0&gt;&gt;

* u18BD4.002: L&lt;&lt;519.0,69.0&gt;--&lt;652.0,68.0&gt;&gt;

* u18BD4.003: L&lt;&lt;519.0,-431.0&gt;--&lt;652.0,-432.0&gt;&gt;

* u18BD5 (U+18BD5): L&lt;&lt;284.0,345.0&gt;--&lt;285.0,208.0&gt;&gt;

* u18BD5.001: L&lt;&lt;-545.0,584.0&gt;--&lt;-408.0,585.0&gt;&gt;

* u18BD5.002: L&lt;&lt;455.0,84.0&gt;--&lt;592.0,85.0&gt;&gt;

* u18BD5.003: L&lt;&lt;455.0,-416.0&gt;--&lt;592.0,-415.0&gt;&gt;

* u18BD9 (U+18BD9): L&lt;&lt;784.0,207.0&gt;--&lt;783.0,49.0&gt;&gt;

* u18BD9.001: L&lt;&lt;-407.0,1084.0&gt;--&lt;-249.0,1083.0&gt;&gt;

* u18BD9.002: L&lt;&lt;593.0,584.0&gt;--&lt;751.0,583.0&gt;&gt;

* u18BD9.003: L&lt;&lt;593.0,84.0&gt;--&lt;751.0,83.0&gt;&gt;

* u18BDA (U+18BDA): L&lt;&lt;724.0,282.0&gt;--&lt;723.0,49.0&gt;&gt;

* u18BDA.001: L&lt;&lt;-482.0,1024.0&gt;--&lt;-249.0,1023.0&gt;&gt;

* u18BDA.002: L&lt;&lt;518.0,524.0&gt;--&lt;751.0,523.0&gt;&gt;

* u18BDA.003: L&lt;&lt;518.0,24.0&gt;--&lt;751.0,23.0&gt;&gt;

* u18C0E (U+18C0E): L&lt;&lt;565.0,547.0&gt;--&lt;564.0,394.0&gt;&gt;

* u18C0E.001: L&lt;&lt;-747.0,865.0&gt;--&lt;-594.0,864.0&gt;&gt;

* u18C0E.002: L&lt;&lt;253.0,365.0&gt;--&lt;406.0,364.0&gt;&gt;

* u18C0E.003: L&lt;&lt;253.0,-135.0&gt;--&lt;406.0,-136.0&gt;&gt;

* u18C60 (U+18C60): L&lt;&lt;447.0,23.0&gt;--&lt;448.0,173.0&gt;&gt;

* u18C60 (U+18C60): L&lt;&lt;448.0,173.0&gt;--&lt;447.0,325.0&gt;&gt;

* u18C60.001: L&lt;&lt;-224.0,747.0&gt;--&lt;-374.0,748.0&gt;&gt;

* u18C60.001: L&lt;&lt;-374.0,748.0&gt;--&lt;-526.0,747.0&gt;&gt;

* u18C60.002: L&lt;&lt;626.0,248.0&gt;--&lt;474.0,247.0&gt;&gt;

* u18C60.002: L&lt;&lt;776.0,247.0&gt;--&lt;626.0,248.0&gt;&gt;

* u18C60.003: L&lt;&lt;626.0,-252.0&gt;--&lt;474.0,-253.0&gt;&gt;

* u18C60.003: L&lt;&lt;776.0,-253.0&gt;--&lt;626.0,-252.0&gt;&gt;

* u18C67 (U+18C67): L&lt;&lt;210.0,17.0&gt;--&lt;211.0,163.0&gt;&gt;

* u18C67 (U+18C67): L&lt;&lt;211.0,163.0&gt;--&lt;210.0,312.0&gt;&gt;

* u18C67 (U+18C67): L&lt;&lt;824.0,135.0&gt;--&lt;825.0,-18.0&gt;&gt;

* u18C67.001: L&lt;&lt;-217.0,510.0&gt;--&lt;-363.0,511.0&gt;&gt;

* u18C67.001: L&lt;&lt;-335.0,1124.0&gt;--&lt;-182.0,1125.0&gt;&gt;

* u18C67.001: L&lt;&lt;-363.0,511.0&gt;--&lt;-512.0,510.0&gt;&gt;

* u18C67.002: L&lt;&lt;637.0,11.0&gt;--&lt;488.0,10.0&gt;&gt;

* u18C67.002: L&lt;&lt;665.0,624.0&gt;--&lt;818.0,625.0&gt;&gt;

* u18C67.002: L&lt;&lt;783.0,10.0&gt;--&lt;637.0,11.0&gt;&gt;

* u18C67.003: L&lt;&lt;637.0,-489.0&gt;--&lt;488.0,-490.0&gt;&gt;

* u18C67.003: L&lt;&lt;665.0,124.0&gt;--&lt;818.0,125.0&gt;&gt;

* u18C67.003: L&lt;&lt;783.0,-490.0&gt;--&lt;637.0,-489.0&gt;&gt;

* u18C81 (U+18C81): L&lt;&lt;554.0,272.0&gt;--&lt;553.0,-20.0&gt;&gt;

* u18C81.001: L&lt;&lt;-472.0,854.0&gt;--&lt;-180.0,853.0&gt;&gt;

* u18C81.002: L&lt;&lt;528.0,354.0&gt;--&lt;820.0,353.0&gt;&gt;

* u18C81.003: L&lt;&lt;528.0,-146.0&gt;--&lt;820.0,-147.0&gt;&gt;

* u18C89 (U+18C89): L&lt;&lt;146.0,20.0&gt;--&lt;147.0,169.0&gt;&gt;

* u18C89 (U+18C89): L&lt;&lt;147.0,169.0&gt;--&lt;146.0,319.0&gt;&gt;

* u18C89 (U+18C89): L&lt;&lt;854.0,145.0&gt;--&lt;855.0,-11.0&gt;&gt;

* u18C89.001: L&lt;&lt;-220.0,446.0&gt;--&lt;-369.0,447.0&gt;&gt;

* u18C89.001: L&lt;&lt;-345.0,1154.0&gt;--&lt;-189.0,1155.0&gt;&gt;

* u18C89.001: L&lt;&lt;-369.0,447.0&gt;--&lt;-519.0,446.0&gt;&gt;

* u18C89.002: L&lt;&lt;631.0,-53.0&gt;--&lt;481.0,-54.0&gt;&gt;

* u18C89.002: L&lt;&lt;655.0,654.0&gt;--&lt;811.0,655.0&gt;&gt;

* u18C89.002: L&lt;&lt;780.0,-54.0&gt;--&lt;631.0,-53.0&gt;&gt;

* u18C89.003: L&lt;&lt;631.0,-553.0&gt;--&lt;481.0,-554.0&gt;&gt;

* u18C89.003: L&lt;&lt;655.0,154.0&gt;--&lt;811.0,155.0&gt;&gt;

* u18C89.003: L&lt;&lt;780.0,-554.0&gt;--&lt;631.0,-553.0&gt;&gt;

* u18C8B (U+18C8B): L&lt;&lt;463.0,67.0&gt;--&lt;464.0,214.0&gt;&gt;

* u18C8B (U+18C8B): L&lt;&lt;525.0,218.0&gt;--&lt;524.0,-21.0&gt;&gt;

* u18C8B.001: L&lt;&lt;-267.0,763.0&gt;--&lt;-414.0,764.0&gt;&gt;

* u18C8B.001: L&lt;&lt;-418.0,825.0&gt;--&lt;-179.0,824.0&gt;&gt;

* u18C8B.002: L&lt;&lt;582.0,325.0&gt;--&lt;821.0,324.0&gt;&gt;

* u18C8B.002: L&lt;&lt;733.0,263.0&gt;--&lt;586.0,264.0&gt;&gt;

* u18C8B.003: L&lt;&lt;582.0,-175.0&gt;--&lt;821.0,-176.0&gt;&gt;

* u18C8B.003: L&lt;&lt;733.0,-237.0&gt;--&lt;586.0,-236.0&gt;&gt;

* u18C8D (U+18C8D): L&lt;&lt;535.0,263.0&gt;--&lt;534.0,-35.0&gt;&gt;

* u18C8D.001: L&lt;&lt;-464.0,835.0&gt;--&lt;-166.0,834.0&gt;&gt;

* u18C8D.002: L&lt;&lt;536.0,335.0&gt;--&lt;834.0,334.0&gt;&gt;

* u18C8D.003: L&lt;&lt;536.0,-165.0&gt;--&lt;834.0,-166.0&gt;&gt;

* u18C8F (U+18C8F): L&lt;&lt;595.0,523.0&gt;--&lt;596.0,222.0&gt;&gt;

* u18C8F.001: L&lt;&lt;-723.0,895.0&gt;--&lt;-422.0,896.0&gt;&gt;

* u18C8F.002: L&lt;&lt;277.0,395.0&gt;--&lt;578.0,396.0&gt;&gt;

* u18C8F.003: L&lt;&lt;277.0,-105.0&gt;--&lt;578.0,-104.0&gt;&gt;

* u18C94 (U+18C94): L&lt;&lt;614.0,116.0&gt;--&lt;615.0,481.0&gt;&gt;

* u18C94 (U+18C94): L&lt;&lt;679.0,566.0&gt;--&lt;677.0,-10.0&gt;&gt;

* u18C94.001: L&lt;&lt;-316.0,914.0&gt;--&lt;-681.0,915.0&gt;&gt;

* u18C94.001: L&lt;&lt;-766.0,979.0&gt;--&lt;-190.0,977.0&gt;&gt;

* u18C94.002: L&lt;&lt;234.0,479.0&gt;--&lt;810.0,477.0&gt;&gt;

* u18C94.002: L&lt;&lt;684.0,414.0&gt;--&lt;319.0,415.0&gt;&gt;

* u18C94.003: L&lt;&lt;234.0,-21.0&gt;--&lt;810.0,-23.0&gt;&gt;

* u18C94.003: L&lt;&lt;684.0,-86.0&gt;--&lt;319.0,-85.0&gt;&gt;

* u18C99 (U+18C99): L&lt;&lt;301.0,201.0&gt;--&lt;302.0,56.0&gt;&gt;

* u18C99.001: L&lt;&lt;-401.0,601.0&gt;--&lt;-256.0,602.0&gt;&gt;

* u18C99.002: L&lt;&lt;599.0,101.0&gt;--&lt;744.0,102.0&gt;&gt;

* u18C99.003: L&lt;&lt;599.0,-399.0&gt;--&lt;744.0,-398.0&gt;&gt;

* u18CD0 (U+18CD0): L&lt;&lt;522.0,-36.0&gt;--&lt;523.0,-151.0&gt;&gt;

* u18CD0.001: L&lt;&lt;-164.0,822.0&gt;--&lt;-49.0,823.0&gt;&gt;

* u18CD0.002: L&lt;&lt;836.0,322.0&gt;--&lt;951.0,323.0&gt;&gt;

* u18CD0.003: L&lt;&lt;836.0,-178.0&gt;--&lt;951.0,-177.0&gt;&gt;

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







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoFangsongKSSRotated/googlefonts/ttf/NotoFangsongKSSRotated-Regular.ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 5 | 12 | 117 | 6 | 111 | 0 | 
| 0% | 0% | 2% | 5% | 47% | 2% | 44% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
