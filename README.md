# M463LA Submaster Module · Summing

Ward-Beck Systems M463LA, 1974|7. Wiki page: [M463LA on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M463LA.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 88 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 7 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 10 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 462 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 18 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 72 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [2 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1974 - M463LA - P003 - 1-1.jpg](MANUALS/1974%20-%20M463LA%20-%20P003%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | +18 dB +/ -0.5 dB (bridging gain) (With fader in15 dB &quot;in-hand&quot; position. |
| **Frequency response** | +/ -0.25 dB from 20 Hz kHz (Equalizer bypass position. |
| **Noise** | dB below dBm nominal output level (20Hz kHz) |
| **Harmonic distortion** | Less than 0.259 irom Hz kHz +28 dBm less Typically less than 057 across most bandwidth) |
| **Source impedances** |  |
| &nbsp;&nbsp;Summing | 30 000 ohms balanced Direct: 600 ohms or less, balanced |
| **Input impedances** |  |
| &nbsp;&nbsp;Summing | Less than Direct: 30,000 ohms ohms |
| **Output impedance** | Less than 100 ohms (at outputs 8-109A amplifiers only) 8-109F |
| **Load impedance** | 500 ohms, balanced (at insertion point and DIRECT output) |
| **Output level** | dBm nomina at insertion +8 dBm nominal DIRECT output _ +30 dBm maximum (at outputs 8-109F 8-109A amplifiers only). |
| **Phasing** | Input and output terminals designated by numbers are phase |
| **Power requirements** | volts dc, 100 mA nominal 300 MA maximum |
| **Ambient temperature** | degrees Celsius |
| **Dimensions** | wide 14.5&quot; high 6.5&quot; deep (41 mm 360 mm 165 mm) |
| **Weight** | 40 ozs (1150 gms) |

## Circuit description

From [1974 - M463LA - Submaster Module (2).pdf](MANUALS/1974%20-%20M463LA%20-%20Submaster%20Module%20(2).pdf) pages 4-9 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The M46 3L i s a combinalion SUBMAST ER/ EOUALIZ ER module, designed 10

~~~~~I c~:~~:~ Ac; ~~~xe~e f~::~ir:~ Ih~re~~~~sl:roc:::~~ne~e m~7~:~ s' g na l, equalize s il and routes it 10 tn e app r op r ia te points withIn the console system.

Input and Summing Amplifier

The signal orign ating from thee Xl erna l mixing network Is applied to thee d ge conne&lt;:tor PI, pins Ian d A and sub seq ue n l l y connects t o the summing current nodes oft h e 4_141 summing amplifier. to facili tale module te sling, a direct input isp r ovid e don P l, pins 17 and U.

EO UALIZ ER Secli on

The o u tpU I of Ih e 4_141 summing amplifier i s rou led to one oft h e normally closed contacts of I h e EOUALIZE R INSERTs witCh SWI3 to a i low bypassing o f I he equalizer. Additionally, Ihe 4-14i output i s fed to Zl, the first of four cascaded summing amplifiers Z I through

ZI through Z4 serve as mixing and Iso la lion amplifiers. They are used 10 mix the primary input signal with a corrections ig na l derived from the outputs o f Ihe 4_ 126 filter networks, re su lling 1n raisin g or lowering the level o f selected portions of Ih e audios p e c tr u m. Addition ally, they t s eter e Ih e fllt er networks from each other and prev e nl interaction between Ihem, resulting inaccurate and repeat ~ able e q ull liz ing performance.

The CUr /BOOST controls R21, R2 2 and R2 3 feed a n in-p has e o r o UIof~ph8 se proportionals i g n a l 10 the buffer amplifiers Z5, Z6 and Z8 r e s peclively. The level o f I h e signal fed 10 I he buffers is dependent on Ih e CUT/aOOST control selling....ith maximum level occurring ale i there n d of the polent iom et e r, 8 n d a null setting a t the poten tj o ~ meter mid ~ po sill on. Full clOCkwise o r full counterclockwise pot enti o meter selling swill result int h e maximum e qua lIza t ion 01 +15 dB and ~15 dB respectively.

The outputs o f buffer amplifiers Z5, Z6 and Z8 e r-e routed to the

1&lt;_ 126 printed circuit board which contains Ihre e b &quot;ndpa s s nues

c orr esp o nd ing toe ach oft he th r-e e sections oft h e equalizer. Each

band pass filter passes only a portion of the s ig &quot;a l delivered to i t from the buffer, with. the center frequency end b endw ldth determined by the F RE&quot;QUENCY, &quot; Q&quot; ·&quot; n d PEAK/SHEL~co&quot;,..o ls.

The HIGH FREQUENCY equal l zelion Is cont in u ou sly adjustable from 1.5 to 25 kHz and is controlled b y Rl /R2. R21 determines the amount o f CUT or BOOST. A total r a&quot;ge from _15 to +15 dB Is provided. With SW11 depress e d Ihe unit will p..o duce a high frequency SHELVING ch a..a c teri stic. When SW11 is release d, both positive or &quot;egative PEAKING can b e obtained. The 0 cont..ol R3 is effect i v eon ly wllh SWll Int h e PEAKiNG mode and covers a O-f actor r a&quot;ge of 2 to 10.

The MID FREQUENCY eq u a liz tltlon Is adjusted by R4/RS, covering a frequency range trom 0.4 to 6.4 kHz. CUT/ BOOST Is controlled by R22. R6 tld j u s ts the O-f tlc to... Positive or &quot; e gtl tive bell shaped PEAKING equal lza l lon 1s applicable Int hem id-fre quency range.

The LOW FREOUENCY e q u tl liza t ion op e..ete s similarly tot he high frequency section. R7/R8 adjusts the frequency range from 25 to 400 Hz. CUT or BOOST are conlroll ed by R23, Q by R9 end SW12 determine s Ihe choice of either SHELVING or PEAKING che..tl c le r ls t k s.

The threes i g n a l s w hkh le tl v e Ih e 4_126 filter are &quot;correcl lon signals &quot; either In-p h a se or 18 0 degrees out_of_ph tl Sew ith the eq u &quot;l l ze.. Inp ul &quot;I'd btlnd p e s slim il e d es del ermlned by thee qua l i ze r sec tl o &quot; tlnd cont..ol setting s. These &quot; correct ions i g n a ls &quot; are t he&quot; summed tog ether w llh Ih e primary (Inp ut) signal by me op e r tlt ion,,1 amp l lfie &quot;s 2 1, 22 end 24 Ih u S fo..mi ng Ih e e q u tl l i zed OUl put slgn &quot; l.

This concept of adding eco....e c uce signal loge the.. with the Incoming s ig &quot;a l to form thee qua l i zeds i g na l Is d l..ec l l y responsible forth e low no l&quot; e and dl s lort ion capabilities oft his unit.

The compound signal es generated along thee n l l r e p&quot;oce s sing ch el l' epp ears e t the ou lput of Z4. F..o m here it Is &quot;oul ed 10 one 01 the norm&quot;l ly open contacts oft h e EQUALIZER INSERTs witch SW13.

ThuS, with SW13 depressed, thee qua l i zed slg n eli s fed tot h e OUlp ut

tl mp l l f l e.. 8-109A. In e d d l t lon, as SWl) Is depressed, the LEO Indi

cato r Is eCllvtlt ed.

S_109A OUl p u l Amplifier and INSERT

The S-109A amplifier ' -r a T&quot; e &quot; the s j g, ~ 10 _10 dBm nominally. The output i 5 active l y balanced and fed tot h e &quot; in &quot; e r t p o; nt&quot; a t pins 22 and Z o f module conn eclor Pl. This point;5 usually connected to a ~:~m::lt ~~d~a ~:~.O I Tns er t jacks, with the output side connected 10 the

The output 01 I h e balanced fade r is return e d 10 the module via p,n&quot; 14 and R of Pl. The feed forth e PRE FADE REVERBERATION SENO (RS), the PRE FADE FOLDBACK (F a) and the P REF ADE PUBliC ADDRESS (PA) channels;5 brought out a t PI, pins 20 and X and original e&quot; normally from the input side 01 the fade r.

An e x t erna l st ere input ' &quot; provided at connector P2, pins 8 and J. The slates ign al is;nj e&lt;:ted i n place oft here g u l a r signal when relay KI is activated. Tr1 m pOi R 142 serves to calibrate the slate level.

8 _ l09F Boo &quot; l er Amp l; fie r

This amplifier operates with again of J J dB. I t recover &quot; the 15dB &quot;in han d&quot; loss incur red by the fade rand provides add i lion alga into produce a nominal level of +8 dBm al II&quot; ou tpul.

A DIRECT outp UI from the 8_l09 F e mp li fie r; &quot; provided 0'1 1 connector P2, pins 12 end N. Aside from other u&quot; es within a given console system, the DIRECT output feeds the submas ter VU meter and serves a s the l a k eo ff point for monitoring.

Me Sl er Outputs and PAN Control

Two left end twO right outp u lS lire e lso fed b y the 8 l 09 F output

s' g nal. They are routed vie PANs witCh SW14 and PAN control R24 10 R27, followed by lou r MASTER ASSIGNMENT SWITCHES SW22 to SW2S. The

Auxiliary Outputs

In addition, a SOLO output i~ available via SWl 6, to allow ~e lec llve monitoring o f the particular sub master channel. Other feeds originating from the 8-10 9F amplifier ares u p plied to the POSTFADE RS, F B, and P A channels.

PRE /POST Selector Switches and Level Controls

P RE/PO ST ~el ec l lon of I heRS, Faa n d PAc h ann el sis fad lit ated by ~ w l lches SW18, SWI9, SW20 and SW4 respectively I each switch i s followed b y its associated level c onlro l. The outputs of the level controls are fed [0 the summing outputs via ind i v i dual assignment swi lc hes. Following the assign men t switches, theSe outputs are fed tot heir a p prop r ia te mixing buses via summing r e ~ l s tors.

A ux i liar y Control FunCllon s

DC c o nlrol c onlacts are provided on tn e SOLO and PA assignments witches top ermil external muting and s e le c l l v e control functions a s maybe require d.

Power Supply Oeco u p ling

An ecnve power supply d ecoupllng net....or k: ~onsiSl l ng of 0 1 through 06 provides a high degree of 1sol a tion between the M46 3L and the +/ _ 25 1,1 0 11 supply rails. The trans lsl o r S 05 and 0 6 ser-ve a s Ih e current monitors and will 11ml t the cur rent flow ing t h rough the pass trans i s tors 0 3 and 04 i n Ihe even l that excessive po....e r ~ upp ly demands should arise a s are sult of compo n e nt failure.

FREQUENCY RESPONSE CHARACTERISTICS

**M.63LA SUBMASTER MODULE EOUALIZ ER**

l=± I&quot;,

**I III II**

lOW FREQUENCY section I, I Mode: SHELVING.

CUT/B OOST: tIS se.

FREQUENCY: 25 1 400Hz.

**III... &quot;&quot;- II**

lOll FREQUENCY section

Mode: PEAKING.

CUT/B OOST: tI S dB.

FREQUENCY: 2S I 400 Hz.

Q: 2.

**FRECUENCY RESPONSE CHARACTERISTICS**

MID FREQUENCY sect fon CUT/ BOOST: ±IS dB.

FREQUENCY: 0.4 &amp; 6.4 kHz.

Q: 2.

MID FREQUENCY section BOOST: +3 t o +15 d B. I n 3 dB steps. Q: 2.

FREQUENCY: 1 kHz.

CUT: -61-15 dB. 0: 10. -

FREQUENCY: 2 kHz. -1II2'lIH'

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZmhEQUNERkl2MGs/view?resourcekey=0-58LeZLoxbrmsRegCry8-9Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZmhEQUNERkl2MGs&resourcekey=0-58LeZLoxbrmsRegCry8-9Q" width="240" alt="1974 - M463LA - 463-04-030 - ENG MEW SUBMASTER MODULE.jpg"></a><br><sub>1974|7 · 463-04-030 - ENG MEW SUBMASTER MODULE · <a href="MECHANICAL/1974%20-%20M463LA%20-%20463-04-030%20-%20ENG%20MEW%20SUBMASTER%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M463LA.stl`](MECHANICAL/M463LA.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M463LA)

- **Size:** 41 × 360 mm panel, 165 mm deep, 3.2 mm plate (TECHNICAL DATA: wide 14.5" high 6.5" deep (41 mm 360 mm 165 mm))
- **From the drawing:** 27 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M463LA - front panel.svg`)
- Made by `tools/module_models.py` (→ `MECHANICAL/M463LA.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKejVDN09nZUtBM3c/view?resourcekey=0-6hLEe_rB9uNNOAc6zep_XQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKejVDN09nZUtBM3c&resourcekey=0-6hLEe_rB9uNNOAc6zep_XQ" width="240" alt="1974 - M463LA - 4-126-02-001 - IOK COMBINED COMBINED VALLE VALUE.jpg"></a><br><sub>1974|7 · 4-126-02-001 - IOK COMBINED COMBINED VALLE VALUE · <a href="SCHEMATICS/1974%20-%20M463LA%20-%204-126-02-001%20-%20IOK%20COMBINED%20COMBINED%20VALLE%20VALUE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ3F1NUd2eVdmeFU/view?resourcekey=0-fiwvodS3K11REyJ5BHPtIg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ3F1NUd2eVdmeFU&resourcekey=0-fiwvodS3K11REyJ5BHPtIg" width="240" alt="1974 - M463LA - 4-126-06-001 - ISSMOD ICKD USED.jpg"></a><br><sub>1974|7 · 4-126-06-001 - ISSMOD ICKD USED · <a href="SCHEMATICS/1974%20-%20M463LA%20-%204-126-06-001%20-%20ISSMOD%20ICKD%20USED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUkRzOG9wX3pMMWc/view?resourcekey=0-m_80A6hU33z-w3PeInlqBg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUkRzOG9wX3pMMWc&resourcekey=0-m_80A6hU33z-w3PeInlqBg" width="240" alt="1974 - M463LA - 4-126-06-001 - SOCCKES ADDEI.jpg"></a><br><sub>1974|7 · 4-126-06-001 - SOCCKES ADDEI · <a href="SCHEMATICS/1974%20-%20M463LA%20-%204-126-06-001%20-%20SOCCKES%20ADDEI%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVktDdjhfV005R2c/view?resourcekey=0-KGE9JiEgBh-MTUoPA9Bbkw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVktDdjhfV005R2c&resourcekey=0-KGE9JiEgBh-MTUoPA9Bbkw" width="240" alt="1974 - M463LA - 4-136-06-023 - PIN ULCL WES WACO-D.jpg"></a><br><sub>1974|7 · 4-136-06-023 - PIN ULCL WES WACO-D · <a href="SCHEMATICS/1974%20-%20M463LA%20-%204-136-06-023%20-%20PIN%20ULCL%20WES%20WACO-D%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQXVwLVhoajNhR1U/view?resourcekey=0-lXcS9BOEjsbvZ4A3Sdxn8w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQXVwLVhoajNhR1U&resourcekey=0-lXcS9BOEjsbvZ4A3Sdxn8w" width="240" alt="1974 - M463LA - 4-141-02-001 - TORY SELECTED JAL VALE.jpg"></a><br><sub>1974|7 · 4-141-02-001 - TORY SELECTED JAL VALE · <a href="SCHEMATICS/1974%20-%20M463LA%20-%204-141-02-001%20-%20TORY%20SELECTED%20JAL%20VALE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcC0xdk55SEpoMm8/view?resourcekey=0-GlGUxrvIXfEuoLBsp5mLOA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcC0xdk55SEpoMm8&resourcekey=0-GlGUxrvIXfEuoLBsp5mLOA" width="240" alt="1974 - M463LA - 4-141-02-001.jpg"></a><br><sub>1974|7 · 4-141-02-001 · <a href="SCHEMATICS/1974%20-%20M463LA%20-%204-141-02-001%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcVFqZFNnRUtGX2c/view?resourcekey=0-29GcwoAkInusFP6qi88WNA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcVFqZFNnRUtGX2c&resourcekey=0-29GcwoAkInusFP6qi88WNA" width="240" alt="1974 - M463LA - 4-141-06-001 - ARE FACTORY SELECTED (2).jpg"></a><br><sub>1974|7 · 4-141-06-001 - ARE FACTORY SELECTED (2) · <a href="SCHEMATICS/1974%20-%20M463LA%20-%204-141-06-001%20-%20ARE%20FACTORY%20SELECTED%20(2)%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaEtPaTF0RnAyZms/view?resourcekey=0-WgMw6KployscV3PnLELDLA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaEtPaTF0RnAyZms&resourcekey=0-WgMw6KployscV3PnLELDLA" width="240" alt="1974 - M463LA - 4-141-06-001 - ARE FACTORY SELECTED.jpg"></a><br><sub>1974|7 · 4-141-06-001 - ARE FACTORY SELECTED · <a href="SCHEMATICS/1974%20-%20M463LA%20-%204-141-06-001%20-%20ARE%20FACTORY%20SELECTED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMDA2VVRwYmRwTlE/view?resourcekey=0-yqpL12IQbyEwBiu8T_D-qg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMDA2VVRwYmRwTlE&resourcekey=0-yqpL12IQbyEwBiu8T_D-qg" width="240" alt="1974 - M463LA - 4-141-06-001 - OPL ZOO RII.jpg"></a><br><sub>1974|7 · 4-141-06-001 - OPL ZOO RII · <a href="SCHEMATICS/1974%20-%20M463LA%20-%204-141-06-001%20-%20OPL%20ZOO%20RII%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ2hBcVdMVThwaG8/view?resourcekey=0-_Zx8PS3nXVrFW3atcJY8Tg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ2hBcVdMVThwaG8&resourcekey=0-_Zx8PS3nXVrFW3atcJY8Tg" width="240" alt="1974 - M463LA - 4-141-06-001 - WAAD-BECK BYSTEMB.jpg"></a><br><sub>1974|7 · 4-141-06-001 - WAAD-BECK BYSTEMB · <a href="SCHEMATICS/1974%20-%20M463LA%20-%204-141-06-001%20-%20WAAD-BECK%20BYSTEMB%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSjBCakRfRlZjT0E/view?resourcekey=0-RqOnkXksKRrR9gUNFdsvqQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSjBCakRfRlZjT0E&resourcekey=0-RqOnkXksKRrR9gUNFdsvqQ" width="240" alt="1974 - M463LA - 463-01-016 - CONTROL SOLO SOLO CONTROL SOLO COMMON CONTROL.jpg"></a><br><sub>1974|7 · 463-01-016 - CONTROL SOLO SOLO CONTROL SOLO COMMON CONTROL · <a href="SCHEMATICS/1974%20-%20M463LA%20-%20463-01-016%20-%20CONTROL%20SOLO%20SOLO%20CONTROL%20SOLO%20COMMON%20CONTROL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLUR4RUlaRDVTbmM/view?resourcekey=0-fEF_oM8Lmd_ZWZJRZvtXIw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLUR4RUlaRDVTbmM&resourcekey=0-fEF_oM8Lmd_ZWZJRZvtXIw" width="240" alt="1974 - M463LA - 463-01-016 - INSERT INSERT JACKS FADER.jpg"></a><br><sub>1974|7 · 463-01-016 - INSERT INSERT JACKS FADER · <a href="SCHEMATICS/1974%20-%20M463LA%20-%20463-01-016%20-%20INSERT%20INSERT%20JACKS%20FADER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKblZoUUFtalJnYkE/view?resourcekey=0-tY_kbe22yGyGoijSlU0p_A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKblZoUUFtalJnYkE&resourcekey=0-tY_kbe22yGyGoijSlU0p_A" width="240" alt="1974 - M463LA - 463-02-016 - SUB-MASTER MODULE COK ROM SCHEMATIC.jpg"></a><br><sub>1974|7 · 463-02-016 - SUB-MASTER MODULE COK ROM SCHEMATIC · <a href="SCHEMATICS/1974%20-%20M463LA%20-%20463-02-016%20-%20SUB-MASTER%20MODULE%20COK%20ROM%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLVlPZGMtSlpIejg/view?resourcekey=0-RFryXxunG8yyjQ8WAHmskA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLVlPZGMtSlpIejg&resourcekey=0-RFryXxunG8yyjQ8WAHmskA" width="240" alt="1974 - M463LA - 8-109-02-002 - OUTPUT AMPLIFIER.jpg"></a><br><sub>1974|7 · 8-109-02-002 - OUTPUT AMPLIFIER · <a href="SCHEMATICS/1974%20-%20M463LA%20-%208-109-02-002%20-%20OUTPUT%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMFV2NGp4a3VVaVU/view?resourcekey=0-6yFkbX2KL4ESKuzRDnTsbQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMFV2NGp4a3VVaVU&resourcekey=0-6yFkbX2KL4ESKuzRDnTsbQ" width="240" alt="1974 - M463LA - 8-109-02-002 - RII RIZ.jpg"></a><br><sub>1974|7 · 8-109-02-002 - RII RIZ · <a href="SCHEMATICS/1974%20-%20M463LA%20-%208-109-02-002%20-%20RII%20RIZ%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSDZ5NWtaYzV3cFU/view?resourcekey=0-AQcEH8XxTiwHxqdu0TCqCQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSDZ5NWtaYzV3cFU&resourcekey=0-AQcEH8XxTiwHxqdu0TCqCQ" width="240" alt="1974 - M463LA - 8-109-02-007 - NDMINAL VALUE.jpg"></a><br><sub>1974|7 · 8-109-02-007 - NDMINAL VALUE · <a href="SCHEMATICS/1974%20-%20M463LA%20-%208-109-02-007%20-%20NDMINAL%20VALUE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcFhPTDFvcjU5c2s/view?resourcekey=0-u5lMfI9zUOafFzORTD5joA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcFhPTDFvcjU5c2s&resourcekey=0-u5lMfI9zUOafFzORTD5joA" width="240" alt="1974 - M463LA - 8-109-02-007 - RII RIZ.jpg"></a><br><sub>1974|7 · 8-109-02-007 - RII RIZ · <a href="SCHEMATICS/1974%20-%20M463LA%20-%208-109-02-007%20-%20RII%20RIZ%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb1daZFlKU1RRSGM/view?resourcekey=0-08ggQSH3dVT3rM-bvaofKg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb1daZFlKU1RRSGM&resourcekey=0-08ggQSH3dVT3rM-bvaofKg" width="240" alt="1974 - M463LA - 8-109-06-002 - RAS COMPONENT LAYOUT.jpg"></a><br><sub>1974|7 · 8-109-06-002 - RAS COMPONENT LAYOUT · <a href="SCHEMATICS/1974%20-%20M463LA%20-%208-109-06-002%20-%20RAS%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVXlOMTNjSHNmMVk/view?resourcekey=0-2xu8AYykKJGb8wEaB41LRQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVXlOMTNjSHNmMVk&resourcekey=0-2xu8AYykKJGb8wEaB41LRQ" width="240" alt="1974 - M463LA - 8-109-06-002.jpg"></a><br><sub>1974|7 · 8-109-06-002 · <a href="SCHEMATICS/1974%20-%20M463LA%20-%208-109-06-002%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcmFlZnFNeG4yN1E/view?resourcekey=0-Vta-_GHsSOhVtN6wyMBVSQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcmFlZnFNeG4yN1E&resourcekey=0-Vta-_GHsSOhVtN6wyMBVSQ" width="240" alt="1974 - M463LA - 8-109-06-007 - BOOSTER AMPLIFIER.jpg"></a><br><sub>1974|7 · 8-109-06-007 - BOOSTER AMPLIFIER · <a href="SCHEMATICS/1974%20-%20M463LA%20-%208-109-06-007%20-%20BOOSTER%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMThKY01DNWllZTQ/view?resourcekey=0-BTOPlySjq4iBtzjxHToZsw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMThKY01DNWllZTQ&resourcekey=0-BTOPlySjq4iBtzjxHToZsw" width="240" alt="1974 - M463LA - 8-109-06-007 - DRI ENG.jpg"></a><br><sub>1974|7 · 8-109-06-007 - DRI ENG · <a href="SCHEMATICS/1974%20-%20M463LA%20-%208-109-06-007%20-%20DRI%20ENG%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVGFESkUyMzFINGM/view?resourcekey=0-qZ4nntvpAIr8T5yWfrikrA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVGFESkUyMzFINGM&resourcekey=0-qZ4nntvpAIr8T5yWfrikrA" width="240" alt="1976 - M463LA - 4-126-02-001 - EQUALIZER FILIER ISCALE AMPLIFIER SCHEMATX.jpg"></a><br><sub>1976|9 · 4-126-02-001 - EQUALIZER FILIER ISCALE AMPLIFIER SCHEMATX · <a href="SCHEMATICS/1976%20-%20M463LA%20-%204-126-02-001%20-%20EQUALIZER%20FILIER%20ISCALE%20AMPLIFIER%20SCHEMATX%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNUVBUWV4Z1pSS0k/view?resourcekey=0-83w1LIwAoA9qqNsvr_L4Ew" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNUVBUWV4Z1pSS0k&resourcekey=0-83w1LIwAoA9qqNsvr_L4Ew" width="240" alt="1974 - M463LA - 4-136-06-023 - COMPONENT SIDE NOTES LEGEND CONNECTOR PIN MOUNTED.jpg"></a><br><sub>1974|7 · 4-136-06-023 - COMPONENT SIDE NOTES LEGEND CONNECTOR PIN MOUNTED · <a href="PINOUTS/1974%20-%20M463LA%20-%204-136-06-023%20-%20COMPONENT%20SIDE%20NOTES%20LEGEND%20CONNECTOR%20PIN%20MOUNTED%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## RTO-144 pinout

12 contacts (P1), 22 contacts (P2). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 |  | unread |  | low |
| 3 |  | unread |  | low |
| 4 | OUTPUTS | out |  | low |
| 6 | OUTPUTS | out |  | low |
| 7 |  | unread |  | low |
| 8 |  | unread |  | low |
| 9 |  | unread |  | low |
| 12 |  | unread |  | low |
| 12 | OUTPUT | out |  | low |
| 18 | CTL COM | ground |  | low |
| 19 |  | unread |  | low |
| 20 |  | unread |  | low |
| 21 |  | unread |  | low |
| 22 |  | unread |  | low |
| D |  | unread |  | low |
| E |  | unread |  | low |
| F |  | unread |  | low |
| T |  | unread |  | low |
| Y |  | unread |  | low |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYUxwX0M4UnV0X2M/view?resourcekey=0-pXo2mON3WpXSmulS-ws9mw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYUxwX0M4UnV0X2M&resourcekey=0-pXo2mON3WpXSmulS-ws9mw" width="240" alt="1974 - M463LA - P003 - 1-1.jpg"></a><br><sub>1974|7 · P003 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd25Balpvc1NlUEU/view?resourcekey=0-uPR2HmMimZgcXMy-JWKdEQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd25Balpvc1NlUEU&resourcekey=0-uPR2HmMimZgcXMy-JWKdEQ" width="240" alt="1974 - M463LA - P004 - 2-1.jpg"></a><br><sub>1974|7 · P004 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaGdkM2RUT2pNdEE/view?resourcekey=0-roUAzp8Mp_G5sPYDiDuHiQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaGdkM2RUT2pNdEE&resourcekey=0-roUAzp8Mp_G5sPYDiDuHiQ" width="240" alt="1974 - M463LA - P005 - 2-2.jpg"></a><br><sub>1974|7 · P005 - 2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWFpHYjBNT21nelE/view?resourcekey=0-NHXu3u_GgqnIuszFob7Tmg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWFpHYjBNT21nelE&resourcekey=0-NHXu3u_GgqnIuszFob7Tmg" width="240" alt="1974 - M463LA - P006 - 2-3.jpg"></a><br><sub>1974|7 · P006 - 2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSVVEeWQ4N2hwVTA/view?resourcekey=0-bg3KslwFe-FwiPABwUB2Sg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSVVEeWQ4N2hwVTA&resourcekey=0-bg3KslwFe-FwiPABwUB2Sg" width="240" alt="1974 - M463LA - P007 - 2-4.jpg"></a><br><sub>1974|7 · P007 - 2-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZmVYd29MYWFSVlE/view?resourcekey=0-5VyL3byeWqdsMSoHx46hhg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZmVYd29MYWFSVlE&resourcekey=0-5VyL3byeWqdsMSoHx46hhg" width="240" alt="1974 - M463LA - P008 - 3-1.jpg"></a><br><sub>1974|7 · P008 - 3-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMEpUSmZOcjJxZWc/view?resourcekey=0-pCTTdpJJKXicMeAgwzN72Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMEpUSmZOcjJxZWc&resourcekey=0-pCTTdpJJKXicMeAgwzN72Q" width="240" alt="1974 - M463LA - P009 - 3-2.jpg"></a><br><sub>1974|7 · P009 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdUFpeFZnMzNnUWM/view?resourcekey=0-oW5Q4xD_rOpGxsKljimKGQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdUFpeFZnMzNnUWM&resourcekey=0-oW5Q4xD_rOpGxsKljimKGQ" width="240" alt="1974 - M463LA - P010 - 3-3.jpg"></a><br><sub>1974|7 · P010 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYmtMUmNrVUJkYk0/view?resourcekey=0-vdfdaUKf7tI7VJ5mC2HzmA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYmtMUmNrVUJkYk0&resourcekey=0-vdfdaUKf7tI7VJ5mC2HzmA" width="240" alt="1974 - M463LA - P011 - 4-1.jpg"></a><br><sub>1974|7 · P011 - 4-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUEJGR3p4U05KeDQ/view?resourcekey=0-dJZSe_gp7Pk46DhTMSWabA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUEJGR3p4U05KeDQ&resourcekey=0-dJZSe_gp7Pk46DhTMSWabA" width="240" alt="1974 - M463LA - P012 - 4-2.jpg"></a><br><sub>1974|7 · P012 - 4-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTzFxZnduQklwcFE/view?resourcekey=0-z6iXKfngbT9UcRYbPUVVwA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTzFxZnduQklwcFE&resourcekey=0-z6iXKfngbT9UcRYbPUVVwA" width="240" alt="1974 - M463LA - P013 - 5-1.jpg"></a><br><sub>1974|7 · P013 - 5-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU0dCb3N0ckFKbFk/view?resourcekey=0-NKRfn7PRnLZYqkZaIn5aeQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU0dCb3N0ckFKbFk&resourcekey=0-NKRfn7PRnLZYqkZaIn5aeQ" width="240" alt="1974 - M463LA - P014 - 5-2.jpg"></a><br><sub>1974|7 · P014 - 5-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdUZJWnVaaldMVFU/view?resourcekey=0-mmes5rrABvT9nReIX6o7sQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdUZJWnVaaldMVFU&resourcekey=0-mmes5rrABvT9nReIX6o7sQ" width="240" alt="1974 - M463LA - P015 - 5-3.jpg"></a><br><sub>1974|7 · P015 - 5-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQXlIWlY3N0RZazA/view?resourcekey=0-pSFMeNXnYBeiMPd9oEjG8w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQXlIWlY3N0RZazA&resourcekey=0-pSFMeNXnYBeiMPd9oEjG8w" width="240" alt="1974 - M463LA - P016 - 5-4.jpg"></a><br><sub>1974|7 · P016 - 5-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQWNIX2E2TmJGTzg/view?resourcekey=0-IrhQ10yaJlpnQvGIaxIR6A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQWNIX2E2TmJGTzg&resourcekey=0-IrhQ10yaJlpnQvGIaxIR6A" width="240" alt="1974 - M463LA - P017 - 5-5.jpg"></a><br><sub>1974|7 · P017 - 5-5</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQmdYbVBobzVZaGM/view?resourcekey=0-sUXwL6MpLXcKqDDK5VOcXQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQmdYbVBobzVZaGM&resourcekey=0-sUXwL6MpLXcKqDDK5VOcXQ" width="240" alt="1974 - M463LA - P018 - 5-6.jpg"></a><br><sub>1974|7 · P018 - 5-6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ1VtcHZ2cERFVVE/view?resourcekey=0-fVU1KF_G2IzUPRI9VBYTRw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ1VtcHZ2cERFVVE&resourcekey=0-fVU1KF_G2IzUPRI9VBYTRw" width="240" alt="1974 - M463LA - P019 - 5-7.jpg"></a><br><sub>1974|7 · P019 - 5-7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcVo1VEhsMFlfdWM/view?resourcekey=0-d_XWcjhqpmfHX2u_31F6hg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcVo1VEhsMFlfdWM&resourcekey=0-d_XWcjhqpmfHX2u_31F6hg" width="240" alt="1974 - M463LA - P020 - 5-8.jpg"></a><br><sub>1974|7 · P020 - 5-8</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNk0yRGxvU1RveWc/view?resourcekey=0-rlhy_cqUCbyVnW5XgrSnCw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNk0yRGxvU1RveWc&resourcekey=0-rlhy_cqUCbyVnW5XgrSnCw" width="240" alt="1974 - M463LA - P021 - 5-9.jpg"></a><br><sub>1974|7 · P021 - 5-9</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ05NUnhxUF9rZzA/view?resourcekey=0-mTtT4hSY1Idje-_IlKPA-A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ05NUnhxUF9rZzA&resourcekey=0-mTtT4hSY1Idje-_IlKPA-A" width="240" alt="1974 - M463LA - P022 - 6-1.jpg"></a><br><sub>1974|7 · P022 - 6-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcFVjR0VBeGpKaG8/view?resourcekey=0-1ljT1Hcx5whh3AqmC6c0zQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcFVjR0VBeGpKaG8&resourcekey=0-1ljT1Hcx5whh3AqmC6c0zQ" width="240" alt="1974 - M463LA - P023 - 6-2.jpg"></a><br><sub>1974|7 · P023 - 6-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcU5qUEhJbnk2SVk/view?resourcekey=0-Dz8mR-5D3QdDtO8X_SUErw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcU5qUEhJbnk2SVk&resourcekey=0-Dz8mR-5D3QdDtO8X_SUErw" width="240" alt="1974 - M463LA - P024 - 6-3.jpg"></a><br><sub>1974|7 · P024 - 6-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR0t2VEJZSUhzVXM/view?resourcekey=0-7q_c0kZEjqIEU1plruiYlA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR0t2VEJZSUhzVXM&resourcekey=0-7q_c0kZEjqIEU1plruiYlA" width="240" alt="1974 - M463LA - P025 - 8-109.jpg"></a><br><sub>1974|7 · P025 - 8-109</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX1VrOEoxcmM0Rm8/view?resourcekey=0-Lha0OH8tID5Aa0lydniIOw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX1VrOEoxcmM0Rm8&resourcekey=0-Lha0OH8tID5Aa0lydniIOw" width="240" alt="1974 - M463LA - P026 - 8-109-1-1.jpg"></a><br><sub>1974|7 · P026 - 8-109-1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWG5SNVpGek1JczQ/view?resourcekey=0-c3bGGRtUx4REu9z5KDRHmw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWG5SNVpGek1JczQ&resourcekey=0-c3bGGRtUx4REu9z5KDRHmw" width="240" alt="1974 - M463LA - P027 - 8-109-1-2.jpg"></a><br><sub>1974|7 · P027 - 8-109-1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWXRGSER4Z2VZUjg/view?resourcekey=0-mEgo4HzWAssWNPYvs9muVQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWXRGSER4Z2VZUjg&resourcekey=0-mEgo4HzWAssWNPYvs9muVQ" width="240" alt="1974 - M463LA - P028 - 8-109-2-1.jpg"></a><br><sub>1974|7 · P028 - 8-109-2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOVhIS1l0dHZTOFk/view?resourcekey=0-iKCXHrvfdWx4Ke9-gFDYWg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOVhIS1l0dHZTOFk&resourcekey=0-iKCXHrvfdWx4Ke9-gFDYWg" width="240" alt="1974 - M463LA - P029 - 8-109-2-2.jpg"></a><br><sub>1974|7 · P029 - 8-109-2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTEhSMFN4X1lnSjg/view?resourcekey=0-51aI3iimlChrQy4-0Vfs7A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTEhSMFN4X1lnSjg&resourcekey=0-51aI3iimlChrQy4-0Vfs7A" width="240" alt="1974 - M463LA - P030 - 8-109-2-3.jpg"></a><br><sub>1974|7 · P030 - 8-109-2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNGNLVHZ2c2pzSnc/view?resourcekey=0-DkpuvXz-fODJn3c2X4IAkQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNGNLVHZ2c2pzSnc&resourcekey=0-DkpuvXz-fODJn3c2X4IAkQ" width="240" alt="1974 - M463LA - P031 - 8-109-2-4.jpg"></a><br><sub>1974|7 · P031 - 8-109-2-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0pTTjJiTU5yOEk/view?resourcekey=0-I38P4wx8KdToHSF039nWHA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0pTTjJiTU5yOEk&resourcekey=0-I38P4wx8KdToHSF039nWHA" width="240" alt="1974 - M463LA - P032 - 8-109-2-5.jpg"></a><br><sub>1974|7 · P032 - 8-109-2-5</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa0czbEh6YUxTbEE/view?resourcekey=0-XEZsNkLn7SdFxDDc12-tPg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa0czbEh6YUxTbEE&resourcekey=0-XEZsNkLn7SdFxDDc12-tPg" width="240" alt="1974 - M463LA - P034 - 4-141 1-1.jpg"></a><br><sub>1974|7 · P034 - 4-141 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKczd0bHpDNjh4TVE/view?resourcekey=0-kNmITs38ID8QVi9zM3mtKw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKczd0bHpDNjh4TVE&resourcekey=0-kNmITs38ID8QVi9zM3mtKw" width="240" alt="1974 - M463LA - P035 - 4-141 2-1.jpg"></a><br><sub>1974|7 · P035 - 4-141 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTHZHbTg0SWJreW8/view?resourcekey=0-mDME9LkUakKI8S-2QSeGRA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTHZHbTg0SWJreW8&resourcekey=0-mDME9LkUakKI8S-2QSeGRA" width="240" alt="1974 - M463LA - P036 - 4-141 2-2.jpg"></a><br><sub>1974|7 · P036 - 4-141 2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVjZVSWVRSVRYczA/view?resourcekey=0-kamRw63cppr8Cm3nWkCtZA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVjZVSWVRSVRYczA&resourcekey=0-kamRw63cppr8Cm3nWkCtZA" width="240" alt="1974 - M463LA - P038 - 4-126 1-1.jpg"></a><br><sub>1974|7 · P038 - 4-126 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN3Z1cHIzOTE1c1k/view?resourcekey=0-I3wPD2kPs0fwFK2OcTT7SA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN3Z1cHIzOTE1c1k&resourcekey=0-I3wPD2kPs0fwFK2OcTT7SA" width="240" alt="1974 - M463LA - P039 - 4-126 2-1.jpg"></a><br><sub>1974|7 · P039 - 4-126 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVU9RYjVfcllXN0E/view?resourcekey=0-gtf5fRdcwtSjcG7Z3mBylA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVU9RYjVfcllXN0E&resourcekey=0-gtf5fRdcwtSjcG7Z3mBylA" width="240" alt="1974 - M463LA - P040 - 4-126 2-2.jpg"></a><br><sub>1974|7 · P040 - 4-126 2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMGdjaVhmajFIeVk/view?resourcekey=0-BlOI_KinBQCzS81MayRr0w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMGdjaVhmajFIeVk&resourcekey=0-BlOI_KinBQCzS81MayRr0w" width="240" alt="1974 - M463LA - P041 - 4-126 2-3.jpg"></a><br><sub>1974|7 · P041 - 4-126 2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcFdxSUxQdF8xU0E/view?resourcekey=0-2Y5svDq0Y-pHWuSk2WQL0g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcFdxSUxQdF8xU0E&resourcekey=0-2Y5svDq0Y-pHWuSk2WQL0g" width="240" alt="1974 - M463LA - P044 - LB463-02-016 001.jpg"></a><br><sub>1974|7 · P044 - LB463-02-016 001</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQTF1S05Yd1l5aGs/view?resourcekey=0-dc8MlXrr2264lxVayROOeg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQTF1S05Yd1l5aGs&resourcekey=0-dc8MlXrr2264lxVayROOeg" width="240" alt="1974 - M463LA - P044 - LB463-02-016 002.jpg"></a><br><sub>1974|7 · P044 - LB463-02-016 002</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVFduSXJveFJLS3M/view?resourcekey=0-nDo_814VYeOrmOsZWQlV6A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVFduSXJveFJLS3M&resourcekey=0-nDo_814VYeOrmOsZWQlV6A" width="240" alt="1974 - M463LA - P044 - LB463-02-016 003.jpg"></a><br><sub>1974|7 · P044 - LB463-02-016 003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYUppOS15bllVQTA/view?resourcekey=0-jSYRlXILGoX0P2d8KA334A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYUppOS15bllVQTA&resourcekey=0-jSYRlXILGoX0P2d8KA334A" width="240" alt="1974 - M463LA - P044 - LB463-02-016 004.jpg"></a><br><sub>1974|7 · P044 - LB463-02-016 004</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUWlBeHk2eG80Nnc/view?resourcekey=0-an4CuFpnhMv6AZioZ6Il9w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUWlBeHk2eG80Nnc&resourcekey=0-an4CuFpnhMv6AZioZ6Il9w" width="240" alt="1974 - M463LA - Submaster Module (2).pdf"></a><br><sub>1974|7 · Submaster Module (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1gB2rUxwIWOv1Wv1HY7MKvDtTVJTyRx3v/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1gB2rUxwIWOv1Wv1HY7MKvDtTVJTyRx3v" width="240" alt="1974 - M463LA - Submaster Module.jpg"></a><br><sub>1974|7 · Submaster Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQU9GVDRqTTVaMlk/view?resourcekey=0-5iqp-iykABso_bGkOvjt6A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQU9GVDRqTTVaMlk&resourcekey=0-5iqp-iykABso_bGkOvjt6A" width="240" alt="1974 - M463LA - Submaster Module.pdf"></a><br><sub>1974|7 · Submaster Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdktCTndmQWVLaHM/view?resourcekey=0-gMTvKHfbv90yr3rTfar4tw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdktCTndmQWVLaHM&resourcekey=0-gMTvKHfbv90yr3rTfar4tw" width="240" alt="1982 - M463LA - P001 - Title Page.jpg"></a><br><sub>1982|15 · P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVlhjeDFDYnViUEE/view?resourcekey=0-PDOxTUGRQG9kNJOEk6eR3w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVlhjeDFDYnViUEE&resourcekey=0-PDOxTUGRQG9kNJOEk6eR3w" width="240" alt="1983 - M463LA - P033 - 4-141.jpg"></a><br><sub>1983|16 · P033 - 4-141</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTXZDZHVrQ0xjUk0/view?resourcekey=0-rC25pHe1mye2W7GncvXVfQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTXZDZHVrQ0xjUk0&resourcekey=0-rC25pHe1mye2W7GncvXVfQ" width="240" alt="1983 - M463LA - P037 - 4-126.jpg"></a><br><sub>1983|16 · P037 - 4-126</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1974 - M463LA - 4-126-02-001 - IOK COMBINED COMBINED VALLE VALUE.kicad_sch](KICAD/1974%20-%20M463LA%20-%204-126-02-001%20-%20IOK%20COMBINED%20COMBINED%20VALLE%20VALUE.kicad_sch)
- [1974 - M463LA - 4-141-02-001 - TORY SELECTED JAL VALE.kicad_sch](KICAD/1974%20-%20M463LA%20-%204-141-02-001%20-%20TORY%20SELECTED%20JAL%20VALE.kicad_sch)
- [1974 - M463LA - 4-141-02-001.kicad_sch](KICAD/1974%20-%20M463LA%20-%204-141-02-001.kicad_sch)
- [1974 - M463LA - 463-01-016 - CONTROL SOLO SOLO CONTROL SOLO COMMON CONTROL.kicad_sch](KICAD/1974%20-%20M463LA%20-%20463-01-016%20-%20CONTROL%20SOLO%20SOLO%20CONTROL%20SOLO%20COMMON%20CONTROL.kicad_sch)
- [1974 - M463LA - 463-01-016 - INSERT INSERT JACKS FADER.kicad_sch](KICAD/1974%20-%20M463LA%20-%20463-01-016%20-%20INSERT%20INSERT%20JACKS%20FADER.kicad_sch)
- [1974 - M463LA - 463-02-016 - SUB-MASTER MODULE COK ROM SCHEMATIC.kicad_sch](KICAD/1974%20-%20M463LA%20-%20463-02-016%20-%20SUB-MASTER%20MODULE%20COK%20ROM%20SCHEMATIC.kicad_sch)
- [1974 - M463LA - 8-109-02-002 - OUTPUT AMPLIFIER.kicad_sch](KICAD/1974%20-%20M463LA%20-%208-109-02-002%20-%20OUTPUT%20AMPLIFIER.kicad_sch)
- [1974 - M463LA - 8-109-02-002 - RII RIZ.kicad_sch](KICAD/1974%20-%20M463LA%20-%208-109-02-002%20-%20RII%20RIZ.kicad_sch)
- [1974 - M463LA - 8-109-02-007 - NDMINAL VALUE.kicad_sch](KICAD/1974%20-%20M463LA%20-%208-109-02-007%20-%20NDMINAL%20VALUE.kicad_sch)
- [1974 - M463LA - 8-109-02-007 - RII RIZ.kicad_sch](KICAD/1974%20-%20M463LA%20-%208-109-02-007%20-%20RII%20RIZ.kicad_sch)
- [1974 - M463LA - Submaster Module (2) p2.kicad_sch](KICAD/1974%20-%20M463LA%20-%20Submaster%20Module%20(2)%20p2.kicad_sch)
- [1974 - M463LA - Submaster Module (2) p61.kicad_sch](KICAD/1974%20-%20M463LA%20-%20Submaster%20Module%20(2)%20p61.kicad_sch)
- [1974 - M463LA - Submaster Module p53.kicad_sch](KICAD/1974%20-%20M463LA%20-%20Submaster%20Module%20p53.kicad_sch)
- [1974 - M463LA - Submaster Module p57.kicad_sch](KICAD/1974%20-%20M463LA%20-%20Submaster%20Module%20p57.kicad_sch)
- [1974 - M463LA - Submaster Module p61.kicad_sch](KICAD/1974%20-%20M463LA%20-%20Submaster%20Module%20p61.kicad_sch)
- [1974 - M463LA - Submaster Module p65.kicad_sch](KICAD/1974%20-%20M463LA%20-%20Submaster%20Module%20p65.kicad_sch)
- [1976 - M463LA - 4-126-02-001 - EQUALIZER FILIER ISCALE AMPLIFIER SCHEMATX.kicad_sch](KICAD/1976%20-%20M463LA%20-%204-126-02-001%20-%20EQUALIZER%20FILIER%20ISCALE%20AMPLIFIER%20SCHEMATX.kicad_sch)
- [M463LA.kicad_sym](KICAD/M463LA.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
