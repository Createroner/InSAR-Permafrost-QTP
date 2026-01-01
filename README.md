## InSAR-RTS-Peramfrost-QTP
This is the repository for the paper "Satellite radar reveals nearly 20% permafrost interannual subsidence in the Qinghai-Tibet Plateau"
### InSAR process
#### SBAS-InSAR process
InSAR processing algorithms including ISCE (source: https://github.com/isce-framework/isce2, accessed on 24 Jan. 2024) and MintPy (source: https://github.com/insarlab/MintPy, accessed on 18 April 2024) are open-source and freely available through Github.
#### HPC-SBAS-InSAR
If you want to run parallel Insar processing algorithms on HPC, you can use the folder HPC-SSAR. You need to place three files (Bach_setinel.sbatch, Sentinel.sbatch, Sentinel_sig.sh) in the same folder. Then run the sbatch sentinel.sbatch script, which is sbatch sentinel.sbatch/work/sentinel/158/158-06/represents a single node to run a Frame's Sentinel-1 data

### Then inventory of RTSs
1、RTSs\RTS-QTP.shp: the known RTSs in QTP provided from Luo (source:https://doi.org/10.5281/ zenodo.7309867, accessed on 18 April 2024). <br>

### Deformation Data
