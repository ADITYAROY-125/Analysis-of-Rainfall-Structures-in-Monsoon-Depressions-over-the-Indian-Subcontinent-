# Analysis of Convective and Stratiform Rainfall Structures in Monsoon Depressions over the Indian Subcontinent (2014–2024)

This repository provides a comprehensive analysis of convective and stratiform rainfall associated with monsoon depressions over the Indian subcontinent from 2014 to 2024. The study leverages high-resolution GPM IMERG satellite data, supported by ERA5, GPM DPR, MEERA, and IMD rain gauge datasets for validation and supplementary analysis.

## Project Overview

- **Domain:** Indian subcontinent (5°N–35°N, 65°E–100°E), focusing on the monsoon season (JJAS).
- **Main Goals:**
  - Differentiate convective and stratiform rainfall in monsoon depressions.
  - Analyze spatial, radial, and azimuthal rainfall structures.
  - Assess annual and decadal trends in rainfall associated with monsoon depressions.
  - Validate satellite-based results with ground and reanalysis data.

## Datasets and Download Links

| Dataset           | Description & Resolution                          | Download/Access Instructions                                                                 |
|-------------------|---------------------------------------------------|---------------------------------------------------------------------------------------------|
| **GPM IMERG**     | Daily & half-hourly, 0.1° grid                    | Register at [NASA Earthdata](https://urs.earthdata.nasa.gov/users/new). Search and download from [GPM IMERG Daily](https://search.earthdata.nasa.gov/search?q=GPM_3IMERGDF.v07) or [GPM IMERG Half-Hourly](https://search.earthdata.nasa.gov/search?q=GPM_3IMERGHH_07). See [IMERG Data Guide](https://gpm.nasa.gov/data/imerg) for details.[1][12][13] |
| **ERA5**          | Hourly, 0.25° grid                                | Register at [Copernicus CDS](https://cds.climate.copernicus.eu/). Download from [ERA5 Single Levels](https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels). See [ERA5 Download Guide](https://github.com/preritaagarwal/How_to_download_ERA5_data/blob/master/ERA5_Steps.md) for step-by-step instructions.[2][3][9] |
| **GPM DPR**       | 0.5°, 1.5-hourly (Gridded Convective/Stratiform)  | Access via [GES DISC GPM DPR](https://disc.gsfc.nasa.gov/datasets/GPM_3GCSH_07/summary) or [Earthdata Search](https://search.earthdata.nasa.gov/search?q=GPM_3GCSH_07).[4][5] |
| **MEERA**         | 0.5°–1°, 3-hourly                                 | Download from [NASA GES DISC](https://disc.gsfc.nasa.gov/datasets/MEERA/summary) (requires Earthdata login). |
| **IMD Gridded Rainfall** | 0.25°, daily (1901–2024)                   | Go to [IMD Pune Grid Data](https://imdpune.gov.in/cmpg/Griddata/Rainfall_25_NetCDF.html) and select the required years. See [YouTube Tutorial](https://www.youtube.com/watch?v=t8qLj4MVn_c) for step-by-step guidance.[6][11] |
| **IMD Rain Gauge**| Station data, daily                               | Use the [imd-data-downloader tool](https://github.com/Iftiazur/imd-data-downloader) or request directly from IMD.[7] |

## How to Use

1. **Clone this repository** and review the analysis notebooks and scripts.
2. **Download the required datasets** using the links and instructions above.
3. **Follow the workflow** in the notebooks to reproduce the analysis or adapt it for your research needs.

## Citation

If you use this code or analysis, please cite the relevant data providers and this repository.

---

*For questions or contributions, please open an issue or pull request.*
