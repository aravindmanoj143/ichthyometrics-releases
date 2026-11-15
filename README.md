# IchthyoMetrics

**Free desktop software for fish morphometrics and meristics.** Measure fish from
calibrated photographs and record meristic counts, then export ready-to-analyse data
for MorphoJ, PAST, R (geomorph) and Excel.

IchthyoMetrics is made for ichthyologists, fish taxonomists, fisheries biologists and
students who measure specimens for species descriptions, taxonomic revisions and
morphometric studies. It runs on Windows and macOS, works fully offline, and keeps your
photos and data on your own computer.

**Free for academic and non-commercial use.**
(c) 2026 Aravind Manoj | Freshwaters India Foundation. See [LICENSE.txt](LICENSE.txt).

## Download

Get the latest version from **[Releases](../../releases/latest)**:

| System | File | Install |
|---|---|---|
| Windows 10 / 11 | `IchthyoMetrics_<version>_x64-setup.exe` (or `.msi`) | Run it. If SmartScreen warns, choose *More info -> Run anyway*. |
| macOS 11+ (Apple Silicon and Intel) | `IchthyoMetrics_<version>_universal.dmg` | Open it, accept the licence, drag IchthyoMetrics to Applications. First start: right-click the app -> *Open*. |

## What it does

### Morphometrics (landmarks and measurements)

- **Import photos** of fish specimens (JPEG, PNG, TIFF), one photo per specimen.
- **Set the scale** by clicking two points on a ruler in the photo, so every distance is in millimetres.
- **Place landmarks** in a fixed order, with a picture guide showing where each landmark goes.
  Zoom, pan and a magnifier help with precise placement.
- **Truss-network and traditional measurements** are calculated automatically from the landmarks:
  standard length (SL), head length, body depth, eye diameter, fin bases and more.
- **Ratio tables** (for example % SL and % head length) with mean, SD, minimum and maximum.
- **Size correction** of measurements (Elliott et al. 1995 allometric method).
- **Left- and right-side photos** are both supported. Right-side specimens are mirrored in coordinate exports.

### Meristics (counts)

- Record **fin-ray counts, lateral-line scales, transverse scale rows, predorsal scales,
  gill rakers, vertebrae, cephalic pores** and other counts for each specimen.
- Type counts in, or **count by clicking** marks on one or more pictures (fins, scales, head pores).
- "Not countable" is recorded as missing, never as 0.
- Summary tables of counts per species: n, mode, range, mean and frequency distribution.

### Built-in templates

Landmark schemes (editable JSON, so you can make your own):

- General fish truss: 10 landmarks (Strauss & Bookstein 1982 style)
- Goby truss: 14 landmarks
- Cichlid / perch truss: 14 landmarks
- Cypriniformes lateral and dorsal views (Armbruster 2012)
- Traditional measurements after Hubbs & Lagler (1964)

Count templates:

- Standard fish counts (Hubbs & Lagler 1964)
- Cypriniformes counts (Armbruster 2012)
- Goby fin and scale counts
- Goby cephalic lateral-line pores and sensory papillae
- Cichlid / perch counts

### Exports

| Format | For |
|---|---|
| TPS | tpsDig2, tpsRelw, MorphoJ |
| Tab-separated file (mm) | PAST |
| TPS + classifiers + ready R script | R / geomorph |
| Excel workbook (.xlsx) | Excel, LibreOffice |
| CSV tables | landmarks, measurements, ratios, size-corrected data, counts |
| project.json | full backup of the project |

Every export folder includes a README that explains the coordinate system and units.

## Who it is for

- Taxonomists writing species descriptions and redescriptions
- Morphometric studies of fish populations, stocks and sexual dimorphism
- Geometric morphometrics using landmark data
- Teaching ichthyology and fish biology practicals

## Licence

- Free for research, teaching, students and other non-commercial use.
- Commercial use requires written permission.
- Unmodified installers may be shared free of charge for non-commercial use, with the licence.
- No modification or reverse engineering. No warranty.

Full terms: [LICENSE.txt](LICENSE.txt). Open-source components: [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt).

## How to cite

If you use IchthyoMetrics in published work, please cite:

> Manoj, A. (2026). *IchthyoMetrics: software for fish morphometrics and meristics* (version x.y.z). Freshwaters India Foundation. https://github.com/aravindmanoj143/ichthyometrics-releases

## Contact

Developed by [Aravind Manoj](https://www.instagram.com/aravind_manoj/) - aravindrevanth@gmail.com
[Freshwaters India Foundation](https://fwif.org/)

Bug reports and feature requests: open an [issue](../../issues).

*Keywords: fish morphometrics software, meristics, ichthyology, truss network, landmarks,
geometric morphometrics, fish taxonomy, fish measurement, fisheries, TPS, MorphoJ, PAST, geomorph.*
