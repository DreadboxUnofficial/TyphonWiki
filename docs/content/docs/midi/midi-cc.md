---
title: "Midi Cc"
date: 2020-11-11T22:16:55-08:00
---

# MIDI CC List

This is the list of MIDI CC, as of firmware v2.0.2. All are CC, so far there aren't any NRPN.


CC# | Function | Notes
----|----------|-------
0 |  BANK SELECT | Added in 2.0.2. Set this CC first to pick the bank (1=A, 2=B, 3=C, 4=D), then send a MIDI program change to select a preset
1 |  MOD WHEEL |
2 |  CC2 | Assignable in CC2 Target Menu: CV.0, CV1.0, CV2.0, WAVE.0, CUT.0, RES.0, EGL.0, VCA.0, FX1.0, FFM.0, FX2.0, DLAY.0 or FX3.0
3 |  RESONANCE |
4 |  CUTOFF |
5 |  WAVESHAPE |
6 |  OSC2 OFFSET |
7 |  GLIDE |
8 |  VCO LEVEL |
9 |  FILTER TRACKING |
... |      | 
11 |  FILTER FM |
12 |  FX1 HP CUTOFF |
13 |  FX1 HP RESONANCE |
14 |  FX1 PARAMETER 1 |
15 |  FX1 PARAMETER 2 |
16 |  FX1 MIX |
17 |  FX2 PARAMETER 1 |
18 |  FX2 PARAMETER 2 |
19 |  FX2 PARAMETER 3 |
20 |  FX2 FEED |
21 |  FX2 MIX |
22 |  FX3 PARAMETER 1 |
23 |  FX3 PARAMETER 2 |
24 |  FX3 FEED |
25 |  FX3 PARAMETER 4 |
26 |  FX3 MIX |
27 |  FILTER EG ATTACK |
28 |  FILTER EG DECAY |
29 |  FILTER EG SUSTAIN |
30 |  FILTER EG RELEASE |
31 |  FILTER EG TIME |
32 |     | (Reserved - some synths send this after CC#0 during a program change)
33 |  FILTER EG LEVEL |
34 |  VCA EG ATTACK |
35 |  VCA EG DECAY |
36 |  VCA EG SUSTAIN |
37 |  VCA EG RELEASE |
38 |  VCA EG TIME |
39 |  VCA EG LVL |
40 |  M1 PARAMETER 1 |
41 |  M1 PARAMETER 2 |
42 |  M1 PARAMETER 3 |
43 |  M1 CV LEVEL |
44 |  M1 CV1 LEVEL |
45 |  M1 CV2 LEVEL |
46 |  M1 WAVE LEVEL |
47 |  M1 CUTOFF LEVEL |
48 |  M1 RESONANCE LEVEL |
49 |  M1 EG LEVEL LEVEL |
50 |  M1 VCA LEVEL |
51 |  M1 FX1 LEVEL |
52 |  M1 FFM LEVEL |
53 |  M1 FX2 LEVEL |
54 |  M1 DELAY TIME LEVEL |
55 |  M1 FX3 LEVEL |
56 |  M2 PARAMETER 1 |
57 |  M2 PARAMETER 2 |
58 |  M2 PARAMETER 3 |
59 |  M2 CV LEVEL |
60 |  M2 CV1 LEVEL |
61 |  M2 CV2 LEVEL |
62 |  M2 WAVE LEVEL |
63 |  M2 CUTOFF LEVEL |
64 |  M2 RESONANCE LEVEL |
65 |  M2 EG LEVEL LEVEL |
66 |  M2 VCA LEVEL |
67 |  M2 FX1 LEVEL |
68 |  M2 FFM LEVEL |
69 |  M2 FX2 LEVEL |
70 |  M2 DELAY TIME LEVEL |
71 |  M2 FX3 LEVEL |
72 |  M3 PARAMETER 1 |
73 |  M3 PARAMETER 2 |
74 |  M3 PARAMETER 3 |
75 |  M3 CV LEVEL |
76 |  M3 CV1 LEVEL |
77 |  M3 CV2 LEVEL |
78 |  M3 WAVE LEVEL |
79 |  M3 CUTOFF LEVEL |
80 |  M3 RESONANCE LEVEL |
81 |  M3 EG LEVEL LEVEL |
82 |  M3 VCA LEVEL |
83 |  M3 FX1 LEVEL |
84 |  M3 FFM LEVEL |
85 |  M3 FX2 LEVEL |
86 |  M3 DELAY TIME LEVEL |
87 |  M3 FX3 LEVEL |
88 |  SEQ LENGTH |
89 |  SEQ DIVISION |
90 |  SEQ PROBABILITY |
91 |  SEQ SWING |



## Reference Docs


- The firmware update ZIP files (latest: [TYPHON-Firmware-Update-V2.0.2.zip](https://www.dreadbox-fx.com/wp-content/uploads/2020/12/TYPHON-Firmware-Update-V2.0.2.zip) ) have a PDF with detailed release notes. It includes the changes to MIDI CC in each version.
