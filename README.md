# Apollo VIEW recovery

An open research project to recover the original Apollo-era VIEW visualization program: its FORTRAN source, operating documentation, dependencies, star and terrain data, and development history.

**Recovery status:** original VIEW source code has not yet been located. The initial release provides archival research findings and a searchable, source-linked title-page dataset to guide that search. A modern reconstruction, if developed later, must be identified separately from recovered historical code.

## Start here

- [Research findings](view_research_findings.md): verified technical anchors, people, historical context, and unresolved connections.
- [Top 50 archival candidates](top_50_view_candidates.md): ranked leads with evidence classes and original image links.
- [Potential archival requests](potential_archival_requests.md): priorities after excluding verified public copies.
- [Verified public full text](verified_public_full_text.md): existing reports to consult before requesting scans.
- [Software documentation leads](software_documentation.md): related manuals and program descriptions; a lead does not establish VIEW ancestry.
- [Recovery roadmap](RECOVERY-ROADMAP.md): missing materials, next indexes to investigate, and evidence standards.

## Initial archival dataset

OCR transcriptions of every title-page image inventoried under the [public ibiblio archive](https://www.ibiblio.org/apollo/NARASWoverflow/TitlePageScans/). Each transcription links directly to its original public image.

**Coverage:** 3,014 images in 220 historical box directories, plus the archive root. This repository transcribes the title-page scans; it does not claim to transcribe the full reports behind those title pages.

**Quality:** all transcriptions and proposed metadata require review. Selected metadata fields were checked on 56 records; that is not certification of the remaining fields. Images 969 and 1155 remain incomplete transcriptions. The 2,927 grouped work identities are provisional. No original VIEW source code was recovered.

## Browse by collection

| Collection | Source pages | Index |
|---|---:|---|
| E156N | 1 | [Browse](INDEX-E156N.md) |
| E157G | 935 | [Browse](INDEX-E157G.md) |
| E158 | 51 | [Browse](INDEX-E158.md) |
| E209 | 254 | [Browse](INDEX-E209.md) |
| E209A | 55 | [Browse](INDEX-E209A.md) |
| E209B | 302 | [Browse](INDEX-E209B.md) |
| E209D | 40 | [Browse](INDEX-E209D.md) |
| E209H | 1376 | [Browse](INDEX-E209H.md) |

## Machine-readable data

- [transcriptions.jsonl](transcriptions.jsonl): one record per source image, containing exact selected OCR text, source URL, source-image hash, transcription hash, identifiers, proposed metadata, and open review notes.
- [source_index.csv](source_index.csv): compact index joining every image to its public source and the corresponding Markdown transcription.
- [manifest.json](manifest.json): checksums and byte counts of the published files.
- [validation.json](validation.json): coverage, source-URL, text-hash and link checks.

The JSONL text is the authoritative exact selected transcription; Markdown adds display formatting. Independent OCR variants and the preserved source images remain in the complete local archival catalog. This GitHub snapshot contains the selected transcriptions and source correlations.

## Provenance and interpretation

Source inventory and OCR were completed on 17 October 2026 UTC using local Windows OCR and Tesseract.js. Raw OCR is kept separate from proposed titles and other normalized fields. Missing reliable metadata is null in JSONL and blank in CSV. Source-image SHA-256 values refer to the original downloaded public images, not to the transcription files.

Historical box names reproduce the website directory labels. They are not verified current NARA shelf locations; the [archive creator describes subsequent reboxing](https://www.ibiblio.org/apollo/QuestForInfo.html).

## Corrections

For a correction, identify the image ID and original source URL, quote the visible wording, and distinguish a transcription correction from an inferred or externally sourced metadata change. Preserve the source URL and the original OCR when recording corrections.

## Rights and attribution

The source images are hosted by ibiblio in its Apollo documentation collection. Linking or transcribing a publicly accessible document does not establish a new license for its underlying contents. Original notices and third-party rights, where applicable, remain with the source material. No blanket public-domain claim is made for the complete collection.
