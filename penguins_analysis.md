# Penguins 데이터셋 분석 보고서

이 보고서는 펭귄 데이터셋을 EDA하고 시각화를 통해 주요 패턴을 요약합니다.

## 생성된 그래프

![](figures/01_hist_bill_length_mm.png)

![](figures/02_hist_bill_depth_mm.png)

![](figures/03_hist_flipper_length_mm.png)

![](figures/04_hist_body_mass_g.png)

![](figures/05_hist_bill_ratio.png)

![](figures/box_body_mass_by_species.png)

![](figures/count_species.png)

![](figures/grouped_bar_sex_species.png)

![](figures/heatmap_correlation.png)

![](figures/jointplot_bill_length_body_mass.png)

![](figures/pairplot_numeric.png)

![](figures/regplot_bill_length_vs_depth.png)

![](figures/scatter_bill_length_depth_by_species.png)

![](figures/scatter_bill_vs_depth_size.png)

![](figures/stacked_bar_island_species.png)

![](figures/violin_bill_length_by_species.png)


## 교차표: species x island

| species   |   Biscoe |   Dream |   Torgersen |
|:----------|---------:|--------:|------------:|
| Adelie    |       44 |      55 |          47 |
| Chinstrap |        0 |      68 |           0 |
| Gentoo    |      119 |       0 |           0 |


## 피봇테이블: mean body_mass_g (island x species)

| island    |   Adelie |   Chinstrap |   Gentoo |
|:----------|---------:|------------:|---------:|
| Biscoe    |   3709.7 |       nan   |   5092.4 |
| Dream     |   3701.4 |      3733.1 |    nan   |
| Torgersen |   3708.5 |       nan   |    nan   |


## 간단 결론

- 데이터는 세 종(species) 간 체질 차이가 존재합니다.

- 섬(island)과 종(species) 분포는 상이합니다.
