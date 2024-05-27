# 🌍 Awesome Large Weather Models (LWMs) | AI for Earth (AI4Earth) | AI for Science (AI4Science)
## 🧭 Guideline
A collection of articles on **Large Weather Models (LWMs)**, to make it easier to find and learn. 👏 Contributions to this hub are welcome!
- [🌍 Awesome Large Weather Models (LWMs) | AI for Earth (AI4Earth) | AI for Science (AI4Science)](#-awesome-large-weather-models-lwms--ai-for-earth-ai4earth--ai-for-science-ai4science)
  - [🧭 Guideline](#-guideline)
  - [🆕 LWMs News](#-lwms-news)
  - [🗂️ LWMs Lists](#️-lwms-lists)
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
    - [More](#more)
  - [🚀 Code](#-code)
  - [🧊 Meteorology](#-meteorology)
## 🆕 LWMs News
- 2024/05/20: Aurora: A Foundation Model of the Atmosphere [[link]](https://arxiv.org/abs/2405.13063);
- 2024/05/06: CRA5: Extreme Compression of ERA5 for Portable Global Climate and Weather Research via an Efficient Variational Transformer [[link]](https://arxiv.org/pdf/2405.03376);
- 2024/03/29: SEEDS: Generative emulation of weather forecast ensembles with diffusion models [[link]](https://www.science.org/doi/full/10.1126/sciadv.adk4489);
- 2024/03/13: KARINA: An Efficient Deep Learning Model for Global Weather Forecast [[link]](https://arxiv.org/abs/2403.10555);
- 2024/02/06: CasCast: Skillful High-resolution Precipitation Nowcasting via Cascaded Modelling [[link]](https://arxiv.org/pdf/2402.04290);
- 2024/02/04: XiHe, the first data-driven 1/12° resolution global ocean eddy-resolving forecasting model [[link]](https://arxiv.org/abs/2402.02995);
- 2024/02/02: ExtremeCast: Boosting Extreme Value Prediction for Global Weather Forecast [[link]](https://arxiv.org/pdf/2402.01295);
- 2024/01/28: FengWu-GHR, the first data-driven global weather forecasting model running at the 0.09∘ horizontal resolution [[link]](https://arxiv.org/abs/2402.00059);
- 2023/12/27: GenCast, a ML-based generative model for ensemble weather forecasting [[link]](https://arxiv.org/pdf/2312.15796);
- 2023/12/16: Four-Dimensional Variational (4DVar) assimilation, and develop an AI-based cyclic weather forecasting system, FengWu-4DVar [[link]](https://arxiv.org/abs/2312.12455);
- 2023/12/11: A unified and flexible framework that can equip any type of spatio-temporal models is proposed based on residual diffusion DiffCast [[link]](https://arxiv.org/abs/2312.06734);
- 2023/11/13: GCMs are physics-based simulators which combine a numerical solver for large-scale dynamics with tuned representations for small-scale processes such as cloud formation. [[link]](https://arxiv.org/abs/2311.07222);
- 2023/12/13: Fuxi is open source [[link]](https://github.com/tpys/ai-models-fuxi);
- 2023/11/14: GraphCast published in Science [[link]](https://github.com/tpys/ai-models-fuxi)；
- 2023/09/14: Pangu-Weather published in Nature [[link]](https://www.nature.com/articles/s41586-023-06185-3)；
- 2023/08/25: ClimaX published in ICML 2023 [[link]](https://openreview.net/forum?id=TowCaiz7Ui)；
## 🗂️ LWMs Lists
| LWM name     | From            | Date(1st) | Publication | Links                                     |
| ------------- | --------------- | ---------------- | -------------- | ------------------------------------------------------------ |
| MetNet   | Google        | 2020.03        | -              | [[paper]](https://arxiv.org/abs/2003.12140) [[github]](https://github.com/openclimatefix/metnet) |
| FourCastNet   | NVIDIA        | 2022.02          | -              | [[paper]](https://arxiv.org/abs/2202.11214) [[github]](https://github.com/NVlabs/FourCastNet) |
| MetNet-2   | Google        | 2022.09        | Nature Communications | [[paper]](https://www.nature.com/articles/s41467-022-32483-x) [[github]](https://github.com/openclimatefix/metnet)  |
| Pangu-Weather | Huaiwei         | 2022.11          | Nature         | [[paper]](https://www.nature.com/articles/s41586-023-06185-3) [[github]](https://github.com/198808xc/Pangu-Weather) |
| GraphCast     | DeepMind        | 2022.12          | Science        | [[paper]](https://www.science.org/doi/10.1126/science.adi2336) [[github]](https://github.com/google-deepmind/graphcast) |
| ClimaX        | Microsoft       | 2023.01          | ICML 2023      | [[paper]](https://arxiv.org/pdf/2301.10343) [[github]](https://github.com/microsoft/ClimaX) |
| Fengwu        | Shanghai AI Lab | 2023.04          | -              | [[paper]](https://arxiv.org/abs/2304.02948) [[github]](https://github.com/OpenEarthLab/FengWu) |
| MetNet-3  | Google        | 2023.06        | - | [[paper]](https://arxiv.org/abs/2306.06079)  | 
| Fuxi          | Fudan           | 2023.06          | -              | [[paper]](https://arxiv.org/abs/2306.12873) [[github]](https://github.com/tpys/ai-models-fuxi) |
| NowcastNet   | Tsinghua        | 2023.07         | Nature      | [[paper]](https://www.nature.com/articles/s41586-023-06184-4) |
| AI-GOMS       | Tsinghua        | 2023.08          | -              | [[paper]](https://arxiv.org/abs/2308.03152)                  |
| Fuxi-Extreme    | Fudan           | 2023.10        | -              | [[paper]](https://arxiv.org/abs/2310.19822) |
| NeuralGCM    | DeepMind           | 2023.11        | -              | [[paper]](https://arxiv.org/abs/2311.07222) |
| FengWu-4DVar    | Tsinghua           | 2023.12        | ICML 2024         | [[paper]](https://arxiv.org/abs/2312.12455) |
| GenCast    | DeepMind           | 2023.12        | -              | [[paper]](https://arxiv.org/pdf/2312.15796) |
| DiffCast    | HITsz    | 2023.12        | CVPR 2024              | [[paper]](https://arxiv.org/abs/2312.06734) | 
| FengWu-GHR    | Shanghai AI Lab           | 2024.01        | -              | [[paper]](https://arxiv.org/abs/2402.00059) |
| ExtremeCast   | Shanghai AI Lab           | 2024.02        | -              | [[paper]](https://arxiv.org/pdf/2402.01295) [[github]](https://github.com/black-yt/ExtremeCast)| 
| XiHe    | NUDT           | 2024.02        | -              | [[paper]](https://arxiv.org/abs/2402.02995) [[github]](https://github.com/Ocean-Intelligent-Forecasting/XiHe-GlobalOceanForecasting)| 
| CasCast    | Shanghai AI Lab           | 2024.02        | ICML 2024              | [[paper]](https://arxiv.org/pdf/2402.04290) | 
| KARINA    | KARINA           | 2024.03        | -             | [[paper]](https://arxiv.org/abs/2403.10555) | 
| SEEDS    | Google           | 2024.03        | Science Advances              | [[paper]](https://www.science.org/doi/full/10.1126/sciadv.adk4489) | 
| CRA5     | Shanghai AI Lab  | 2024.05        | -              | [[paper]](https://arxiv.org/pdf/2405.03376) [[github]](https://github.com/taohan10200/CRA5)| 
| Aurora     | Microsoft  | 2024.05        | -              | [[paper]](https://arxiv.org/abs/2405.13063)| 



## 📖 Papers

### WeatherBench
- WeatherBench: A benchmark dataset for data-driven weather forecasting [[paper]](https://agupubs.onlinelibrary.wiley.com/doi/pdf/10.1029/2020MS002203)
- WeatherBench 2: A benchmark for the next generation of data-driven global weather models [[paper]](https://arxiv.org/pdf/2308.15560)
### MetNet
- MetNet: A Neural Weather Model for Precipitation Forecasting (MetNet) [[paper]](https://arxiv.org/pdf/2003.12140)
- Deep learning for twelve hour precipitation forecasts (MetNet-2) [[paper]](https://www.nature.com/articles/s41467-022-32483-x%3C/p%3E)
- Deep Learning for Day Forecasts from Sparse Observations (MetNet-3) [[paper]](https://arxiv.org/pdf/2306.06079)
### FourCastNet
- FourCastNet: A Global Data-driven High-resolution Weather Model using Adaptive Fourier Neural Operators (FourCastNet) [[paper]](https://arxiv.org/pdf/2202.11214)
### Pangu-Weather
- Accurate medium-range global weather forecasting with 3D neural networks (Pangu-Weather) [[paper]](https://www.nature.com/articles/s41586-023-06185-3)
### GraphCast
- Learning skillful medium-range global weather forecasting (GraphCast) [[paper]](https://www.science.org/doi/full/10.1126/science.adi2336)
### ClimaX
- ClimaX: A foundation model for weather and climate (ClimaX) [[paper]](https://arxiv.org/pdf/2301.10343)
### FengWu
- FengWu: Pushing the Skillful Global Medium-range Weather Forecast beyond 10 Days Lead (FengWu) [[paper]](https://arxiv.org/pdf/2304.02948)
- FengWu-4DVar: Coupling the Data-driven Weather Forecasting Model with 4D Variational Assimilation [[paper]](https://arxiv.org/pdf/2312.12455)
- FengWu-GHR: Learning the Kilometer-scale Medium-range Global Weather Forecasting [[paper]](https://arxiv.org/pdf/2402.00059)
- ExtremeCast: Boosting Extreme Value Prediction for Global Weather Forecast [[paper]](https://arxiv.org/pdf/2402.01295)
### FuXi
- FuXi: A cascade machine learning forecasting system for 15-day global weather forecast (FuXi) [[paper]](https://arxiv.org/pdf/2306.12873)
- FuXi-Extreme: Improving extreme rainfall and wind forecasts with diffusion model (FuXi-Extreme) [[paper]](https://arxiv.org/abs/2310.19822)
### AI-GOMS
- AI-GOMS: Large AI-Driven Global Ocean Modeling System (AI-GOMS) [[paper]](https://arxiv.org/pdf/2308.03152)
### XiHe
- XiHe: A Data-Driven Model for Global Ocean Eddy-Resolving Forecasting [[paper]](https://arxiv.org/abs/2402.02995)
### FNO
- Fourier Neural Operator with Learned Deformations for PDEs on General Geometries [[paper]](https://arxiv.org/pdf/2207.05209)
- SFNO: Spherical Fourier Neural Operators: Learning Stable Dynamics on the Sphere [[paper]](https://arxiv.org/pdf/2306.03838)
### Nowcast
- Earthformer: Exploring Space-Time Transformers for Earth System Forecasting [[paper]](https://proceedings.neurips.cc/paper_files/paper/2022/file/a2affd71d15e8fedffe18d0219f4837a-Paper-Conference.pdf)
- PreDiff: Precipitation Nowcasting with Latent Diffusion Models [[paper]](https://arxiv.org/pdf/2307.10422)
- DGMR: Skilful precipitation nowcasting using deep generative models of radar [[paper]](https://www.nature.com/articles/s41586-021-03854-z)
- Skilful nowcasting of extreme precipitation with NowcastNet (NowcastNet) [[paper]](https://www.nature.com/articles/s41586-023-06184-4)
- DiffCast: A Unified Framework via Residual Diffusion for Precipitation Nowcasting [[paper]](https://arxiv.org/abs/2312.06734)
- CasCast: Skillful High-resolution Precipitation Nowcasting via Cascaded Modelling [[paper]](https://arxiv.org/pdf/2402.04290)
### More
- Can deep learning beat numerical weather prediction? [[paper]](https://royalsocietypublishing.org/doi/pdf/10.1098/rsta.2020.0097?download=true)
- AtmoRep: A stochastic model of atmosphere dynamics using large scale representation learning [[paper]](https://arxiv.org/abs/2308.13280)
- Anthropogenic fingerprints in daily precipitation revealed by deep learning [[paper]](https://www.nature.com/articles/s41586-023-06474-x)
- Neural General Circulation Models [[paper]](https://arxiv.org/abs/2311.07222)
- GenCast: Diffusion-based ensemble forecasting for medium-range weather [[paper]](https://arxiv.org/pdf/2312.15796)
- KARINA: An Efficient Deep Learning Model for Global Weather Forecast [[paper]](https://arxiv.org/abs/2403.10555)
- SEEDS: Generative emulation of weather forecast ensembles with diffusion models [[paper]](https://www.science.org/doi/full/10.1126/sciadv.adk4489);
- CRA5: Extreme Compression of ERA5 for Portable Global Climate and Weather Research via an Efficient Variational Transformer [[paper]](https://arxiv.org/pdf/2405.03376);
- Aurora: A Foundation Model of the Atmosphere [[paper]](https://arxiv.org/abs/2405.13063);
## 🚀 Code
- [ECMWF AI Models](https://github.com/ecmwf-lab/ai-models)
- [Skyrim](https://github.com/secondlaw-ai/skyrim)
- [NVIDIA Earth2Mip](https://github.com/NVIDIA/earth2mip)
- [AI Models for All](https://github.com/darothen/ai-models-for-all)

## 🧊 Meteorology
- IPCC
- IMO | WMO
- ECMWF

