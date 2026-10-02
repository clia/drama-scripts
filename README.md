# drama-scripts

短剧脚本库，按剧名组织。

## 目录结构

```
scripts/
├── _模板/          # 新剧模板，复制后改名即可
└── <剧名>/
    ├── README.md   # 剧名、类型、集数、简介、角色
    ├── 第01集.md
    └── 第02集.md
```

## 新增一部短剧

1. `cp -r scripts/_模板 scripts/<剧名>`
2. 编辑 `README.md` 填写剧集信息
3. 按集添加 `第NN集.md`
