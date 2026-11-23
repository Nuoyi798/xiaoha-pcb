# NextPal 小狗 PCB（立创EDA 工程）

NextPal 四足机器人（小狗）的 PCB 版图与原理图工程文件，使用立创EDA（EasyEDA）编辑，工程版本 6.5.51。

## 文件说明

| 文件 | 说明 |
| --- | --- |
| `1-PCB_PCB_小狗new3.3.json` | PCB 版图工程（立创EDA，docType 3） |
| `1-Schematic_NEXTPAL.json` | 原理图工程（立创EDA，docType 1） |
| `README.txt` | 立创EDA 导出时附带的打开说明 |

## 如何打开

1. 打开 [立创EDA](https://lceda.cn/)（EasyEDA）编辑器。
2. 顶部菜单：**文件 → 打开 → 立创EDA...**（EasyEDA...）。
3. 选择对应的 `.json` 文件，即可在编辑器中打开，并可另存为工程。

> PCB 与原理图是两个独立文件，需要分别打开。

## 说明

- 本仓库仅包含 EDA 源文件，不包含 Gerber / 制造文件；如需打样，请在立创EDA 中打开工程后自行导出 Gerber。
- 相关项目：四足机器人控制代码 [Nuoyi798/xiaoha](https://github.com/Nuoyi798/xiaoha)

---

# NextPal Robot Dog PCB (EasyEDA Project)

PCB layout and schematic source files for the NextPal quadruped robot dog, created with EasyEDA (LCEDA), project version 6.5.51.

## Files

| File | Description |
| --- | --- |
| `1-PCB_PCB_小狗new3.3.json` | PCB layout project (EasyEDA, docType 3) |
| `1-Schematic_NEXTPAL.json` | Schematic project (EasyEDA, docType 1) |
| `README.txt` | Original export instructions |

## How to open

1. Open the [EasyEDA](https://easyeda.com/) / [LCEDA](https://lceda.cn/) editor.
2. Menu: **File → Open → EasyEDA...**
3. Select the `.json` file to open it, then save it as a project.

> The PCB and schematic are separate files and must be opened individually.

## Notes

- This repository contains EDA source files only. Gerber / fabrication files are not included; export them from EasyEDA when needed.
- Related project: robot control firmware [Nuoyi798/xiaoha](https://github.com/Nuoyi798/xiaoha)
