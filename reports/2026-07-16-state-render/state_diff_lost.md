# State Diff: Lost Flags and Removed Entries

Generated: 2026-07-16

Comparison: current working tree against `HEAD` in `xcube-cci-registry`.
`write_geojson` is normalized to `write_kml` before comparing flags.

## Summary

| Data type | Removed entries | Entries with lost flags |
| --- | ---: | ---: |
| `dataset` | 0 | 6 |
| `datatree` | 0 | 0 |
| `geodataframe` | 0 | 2 |
| `vectordatacube` | 0 | 1 |

## Removed State Entries

None.

## Lost Flags

### dataset

#### Lost `constrain_region` (3)

- `esacci.SOILMOISTURE.day.L3S.SSMS.multi-sensor.multi-platform.ACTIVE.05-2.r1`
  - old: `open, constrain_time, constrain_region, write_zarr`
  - new: `open, constrain_time, write_zarr`
- `esacci.SOILMOISTURE.day.L3S.SSMV.multi-sensor.multi-platform.COMBINED.05-2.r1`
  - old: `open, constrain_time, constrain_region, write_zarr`
  - new: `open, constrain_time, write_zarr`
- `esacci.SOILMOISTURE.day.L3S.SSMV.multi-sensor.multi-platform.PASSIVE.05-2.r1`
  - old: `open, constrain_time, constrain_region, write_zarr`
  - new: `open, constrain_time, write_zarr`

#### Lost `constrain_time` (1)

- `esacci.OZONE.mon.L3.LP.SCIAMACHY.Envisat.SCIAMACHY_ENVISAT.v0001.r1`
  - old: `open, constrain_time, constrain_region, write_zarr`
  - new: `open, constrain_region, write_zarr`

#### Lost `open, constrain_time, constrain_region, write_zarr` (1)

- `esacci.SNOW.day.L3C.SCFV.AVHRR.NOAA-8.AVHRR_NOAA8.3-0.r1`
  - old: `open, constrain_time, constrain_region, write_zarr`
  - new: `(none)`

#### Lost `write_zarr` (1)

- `esacci.AEROSOL.mon.L3C.AER_PRODUCTS.multi-sensor.multi-platform.AATSR-ENVISAT-ENS_MONTHLY.v2-6.r1`
  - old: `open, constrain_time, constrain_region, write_zarr`
  - new: `open, constrain_time, constrain_region`

### geodataframe

#### Lost `constrain_region` (2)

- `esacci.AEROSOL.satellite-orbit-frequency.L2P.AER_PRODUCTS.AATSR.Envisat.ORAC.04-01.r1`
  - old: `open, constrain_time, constrain_region, write_kml`
  - new: `open, constrain_time, write_kml`
- `esacci.AEROSOL.satellite-orbit-frequency.L2P.AER_PRODUCTS.ATSR-2.ERS-2.ORAC.04-01.r1`
  - old: `open, constrain_time, constrain_region, write_kml`
  - new: `open, constrain_time, write_kml`

### vectordatacube

#### Lost `open` (1)

- `esacci.SEALEVEL.mon.IND.MSLTR.multi-sensor.multi-platform.MERGED.2-2.SE_ASIA`
  - old: `open`
  - new: `(none)`
