# 来源与第三方许可

## Fe-Fool

来源：https://gitee.com/Kkoutianwu/Fe-Fool
作者页面名：拿笔小新；账号：Kkoutianwu。
根 LICENSE 明确提供 GNU GPL version 3。部分源码注明作者 wmy / wjx，已原样保留；本整理不声称这些源码属于本仓库创建者原创。

## YOLOv5

原目录 `code/yolov5` 带有独立 GPL-3.0 LICENSE，随源码保留。没有将其替换为当前其他版本许可。

## rembg

来源：https://github.com/danielgatis/rembg
`code/rembg/_version.py` 提供上游提交线索 `a11480edac808cafa8fa86673ef87a284756b519`（2022-08-06）。
该确切提交的 LICENSE.txt 已核实为 MIT，Copyright (c) 2020 Daniel Gatis：
https://github.com/danielgatis/rembg/blob/a11480edac808cafa8fa86673ef87a284756b519/LICENSE.txt

补回 `code/rembg/LICENSE.txt`。Fe-Fool 内文件可能经过修改，未声称与该提交逐字一致。`_version.py` 自带 Versioneer public-domain 声明，也已保留。模型、权重均未包含。

## 象棋引擎：Elephantfish / Sunfish

`code/robot/chess.py` 从 Fe-Fool 固定提交 `533c85b9a97fd99d0244442acf02b22939b9f073` 原样恢复，未修改代码。其子力表、Position / Searcher 结构及大量源码与 bupticybee 的 Elephantfish 对应；Elephantfish README 明确说明其基于 Thomas Ahle 的 Sunfish，并参考象眼子力价值表。这里说明代码来源，不声称本项目作者原创此引擎，也不声称已定位其精确历史引入提交。

- Elephantfish 源码与说明：https://github.com/bupticybee/elephantfish
- Elephantfish GNU GPL v3：https://github.com/bupticybee/elephantfish/blob/master/LICENSE.md
- Sunfish：https://github.com/thomasahle/sunfish
- Sunfish GNU GPL v3：https://github.com/thomasahle/sunfish/blob/master/LICENSE.md

上述 GPL v3 与 Fe-Fool 根 GPL v3 相容；许可证全文保留于根 `LICENSE`，原源码注释完整保留。2026-11-15 本次整理仅恢复缺失文件并补充来源、更新清单和限制说明，没有运行或测试棋类/硬件功能。

## 尚未确认而排除

CH341SER.EXE、素材/数据、音频、模型权重及校准文件的独立再分发授权未逐项确认，未包含。不使用根 GPL 文本替代第三方权利核查。
