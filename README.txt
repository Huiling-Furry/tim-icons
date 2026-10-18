TIM 图标资源库 (tim-icons)
============================================================

简介
------------------------------------------------------------
本仓库收录从 TIM 官方安装包中提取的全部图片资源，供静态资源 / CDN 使用。

来源
------------------------------------------------------------
- 应用：TIM（腾讯）
- 版本：tim_4.1.0.4050
- 提取方式：解包 APK 内的图片文件（png / jpg / jpeg / webp / gif），并按原路径结构保存。

内容统计
------------------------------------------------------------
- 图片总数：10668
    r/        10456   （资源目录；被 AndResGuard 混淆重命名为 "r"，
                        子目录与文件名均为缩短名，无实际语义）
    assets/     210
    junit/        2
- 整包压缩文件：tim_icons.zip（约 9.8 MB）

目录结构
------------------------------------------------------------
- r/       : 原 res/ 目录，存放资源图片（例如 r/aa/a.png）
- assets/  : assets 目录下的图片
- junit/   : 测试相关图片

访问方式（CDN）
------------------------------------------------------------
1) GitHub Pages
   https://huiling-furry.github.io/tim-icons/<路径>
   示例：https://huiling-furry.github.io/tim-icons/r/aa/a.png

2) jsDelivr（推荐，国内访问通常更快）
   https://cdn.jsdelivr.net/gh/Huiling-Furry/tim-icons@main/<路径>
   示例：https://cdn.jsdelivr.net/gh/Huiling-Furry/tim-icons@main/r/aa/a.png

3) GitHub raw（无缓存，有速率限制）
   https://raw.githubusercontent.com/Huiling-Furry/tim-icons/main/<路径>
   示例：https://raw.githubusercontent.com/Huiling-Furry/tim-icons/main/r/aa/a.png

整包下载
   https://cdn.jsdelivr.net/gh/Huiling-Furry/tim-icons@main/tim_icons.zip

注意事项
------------------------------------------------------------
- 文件名经过混淆，无可读语义；如需定位某个图标，建议按尺寸 / 用途比对。
- GitHub 限制：单文件 <= 100MB，仓库建议 < 1GB；
  Pages 站点建议 <= 1GB、月流量约 100GB，超出可能被限流。
- jsDelivr 与 Pages 均为免费静态托管，不适合大流量商业 CDN。
- 资源版权归腾讯所有，仅供个人学习 / 研究使用，请勿用于商业用途。

生成时间
------------------------------------------------------------
2026-10-18
