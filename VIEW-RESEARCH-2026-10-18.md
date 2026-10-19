# VIEW naming and additional archival records

Research checked 18 October 2026, America/Denver. This supplement adds evidence to the initial catalog; the finalized SQLite, exports, and original release remain unchanged. Original VIEW source code has not been recovered.

## Naming: descriptions are not automatically aliases

| Wording | Evidence | Interpretation |
|---|---|---|
| VIEW; view program; lunar-mission view-program | [NASA TN D-6853 / MSC-S-323](https://ntrs.nasa.gov/citations/19720017950), printed pp. 2-3 and appendix p. 12 | Verified contemporary naming and descriptive variants. Capitalization alone does not identify a separate program. |
| Major analytical tool | [69-FM-197 Revision 1](https://www.ibiblio.org/apollo/Documents/19740073250.pdf), introduction | Credits G. B. Roush, Computation and Analysis Division; does not supply a second formal program name. |
| Computer window view program | [Apollo 13 GNC paper, NTRS 20090026451](https://ntrs.nasa.gov/citations/20090026451), printed/PDF p. 19, reference 28 on p. 42 | Strong descriptive match: Apollo 13 burn-attitude window/AOT predictions, with figures attributed to Lunde's 70-FM-90. The paper does not explicitly equate the phrase with the name VIEW. |
| Star plotter program | [NTRS 19700025041](https://ntrs.nasa.gov/citations/19700025041), Appendix B, PDF p. 53 | Related Roush/Gemini software; possible ancestry or shared routines. Identity with VIEW remains unproven. |

The last description is a substantial new lead. The July 9, 1968 report, MSC-EG-68-08 / NASA-TM-X-64343, attributes a Gemini star plotter to Bernie Roush in Flight Mechanics Application. For AOT data reduction, it was adapted to accept Smithsonian Astrophysical Observatory catalog tapes, with magnitude limits +6, +8, and +14; the report describes completeness through +8. Inputs include field-center coordinates, angular diameter, magnitude cutoff, and an optional star-count limit. Outputs include star lists and 4020 plots. Appendix B and its two example figures were visually checked. This identifies a data/routine search route, not VIEW's exact star catalogs.

## Eight specific document targets from the JSC index

The [JSC Document Index, NTRS 19900007273](https://ntrs.nasa.gov/citations/19900007273) was downloaded and searched as a 450-page PDF. Relevant rows on PDF pages 31, 67, 79, 111, 132, 142, and 152 were visually verified. Titles below are shortened descriptions. Dates are index dates; the reports themselves have not been retrieved here.

| MSC/JSC number | Internal note | Date | Subject | Index printed page |
|---|---|---|---|---:|
| 02500 | 70-FM-090 / 70-FM-90 | 1970-05-15 | Apollo 13 return views | 29 |
| 03935 | 71-FM-041 | 1971-01-27 | Apollo 14 pilot/camera window views | 65 |
| 04313 | **71-FM-186** | 1971-05-17 | Apollo 15 spacecraft views; A. N. Lunde | 77 |
| 05811 | 72-FM-057 | 1972-02-29 | Apollo 16 spacecraft views | 109 |
| 07068 | 72-FM-163 | 1972-06-29 | Skylab wardroom-window simulation views | 130 |
| 07351 | 72-FM-219 | 1972-09-18 | Apollo 17 spacecraft views | 140 |
| 07634 | 72-FM-290 | 1972-12-06 | Apollo 17 UV-spectrometer views | 150 |
| 07635 | 72-FM-291 | 1972-12-06 | Apollo 17 T+24-hour views | 150 |

OCR misreads **71-FM-186** as 71-FM-188 and **07634** as 07834. The page images resolve both. Seven identifiers have no exact identifier match in the initial title-page JSONL; this is not proof that no damaged or differently indexed reference exists there. The Skylab entry establishes a relevant report, but not reuse of VIEW under a new name.

## Two existing catalog records deserve higher research priority

- **70-FM-90 / MSC-02500**, image 774, [public cover](https://www.ibiblio.org/apollo/NARASWoverflow/TitlePageScans/E157G-50/E157G-50_003.tif.png). Its OCR title begins `VIE-ws`, and the original score was only 5. The Apollo 13 paper cited above attributes its window-view figures to this report and names A. N. Lunde in reference 28. This is a strong output/reconstruction target. Reproduced figures in a later paper do not constitute recovery of the original report or code.
- **68-FM-294**, images 299 and 1391, [public cover](https://www.ibiblio.org/apollo/NARASWoverflow/TitlePageScans/E157G-26/E157G-26_003.tif.png). This Apollo 8 celestial-sphere maneuver-attitude report also scored only 5. Its date and subject warrant much higher priority. [Heritage's direct catalog record](https://historical.ha.com/itm/space-exploration/flight-reports/apollo-8-training-used-apollo-8-maneuver-attitudes-relative-to-the-celestial-sphere-book/a/6115-40094.s) describes a 118-page Lovell training copy. That is evidence of a surviving artifact, not a public complete scan or source listing.

These are research-priority corrections to the initial ranking, not silent changes to raw OCR or the finalized master.

## Where software records might be filed

[NASA TN D-6855 / MSC-S-326](https://ntrs.nasa.gov/citations/19720017573), printed pp. 3-4 and 7-8, describes mission-specific RTACF operational support plans, flight annexes, work plans, databases, and ACR setup handbooks. It also describes an Apollo Reference Mission Program, trajectory ephemeris tapes, a 200-Word Record interface, and FASTRAND storage. These are concrete record-series and interface search terms. The report does not name VIEW or establish that its integrator was VIEW's integrator.

The [2019 interview with Bernie Roush](https://www.click2houston.com/apollo/2019/07/24/meet-computer-programmer-who-created-software-to-help-astronauts-see-out-of-spacecraft-window/) supplies a first-person account of Apollo window-view software and emergency support. It gives no formal alternate program name; use it for people/history leads, and use technical reports for program architecture. Search both Bernie Roush and G. B. Roush; the article also inconsistently spells the surname Rousch.

The [Purdue Armstrong papers record](https://archives.lib.purdue.edu/repositories/2/archival_objects/38305) places the 1968 AOT evaluation in MSA 5, Box 65, Folder 11. Public NASA full text is already available, so this copy is useful for provenance or annotations rather than paying to reproduce an accessible report.

## Names to keep separate

- **RAVFAC / thermal VIEW:** [NASA-TM-X-70538](https://ntrs.nasa.gov/citations/19740005525) describes Goddard's IBM System/360 thermal view-factor software. It is a different program, despite a promising-looking VIEW user-manual title.
- **EIG:** [NASA TN D-7112 / MSC-S-346](https://ntrs.nasa.gov/citations/19730011149), printed pp. 20-21 / PDF pp. 28-29, describes an electronic image generator for Gemini and LM training. This passage does not mention VIEW or establish a code relationship. The claim that VIEW originated specifically in the Gemini part-task trainer remains unverified; D-6853 supports the broader Gemini rendezvous/docking ancestry.
- **VIEW-1108:** [the modern project's own page](https://aaronsb.github.io/view1108/) explicitly identifies its FORTRAN as reconstruction. Its name and routines are not evidence of historical NASA naming or recovered code.
- TRW lunar perspective plotting, ORACLE-MAFIA, OBSIM, NAVSIM, and GLSAEG remain separate or adjacent leads unless a source establishes an actual relationship.

## Next retrieval priorities

1. Locate the Roush Gemini star-plotter description/listing, AOT reduction modifications, SAO tape layout, and 4020 interface documentation through Computation and Analysis / Flight Mechanics records.
2. Retrieve 70-FM-90 and 68-FM-294; compare acknowledgments, references, plot legends, and input conventions with the known VIEW report.
3. Follow 71-FM-186 through the Apollo 16/17 reports, then test the Skylab continuation hypothesis using 72-FM-163.
4. Search RTACF flight annexes and ACR setup documentation for VIEW, window-view, star-plotter, Roush, Lunde, and program/library identifiers.

All are retrieval priorities, not assertions of exclusive archival availability. No inquiry was sent to an archive or individual. Downloaded evidence and SHA-256 metadata are preserved locally under `catalog/research/view_names_2026-10-18/`; PDFs remain linked at public sources rather than bundled in this repository supplement.
