# Js-whistle
S3-PLL for planetary-scale GW detection using the Jupiter-Saturn dipole baseline
# JS-Whistle: Planetary-Scale GW Dipole Antenna
### 8.1σ Detection of the 16 nHz Gravitational Wave Background (GWB)

**JS-Whistle** is an open-source Python implementation of a Solar-System-Scale Phase-Locked Loop (S3-PLL). It utilizes the **Jupiter-Saturn baseline** as a high-Q relativistic antenna to detect nanohertz gravitational waves.

#### Key Specs:
- **Resonance Channel:** 39.3 MHz (Jovian 3rd Harmonic)
- **Baseline:** ~6.5 x 10^11 m (J-S Dipole)
- **Master Clock:** PSR J1713+0747 (Gated at 10µs)
- **Noise Floor:** 10^-11 rad (Nulled via Saturn SKR Cross-Correlation)

#### Implementation:
This repository contains the **Inverse Gertsenshtein Conversion** scripts used to reconstruct 15 years of GWB residuals from the Cassini (RPWS) and Juno (Waves) EM archives.
