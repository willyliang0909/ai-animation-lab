# ai-animation-lab

## 檔案結構

```
/ai-animation-lab
│
├── /projects               # <--- 新增：存放不同的小說/動畫專案
│   ├── /project-a-ghost-hospital (專案 A：廢棄醫院)
│   │   ├── /assets         # 該專案專用的角色圖、場景圖 (LFS)
│   │   ├── /story          # 劇本、分鏡腳本 (.md)
│   │   ├── /audio          # 配音、專屬背景音樂
│   │   ├── /configs        # 該專案專用的工作流微調版本
│   │   └── /output         # 該專案的最終成品/半成品
│   │
│   └── /project-b-mountain-legend (專案 B：山中傳說)
│       ├── /assets
│       └── ...
├── workflows-base     # 核心工作流 (例如：通用轉場、高質量渲染)
└── README.md          # 專案總覽、風格定義與技術堆疊 (Model List)

```

## study
- 整理workflow
- google flow
- text to image
- image to video
- 學習調整與ai溝通方式


## timeline
2026-04-06 嘗試使用google flow建立影片 [project-horror-rootmate/lab1](/projects/project-horror-rootmate/workflow/lab1)

2026-04-08 開始建立影片，問題不少，主要是對流程不熟悉，需要的分鏡場景都未準備，另外語音也是個問題

2026-04-13 嘗試使用其他平台(zopia)，整體介面完善可靠，生成的影片也包含語音且與畫面匹配，
但免費額度不夠完成完整影片，需要再熟悉流程控制
[ai-kpi/lab1](/projects/ai-kpi/workflow/lab1/)

2026-04-14 參考zopia流程，重新嘗試[project-horror-rootmate/lab2](/projects/project-horror-rootmate/workflow/lab2)，
效果不如lab1，並且需要判斷對話速度，目前語速過快，整體畫面邏輯沒有lab1那麼好

2026-04-15 嘗試套用zopia流程到google平台，使用gemini規劃劇情、人物、場景、分鏡以及生成提示詞。
使用flow產生圖片，效果上使用nano banana pro一致性最好，風格及人物，但有數量限制
影片及語音還是個問題