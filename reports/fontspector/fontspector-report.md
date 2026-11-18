## FontSpector report

fontspector version: 1.9.0






## Check results




<details><summary>[19] fonts/ttf/CCSellipiCANARY-Regular.ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- 🔥 **FAIL** No GF glyphset was found to be supported >80%, so language shaping support couldn't get checked. [code: no-glyphset-supported]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Directory name in GFonts repo structure must
    match NameID 1 of the regular. (googlefonts/repo/dirname_matches_nameid_1)</summary>
    <div>








- 🔥 **FAIL** Family name on the name table ('CCSellipi CANARY') does not match directory name in the repo structure ('ttf'). Expected 'ccsellipicanary'. [code: mismatch]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Ensure font can render its own name. (googlefonts/render_own_name)</summary>
    <div>








- 🔥 **FAIL** .notdef glyphs were found when attempting to render CCSellipi CANARY [code: render-own-name]
  
  

</div>
</details>





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
* uni0DAE (U+0DAE): found 1, expected one of: [2, 3]
* uni0D85 (U+0D85): found 1, expected one of: [2, 3, 4]
* uni0D91 (U+0D91): found 1, expected one of: [2, 3]
* uni0DBB (U+0DBB): found 1, expected one of: [2, 3]
* uni0DC1 (U+0DC1): found 1, expected one of: [2, 3, 4]
* uni0D89 (U+0D89): found 1, expected one of: [2, 3, 4]
* uni0DAA (U+0DAA): found 1, expected one of: [2, 3, 4]
* uni0DB9 (U+0DB9): found 1, expected one of: [2, 3]
* uni0DD3 (U+0DD3): found 1, expected one of: [2, 3]
* uni0D8A (U+0D8A): found 3, expected one of: [4, 5, 6]
* uni0DA8 (U+0DA8): found 1, expected one of: [2, 3]
* uni0D9B (U+0D9B): found 1, expected one of: [2, 3]
* uni0DA1 (U+0DA1): found 2, expected one of: [3, 4, 5]
* uni0D95 (U+0D95): found 2, expected one of: [3, 4]
* uni0DA5 (U+0DA5): found 1, expected one of: [2, 3, 5]
* uni0DA3 (U+0DA3): found 2, expected one of: [3, 4]
* two (U+0032): found 9, expected one of: [1, 2, 5]
* uni0D9E (U+0D9E): found 1, expected one of: [2, 3, 4]
* uni0D93 (U+0D93): found 2, expected one of: [4, 5, 6]
* uni0D92 (U+0D92): found 2, expected one of: [3, 4, 5]
* uni0D88 (U+0D88): found 2, expected one of: [3, 4, 5]
* uni0D86 (U+0D86): found 2, expected one of: [3, 4, 5]
* uni0D87 (U+0D87): found 2, expected one of: [3, 4, 5] [code: contour-count]
  
  

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








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* viramasinh.alt1
* kSsasinh.alt1
* gasinh.alt1 [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* uni0DDD (U+0DDD)
* mIisinh
* bIisinh
* uni0D92 (U+0D92)
* uni0DDA (U+0DDA)
* khIisinh [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** Missing separator glyph U+2028 [code: missing-separator-glyphs]
  
  


- ⚠️ **WARN** Missing separator glyph U+2029 [code: missing-separator-glyphs]
  
  

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
* - uni0DBB (U+0DBB): X=247.5,Y=2 (should be at baseline 0?)
* - uni0DBB (U+0DBB): X=247.5,Y=2 (should be at cap-height 0?)
* - uni0DC1 (U+0DC1): X=623,Y=2 (should be at baseline 0?)
* - uni0DC1 (U+0DC1): X=623,Y=2 (should be at cap-height 0?)
* - khsinh: X=513,Y=-1 (should be at baseline 0?)
* - khsinh: X=513,Y=-1 (should be at cap-height 0?)
* - khIsinh: X=464,Y=-2 (should be at baseline 0?)
* - khIsinh: X=464,Y=-2 (should be at cap-height 0?)
* - khIisinh: X=420,Y=2 (should be at baseline 0?)
* - khIisinh: X=420,Y=2 (should be at cap-height 0?)
* - khIisinh: X=109,Y=2 (should be at baseline 0?)
* - khIisinh: X=109,Y=2 (should be at cap-height 0?)
* - rasignsinh: X=-121.5,Y=1.5 (should be at baseline 0?)
* - rasignsinh: X=-121.5,Y=1.5 (should be at cap-height 0?)
* - dRasinh: X=211.5,Y=-1.5 (should be at baseline 0?)
* - dRasinh: X=211.5,Y=-1.5 (should be at cap-height 0?)
* - lUsinh: X=287.5,Y=-1 (should be at baseline 0?)
* - lUsinh: X=287.5,Y=-1 (should be at cap-height 0?)
* - uni0DB3 (U+0DB3): X=513,Y=-2 (should be at baseline 0?)
* - uni0DB3 (U+0DB3): X=513,Y=-2 (should be at cap-height 0?)
* - uni0DB3 (U+0DB3): X=513,Y=-2 (should be at baseline 0?)
* - uni0DB3 (U+0DB3): X=513,Y=-2 (should be at cap-height 0?)
* - daa._csinh: X=369,Y=-2 (should be at baseline 0?)
* - daa._csinh: X=369,Y=-2 (should be at cap-height 0?)
* - rAaesinh: X=711,Y=-1 (should be at baseline 0?)
* - rAaesinh: X=711,Y=-1 (should be at cap-height 0?)
* - percent (U+0025): X=364.5,Y=2 (should be at baseline 0?)
* - percent (U+0025): X=364.5,Y=2 (should be at cap-height 0?)
* - rUusinh: X=247.5,Y=2 (should be at baseline 0?)
* - rUusinh: X=247.5,Y=2 (should be at cap-height 0?)
* - rUsinh: X=247.5,Y=2 (should be at baseline 0?)
* - rUsinh: X=247.5,Y=2 (should be at cap-height 0?) [code: found-misalignments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* uni0DD1 (U+0DD1): from (47.0, 283.0) to (47.0, 283.0) is colinear with segment from (47.0, 283.0) to (47.0, 283.0)
* two (U+0032): from (105.0, 334.0) to (105.0, 334.0) is colinear with segment from (105.0, 334.0) to (105.0, 334.0)
* four (U+0034): from (246.0, 380.0) to (246.0, 380.0) is colinear with segment from (246.0, 380.0) to (246.0, 380.0)
* five (U+0035): from (271.0, 486.0) to (271.0, 486.0) is colinear with segment from (271.0, 486.0) to (271.0, 486.0)
* five (U+0035): from (271.0, 486.0) to (271.0, 486.0) is colinear with segment from (271.0, 486.0) to (271.0, 486.0)
* five (U+0035): from (271.0, 486.0) to (271.0, 486.0) is colinear with segment from (271.0, 486.0) to (271.0, 486.0)
* five (U+0035): from (267.0, 521.0) to (267.0, 521.0) is colinear with segment from (267.0, 521.0) to (267.0, 521.0)
* five (U+0035): from (267.0, 521.0) to (267.0, 521.0) is colinear with segment from (267.0, 521.0) to (267.0, 521.0)
* rUusinh: from (552.0, 283.0) to (552.0, 283.0) is colinear with segment from (552.0, 283.0) to (552.0, 283.0)
* uni0D88 (U+0D88): from (515.0, 283.0) to (515.0, 283.0) is colinear with segment from (515.0, 283.0) to (515.0, 283.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph (outline_direction)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have a counter-clockwise outer contour:

* yasignsinh has a path with no bounds (probably a single point)
* bIisinh has a path with no bounds (probably a single point)
* mIisinh has a path with no bounds (probably a single point)
* mIisinh has a path with no bounds (probably a single point)
* mIisinh has a path with no bounds (probably a single point)
* mIisinh has a path with no bounds (probably a single point)
* mIisinh has a path with no bounds (probably a single point)
* mIisinh has a path with no bounds (probably a single point)
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
* rephasinh has a path with no bounds (probably a single point)
* uniE001 (U+E001) has a path with no bounds (probably a single point) [code: ccw-outer-contour]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* uni0D8B (U+0D8B): Quad(QuadBez { p0: (146.0, 253.0), p1: (148.0, 258.0), p2: (149.0, 261.0) })/Quad(QuadBez { p0: (149.0, 261.0), p1: (148.0, 259.0), p2: (148.5, 262.0) }) = 8.130102354156051 degrees
* vIisinh: Quad(QuadBez { p0: (105.0, 507.5), p1: (92.0, 498.0), p2: (84.0, 485.0) })/Quad(QuadBez { p0: (84.0, 485.0), p1: (90.0, 491.0), p2: (98.5, 492.0) }) = 13.392497753751043 degrees
* csinh: Quad(QuadBez { p0: (165.0, 426.0), p1: (162.0, 423.0), p2: (161.0, 422.0) })/Quad(QuadBez { p0: (161.0, 422.0), p1: (163.0, 424.0), p2: (165.0, 426.0) }) = 0.0000012074182697257333 degrees
* ddIisinh: Quad(QuadBez { p0: (423.0, 473.0), p1: (422.0, 473.0), p2: (421.0, 473.0) })/Quad(QuadBez { p0: (421.0, 473.0), p1: (451.0, 468.0), p2: (479.5, 457.5) }) = 9.462322208025613 degrees
* ddIisinh: Quad(QuadBez { p0: (360.0, 480.0), p1: (382.0, 479.0), p2: (404.0, 476.0) })/Quad(QuadBez { p0: (404.0, 476.0), p1: (384.0, 481.0), p2: (368.5, 494.5) }) = 6.271077449501227 degrees
* ddIsinh: Quad(QuadBez { p0: (205.0, 517.0), p1: (206.0, 509.0), p2: (210.0, 506.0) })/Quad(QuadBez { p0: (210.0, 506.0), p1: (208.0, 508.0), p2: (213.5, 506.0) }) = 8.130102354156005 degrees
* nnddIsinh: Quad(QuadBez { p0: (213.0, 158.0), p1: (214.0, 158.0), p2: (215.0, 158.0) })/Quad(QuadBez { p0: (215.0, 158.0), p1: (193.0, 163.0), p2: (178.5, 181.5) }) = 12.804266065286768 degrees
* nnddIisinh: Quad(QuadBez { p0: (202.0, 164.0), p1: (203.0, 164.0), p2: (204.0, 164.0) })/Quad(QuadBez { p0: (204.0, 164.0), p1: (182.0, 169.0), p2: (167.5, 187.5) }) = 12.804266065286768 degrees
* mIisinh: Quad(QuadBez { p0: (215.0, 597.0), p1: (185.0, 601.0), p2: (158.0, 598.0) })/Quad(QuadBez { p0: (158.0, 598.0), p1: (159.0, 598.0), p2: (152.5, 597.0) }) = 6.340191745909908 degrees
* seven (U+0037): Quad(QuadBez { p0: (320.0, 538.0), p1: (320.0, 539.0), p2: (321.0, 538.0) })/Quad(QuadBez { p0: (321.0, 538.0), p1: (320.0, 539.0), p2: (320.0, 538.0) }) = 0.0000012074182697257333 degrees
* eight (U+0038): Quad(QuadBez { p0: (133.0, 80.0), p1: (134.0, 79.0), p2: (135.0, 78.0) })/Quad(QuadBez { p0: (135.0, 78.0), p1: (134.0, 79.0), p2: (136.0, 77.0) }) = 0.0000012074182697257333 degrees
* eight (U+0038): Quad(QuadBez { p0: (315.0, 272.0), p1: (313.0, 274.0), p2: (314.0, 273.0) })/Quad(QuadBez { p0: (314.0, 273.0), p1: (308.0, 277.0), p2: (301.0, 281.0) }) = 11.309932474020261 degrees
* eight (U+0038): Quad(QuadBez { p0: (86.0, 565.0), p1: (86.0, 565.0), p2: (87.0, 566.0) })/Quad(QuadBez { p0: (87.0, 566.0), p1: (86.0, 565.0), p2: (86.0, 565.0) }) = 0.0000012074182697257333 degrees
* rephasinh: Quad(QuadBez { p0: (-330.0, 599.0), p1: (-330.0, 599.0), p2: (-329.0, 598.0) })/Quad(QuadBez { p0: (-329.0, 598.0), p1: (-330.0, 599.0), p2: (-330.0, 599.0) }) = 0.0000012074182697257333 degrees
* uni0D8C (U+0D8C): Quad(QuadBez { p0: (146.0, 253.0), p1: (148.0, 258.0), p2: (149.0, 261.0) })/Quad(QuadBez { p0: (149.0, 261.0), p1: (148.0, 259.0), p2: (148.5, 262.0) }) = 8.130102354156051 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* uni0D9D (U+0D9D): Quad(QuadBez { p0: (59.0, 280.0), p1: (59.0, 280.0), p2: (59.0, 280.0) }) has the same coordinates as a previous segment.
* uni0DD1 (U+0DD1): Line(Line { p0: (47.0, 283.0), p1: (47.0, 283.0) }) has the same coordinates as a previous segment.
* yasignsinh: Quad(QuadBez { p0: (301.0, 134.0), p1: (301.0, 134.0), p2: (301.0, 134.0) }) has the same coordinates as a previous segment.
* dUusinh: Quad(QuadBez { p0: (406.5, -282.5), p1: (403.0, -280.0), p2: (403.0, -281.0) }) has the same coordinates as a previous segment.
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
* lUusinh: Line(Line { p0: (321.0, -92.0), p1: (321.0, -92.0) }) has the same coordinates as a previous segment.
* lUusinh: Quad(QuadBez { p0: (322.0, -93.0), p1: (322.0, -93.0), p2: (322.0, -92.5) }) has the same coordinates as a previous segment.
* lUusinh: Quad(QuadBez { p0: (322.0, -92.0), p1: (323.0, -92.0), p2: (322.0, -92.5) }) has the same coordinates as a previous segment.
* lUusinh: Quad(QuadBez { p0: (530.0, -39.0), p1: (530.0, -39.0), p2: (530.0, -39.0) }) has the same coordinates as a previous segment.
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
* rephasinh: Quad(QuadBez { p0: (-329.0, 598.0), p1: (-330.0, 599.0), p2: (-330.0, 599.0) }) has the same coordinates as a previous segment.
* rephasinh: Quad(QuadBez { p0: (-366.0, 558.0), p1: (-366.0, 558.0), p2: (-365.0, 558.0) }) has the same coordinates as a previous segment.
* uniE001 (U+E001): Quad(QuadBez { p0: (329.0, 496.0), p1: (329.0, 496.0), p2: (329.0, 497.0) }) has the same coordinates as a previous segment.
* uniE001 (U+E001): Quad(QuadBez { p0: (292.0, 455.0), p1: (293.0, 455.0), p2: (293.0, 455.0) }) has the same coordinates as a previous segment.
* rUusinh: Line(Line { p0: (552.0, 283.0), p1: (552.0, 283.0) }) has the same coordinates as a previous segment.
* uni0D88 (U+0D88): Line(Line { p0: (515.0, 283.0), p1: (515.0, 283.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Description strings in the name table must not exceed 200 characters. (googlefonts/name/description_max_length)</summary>
    <div>








- ⚠️ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'MNIK' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>


</div>
</details>


<details><summary>[3] fonts/ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. (googlefonts/glyph_coverage)</summary>
    <div>








- 🔥 **FAIL** fonts/ttf/CCSellipiCANARY-Regular.ttf missing required codepoints:

* 0x0021: EXCLAMATION MARK
* 0x0022: QUOTATION MARK
* 0x0023: NUMBER SIGN
* 0x0024: DOLLAR SIGN
* 0x0026: AMPERSAND
* 0x0027: APOSTROPHE
* 0x002A: ASTERISK
* 0x003B: SEMICOLON
* 0x003C: LESS-THAN SIGN
* 0x003E: GREATER-THAN SIGN
* 0x0040: COMMERCIAL AT
* 0x0041: LATIN CAPITAL LETTER A
* 0x0042: LATIN CAPITAL LETTER B
* 0x0043: LATIN CAPITAL LETTER C
* 0x0044: LATIN CAPITAL LETTER D
* 0x0045: LATIN CAPITAL LETTER E
* 0x0046: LATIN CAPITAL LETTER F
* 0x0047: LATIN CAPITAL LETTER G
* 0x0048: LATIN CAPITAL LETTER H
* 0x0049: LATIN CAPITAL LETTER I
* 0x004A: LATIN CAPITAL LETTER J
* 0x004B: LATIN CAPITAL LETTER K
* 0x004C: LATIN CAPITAL LETTER L
* 0x004D: LATIN CAPITAL LETTER M
* 0x004E: LATIN CAPITAL LETTER N
* 0x004F: LATIN CAPITAL LETTER O
* 0x0050: LATIN CAPITAL LETTER P
* 0x0051: LATIN CAPITAL LETTER Q
* 0x0052: LATIN CAPITAL LETTER R
* 0x0053: LATIN CAPITAL LETTER S
* 0x0054: LATIN CAPITAL LETTER T
* 0x0055: LATIN CAPITAL LETTER U
* 0x0056: LATIN CAPITAL LETTER V
* 0x0057: LATIN CAPITAL LETTER W
* 0x0058: LATIN CAPITAL LETTER X
* 0x0059: LATIN CAPITAL LETTER Y
* 0x005A: LATIN CAPITAL LETTER Z
* 0x005B: LEFT SQUARE BRACKET
* 0x005C: REVERSE SOLIDUS
* 0x005D: RIGHT SQUARE BRACKET
* 0x005E: CIRCUMFLEX ACCENT
* 0x005F: LOW LINE
* 0x0060: GRAVE ACCENT
* 0x0061: LATIN SMALL LETTER A
* 0x0062: LATIN SMALL LETTER B
* 0x0063: LATIN SMALL LETTER C
* 0x0064: LATIN SMALL LETTER D
* 0x0065: LATIN SMALL LETTER E
* 0x0066: LATIN SMALL LETTER F
* 0x0067: LATIN SMALL LETTER G
* 0x0068: LATIN SMALL LETTER H
* 0x0069: LATIN SMALL LETTER I
* 0x006A: LATIN SMALL LETTER J
* 0x006B: LATIN SMALL LETTER K
* 0x006C: LATIN SMALL LETTER L
* 0x006D: LATIN SMALL LETTER M
* 0x006E: LATIN SMALL LETTER N
* 0x006F: LATIN SMALL LETTER O
* 0x0070: LATIN SMALL LETTER P
* 0x0071: LATIN SMALL LETTER Q
* 0x0072: LATIN SMALL LETTER R
* 0x0073: LATIN SMALL LETTER S
* 0x0074: LATIN SMALL LETTER T
* 0x0075: LATIN SMALL LETTER U
* 0x0076: LATIN SMALL LETTER V
* 0x0077: LATIN SMALL LETTER W
* 0x0078: LATIN SMALL LETTER X
* 0x0079: LATIN SMALL LETTER Y
* 0x007A: LATIN SMALL LETTER Z
* 0x007B: LEFT CURLY BRACKET
* 0x007C: VERTICAL LINE
* 0x007D: RIGHT CURLY BRACKET
* 0x007E: TILDE
* 0x00A1: INVERTED EXCLAMATION MARK
* 0x00A2: CENT SIGN
* 0x00A3: POUND SIGN
* 0x00A5: YEN SIGN
* 0x00A7: SECTION SIGN
* 0x00A8: DIAERESIS
* 0x00A9: COPYRIGHT SIGN
* 0x00AA: FEMININE ORDINAL INDICATOR
* 0x00AB: LEFT-POINTING DOUBLE ANGLE QUOTATION MARK
* 0x00AE: REGISTERED SIGN
* 0x00AF: MACRON
* 0x00B0: DEGREE SIGN
* 0x00B4: ACUTE ACCENT
* 0x00B6: PILCROW SIGN
* 0x00B7: MIDDLE DOT
* 0x00B8: CEDILLA
* 0x00BA: MASCULINE ORDINAL INDICATOR
* 0x00BB: RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK
* 0x00BF: INVERTED QUESTION MARK
* 0x00C0: LATIN CAPITAL LETTER A WITH GRAVE
* 0x00C1: LATIN CAPITAL LETTER A WITH ACUTE
* 0x00C2: LATIN CAPITAL LETTER A WITH CIRCUMFLEX
* 0x00C3: LATIN CAPITAL LETTER A WITH TILDE
* 0x00C4: LATIN CAPITAL LETTER A WITH DIAERESIS
* 0x00C5: LATIN CAPITAL LETTER A WITH RING ABOVE
* 0x00C6: LATIN CAPITAL LETTER AE
* 0x00C7: LATIN CAPITAL LETTER C WITH CEDILLA
* 0x00C8: LATIN CAPITAL LETTER E WITH GRAVE
* 0x00C9: LATIN CAPITAL LETTER E WITH ACUTE
* 0x00CA: LATIN CAPITAL LETTER E WITH CIRCUMFLEX
* 0x00CB: LATIN CAPITAL LETTER E WITH DIAERESIS
* 0x00CC: LATIN CAPITAL LETTER I WITH GRAVE
* 0x00CD: LATIN CAPITAL LETTER I WITH ACUTE
* 0x00CE: LATIN CAPITAL LETTER I WITH CIRCUMFLEX
* 0x00CF: LATIN CAPITAL LETTER I WITH DIAERESIS
* 0x00D0: LATIN CAPITAL LETTER ETH
* 0x00D1: LATIN CAPITAL LETTER N WITH TILDE
* 0x00D2: LATIN CAPITAL LETTER O WITH GRAVE
* 0x00D3: LATIN CAPITAL LETTER O WITH ACUTE
* 0x00D4: LATIN CAPITAL LETTER O WITH CIRCUMFLEX
* 0x00D5: LATIN CAPITAL LETTER O WITH TILDE
* 0x00D6: LATIN CAPITAL LETTER O WITH DIAERESIS
* 0x00D8: LATIN CAPITAL LETTER O WITH STROKE
* 0x00D9: LATIN CAPITAL LETTER U WITH GRAVE
* 0x00DA: LATIN CAPITAL LETTER U WITH ACUTE
* 0x00DB: LATIN CAPITAL LETTER U WITH CIRCUMFLEX
* 0x00DC: LATIN CAPITAL LETTER U WITH DIAERESIS
* 0x00DD: LATIN CAPITAL LETTER Y WITH ACUTE
* 0x00DE: LATIN CAPITAL LETTER THORN
* 0x00DF: LATIN SMALL LETTER SHARP S
* 0x00E0: LATIN SMALL LETTER A WITH GRAVE
* 0x00E1: LATIN SMALL LETTER A WITH ACUTE
* 0x00E2: LATIN SMALL LETTER A WITH CIRCUMFLEX
* 0x00E3: LATIN SMALL LETTER A WITH TILDE
* 0x00E4: LATIN SMALL LETTER A WITH DIAERESIS
* 0x00E5: LATIN SMALL LETTER A WITH RING ABOVE
* 0x00E6: LATIN SMALL LETTER AE
* 0x00E7: LATIN SMALL LETTER C WITH CEDILLA
* 0x00E8: LATIN SMALL LETTER E WITH GRAVE
* 0x00E9: LATIN SMALL LETTER E WITH ACUTE
* 0x00EA: LATIN SMALL LETTER E WITH CIRCUMFLEX
* 0x00EB: LATIN SMALL LETTER E WITH DIAERESIS
* 0x00EC: LATIN SMALL LETTER I WITH GRAVE
* 0x00ED: LATIN SMALL LETTER I WITH ACUTE
* 0x00EE: LATIN SMALL LETTER I WITH CIRCUMFLEX
* 0x00EF: LATIN SMALL LETTER I WITH DIAERESIS
* 0x00F0: LATIN SMALL LETTER ETH
* 0x00F1: LATIN SMALL LETTER N WITH TILDE
* 0x00F2: LATIN SMALL LETTER O WITH GRAVE
* 0x00F3: LATIN SMALL LETTER O WITH ACUTE
* 0x00F4: LATIN SMALL LETTER O WITH CIRCUMFLEX
* 0x00F5: LATIN SMALL LETTER O WITH TILDE
* 0x00F6: LATIN SMALL LETTER O WITH DIAERESIS
* 0x00F8: LATIN SMALL LETTER O WITH STROKE
* 0x00F9: LATIN SMALL LETTER U WITH GRAVE
* 0x00FA: LATIN SMALL LETTER U WITH ACUTE
* 0x00FB: LATIN SMALL LETTER U WITH CIRCUMFLEX
* 0x00FC: LATIN SMALL LETTER U WITH DIAERESIS
* 0x00FD: LATIN SMALL LETTER Y WITH ACUTE
* 0x00FE: LATIN SMALL LETTER THORN
* 0x00FF: LATIN SMALL LETTER Y WITH DIAERESIS
* 0x0100: LATIN CAPITAL LETTER A WITH MACRON
* 0x0101: LATIN SMALL LETTER A WITH MACRON
* 0x0102: LATIN CAPITAL LETTER A WITH BREVE
* 0x0103: LATIN SMALL LETTER A WITH BREVE
* 0x0104: LATIN CAPITAL LETTER A WITH OGONEK
* 0x0105: LATIN SMALL LETTER A WITH OGONEK
* 0x0106: LATIN CAPITAL LETTER C WITH ACUTE
* 0x0107: LATIN SMALL LETTER C WITH ACUTE
* 0x010A: LATIN CAPITAL LETTER C WITH DOT ABOVE
* 0x010B: LATIN SMALL LETTER C WITH DOT ABOVE
* 0x010C: LATIN CAPITAL LETTER C WITH CARON
* 0x010D: LATIN SMALL LETTER C WITH CARON
* 0x010E: LATIN CAPITAL LETTER D WITH CARON
* 0x010F: LATIN SMALL LETTER D WITH CARON
* 0x0110: LATIN CAPITAL LETTER D WITH STROKE
* 0x0111: LATIN SMALL LETTER D WITH STROKE
* 0x0112: LATIN CAPITAL LETTER E WITH MACRON
* 0x0113: LATIN SMALL LETTER E WITH MACRON
* 0x0116: LATIN CAPITAL LETTER E WITH DOT ABOVE
* 0x0117: LATIN SMALL LETTER E WITH DOT ABOVE
* 0x0118: LATIN CAPITAL LETTER E WITH OGONEK
* 0x0119: LATIN SMALL LETTER E WITH OGONEK
* 0x011A: LATIN CAPITAL LETTER E WITH CARON
* 0x011B: LATIN SMALL LETTER E WITH CARON
* 0x011E: LATIN CAPITAL LETTER G WITH BREVE
* 0x011F: LATIN SMALL LETTER G WITH BREVE
* 0x0120: LATIN CAPITAL LETTER G WITH DOT ABOVE
* 0x0121: LATIN SMALL LETTER G WITH DOT ABOVE
* 0x0122: LATIN CAPITAL LETTER G WITH CEDILLA
* 0x0123: LATIN SMALL LETTER G WITH CEDILLA
* 0x0126: LATIN CAPITAL LETTER H WITH STROKE
* 0x0127: LATIN SMALL LETTER H WITH STROKE
* 0x012A: LATIN CAPITAL LETTER I WITH MACRON
* 0x012B: LATIN SMALL LETTER I WITH MACRON
* 0x012E: LATIN CAPITAL LETTER I WITH OGONEK
* 0x012F: LATIN SMALL LETTER I WITH OGONEK
* 0x0130: LATIN CAPITAL LETTER I WITH DOT ABOVE
* 0x0131: LATIN SMALL LETTER DOTLESS I
* 0x0136: LATIN CAPITAL LETTER K WITH CEDILLA
* 0x0137: LATIN SMALL LETTER K WITH CEDILLA
* 0x0139: LATIN CAPITAL LETTER L WITH ACUTE
* 0x013A: LATIN SMALL LETTER L WITH ACUTE
* 0x013B: LATIN CAPITAL LETTER L WITH CEDILLA
* 0x013C: LATIN SMALL LETTER L WITH CEDILLA
* 0x013D: LATIN CAPITAL LETTER L WITH CARON
* 0x013E: LATIN SMALL LETTER L WITH CARON
* 0x0141: LATIN CAPITAL LETTER L WITH STROKE
* 0x0142: LATIN SMALL LETTER L WITH STROKE
* 0x0143: LATIN CAPITAL LETTER N WITH ACUTE
* 0x0144: LATIN SMALL LETTER N WITH ACUTE
* 0x0145: LATIN CAPITAL LETTER N WITH CEDILLA
* 0x0146: LATIN SMALL LETTER N WITH CEDILLA
* 0x0147: LATIN CAPITAL LETTER N WITH CARON
* 0x0148: LATIN SMALL LETTER N WITH CARON
* 0x0150: LATIN CAPITAL LETTER O WITH DOUBLE ACUTE
* 0x0151: LATIN SMALL LETTER O WITH DOUBLE ACUTE
* 0x0152: LATIN CAPITAL LIGATURE OE
* 0x0153: LATIN SMALL LIGATURE OE
* 0x0154: LATIN CAPITAL LETTER R WITH ACUTE
* 0x0155: LATIN SMALL LETTER R WITH ACUTE
* 0x0158: LATIN CAPITAL LETTER R WITH CARON
* 0x0159: LATIN SMALL LETTER R WITH CARON
* 0x015A: LATIN CAPITAL LETTER S WITH ACUTE
* 0x015B: LATIN SMALL LETTER S WITH ACUTE
* 0x015E: LATIN CAPITAL LETTER S WITH CEDILLA
* 0x015F: LATIN SMALL LETTER S WITH CEDILLA
* 0x0160: LATIN CAPITAL LETTER S WITH CARON
* 0x0161: LATIN SMALL LETTER S WITH CARON
* 0x0164: LATIN CAPITAL LETTER T WITH CARON
* 0x0165: LATIN SMALL LETTER T WITH CARON
* 0x016A: LATIN CAPITAL LETTER U WITH MACRON
* 0x016B: LATIN SMALL LETTER U WITH MACRON
* 0x016E: LATIN CAPITAL LETTER U WITH RING ABOVE
* 0x016F: LATIN SMALL LETTER U WITH RING ABOVE
* 0x0170: LATIN CAPITAL LETTER U WITH DOUBLE ACUTE
* 0x0171: LATIN SMALL LETTER U WITH DOUBLE ACUTE
* 0x0172: LATIN CAPITAL LETTER U WITH OGONEK
* 0x0173: LATIN SMALL LETTER U WITH OGONEK
* 0x0174: LATIN CAPITAL LETTER W WITH CIRCUMFLEX
* 0x0175: LATIN SMALL LETTER W WITH CIRCUMFLEX
* 0x0176: LATIN CAPITAL LETTER Y WITH CIRCUMFLEX
* 0x0177: LATIN SMALL LETTER Y WITH CIRCUMFLEX
* 0x0178: LATIN CAPITAL LETTER Y WITH DIAERESIS
* 0x0179: LATIN CAPITAL LETTER Z WITH ACUTE
* 0x017A: LATIN SMALL LETTER Z WITH ACUTE
* 0x017B: LATIN CAPITAL LETTER Z WITH DOT ABOVE
* 0x017C: LATIN SMALL LETTER Z WITH DOT ABOVE
* 0x017D: LATIN CAPITAL LETTER Z WITH CARON
* 0x017E: LATIN SMALL LETTER Z WITH CARON
* 0x0218: LATIN CAPITAL LETTER S WITH COMMA BELOW
* 0x0219: LATIN SMALL LETTER S WITH COMMA BELOW
* 0x021A: LATIN CAPITAL LETTER T WITH COMMA BELOW
* 0x021B: LATIN SMALL LETTER T WITH COMMA BELOW
* 0x0237: LATIN SMALL LETTER DOTLESS J
* 0x02C6: MODIFIER LETTER CIRCUMFLEX ACCENT
* 0x02C7: CARON
* 0x02D8: BREVE
* 0x02D9: DOT ABOVE
* 0x02DA: RING ABOVE
* 0x02DB: OGONEK
* 0x02DC: SMALL TILDE
* 0x02DD: DOUBLE ACUTE ACCENT
* 0x0300: COMBINING GRAVE ACCENT
* 0x0301: COMBINING ACUTE ACCENT
* 0x0302: COMBINING CIRCUMFLEX ACCENT
* 0x0303: COMBINING TILDE
* 0x0304: COMBINING MACRON
* 0x0306: COMBINING BREVE
* 0x0307: COMBINING DOT ABOVE
* 0x0308: COMBINING DIAERESIS
* 0x030A: COMBINING RING ABOVE
* 0x030B: COMBINING DOUBLE ACUTE ACCENT
* 0x030C: COMBINING CARON
* 0x0326: COMBINING COMMA BELOW
* 0x0327: COMBINING CEDILLA
* 0x0328: COMBINING OGONEK
* 0x1E80: LATIN CAPITAL LETTER W WITH GRAVE
* 0x1E81: LATIN SMALL LETTER W WITH GRAVE
* 0x1E82: LATIN CAPITAL LETTER W WITH ACUTE
* 0x1E83: LATIN SMALL LETTER W WITH ACUTE
* 0x1E84: LATIN CAPITAL LETTER W WITH DIAERESIS
* 0x1E85: LATIN SMALL LETTER W WITH DIAERESIS
* 0x1E9E: LATIN CAPITAL LETTER SHARP S
* 0x1EF2: LATIN CAPITAL LETTER Y WITH GRAVE
* 0x1EF3: LATIN SMALL LETTER Y WITH GRAVE
* 0x2013: EN DASH
* 0x2014: EM DASH
* 0x201A: SINGLE LOW-9 QUOTATION MARK
* 0x201C: LEFT DOUBLE QUOTATION MARK
* 0x201D: RIGHT DOUBLE QUOTATION MARK
* 0x201E: DOUBLE LOW-9 QUOTATION MARK
* 0x2022: BULLET
* 0x2026: HORIZONTAL ELLIPSIS
* 0x2039: SINGLE LEFT-POINTING ANGLE QUOTATION MARK
* 0x203A: SINGLE RIGHT-POINTING ANGLE QUOTATION MARK
* 0x20AC: EURO SIGN
* 0x2122: TRADE MARK SIGN
* 0x2212: MINUS SIGN [code: missing-codepoints]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure Fonts have 'ital' STAT axis. (opentype/STAT/ital_axis)</summary>
    <div>








- ⚠️ **WARN** Static font is missing the 'STAT' table. [code: no-stat-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. (googlefonts/metadata/unreachable_subsetting)</summary>
    <div>








- ⚠️ **WARN** fonts/ttf/CCSellipiCANARY-Regular.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+0025 PERCENT SIGN: try adding one of: gunjala-gondi, khmer, latin, adlam, math, masaram-gondi
* U+0028 LEFT PARENTHESIS: try adding one of: mongolian, latin, cham, masaram-gondi, adlam, math, khmer, syriac, wancho, gunjala-gondi, thaana
* U+0029 RIGHT PARENTHESIS: try adding one of: cham, masaram-gondi, math, mongolian, syriac, wancho, adlam, thaana, gunjala-gondi, khmer, latin
* U+002B PLUS SIGN: try adding one of: latin, masaram-gondi, khmer, math, syriac, adlam, gunjala-gondi
* U+002C COMMA: try adding one of: nushu, coptic, masaram-gondi, gunjala-gondi, latin, khmer, math, adlam, cham, thaana, wancho
* U+002D HYPHEN-MINUS: try adding one of: armenian, hebrew, lisu, wancho, cham, math, coptic, kharoshthi, mongolian, sundanese, latin, adlam, khmer, masaram-gondi, kaithi, nushu, sora-sompeng, gunjala-gondi, kayah-li, syriac
* U+002E FULL STOP: try adding one of: wancho, gunjala-gondi, khmer, cham, nushu, masaram-gondi, coptic, adlam, avestan, syriac, thaana, math, latin
* U+002F SOLIDUS: try adding one of: gunjala-gondi, math, syriac, wancho, khmer, latin, masaram-gondi, cham, adlam
* U+0030 DIGIT ZERO: try adding one of: math, symbols, khmer, nushu, latin
* U+0031 DIGIT ONE: try adding one of: math, latin, nushu, symbols, khmer
* U+0032 DIGIT TWO: try adding one of: latin, nushu, symbols, khmer, math
* U+0033 DIGIT THREE: try adding one of: khmer, math, symbols, latin, nushu
* U+0034 DIGIT FOUR: try adding one of: math, khmer, latin, nushu, symbols
* U+0035 DIGIT FIVE: try adding one of: math, khmer, nushu, symbols, latin
* U+0036 DIGIT SIX: try adding one of: math, symbols, nushu, khmer, latin
* U+0037 DIGIT SEVEN: try adding one of: latin, math, khmer, nushu, symbols
* U+0038 DIGIT EIGHT: try adding one of: math, nushu, symbols, khmer, latin
* U+0039 DIGIT NINE: try adding one of: math, khmer, latin, nushu, symbols
* U+003A COLON: try adding one of: coptic, adlam, cham, gunjala-gondi, meroitic, masaram-gondi, khmer, math, latin, syriac, thaana
* U+003D EQUALS SIGN: try adding one of: masaram-gondi, syriac, khmer, adlam, latin, math, gunjala-gondi
* U+003F QUESTION MARK: try adding one of: adlam, balinese, cham, mongolian, math, latin, masaram-gondi, gunjala-gondi, khmer
* U+00D7 MULTIPLICATION SIGN: try adding one of: math, gunjala-gondi, latin, masaram-gondi
* U+00F7 DIVISION SIGN: try adding one of: masaram-gondi, gunjala-gondi, math, latin
* U+2018 LEFT SINGLE QUOTATION MARK: try adding one of: latin, masaram-gondi, thaana, adlam, gunjala-gondi
* U+2019 RIGHT SINGLE QUOTATION MARK: try adding one of: adlam, gunjala-gondi, latin, thaana, masaram-gondi

Or you can add the above codepoints to one of the subsets supported by the font: sinhala [code: unreachable-subsetting]
  
  

</div>
</details>


</div>
</details>






### Summary

| 🔥 FAIL | ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|---|
| 4 | 19 | 20 | 93 | 86 | 
| 2% | 9% | 9% | 42% | 39% | 



