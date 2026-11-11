# archive

个人旧项目归档（2022-2023），由 3 个原独立仓库合并导入：

| 目录 | 原仓库 | 内容 |
|---|---|---|
| `Python_gadgets/` | qifiqi/Python_gadgets（2022，⭐1） | Python 模块小玩意 |
| `codebase/` | qifiqi/codebase（2022-23，⭐3） | 学习代码：python / web / java / go / 大数据 / 算法 |
| `website-books/` | qifiqi/website-books（2023） | Django 个人网站草稿 |

## 清洗说明

2026-11-11 导入时剔除（原仓库已删除，被剔文件未保留——均为可重新下载的数据集/二进制/生成物）：

- 全部 >5MB 文件 14 个（最大：img_src.csv 72MB、前端练习 zip 60MB、ffmpeg 静态包 39MB、Eclipse 工作区 37MB、数据集 csv 等）
- >1MB 的数据/媒体/二进制 27 个（约 78MB：csv/json/sql/zip/字体/压缩包/exe）
- `__pycache__`、`dist`、`build`、`target`、Eclipse 工作区等生成目录

明细见 [excluded-files.md](excluded-files.md)。原 git 提交历史未保留（导入快照）。
