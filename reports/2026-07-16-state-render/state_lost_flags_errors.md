# Lost Flags: Error Groups

Generated: 2026-07-16

Result source: `/home/tonio/projects/esa-cci/work/results`.

## Summary

- Entries with lost flags: 9
- Error groups: 6
- Missing result JSONs: 0

## Error Group Summary

| Type | Check | Message | Count |
| --- | --- | --- | ---: |
| `ValueError` | `constrain_region` | cannot reshape array of size 1036800 into shape (1,2,2) | 3 |
| `ValueError` | `constrain_region` | All arrays must be of the same length | 2 |
| `CheckTimeoutError` | `constrain_time` | Time out after 120 seconds. | 1 |
| `KeyError` | `write_zarr` | 'AOD550' | 1 |
| `OpendapTimeoutError` | `(top-level)` | Error 500: Cannot access url 'https://data.cci.ceda.ac.uk/thredds/dodsC/esacci/snow/data/scfv/AVHRR_SINGLE/v3.0/AVHRR_NOAA8/1983/09/19830920-ESACCI-L3C_SNOW-SCFV-AVHRR_NOAA8-fv3.0.nc.dds' | 1 |
| `ValueError` | `(top-level)` | conflicting sizes for dimension 'nbmonth': length 216 on 'nbmonth' and length 215 on {'nbpoints': 'distance_to_coast', 'nbmonth': 'sla'} | 1 |

## Groups

### ValueError / constrain_region

Message: cannot reshape array of size 1036800 into shape (1,2,2)

#### dataset (3)

- `esacci.SOILMOISTURE.day.L3S.SSMS.multi-sensor.multi-platform.ACTIVE.05-2.r1`
  - lost: `constrain_region`
  - old: `open, constrain_time, constrain_region, write_zarr`
  - new: `open, constrain_time, write_zarr`
  - result: `work/results/dataset/esacci.SOILMOISTURE.day.L3S.SSMS.multi-sensor.multi-platform.ACTIVE.05-2.r1--0f86744a787f.json`
- `esacci.SOILMOISTURE.day.L3S.SSMV.multi-sensor.multi-platform.COMBINED.05-2.r1`
  - lost: `constrain_region`
  - old: `open, constrain_time, constrain_region, write_zarr`
  - new: `open, constrain_time, write_zarr`
  - result: `work/results/dataset/esacci.SOILMOISTURE.day.L3S.SSMV.multi-sensor.multi-platform.COMBINED.05-2.r1--2455672d558d.json`
- `esacci.SOILMOISTURE.day.L3S.SSMV.multi-sensor.multi-platform.PASSIVE.05-2.r1`
  - lost: `constrain_region`
  - old: `open, constrain_time, constrain_region, write_zarr`
  - new: `open, constrain_time, write_zarr`
  - result: `work/results/dataset/esacci.SOILMOISTURE.day.L3S.SSMV.multi-sensor.multi-platform.PASSIVE.05-2.r1--74cec84686e2.json`

### ValueError / constrain_region

Message: All arrays must be of the same length

#### geodataframe (2)

- `esacci.AEROSOL.satellite-orbit-frequency.L2P.AER_PRODUCTS.AATSR.Envisat.ORAC.04-01.r1`
  - lost: `constrain_region`
  - old: `open, constrain_time, constrain_region, write_kml`
  - new: `open, constrain_time, write_kml`
  - result: `work/results/geodataframe/esacci.AEROSOL.satellite-orbit-frequency.L2P.AER_PRODUCTS.AATSR.Envisat.ORAC.04-01.r1--c26372130eb1.json`
- `esacci.AEROSOL.satellite-orbit-frequency.L2P.AER_PRODUCTS.ATSR-2.ERS-2.ORAC.04-01.r1`
  - lost: `constrain_region`
  - old: `open, constrain_time, constrain_region, write_kml`
  - new: `open, constrain_time, write_kml`
  - result: `work/results/geodataframe/esacci.AEROSOL.satellite-orbit-frequency.L2P.AER_PRODUCTS.ATSR-2.ERS-2.ORAC.04-01.r1--68f1efa6e601.json`

### CheckTimeoutError / constrain_time

Message: Time out after 120 seconds.

#### dataset (1)

- `esacci.OZONE.mon.L3.LP.SCIAMACHY.Envisat.SCIAMACHY_ENVISAT.v0001.r1`
  - lost: `constrain_time`
  - old: `open, constrain_time, constrain_region, write_zarr`
  - new: `open, constrain_region, write_zarr`
  - result: `work/results/dataset/esacci.OZONE.mon.L3.LP.SCIAMACHY.Envisat.SCIAMACHY_ENVISAT.v0001.r1--b066bf198c84.json`

### KeyError / write_zarr

Message: 'AOD550'

#### dataset (1)

- `esacci.AEROSOL.mon.L3C.AER_PRODUCTS.multi-sensor.multi-platform.AATSR-ENVISAT-ENS_MONTHLY.v2-6.r1`
  - lost: `write_zarr`
  - old: `open, constrain_time, constrain_region, write_zarr`
  - new: `open, constrain_time, constrain_region`
  - result: `work/results/dataset/esacci.AEROSOL.mon.L3C.AER_PRODUCTS.multi-sensor.multi-platform.AATSR-ENVISAT-ENS_MONTHLY.v2-6.r1--a086f11d13f8.json`

### OpendapTimeoutError / (top-level)

Message: Error 500: Cannot access url 'https://data.cci.ceda.ac.uk/thredds/dodsC/esacci/snow/data/scfv/AVHRR_SINGLE/v3.0/AVHRR_NOAA8/1983/09/19830920-ESACCI-L3C_SNOW-SCFV-AVHRR_NOAA8-fv3.0.nc.dds'

#### dataset (1)

- `esacci.SNOW.day.L3C.SCFV.AVHRR.NOAA-8.AVHRR_NOAA8.3-0.r1`
  - lost: `open, constrain_time, constrain_region, write_zarr`
  - old: `open, constrain_time, constrain_region, write_zarr`
  - new: `(none)`
  - result: `work/results/dataset/esacci.SNOW.day.L3C.SCFV.AVHRR.NOAA-8.AVHRR_NOAA8.3-0.r1--475b9b4beffd.json`

### ValueError / (top-level)

Message: conflicting sizes for dimension 'nbmonth': length 216 on 'nbmonth' and length 215 on {'nbpoints': 'distance_to_coast', 'nbmonth': 'sla'}

#### vectordatacube (1)

- `esacci.SEALEVEL.mon.IND.MSLTR.multi-sensor.multi-platform.MERGED.2-2.SE_ASIA`
  - lost: `open`
  - old: `open`
  - new: `(none)`
  - result: `work/results/vectordatacube/esacci.SEALEVEL.mon.IND.MSLTR.multi-sensor.multi-platform.MERGED.2-2.SE_ASIA--0fc47ed7591e.json`
