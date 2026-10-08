# Dating subscription cancellation rules in Switzerland (2026)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23036874.svg)](https://doi.org/10.5281/zenodo.23036874)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

How do you cancel a paid dating subscription in Switzerland, and how much notice do you need to give? This dataset compares the cancellation rules of 18 online dating platforms available in Switzerland, collected from official sources only.

- **Full study with charts:** https://www.webandreview.com/dating/cancellation-study-2026/
- **Archived version (DOI):** https://doi.org/10.5281/zenodo.23036874
- **Report (PDF):** [`report/webandreview-dating-cancellation-study-2026-v1.pdf`](report/webandreview-dating-cancellation-study-2026-v1.pdf)
- **Data (CSV):** [`data/cancellation-study-2026.csv`](data/cancellation-study-2026.csv)

## Platforms

be2, eDarling, Academic Singles, Zusammen.ch, Verliebt ab 40, 60plusTreff, Aktiv & Verliebt, 50plus Singlebörse, C-Date, Parship, ElitePartner, LoveScout24, Zweisam, 50plus-Treff, LemonSwan, Tinder, Bumble, Hinge.

## Key figures

- **Notice period:** 28 days for 8 platforms, 14 days for 1, none (cancel any time before renewal) for 6, not stated as a number for 3.
- **Shown at checkout:** the notice period was visible during the order process for 8 of 18 platforms. For the other 10, checkout was not observed and the public terms are the source.
- **Cancellation channels:** online cancellation is possible on all 18 platforms. 8 offer a cancellation form that works without logging in.
- **Deleting your profile is not cancelling:** on the 8 platforms operated by be2 S.à r.l., closing the profile does not end the paid subscription.
- **App purchases:** 11 platforms have an app in the Swiss App Store. Subscriptions bought in an app are cancelled in the Apple or Google account, not on the website.

## Columns

| Column | Description |
|---|---|
| `platform` | Platform name |
| `segment` | Type of platform (serious dating, casual dating, swipe app, 40/50/60 plus, graduates…) |
| `operator` | Company operating the platform |
| `operator_country` | Country of the operator (ISO code) |
| `notice_period` | Notice period as written in the official sources |
| `notice_days` | Notice period in days (empty when not stated as a number) |
| `shown_at_checkout` | Whether the notice period is shown during the order process |
| `how_to_cancel` | Accepted cancellation channels |
| `app_in_switzerland` | App available in the Swiss App Store (yes/no) |
| `source_date` | Date the data was collected (YYYY-MM-DD) |
| `sources` | Official source URLs, separated by ` \| ` |

## Method

Data collected between 20 and 29 September 2026 from official sources only: terms of service, imprint and help pages, cancellation forms and the Swiss App Store. For the eight platforms operated by be2 S.à r.l., the order process was followed with a test profile up to the payment step, without purchase and without contacting members. Comparison sites, forums and review platforms were not used.

**Limitations:** checkout pages were observed for 8 of 18 platforms. Terms change over time, so every value carries its collection date. Test profiles were female.

**Disclosure:** Webandreview earns affiliate commissions from some of the platforms covered, including be2 group brands. Platforms did not see or approve the study.

## Citation

> Bernard, S. (2026). *How to cancel a dating subscription in Switzerland: 18 platforms compared (2026)* (Version 1.0) [Data set]. Webandreview. https://doi.org/10.5281/zenodo.23036874

Please cite the DOI above rather than this repository. GitHub's "Cite this repository" button uses the same reference.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You can reuse, share and adapt the data, including commercially, as long as you credit the source with the citation above.

## Author

Sacha Bernard, independent publisher (Webandreview, Belgium) · ORCID [0009-0008-1350-0334](https://orcid.org/0009-0008-1350-0334) · https://www.webandreview.com/sacha-bernard/

Next update planned for March 2027, as a new version of the same Zenodo record.
