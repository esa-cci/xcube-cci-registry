# State Diff Summary

Generated: 2026-07-16

Comparison: current working tree against `HEAD` in `xcube-cci-registry`.
`write_geojson` is normalized to `write_kml` before comparing flags.

## Summary

| Data type | Old entries | New entries | Added entries | Removed entries | Changed flags | Gained flags | Lost flags |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| `dataset` | 588 | 589 | 1 | 0 | 164 | 158 | 6 |
| `datatree` | 19 | 19 | 0 | 0 | 0 | 0 | 0 |
| `geodataframe` | 49 | 49 | 0 | 0 | 2 | 0 | 2 |
| `vectordatacube` | 37 | 37 | 0 | 0 | 1 | 0 | 1 |
| **Total** | 693 | 694 | 1 | 0 | 167 | 158 | 9 |

## Flag Transition Summary

### dataset

- 112x `open, constrain_time` -> `open, constrain_time, write_zarr`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.4-0.r1`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.5-0.2016-2015`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.5-0.2017-2016`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.5-0.2018-2017`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.5-0.2019-2018`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.5-0.2020-2010`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.5-0.2020-2019`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.5-0.2021-2020`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.6-0.100m-2010-2007`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.6-0.100m-2016-2015`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.6-0.100m-2017-2016`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.6-0.100m-2018-2017`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.6-0.100m-2019-2018`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.6-0.100m-2020-2010`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.6-0.100m-2020-2019`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.6-0.100m-2021-2020`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.6-0.100m-2022-2021`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.7-0.100m-2020-2010`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.CHANGE.7-0.100m-2020-2019`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.MERGED.2-0.r1`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.MERGED.3-0.r1`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.MERGED.4-0.r1`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.MERGED.5-0.100m`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.MERGED.6-0.100m`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.MERGED.7-0.100m`
  - `esacci.ICESHEETS.unspecified.L4.IV.SAR-C-(Sentinel-1).multi-platform.UNSPECIFIED.1-1.greenland_s1_250m_20150610_20170321_Helheim`
  - `esacci.ICESHEETS.unspecified.L4.SEC.multi-sensor.multi-platform.UNSPECIFIED.0-1.greenland_sec_saral_altika`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.AMI-SAR.ERS-1.UNSPECIFIED.1-1.greenland_northern_drainage_basin_winter_1991_1992`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.AMI-SAR.ERS-2.UNSPECIFIED.1-1.greenland_margin_1995_1996`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.MSI-(Sentinel-2).Sentinel-2A.UNSPECIFIED.1-0.greenland_s2_50m_20160508_20160518_docker_smith`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.MSI-(Sentinel-2).multi-platform.UNSPECIFIED.1-1.greenland_s2_50m_seasonal_20170501_20170829_Helheim`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.MSI-(Sentinel-2).multi-platform.UNSPECIFIED.1-1.greenland_s2_50m_seasonal_20170501_20170914_Petermann`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.MSI-(Sentinel-2).multi-platform.UNSPECIFIED.1-1.greenland_s2_50m_seasonal_20170603_20170908_Jakobshavn`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.MSI-(Sentinel-2).multi-platform.UNSPECIFIED.1-1.greenland_s2_50m_seasonal_20170625_20170810_79Fjord`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.MSI-(Sentinel-2).multi-platform.UNSPECIFIED.1-1.greenland_s2_50m_seasonal_20170625_20170810_Zachariae`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.MSI-(Sentinel-2).multi-platform.UNSPECIFIED.1-1.greenland_s2_50m_seasonal_20170630_20170814_Hagen`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.MSI-(Sentinel-2).multi-platform.UNSPECIFIED.1-1.greenland_s2_50m_seasonal_20170715_20170814_Upernavik`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.MSI-(Sentinel-2).multi-platform.UNSPECIFIED.1-1.greenland_s2_50m_seasonal_20170721_20170820_Kangerdlugssuaq`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.MSI-(Sentinel-2).multi-platform.UNSPECIFIED.1-1.greenland_s2_50m_timeseries_20170501_20170829_Helheim`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.MSI-(Sentinel-2).multi-platform.UNSPECIFIED.1-1.greenland_s2_50m_timeseries_20170501_20170914_Petermann`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.MSI-(Sentinel-2).multi-platform.UNSPECIFIED.1-1.greenland_s2_50m_timeseries_20170603_20170908_Jakobshavn`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.MSI-(Sentinel-2).multi-platform.UNSPECIFIED.1-1.greenland_s2_50m_timeseries_20170625_20170810_79Fjord`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.MSI-(Sentinel-2).multi-platform.UNSPECIFIED.1-1.greenland_s2_50m_timeseries_20170625_20170810_Zachariae`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.MSI-(Sentinel-2).multi-platform.UNSPECIFIED.1-1.greenland_s2_50m_timeseries_20170630_20170814_Hagen`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.MSI-(Sentinel-2).multi-platform.UNSPECIFIED.1-1.greenland_s2_50m_timeseries_20170715_20170814_Upernavik`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.MSI-(Sentinel-2).multi-platform.UNSPECIFIED.1-1.greenland_s2_50m_timeseries_20170721_20170820_Kangerdlugssuaq`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.SAR-(RadarSat-2).RadarSat-2.UNSPECIFIED.1-0.greenland_map_winter_2013_2014`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.SAR-2000.multi-platform.UNSPECIFIED.1-0.greenland_csk_250m_timeseries_20120604_20141223_Jakobshavn`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.SAR-C-(Sentinel-1).Sentinel-1A.UNSPECIFIED.1-0.greenland_map_winter_2014_2015`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.SAR-C-(Sentinel-1).Sentinel-1A.UNSPECIFIED.1-2.greenland_map_winter_2015_2016`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.SAR-C-(Sentinel-1).multi-platform.UNSPECIFIED.1-0.greenland_map_winter_2016_2017`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.SAR-C-(Sentinel-1).multi-platform.UNSPECIFIED.1-0.greenland_map_winter_2017_2018`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.SAR-C-(Sentinel-1).multi-platform.UNSPECIFIED.1-1.greenland_s1_250m_20141010_20170317_Upernavik`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.SAR-C-(Sentinel-1).multi-platform.UNSPECIFIED.1-1.greenland_s1_250m_20141011_20170317_20150122_20170322_Hagen`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.SAR-C-(Sentinel-1).multi-platform.UNSPECIFIED.1-1.greenland_s1_250m_20141011_20170317_Jakobshavn`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.SAR-C-(Sentinel-1).multi-platform.UNSPECIFIED.1-1.greenland_s1_250m_20150118_20170321_Kangerlussuaq`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.SAR-C-(Sentinel-1).multi-platform.UNSPECIFIED.1-1.greenland_s1_250m_20150122_20170319_Petermann`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.SAR-C-(Sentinel-1).multi-platform.UNSPECIFIED.1-1.greenland_s1_250m_20150122_20170322_79-Fjord`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.SAR-C-(Sentinel-1).multi-platform.UNSPECIFIED.1-1.greenland_s1_250m_20150124_20170322_Storstroemmen`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.SAR-C-(Sentinel-1).multi-platform.UNSPECIFIED.1-1.greenland_s1_250m_20150126_20170322_Zachariae`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.multi-sensor.multi-platform.UNSPECIFIED.1-0.greenland_timeseries_Kangerlussuaq`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.multi-sensor.multi-platform.UNSPECIFIED.1-1.greenland_timeseries_2002_2010_Jakobshavn`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.multi-sensor.multi-platform.UNSPECIFIED.1-1.greenland_timeseries_Hagen`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.multi-sensor.multi-platform.UNSPECIFIED.1-1.greenland_timeseries_Helheim`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.multi-sensor.multi-platform.UNSPECIFIED.1-1.greenland_timeseries_Petermann`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.multi-sensor.multi-platform.UNSPECIFIED.1-1.greenland_timeseries_Storstrommen`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.multi-sensor.multi-platform.UNSPECIFIED.1-1.greenland_timeseries_Zachariae_79Fjord`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.multi-sensor.multi-platform.UNSPECIFIED.1-2.greenland_timeseries_1992_2010_Jakobshavn`
  - `esacci.ICESHEETS.unspecified.Unspecified.IV.multi-sensor.multi-platform.UNSPECIFIED.1-2.greenland_timeseries_Upernarvik`
  - `esacci.ICESHEETS.yr.Unspecified.SEC.multi-sensor.multi-platform.UNSPECIFIED.1-2.r1`
  - `esacci.LC.yr.L4.PFT.Unspecified.Unspecified.Map.2-0-81.r1`
  - `esacci.PERMAFROST.yr.L4.ALT.multi-sensor.multi-platform.ERA5_MODISLST_BIASCORRECTED.03-0.r1`
  - `esacci.PERMAFROST.yr.L4.ALT.multi-sensor.multi-platform.MODISLST_CRYOGRID.03-0.r1`
  - `esacci.PERMAFROST.yr.L4.GTD.multi-sensor.multi-platform.ERA5_MODISLST_BIASCORRECTED.03-0.r1`
  - `esacci.PERMAFROST.yr.L4.GTD.multi-sensor.multi-platform.MODISLST_CRYOGRID.03-0.r1`
  - `esacci.PERMAFROST.yr.L4.PFR.multi-sensor.multi-platform.ERA5_MODISLST_BIASCORRECTED.03-0.r1`
  - `esacci.PERMAFROST.yr.L4.PFR.multi-sensor.multi-platform.MODISLST_CRYOGRID.03-0.r1`
  - `esacci.SEAICE.day.L3C.SICONC.ESMR-(Nimbus-5).Nimbus-5.NIMBUS5_ESMR-EASE2_NH.1-0.NH`
  - `esacci.SEAICE.day.L3C.SICONC.ESMR-(Nimbus-5).Nimbus-5.NIMBUS5_ESMR-EASE2_SH.1-0.SH`
  - `esacci.SEAICE.day.L3C.SICONC.ESMR-(Nimbus-5).Nimbus-5.NIMBUS5_ESMR_EASE2_LDTPcorrected_NH.1-1.NH`
  - `esacci.SEAICE.day.L3C.SICONC.ESMR-(Nimbus-5).Nimbus-5.NIMBUS5_ESMR_EASE2_LDTPcorrected_SH.1-1.SH`
  - `esacci.SEAICE.day.L4.SICONC.multi-sensor.multi-platform.AMSR_25kmEASE2.2-1.NH`
  - `esacci.SEAICE.day.L4.SICONC.multi-sensor.multi-platform.AMSR_25kmEASE2.2-1.SH`
  - `esacci.SEAICE.day.L4.SICONC.multi-sensor.multi-platform.AMSR_50kmEASE2.2-1.NH`
  - `esacci.SEAICE.day.L4.SICONC.multi-sensor.multi-platform.AMSR_50kmEASE2.2-1.SH`
  - `esacci.SEAICE.day.L4.SICONC.multi-sensor.multi-platform.RE_SSMI_12-5kmEASE2-NH.3-0.NH`
  - `esacci.SEAICE.day.L4.SICONC.multi-sensor.multi-platform.RE_SSMI_12-5kmEASE2-SH.3-0.SH`
  - `esacci.SEAICE.mon.L3C.SITHICK.RA-2.Envisat.NH25KMEASE2.2-0.r1`
  - `esacci.SEAICE.mon.L3C.SITHICK.RA-2.Envisat.NH25KMEASE2.3-0.r1`
  - `esacci.SEAICE.mon.L3C.SITHICK.RA-2.Envisat.NH25KMEASE2.4-0.r1`
  - `esacci.SEAICE.mon.L3C.SITHICK.RA-2.Envisat.SH50KMEASE2.2-0.r1`
  - `esacci.SEAICE.mon.L3C.SITHICK.RA-2.Envisat.SH50KMEASE2.3-0.r1`
  - `esacci.SEAICE.mon.L3C.SITHICK.RA-2.Envisat.SH50KMEASE2.4-0.r1`
  - `esacci.SEAICE.mon.L3C.SITHICK.RA.ERS-2.NH25KMEASE2.4-0.r1`
  - `esacci.SEAICE.mon.L3C.SITHICK.SIRAL.CryoSat-2.NH25KMEASE2.2-0.r1`
  - `esacci.SEAICE.mon.L3C.SITHICK.SIRAL.CryoSat-2.NH25KMEASE2.3-0.r1`
  - `esacci.SEAICE.mon.L3C.SITHICK.SIRAL.CryoSat-2.NH25KMEASE2.4-0.r1`
  - `esacci.SEAICE.mon.L3C.SITHICK.SIRAL.CryoSat-2.SH50KMEASE2.2-0.r1`
  - `esacci.SEAICE.mon.L3C.SITHICK.SIRAL.CryoSat-2.SH50KMEASE2.3-0.r1`
  - `esacci.SEAICE.mon.L3C.SITHICK.SIRAL.CryoSat-2.SH50KMEASE2.4-0.r1`
  - `esacci.SEAICE.mon.L3C.SITHICK.SRAL.Sentinel-3A.NH25KMEASE2.4-0.r1`
  - `esacci.SEAICE.mon.L3C.SITHICK.SRAL.Sentinel-3A.SH50KMEASE2.4-0.r1`
  - `esacci.SEAICE.mon.L3C.SITHICK.SRAL.Sentinel-3B.NH25KMEASE2.4-0.r1`
  - `esacci.SEAICE.mon.L3C.SITHICK.SRAL.Sentinel-3B.SH50KMEASE2.4-0.r1`
  - `esacci.SEASURFACESALINITY.15-days.L4.SSS.multi-sensor.multi-platform.POLAR-MERGED_OI_Monthly_CENTRED_15Day_25kmEASE2-NH.05-5.r1`
  - `esacci.SEASURFACESALINITY.15-days.L4.SSS.multi-sensor.multi-platform.POLAR-MERGED_OI_Monthly_CENTRED_15Day_25kmEASE2-NH.4-41.r1`
  - `esacci.SEASURFACESALINITY.15-days.L4.SSS.multi-sensor.multi-platform.POLAR-MERGED_OI_Monthly_CENTRED_15Day_25kmEASE2-SH.05-5.r1`
  - `esacci.SEASURFACESALINITY.15-days.L4.SSS.multi-sensor.multi-platform.POLAR-MERGED_OI_Monthly_CENTRED_15Day_25kmEASE2-SH.4-41.r1`
  - `esacci.SEASURFACESALINITY.day.L4.SSS.multi-sensor.multi-platform.POLAR-MERGED_OI_7DAY_RUNNINGMEAN_DAILY_25kmEASE2-NH.05-5.r1`
  - `esacci.SEASURFACESALINITY.day.L4.SSS.multi-sensor.multi-platform.POLAR-MERGED_OI_7DAY_RUNNINGMEAN_DAILY_25kmEASE2-NH.4-41.r1`
  - `esacci.SEASURFACESALINITY.day.L4.SSS.multi-sensor.multi-platform.POLAR-MERGED_OI_7DAY_RUNNINGMEAN_DAILY_25kmEASE2-SH.05-5.r1`
  - `esacci.SEASURFACESALINITY.day.L4.SSS.multi-sensor.multi-platform.POLAR-MERGED_OI_7DAY_RUNNINGMEAN_DAILY_25kmEASE2-SH.4-41.r1`
- 25x `(none)` -> `open, constrain_time, write_zarr`
  - `esacci.OC.5-days.L3S.CHLOR_A.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.5-days.L3S.IOP.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.5-days.L3S.K_490.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.5-days.L3S.OC_PRODUCTS.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.5-days.L3S.RRS.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.8-days.L3S.CHLOR_A.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.8-days.L3S.IOP.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.8-days.L3S.K_490.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.8-days.L3S.OC_PRODUCTS.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.8-days.L3S.RRS.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.day.L3S.CHLOR_A.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.day.L3S.IOP.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.day.L3S.K_490.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.day.L3S.OC_PRODUCTS.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.day.L3S.RRS.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.mon.L3S.CHLOR_A.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.mon.L3S.IOP.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.mon.L3S.K_490.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.mon.L3S.OC_PRODUCTS.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.mon.L3S.RRS.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.yr.L3S.CHLOR_A.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.yr.L3S.IOP.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.yr.L3S.K_490.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.yr.L3S.OC_PRODUCTS.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
  - `esacci.OC.yr.L3S.RRS.multi-sensor.multi-platform.MERGED.6-0.sinusoidal`
- 7x `open, constrain_time` -> `open, constrain_time, constrain_region`
  - `esacci.GHG.satellite-orbit-frequency.L2.CH4.TANSO-FTS-2.GOSAT-2.SRFP.v2-0-3.r1`
  - `esacci.GHG.satellite-orbit-frequency.L2.CH4.TANSO-FTS-2.GOSAT-2.SRPR.v2-0-3.r1`
  - `esacci.GHG.satellite-orbit-frequency.L2.CO2.TANSO-FTS-2.GOSAT-2.SRFP.v2-0-3.r1`
  - `esacci.SEALEVEL.unspecified.IND.MSLAMPH.multi-sensor.multi-platform.MERGED.2-0.r1`
  - `esacci.SST.satellite-orbit-frequency.L2P.SSTskin.AATSR.Envisat.AATSR.2-1.r1`
  - `esacci.SST.satellite-orbit-frequency.L2P.SSTskin.AVHRR-2.NOAA-7.AVHRR07_G.2-1.r1`
  - `esacci.SST.satellite-orbit-frequency.L2P.SSTskin.AVHRR-3.Metop-A.AVHRRMTA_G.2-1.r1`
- 6x `(none)` -> `open, constrain_time, constrain_region, write_zarr`
  - `esacci.LST.day.L3C.LST.MODIS.Aqua.MODISA.3-00.DAY`
  - `esacci.LST.day.L3C.LST.MODIS.Aqua.MODISA.3-00.NIGHT`
  - `esacci.LST.day.L3C.LST.MODIS.Aqua.MODISA.4-00.DAY`
  - `esacci.LST.day.L3C.LST.MODIS.Aqua.MODISA.4-00.NIGHT`
  - `esacci.LST.mon.L3C.LST.MODIS.Aqua.MODISA.3-00.DAY`
  - `esacci.LST.mon.L3C.LST.MODIS.Aqua.MODISA.3-00.NIGHT`
- 5x `open, constrain_time` -> `open, constrain_time, constrain_region, write_zarr`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.MERGED.7-0.10000m`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.MERGED.7-0.1000m`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.MERGED.7-0.25000m`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.MERGED.7-0.50000m`
  - `esacci.PREC.mon.L3C.NO2.TROPOMI.Sentinel-5P.TROPOMI_KNMI-0900x1800_1M.fv1-0.r1`
- 3x `open, constrain_time, constrain_region, write_zarr` -> `open, constrain_time, write_zarr`
  - `esacci.SOILMOISTURE.day.L3S.SSMS.multi-sensor.multi-platform.ACTIVE.05-2.r1`
  - `esacci.SOILMOISTURE.day.L3S.SSMV.multi-sensor.multi-platform.COMBINED.05-2.r1`
  - `esacci.SOILMOISTURE.day.L3S.SSMV.multi-sensor.multi-platform.PASSIVE.05-2.r1`
- 2x `open` -> `open, write_zarr`
  - `esacci.ICESHEETS.yr.Unspecified.SEC.SIRAL.CryoSat-2.UNSPECIFIED.2-2.greenland_sec_cryosat_2yr`
  - `esacci.ICESHEETS.yr.Unspecified.SEC.SIRAL.CryoSat-2.UNSPECIFIED.2-2.greenland_sec_cryosat_5yr`
- 1x `open, constrain_time, constrain_region, write_zarr` -> `open, constrain_time, constrain_region`
  - `esacci.AEROSOL.mon.L3C.AER_PRODUCTS.multi-sensor.multi-platform.AATSR-ENVISAT-ENS_MONTHLY.v2-6.r1`
- 1x `open, constrain_time, constrain_region, write_zarr` -> `open, constrain_region, write_zarr`
  - `esacci.OZONE.mon.L3.LP.SCIAMACHY.Envisat.SCIAMACHY_ENVISAT.v0001.r1`
- 1x `open, constrain_time, constrain_region, write_zarr` -> `(none)`
  - `esacci.SNOW.day.L3C.SCFV.AVHRR.NOAA-8.AVHRR_NOAA8.3-0.r1`
- 1x `open, constrain_time, write_zarr` -> `open, constrain_time, constrain_region, write_zarr`
  - `esacci.BIOMASS.yr.L4.AGB.multi-sensor.multi-platform.DIFF.7-0.50000m-2020-2019`

### geodataframe

- 2x `open, constrain_time, constrain_region, write_kml` -> `open, constrain_time, write_kml`
  - `esacci.AEROSOL.satellite-orbit-frequency.L2P.AER_PRODUCTS.AATSR.Envisat.ORAC.04-01.r1`
  - `esacci.AEROSOL.satellite-orbit-frequency.L2P.AER_PRODUCTS.ATSR-2.ERS-2.ORAC.04-01.r1`

### vectordatacube

- 1x `open` -> `(none)`
  - `esacci.SEALEVEL.mon.IND.MSLTR.multi-sensor.multi-platform.MERGED.2-2.SE_ASIA`

## Report Files

- `state_diff_gained.md`
- `state_diff_lost.md`
- `state_lost_flags_errors.md`
