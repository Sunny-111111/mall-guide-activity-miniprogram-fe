# mall-guide-activity-miniprogram-fe
商场导购活动百事通小程序 - 纯前端版本，提供活动日历、筛选检索、活动详情、导购话术展示，无后端、静态 Mock 数据，适用于商场导购内部查询使用。
mall-guide-activity-miniprogram-fe/
├── docs/                    # 项目文档
├── miniprogram/             # 小程序前端核心代码
│   ├── pages/               # 所有页面
│   │   ├── index/           # 首页-活动日历+筛选
│   │   ├── search/          # 搜索页面
│   │   └── activityDetail/  # 活动详情页面
│   ├── mock/                # 前端模拟数据（唯一数据源）
│   │   └── activity.js
│   ├── utils/               # 工具方法
│   │   └── filter.js        # 筛选、搜索核心逻辑
│   ├── static/              # 静态图片资源
│   ├── app.js
│   ├── app.json
│   └── app.wxss
├── .gitignore               # Git忽略配置
└── README.md                # 项目说明文档
