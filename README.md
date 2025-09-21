# Resume Assets Repository

這個倉庫用於儲存履歷相關的圖片、影片和其他多媒體素材。

## 資料夾結構

```
resume-assets/
├── attendance-app/          # 企業級員工考勤管理系統
│   ├── screenshots/         # 應用截圖 (脫敏處理)
│   ├── demo-videos/         # 功能演示影片
│   └── architecture/        # 系統架構圖
├── facility-mgmt/           # 企業級設施管理平台
│   ├── screenshots/         # 介面截圖 (脫敏處理)
│   └── code-samples/        # 程式碼片段圖片
├── ai-project/              # 旗艦AI專案
│   ├── architecture/        # 架構設計圖
│   ├── performance/         # 性能指標圖表
│   └── demo/                # 技術展示
├── emergency-push/          # 跨域緊急救援推播系統
│   ├── code-samples/        # Laravel 程式碼片段
│   └── system-design/       # 系統設計圖
└── national-park-ios/       # 國家公園 iOS 應用
    ├── screenshots/         # App 截圖
    └── features/            # 功能展示圖
```

## 使用方式

在履歷 HTML 中引用圖片：
```html
<img src="https://raw.githubusercontent.com/your-username/resume-assets/main/attendance-app/screenshots/login-screen.png" alt="考勤系統登入畫面">
```

## 注意事項

- 所有截圖都需要脫敏處理，移除敏感資訊
- 影片檔案建議壓縮至合理大小
- 程式碼片段請移除商業邏輯部分
- 保持檔案命名規範和組織結構