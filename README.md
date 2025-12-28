# -Analysis-of-Traffic-Volume-Patterns-and-Influencing-Factors

## 项目简介
本项目基于 `Metro_Interstate_Traffic_Volume` 数据集，通过**标准数据可视化技术**（直方图、箱线图、散点图等），系统探究城市州际公路交通量的分布特征、时间规律及天气影响，挖掘「时间基础节奏+天气双向调节」的核心交通运行逻辑，为交通管理与调度提供数据支撑。

## 数据集说明
- 数据集名称：`Metro_Interstate_Traffic_Volume`
- 数据规模：48,204 条小时级观测记录，9 个核心属性
- 关键字段：`traffic_volume`（交通量）、`date_time`（时间戳）、`temp`（气温）、`rain_1h`（小时降雨量）、`weather_main`（天气类型）
- 数据来源：[[Kaggle Metro Interstate Traffic Volume](https://www.kaggle.com/datasets/robikscube/metro-interstate-traffic-volume)](https://archive.ics.uci.edu/dataset/492/metro+interstate+traffic+volume)

## 核心研究内容
1.  **分布分析**：揭示交通量双峰分布特征，对比不同天气下交通量的离散程度
2.  **关系探索**：探究气温、降水与交通量的关联，明确多变量间的相互影响
3.  **时序模式**：分析日内（早晚高峰）、周内（工作日/周末）、季节（春夏秋冬）的交通波动规律
4.  **对比分析**：多维度对比天气类型、温度区间、云量覆盖对交通量的影响

## 核心结论
1.  通勤行为是交通核心驱动：早7时、晚16时高峰显著，峰值具有强刚性，不受轻度天气干扰
2.  天气起双向调节作用：适宜天气（多云、晴朗）支撑高稳定交通量，极端天气/强降水显著抑制出行
3.  时间与天气协同塑造交通：时间决定交通基础节奏，天气调节流量强度，二者共同影响交通动态
