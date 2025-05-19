# IMPRO: Industrial Heat Demand Profile Generator

**IMPRO** (Industrial Heat Demand Profile Generator) is an Excel‑based tool for generating multi‑temperature, hourly industrial heat load profiles. It enables energy system modelers and researchers to:

* Capture sector‑specific seasonal and diurnal variations in process heat demand
* Disaggregate total heat demand across customizable temperature levels (e.g., low‑temperature hot water to high‑temperature steam)
* Estimate excess heat availability for heat recovery and sector‑coupling analyses
* Quickly use built‑in presets for seven major industry sectors or create fully custom profiles

---

## Key Features

* **Cluster Blend**: Represents seasonal variations by combining multiple outdoor temperature‑sensitivity clusters.
* **Temperature Level Distributions**: Splits total demand into user‑defined temperature levels to reflect different process heat requirements.
* **Hourly Resolution**: Applies standardized shift‑based load profiles to convert daily demand into realistic hourly curves.
* **Standard Presets**: Includes ready‑to‑use profiles for seven sectors—Iron & Steel, Basic Chemicals, Non‑Metallic Minerals, Pulp & Paper, Food & Beverages & Tobacco, Machinery & Transport, and Non‑Ferrous Metals—so you can generate a profile with just an outdoor temperature time series and annual demand.
* **Excess Heat Module**: Allows specification of a fixed fraction of heat demand as recoverable excess heat at lower temperature levels.

---

## Getting Started

1. **Download** the latest release from this repository.
2. **Open** `IMPRO.xlsx` in Microsoft Excel (version 2016 or later).
3. **Select** a preset industry sector or choose “Custom” to define your own cluster blend, temperature distribution, and shift profiles.
4. **Import** an hourly outdoor temperature time series or choose one of the included profiles.
5. **Scale** the normalized output to match your desired annual heat demand.
6. **Export** the generated daily or hourly profiles (and excess heat series) for use in energy system models.

For detailed usage instructions and examples, refer to the **Information** worksheet included in the Excel file.

---

## Publication - not yet published

(Holmes, T., Kauko, H., & Backe, S. (2025). *IMPRO – An Industrial Heat Demand Profile Tool: Multi‑Temperature Load Profile Generation for Industrial Heat Demand Modelling*. **MethodsX**.
🔗 [View the full article (Elsevier)](ENTER LINK HERE))

---

## License

This project is released under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

IMPRO builds on:

* Mateo Jesper, Felix Pag, Klaus Vajen, Ulrike Jordan,*Annual Industrial and Commercial Heat Load Profiles: Modeling Based on k-Means Clustering and Regression Analysis*, Energy Conversion and Management: X, Volume 10, 2021, 100085, ISSN 2590-1745, https://doi.org/10.1016/j.ecmx.2021.100085.
* Rehfeldt, M., Fleiter, T. & Toro, F. *A bottom-up estimation of the heating and cooling demand in European industry.* Energy Efficiency 11, 1057–1082 (2018), https://doi.org/10.1007/s12053-017-9571-y
* Fabian Bühler, Stefan Petrović, Fridolin Müller Holm, Kenneth Karlsson, Brian Elmegaard, *Spatiotemporal and economic analysis of industrial excess heat as a resource for district heating*, Energy, Volume 151, 2018, Pages 715-728, ISSN 0360-5442, https://doi.org/10.1016/j.energy.2018.03.059


