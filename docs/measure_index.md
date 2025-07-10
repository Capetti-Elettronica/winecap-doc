---
title: Measure Index
nav_order: 1
nav_enabled: false
---

# Measure Index

| FW Define | Descsription ITA | Description ENG | DEC | HEX | Unit | Offset | Gain |
| - | - | - | - | - | - | - | - |
| NO_MEAS_TYPE  | - | - | 0 | 0x00 | - | 0 | 1 |
| TEMP_MEAS_TYPE  | Temperatura | Temperature | 1 | 0x01 | °C | 0 | 0,01 |
| HUMI_MEAS_TYPE  | Umidità Relativa | Relative Humidity | 2 | 0x02 | % | 0 | 0,01 |
| LUX_MEAS_TYPE  | Luce | Light | 3 | 0x03 | lux | 32768 LuPo 0 LoRa | 0,1 |
| STRAIN_MEAS_TYPE  | Deformazione | Deformation | 4 | 0x04 | mm |0| 0,001 |
| CO2_MEAS_TYPE  | Concentrazione CO2 | CO2 Concentration | 5 | 0x05 | ppm | 0 | 1 |
| NRG_ELTR_MEAS_TYPE  | Energia Elettrica Attiva | Active Electric Energy | 6 | 0x06 | KWh | 0 | 1 |
| NRG_ELTA_MEAS_TYPE  | Energia Elettrica Apparente | Apparent Electric Energy | 7 | 0x07 | KVAh | 0 | 1 |
| VOL_FLD_MEAS_TYPE  | Volume Fluido | Fluid Volume | 8 | 0x08 | L | 0 | 10 |
| NRG_TRM_MEAS_TYPE  | Energia Termica | Thermal Energy | 9 | 0x09 | KWh | 0 | 1 |
| INCLINAZ_MEAS_TYPE  | Inclinazione | Tilt Angle | 10 | 0x0A | ° | 0 | 100 |
| CONTACT_MEAS_TYPE  | Contatto | Contact | 11 | 0x0B | - | 0 | 1 |
| CH4_MEAS_TYPE  | CH4 | CH4 | 12 | 0x0C | ppm |  0 | 1 |
| PRESSURE_MEAS_TYPE  | Pressione | Pressure | 13 | 0x0D | mbar | 0 | 0,1 |
| V_MEAS_TYPE  | Tensione | Voltage | 14 | 0x0E | V | 0 | 0,001 |
| I_MEAS_TYPE  | Corrente | Current | 15 | 0x0F | mA | 0 | 0,001 |
| PROP_TYPE  | Proporzionale | Proportional | 16 | 0x10 | % | 0 | 0,01 |
| WATT_M2  | Flusso Termico | Thermal Flux | 17 | 0x11 | W/m2 | 0 | 0,01 |
| FREQUENCY  | Frequenza | Frequency | 18 | 0x12 | Hz | 32768 | 0,1|
| MICROV_AL_V  | Rapporto | Ratio | 19 | 0x13 | uV/V | 0 | 0,1 |
| SPEED  | Velocità | Speed | 20 | 0x14 | m/s | 0 | 0,1 |
| AZIMUT  | Direzione | Direction | 21 | 0x15 | ° | 0 | 0,1 |
| RAD_SOLARE  | Radiazione Solare | Solar Radiation | 22 | 0x16 | W/m2 | 0 | 0,1 |
| IA_MEAS_TYPE  | Corrente  | Current  | 23 | 0x17 | A | 0 | 1 |
| IMPULSI  | Impulsi | Pulses | 24 | 0x18 | - | 0 | 1 |
| IAQ_INDEX  | IAQ | IAQ | 25 | 0x19 | - | 0 | 0,1 |
| NRG_E_REA_MEAS_TYPE  | Energia Elettrica Reattiva | Reactive Electric Energy | 26 | 0x1A | Kvarh | 0 | 1 |
| HEATING_DEGREE_DAY  | Gradi Giorno | Degree Day | 27 | 0x1B | GG | 0 | 1 |
| ACCELERATION  | Accelerazione | Acceleration | 28 | 0x1C | g | 0 | 0,1 |
| NODES  | Nodi | Nodes | 29 | 0x1D | - | 0 | 1 |
| PACKETS  | Pacchetti | Packets | 30 | 0x1E | - | 0 | 1 |
| IMPULSI_CUMULATIVI  | Impulso Cumulativo | Cumulative Pulse | 31 | 0x1F | - | 0 | 1 |
| VOC_MEAS_TYPE  | VOC | VOC | 32 | 0x20 | ppm | 0 | 1 |
| CO_MEAS_TYPE  | CO | CO | 33 | 0x21 | ppm | 0 | 1 |
| O3_MEAS_TYPE  | O3 | O3 | 34 | 0x22 | ppm | 0 | 1 |
| NO2_MEAS_TYPE  | NO2 | NO2 | 35 | 0x23 | ppm | 0 | 1 |
| CH2O_MEAS_TYPE  | CH2O | CH2O | 36 | 0x24 | ppm | 0 | 1 |
| TVOC_MEAS_TYPE  | TVOC | TVOC | 37 | 0x25 | ppb | 0 | 1 |
| MASS_PM_1_0_TYPE  | Conc Massa PM1.0 | Mass Conc PM1.0 | 38 | 0x26 | µg/m³ | 0 | 1 |
| MASS_PM_2_5_TYPE  | Conc Massa PM2.5 | Mass Conc PM2.5 | 39 | 0x27 | µg/m³ | 0 | 0,01 |
| MASS_PM_4_0_TYPE  | Conc Massa PM4.0 | Mass Conc PM4.0 | 40 | 0x28 | µg/m³ | 0 | 0,01 |
| MASS_PM_10_0_TYPE  | Conc Massa PM10.0 | Mass Conc PM10.0 | 41 | 0x29 | µg/m³ | 0 | 0,01 |
| NUMB_PM_0_5_TYPE  | Conc Numero PM0.5 | Numb Conc PM0.5 | 42 | 0x2A | #/cm³ | 0 | 1 |
| NUMB_PM_1_0_TYPE  | Conc Numero PM1.0 | Numb Conc PM1.0 | 43 | 0x2B | #/cm³ | 0 | 1 |
| NUMB_PM_2_5_TYPE  | Conc Numero PM2.5 | Numb Conc PM2.5 | 44 | 0x2C | #/cm³ | 0 | 1 |
| NUMB_PM_4_0_TYPE  | Conc Numero PM4.0 | Numb Conc PM4.0 | 45 | 0x2D | #/cm³ | 0 | 1 |
| NUMB_PM_10_0_TYPE  | Conc Numero PM10.0 | Numb Conc PM10.0 | 46 | 0x2E | #/cm³ | 0 | 1 |
| SIZE_PM_TYPE  | Dimensione Tipica PM | Typical Particle Size | 47 | 0x2F | µm | 0 | 1 |
| DIST_ABS_MEAS_TYPE  | Distanza assoluta | Absolute Distance | 48 | 0x30 | mm | 0 | 1 |
| DIST_REL_MEAS_TYPE  | Distanza relativa | Relative Distance | 49 | 0x31 | mm | 0 | 0,1 |
| INCLINAZ_AXIS_X_MEAS_TYPE  | Inclinazione X | Tilt Angle X | 50 | 0x32 | ° |0 | 0,0002 |
| INCLINAZ_AXIS_Y_MEAS_TYPE  | Inclinazione Y | Tilt Angle Y | 51 | 0x33 | ° |0 | 0,0002 |
| NRG_ELTR_CUM_MEAS_TYPE  | Energia Elettrica Attiva Cumulativa | Cumulative Active Electric Energy | 52 | 0x34 | KWh | 0 | 1 |
| NRG_ELTA_CUM_MEAS_TYPE  | Energia Elettrica Apparente Cumulativa | Cumulative Apparent Electric Energy | 53 | 0x35 | KVAh | 0 | 1 |
| VOL_FLD_CUM_MEAS_TYPE  | Volume Fluido Cumulativo| Cumulative Fluid Volume | 54 | 0x36 | L | 0 | 1 |
| NRG_TRM_CUM_MEAS_TYPE  | Energia Termica Cumulativa| Cumulative Thermal Energy | 55 | 0x37 | KWh | 0 | 1 |
| NRG_E_REA_CUM_MEAS_TYPE  | Energia Elettrica Reattiva Cumulativa| Cumulative Reactive Electric Energy | 56 | 0x38 | Kvarh | 0 | 1 |
| GENERIC_MEAS_TYPE  | Generico | Generic | 57 | 0x39 | - | 0 | 1 |
| NRG_ELTR_DIFF_MEAS_TYPE  | Energia Elettrica Attiva Differenziale | Differential Active Electric Energy | 58 | 0x3A | KWh | 0 | 1 |
| NRG_ELTA_DIFF_MEAS_TYPE  | Energia Elettrica Apparente Differenziale | Differential Apparent Electric Energy | 59 | 0x3B | KVAh | 0 | 1 |
| VOL_FLD_DIFF_MEAS_TYPE  | Volume Fluido Differenziale| Differential Fluid Volume | 60 | 0x3C | L | 0 | 1 |
| NRG_TRM_DIFF_MEAS_TYPE  | Energia Termica Differenziale| Differential Thermal Energy | 61 | 0x3D | KWh | 0 | 1 |
| NRG_E_REA_DIFF_MEAS_TYPE  | Energia Elettrica Reattiva Differenziale| Differential Reactive Electric Energy | 62 | 0x3E | Kvarh | 0 | 1 |
| INCLINAZ_AXIS_Z_MEAS_TYPE  | Inclinazione Z | Tilt Angle Z | 63 | 0x3F | ° | 0 | 0,0002 |
| MAGN_X_MEAS_TYPE  | Campo Magnetico X | Magnetic Field X | 64 | 0x40 | G | 0 | 0,001 |
| MAGN_Y_MEAS_TYPE  | Campo Magnetico Y | Magnetic Field Y | 65 | 0x41 | G | 0 | 0,001 |
| MAGN_Z_MEAS_TYPE  | Campo Magnetico Z | Magnetic Field Z | 66 | 0x42 | G | 0 | 0,001 |
| DAILY_TEMP_MEAS_TYPE | Temperatura Giornaliera | Daily Temperature | 67 | 0x43 | °C | 0 | 0,01|
| POWER_MEAS_TYPE | Potenza | Power | 68 | 0x44 | kW | 0 | 1 |
| RELATIVE_IAQ_INDEX | Relative IAQ | Relative IAQ | 69 | 0x45 | - | 0 | 1 |
| INDEX  | Indice | Index | 200 | 0xC8 | - | 0 | 1 |
| - | - | - | - | - | - | - | - |
| CUSTOM_CH  | Test | Test | 252 | 0xFC | - | 0 | 1 |
| RX_SIGNAL  | Segnale Rx | Rx Signal | 253 | 0xFD | % | | |
| TX_SIGNAL  | Segnale Tx | Tx signal | 254 | 0xFE | % | | |
| BATTERY  | Batteria | Battery | 255 | 0xFF | x/7 | | |

{: .fs-6 .fw-300 }
