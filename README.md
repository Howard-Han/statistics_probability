# statistics_probability
統計相關應用 (機率分布模擬、抽籤工具、......)

網站：<https://howard-han.github.io/statistics_probability/>

## 工具

| 工具 | 路徑 | 說明 |
| --- | --- | --- |
| 機率分布探索器 | [`distributions/`](distributions/) | 14 種連續與離散分布的 PDF / PMF、CDF 與抽樣直方圖，參數調整時曲線平滑過渡 |

### 機率分布探索器

- 連續型：常態、t、卡方、指數、Gamma、Beta、均勻、對數常態、Weibull、Cauchy、F
- 離散型：二項、Poisson、幾何
- 檢視：機率密度、累積分布、抽樣直方圖（樣本數 100 / 1,000 / 10,000，可調組數、疊加理論曲線）
- 在圖上移動或拖曳可查看 f(x) 與 P(X ≤ x)
- 網址後加 `#分布代號` 可直接開啟指定分布，例如 `distributions/#poisson`

所有頁面皆為單一 HTML 檔，不需建置流程，直接由 GitHub Pages 提供。
