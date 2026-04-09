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