# RetroJapSound [alpha] [v0.1.0]
A Comprehensive Reference to Sound Chips in Japanese Computers and Consoles, Including FMP, PMD, and MDX Music File Formats.

## Sound Chip
<table style="text-align: center">
<tr>
<th>Chip</th><th>FM</th><th>SSG</th><th>ADPCM / PCM</th><th>Output<br>DAC</th><th>Applications</th>
</tr>
<tr>
<td align="center" rowspan="3">YM2151<br>(OPM)</td><td align="center">FM (4-OP) ×8</td><td align="center" rowspan="3">N/A</td><td align="center" rowspan="3">N/A</td><td align="center">Stereo</td><td align="center">Arcade</td>
</tr>
<tr>
<td align="center" rowspan="2">

CSM[^1]
</td><td align="center" rowspan="2">YM3012</td><td align="center">X1turboZ</td>
</tr>
<tr>
<td align="center">X68000</td>
</tr>
<tr>
<td align="center" rowspan="3">YM2203<br>(OPN)</td><td align="center">FM (4-OP) ×3</td><td align="center" rowspan="3">SSG ×3<br>(Mono)<br>

(Built-in DAC)[^2]</td><td align="center" rowspan="3">N/A</td><td align="center">Mono</td><td align="center">PC-8801-11<br>(Soundboard)</td>
</tr>
<tr>
<td align="center" rowspan="2">

FM3ch Extend[^3] ×3 / CSM /<br> SSG-EG[^4]<br>(LFO removed)</td><td align="center" rowspan="2">YM3014</td><td align="center">PC-9801-26</td>
</tr>
<tr>
<td align="center">FM-77AV</td>
</tr>
<tr>
<td align="center" rowspan="3">YM2608<br>(OPNA)</td><td align="center">FM (4-OP) ×6</td> <td align="center" rowspan="3">SSG ×3<br>(Mono)<br>(Built-in DAC)</td><td align="center">4-bit/18.5kHz ADPCM-A RHY ×6<br>(Built-in rhythm samples)</td><td align="center">Stereo</td><td align="center">PC-8801-23<br>(Soundboard II)</td>
</tr>
<tr>
<td align="center" rowspan="2">FM3ch Extend ×3 / CSM /<br> SSG-EG</td><td align="center" rowspan="2">

4-bit[^5]/2-55.5kHz[^6]<br>ADPCM-B ×1</td><td align="center" rowspan="2">YM3016</td><td align="center">PC-9801-86<br>(86-Board)</td>
</tr>
<tr>
<td align="center">PC-9821</td>
</tr>
<tr>
<td align="center" rowspan="2">YM2610<br>(OPNB)</td><td align="center">FM (4-OP) ×4</td> <td align="center" rowspan="2">SSG ×3<br>(Mono)<br>(Built-in DAC)</td><td align="center">4-bit/18.5kHz<br>

ADPCM-A[^7] ×6</td><td align="center">Stereo</td><td align="center">SNK NEO•GEO</td>
</tr>
<tr>
<td align="center">2CH mode ×3 / CSM /<br> SSG-EG</td><td align="center">4-bit/2-55.5kHz<br>

ADPCM-B[^8] ×1</td><td align="center">YM3016</td><td align="center">TAITO Z System</td>
</tr>
<tr>
<td align="center" rowspan="2">YM2612<br>(OPN2)</td><td align="center">FM (4-OP) ×6</td><td align="center" rowspan="2">N/A</td><td align="center" rowspan="2">

8-bit/26(32)[^9]kHz<br>PCM ×1 (DA Mode, replaces FM Ch.6 when in use)</td><td align="center">Stereo</td><td align="center">FM Towns</td>
</tr>
<tr>
<td align="center">FM3ch Extend ×3 / CSM /<br> SSG-EG</td><td align="center">Built-in 9-bit DAC<br>

(w/ ladder effect)[^10]</td><td align="center">Mega Drive / Genesis<br>(MD1, MD2 VA2)</td>
</tr>
<tr>
<td align="center" rowspan="2">ASIC YM3438<br>(OPN2C)</td><td align="center">FM (4-OP) ×6</td><td align="center" rowspan="2">N/A</td><td align="center" rowspan="2">8-bit/26(32)kHz<br>PCM ×1 (DA Mode, replaces FM Ch.6 when in use)</td><td align="center">Stereo</td><td align="center" rowspan="2">Mega Drive / Genesis<br>(MD1 VA7, MD2, MD3, etc.)</td>
</tr>
<tr>
<td align="center">FM3ch Extend ×3 / CSM /<br> SSG-EG</td><td align="center">Built-in 9-bit DAC<br>(w/o ladder effect)</td>
</tr>
<tr>
<td align="center" rowspan="2">YMF288<br>(OPN3-L)</td><td align="center">FM (4-OP) ×6</td><td align="center" rowspan="2">SSG ×3<br>(Mono)<br>(Rare chip which has digital output of SSG)</td><td align="center">4-bit/18.5kHz ADPCM-A RHY ×6<br>(Built-in rhythm samples)</td><td align="center">Stereo</td><td align="center" rowspan="2">PC-9821</td>
</tr>
<tr>
<td align="center">FM3ch Extend ×3 / SSG-EG (CSM removed)</td><td align="center">ADPCM-B Removed</td><td align="center">Needs external DAC for both FM and SSG output</td>
</tr>
<tr>
<td align="center" rowspan="5">YMF262<br>(OPL3)</td><td align="center" colspan="3">FM<br>(36-OP, 2-OP or 4-OP per channel, with 8 types of waveforms)</td><td align="center">4-channel</td><td align="center" rowspan="3">SoundBlaster16 for PC-9800</td>
</tr>
<tr>
<td align="center" colspan="2">FM (2-OP) ×18 = 18ch</td><td align="center" rowspan="4">FM RHY ×5<br>(Built-in FM ryhthm generation, utilizing 3 FM channels)</td><td align="center" rowspan="4">YAC512</td>
</tr>
<tr>
<td align="center" colspan="2">FM (4-OP) ×6 + FM (2-OP) ×6 = 12ch</td>
</tr>
<tr>
<td align="center" colspan="2">FM (4-OP) ×6 + FM (2-OP) ×3 + RHY ×5 (6-OP) = 14ch</td><td align="center" rowspan="2">PC-9821</td>
</tr>
<tr>
<td align="center" colspan="2">FM (2-OP) ×15 + RHY ×5 (6-OP) = 20ch</td>
</tr>
<tr>
<td align="center" rowspan="4">YMF297<br>(OPN4)</td><td align="center" rowspan="3">YMF288 Mode<br>(Standard FM)</td><td align="center" colspan="2">FM (4-OP) ×6 + SSG ×3</td><td align="center">Stereo</td><td align="center" rowspan="2">PC-9821</td>
</tr>
<tr>
<td align="center" colspan="2">ADPCM-A RHY ×6<br>(Built-in rhythm samples)</td><td align="center" rowspan="3">Needs external DAC for both FM and SSG output</td>
</tr>
<tr>
<td align="center" colspan="2">ADPCM-B Removed</td><td align="center" rowspan="2">PC-9801-118</td>
</tr>
<tr>
<td align="center">YMF262 Mode<br>(Extended FM)</td><td align="center" colspan="2">36-OP, 2-OP or 4-OP per channel, with 8 types of waveforms</td>
</tr>
</table>

## Sound Board for PC-8800/PC-9800 series
<table style="text-align: center">
<tr>
<th>Sound Board</th><th>Chip</th><th>Year</th><th>JPY</th>
</tr>
<tr>
<td align="center">PC-8801-11<br>(Soundboard)</td><td align="center">YM2203</td><td align="center">1985/3</td><td align="center">¥19,800</td>
</tr>
<tr>
<td align="center">PC-8801-23<br>(Soundboard II)</td><td align="center">YM2608<br>(4-bit/2-55.5kHz ADPCM ×1)</td><td align="center">1987/10</td><td align="center">¥39,800</td>
</tr>
<tr>
<td align="center">PC-8801-24<br>(Soundboard II)<br>(for PC-8801FH/MH)</td><td align="center">YM2608<br>(4-bit/2-55.5kHz ADPCM ×1)</td><td align="center">1987/10</td><td align="center">¥39,800</td>
</tr>
<tr>
<td align="center">PC-8801-25<br>(Soundboard II)<br>(for PC-8801FE/FE2)</td><td align="center">YM2608<br>(4-bit/2-55.5kHz ADPCM ×1)</td><td align="center">1988/10</td><td align="center">¥39,800</td>
</tr>
<tr>
<td align="center">PC-88VA-12<br>(Soundboard II)<br>(for PC-88VA)</td><td align="center">YM2608<br>(4-bit/2-55.5kHz ADPCM ×1)</td><td align="center">1987/10</td><td align="center">¥39,800</td>
</tr>
<tr>
<td align="center">PC-9801-26<br>(Compatible with 8086)</td><td align="center">YM2203</td><td align="center">1985/7</td><td align="center">¥25,000</td>
</tr>
<tr>
<td align="center">PC-9801-26K<br>(Compatible with 80286)</td><td align="center">YM2203</td><td align="center">1986/11</td><td align="center">¥25,000</td>
</tr>
<tr>
<td align="center">Idol Japan<br>SP-26<br>(Speak-Board)</td><td align="center">YM2608<br>(4-bit/2-55.5kHz ADPCM ×1)</td><td align="center">1991/?</td><td align="center">¥49,800</td>
</tr>
<tr>
<td align="center">PC-9801-73</td><td align="center">YM2608<br>(4-bit/2-55.5kHz ADPCM ×1) +<br>

16-bit/44.1kHz PCM ×1[^11] + DSP(μPD6380)</td><td align="center">1991/11</td><td align="center">¥90,000</td>
</tr>
<tr>
<td align="center">PC-9801-86<br>(86-Board / 86-Sound)</td><td align="center">YM2608<br>

(w/o ADPCM-RAM)[^12] +<br>16-bit/44.1kHz 86-PCM ×1</td><td align="center">1993/2</td><td align="center">¥25,000</td>
</tr>
<tr>
<td align="center">MAD Factory<br>Chibi-oto add on<br>(ADPCM-RAM for 86-Board)</td><td align="center">86-Board + Chibi-oto add on<br>YM2608<br>(w/ ADPCM-RAM) ADPCM ×1</td><td align="center">1993/12</td><td align="center">¥5,000</td>
</tr>
<tr>
<td align="center" rowspan="2">PC-9801-118<br>(Windows)<br>(Set PnP switch to OFF<br>for MS-DOS mode)</td><td align="center">YMF297<br>(YMF288 Mode or YMF262 Mode)<br>(Compatible with 86-Board / Sound Blaster)</td><td align="center" rowspan="2">1995/11</td><td align="center" rowspan="2">¥22,000</td>
</tr>
<tr>
<td align="center">CS4232<br>(WSS-PCM ×1 + JOY + MIDI I/F)</td>
</tr>
</table>

## Relative SSG to FM Volume Ratio
| Environment | Relative Volume of SSG[^13] |
| :----: | :----: |
| PC-8001mk II SR<br>PC-8801-11 (JP2:1-2) | 60% |
| PC-8801 (YM2203-equipped models)<br>PC-8801-11 (JP2:2-3) | 	55% |
| PC-8801 (YM2608-equipped models) | 50% |
| PC-8801-23 | 58% |
| PC-88VA,VA2,VA3 | 55% |
| PC-88VA-12 | 125%<sup>?</sup> |
| PC-98DO+ | 50% |
| PC-9801 (YM2203-equipped models)<br>Soundboard (YM2203-equipped models) | 30% |
| PC-98x1 (YM2608-equipped models)<br>Soundboard (YM2608-equipped models) | 25% |
| PC-98x1 (YMF288/YMF297-equipped models)<br>Soundboard (YMF288/YMF297-equipped models) | 25%
| Speak-Board | 30% |
| AMUSEMENT SOUND BOARD (ASB-01) | 24% |
| Otomi-chan | 65%<sup>?</sup> |

## Sound Driver
### FMP
<table style="text-align: center">
<tr>
<th>Environment</th><th>Sound Source</th><th>Polyphony</th><th>Driver</th><th>File Ext.</th>
</tr>
<tr>
<td align="center">PC-9801-26(K)</td><td align="center">YM2203</td><td align="center">FM ×3 + SSG ×3 + FM3 Extend ×3<br>Max: 9</td><td align="center">FMP.COM<br>(FMP4)</td><td align="center"><code>.OPI</code></td>
</tr>
<tr>
<td align="center" rowspan="2">PC-9801-26(K)</td><td align="center">YM2203</td><td align="center" rowspan="2">FM ×3 + SSGPCM ×3 + FM3 Extend ×3<br>Max: 9</td><td align="center">FMP.COM</td><td align="center"><code>.OZI</code></td>
</tr>
<tr>
<td align="center">SSGPCM ×3<br>

(8-bit/16kHz)[^14]</td><td align="center">PPZ.COM</td><td align="center"><code>.PVI</code></td>
</tr>
<tr>
<td align="center" rowspan="2">Idol Japan SP-26<br>(Speak-Board)</td><td align="center">YM2608</td><td align="center" rowspan="2">FM ×6 + SSG ×3 + FM3 Extend ×3 + RHY ×6 + ADPCM ×1<br>Max: 19</td><td align="center" rowspan="2">FMP.COM<br>(FMP4)</td><td align="center"><code>.OVI</code></td>
</tr>
<tr>
<td align="center">ADPCM ×1</td><td align="center"><code>.PVI</code></td>
</tr>
<tr>
<td align="center" rowspan="3">Idol Japan SP-26<br>(Speak-Board)</td><td align="center">YM2608</td><td align="center" rowspan="3">FM ×6 + SSGPCM ×3 + FM3 Extend ×3 + RHY ×6 + ADPCM ×1<br>Max: 19</td><td align="center" rowspan="2">FMP.COM</td><td align="center"><code>.OZI</code></td>
</tr>
<tr>
<td align="center">ADPCM ×1</td><td align="center" rowspan="2"><code>.PVI</code></td>
</tr>
<tr>
<td align="center">SSGPCM ×3<br>(8-bit/16kHz)</td><td align="center">PPZ.COM</td>
</tr>
<tr>
<td align="center" rowspan="3">PC-9801-86<br>+<br>Chibi-oto add on</td><td align="center">YM2608</td><td align="center" rowspan="3">FM ×6 + SSGPCM ×3 + FM3 Extend ×3 + RHY ×6 + ADPCM/PCM ×1<br>Max: 19</td><td align="center" rowspan="2">FMP.COM</td><td align="center"><code>.OZI</code></td>
</tr>
<tr>
<td align="center">ADPCM ×1</td><td align="center" rowspan="2"><code>.PVI</code></td>
</tr>
<tr>
<td align="center">SSGPCM ×3<br>(8-bit/16kHz)</td><td align="center">PPZ.COM</td>
</tr>
<tr>
<td align="center" rowspan="3">PC-9801-86</td><td align="center">YM2608</td><td align="center" rowspan="3">

FM ×6 + SSGPCM ×3 + FM3 Extend ×3 + RHY ×6 + ADPCM/PCM ×1[^15]<br>Max: 19</td><td align="center">FMP.COM</td><td align="center"><code>.OZI</code></td>
</tr>
<tr>
<td align="center">ADPCM ×1<br>

(Speak-Board EMU)[^16]</td><td align="center" rowspan="2">PPZ8.COM</td><td align="center" rowspan="2"><code>.PVI</code></td>
</tr>
<tr>
<td align="center">SSGPCM ×3<br>

(PPZ EMU)[^17]</td>
</tr>
<tr>
<td align="center" rowspan="4">PC-9801-86</td><td align="center">YM2608</td><td align="center" rowspan="4">FM ×6 + SSGPCM ×3 + FM3 Extend PCM ×3 + RHY ×6 + ADPCM/PCM ×1<br>Max: 19</td><td align="center">FMP.COM</td><td align="center"><code>.OZI</code></td>
</tr>
<tr>
<td align="center">ADPCM ×1<br>(Speak-Board EMU)</td><td align="center" rowspan="2">PPZ8.COM</td><td align="center" rowspan="3"><code>.PVI</code></td>
</tr>
<tr>
<td align="center">SSGPCM ×3<br>(PPZ EMU)</td>
</tr>
<tr>
<td align="center">FM3 Extend PCM ×3</td><td align="center">Z8X.COM</td>
</tr>
<tr>
<td align="center" rowspan="4">PC-9801-86</td><td align="center">YM2608</td><td align="center" rowspan="4">FM ×6 + SSGPCM ×3 + FM3 Extend PCM ×3 + RHY PCM ×6 + ADPCM/PCM ×1<br>Max: 19</td><td align="center">FMP.COM</td><td align="center"><code>.OZI</code></td>
</tr>
<tr>
<td align="center">SSGPCM ×3<br>(PDZF)</td><td align="center">PPZ8.COM</td><td align="center" rowspan="3"><code>.PVI</code></td>
</tr>
<tr>
<td align="center">FM3 Extend PCM ×3</td><td align="center" rowspan="2">PDZF.COM</td>
</tr>
<tr>
<td align="center">RHY PCM ×6</td>
</tr>
<tr>
<td align="center" rowspan="3">PC<br>Windows</td><td align="center">FMP</td><td align="center" rowspan="3">FM ×6 + SSGPCM ×3 + FM3 Extend PCM ×3 + RHY PCM ×6 + ADPCM/PCM ×1<br>Max: 19</td><td align="center" rowspan="2">

WinFMP.dll[^18]</td><td align="center" rowspan="3"><code>.OPI</code><br><code>.OVI</code><br><code>.OZI</code><br><code>.PVI</code></td>
</tr>
<tr>
<td align="center">PPZ8</td>
</tr>
<tr>
<td align="center">Z8X + PDZF</td><td align="center">PDZFZ8XWin.dll</td>
</tr>
<tr>
<td align="center">PC<br>Windows</td><td align="center">

[FMP7](http://guu.fmp.jp/archives/493)[^19]</td><td align="center">OPNA FM ×32 + OPM FM ×32 + SSG ×32 + PCM ×32<br>Max: 64</td><td align="center">exFMP7.dll</td><td align="center"><code>.OWI</code><br><code>.PWI</code></td>
</tr>
</table>

### PMD(98)
<table style="text-align: center">
<tr>
<th>Environment</th><th>Sound Source</th><th>Polyphony</th><th>Driver</th><th>File Ext.</th>
</tr>
<tr>
<td align="center" rowspan="2">PC-9801-26(K)</td><td align="center">YM2203</td><td align="center" rowspan="2">

FM ×3 + SSG ×2 + SSG Drums[^20] ×1 + FM3 Extend ×3<br>Max: 9</td><td align="center" rowspan="2">PMD.COM</td><td align="center" rowspan="2"><code>.M</code></td>
</tr>
<td align="center"><br>SSGDrums ×1 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
<tr>
</tr>
<tr>
<td align="center" rowspan="2">PC-9801-26(K)</td><td align="center">YM2203</td><td align="center" rowspan="2">FM ×3 + SSG ×2 + SSGPCM ×1 + FM3 Extend ×3<br>Max: 9</td><td align="center">PMD.COM</td><td align="center"><code>.M</code></td>
</tr>
<tr>
<td align="center">SSGPCM ×1<br>

(4-bit/16kHz)[^21]</td><td align="center">PDR.COM<br>PPSDRV.COM</td><td align="center"><code>.PPS</code></td>
</tr>
<tr>
<td align="center" rowspan="2">Idol Japan SP-26<br>(Speak-Board)</td><td align="center">YM2608</td><td align="center" rowspan="2">FM ×6 + SSG ×2 + SSG Drums ×1 + FM3 Extend ×3 + RHY ×6 + ADPCM ×1<br>Max: 19</td><td align="center" rowspan="2">PMDB2.COM</td><td align="center"><code>.M2</code></td>
</tr>
<tr>
<td align="center">ADPCM ×1</td><td align="center"><code>.PVI</code><br><code>.PPC</code></td>
</tr>
<tr>
<td align="center" rowspan="2">PC-9801-86</td><td align="center">YM2608</td><td align="center" rowspan="2">FM ×6 + SSG ×2 + SSG Drums ×1 + FM3 Extend ×3 + RHY ×6 + 86-PCM ×1<br>Max: 19</td><td align="center">PMD86.COM</td><td align="center"><code>.M2</code></td>
</tr>
<tr>
<td align="center">86-PCM ×1</td><td align="center">P86DRV.COM</td><td align="center"><code>.P86</code></td>
</tr>
<tr>
<td align="center" rowspan="3">PC-9801-86</td><td align="center">YM2608</td><td align="center" rowspan="3">FM ×6 + SSG ×2 + SSG Drums ×1 + FM3 Extend ×3 + RHY ×6 + PPZ8 PCM ×8<br>(Software Mixing)<br>Max: 26</td><td align="center">PMDPPZ.COM</td><td align="center"><code>.MZ</code></td>
</tr>
<tr>
<td align="center" rowspan="2">PPZ8 PCM ×8</td><td align="center" rowspan="2">PPZ8.COM</td><td align="center"><code>.PVI</code></td>
</tr>
<tr>
<td align="center"><code>.PZI</code></td>
</tr>
<tr>
<td align="center" rowspan="4">PC<br>Windows</td><td align="center">PMDPPZ</td><td align="center" rowspan="4">FM ×6 + SSG ×2 + SSGPCM ×1 + FM3 Extend ×3 + RHY ×6 + PCM ×8<br>(Software Mixing)<br>Max: 26</td><td align="center" rowspan="4">

PMDWin.dll[^18]</td><td align="center"><code>.M</code><br><code>.M2</code><br><code>.MZ</code><br><code>.PPC</code></td>
</tr>
<tr>
<td align="center">PDR<br>PPSDRV</td><td align="center"><code>.PPS</code></td>
</tr>
<tr>
<td align="center">P86drv</td><td align="center"><code>.P86</code></td>
</tr>
<tr>
<td align="center">PPZ8</td><td align="center"><code>.PVI</code><br><code>.PZI</code></td>
</tr>
</table>

### MXDRV
<table style="text-align: center">
<tr>
<th>Environment</th><th>Sound Source</th><th>Polyphony</th><th>Driver</th><th>File Ext.</th>
</tr>
<tr>
<td align="center" rowspan="2"><br>Sharp<br>X68000<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td><td align="center"><br>YM2151<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td><td align="center" rowspan="2"><br>FM ×8 + ADPCM ×8<br>(Software Mixing)<br>Max: 16<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td><td align="center">MXDRV.X</td><td align="center" rowspan="2"><code>.MDX</code><br><code>.PDX</code></td>
</tr>
<tr>
<td align="center">PCM8</td><td align="center">PCM8.X</td>
</tr>
</table>

## File Format
<table style="text-align: center">
<tr>
<th>File Ext.</th><th>Type</th><th>Codec</th><th>Driver</th><th>Environment</th><th  width="300">Specifications</th>
</tr>
<tr>
<td align="center"><code>.OPI</code></td><td align="center">Music</td><td align="center">N/A</td><td align="center">FMP</td><td align="center">OPN</td><td align="center"></td>
</tr>
<tr>
<td align="center"><code>.OVI</code></td><td align="center">Music</td><td align="center">N/A</td><td align="center">FMP</td><td align="center">OPNA</td><td align="center"></td>
</tr>
<tr>
<td align="center" rowspan="2"><code>.OZI</code></td><td align="center" rowspan="2">Music</td><td align="center" rowspan="2">N/A</td><td align="center">FMP<br>(w/ PPZ)</td><td align="center">OPN<br>OPNA</td><td align="center"></td>
</tr>
<tr>
<td align="center">FMP<br>(w/ PPZ8)</td><td align="center">86-Board</td><td align="center"></td>
</tr>
<tr>
<td align="center"><code>.OWI</code></td><td align="center">Music</td><td align="center">N/A</td><td align="center">FMP7</td><td align="center">Windows</td><td align="center"></td>
</tr>
<tr>
<td align="center"><code>.M</code></td><td align="center">Music</td><td align="center">N/A</td><td align="center">PMD</td><td align="center">OPN</td><td align="center">Some PMDB2, PMD86, and PMDPPZ music data also use this extension.</td>
</tr>
<tr>
<td align="center" rowspan="2"><code>.M2</code></td><td align="center" rowspan="2">Music</td><td align="center" rowspan="2">N/A</td><td align="center">PMDB2</td><td align="center">OPNA</td><td align="center" rowspan="2"></td>
</tr>
<tr>
<td align="center">PMD86</td><td align="center">86-Board</td>
</tr>
<tr>
<td align="center"><code>.MZ</code></td><td align="center">Music</td><td align="center">N/A</td><td align="center">PMDPPZ<br>(w/ PPZ8)</td><td align="center">86-Board</td><td align="center"></td>
</tr>
<tr>
<td align="center"><code>.MDX</code></td><td align="center">Music</td><td align="center">N/A</td><td align="center">MXDRV</td><td align="center">X68000</td><td align="center"></td>
</tr>
<tr>
<td align="center" rowspan="5"><code>.PVI</code></td><td align="center" rowspan="5">Sample</td><td align="center" rowspan="5">ADPCM</td><td align="center">FMP<br>(w/ PPZ)</td><td align="center">OPN<br>OPNA</td><td align="center">SSGPCM: 8-bit/16kHz<br>(4-bit ADPCM -> 8-bit PCM)</td>
</tr>
<tr>
<td align="center">FMP</td><td align="center" rowspan="2">OPNA</td><td align="center" rowspan="4">ADPCM: 4-bit/16kHz at <code>o5g</code><br>While it was initially designed as FMP's sample data in ADPCM format, this data can be adapted for use in PPZ8 parts (compatible with both FMP and PMDPPZ) as well as PMDB2.</td>
</tr>
<tr>
<td align="center">PMDB2</td>
</tr>
<tr>
<td align="center">FMP<br>(w/ PPZ8)</td><td align="center" rowspan="2">86-Board</td>
</tr>
<tr>
<td align="center">PMDPPZ<br>(w/ PPZ8)</td>
</tr>
<tr>
<td align="center"><code>.PZI</code></td><td align="center">Sample</td><td align="center">PCM</td><td align="center">PMDPPZ<br>(w/ PPZ8)</td><td align="center">86-Board</td><td align="center">PPZ8 PCM: 8-bit/16.54kHz at <code>o5c</code></td>
</tr>
<tr>
<td align="center"><code>.PPS</code></td><td align="center">Sample</td><td align="center">PCM</td><td align="center">PDR<br>PPSDRV</td><td align="center">OPN<br>OPNA<br>86-Board</td><td align="center">SSGPCM: 4-bit/16kHz</td>
</tr>
<tr>
<td align="center"><code>.PPC</code></td><td align="center">Sample</td><td align="center">ADPCM</td><td align="center">PMDB2</td><td align="center">OPNA</td><td align="center">ADPCM: 4-bit/16kHz at <code>o5g</code></td>
</tr>
<tr>
<td align="center"><code>.P86</code></td><td align="center">Sample</td><td align="center">PCM</td><td align="center">P86DRV</td><td align="center">86-Board</td><td align="center">86-PCM: 8-bit/16.54kHz at <code>o5g</code></td>
</tr>
<tr>
<td align="center"><code>.PWI</code></td><td align="center">Sample</td><td align="center">PCM</td><td align="center">FMP7</td><td align="center">Windows</td><td align="center">PCM: 16-bit/44.1kHz</td>
</tr>
<tr>
<td align="center" rowspan="2"><code>.PDX</code></td><td align="center" rowspan="2">Sample</td><td align="center" rowspan="2">ADPCM</td><td align="center" rowspan="2">MXDRV</td><td align="center" rowspan="2">X68000</td><td align="center">PDX<br>ADPCM: 4-bit@3.9/5.2/7.8/10.4/15.6kHz</td>
</tr>
<tr>
<td align="center">EX-PDX<br>PCM8: 8-bit@15.6kHz or 16bit@15.6kHz<br>(Uses linear PCM in EX-PCM mode)</td>
</tr>
</table>

## Platforms
<table style="text-align: center">
<tr>
<th>Name</th><th>Chip</th><th>Synthesis</th><th>ADPCM / PCM</th><th colspan="2">Showcase</th>
</tr>
<tr>
<td align="center" rowspan="5">NEC<br>PC Engine / <br>TurboGrafx-16

***
PC Engine SuperGrafx</td><td align="center" rowspan="3">Hudson Soft HuC6280</td><td align="center">WSG ×6<br>(Programmable 5bit ×32 sample waveforms)</td><td align="center" rowspan="3">

5-bit, 8/9/10-bit[^22]<br>(using channel pairing)<br>@7kHz, 15.7kHz<br>(using hblank interrupt)<br>PCM<br>(Direct D/A Mode, replaces any channel)</td><td align="center" rowspan="3" width="15%">

[Soldier Blade](https://www.youtube.com/watch?v=FX3tK3u9clU "Operation 1 / Keita Hoshi / The HuC6280's panpot control was quite unique compared to other sound chips of its time, which typically only allowed three positions: left, center, and right. The HuC6280, however, used 4-bit volume registers for each stereo channel, allowing fine control over the panpot position with 16 levels per side. In this video, you can hear the composer using the HuC6280's DDA function to play PCM drum samples, with rapid and wild panpot changes to move the tom-tom across the stereo field.")
***
[Magical Chase](https://www.youtube.com/watch?v=vl0BLQr2nww "Variations on a Ra Melody (6TH STAGE - SUNCTUARY) / Hitoshi Sakimoto")
***
[Devil Crash](https://www.youtube.com/watch?v=_P6FFjlSbVY "Main Table / Toshiaki Sakoda")
***
[PC Denjin](https://www.youtube.com/watch?v=OMdFIDkuvMU "Stage 2 (Brains Town) / Daisuke Morishima")
***
[Momotarou Katsugeki](https://www.youtube.com/watch?v=aY6xjWaEgj4 "Netarou Village / Michiko Yoshida")</td><td align="center" rowspan="3" width="15%">

[Aldynes](https://www.youtube.com/watch?v=LlFHCJGPxfs "Stage 4 / Keita Hoshi")
***
[Zero4 Champ](https://fi.zophar.net/soundfiles/turbografx-16-hes/zero4-champ/10%20BGM%20%2310.mp3 "ZERO 4 CHAMP ! (Ending Ver.) ‐Epilogue Demo- / Tsukushi Sasaki")
[^23]
***
[TATSUJIN](https://www.youtube.com/watch?v=8is3T-juZe0&t=724s "Unknown (Stage 5) / Masahiro Yuge / arr. by Tsukasa Masuko")
***
[Streets of Rage](https://www.youtube.com/watch?v=b5wIDsarIVs "Fighting In The Street (TurboGrafx-16/PC-Engine Chiptune Cover) [No Samples] / Yuzo Koshiro / covered by Fragmare")
***
[Paper Energy](https://www.youtube.com/watch?v=6QSx4o9Q9tM "Original tune by MegaSparky")</td>
</tr>
<tr>
<td align="center">LFO Mode:<br>

Quasi-FM[^24] ×1<br>(Uses Ch.1 + Ch.2)</td>
</tr>
<tr>
<td align="center">Noise Mode:<br>Noise ×1 or Noise ×2<br>(Uses Ch.5 or Ch.6)</td>
</tr>
<tr>
<td align="center" colspan="5">CD-ROM<sup>2</sup> / TurboGrafx-CD</td>
</tr>
<tr>
<td align="center">Oki MSM5205</td><td align="center">N/A</td><td align="center">

4-bit[^25]/up to 32.088kHz ADPCM ×1</td><td align="center" colspan="2">[Dragon Slayer:<br>The Legend of Heroes](https://www.youtube.com/watch?v=d_cbsEA_vO4 "Town (PSG Version) / Falcom Sound Team J.D.K. / PSG programmed by Keita Hoshi")</td>
</tr>
<tr>
<td align="center" rowspan="3">SEGA<br>Mega Drive / Genesis</td><td align="center" rowspan="2">YM2612</td><td align="center" rowspan="2">FM ×6<br>FM3ch Extend ×3 / CSM</td><td align="center">8-bit/26(32)kHz PCM ×1 (DA Mode, replaces FM Ch.6 when in use)</td><td align="center" rowspan="3">

[Vapor Trail](https://www.youtube.com/watch?v=XQT5f_-vEAU "Vapor Trail / Hiroaki Yoshida")
***
[Zero Wing](https://www.youtube.com/watch?v=ICSbPAfaA04 "New Day for Me (Stage 2: Legrous) / Toshiaki Tomizawa, Tatsuya Uemura")
***
[Master of Monsters](https://www.youtube.com/watch?v=XkskpN2cl-s "Standing in the White Fortress (BGM 05) / Hayato Matsuo / Manipulate, sound effect, sound driver creation by Hitoshi Sakimoto")
***
[The Hybrid Front](https://www.youtube.com/watch?v=Pi7tRTLZ32U "Moon / Mars ~ Sukarabe Fight BGM 2 / Naofumi Hataya")
***
[Mega Turrican](https://www.youtube.com/watch?v=rMfi_airOZA&t=112s "Stage 1-1 / Chris Hülsbeck")</td><td align="center" rowspan="3">

[Elemental Master](https://www.youtube.com/watch?v=PfpqMezmA4g "Blood-Stained Lake (Stage 4) / Toshiharu Yamanishi")
***
[Gauntlet IV](https://www.youtube.com/watch?v=tagsexfxDoE "Sortie / Hitoshi Sakimoto, Masaharu Iwata")
***
[Time Trax](https://www.youtube.com/watch?v=grWDeVPchzE "Title Screen/Credits / Tim Follin")
***
[Sonic the Hedgehog](https://www.youtube.com/watch?v=6lM4BfqzaSM "Green Hill Zone (2024) (YM2612 + SN76489 Arrangement) / covered by John \"Joy\" Tay")
***
[Xeno Crisis](https://www.youtube.com/watch?v=qFng5qjbVVc "Area 1 - Perimeter / Savaged Regime")
[^26]</td>
</tr>
<tr>
<td align="center">

Various Sound Drivers[^27] (Software mixing, e.g. XGM: up to 8-bit/14kHz PCM ×4, replaces FM Ch.6 when in use)</td>
</tr>
<tr>
<td align="center">SN76489<br>(DCSG)</td><td align="center">Square ×3 + Simple Noise ×1<br>(Limited Mode)<br>or<br>Square ×2 + Full Noise ×1<br>

(Full Mode)[^28]<br>(Mono)</td><td align="center">Various PCM Drivers<br>(e.g. pcmenc: up to 12-bit/11.025kHz<br>

PSGPCM[^29] ×1, replaces PSG channels when in use)</td>
</tr>
<tr>
<td align="center" rowspan="16">Sharp X68000</td><td align="center">YM2151</td><td align="center">FM×8<br>CSM</td><td align="center">N/A</td><td align="center" rowspan="3">

[Sion II](https://www.youtube.com/watch?v=3cbJ3-U4qnE "It doesn't amount to anything. / Zenji Nishikawa / reprogrammed by Noriyuki Shindou from the SC-55 version")
[^30]
***
[Namachuukei 68](https://www.youtube.com/watch?v=zMHsJR6xSQw "Ending / Yuji Takenouchi")
[^31]
***
[Bosconian](https://www.youtube.com/watch?v=uKO3S_YTLZY "Flash Flash Flash / Yuzo Koshiro")
[^32]
***
[OVERTAKE](https://www.youtube.com/watch?v=l_yrxQZ9kPg "FRANTICALLY / ZOOM Sound Team (Hideyuki Shimono, Naoyuki Kimura)")
[^33]
***
[Illumination Laser](https://www.youtube.com/watch?v=TKDZS6ugsx8&t=552s "The Origin Yellow / Nobuhisa Shinoda (I.C.KaZe)")
[^34]
***
[Cyber Block Metal Orange EX](https://www.youtube.com/watch?v=SFKi02h4q4A "Stage 1 (ORION) / Yoshio Furukawa (JKL FURUKAWA)")
[^35]</td><td align="center" rowspan="3">

[Butasan Quest](https://www.youtube.com/watch?v=goSCKFGv1Ys&t=116s "SKYHIGH ADVENTURE / Karuchan (CUL.)")
[^36]
***
[Viper-V8 Twin Turbo](https://www.youtube.com/watch?v=syNw5FZxjBk&t=825s "TOO COLD / Kenichi Arakawa")
***
[Dragon Knight 4](https://www.youtube.com/watch?v=biyc15hFm-U&t=3633s "lead the van / Witch (Tsuyoshi Fukutomi, Youichi Shimizu, Masaki Sugo)")
[^37]
***
[War torn VERSNAG](https://www.youtube.com/watch?v=69RoPDQUbwg "Event 1 / Masasuke Kusanagi (TOYO Kusanagi), Ryu Umemoto")
[^38]
***
[Lam-Mal](https://www.youtube.com/watch?v=rNY9I8vUTKU&t=1913s "Ending / Ryu Takami, Hideaki Takeshita (BAKI)")
***
[Magical Block Carat](https://www.youtube.com/watch?v=HSw0CkMcuSY "Ending (Normal) / Yoshio Furukawa (JKL FURUKAWA)")
</td>
</tr>
<tr>
<td align="center" rowspan="2">OKI MSM6258</td><td align="center" rowspan="2">N/A</td><td align="center">

4-bit[^39]@3.9 / 5.2 / 7.8 / 10.4 / 15.6kHz ADPCM ×1 (Mono, with external panpot control, pitch adjustable in 5 fixed steps only, cannot be freely varied, and volume cannot be adjusted)</td>
</tr>
<tr>
<td align="center">PCM8 Driver<br>

ADPCM ×8[^40]<br>(Software Mixing)</td>
</tr>
<tr>
<td align="center" colspan="5">MIDI I/F</td>
</tr>
<tr>
<td align="center">Roland<br>MT-32</td><td align="center" colspan="2">LA ×32<br>

Polyphony: 8-32 voices (32 partials)[^41]<br>Multitimbral: 8 synth + 1 rhythm parts<br>(ch.2~9 & ch.10)<br>Preset: 128 synth + 30 rhythm<br>Effect: Reverb (4 types)</td><td align="center" rowspan="5">

[Gradius II](https://www.youtube.com/watch?v=9N0SvElItRs "Now Loading / Masahiro Ikariko, Hideto Inoue")
[^42]
***
[Akumajou Dracula](https://www.youtube.com/watch?v=2B8l-NFn-qc&t=1202s "Theme of Simon Belmondo / Hiroshi Kobayashi, Keizo Nakamura")
[^43]
***
[PHALANX](https://www.youtube.com/watch?v=OdY3mhtM_qY "Stage 5 / Kenichi Kamio")
[^44]
***
[Granada](https://www.youtube.com/watch?v=NGVM7LDvl7s&t=2415s "Advance \"GRANADA\" (Opening Theme) / Motoi Sakuraba")
[^45]
****
[Street Fighter II](https://www.nicovideo.jp/watch/sm1269845 "U.S.A. (Ken) I / Yoko Shimomura / arr. by 染之介 / CM-64 + SN-U110-07 (Electric Guitar PCM Card)")
[^46]
***
[STAR WARS](https://www.youtube.com/watch?v=8Wes4GiH2D4 "STAR WARS Part2 / John Williams / arr. by Shige / CM-64 + SN-U110-06 (Orchestral Winds PCM Card)")
[^47]
</td><td align="center" rowspan="5">

[Parodius Da!: Shinwa kara Owarai e](https://www.youtube.com/watch?v=1ELsijQTvGc&t=3404s "Let's Get Fever with Gunkan March (Stage 6) / Tokichi Setoguchi: Warship March / arr. by Kazuki Muraoka")
[^48]
***
[Metal Sight](https://www.youtube.com/watch?v=96h5UzfcHv8&t=4619s "Last Period (Opening) / Keishi Yonao, Izuru Aki")
[^49]
***
[Gemini Wing](https://www.youtube.com/watch?v=_9r4LHnBhNs "Round 2 BGM / Mikio Saito / programmed by Manabu Saito / CM-64 + SN-U110-10 (Rock Drums PCM Card)")
[^50]
***
[Sol-Feace](https://www.youtube.com/watch?v=ZtXMKHtwLKo&t=107s "MISSION 1：”Cosmic Illusion” / Motoi Sakuraba")
[^51]
***
[SOLDAM](https://www.youtube.com/watch?v=6sURduEaj3A "ENDING / Yasuyuki Suzuki, Atsuyoshi Isemura, Yasuhiko Takashiba / arr. by Warmbell / CM-64 + SN-U110-10 (Rock Drums PCM Card)")
</td>
</tr>
<tr>
<td align="center" rowspan="4">Roland<br>CM-64</td><td align="center" colspan="2">CM-32L</td>
</tr>
<tr>
<td align="center" colspan="2">LA ×32<br>Polyphony: 8-32 voices (32 partials)<br>Multitimbral: 8 synth + 1 rhythm parts<br>(ch.2~9 & ch.10)<br>Preset: 128 synth + 30 rhythm + 33 sound effect<br>Effect: Reverb (4 types)</td>
</tr>
<tr>
<td align="center" colspan="2">CM-32P</td>
</tr>
<tr>
<td align="center" colspan="2">RS-PCM ×31<br>Polyphony: 16-31 voices (31 partials)<br>Multitimbral: 6 synth parts<br>(ch.11~16)<br>Preset: 64 synth<br>Effect: Reverb (4 types)</td>
</tr>
<tr>
<td align="center" rowspan="6">Roland<br>GS / GM</td><td align="center" colspan="2">SC-55 / CM-300</td><td align="center" rowspan="6">

[Detana!! TwinBee](https://www.youtube.com/watch?v=iY9fTZ1GSsc "KONAMI MORNING MUSIC (LOADING DEMO) / composed by unknown / programmed by Masahiro Ikariko (IKAchan), Yuichi Takamine (Cyber Takamin), Kaori Kinouchi (KAORI-CHAN)")
[^52]
***
[Ghouls 'n Ghosts](https://www.youtube.com/watch?v=iwDjHa-JXbw&t=83 "2ND BGM / Tamayo Kawamoto / programmed by unknown")
[^53]
***
[OVERTAKE](https://www.youtube.com/watch?v=Uk5nJfYZkyc&t=94s "DEEPEST RED (OPENING 2) / ZOOM Sound Team (Hideyuki Shimono, Naoyuki Kimura)")
[^33]
***
[Super Real Mahjong PIV](https://www.youtube.com/watch?v=puro4m6saYM "Arcade Mode / Daisuke Morishima")
[^54]
***
[Asuka 120% Burning Fest.](https://www.youtube.com/watch?v=WOp6kggHvy8 "Epilogue / Keishi Yonao")
[^55]</td><td align="center" rowspan="6">[Cyber Block Metal Orange EX](https://kappa.vgmsite.com/soundtracks/metal-orange-ex-x68000-gamerip-1993/jmutnunmzn/05.mp3 "VISUAL 4 / Yoshio Furukawa (JKL FURUKAWA) / SC-55 Ver.")
[^56]
***
[Super Street Fighter II](https://www.youtube.com/watch?v=S4Cp9n4gUCw "Chun-Li's Theme / Yoko Shimomura / arr. by Syun Nishigaki (SYUN), Isao Abe (OYAJI) / programmed by Yoshinori Ono / SC-55")
[^57]
***
[Galaxy Express 999](https://www.youtube.com/watch?v=ejoP3dKq8TM "The Galaxy Express 999 / Godiego / programmed by ＮＡＭ ＆ ＨＭ米子")
[^58]
***
[SNATCHER](https://www.youtube.com/watch?v=x-BBziiRfaw "One Night in NEO KOBE CITY / Motoaki Furukawa / programmed by Kenichiro Fukui (Funiki Fukui) / SC-88 Ver. from album \"MIDI POWER ver.5.0\"")
***
[Salamander 2](https://www.youtube.com/watch?v=On446UZcIZo "Sensation / Naoki Maeda / programmed by Eisaku Nambu (Eisaku \"Bootsy\" Nambu) / SC-88Pro Ver. from album \"MIDI POWER Pro 5 ~SALAMANDER~\"")</td>
</tr>
<tr>
<td align="center" colspan="2">Polyphony: 24 voices<br>Multitimbral: 16 parts<br>(ch.1~16)<br>Preset: 315/317(GM Ver) instruments + 8 drum kits + 1 SFX kit + 1 MT-32 rhythm kit<br>Effect: Reverb (8 types) + Chrous (8types)</td>
</tr>
<tr>
<td align="center" colspan="2">SC-55mkII</td>
</tr>
<tr>
<td align="center" colspan="2">Polyphony: 28 voices<br>Multitimbral: 16 parts<br>(ch.1~16)<br>Preset: 354 instruments + 8 drum kits + 1 SFX kit + 1 MT-32 rhythm kit<br>Effect: Reverb (8 types) + Chrous (8types)</td>
</tr>
<tr>
<td align="center" colspan="2">CM-500</td>
</tr>
<tr>
<td align="center" colspan="2">

CM300 + CM-32L[^59] + Emulated CM-32P</td>
</tr>
</table>

## Chiptune Resource
### Online / Web Player
 - PlayMOD: https://www.wothke.ch/playmod/
 - Chip Player JS: https://chiptune.app/
 - Vampi's MDX collection: https://mdx.vampi.tech/
 - ProcrastinationLand's MIDI stuff: https://www.procrastinationland.com/music/
 - M3disp: https://m3.ym2413.com/
 - keygenmusic\.tk - tracker music player: https://keygenmusic.tk/
 - MOD/S3M/XM module player for Web Audio: https://cable.ayra.ch/modplayer/
 ###
 - VGMRips: https://vgmrips.net/packs/latest
 - Zophar's Domain: https://www.zophar.net/music
 - Kingdom Hearts Insider: https://downloads.khinsider.com/
 ###
 - MDXWin 雑なMXDRVエミュレータ: https://mdxonline.s3.us-west-2.amazonaws.com/MDXWin_ENG.html
 - MDXOnline: https://x.com/MDXOnlineAF
### Emulator
 - Munt: https://github.com/munt/munt
 - Nuked SC55: https://github.com/nukeykt/Nuked-SC55
 - MAME: https://github.com/mamedev/mame
### Hoot Archive
 - hoot... - Sound Hardware Emulator: http://dmpsoft.s17.xrea.com/hoot/
 - HootFavoritter: https://kurohane.net/seisanbutu.html
 - Vermouth Synthesizer: http://retropc.net/yui/hoot/
 - FAQ ~ Hoot Archive: http://snesmusic.org/hoot/v2/faq.php
 - czarek7711's collection: https://github.com/czarek7711/hoot
 - Hoot Archive 20240621: https://archive.org/details/hoot-archive-20240621
 - Knurek's collection https://hoot.joshw.info/
### Music Player
 - foobar2000: https://www.foobar2000.org/
   - HES input: https://foobar2000.xrea.jp/?Input#t3e2110a
   - FMP/PMD Music Objects Decoder: https://foobar2000.xrea.jp/?Input#cc29139f
   - S98 input: https://foobar2000.xrea.jp/?Input#re1ccf59
   - MDX / MDC input: https://foobar2000.xrea.jp/?Input#y1422c1c
   - VGM input: https://foobar2000.xrea.jp/?Input#m8ab66e7
   - MIDI Player: https://github.com/stuerp/foo_midi
 - MDPlayer: https://github.com/kuma4649/MDPlayer
 - FMPMD2000/WinFMP.dll/PMDWin.dll: http://c60.la.coocan.jp/download.html
 - FMP7: http://archive.fmp.jp/archives/448
   - FMDSP7: http://archive.fmp.jp/archives/30
   - exFMP4: http://archive.fmp.jp/archives/15
   - exPMD: http://archive.fmp.jp/archives/17
   - exMXDRV: http://archive.fmp.jp/archives/19
   - exS98P: http://archive.fmp.jp/archives/21
 - 98fmplayer: https://github.com/myon98/98fmplayer
 - MXDRV for Win32 [MXDRVg]: http://na01.shonan.ne.jp/~gorry/mx/
### Music Archive
 - xxx\.joshw.info Music Archive: https://vgm.hcs64.com/
 - VGMRips: https://vgmrips.net/packs/
 - Project 2612 - The Sega Genesis/Sega Mega Drive Music Archive: https://project2612.org/
   - Project 2612 Complete Archive (2021-07-12) [704 Sets]: https://archive.org/details/project-2612-complete-archive-2021-07-12-704-sets.-7z
 - Mirsoft\.info - World of Game Music: http://mirsoft.info/
   - mirsoftJuly2021snapshot: https://archive.org/details/mirsoftJuly2021snapshot
 - VGMusic - 31806 Game Music MIDI files: https://vgmusic.com/
   - 30000 Video Game MIDI Files: https://www.kaggle.com/datasets/hansespinosa2/40000-video-game-midi-files
 - Modland: https://ftp.modland.com/
 - jreina2002's collection: https://chiparchive.com/files/
###
 - 【雷門】 Kaminarimon HES Music Archive: http://kaminarimon.free.fr/hes/
 - SMT's MDX Collection v1.04 - Hyper Burst CE++: https://archive.org/details/smts-mdx-collection-v-1.04-hyper-burst-ce-2023-08-27-ultra.-7z
 - WARC: mdxoarchive\.webcrow.jp (2018-04-25): https://archive.org/details/mdxoarchive.webcrow.jp-20180425
 - X68000 MDX Master Library: https://archive.org/details/X68000MDXML
 - NFG Games - Directory Listing of /X68000/Music/: https://nfggames.com/X68000/index.php/Music/
 - NFG Games - Directory Listing of /PC98/Music/: https://nfggames.com/PC98/index.php/Music/
 - PC-98 Music Disks: FMP Music DIsk 1-9, some PMD disks, a lot of FMP/PMD files, and more: https://archive.org/details/c-77-fmp-fmp-music-disk-vol.-9-mdfmdsdcp
 - NEC PC-8801 Music Disks (2024-06-16): https://archive.org/details/PC88MusicDisks_20240616
 - .s98 OPN Soundtrack Archive: https://archive.org/details/opn-s98
 - FMP archive center: http://archive.fmp.jp/
 - Collections of MOD music from Japan: https://archive.org/details/jp-mod-music
 - Keygen Music Pack: https://archive.org/details/keygen-music
 - keygenmusic\.org full collection: https://archive.org/details/keygen-music-2020-03-pack
 - Sound Canvas MIDI collection: https://archive.org/details/sound_canvas_midi_collection



[^1]: CSM (Composite Sinusoidal Modeling) is a technique used in speech synthesis to break down complex sounds into simpler sine waves. By recombining these sine waves, we can recreate the original speech signal. Many Yamaha FM sound chips have a built-in feature called "CSM mode" that offers more precise control over the timing of sound generation, aiding in the accurate implementation of CSM speech synthesis. However, this mode is not strictly necessary for speech synthesis using CSM. By carefully managing the timing of sine wave generation yourself, you can achieve similar results without the dedicated CSM mode. In essence, the CSM mode is a tool that can assist in the process, but the core of CSM lies in the technique of breaking down and recombining sounds into sine waves.<br>
[OPMでCSM音声合成 - NRTDRV](https://nrtdrv.sakura.ne.jp/index.cgi?page=OPM%A4%C7CSM%B2%BB%C0%BC%B9%E7%C0%AE)<br>
[【MSX turboR】悲しみよこんにちは（めぞん一刻 OP）【音声合成】【Mu-PLAYER】改訂版](https://www.youtube.com/watch?v=KjLm2XVwlw8 "This video showcases a song played on an actual MSX computer. The audio synthesis is achieved by employing 9 channels of FM synthesis for the vocal component, while the melody and drums are handled using PCM samples. The total data used amounts to 254 KB for PCM samples and 91 KB for the music sequence data.
Channel Allocation:
Channels 1-3: PSG (unused in this sequence)
Channels 4-12: FM for vocal synthesis
Channels 13-20: PCM for 8-voice polyphony, providing the melody and drums
Music Transcription:
Transcribed by aro.
Hardware:
A1GT MSX computer.
Technical Details:
Vocal Synthesis: The vocal sounds were synthesized using sine waves, whose parameters were calculated based on Fourier transforms at 1/60 second intervals.
PCM: A sampling rate of 15.7 kHz was used for the PCM samples. To reduce data size, loop playback was implemented for the sampled data.
FM Synthesis: By fully utilizing the 9-voice polyphony of the FM synthesis, a rich and expressive vocal quality was achieved.")<br>
[PC-8801シリーズ　ゲームアーツの音声合成集](https://www.youtube.com/watch?v=bzyf4fjjjN0)
[^2]: SSG uses its built-in DAC to output analog signals directly, while FM uses an external DAC. These two require hardware mixing to combine, with different systems and sound modules using various mixing ratios. As a result, the volume balance between SSG and FM parts may vary when played on different devices. The later YMF288 and YMF297 chips omitted SSG's built-in DAC, using an external DAC for both FM and SSG parts. This fixed the volume ratio at 100% for FM and 25% for SSG, which cannot be adjusted.
[^3]: FM Channel 3 in the OPN soundchips has a special mode that allows frequencies to be set independently between the 4 operators, bringing the possibility of extended polyphony and other effects. This feature is officially known as Sound Effect Mode, but is also referred to as FM3ch Extend Mode (BambooTracker), Multi-Frequency Mode (ymfm), Ext. CH3 Mode (DefleMask), Extended Channel Mode (furnace), and 2CH Mode (YM2610).<br>
[FM3Extend - pedipanol's guide to MML](https://mml-guide.readthedocs.io/pmd/fm3extend/)<br>
[BambooTracker FM3ch拡張モードについて](https://maakmusic.hatenablog.com/entry/2020/03/01/160542)<br>
[PC-98 - "Sonorously Box" by Takeaki Watanabe - Oscilloscope View](https://www.youtube.com/watch?v=BDOSkD0Twos "This composition utilizes algorithm ALG 4, pairing OP1 with OP2 and OP3 with OP4. Each pair combines to generate a single voice, effectively doubling the polyphony of channel 3, which is visually represented in the video as FM3 and FM3Ex1 grids.")
[^4]: A [feature](https://mml-guide.readthedocs.io/pmd/ssgeg/ "SSG-EG - pedipanol's guide to MML") that allows the application of SSG (PSG) style hardware envelopes to FM sound sources, using SSG-type waveforms as the envelope's shape. This enables envelope variations that cannot be achieved with standard EG (Envelope Generator) parameters alone.<br>
[PPSSGEG (Sega Genesis, YM2612) [Original]](https://www.youtube.com/watch?v=hsPpDkWjOYQ)
[^5]: Samples are compressed to 4-bit ADPCM, with internal processing at 16-bit.
[^6]: The sampling rate for audio samples can range from 2kHz to 55.5kHz, with the YM2608 adjusting pitch by varying the sampling rate. However, with only 256kB of RAM available for storing samples, using higher sampling rates significantly increases sample size and limits the adjustable pitch range. In practice, samples are typically set to 8kHz or 16kHz, with 8kHz corresponding to a reference pitch of C4 (o4c) and 16kHz corresponding to G5 (o5g).
[^7]: Six ADPCM channels, fixed pitch, 18.5 kHz sampling rate at 12-bit from 4-bit data.
[^8]: One ADPCM channel, variable pitch, 2–55.5 kHz sampling rate at 16-bit from 4-bit data.
[^9]: [Near CD-quality music on Sega Mega-Drive? - Mega PCM 2](https://www.youtube.com/watch?v=4RZbvuL2m1c)<br>
[Genesis/Mega Drive voice examples](https://www.youtube.com/watch?v=KsMRe_QenvU)<br>
[A rundown on Genesis PCM/Sample quality](https://www.youtube.com/watch?v=2W4yTL-9gZE)<br>
[VGM Player YM2612 - PCM 44.1 kHz playback](https://www.youtube.com/watch?v=DkkqFxyVbDQ)
[^10]: [Nuked OPN2 Emulator. YM2612 / YM3438.](https://www.youtube.com/watch?v=PuK_Rjf20iE)<br>
[Earthworm Jim 2 Sound Test #0 Moonlight Sonata (real hardware, Mega Drive VA1 NTSC J, YM2612)](https://www.youtube.com/watch?v=V2he1ez_JKc)<br>
[SEGA Genesis Model 1 VS Model 2 (Ladder Effect Demo)](https://www.youtube.com/watch?v=zDSwjQo5MQM)
[^11]: The PCM sound source on the PC-9801-73 isn't fully compatible with the 86-PCM used by the PC-9801-86 due to differences in the initialization method. It also doesn't work with the WSS-PCM used by the PC-9801-118.
[^12]: While the YM2608 on the 86-Board technically supports ADPCM recording and playback, it lacks the necessary ADPCM RAM on the board, making the ADPCM feature unusable and incompatible with the Soundboard II and Speak-Board. To address this, the doujin group MAD Factory created an expansion board called Chibi-oto, which adds ADPCM RAM to the 86-Board. With this expansion, the 86-Board can play ADPCM just like the Soundboard II and Speak-Board.
[^13]: Relative volume of SSG when FM volume is set to 100%.
[^14]: PPZ's SSGPCM offers three sound modes. In mode 0, only one SSG channel is used, allowing the remaining SSG channels to play alongside PCM. However, the PCM resolution is limited to 4-bit, going through a conversion process from the original 4-bit ADPCM to 8-bit PCM, and then reduced back to 4-bit using a mapping table, which results in lower sound quality. Modes 1 and 2 utilize all three SSG channels, preventing SSG sound output but increasing PCM resolution to 8-bit—mode 1 operates at 8kHz, while mode 2 runs at 16kHz. Even with all three SSG channels, SSGPCM can only play a single channel of 8-bit/16kHz PCM. However, by using software mixing, PPZ combines the data from three PCM samples and outputs them together, allowing it to support up to three PCM channels.<br>
[FMP PPZ SSGPCM実機再生 (XT2.OZI) (YM2203 only)](https://www.youtube.com/watch?v=ZSwSkn0eq6A)
[^15]: FMP doesn't support the 8-channel PCM playback feature of the PPZ8.
[^16]: Decode the original ADPCM sample data to PCM and play it through the 86-PCM channel.
[^17]: Decode the ADPCM sample data that was originally played through the SSGPCM channel, and play it through the 86-PCM channel, which will result in significantly improved audio quality compared to the original SSGPCM playback.
[^18]: Two versions are available, each utilizing a different FM synthesizer. The speed-priority version employs fmgen with linear interpolation, while the quality-priority version uses ymfm with sinc interpolation.
[^19]: FMP7 utilizes fmgen as its FM synthesizer core. In addition to increasing the number of channels, it also enhances the following features:
    <ul>
    <li>OPNA<br>
    <ul>
    <li>Number of voices expanded from 6ch to 32ch</li>
    <li>Hardware LFO can be specified independently for all channels</li>
    <li>Frequency can be specified for each operator on all channels</li>
    <li>Independent volume management implemented</li>
    <li>Pan pot expanded from 3 levels to 128 levels</li>
    </ul>
    </li>
    <br>
    <li>OPM<br>
    <ul>
    <li>Number of voices expanded from 8ch to 32ch</li>
    <li>Hardware LFO can be specified independently for all channels</li>
    <li>Noise output possible on slot 4 of all channels</li>
    <li>Independent volume management implemented</li>
    <li>Pan pot expanded from 3 levels to 128 levels</li>
    </ul>
    </li>
    <br>
    <li>SSG<br>
    <ul>
    <li>Number of voices expanded from 3ch to 32ch</li>
    <li>Hardware envelope can be specified independently for all channels</li>
    <li>Independent noise frequency specification possible for all channels</li>
    <li>Independent volume management implemented</li>
    <li>128-level pan pot implemented</li>
    <li>Added "triangle wave", "pulse wave", and "sawtooth wave" to output waveforms</li>
    </ul>
    </li>
    <br>
    <li>PCM<br>
    <ul>
    <li>32 voice polyphony</li>
    <li>Software envelope can be specified independently for all channels</li>
    <li>Independent volume management implemented</li>
    <li>128-level pan pot implemented</li>
    <li>Loop playback supported</li>
    </ul>
    </li>
    </ul>

[^20]: SSG Drums are a built-in preset rhythm set in PMD, synthesized using the SSG. By default, they utilize the third SSG channel. When playing the SSG Drums part, enabling the `SSG + RHY` option in `PMDWin` on Windows or adding the `/N-` argument when running `PMD.COM` in MS-DOS on PC-98 systems, both the SSG Drums and the OPNA's built-in ADPCM Rhythm sound source (RSS) will play concurrently.
[^21]: While FMP's PPZ and MUAP's SSGPCM can expand SSG capabilities to support up to 3-channel, 8-bit PCM, the PMD-based PDR is limited to monophonic 4-bit PCM (with a maximum of 2 channels). This limitation stems from the author's decision to preserve the original SSG functionality and to minimize the performance impact on game compatibility, as PMD is commonly used as a game-embedded driver. Despite these constraints, the author has strived to optimize the sound quality achievable within the limitations of 4-bit PCM.
[^22]: [Strobe - "Citizens of Luala" (PC Engine) [Oscilloscope View]](https://www.youtube.com/watch?v=b36uE0WvJ0w)<br>
[ADPCM demo PC Engine / TurboGrafx](https://www.youtube.com/watch?v=jdWYOHPV6Uw)<br>
[firepro2 PC-Engine sound example](https://www.youtube.com/watch?v=V845pHyaePk)
[^23]: [THE BATTLE !   ‐警備員アルバイト・戦闘-](https://fi.zophar.net/soundfiles/turbografx-16-hes/zero4-champ/08%20BGM%20%2308.mp3)<br>
[【DQ・FFを】PCエンジン ゼロヨンチャンプ【神アレンジでパロディ】](https://www.nicovideo.jp/watch/sm327766)<br>
[PCエンジン版ゼロヨンチャンプとドラクエ・FFのBGMを聴き比べてみた【レトロゲーム雑学9】](https://www.youtube.com/shorts/c8-2S9kEbLA)<br>
[ゼロヨンチャンプ | レトロゲームの版権曲 Wiki | Fandom](https://outsidemusicinclassicgames.fandom.com/ja/wiki/%E3%82%BC%E3%83%AD%E3%83%A8%E3%83%B3%E3%83%81%E3%83%A3%E3%83%B3%E3%83%97)
[^24]: [PC Engine Hardware : PSG](http://www.magicengine.com/mkit/doc_hard_psg.html)<br>
[(PCE/TG16)はにいいんざすかい/Hany in the Sky-Soundtrack](https://www.youtube.com/watch?v=F83JI8npLik&t=1406s "The main melody in this video employs LFO mode, using channel 2 to modulate channel 1. In this mode, Channel 2 is muted, reducing the overall polyphony by one voice. However, this technique allows for an exaggerated vibrato effect on the main melody.")<br>
[In a Shallow Dream | はにいいんざすかい/Hany in the Sky [PC Engine] | Original Soundtrack](https://www.youtube.com/watch?v=FUAQ0Aue2no&t=79s "However, not all software emulators can accurately reproduce the LFO Mode of real hardware. For example, the LFO Mode in this video is played incorrectly.")
[^25]: Samples are compressed to 4-bit ADPCM, which decompresses to 12-bit PCM, but only the top 10 bits are output through the built-in DAC.
[^26]: [Xeno Crisis - Perimeter (Arranged)](https://www.youtube.com/watch?v=sgbFYarpLhs)<br>
[Sonic the Hedgehog - Green Hill Zone (YM2612 Rearranged)](https://www.youtube.com/watch?v=QGEDcfIbPwM)<br>
[StarCraft - Terran 3 (YM2612 Cover)](https://www.youtube.com/watch?v=5NBqicMz5Zc)
[^27]: [Chris Hülsbeck - "Intro" (Mega Turrican, Sega Genesis) [Oscilloscope Visualization]](https://www.youtube.com/watch?v=FYz6AL9sLCQ)<br>
[Toy Story's Hardware Defying Music - How We Did It](https://www.youtube.com/watch?v=x3m3JrVImmU)<br>
[Toy Story (Genesis) - Strange Things - Oscilloscope Deconstruction](https://www.youtube.com/watch?v=gL9__8TCd88)<br>
[Dual PCM - FlexEd](https://www.youtube.com/watch?v=hP45A0pTVLQ)
[^28]: [The Sound Capabilities of the Sega Genesis](https://www.youtube.com/watch?v=IGy7HBG3I1c&t=13s)
[^29]: [Playing samples on the PSG](https://www.smspower.org/Development/SN76489#PlayingSamplesOnThePSG)<br>
[Unusual Sound Playback Method](https://tcrf.net/After_Burner_II_(Genesis)#Unusual_Sound_Playback_Method)<br>
[After Burner II (Mega Drive/Genesis) - After Burner (Oscilloscope view)](https://www.youtube.com/watch?v=unazqYjSzaM "The Sega Mega Drive/Genesis version of After Burner II utilizes PSGPCM for sampled drum sounds, which is visually represented in the video as SN76489 PSG1 grid. However, the orchestra hit on this channel is noticeably out-of-tune, a direct result of inaccuracies in the software emulator's simulation of PSGPCM.")<br>
[Recorded from Sega Genesis, Model 2 VA 2.3 w/discrete YM2612 + line out mods + MegaAmp via Tascam US-1x2 @ 24bit/96KHz](https://www.youtube.com/watch?v=3XTsB_pKa-s&t=774s "This recording was captured on authentic hardware, so you won't hear the out-of-tune issues with the orchestra hits that occur when using emulators.")
[^30]: [創刊10周年記念PRO-68K SIONⅡ \~THE FIRST ATTACK\~](http://gyusyabu.ddo.jp/MP3/1992/SION2.html)
[^31]: [KONAMI ORIGINAL GAME SOFTWARE 生中継68](http://gyusyabu.ddo.jp/MP3/1991/NAMA1.html)
[^32]: The first x68k game to use ADPCM drum kit samples.<br>[namco オリジナル･ゲーム･シリーズ ボスコニアン](http://gyusyabu.ddo.jp/MP3/1988/BOS1.html)
[^33]: [Challenge The Limit OVERTAKE（オーバーテイク）](http://gyusyabu.ddo.jp/MP3/1992/OT55.html)
[^34]: [Illumination Laser found?](https://nfggames.com/forum2/index.php?topic=5340.0)<br>
[AY OTOME](http://www.critical.ne.jp/~kaze/)<br>
[篠田信久(Nobuhisa Shinoda) (@ickaze) / X](https://x.com/ickaze)
[^35]: [CYBER BLOCK メタルオレンジEX](http://gyusyabu.ddo.jp/MP3/1993/META68.html)<br>
[METAL ORANGE STAGE1BGM](https://www.youtube.com/watch?v=1ro_d-cqC7k "arr. by the original composer")
[^36]: [ぶたさん・くえすと](https://web.archive.org/web/19991013194439/http://cclub.cc.tut.ac.jp/%7Emikami/fsw/butaq.html)<br>
The composer is also the author of the MCDRV sound driver for x68k.<br>
[CUL. CAN (かる缶) ](http://www.culcan.net/support.php)<br>
[Kyuukyoku Senki Gikadiver - Sharp X68000 OST (Full Soundtrack) (1996)](https://www.youtube.com/watch?v=Oy_Otc-Fm3s&t=344s "Ｋ･Ｙ･Ａ･Ｈ･Ｈ･Ｏ･Ｕ (Boss)")
[^37]: [DRAGONKNIGHT IS THRILLING SLG. ドラゴンナイト４](http://gyusyabu.ddo.jp/MP3/1994/DK4.html)
[^38]: [Fantasy Roleplaying Game ヴェルスナーグ戦乱](http://gyusyabu.ddo.jp/MP3/1993/VERS1.html)
[^39]: Samples are compressed to 4-bit ADPCM, which decompresses to 12-bit PCM, but only the top 10 bits are output through the built-in DAC.
[^40]: PCM8.X uses software mixing to expand the number of ADPCM channels to 8 and extends PDX format (EX-PDX) support to both 8-bit and 16-bit linear PCM (EX-PCM mode), with the ability to adjust sample volume. The subsequent PCM8A.X further added the pitch adjustment capabilities from MPCM.X.<br>
[X68000 MDX FM音源 THE SQUARE［TRUTH］より「TRUTH」](https://www.youtube.com/watch?v=UyG8u4UudvA)<br>
[X68030 PCM8.x と PCM8SB.x 比較](https://www.youtube.com/watch?v=dag6A-4TrEQ)
[^41]: Voices are created from up to 4 partials which can be combined in various ways (including ring modulation). With 32 partials available overall, polyphony depends on the tonal complexity of the music, and 8 to 32 notes can be played simultaneously.
[^42]: [ゲームフリーク待望のシューティングゲームの最高傑作。 グラディウスⅡ ⎯ GOFERの野望 ⎯](http://gyusyabu.ddo.jp/MP3/1992/GRA2.html)
[^43]: [KONAMI ORIGINAL GAME SOFTWARE 悪魔城ドラキュラ](http://gyusyabu.ddo.jp/MP3/1993/AKU55.html)
[^44]: [THE ENFORCE FIGHTER A-144 PHALANX（ファランクス）](http://gyusyabu.ddo.jp/MP3/1991/PHALA1.html)
[^45]: [MANEUVER CEPTER グラナダ](http://gyusyabu.ddo.jp/MP3/1990/GRANA1.html)<br>
[Advance "GRANADA" (Opening Theme) - Granada (Sharp X68000, MT-32 emulated)](https://www.youtube.com/watch?v=XM9Xk0IuBYg "The feature here is, that you can see instruments used to play the sound effects on channel 9.")
[^46]: Known as "染之介" (Somenosuke) online, the arranger produced his compositions on an X68000 using RC-System and STed2. He is celebrated for his mastery of MIDI techniques in crafting electrifying electric guitar compositions.<br>
[B'z - Alone (CM64 + SN-U110-07) cover (c) 染之介](https://www.youtube.com/watch?v=7t9aIbKFHKE)<br>
To correctly playback RCP format MIDI files with CM6 control data on Windows, as seen in this video, the specialized software player [Miyap2002](https://www.vector.co.jp/soft/win95/art/se236400.html) is necessary. While the widely used [TMIDI Player](https://blackmidi.fandom.com/wiki/Software:TMIDI_Player) cannot transmit CM6 sysex data, Miyap2002 can. Additionally, since 2018, newer versions of [MDPlayer](https://github.com/kuma4649/MDPlayer) have also acquired the ability to transmit CM6/GSD files.
[^47]: This video was uploaded by the author of [MAmidiMEmo](https://github.com/110-kenichi/mame).<br>
[DANGUN FEVERON - SOUL SUPERMARKET / N.Misawa - YM2414 + YM2608 \*REAL CHIP\* Ver. by Cadon](https://www.youtube.com/watch?v=mbsEIKtRiHA)<br>
`.RCP` is the file format used by the MIDI sequencing software "Recomposer" Ver.2.0 to Ver.2.5. `.CM6` is a sysex file used alongside .RCP, controlling sound modules like the CM-64 or MT-32.<br>
[A Recomposer file (.RCP, .R36, .G36, and .MCP) to Standard MIDI File (.mid) converter](https://shingo45endo.github.io/rcm2smf/)
[^48]: [KONAMI ORIGINAL GAME SOFTWARE パロディウスだ！ ⎯ 神話からお笑いへ ⎯](http://gyusyabu.ddo.jp/MP3/1991/PARO1.html)
[^49]: [超弩級3Dシューティングゲーム メタルサイト](http://gyusyabu.ddo.jp/MP3/1989/MS1.html)
[^50]: [アドレナリン全開シューティング ジェミニウイング](http://gyusyabu.ddo.jp/MP3/1990/GEM1.html)<br>
[Gemini Wing Soundtrack · Sharp X68000 CM-64 SN-U110-10 Rock Drums](https://www.youtube.com/watch?v=5OFTSEsPKbA)
[^51]: [疾駆する宇宙､X68000オリジナル｡シューティング･ドリーム発進! ソル・フィース](http://gyusyabu.ddo.jp/MP3/1990/SOLF1.html)<br>
[Sol-Feace (YM2151 / MT-32 / CM-64) | Sharp X68000 Full Soundtrack OST](https://www.youtube.com/watch?v=ClWzfO0aR0o&t=4567s "(CM-64 ver.)")
[^52]: [KONAMI ORIGINAL GAME SOFTWARE 出たな!!ツインビー](http://gyusyabu.ddo.jp/MP3/1991/DTTW55.html)<br>
[【MIDI X68000】Detana!! TwinBee | 出たな!! ツインビー ~ BGM ~ MT-32 ver. // MiSTer FPGA // MT32-pi MT32](https://www.youtube.com/watch?v=c346cZnghyI&t=1142s "Loading (MT-32 ver.)")
[^53]: [Tim Follin - "Ghouls 'n' Ghosts (C64)" Soundtrack [Oscilloscope View]](https://www.youtube.com/watch?v=wz36JWHTk-A&t=498s)<br>
[Tim Follin - “Ghouls 'n' Ghosts (Amiga) - Main Theme” [Oscilloscope View]](https://www.youtube.com/watch?v=4JS6pHeTcLg "Tim Follin adapted the Stage 2 BGM into a new Main Theme for the Amiga version.")<br>
[(PCE/TG16)大魔界村/Ghouls'n Ghosts-Soundtrack](https://www.youtube.com/watch?v=1hz_s8rAKA4 "reprogrammed by Toshiaki Takimoto (Takimoto), Keita Hoshi (Hoshi)")
[^54]: [Super Real Mahjong PIV Theme - Sega Saturn](https://www.youtube.com/watch?v=lfcHArsBQ9o)
[^55]: [対戦格闘アクションゲーム あすか120% BURNING Fest.](http://gyusyabu.ddo.jp/MP3/1994/AS.html)<br>
[Asuka 120% BURNING Fest. (YM2151 / SC-55 / TG-100) | Sharp X68000 Full Soundtrack OST](https://www.youtube.com/watch?v=0Nw77aQ1crE&t=3566s "(TG-100 ver.)")
[^56]: [X68000「メタルオレンジEX」(SC-55 ver) / METAL ORANGE EX](https://www.youtube.com/watch?v=Xt_9rSo6Lys&t=684s)<br>
[VGM Hall of Fame: Cyberblock Metal Orange EX - Visual 4 (X68000)](https://www.youtube.com/watch?v=eAZ3mvXaRec "Built-in FM Ver.")
[^57]: [高感度移植!美技を極めろ!!" スーパーストリートファイターⅡ ⎯ The New Challengers ⎯](http://gyusyabu.ddo.jp/MP3/1994/SSF2.html)
[^58]: [【MIDI再生】ゴダイゴ／銀河鉄道９９９　　THE GALAXY EXPRESS 999](https://www.youtube.com/watch?v=eNqcYEUVotE)
[^59]: [CM-500 Faster Vibrato Issue](https://www.youtube.com/watch?v=OLvsaJ4h-VY&t=9536s)<br>
[Fixing the Roland CM-500 Vibrato Bug](https://www.vogons.org/viewtopic.php?f=62&p=1042409)
