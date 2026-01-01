## InSAR-RTS-Peramfrost-QTP
This is the repository for the paper "Satellite radar reveals nearly 20% permafrost interannual subsidence in the Qinghai-Tibet Plateau"
### InSAR process
#### SBAS-InSAR process
InSAR processing algorithms including ISCE (source: https://github.com/isce-framework/isce2, assessed 30 December 2025) and MintPy (source: https://github.com/insarlab/MintPy,assessed 30 December 2025) are open-source and freely available through Github.
#### HPC-SBAS-InSAR
If you want to run parallel Insar processing algorithms on HPC, you can use the folder Code. You need to place three files (Bach_setinel.sbatch, Sentinel.sbatch, Sentinel_sig.sh) in the same folder. Then run the sbatch sentinel.sbatch script, which is sbatch sentinel.sbatch/work/sentinel/158/158-06/represents a single node to run a Frame's Sentinel-1 data

### Deformation Data
The InSAR-derived surface deformation results over permafrost regions of the Qinghai–Tibet Plateau used in this study are publicly shared for academic research ().
