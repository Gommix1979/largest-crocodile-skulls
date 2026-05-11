# Largest Crocodile Skulls

An open citizen-science database of the world's biggest crocodilian skulls, with measurements consolidated from published sources and verified collections.

## Live site

[https://gommix1979.github.io/largest-crocodile-skulls/](https://gommix1979.github.io/largest-crocodile-skulls/)

## Why this exists

Many of the largest crocodiles ever recorded are known only from their skulls. A skull's dorsal cranial length (DCL) and maximum head width (MHW) can be used to estimate the size of the live animal it came from. This database consolidates measurements published in the scientific literature, museum records, and verified private collections, with full provenance for every entry.

The data is intentionally open: researchers, museum curators, hobbyists and anyone with an interest in crocodilian morphometrics is welcome to use, cite, fork, or contribute.

## What's in the data

A CSV / JSON file with the standard crocodile-skull measurements per specimen:

| Column | Meaning |
|---|---|
| ID | Database row number |
| Species | Scientific name |
| Common Name | Plain-English name |
| Specimen Name | Individual name (Lolong, Edgar, etc.) where known |
| Origin | Where the animal came from |
| Current Location | Where the skull is held now |
| DCL_A_Curve_mm | Dorsal Cranial Length following the curve |
| DCL_B_Straight_mm | DCL straight-line measurement |
| MHW_mm | Maximum Head Width |
| MCW_mm | Maximum Cranial Width (between squamosals) |
| IOW_mm | Inter-Orbital Width |
| TL_cm | Live-animal Total Length |
| TL_estimated | Y if TL was estimated rather than measured |
| Mandible_cm | Length of the lower jaw |
| Weight_kg | Animal weight if known |
| Teeth_Num | Teeth count if recorded |
| Notes | Free-text context |
| Source | Citation |

## Notable specimens

- **Longest skull on record**: a *Tomistoma schlegelii* (False Gharial) at the British Museum, 840 mm DCL.
- **Widest skull on record**: *Edgar*, a *Crocodylus porosus* at the Lee Kong Chian Natural History Museum in Singapore, 520 mm MHW (Fukuda et al. 2018).
- **Best-documented giant saltwater crocodile**: *Lolong*, the Philippines specimen with 700 mm DCL and 617 cm measured total length (Britton et al. 2012).

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for the full guide. The short version:

1. Fork this repo
2. Add your specimen to `data.csv`
3. Submit a pull request with a clear source citation
4. We review and merge

Every specimen must have a verifiable source. Anecdotes and unverified claims won't be merged.

## Citation

If you use this data in research or publication, please cite as:

> *Largest Crocodile Skulls: an open citizen-science database*. Available at: https://gommix1979.github.io/largest-crocodile-skulls/

And cite the original sources for individual records (Whitaker & Whitaker 2008, Fukuda et al. 2018, etc.) where applicable.

## Original sources

- Whitaker, R. and Whitaker, N. (2008). Who's got the biggest? *Crocodile Specialist Group Newsletter* 27(4): 26-30.
- Fukuda, Y., How, C.B., Seah, B., Yang, S., Pocklington, K. and Lim, K.P. (2018). Historical, exceptionally large skulls of saltwater crocodiles discovered at the Lee Kong Chian Natural History Museum in Singapore. *Raffles Bulletin of Zoology* 66: 810-813.
- Britton, A.R.C., Whitaker, R. and Whitaker, N. (2012). Here be a dragon: exceptional size in a saltwater crocodile from the Philippines. *Herpetological Review* 43(4): 541-546.
- Webb, G.J.W. and Messel, H. (1978). Morphometric analysis of *Crocodylus porosus* from the north coast of Arnhem Land. *Australian Journal of Zoology* 26: 1-27.
- Manolis, C. (2006). Record of a large saltwater crocodile from the Northern Territory, Australia. *Crocodile Specialist Group Newsletter* 25(3): 27-28.

## Licence

Data and content released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You're free to use, share, and adapt the data with attribution.

Code and HTML viewer released under MIT licence.

## Maintainer

This is a hobby project. Contributions, corrections, and suggestions are welcome via Issues or Pull Requests.
