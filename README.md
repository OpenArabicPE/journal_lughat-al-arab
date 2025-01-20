---
title: "Readme: Journal *Lughat al-ʿArab*"
author: Till Grallert
date: 2022-02-04
ORCID: orcid.org/0000-0002-5739-8094
---

[![DOI](https://zenodo.org/badge/171823864.svg)](https://zenodo.org/badge/latestdoi/171823864)
[![GitHub release](https://img.shields.io/github/release/openarabicpe/journal_lughat-al-arab.svg)](https://github.com/openarabicpe/journal_lughat-al-arab/releases)
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Maintenance](https://img.shields.io/badge/maintained%3F-yes-green.svg)](https://github.com/openarabicpe/journal_lughat-al-arab/graphs/commit-activity)
![Commit activity](https://img.shields.io/github/commit-activity/m/openarabicpe/journal_lughat-al-arab)
![GitHub commits since latest release (by date)](https://img.shields.io/github/commits-since/openarabicpe/journal_lughat-al-arab/latest)
![GitHub last commit](https://img.shields.io/github/last-commit/openarabicpe/journal_lughat-al-arab)
![GitHub contributors](https://img.shields.io/github/contributors/openarabicpe/journal_lughat-al-arab)

# An open, collaborative, and scholarly digital edition of Anastās Mārī al-Karmalī's monthly journal *Lughat al-ʿArab* (Baghdad, 1911--)

If you just want to browse the edition in a more human-readable view, start [here](https://openarabicpe.github.io/journal_lughat-al-arab/tei/oclc_472450345-i_1.TEIP5.xml). All bibliographic metadata is available as part of [OpenArabicPE's public Zotero group](https://www.zotero.org/groups/904125/openarabicpe/items/).

This digital edition of Anastās Mārī al-Karmalī's monthly journal *Lughat al-ʿArab* (Baghdad, 1911--) is part of and follows the principles of [Open Arabic Periodical Editions (OpenArabicPE)](https://openarabicpe.github.io) that were originally developped in the context of [Digital Muqtabas](https://github.com/openarabicpe/journal_al-muqtabas). The full text of this edition has been transcribed by the anonymous transcribers at [*al-maktaba al-shamela*](http://shamela.ws/index.php/book/36540). 

Note that I focus on the first three volumes (34 issues) published before WWI. Publication dates for later volumes have not been corrected. Their bibliographic data will appear at faulty positions in the Zotero group if sorted by date.

Digital imagery is available from [*arshīf al-majallāt ...*](http://archive.alsharekh.org/newmagazineYears/14) and

- Hathitrust:
    - [Princeton (vol. 1)](https://hdl.handle.net/2027/njp.32101011506357), reprint 1971
    - Michigan:
        + [vol. 1](https://hdl.handle.net/2027/mdp.39015009032320), reprint 1970
        + [vol. 2](https://hdl.handle.net/2027/mdp.39015020088392), reprint 1970
    - Indiana University (8 vol.s, search only)
    - [University of California](https://catalog.hathitrust.org/Record/010305806) (9 vol.s, search only)

It appeared that the page breaks from *al-maktaba al-shamela* correspond to the printed copy. We have therefore added the relevant mark-up for page beginnings (`<pb ed="print" n="123"/>`) and an `<facsimile>` element containing links to the digital facsimiles at [*arshīf al-majallāt*](http://archive.alsharekh.org/). The boilerplate view, therefore, displays both facsimiles and the digital text. We have added publication dates for the first three volumes based on the physical copies at the Orient-Institut Beirut's library.


# mark-up of sections
## to do

- Jakob Koppermann began validating the mark-up of articles in sections
- تاريخ وقائع العراق وما جاوره
- [x] تاريخ وقائع الشهر في العراق وما جاوره
- [x] باب المشارفة والانتقاد
- [ ] باب المكاتبة والمطارحة

## general notes

- Sections in articles are usually numbered and the digit is wrapped in a `<hi>` element. Mark-up can be automated
- Articles in sections frequently commence with an inline-header, wrapped in brackets. Mark-up can be automated but will need some validation.
-