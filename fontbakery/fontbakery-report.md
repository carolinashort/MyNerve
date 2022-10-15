## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[9] MyNerve-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 469, but got 466 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret positioning values for these ligature glyphs:
	- A_p
	- b_e
	- c_c
	- c_h
	- c_t
	- e_i
	- e_x
	- f_o
	- h_o
	- l_i
	- o_v
	- r_o
	- s_h
	- s_t
	- t_h
	- t_t
	- t_u

   [code: incomplete-caret-pos-data]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- A + p

	- b + e

	- c + c

	- c + h

	- h + t

	- e + i

	- i + x

	- f + i

	- i + l

	- l + o

	- h + o

	- l + i

	- o + v

	- r + o

	- s + h

	- t + h

	- h + i

	- i + t 

	- And t + u [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- A.alt4

	- LF

	- S.alt5

	- U.alt3

	- X.alt3

	- a.alt3

	- asterisk.alt

	- dollar.alt1

	- e.alt4

	- g.alt3

	- guion

	- i.alt3

	- j.alt1.001

	- lowquote

	- m.alt3

	- minussign

	- n.alt3

	- n.alt4

	- o.alt3

	- o.alt4

	- o.alt5

	- oe.001

	- quotedblleft.001

	- quotedblright.001

	- s.alt3

	- s.alt4

	- uni02BB.001

	- w.alt4 

	- And y.alt3
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 1	Expected: 2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: a	Contours detected: 1	Expected: 2

	- Glyph name: b	Contours detected: 1	Expected: 2

	- Glyph name: q	Contours detected: 1	Expected: 2

	- Glyph name: ordfeminine	Contours detected: 1	Expected: 2 or 3

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: adieresis	Contours detected: 3	Expected: 4

	- Glyph name: aring	Contours detected: 3	Expected: 4

	- Glyph name: ae	Contours detected: 2	Expected: 3

	- Glyph name: eth	Contours detected: 1	Expected: 2

	- Glyph name: thorn	Contours detected: 1	Expected: 2

	- Glyph name: abreve	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Ebreve	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 1	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0181	Contours detected: 2	Expected: 3

	- Glyph name: Dtail	Contours detected: 3	Expected: 2

	- Glyph name: uni018A	Contours detected: 1	Expected: 2

	- Glyph name: uni018E	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uni01A4	Contours detected: 1	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01CE	Contours detected: 2	Expected: 3

	- Glyph name: uni01DF	Contours detected: 4	Expected: 5

	- Glyph name: uni01E3	Contours detected: 3	Expected: 4

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01E9	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: aeacute	Contours detected: 3	Expected: 4

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 3	Expected: 2

	- Glyph name: Epsilontonos	Contours detected: 3	Expected: 2

	- Glyph name: Beta	Contours detected: 2	Expected: 3

	- Glyph name: Epsilon	Contours detected: 2	Expected: 1

	- Glyph name: beta	Contours detected: 1	Expected: 2

	- Glyph name: delta	Contours detected: 1	Expected: 2

	- Glyph name: xi	Contours detected: 2	Expected: 1

	- Glyph name: sigma	Contours detected: 3	Expected: 2

	- Glyph name: uni03D7	Contours detected: 3	Expected: 1

	- Glyph name: uni1E5C	Contours detected: 3	Expected: 4

	- Glyph name: Rmacronbelow	Contours detected: 2	Expected: 3

	- Glyph name: uni1EA3	Contours detected: 2	Expected: 3

	- Glyph name: uni1EAF	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EBA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EBC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EBE	Contours detected: 4	Expected: 3

	- Glyph name: uni1EC0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EC2	Contours detected: 4	Expected: 3

	- Glyph name: uni1EC4	Contours detected: 4	Expected: 3

	- Glyph name: uni1EC6	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: oneeighth	Contours detected: 4	Expected: 5

	- Glyph name: threeeighths	Contours detected: 4	Expected: 5

	- Glyph name: fiveeighths	Contours detected: 4	Expected: 5

	- Glyph name: seveneighths	Contours detected: 4	Expected: 5

	- Glyph name: partialdiff	Contours detected: 1	Expected: 2

	- Glyph name: uni25A1	Contours detected: 1	Expected: 2

	- Glyph name: uni25CC	Contours detected: 17	Expected: 16 or 12

	- Glyph name: Beta	Contours detected: 2	Expected: 3

	- Glyph name: Ebreve	Contours detected: 3	Expected: 2

	- Glyph name: Epsilon	Contours detected: 2	Expected: 1

	- Glyph name: Epsilontonos	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 1	Expected: 2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: a	Contours detected: 1	Expected: 2

	- Glyph name: abreve	Contours detected: 2	Expected: 3

	- Glyph name: adieresis	Contours detected: 3	Expected: 4

	- Glyph name: ae	Contours detected: 2	Expected: 3

	- Glyph name: aeacute	Contours detected: 3	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: aring	Contours detected: 3	Expected: 4

	- Glyph name: at	Contours detected: 1	Expected: 2

	- Glyph name: b	Contours detected: 1	Expected: 2

	- Glyph name: beta	Contours detected: 1	Expected: 2

	- Glyph name: delta	Contours detected: 1	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: eth	Contours detected: 1	Expected: 2

	- Glyph name: fiveeighths	Contours detected: 4	Expected: 5

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: oneeighth	Contours detected: 4	Expected: 5

	- Glyph name: ordfeminine	Contours detected: 1	Expected: 2 or 3

	- Glyph name: partialdiff	Contours detected: 1	Expected: 2

	- Glyph name: q	Contours detected: 1	Expected: 2

	- Glyph name: seveneighths	Contours detected: 4	Expected: 5

	- Glyph name: sigma	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: thorn	Contours detected: 1	Expected: 2

	- Glyph name: threeeighths	Contours detected: 4	Expected: 5

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0181	Contours detected: 2	Expected: 3

	- Glyph name: uni018A	Contours detected: 1	Expected: 2

	- Glyph name: uni018E	Contours detected: 2	Expected: 1

	- Glyph name: uni01A4	Contours detected: 1	Expected: 2

	- Glyph name: uni01CE	Contours detected: 2	Expected: 3

	- Glyph name: uni01DF	Contours detected: 4	Expected: 5

	- Glyph name: uni01E3	Contours detected: 3	Expected: 4

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01E9	Contours detected: 3	Expected: 2

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 3	Expected: 2

	- Glyph name: uni03D7	Contours detected: 3	Expected: 1

	- Glyph name: uni1E5C	Contours detected: 3	Expected: 4

	- Glyph name: uni1EA3	Contours detected: 2	Expected: 3

	- Glyph name: uni1EAF	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EBA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EBC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EBE	Contours detected: 4	Expected: 3

	- Glyph name: uni1EC0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EC2	Contours detected: 4	Expected: 3

	- Glyph name: uni1EC4	Contours detected: 4	Expected: 3

	- Glyph name: uni1EC6	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni25A1	Contours detected: 1	Expected: 2

	- Glyph name: uni25CC	Contours detected: 17	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1 

	- And Glyph name: xi	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Racute (U+0154): L<<607.0,38.0>--<422.0,118.0>> -> L<<422.0,118.0>--<178.0,228.0>>

	* Rcaron (U+0158): L<<607.0,20.0>--<422.0,100.0>> -> L<<422.0,100.0>--<178.0,210.0>>

	* Upsilon (U+03A5): L<<352.0,401.0>--<349.0,203.0>> -> L<<349.0,203.0>--<354.0,46.0>>

	* Upsilondieresis (U+03AB): L<<352.0,401.0>--<349.0,203.0>> -> L<<349.0,203.0>--<354.0,46.0>>

	* Upsilontonos (U+038E): L<<543.0,401.0>--<540.0,203.0>> -> L<<540.0,203.0>--<545.0,46.0>>

	* arrowdown (U+2193): L<<256.0,684.0>--<256.0,590.0>> -> L<<256.0,590.0>--<258.0,543.0>>

	* arrowupdn (U+2195): L<<347.0,132.0>--<409.0,226.0>> -> L<<409.0,226.0>--<423.0,249.0>>

	* cent (U+00A2): L<<260.0,440.0>--<260.0,387.0>> -> L<<260.0,387.0>--<264.0,183.0>>

	* multiply (U+00D7): L<<252.0,309.0>--<132.0,451.0>> -> L<<132.0,451.0>--<79.0,512.0>>

	* notequal (U+2260): L<<732.0,679.0>--<653.0,566.0>> -> L<<653.0,566.0>--<557.0,426.0>>

	* oneeighth (U+215B): L<<149.0,628.0>--<115.0,586.0>> -> L<<115.0,586.0>--<83.0,538.0>>

	* onehalf (U+00BD): L<<192.0,628.0>--<158.0,586.0>> -> L<<158.0,586.0>--<126.0,538.0>>

	* pi (U+03C0): L<<597.0,500.0>--<600.0,452.0>> -> L<<600.0,452.0>--<605.0,412.0>>

	* trademark (U+2122): L<<141.0,681.0>--<148.0,721.0>> -> L<<148.0,721.0>--<155.0,764.0>>

	* trademark (U+2122): L<<392.0,717.0>--<376.0,682.0>> -> L<<376.0,682.0>--<361.0,639.0>>

	* trademark (U+2122): L<<523.0,724.0>--<549.0,779.0>> -> L<<549.0,779.0>--<574.0,836.0>>

	* trademark (U+2122): L<<623.0,518.0>--<610.0,518.0>> -> L<<610.0,518.0>--<590.0,519.0>>

	* uni0156 (U+0156): L<<607.0,38.0>--<422.0,118.0>> -> L<<422.0,118.0>--<178.0,228.0>>

	* uni0199 (U+0199): L<<123.0,592.0>--<123.0,501.0>> -> L<<123.0,501.0>--<123.0,497.0>>

	* uni0199 (U+0199): L<<50.0,351.0>--<51.0,533.0>> -> L<<51.0,533.0>--<51.0,570.0>>

	* uni024B (U+024B): L<<288.0,163.0>--<296.0,284.0>> -> L<<296.0,284.0>--<296.0,288.0>>

	* uni028C (U+028C): L<<342.0,31.0>--<314.0,112.0>> -> L<<314.0,112.0>--<301.0,150.0>>

	* uni2197 (U+2197): L<<114.0,192.0>--<274.0,420.0>> -> L<<274.0,420.0>--<297.0,451.0>>

	* uni2197 (U+2197): L<<60.0,101.0>--<114.0,192.0>> -> L<<114.0,192.0>--<274.0,420.0>>

	* uni2198 (U+2198): L<<618.0,-5.0>--<484.0,16.0>> -> L<<484.0,16.0>--<408.0,28.0>>

	* uni2199 (U+2199): L<<547.0,438.0>--<304.0,184.0>> -> L<<304.0,184.0>--<181.0,72.0>>

	* uni25A1 (U+25A1): L<<580.0,477.0>--<580.0,419.0>> -> L<<580.0,419.0>--<582.0,353.0>>

	* uni2758 (U+2758): L<<77.0,163.0>--<77.0,273.0>> -> L<<77.0,273.0>--<74.0,309.0>>

	* uni2758 (U+2758): L<<77.0,273.0>--<74.0,309.0>> -> L<<74.0,309.0>--<61.0,454.0>>

	* xi (U+03BE): L<<185.0,7.0>--<327.0,-52.0>> -> L<<327.0,-52.0>--<336.0,-55.0>> 

	* And yen (U+00A5): L<<334.0,244.0>--<334.0,227.0>> -> L<<334.0,227.0>--<339.0,78.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Acircumflex (U+00C2): B<<362.0,757.0>-<342.0,795.0>-<316.0,763.0>>/B<<316.0,763.0>-<318.0,765.0>-<305.5,754.0>> = 5.906141113770497

	* Adieresis (U+00C4): B<<452.0,687.0>-<441.0,694.0>-<419.0,712.0>>/B<<419.0,712.0>-<421.0,711.0>-<415.0,715.5>> = 12.724355685422363

	* Ccircumflex (U+0108): B<<389.0,797.0>-<369.0,835.0>-<343.0,803.0>>/B<<343.0,803.0>-<345.0,805.0>-<332.5,794.0>> = 5.906141113770497

	* Ecircumflex (U+00CA): B<<340.0,800.0>-<320.0,838.0>-<294.0,806.0>>/B<<294.0,806.0>-<296.0,808.0>-<283.5,797.0>> = 5.906141113770497

	* Edieresis (U+00CB): B<<410.5,739.0>-<399.0,745.0>-<375.0,761.0>>/B<<375.0,761.0>-<377.0,759.0>-<370.5,763.5>> = 11.309932474020195

	* Gcircumflex (U+011C): B<<431.0,764.0>-<411.0,802.0>-<385.0,770.0>>/B<<385.0,770.0>-<387.0,772.0>-<374.5,761.0>> = 5.906141113770497

	* Hcircumflex (U+0124): B<<393.0,800.0>-<373.0,838.0>-<347.0,806.0>>/B<<347.0,806.0>-<349.0,808.0>-<336.5,797.0>> = 5.906141113770497

	* Icircumflex (U+00CE): B<<223.0,795.0>-<206.0,826.0>-<185.0,800.0>>/B<<185.0,800.0>-<186.0,802.0>-<176.5,793.0>> = 12.362492415714259

	* Icircumflex (U+00CE): B<<97.0,717.5>-<87.0,708.0>-<88.0,708.0>>/B<<88.0,708.0>-<80.0,706.0>-<70.0,709.0>> = 14.036243467926484

	* Iotadieresis (U+03AA): B<<315.0,707.0>-<304.0,714.0>-<282.0,732.0>>/B<<282.0,732.0>-<284.0,731.0>-<278.0,735.5>> = 12.724355685422363

	* Jcircumflex (U+0134): B<<337.0,761.0>-<317.0,799.0>-<291.0,767.0>>/B<<291.0,767.0>-<293.0,769.0>-<280.5,758.0>> = 5.906141113770497

	* M.alt2 (U+F041): B<<523.5,538.5>-<514.0,544.0>-<514.0,546.0>>/B<<514.0,546.0>-<504.0,501.0>-<489.5,452.5>> = 12.528807709151522

	* Ocircumflex (U+00D4): B<<360.0,777.0>-<343.0,811.0>-<320.0,782.0>>/B<<320.0,782.0>-<321.0,784.0>-<310.5,774.5>> = 11.853004167743949

	* Odieresis (U+00D6): B<<439.5,691.0>-<428.0,697.0>-<404.0,713.0>>/B<<404.0,713.0>-<406.0,711.0>-<399.5,715.5>> = 11.309932474020195

	* Ohungarumlaut (U+0150): B<<383.5,644.5>-<376.0,645.0>-<378.0,640.0>>/B<<378.0,640.0>-<369.0,661.0>-<374.0,680.0>> = 1.397181027296108

	* Ohungarumlaut (U+0150): B<<534.5,840.5>-<541.0,835.0>-<536.0,805.0>>/B<<536.0,805.0>-<537.0,814.0>-<523.0,788.0>> = 3.1221304621157

	* Scircumflex (U+015C): B<<332.0,749.0>-<312.0,787.0>-<286.0,755.0>>/B<<286.0,755.0>-<288.0,757.0>-<275.5,746.0>> = 5.906141113770497

	* Uhungarumlaut (U+0170): B<<330.5,559.5>-<323.0,560.0>-<325.0,555.0>>/B<<325.0,555.0>-<316.0,576.0>-<321.0,595.0>> = 1.397181027296108

	* Uhungarumlaut (U+0170): B<<481.5,755.5>-<488.0,750.0>-<483.0,720.0>>/B<<483.0,720.0>-<484.0,729.0>-<470.0,703.0>> = 3.1221304621157

	* Upsilondieresis (U+03AB): B<<405.0,720.0>-<394.0,727.0>-<372.0,745.0>>/B<<372.0,745.0>-<374.0,744.0>-<368.0,748.5>> = 12.724355685422363

	* Wcircumflex (U+0174): B<<487.0,643.0>-<467.0,681.0>-<441.0,649.0>>/B<<441.0,649.0>-<443.0,651.0>-<430.5,640.0>> = 5.906141113770497

	* Wdieresis (U+1E84): B<<581.0,627.0>-<570.0,634.0>-<548.0,652.0>>/B<<548.0,652.0>-<550.0,651.0>-<544.0,655.5>> = 12.724355685422363

	* Ycircumflex (U+0176): B<<346.0,734.0>-<330.0,765.0>-<309.0,739.0>>/B<<309.0,739.0>-<310.0,740.0>-<300.5,731.5>> = 6.0724564072076905

	* Ydieresis (U+0178): B<<294.0,787.0>-<290.0,774.0>-<292.0,776.0>>/B<<292.0,776.0>-<271.0,760.0>-<260.0,753.5>> = 7.69605172201651

	* adieresis (U+00E4): B<<344.5,518.5>-<332.0,526.0>-<307.0,546.0>>/B<<307.0,546.0>-<309.0,545.0>-<302.5,550.0>> = 12.094757077012058

	* b.alt1 (U+F024): B<<123.5,52.0>-<109.0,61.0>-<104.0,81.0>>/B<<104.0,81.0>-<104.0,80.0>-<101.5,106.0>> = 14.036243467926484

	* b.alt1 (U+F024): B<<56.5,528.5>-<54.0,554.0>-<54.0,553.0>>/B<<54.0,553.0>-<51.0,608.0>-<50.5,664.0>> = 3.1221304621157

	* ccircumflex (U+0109): B<<263.0,618.0>-<243.0,656.0>-<217.0,624.0>>/B<<217.0,624.0>-<219.0,626.0>-<206.5,615.0>> = 5.906141113770497

	* circumflex (U+02C6): B<<263.0,702.0>-<243.0,740.0>-<217.0,708.0>>/B<<217.0,708.0>-<219.0,710.0>-<206.5,699.0>> = 5.906141113770497

	* dieresis (U+00A8): B<<139.0,631.0>-<134.0,618.0>-<136.0,620.0>>/B<<136.0,620.0>-<114.0,606.0>-<102.5,600.5>> = 12.528807709151522

	* dieresistonos (U+0385): B<<160.0,652.0>-<154.0,635.0>-<157.0,638.0>>/B<<157.0,638.0>-<129.0,618.0>-<115.0,610.5>> = 9.462322208025535

	* edieresis (U+00EB): B<<486.5,452.5>-<474.0,460.0>-<449.0,480.0>>/B<<449.0,480.0>-<451.0,479.0>-<444.5,484.0>> = 12.094757077012058

	* gcircumflex (U+011D): B<<253.0,638.0>-<233.0,676.0>-<207.0,644.0>>/B<<207.0,644.0>-<209.0,646.0>-<196.5,635.0>> = 5.906141113770497

	* hcircumflex (U+0125): B<<302.0,743.0>-<282.0,781.0>-<256.0,749.0>>/B<<256.0,749.0>-<258.0,751.0>-<245.5,740.0>> = 5.906141113770497

	* hungarumlaut (U+02DD): B<<203.5,541.5>-<196.0,542.0>-<198.0,537.0>>/B<<198.0,537.0>-<189.0,558.0>-<194.0,577.0>> = 1.397181027296108

	* hungarumlaut (U+02DD): B<<354.5,737.5>-<361.0,732.0>-<356.0,702.0>>/B<<356.0,702.0>-<357.0,711.0>-<343.0,685.0>> = 3.1221304621157

	* icircumflex (U+00EE): B<<157.0,624.0>-<141.0,656.0>-<119.0,629.0>>/B<<119.0,629.0>-<121.0,631.0>-<111.0,622.0>> = 5.826342029555751

	* iotadieresis (U+03CA): B<<315.0,578.0>-<304.0,585.0>-<282.0,603.0>>/B<<282.0,603.0>-<284.0,602.0>-<278.0,606.5>> = 12.724355685422363

	* iotadieresistonos (U+0390): B<<160.0,730.0>-<154.0,713.0>-<157.0,716.0>>/B<<157.0,716.0>-<129.0,696.0>-<115.0,688.5>> = 9.462322208025535

	* jcircumflex (U+0135): B<<220.0,644.0>-<200.0,682.0>-<174.0,650.0>>/B<<174.0,650.0>-<176.0,652.0>-<163.5,641.0>> = 5.906141113770497

	* m (U+006D): B<<525.0,335.0>-<530.0,348.0>-<526.0,341.0>>/B<<526.0,341.0>-<538.0,364.0>-<555.5,379.0>> = 2.1920697202241306

	* notequal (U+2260): L<<174.0,403.0>--<157.0,419.0>>/B<<157.0,419.0>-<166.0,413.0>-<184.0,423.0>> = 9.574227885091826

	* ocircumflex (U+00F4): B<<248.0,507.0>-<232.0,539.0>-<210.0,512.0>>/B<<210.0,512.0>-<211.0,514.0>-<201.5,505.0>> = 12.608606793366192

	* odieresis (U+00F6): B<<318.0,459.0>-<307.0,466.0>-<285.0,484.0>>/B<<285.0,484.0>-<287.0,483.0>-<281.0,487.5>> = 12.724355685422363

	* ohungarumlaut (U+0151): B<<224.5,428.0>-<218.0,428.0>-<219.0,424.0>>/B<<219.0,424.0>-<211.0,443.0>-<215.5,459.5>> = 8.797410709991091

	* ohungarumlaut (U+0151): B<<357.0,601.0>-<363.0,596.0>-<358.0,570.0>>/B<<358.0,570.0>-<359.0,578.0>-<347.0,555.0>> = 3.760510705756924

	* p (U+0070): B<<67.0,447.0>-<66.0,458.0>-<66.0,455.0>>/B<<66.0,455.0>-<64.0,488.0>-<88.0,491.0>> = 3.468229258917096

	* p (U+0070): B<<80.5,36.0>-<80.0,55.0>-<80.0,53.0>>/B<<80.0,53.0>-<78.0,95.0>-<78.5,137.5>> = 2.726310993906212

	* scircumflex (U+015D): B<<293.0,646.0>-<273.0,684.0>-<247.0,652.0>>/B<<247.0,652.0>-<249.0,654.0>-<236.5,643.0>> = 5.906141113770497

	* t.alt1 (U+F011): B<<144.5,511.0>-<141.0,496.0>-<141.0,497.0>>/B<<141.0,497.0>-<137.0,469.0>-<135.0,438.5>> = 8.13010235415596

	* tcaron (U+0165): B<<129.5,511.0>-<126.0,496.0>-<126.0,497.0>>/B<<126.0,497.0>-<122.0,469.0>-<120.0,438.5>> = 8.13010235415596

	* tmacronbelow (U+1E6F): B<<267.5,490.0>-<264.0,475.0>-<264.0,476.0>>/B<<264.0,476.0>-<260.0,448.0>-<258.0,417.5>> = 8.13010235415596

	* ucircumflex (U+00FB): B<<280.0,548.0>-<260.0,586.0>-<234.0,554.0>>/B<<234.0,554.0>-<236.0,556.0>-<223.5,545.0>> = 5.906141113770497

	* udieresis (U+00FC): B<<355.0,486.0>-<344.0,493.0>-<322.0,511.0>>/B<<322.0,511.0>-<324.0,510.0>-<318.0,514.5>> = 12.724355685422363

	* uhungarumlaut (U+0171): B<<275.5,415.5>-<268.0,416.0>-<270.0,411.0>>/B<<270.0,411.0>-<261.0,432.0>-<266.0,451.0>> = 1.397181027296108

	* uhungarumlaut (U+0171): B<<426.5,611.5>-<433.0,606.0>-<428.0,576.0>>/B<<428.0,576.0>-<429.0,585.0>-<415.0,559.0>> = 3.1221304621157

	* uni0163 (U+0163): B<<129.5,511.0>-<126.0,496.0>-<126.0,497.0>>/B<<126.0,497.0>-<122.0,469.0>-<120.0,438.5>> = 8.13010235415596

	* uni01A5 (U+01A5): B<<80.5,36.0>-<80.0,55.0>-<80.0,53.0>>/B<<80.0,53.0>-<78.0,95.0>-<78.5,137.5>> = 2.726310993906212

	* uni01AD (U+01AD): B<<144.0,508.5>-<141.0,496.0>-<141.0,497.0>>/B<<141.0,497.0>-<137.0,469.0>-<135.0,438.5>> = 8.13010235415596

	* uni01D5 (U+01D5): B<<197.0,695.0>-<192.0,682.0>-<194.0,684.0>>/B<<194.0,684.0>-<172.0,670.0>-<160.5,664.5>> = 12.528807709151522

	* uni01D6 (U+01D6): B<<180.0,480.0>-<175.0,467.0>-<177.0,469.0>>/B<<177.0,469.0>-<155.0,455.0>-<143.5,449.5>> = 12.528807709151522

	* uni01D7 (U+01D7): B<<222.0,652.0>-<217.0,639.0>-<219.0,641.0>>/B<<219.0,641.0>-<197.0,627.0>-<185.5,621.5>> = 12.528807709151522

	* uni01D8 (U+01D8): B<<168.0,480.0>-<163.0,467.0>-<165.0,469.0>>/B<<165.0,469.0>-<143.0,455.0>-<131.5,449.5>> = 12.528807709151522

	* uni01D9 (U+01D9): B<<218.0,654.0>-<213.0,641.0>-<215.0,643.0>>/B<<215.0,643.0>-<193.0,629.0>-<181.5,623.5>> = 12.528807709151522

	* uni01DA (U+01DA): B<<161.0,451.0>-<156.0,438.0>-<158.0,440.0>>/B<<158.0,440.0>-<136.0,426.0>-<124.5,420.5>> = 12.528807709151522

	* uni01DB (U+01DB): B<<232.0,662.0>-<227.0,649.0>-<229.0,651.0>>/B<<229.0,651.0>-<207.0,637.0>-<195.5,631.5>> = 12.528807709151522

	* uni01DC (U+01DC): B<<191.0,437.0>-<186.0,424.0>-<188.0,426.0>>/B<<188.0,426.0>-<166.0,412.0>-<154.5,406.5>> = 12.528807709151522

	* uni01DE (U+01DE): B<<445.0,655.0>-<434.0,662.0>-<412.0,680.0>>/B<<412.0,680.0>-<414.0,679.0>-<408.0,683.5>> = 12.724355685422363

	* uni01DF (U+01DF): B<<355.0,497.0>-<344.0,504.0>-<322.0,522.0>>/B<<322.0,522.0>-<324.0,521.0>-<318.0,525.5>> = 12.724355685422363

	* uni021B (U+021B): B<<129.5,522.0>-<126.0,507.0>-<126.0,508.0>>/B<<126.0,508.0>-<122.0,480.0>-<120.0,449.5>> = 8.13010235415596

	* uni022A (U+022A): B<<463.5,654.0>-<452.0,660.0>-<428.0,675.0>>/B<<428.0,675.0>-<430.0,674.0>-<423.5,678.0>> = 5.440332031005414

	* uni022B (U+022B): B<<325.0,448.0>-<314.0,455.0>-<292.0,473.0>>/B<<292.0,473.0>-<294.0,472.0>-<288.0,476.5>> = 12.724355685422363

	* uni0288 (U+0288): B<<285.0,491.5>-<280.0,477.0>-<280.0,478.0>>/B<<280.0,478.0>-<273.0,450.0>-<268.5,420.5>> = 14.036243467926484

	* uni0289 (U+0289): B<<588.0,289.5>-<570.0,286.0>-<548.0,282.0>>/L<<548.0,282.0>--<548.0,282.0>> = 10.304846468766044

	* uni0302 (U+0302): B<<263.0,702.0>-<243.0,740.0>-<217.0,708.0>>/B<<217.0,708.0>-<219.0,710.0>-<206.5,699.0>> = 5.906141113770497

	* uni0308 (U+0308): B<<355.0,588.0>-<344.0,595.0>-<322.0,613.0>>/B<<322.0,613.0>-<324.0,612.0>-<318.0,616.5>> = 12.724355685422363

	* uni030B (U+030B): B<<223.5,533.5>-<216.0,534.0>-<218.0,529.0>>/B<<218.0,529.0>-<209.0,550.0>-<214.0,569.0>> = 1.397181027296108

	* uni030B (U+030B): B<<374.5,729.5>-<381.0,724.0>-<376.0,694.0>>/B<<376.0,694.0>-<377.0,703.0>-<363.0,677.0>> = 3.1221304621157

	* uni0324 (U+0324): B<<159.0,-108.0>-<154.0,-121.0>-<156.0,-119.0>>/B<<156.0,-119.0>-<134.0,-133.0>-<122.5,-138.5>> = 12.528807709151522

	* uni1E12 (U+1E12): B<<391.0,-85.0>-<371.0,-47.0>-<345.0,-79.0>>/B<<345.0,-79.0>-<347.0,-77.0>-<334.5,-88.0>> = 5.906141113770497

	* uni1E13 (U+1E13): B<<315.0,-106.0>-<299.0,-75.0>-<278.0,-101.0>>/B<<278.0,-101.0>-<279.0,-99.0>-<269.5,-108.0>> = 12.362492415714259

	* uni1E2E (U+1E2E): B<<308.0,662.5>-<296.0,669.0>-<273.0,685.0>>/B<<273.0,685.0>-<275.0,684.0>-<269.0,688.0>> = 8.259437979878793

	* uni1E3C (U+1E3C): B<<361.0,-85.0>-<342.0,-50.0>-<318.0,-79.0>>/B<<318.0,-79.0>-<319.0,-77.0>-<308.0,-87.5>> = 13.04563706294857

	* uni1E3D (U+1E3D): B<<233.0,-106.0>-<214.0,-71.0>-<190.0,-100.0>>/B<<190.0,-100.0>-<191.0,-98.0>-<180.0,-108.5>> = 13.04563706294857

	* uni1E3F (U+1E3F): B<<525.0,335.0>-<530.0,348.0>-<526.0,341.0>>/B<<526.0,341.0>-<538.0,364.0>-<555.5,379.0>> = 2.1920697202241306

	* uni1E41 (U+1E41): B<<525.0,335.0>-<530.0,348.0>-<526.0,341.0>>/B<<526.0,341.0>-<538.0,364.0>-<555.5,379.0>> = 2.1920697202241306

	* uni1E43 (U+1E43): B<<525.0,335.0>-<530.0,348.0>-<526.0,341.0>>/B<<526.0,341.0>-<538.0,364.0>-<555.5,379.0>> = 2.1920697202241306

	* uni1E4A (U+1E4A): B<<351.0,-85.0>-<332.0,-50.0>-<308.0,-79.0>>/B<<308.0,-79.0>-<309.0,-77.0>-<298.0,-87.5>> = 13.04563706294857

	* uni1E6D (U+1E6D): B<<129.5,511.0>-<126.0,496.0>-<126.0,497.0>>/B<<126.0,497.0>-<122.0,469.0>-<120.0,438.5>> = 8.13010235415596

	* uni1E70 (U+1E70): B<<390.0,-85.0>-<371.0,-50.0>-<347.0,-79.0>>/B<<347.0,-79.0>-<348.0,-77.0>-<337.0,-87.5>> = 13.04563706294857

	* uni1E71 (U+1E71): B<<267.5,591.0>-<264.0,576.0>-<264.0,577.0>>/B<<264.0,577.0>-<260.0,549.0>-<258.0,518.5>> = 8.13010235415596

	* uni1E71 (U+1E71): B<<346.0,-85.0>-<327.0,-50.0>-<303.0,-79.0>>/B<<303.0,-79.0>-<304.0,-77.0>-<293.0,-87.5>> = 13.04563706294857

	* uni1E97 (U+1E97): B<<355.0,588.0>-<344.0,595.0>-<322.0,613.0>>/B<<322.0,613.0>-<324.0,612.0>-<318.0,616.5>> = 12.724355685422363

	* uni1EA4 (U+1EA4): B<<353.0,664.0>-<337.0,693.0>-<317.0,668.0>>/B<<317.0,668.0>-<318.0,670.0>-<308.5,661.5>> = 12.094757077012058

	* uni1EA5 (U+1EA5): B<<214.0,575.0>-<198.0,604.0>-<178.0,579.0>>/B<<178.0,579.0>-<179.0,581.0>-<169.5,572.5>> = 12.094757077012058

	* uni1EA6 (U+1EA6): B<<319.0,690.0>-<303.0,722.0>-<281.0,695.0>>/B<<281.0,695.0>-<283.0,697.0>-<273.0,688.0>> = 5.826342029555751

	* uni1EA7 (U+1EA7): B<<245.0,567.0>-<229.0,599.0>-<207.0,572.0>>/B<<207.0,572.0>-<209.0,574.0>-<199.0,565.0>> = 5.826342029555751

	* uni1EA8 (U+1EA8): B<<344.0,652.0>-<328.0,681.0>-<308.0,656.0>>/B<<308.0,656.0>-<309.0,658.0>-<299.5,649.5>> = 12.094757077012058

	* uni1EA9 (U+1EA9): B<<215.0,572.0>-<199.0,601.0>-<179.0,576.0>>/B<<179.0,576.0>-<180.0,578.0>-<170.5,569.5>> = 12.094757077012058

	* uni1EAA (U+1EAA): B<<336.0,705.0>-<320.0,734.0>-<300.0,709.0>>/B<<300.0,709.0>-<301.0,711.0>-<291.5,702.5>> = 12.094757077012058

	* uni1EAB (U+1EAB): B<<247.0,571.0>-<231.0,600.0>-<211.0,575.0>>/B<<211.0,575.0>-<212.0,577.0>-<202.5,568.5>> = 12.094757077012058

	* uni1EAC (U+1EAC): B<<343.0,785.0>-<323.0,823.0>-<297.0,791.0>>/B<<297.0,791.0>-<299.0,793.0>-<286.5,782.0>> = 5.906141113770497

	* uni1EAD (U+1EAD): B<<218.0,555.0>-<202.0,586.0>-<181.0,560.0>>/B<<181.0,560.0>-<182.0,562.0>-<172.5,553.0>> = 12.362492415714259

	* uni1EBE (U+1EBE): B<<313.0,723.0>-<299.0,750.0>-<281.0,727.0>>/B<<281.0,727.0>-<282.0,729.0>-<273.5,721.0>> = 11.481991354748077

	* uni1EBF (U+1EBF): B<<271.0,563.0>-<255.0,592.0>-<235.0,567.0>>/B<<235.0,567.0>-<236.0,569.0>-<226.5,560.5>> = 12.094757077012058

	* uni1EC0 (U+1EC0): B<<330.0,751.0>-<314.0,783.0>-<292.0,756.0>>/B<<292.0,756.0>-<294.0,758.0>-<284.0,749.0>> = 5.826342029555751

	* uni1EC1 (U+1EC1): B<<139.0,489.5>-<128.0,479.0>-<129.0,479.0>>/B<<129.0,479.0>-<121.0,477.0>-<109.5,480.0>> = 14.036243467926484

	* uni1EC1 (U+1EC1): B<<278.0,576.0>-<260.0,610.0>-<237.0,581.0>>/B<<237.0,581.0>-<238.0,583.0>-<227.5,573.0>> = 11.853004167743949

	* uni1EC2 (U+1EC2): B<<308.0,719.0>-<294.0,746.0>-<276.0,723.0>>/B<<276.0,723.0>-<277.0,725.0>-<268.5,717.0>> = 11.481991354748077

	* uni1EC3 (U+1EC3): B<<279.0,570.0>-<261.0,605.0>-<237.0,576.0>>/B<<237.0,576.0>-<238.0,577.0>-<227.0,567.0>> = 5.389311759973354

	* uni1EC4 (U+1EC4): B<<328.0,731.0>-<312.0,760.0>-<292.0,735.0>>/B<<292.0,735.0>-<293.0,737.0>-<283.5,728.5>> = 12.094757077012058

	* uni1EC5 (U+1EC5): B<<273.0,576.0>-<256.0,608.0>-<235.0,581.0>>/B<<235.0,581.0>-<236.0,582.0>-<226.0,573.0>> = 7.1250163489018075

	* uni1EC6 (U+1EC6): B<<343.0,785.0>-<323.0,823.0>-<297.0,791.0>>/B<<297.0,791.0>-<299.0,793.0>-<286.5,782.0>> = 5.906141113770497

	* uni1EC7 (U+1EC7): B<<286.0,593.0>-<266.0,631.0>-<240.0,599.0>>/B<<240.0,599.0>-<242.0,601.0>-<229.5,590.0>> = 5.906141113770497

	* uni1ED0 (U+1ED0): B<<354.0,691.0>-<340.0,718.0>-<322.0,695.0>>/B<<322.0,695.0>-<323.0,697.0>-<314.5,689.0>> = 11.481991354748077

	* uni1ED1 (U+1ED1): B<<222.0,503.0>-<206.0,532.0>-<186.0,507.0>>/B<<186.0,507.0>-<187.0,509.0>-<177.5,500.5>> = 12.094757077012058

	* uni1ED2 (U+1ED2): B<<353.0,699.0>-<337.0,731.0>-<315.0,704.0>>/B<<315.0,704.0>-<317.0,706.0>-<307.0,697.0>> = 5.826342029555751

	* uni1ED3 (U+1ED3): B<<246.0,541.0>-<230.0,573.0>-<208.0,546.0>>/B<<208.0,546.0>-<210.0,548.0>-<200.0,539.0>> = 5.826342029555751

	* uni1ED4 (U+1ED4): B<<344.0,702.0>-<330.0,729.0>-<312.0,706.0>>/B<<312.0,706.0>-<313.0,708.0>-<304.5,700.0>> = 11.481991354748077

	* uni1ED5 (U+1ED5): B<<231.0,533.0>-<215.0,562.0>-<195.0,537.0>>/B<<195.0,537.0>-<196.0,539.0>-<186.5,530.5>> = 12.094757077012058

	* uni1ED6 (U+1ED6): B<<327.0,705.0>-<311.0,734.0>-<291.0,709.0>>/B<<291.0,709.0>-<292.0,711.0>-<282.5,702.5>> = 12.094757077012058

	* uni1ED7 (U+1ED7): B<<248.0,574.0>-<232.0,603.0>-<212.0,578.0>>/B<<212.0,578.0>-<213.0,580.0>-<203.5,571.5>> = 12.094757077012058

	* uni1ED8 (U+1ED8): B<<343.0,734.0>-<323.0,772.0>-<297.0,740.0>>/B<<297.0,740.0>-<299.0,742.0>-<286.5,731.0>> = 5.906141113770497

	* uni1ED9 (U+1ED9): B<<263.0,530.0>-<243.0,568.0>-<217.0,536.0>>/B<<217.0,536.0>-<219.0,538.0>-<206.5,527.0>> = 5.906141113770497

	* uni2198 (U+2198): B<<405.0,115.5>-<475.0,100.0>-<521.0,80.0>>/B<<521.0,80.0>-<485.0,106.0>-<475.0,114.0>> = 12.33908727832618

	* upsilondieresis (U+03CB): B<<355.0,588.0>-<344.0,595.0>-<322.0,613.0>>/B<<322.0,613.0>-<324.0,612.0>-<318.0,616.5>> = 12.724355685422363

	* upsilondieresistonos (U+03B0): B<<160.0,604.0>-<154.0,587.0>-<157.0,590.0>>/B<<157.0,590.0>-<129.0,570.0>-<115.0,562.5>> = 9.462322208025535

	* wcircumflex (U+0175): B<<360.0,544.0>-<344.0,576.0>-<322.0,549.0>>/B<<322.0,549.0>-<323.0,551.0>-<313.0,541.5>> = 12.608606793366192

	* wdieresis (U+1E85): B<<461.0,504.0>-<450.0,511.0>-<428.0,529.0>>/B<<428.0,529.0>-<430.0,528.0>-<424.0,532.5>> = 12.724355685422363

	* xi (U+03BE): B<<387.0,594.0>-<400.0,593.0>-<392.0,591.0>>/B<<392.0,591.0>-<395.0,591.0>-<399.0,588.5>> = 14.036243467926484

	* ycircumflex (U+0177): B<<256.0,645.0>-<240.0,676.0>-<218.0,649.0>>/B<<218.0,649.0>-<220.0,651.0>-<210.0,642.0>> = 5.826342029555751 

	* And ydieresis (U+00FF): B<<355.0,588.0>-<344.0,595.0>-<322.0,613.0>>/B<<322.0,613.0>-<324.0,612.0>-<318.0,616.5>> = 12.724355685422363 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* arrowleft (U+2190): L<<246.0,400.0>--<368.0,401.0>>

	* equal (U+003D): L<<125.0,255.0>--<476.0,257.0>>

	* fl.liga (U+FB02): L<<509.0,183.0>--<510.0,67.0>>

	* minus (U+2212): L<<110.0,301.0>--<461.0,303.0>> 

	* And uni0199 (U+0199): L<<50.0,351.0>--<51.0,533.0>> [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 8 | 111 | 7 | 100 | 0 |
| 0% | 0% | 4% | 49% | 3% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
