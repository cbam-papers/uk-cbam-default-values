# UK CBAM default values

HMRC's default values for the UK Carbon Border Adjustment Mechanism (CBAM), as one machine-readable table: one row per CN code, with its sector, description and default value in tonnes of CO2e per tonne of product. GOV.UK publishes them as five separate sector tables; this is the same data in one file.

- 570 CN codes: iron and steel (478), aluminium (58), fertiliser (27), cement (6) and hydrogen (1)
- From GOV.UK's "Check the default values for CBAM" (16 October 2026), parsed and checked on 8 November 2026

Maintained by [CBAM Papers](https://cbampapers.co.uk), a free check of whether UK CBAM applies to your imports and roughly what it costs. Search the values by code or description at [cbampapers.co.uk/cbam-default-values](https://cbampapers.co.uk/cbam-default-values).

## Files

- `uk-cbam-default-values.csv`: one row per CN code
- `uk-cbam-default-values.json`: the same rows as JSON

| Column | Meaning |
|---|---|
| `cn_code` | The 8-digit Combined Nomenclature code |
| `sector` | Iron and steel, Aluminium, Cement, Fertiliser or Hydrogen |
| `description` | The goods, as GOV.UK describes them |
| `default_value_tco2e_per_tonne` | The default value, in tonnes of CO2e per tonne of product |
| `source_url` | GOV.UK's default values page |
| `details` | The search page on CBAM Papers |

## Things to know

- UK CBAM starts on 1 January 2027. Default values can be used on a CBAM return instead of verified emissions data from the producer, and apply whatever the country of origin.
- HMRC can update the values. Check GOV.UK before relying on a row.
- This is not tax advice.

## Corrections

If a value differs from GOV.UK, open an issue with the code.

## Licence

The values are HMRC's, published under the [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/). Contains public sector information licensed under the Open Government Licence v3.0. This compilation is [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): you can reuse it, including commercially, if you credit CBAM Papers with a link to https://cbampapers.co.uk.
