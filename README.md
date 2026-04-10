# Tehranplume
# Tehran Air Strike Pollutant Diffusion Prediction System

This project implements real-time visual prediction of pollutant diffusion in Tehran under air strike scenarios based on the **Gaussian Plume Model**, integrating real-time meteorological data and interactive map visualization. Users can generate a pollutant plume diffusion map by simply clicking on a geographic location.

## Project Introduction

This system is designed for simulating and analyzing pollutant diffusion caused by air strikes in urban Tehran. It uses the classic Gaussian Plume Model for diffusion calculation, combined with real-time meteorological data to improve prediction accuracy. The interactive map visualizes the pollutant spread and concentration distribution, providing support for emergency analysis and research.

## Core Technologies & Data Sources

1. **Meteorological Data**: Real-time wind speed and direction are obtained via the **Open-Meteo API**, providing dynamic input for the diffusion model.
2. **Map Visualization**: Uses **Carto Light** basemap for a clean and clear geographic visualization base.
3. **Model Parameters**:
   - Initial source concentration: 0.08 kg/m³
   - Diffusion time: 1 hour
4. **Deployment**: Hosted online through **Vercel** for direct browser access.

## Online Usage

Available at:
🌐 https://tehranplume260405.vercel.app

### How to Use

1. Open the link above and wait for the Tehran map to load.
2. Click on the map to select the impact location.
3. The system automatically fetches real-time wind data and runs the Gaussian Plume Model.
4. The pollutant plume visualization is displayed immediately.

### Access Notice

This project is hosted on overseas servers. It can be accessed directly outside mainland China; users in mainland China may need a **VPN** for normal use.

## Features

- Real-time wind data from Open-Meteo API
- Clean Carto light basemap for Tehran region
- One-hour pollutant diffusion calculation using Gaussian Plume Model
- Interactive point-and-click geographic selection
- Lightweight web application, no local setup required

## Tech Stack

- Frontend map rendering: Web map framework
- Data API: Open-Meteo
- Diffusion model: Gaussian Plume Model
- Deployment: Vercel

## Disclaimer

1. This project is a **simulation tool** for research and emergency reference only. Results are based on theoretical calculations and do not reflect real-world outcomes.
2. Dependent on Open-Meteo API availability; service interruptions may affect performance.
3. Tuned for the Tehran region; parameters must be adjusted for other areas.


# 德黑兰空袭污染物扩散预测系统

本项目基于高斯烟羽模型，实现德黑兰地区空袭场景下污染物扩散的实时可视化预测，集成气象数据获取与地图渲染功能，可通过点击坐标快速生成污染物烟羽扩散图。


## 核心技术与数据来源

1. **气象数据获取**：调用 Open-Meteo API，实时获取目标区域风速、风向数据，为污染物扩散模型提供动态气象参数。
2. **地图底图加载**：集成 Carto 浅色地图，提供清晰、简洁的地理可视化基底，提升地图查看体验。
3. **扩散模型参数**：采用高斯烟羽模型，预设核心参数：
   - 原点污染物浓度：0.08kg/立方米
   - 污染物扩散时长：1小时
4. **项目部署**：通过 Vercel 完成线上部署，实现网页端直接访问使用。

## 在线使用

项目已部署至线上，访问地址：  
🌐 https://tehranplume260405.vercel.app

### 使用方式

1. 打开上述在线链接，加载德黑兰地区地图；
2. 在地图上点击选择空袭发生坐标位置；
3. 系统自动结合实时风速、风向数据，调用高斯烟羽模型计算；
4. 页面实时生成并展示污染物扩散烟羽图。

### 访问须知

该项目部署于海外服务器，中国大陆地区需借助VPN方可正常访问使用，境外网络可直接流畅使用。

## 项目功能

- 实时获取Open-Meteo气象API数据，动态更新风速、风向参数
- 加载Carto浅色底图，实现德黑兰区域地理信息可视化
- 基于高斯烟羽模型，快速计算空袭后污染物1小时扩散规律
- 交互式坐标选择，一键生成污染物扩散烟羽可视化效果图
- 轻量级网页部署，无需本地配置环境，直接在线操作

## 技术栈

- 前端地图渲染：基于Web地图开发框架
- 数据请求：Open-Meteo API 接口调用
- 扩散计算：高斯烟羽模型算法实现
- 部署平台：Vercel

## 注意事项

1. 本项目仅为污染物扩散模拟预测，结果基于高斯烟羽模型理论计算，仅供学习研究与应急参考，不代表实际灾害扩散结果；
2. 气象数据依赖Open-Meteo API服务，若接口异常可能影响预测结果；
3. 项目仅针对德黑兰地区进行模拟，地理范围与模型参数适配该区域，如需适配其他地区需调整相关参数。
