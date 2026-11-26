## FontSpector report

fontspector version: 1.9.0






## Check results




<details><summary>[1] fonts/ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Ensure Fonts have 'ital' STAT axis. (opentype/STAT/ital_axis)</summary>
    <div>








- ⚠️ **WARN** Static font is missing the 'STAT' table. [code: no-stat-table]
  
  

</div>
</details>


</div>
</details>


<details><summary>[13] fonts/ttf/CCSellipiCANARY-Regular.ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     inferred from the typical amounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* uni0D85 (U+0D85): found 1, expected one of: [2, 3, 4]
* uni0D86 (U+0D86): found 2, expected one of: [3, 4, 5]
* uni0D87 (U+0D87): found 2, expected one of: [3, 4, 5]
* uni0D88 (U+0D88): found 2, expected one of: [3, 4, 5]
* uni0D89 (U+0D89): found 1, expected one of: [2, 3, 4]
* uni0D8A (U+0D8A): found 3, expected one of: [4, 5, 6]
* uni0D91 (U+0D91): found 1, expected one of: [2, 3]
* uni0D92 (U+0D92): found 2, expected one of: [3, 4, 5]
* uni0D93 (U+0D93): found 2, expected one of: [4, 5, 6]
* uni0D95 (U+0D95): found 2, expected one of: [3, 4]
* uni0D9B (U+0D9B): found 1, expected one of: [2, 3]
* uni0D9E (U+0D9E): found 1, expected one of: [2, 3, 4]
* uni0DA1 (U+0DA1): found 2, expected one of: [3, 4, 5]
* uni0DA3 (U+0DA3): found 2, expected one of: [3, 4]
* uni0DA5 (U+0DA5): found 1, expected one of: [2, 3, 5]
* uni0DA8 (U+0DA8): found 1, expected one of: [2, 3]
* uni0DAA (U+0DAA): found 1, expected one of: [2, 3, 4]
* uni0DAE (U+0DAE): found 1, expected one of: [2, 3]
* uni0DB9 (U+0DB9): found 1, expected one of: [2, 3]
* uni0DBB (U+0DBB): found 1, expected one of: [2, 3]
* uni0DC1 (U+0DC1): found 1, expected one of: [2, 3, 4]
* uni0DD3 (U+0DD3): found 1, expected one of: [2, 3]
* two (U+0032): found 9, expected one of: [1, 2, 5] [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? (gpos_kerning_info)</summary>
    <div>








- ⚠️ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 272 among a set of 4  math glyphs.
The following math glyphs have a different width, though:
width=394: equal
width=322: divide [code: width-outliers]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. (Overriden: Sinhala fonts: U+20B9 is optional (Sri Lanka writes රු / Rs)) [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* gasinh.alt1
* kSsasinh.alt1
* viramasinh.alt1 [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* bIisinh
* uni0DDA (U+0DDA)
* mIisinh
* uni0D92 (U+0D92)
* uni0DDD (U+0DDD)
* khIisinh [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? (outline_alignment_miss)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

* - uni0D9D (U+0D9D): X=557,Y=-2 (should be at baseline 0?)
* - uni0D9D (U+0D9D): X=557,Y=-2 (should be at cap-height 0?)
* - uni0D9D (U+0D9D): X=558.5,Y=-1.5 (should be at baseline 0?)
* - uni0D9D (U+0D9D): X=558.5,Y=-1.5 (should be at cap-height 0?)
* - uni0D9D (U+0D9D): X=560,Y=-1 (should be at baseline 0?)
* - uni0D9D (U+0D9D): X=560,Y=-1 (should be at cap-height 0?)
* - uni0D9D (U+0D9D): X=562,Y=-1 (should be at baseline 0?)
* - uni0D9D (U+0D9D): X=562,Y=-1 (should be at cap-height 0?)
* - uni0D9D (U+0D9D): X=563,Y=-1 (should be at baseline 0?)
* - uni0D9D (U+0D9D): X=563,Y=-1 (should be at cap-height 0?)
* - uni0D9D (U+0D9D): X=572,Y=2 (should be at baseline 0?)
* - uni0D9D (U+0D9D): X=572,Y=2 (should be at cap-height 0?)
* - uni0D9D (U+0D9D): X=110,Y=2.5 (should be at baseline 0?)
* - uni0D9D (U+0D9D): X=110,Y=2.5 (should be at cap-height 0?)
* - uni0DB3 (U+0DB3): X=513,Y=-2 (should be at baseline 0?)
* - uni0DB3 (U+0DB3): X=513,Y=-2 (should be at cap-height 0?)
* - uni0DB3 (U+0DB3): X=513,Y=-2 (should be at baseline 0?)
* - uni0DB3 (U+0DB3): X=513,Y=-2 (should be at cap-height 0?)
* - uni0DBB (U+0DBB): X=247.5,Y=2 (should be at baseline 0?)
* - uni0DBB (U+0DBB): X=247.5,Y=2 (should be at cap-height 0?)
* - uni0DC1 (U+0DC1): X=623,Y=2 (should be at baseline 0?)
* - uni0DC1 (U+0DC1): X=623,Y=2 (should be at cap-height 0?)
* - rasignsinh: X=-121.5,Y=1.5 (should be at baseline 0?)
* - rasignsinh: X=-121.5,Y=1.5 (should be at cap-height 0?)
* - khsinh: X=513,Y=-1 (should be at baseline 0?)
* - khsinh: X=513,Y=-1 (should be at cap-height 0?)
* - khIsinh: X=464,Y=-2 (should be at baseline 0?)
* - khIsinh: X=464,Y=-2 (should be at cap-height 0?)
* - khIisinh: X=420,Y=2 (should be at baseline 0?)
* - khIisinh: X=420,Y=2 (should be at cap-height 0?)
* - khIisinh: X=109,Y=2 (should be at baseline 0?)
* - khIisinh: X=109,Y=2 (should be at cap-height 0?)
* - rUsinh: X=247.5,Y=2 (should be at baseline 0?)
* - rUsinh: X=247.5,Y=2 (should be at cap-height 0?)
* - lUsinh: X=287.5,Y=-1 (should be at baseline 0?)
* - lUsinh: X=287.5,Y=-1 (should be at cap-height 0?)
* - rUusinh: X=247.5,Y=2 (should be at baseline 0?)
* - rUusinh: X=247.5,Y=2 (should be at cap-height 0?)
* - rAaesinh: X=711,Y=-1 (should be at baseline 0?)
* - rAaesinh: X=711,Y=-1 (should be at cap-height 0?)
* - dRasinh: X=211.5,Y=-1.5 (should be at baseline 0?)
* - dRasinh: X=211.5,Y=-1.5 (should be at cap-height 0?)
* - daa._csinh: X=369,Y=-2 (should be at baseline 0?)
* - daa._csinh: X=369,Y=-2 (should be at cap-height 0?)
* - percent (U+0025): X=364.5,Y=2 (should be at baseline 0?)
* - percent (U+0025): X=364.5,Y=2 (should be at cap-height 0?) [code: found-misalignments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* uni0D88 (U+0D88): from (515.0, 283.0) to (515.0, 283.0) is colinear with segment from (515.0, 283.0) to (515.0, 283.0)
* uni0DD1 (U+0DD1): from (47.0, 283.0) to (47.0, 283.0) is colinear with segment from (47.0, 283.0) to (47.0, 283.0)
* rUusinh: from (552.0, 283.0) to (552.0, 283.0) is colinear with segment from (552.0, 283.0) to (552.0, 283.0)
* two (U+0032): from (105.0, 334.0) to (105.0, 334.0) is colinear with segment from (105.0, 334.0) to (105.0, 334.0)
* four (U+0034): from (246.0, 380.0) to (246.0, 380.0) is colinear with segment from (246.0, 380.0) to (246.0, 380.0)
* five (U+0035): from (271.0, 486.0) to (271.0, 486.0) is colinear with segment from (271.0, 486.0) to (271.0, 486.0)
* five (U+0035): from (271.0, 486.0) to (271.0, 486.0) is colinear with segment from (271.0, 486.0) to (271.0, 486.0)
* five (U+0035): from (271.0, 486.0) to (271.0, 486.0) is colinear with segment from (271.0, 486.0) to (271.0, 486.0)
* five (U+0035): from (267.0, 521.0) to (267.0, 521.0) is colinear with segment from (267.0, 521.0) to (267.0, 521.0)
* five (U+0035): from (267.0, 521.0) to (267.0, 521.0) is colinear with segment from (267.0, 521.0) to (267.0, 521.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph (outline_direction)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have a counter-clockwise outer contour:

* rephasinh has a path with no bounds (probably a single point)
* bIisinh has a path with no bounds (probably a single point)
* mIisinh has a path with no bounds (probably a single point)
* mIisinh has a path with no bounds (probably a single point)
* mIisinh has a path with no bounds (probably a single point)
* mIisinh has a path with no bounds (probably a single point)
* mIisinh has a path with no bounds (probably a single point)
* mIisinh has a path with no bounds (probably a single point)
* yasignsinh has a path with no bounds (probably a single point)
* zero (U+0030) has a path with no bounds (probably a single point)
* two (U+0032) has a path with no bounds (probably a single point)
* two (U+0032) has a path with no bounds (probably a single point)
* two (U+0032) has a path with no bounds (probably a single point)
* two (U+0032) has a path with no bounds (probably a single point)
* two (U+0032) has a path with no bounds (probably a single point)
* two (U+0032) has a path with no bounds (probably a single point)
* two (U+0032) has a path with no bounds (probably a single point)
* four (U+0034) has a path with no bounds (probably a single point)
* four (U+0034) has a path with no bounds (probably a single point)
* four (U+0034) has a path with no bounds (probably a single point)
* four (U+0034) has a path with no bounds (probably a single point)
* eight (U+0038) has a path with no bounds (probably a single point)
* uniE001 (U+E001) has a path with no bounds (probably a single point) [code: ccw-outer-contour]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* uni0D8B (U+0D8B): Quad(QuadBez { p0: (146.0, 253.0), p1: (148.0, 258.0), p2: (149.0, 261.0) })/Quad(QuadBez { p0: (149.0, 261.0), p1: (148.0, 259.0), p2: (148.5, 262.0) }) = 8.130102354156051 degrees
* uni0D8C (U+0D8C): Quad(QuadBez { p0: (146.0, 253.0), p1: (148.0, 258.0), p2: (149.0, 261.0) })/Quad(QuadBez { p0: (149.0, 261.0), p1: (148.0, 259.0), p2: (148.5, 262.0) }) = 8.130102354156051 degrees
* rephasinh: Quad(QuadBez { p0: (-330.0, 599.0), p1: (-330.0, 599.0), p2: (-329.0, 598.0) })/Quad(QuadBez { p0: (-329.0, 598.0), p1: (-330.0, 599.0), p2: (-330.0, 599.0) }) = 0.0000012074182697257333 degrees
* csinh: Quad(QuadBez { p0: (165.0, 426.0), p1: (162.0, 423.0), p2: (161.0, 422.0) })/Quad(QuadBez { p0: (161.0, 422.0), p1: (163.0, 424.0), p2: (165.0, 426.0) }) = 0.0000012074182697257333 degrees
* ddIsinh: Quad(QuadBez { p0: (205.0, 517.0), p1: (206.0, 509.0), p2: (210.0, 506.0) })/Quad(QuadBez { p0: (210.0, 506.0), p1: (208.0, 508.0), p2: (213.5, 506.0) }) = 8.130102354156005 degrees
* nnddIsinh: Quad(QuadBez { p0: (213.0, 158.0), p1: (214.0, 158.0), p2: (215.0, 158.0) })/Quad(QuadBez { p0: (215.0, 158.0), p1: (193.0, 163.0), p2: (178.5, 181.5) }) = 12.804266065286768 degrees
* ddIisinh: Quad(QuadBez { p0: (423.0, 473.0), p1: (422.0, 473.0), p2: (421.0, 473.0) })/Quad(QuadBez { p0: (421.0, 473.0), p1: (451.0, 468.0), p2: (479.5, 457.5) }) = 9.462322208025613 degrees
* ddIisinh: Quad(QuadBez { p0: (360.0, 480.0), p1: (382.0, 479.0), p2: (404.0, 476.0) })/Quad(QuadBez { p0: (404.0, 476.0), p1: (384.0, 481.0), p2: (368.5, 494.5) }) = 6.271077449501227 degrees
* nnddIisinh: Quad(QuadBez { p0: (202.0, 164.0), p1: (203.0, 164.0), p2: (204.0, 164.0) })/Quad(QuadBez { p0: (204.0, 164.0), p1: (182.0, 169.0), p2: (167.5, 187.5) }) = 12.804266065286768 degrees
* mIisinh: Quad(QuadBez { p0: (215.0, 597.0), p1: (185.0, 601.0), p2: (158.0, 598.0) })/Quad(QuadBez { p0: (158.0, 598.0), p1: (159.0, 598.0), p2: (152.5, 597.0) }) = 6.340191745909908 degrees
* vIisinh: Quad(QuadBez { p0: (105.0, 507.5), p1: (92.0, 498.0), p2: (84.0, 485.0) })/Quad(QuadBez { p0: (84.0, 485.0), p1: (90.0, 491.0), p2: (98.5, 492.0) }) = 13.392497753751043 degrees
* seven (U+0037): Quad(QuadBez { p0: (320.0, 538.0), p1: (320.0, 539.0), p2: (321.0, 538.0) })/Quad(QuadBez { p0: (321.0, 538.0), p1: (320.0, 539.0), p2: (320.0, 538.0) }) = 0.0000012074182697257333 degrees
* eight (U+0038): Quad(QuadBez { p0: (133.0, 80.0), p1: (134.0, 79.0), p2: (135.0, 78.0) })/Quad(QuadBez { p0: (135.0, 78.0), p1: (134.0, 79.0), p2: (136.0, 77.0) }) = 0.0000012074182697257333 degrees
* eight (U+0038): Quad(QuadBez { p0: (315.0, 272.0), p1: (313.0, 274.0), p2: (314.0, 273.0) })/Quad(QuadBez { p0: (314.0, 273.0), p1: (308.0, 277.0), p2: (301.0, 281.0) }) = 11.309932474020261 degrees
* eight (U+0038): Quad(QuadBez { p0: (86.0, 565.0), p1: (86.0, 565.0), p2: (87.0, 566.0) })/Quad(QuadBez { p0: (87.0, 566.0), p1: (86.0, 565.0), p2: (86.0, 565.0) }) = 0.0000012074182697257333 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* uni0D88 (U+0D88): Line(Line { p0: (515.0, 283.0), p1: (515.0, 283.0) }) has the same coordinates as a previous segment.
* uni0D9D (U+0D9D): Quad(QuadBez { p0: (59.0, 280.0), p1: (59.0, 280.0), p2: (59.0, 280.0) }) has the same coordinates as a previous segment.
* uni0DD1 (U+0DD1): Line(Line { p0: (47.0, 283.0), p1: (47.0, 283.0) }) has the same coordinates as a previous segment.
* rephasinh: Quad(QuadBez { p0: (-329.0, 598.0), p1: (-330.0, 599.0), p2: (-330.0, 599.0) }) has the same coordinates as a previous segment.
* rephasinh: Quad(QuadBez { p0: (-366.0, 558.0), p1: (-366.0, 558.0), p2: (-365.0, 558.0) }) has the same coordinates as a previous segment.
* csinh: Quad(QuadBez { p0: (161.0, 422.0), p1: (163.0, 424.0), p2: (165.0, 426.0) }) has the same coordinates as a previous segment.
* bIisinh: Quad(QuadBez { p0: (149.0, 541.0), p1: (149.0, 541.0), p2: (149.0, 541.0) }) has the same coordinates as a previous segment.
* bIisinh: Quad(QuadBez { p0: (146.0, 542.0), p1: (146.0, 542.0), p2: (145.0, 542.0) }) has the same coordinates as a previous segment.
* mIisinh: Quad(QuadBez { p0: (207.0, 554.0), p1: (207.0, 554.0), p2: (207.0, 554.0) }) has the same coordinates as a previous segment.
* mIisinh: Line(Line { p0: (207.0, 554.0), p1: (207.0, 554.0) }) has the same coordinates as a previous segment.
* mIisinh: Quad(QuadBez { p0: (207.0, 554.0), p1: (207.0, 554.0), p2: (207.0, 554.0) }) has the same coordinates as a previous segment.
* mIisinh: Quad(QuadBez { p0: (206.0, 554.0), p1: (206.0, 554.0), p2: (206.0, 554.0) }) has the same coordinates as a previous segment.
* mIisinh: Quad(QuadBez { p0: (205.0, 554.0), p1: (206.0, 554.0), p2: (206.0, 554.0) }) has the same coordinates as a previous segment.
* mIisinh: Quad(QuadBez { p0: (205.0, 553.0), p1: (205.0, 553.0), p2: (205.0, 553.0) }) has the same coordinates as a previous segment.
* mIisinh: Quad(QuadBez { p0: (204.0, 553.0), p1: (204.0, 553.0), p2: (205.0, 553.0) }) has the same coordinates as a previous segment.
* dUusinh: Quad(QuadBez { p0: (406.5, -282.5), p1: (403.0, -280.0), p2: (403.0, -281.0) }) has the same coordinates as a previous segment.
* rUusinh: Line(Line { p0: (552.0, 283.0), p1: (552.0, 283.0) }) has the same coordinates as a previous segment.
* lUusinh: Line(Line { p0: (321.0, -92.0), p1: (321.0, -92.0) }) has the same coordinates as a previous segment.
* lUusinh: Quad(QuadBez { p0: (322.0, -93.0), p1: (322.0, -93.0), p2: (322.0, -92.5) }) has the same coordinates as a previous segment.
* lUusinh: Quad(QuadBez { p0: (322.0, -92.0), p1: (323.0, -92.0), p2: (322.0, -92.5) }) has the same coordinates as a previous segment.
* lUusinh: Quad(QuadBez { p0: (530.0, -39.0), p1: (530.0, -39.0), p2: (530.0, -39.0) }) has the same coordinates as a previous segment.
* yasignsinh: Quad(QuadBez { p0: (301.0, 134.0), p1: (301.0, 134.0), p2: (301.0, 134.0) }) has the same coordinates as a previous segment.
* zero (U+0030): Quad(QuadBez { p0: (185.0, 501.0), p1: (185.0, 502.0), p2: (185.0, 502.0) }) has the same coordinates as a previous segment.
* two (U+0032): Quad(QuadBez { p0: (106.0, 334.0), p1: (105.0, 334.0), p2: (106.0, 334.0) }) has the same coordinates as a previous segment.
* two (U+0032): Line(Line { p0: (92.0, 471.0), p1: (92.0, 471.0) }) has the same coordinates as a previous segment.
* two (U+0032): Quad(QuadBez { p0: (74.0, 358.0), p1: (74.0, 358.0), p2: (74.0, 358.0) }) has the same coordinates as a previous segment.
* two (U+0032): Quad(QuadBez { p0: (74.0, 358.0), p1: (74.0, 358.0), p2: (74.0, 358.0) }) has the same coordinates as a previous segment.
* two (U+0032): Line(Line { p0: (106.0, 334.0), p1: (106.0, 334.0) }) has the same coordinates as a previous segment.
* two (U+0032): Quad(QuadBez { p0: (106.0, 334.0), p1: (106.0, 334.0), p2: (106.0, 334.0) }) has the same coordinates as a previous segment.
* two (U+0032): Quad(QuadBez { p0: (107.0, 335.0), p1: (107.0, 335.0), p2: (107.0, 335.0) }) has the same coordinates as a previous segment.
* two (U+0032): Quad(QuadBez { p0: (107.0, 335.0), p1: (107.0, 335.0), p2: (107.0, 335.0) }) has the same coordinates as a previous segment.
* two (U+0032): Quad(QuadBez { p0: (107.0, 335.0), p1: (107.0, 335.0), p2: (107.0, 335.0) }) has the same coordinates as a previous segment.
* two (U+0032): Quad(QuadBez { p0: (107.0, 335.0), p1: (107.0, 335.0), p2: (107.0, 335.0) }) has the same coordinates as a previous segment.
* two (U+0032): Line(Line { p0: (106.0, 335.0), p1: (106.0, 334.0) }) has the same coordinates as a previous segment.
* two (U+0032): Line(Line { p0: (106.0, 334.0), p1: (106.0, 334.0) }) has the same coordinates as a previous segment.
* two (U+0032): Quad(QuadBez { p0: (106.0, 334.0), p1: (106.0, 334.0), p2: (106.0, 334.0) }) has the same coordinates as a previous segment.
* two (U+0032): Quad(QuadBez { p0: (106.0, 334.0), p1: (106.0, 334.0), p2: (106.0, 334.0) }) has the same coordinates as a previous segment.
* two (U+0032): Quad(QuadBez { p0: (106.0, 334.0), p1: (106.0, 335.0), p2: (106.0, 335.0) }) has the same coordinates as a previous segment.
* two (U+0032): Quad(QuadBez { p0: (105.0, 334.0), p1: (105.0, 334.0), p2: (105.0, 334.0) }) has the same coordinates as a previous segment.
* two (U+0032): Line(Line { p0: (105.0, 334.0), p1: (105.0, 334.0) }) has the same coordinates as a previous segment.
* three (U+0033): Quad(QuadBez { p0: (98.0, 389.0), p1: (98.0, 389.0), p2: (97.0, 389.0) }) has the same coordinates as a previous segment.
* three (U+0033): Quad(QuadBez { p0: (97.0, 389.0), p1: (98.0, 388.0), p2: (97.0, 389.0) }) has the same coordinates as a previous segment.
* four (U+0034): Quad(QuadBez { p0: (248.5, 381.0), p1: (248.0, 381.0), p2: (248.0, 381.0) }) has the same coordinates as a previous segment.
* four (U+0034): Quad(QuadBez { p0: (248.0, 381.0), p1: (248.0, 381.0), p2: (248.0, 381.0) }) has the same coordinates as a previous segment.
* four (U+0034): Quad(QuadBez { p0: (248.0, 381.0), p1: (248.0, 381.0), p2: (248.0, 381.0) }) has the same coordinates as a previous segment.
* four (U+0034): Line(Line { p0: (248.0, 381.0), p1: (248.0, 381.0) }) has the same coordinates as a previous segment.
* four (U+0034): Quad(QuadBez { p0: (248.0, 381.0), p1: (248.0, 381.0), p2: (248.0, 381.0) }) has the same coordinates as a previous segment.
* four (U+0034): Quad(QuadBez { p0: (248.0, 381.0), p1: (248.0, 381.0), p2: (248.0, 381.0) }) has the same coordinates as a previous segment.
* four (U+0034): Line(Line { p0: (246.0, 380.0), p1: (246.0, 380.0) }) has the same coordinates as a previous segment.
* four (U+0034): Quad(QuadBez { p0: (247.0, 381.0), p1: (247.0, 381.0), p2: (247.0, 381.0) }) has the same coordinates as a previous segment.
* four (U+0034): Quad(QuadBez { p0: (247.0, 381.0), p1: (247.0, 381.0), p2: (248.0, 381.0) }) has the same coordinates as a previous segment.
* four (U+0034): Line(Line { p0: (248.0, 381.0), p1: (248.0, 381.0) }) has the same coordinates as a previous segment.
* four (U+0034): Quad(QuadBez { p0: (246.0, 380.0), p1: (246.0, 380.0), p2: (246.0, 380.0) }) has the same coordinates as a previous segment.
* four (U+0034): Line(Line { p0: (246.0, 381.0), p1: (247.0, 381.0) }) has the same coordinates as a previous segment.
* four (U+0034): Quad(QuadBez { p0: (247.0, 381.0), p1: (247.0, 381.0), p2: (247.0, 380.5) }) has the same coordinates as a previous segment.
* four (U+0034): Quad(QuadBez { p0: (247.0, 380.5), p1: (247.0, 380.0), p2: (248.0, 380.0) }) has the same coordinates as a previous segment.
* four (U+0034): Quad(QuadBez { p0: (218.0, 362.0), p1: (218.0, 362.0), p2: (218.0, 362.0) }) has the same coordinates as a previous segment.
* four (U+0034): Quad(QuadBez { p0: (218.0, 317.0), p1: (218.0, 318.0), p2: (218.0, 318.0) }) has the same coordinates as a previous segment.
* four (U+0034): Quad(QuadBez { p0: (80.0, 250.0), p1: (80.0, 250.0), p2: (80.0, 250.0) }) has the same coordinates as a previous segment.
* four (U+0034): Quad(QuadBez { p0: (88.0, 238.0), p1: (88.0, 237.0), p2: (89.0, 237.0) }) has the same coordinates as a previous segment.
* four (U+0034): Quad(QuadBez { p0: (89.0, 237.0), p1: (90.0, 236.0), p2: (90.0, 236.0) }) has the same coordinates as a previous segment.
* four (U+0034): Quad(QuadBez { p0: (90.0, 236.0), p1: (89.0, 237.0), p2: (89.0, 237.0) }) has the same coordinates as a previous segment.
* four (U+0034): Line(Line { p0: (89.0, 237.0), p1: (88.0, 238.0) }) has the same coordinates as a previous segment.
* five (U+0035): Line(Line { p0: (271.0, 486.0), p1: (271.0, 486.0) }) has the same coordinates as a previous segment.
* five (U+0035): Line(Line { p0: (271.0, 486.0), p1: (271.0, 486.0) }) has the same coordinates as a previous segment.
* five (U+0035): Quad(QuadBez { p0: (271.0, 486.0), p1: (271.0, 486.0), p2: (271.0, 486.0) }) has the same coordinates as a previous segment.
* five (U+0035): Quad(QuadBez { p0: (271.0, 486.0), p1: (271.0, 486.0), p2: (271.0, 486.0) }) has the same coordinates as a previous segment.
* five (U+0035): Quad(QuadBez { p0: (271.0, 486.0), p1: (271.0, 486.0), p2: (271.0, 486.0) }) has the same coordinates as a previous segment.
* five (U+0035): Line(Line { p0: (271.0, 486.0), p1: (271.0, 486.0) }) has the same coordinates as a previous segment.
* five (U+0035): Line(Line { p0: (271.0, 486.0), p1: (271.0, 486.0) }) has the same coordinates as a previous segment.
* five (U+0035): Line(Line { p0: (271.0, 486.0), p1: (271.0, 486.0) }) has the same coordinates as a previous segment.
* five (U+0035): Quad(QuadBez { p0: (271.0, 486.0), p1: (272.0, 486.0), p2: (271.0, 486.0) }) has the same coordinates as a previous segment.
* five (U+0035): Line(Line { p0: (267.0, 521.0), p1: (267.0, 521.0) }) has the same coordinates as a previous segment.
* five (U+0035): Line(Line { p0: (267.0, 521.0), p1: (267.0, 521.0) }) has the same coordinates as a previous segment.
* seven (U+0037): Quad(QuadBez { p0: (321.0, 538.0), p1: (320.0, 539.0), p2: (320.0, 538.0) }) has the same coordinates as a previous segment.
* seven (U+0037): Quad(QuadBez { p0: (82.0, 499.0), p1: (82.0, 499.0), p2: (82.0, 498.5) }) has the same coordinates as a previous segment.
* eight (U+0038): Quad(QuadBez { p0: (76.0, 539.5), p1: (76.0, 539.0), p2: (76.0, 539.0) }) has the same coordinates as a previous segment.
* eight (U+0038): Quad(QuadBez { p0: (76.0, 538.0), p1: (76.0, 539.0), p2: (76.0, 539.0) }) has the same coordinates as a previous segment.
* eight (U+0038): Quad(QuadBez { p0: (76.0, 539.0), p1: (76.0, 538.0), p2: (76.0, 538.0) }) has the same coordinates as a previous segment.
* eight (U+0038): Quad(QuadBez { p0: (87.0, 566.0), p1: (86.0, 565.0), p2: (86.0, 565.0) }) has the same coordinates as a previous segment.
* eight (U+0038): Quad(QuadBez { p0: (86.0, 565.0), p1: (86.0, 565.0), p2: (87.0, 566.0) }) has the same coordinates as a previous segment.
* eight (U+0038): Quad(QuadBez { p0: (87.0, 566.0), p1: (87.0, 566.0), p2: (87.0, 566.0) }) has the same coordinates as a previous segment.
* uniE001 (U+E001): Quad(QuadBez { p0: (329.0, 496.0), p1: (329.0, 496.0), p2: (329.0, 497.0) }) has the same coordinates as a previous segment.
* uniE001 (U+E001): Quad(QuadBez { p0: (292.0, 455.0), p1: (293.0, 455.0), p2: (293.0, 455.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>


</div>
</details>






### Summary

| ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|
| 14 | 12 | 80 | 51 | 
| 9% | 8% | 51% | 32% | 



