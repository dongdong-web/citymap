# 走遍哈尔滨 · Every Street Harbin

一个纯静态的哈尔滨街道探索网页。随机抽取尚未打卡的城市道路，在 OSM 地图上显示道路形状，并可跳转高德搜索。

## GitHub Pages 部署
1. 新建 GitHub 仓库。
2. 上传本目录全部文件（必须保留 `data/harbin-roads.json`）。
3. Settings → Pages → Deploy from a branch → `main` / `/ (root)`。
4. 等待 GitHub 生成 Pages 地址。

## 数据与存档
- 路网：OpenStreetMap / Overpass，ODbL。
- 当前路网快照：2026-09-28。
- 打卡：浏览器 localStorage，不会同步到其他设备。

## 注意
第一版使用一个覆盖哈尔滨核心建成区的地理范围并进行启发式过滤；OSM 数据可能存在缺失、旧名称、重复/异常命名或不可步行路段。出行时以现场交通规则和安全条件为准。
