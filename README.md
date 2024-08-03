# 🌍 Awesome Large Weather Models (LWMs) | AI for Earth (AI4Earth) | AI for Science (AI4Science)
## 🧭 Guideline
A collection of articles on **Large Weather Models (LWMs)**, to make it easier to find and learn. 👏 Contributions to this hub are welcome!
- [🌍 Awesome Large Weather Models (LWMs) | AI for Earth (AI4Earth) | AI for Science (AI4Science)](#-awesome-large-weather-models-lwms--ai-for-earth-ai4earth--ai-for-science-ai4science)
  - [🧭 Guideline](#-guideline)
  - [🆕 LWMs News](#-lwms-news)
  - [🗂️ LWMs Lists](#️-lwms-lists)
  - [🗃️ Dataset Lists](#️-dataset-lists)
  - [📖 Papers](#-papers)
    - [WeatherBench](#weatherbench)
    - [MetNet](#metnet)
    - [FourCastNet](#fourcastnet)
    - [Pangu-Weather](#pangu-weather)
    - [GraphCast](#graphcast)
    - [ClimaX](#climax)
    - [FengWu](#fengwu)
    - [FuXi](#fuxi)
    - [AI-GOMS](#ai-goms)
    - [XiHe](#xihe)
    - [FNO](#fno)
    - [Nowcast](#nowcast)
    - [Physics-AI](#physics-ai)
    - [Datasets](#datasets)
    - [More](#more)
  - [🚀 Code](#-code)
## 🆕 LWMs News
- 2024/07/30: FuXi-S2S published in Nature Communications [[link]](https://www.nature.com/articles/s41467-024-50714-1));
- 2024/06/20: WEATHER-5K: A Large-scale Global Station Weather Dataset Towards Comprehensive Time-series Forecasting Benchmark [[link]](https://arxiv.org/abs/2406.14399);
- 2024/05/24: ORCA: A Global Ocean Emulator for Multi-year to Decadal Predictions [[link]](https://arxiv.org/abs/2405.15412);
- 2024/05/22: Generalizing Weather Forecast to Fine-grained Temporal Scales via Physics-AI Hybrid Modeling [[link]](https://arxiv.org/abs/2405.13796);
- 2024/05/20: Aurora: A Foundation Model of the Atmosphere [[link]](https://arxiv.org/abs/2405.13063);
- 2024/05/09: FuXi-ENS: A machine learning model for medium-range ensemble weather forecasting [[link]](https://arxiv.org/abs/2405.05925);
- 2024/05/06: CRA5: Extreme Compression of ERA5 for Portable Global Climate and Weather Research via an Efficient Variational Transformer [[link]](https://arxiv.org/abs/2405.03376);
- 2024/04/15: ClimODE: Climate and Weather Forecasting with Physics-informed Neural ODEs [[link]](https://arxiv.org/abs/2404.10024);
- 2024/04/12: FuXi-DA: A Generalized Deep Learning Data Assimilation Framework for Assimilating Satellite Observations [[link]](https://arxiv.org/abs/2404.08522);
- 2024/03/29: SEEDS: Generative emulation of weather forecast ensembles with diffusion models [[link]](https://www.science.org/doi/full/10.1126/sciadv.adk4489);
- 2024/03/13: KARINA: An Efficient Deep Learning Model for Global Weather Forecast [[link]](https://arxiv.org/abs/2403.10555);
- 2024/02/06: CasCast: Skillful High-resolution Precipitation Nowcasting via Cascaded Modelling [[link]](https://arxiv.org/abs/2402.04290);
- 2024/02/04: XiHe, the first data-driven 1/12° resolution global ocean eddy-resolving forecasting model [[link]](https://arxiv.org/abs/2402.02995);
- 2024/02/02: ExtremeCast: Boosting Extreme Value Prediction for Global Weather Forecast [[link]](https://arxiv.org/abs/2402.01295);
<details>
  <summary>Expand to see more LWMs news</summary>
- 2024/01/28: FengWu-GHR, the first data-driven global weather forecasting model running at the 0.09∘ horizontal resolution [[link]](https://arxiv.org/abs/2402.00059);
- 2023/12/27: GenCast, a ML-based generative model for ensemble weather forecasting [[link]](https://arxiv.org/abs/2312.15796);
- 2023/12/16: Four-Dimensional Variational (4DVar) assimilation, and develop an AI-based cyclic weather forecasting system, FengWu-4DVar [[link]](https://arxiv.org/abs/2312.12455);
- 2023/12/15: FuXi-S2S: An accurate machine learning model for global subseasonal forecasts [[link]](https://arxiv.org/abs/2312.09926);
- 2023/12/11: A unified and flexible framework that can equip any type of spatio-temporal models is proposed based on residual diffusion DiffCast [[link]](https://arxiv.org/abs/2312.06734);
- 2023/11/13: GCMs are physics-based simulators which combine a numerical solver for large-scale dynamics with tuned representations for small-scale processes such as cloud formation. [[link]](https://arxiv.org/abs/2311.07222);
- 2023/12/13: FuXi is open source [[link]](https://github.com/tpys/ai-models-fuxi);
- 2023/11/14: GraphCast published in Science [[link]](https://www.science.org/doi/abs/10.1126/science.adi2336);
- 2023/09/14: Pangu-Weather published in Nature [[link]](https://www.nature.com/articles/s41586-023-06185-3);
- 2023/08/25: ClimaX published in ICML 2023 [[link]](https://openreview.net/forum?id=TowCaiz7Ui);
</details>

## 🗂️ LWMs Lists
| LWM name     | From            | Date(1st) | Publication | Links                                     |
| ------------- | --------------- | ---------------- | -------------- | ------------------------------------------------------------ |
| MetNet   | Google        | 2020.03        | -              | [[paper]](https://arxiv.org/abs/2003.12140) [[github]](https://github.com/openclimatefix/metnet) |
| FourCastNet   | NVIDIA        | 2022.02          | PASC 23              | [[paper]](https://arxiv.org/abs/2202.11214) [[github]](https://github.com/NVlabs/FourCastNet) |
| MetNet-2   | Google        | 2022.09        | Nature Communications | [[paper]](https://www.nature.com/articles/s41467-022-32483-x) [[github]](https://github.com/openclimatefix/metnet)  |
| Pangu-Weather | Huaiwei         | 2022.11          | Nature         | [[paper]](https://www.nature.com/articles/s41586-023-06185-3) [[github]](https://github.com/198808xc/Pangu-Weather) |
| GraphCast     | DeepMind        | 2022.12          | Science        | [[paper]](https://www.science.org/doi/10.1126/science.adi2336) [[github]](https://github.com/google-deepmind/graphcast) |
| ClimaX        | Microsoft       | 2023.01          | ICML 2023      | [[paper]](https://arxiv.org/abs/2301.10343) [[github]](https://github.com/microsoft/ClimaX) |
| Fengwu        | Shanghai AI Lab | 2023.04          | -              | [[paper]](https://arxiv.org/abs/2304.02948) [[github]](https://github.com/OpenEarthLab/FengWu) |
| MetNet-3  | Google        | 2023.06        | - | [[paper]](https://arxiv.org/abs/2306.06079)  | 
| FuXi          | Fudan           | 2023.06          | npj 2023              | [[paper]](https://arxiv.org/abs/2306.12873) [[github]](https://github.com/tpys/ai-models-fuxi) |
| NowcastNet   | Tsinghua        | 2023.07         | Nature      | [[paper]](https://www.nature.com/articles/s41586-023-06184-4) |
| AI-GOMS       | Tsinghua        | 2023.08          | -              | [[paper]](https://arxiv.org/abs/2308.03152)                  |
| FuXi-Extreme    | Fudan           | 2023.10        | -              | [[paper]](https://arxiv.org/abs/2310.19822) |
| NeuralGCM    | DeepMind           | 2023.11        | -              | [[paper]](https://arxiv.org/abs/2311.07222) |
| FengWu-4DVar    | Tsinghua           | 2023.12        | ICML 2024         | [[paper]](https://arxiv.org/abs/2312.12455) |
| FengWu-Adas     | Shanghai AI Lab  | 2023.12        | -              | [[paper]](https://arxiv.org/abs/2312.12462) | 
| FuXi-S2S     | Fudan  | 2023.12        | Nature Communications              | [[arXiv paper]](https://arxiv.org/abs/2312.09926) [[NC paper]](https://www.nature.com/articles/s41467-024-50714-1)| 
| GenCast    | DeepMind           | 2023.12        | -              | [[paper]](https://arxiv.org/abs/2312.15796) |
| DiffCast    | HITsz    | 2023.12        | CVPR 2024              | [[paper]](https://arxiv.org/abs/2312.06734) | 
| FengWu-GHR    | Shanghai AI Lab           | 2024.01        | -              | [[paper]](https://arxiv.org/abs/2402.00059) |
| ExtremeCast   | Shanghai AI Lab           | 2024.02        | -              | [[paper]](https://arxiv.org/abs/2402.01295) [[github]](https://github.com/black-yt/ExtremeCast)| 
| XiHe    | NUDT           | 2024.02        | -              | [[paper]](https://arxiv.org/abs/2402.02995) [[github]](https://github.com/Ocean-Intelligent-Forecasting/XiHe-GlobalOceanForecasting)| 
| CasCast    | Shanghai AI Lab           | 2024.02        | ICML 2024              | [[paper]](https://arxiv.org/abs/2402.04290) [[github]](https://github.com/OpenEarthLab/CasCast)| 
| KARINA    | KIST           | 2024.03        | -             | [[paper]](https://arxiv.org/abs/2403.10555) | 
| SEEDS    | Google           | 2024.03        | Science Advances              | [[paper]](https://www.science.org/doi/full/10.1126/sciadv.adk4489) | 
| FuXi-DA          | Fudan           | 2024.04          | -              | [[paper]](https://arxiv.org/abs/2404.08522)  |
| ClimODE  | Aalto University | 2024.04        | ICLR 2024 (Oral)           | [[paper]](https://arxiv.org/abs/2404.10024) [[github]](https://github.com/Aalto-QuML/ClimODE)  |
| FuXi-ENS     | Fudan  | 2024.05        | -              | [[paper]](https://arxiv.org/abs/2405.05925) | 
| Aurora     | Microsoft  | 2024.05        | -              | [[paper]](https://arxiv.org/abs/2405.13063)| 
| WeatherGFT     | Shanghai AI Lab  | 2024.05        | -              | [[paper]](https://arxiv.org/abs/2405.13796) [[github]](https://github.com/black-yt/WeatherGFT)| 
| ORCA     | Shanghai AI Lab  | 2024.05        | -              | [[paper]](https://arxiv.org/abs/2405.15412) [[github]](https://github.com/OpenEarthLab/ORCA)| 

## 🗃️ Dataset Lists
| Dataset name     | From            | Date(1st) | Publication | Links                                     |
| ------------- | --------------- | ---------------- | -------------- | ------------------------------------------------------------ |
| WeatherBench     | Google        | 2020.02        | JAMES 2020 | [[paper]](https://arxiv.org/abs/2002.00469) [[github]](https://github.com/pangeo-data/WeatherBench) |
| ERA5             | ECMWF         | 2020.05        | -              | [[paper]](https://rmets.onlinelibrary.wiley.com/doi/full/10.1002/qj.3803?_hsenc=p2ANqtz-_Rot9IrSLOikF_COUhGRbbp9PzsUsmjSNJP6g-f4x5EegqaFipfLPkl9hMvTpyZVGACYUneXK1UVgfCc-V_Lx98XGPtw) [[link]](https://cds.climate.copernicus.eu/#!/search?text=ERA5&type=dataset&keywords=((%20%22Product%20type:%20Reanalysis%22%20)%20AND%20(%20%22Variable%20domain:%20Atmosphere%20(surface)%22%20)%20AND%20(%20%22Spatial%20coverage:%20Global%22%20)%20AND%20(%20%22Temporal%20coverage:%20Past%22%20)%20AND%20(%20%22Provider:%20Copernicus%20C3S%22%20))) |
| SEVIR            | MIT           | 2020.06        | NeurIPS 2020   | [[paper]](https://proceedings.neurips.cc/paper_files/paper/2020/file/fa78a16157fed00d7a80515818432169-Paper.pdf) [[github]](https://github.com/MIT-AI-Accelerator/neurips-2020-sevir) [[link]](https://sevir.mit.edu/) |
| WeatherBench2    | Google        | 2023.08        | -              | [[paper]](https://arxiv.org/abs/2308.15560) [[github]](https://github.com/google-research/weatherbench2) |
| CRA5             | Shanghai AI Lab        | 2024.05        | -              | [[paper]](https://arxiv.org/abs/2405.03376) [[github]](https://github.com/taohan10200/CRA5)| 
| WEATHER-5K       | Shanghai AI Lab        | 2024.06        | -              | [[paper]](https://arxiv.org/abs/2406.14399) [[github]](https://github.com/taohan10200/WEATHER-5K) |


## 📖 Papers

### WeatherBench
- WeatherBench: A benchmark dataset for data-driven weather forecasting [[pdf]](https://agupubs.onlinelibrary.wiley.com/doi/pdf/10.1029/2020MS002203)
- WeatherBench 2: A benchmark for the next generation of data-driven global weather models [[pdf]](https://arxiv.org/pdf/2308.15560)
### MetNet
- MetNet: A Neural Weather Model for Precipitation Forecasting (MetNet) [[pdf]](https://arxiv.org/pdf/2003.12140)
- Deep learning for twelve hour precipitation forecasts (MetNet-2) [[pdf]](https://www.nature.com/articles/s41467-022-32483-x.pdf)
- Deep Learning for Day Forecasts from Sparse Observations (MetNet-3) [[pdf]](https://arxiv.org/pdf/2306.06079)
### FourCastNet
- FourCastNet: A Global Data-driven High-resolution Weather Model using Adaptive Fourier Neural Operators (FourCastNet) [[pdf]](https://arxiv.org/pdf/2202.11214)
### Pangu-Weather
- Accurate medium-range global weather forecasting with 3D neural networks (Pangu-Weather) [[pdf]](https://www.nature.com/articles/s41586-023-06185-3.pdf)
### GraphCast
- Learning skillful medium-range global weather forecasting (GraphCast) [[pdf]](https://arxiv.org/pdf/2212.12794)
### ClimaX
- ClimaX: A foundation model for weather and climate (ClimaX) [[pdf]](https://arxiv.org/pdf/2301.10343)
### FengWu
- FengWu: Pushing the Skillful Global Medium-range Weather Forecast beyond 10 Days Lead (FengWu) [[pdf]](https://arxiv.org/pdf/2304.02948)
- FengWu-4DVar: Coupling the Data-driven Weather Forecasting Model with 4D Variational Assimilation [[pdf]](https://arxiv.org/pdf/2312.12455)
- Towards an end-to-end artificial intelligence driven global weather forecasting system [[pdf]](https://arxiv.org/pdf/2312.12462)
- FengWu-GHR: Learning the Kilometer-scale Medium-range Global Weather Forecasting [[pdf]](https://arxiv.org/pdf/2402.00059)
- ExtremeCast: Boosting Extreme Value Prediction for Global Weather Forecast [[pdf]](https://arxiv.org/pdf/2402.01295)
### FuXi
- FuXi: A cascade machine learning forecasting system for 15-day global weather forecast (FuXi) [[pdf]](https://arxiv.org/pdf/2306.12873)
- FuXi-Extreme: Improving extreme rainfall and wind forecasts with diffusion model (FuXi-Extreme) [[pdf]](https://arxiv.org/pdf/2310.19822)
- FuXi-S2S: An accurate machine learning model for global subseasonal forecasts [[pdf]](https://arxiv.org/pdf/2312.09926)
- Fuxi-DA: A Generalized Deep Learning Data Assimilation Framework for Assimilating Satellite Observations [[pdf]](https://arxiv.org/pdf/2404.08522)
- FuXi-ENS: A machine learning model for medium-range ensemble weather forecasting [[pdf]](https://arxiv.org/pdf/2405.05925)
### AI-GOMS
- AI-GOMS: Large AI-Driven Global Ocean Modeling System (AI-GOMS) [[pdf]](https://arxiv.org/pdf/2308.03152)
### XiHe
- XiHe: A Data-Driven Model for Global Ocean Eddy-Resolving Forecasting [[pdf]](https://arxiv.org/pdf/2402.02995)
### FNO
- Fourier Neural Operator with Learned Deformations for PDEs on General Geometries [[pdf]](https://arxiv.org/pdf/2207.05209)
- SFNO: Spherical Fourier Neural Operators: Learning Stable Dynamics on the Sphere [[pdf]](https://arxiv.org/pdf/2306.03838)
### Nowcast
- Earthformer: Exploring Space-Time Transformers for Earth System Forecasting [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2022/file/a2affd71d15e8fedffe18d0219f4837a-Paper-Conference.pdf)
- PreDiff: Precipitation Nowcasting with Latent Diffusion Models [[pdf]](https://arxiv.org/pdf/2307.10422)
- DGMR: Skilful precipitation nowcasting using deep generative models of radar [[odf]](https://www.nature.com/articles/s41586-021-03854-z.pdf)
- Skilful nowcasting of extreme precipitation with NowcastNet (NowcastNet) [[pdf]](https://www.nature.com/articles/s41586-023-06184-4.pdf)
- DiffCast: A Unified Framework via Residual Diffusion for Precipitation Nowcasting [[pdf]](https://arxiv.org/pdf/2312.06734)
- CasCast: Skillful High-resolution Precipitation Nowcasting via Cascaded Modelling [[pdf]](https://arxiv.org/pdf/2402.04290)
- Generalizing Weather Forecast to Fine-grained Temporal Scales via Physics-AI Hybrid Modeling [[pdf]](https://arxiv.org/pdf/2405.13796)
### Physics-AI
- Neural General Circulation Models for Weather and Climate [[pdf]](https://arxiv.org/pdf/2311.07222)
- ClimODE: Climate and Weather Forecasting with Physics-informed Neural ODEs [[pdf]](https://arxiv.org/pdf/2404.10024)
- Generalizing Weather Forecast to Fine-grained Temporal Scales via Physics-AI Hybrid Modeling [[pdf]](https://arxiv.org/pdf/2405.13796)
### Datasets
- WeatherBench: A benchmark dataset for data-driven weather forecasting [[pdf]](https://agupubs.onlinelibrary.wiley.com/doi/pdf/10.1029/2020MS002203)
- The ERA5 global reanalysis [[pdf]](https://rmets.onlinelibrary.wiley.com/doi/epdf/10.1002/qj.3803)
- SEVIR : A Storm Event Imagery Dataset for Deep Learning Applications in Radar and Satellite Meteorology [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2020/file/fa78a16157fed00d7a80515818432169-Paper.pdf)
- WeatherBench 2: A benchmark for the next generation of data-driven global weather models [[pdf]](https://arxiv.org/pdf/2308.15560)
- CRA5: Extreme Compression of ERA5 for Portable Global Climate and Weather Research via an Efficient Variational Transformer [[pdf]](https://arxiv.org/pdf/2405.03376)
- WEATHER-5K: A Large-scale Global Station Weather Dataset Towards Comprehensive Time-series Forecasting Benchmark [[pdf]](https://arxiv.org/pdf/2406.14399)
### More
- Can deep learning beat numerical weather prediction? [[pdf]](https://royalsocietypublishing.org/doi/pdf/10.1098/rsta.2020.0097?download=true)
- AtmoRep: A stochastic model of atmosphere dynamics using large scale representation learning [[pdf]](https://arxiv.org/pdf/2308.13280)
- Anthropogenic fingerprints in daily precipitation revealed by deep learning [[pdf]](https://www.nature.com/articles/s41586-023-06474-x.pdf)
- GenCast: Diffusion-based ensemble forecasting for medium-range weather [[pdf]](https://arxiv.org/pdf/2312.15796)
- KARINA: An Efficient Deep Learning Model for Global Weather Forecast [[pdf]](https://arxiv.org/pdf/2403.10555)
- SEEDS: Generative emulation of weather forecast ensembles with diffusion models [[pdf]](https://www.science.org/doi/pdf/10.1126/sciadv.adk4489)
- Aurora: A Foundation Model of the Atmosphere [[pdf]](https://arxiv.org/pdf/2405.13063)
- ORCA: A Global Ocean Emulator for Multi-year to Decadal Predictions [[pdf]](https://arxiv.org/pdf/2405.15412)
## 🚀 Code
- [ECMWF AI Models](https://github.com/ecmwf-lab/ai-models): AI-based weather forecasting models.
- [Skyrim](https://github.com/secondlaw-ai/skyrim): AI weather models united.
- [NVIDIA Earth2Mip](https://github.com/NVIDIA/earth2mip): Earth-2 Model Intercomparison Project (MIP) is a python framework that enables climate researchers and scientists to inter-compare AI models for weather and climate.
- [AI Models for All](https://github.com/darothen/ai-models-for-all): Run AI NWP forecasts hassle-free, serverless in the cloud!
- [OpenEarthLab](https://github.com/OpenEarthLab): OpenEarthLab, aiming at developing cutting-edge Spatiaotemporal Generation algorithms and promoting the development of Earth Science.
