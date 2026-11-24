# Dog breed lifespan figures from four open-access studies

**Site: [dog-breed-data.at01.io](https://dog-breed-data.at01.io/)** · Download: [latest release](https://github.com/JasonTKG/dog-breed-data/releases/latest)

Lifespan figures by dog breed from four open-access studies, one row per study and breed, with the figures exactly as each paper's table prints them. The breed pages of Dog Breed Data show these rows beside kennel-club figures.

## Files

| File | Rows |
|---|---|
| `lifespan_by_breed.csv` | 210 |

## Columns

**`lifespan_by_breed.csv`**

- `study`: short citation
- `doi`: DOI link of the paper
- `table`: table of the paper the row was read from
- `country`: where the dogs lived
- `breed_as_published`: breed name as the study prints it
- `akc_breed_name`: the American Kennel Club breed name this row is shown under on the site; blank where the row is not attached to a breed page
- `measure`: what the figure is
- `value`: the figure, unchanged
- `unit`: years or months, as published
- `low`: lower bound; blank where the study gives none
- `high`: upper bound; blank where the study gives none
- `interval`: what low and high are
- `dogs`: dogs in the group, where the table gives it
- `deaths`: deaths in the group, where the table gives it

## Sources

| Source | URL | Terms | Retrieved |
|---|---|---|---|
| McMillan KM, Bielby J, Williams CL, Upjohn MM, Casey RA, Christley RM. Longevity of companion dog breeds: those at risk from early death. Scientific Reports 14, 531 (2024) | https://doi.org/10.1038/s41598-023-50458-w | CC BY 4.0 | 2026-11-24 |
| Teng KT, Brodbelt DC, Pegram C, Church DB, O’Neill DG. Life tables of annual life expectancy and mortality for companion dogs in the United Kingdom. Scientific Reports 12, 6415 (2022) | https://doi.org/10.1038/s41598-022-10341-6 | CC BY 4.0 | 2026-11-24 |
| Lewis TW, Wiles BM, Llewellyn-Zaidi AM, Evans KM, O’Neill DG. Longevity and mortality in Kennel Club registered dog breeds in the UK in 2014. Canine Genetics and Epidemiology 5, 10 (2018) | https://doi.org/10.1186/s40575-018-0066-8 | CC BY 4.0 | 2026-11-24 |
| Urfer SR, Kaeberlein M, Promislow DEL, Creevy KE. Lifespan of companion dogs seen in three independent primary care veterinary clinics in the United States. Canine Medicine and Genetics 7, 7 (2020) | https://doi.org/10.1186/s40575-020-00086-8 | CC BY 4.0 | 2026-11-24 |

## How it was checked

Each table was read by program from the paper's open-access full text or supplementary file (Europe PMC, PMC open data). A second program re-reads the saved copies and compares every figure on the site with them before each release. Matching a study's breed name to an AKC breed name is the site's own work: names that differ only in case, accents, word order or the word "dog" are joined by rule, the rest by hand, and the site's About page lists the hand joins.

## Left out

The site also prints figures read from the American Kennel Club's breed pages, The Royal Kennel Club's breed standards and the FCI breeds nomenclature. Those sources publish no open licence, so their figures are not in this dataset; only AKC breed names appear, as the key the rows are shown under.

## Licence

The figures come from articles published under the Creative Commons Attribution 4.0 International licence; cite the paper named in each row. This compilation is offered under the same licence (see `LICENSE`).

## Maintainer

Built and maintained by [JasonTKG](https://github.com/JasonTKG); corrections and questions: open an issue.

Exported 2026-11-24 from the data the site's pages are generated from.
