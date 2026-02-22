Unicode 17.0 + Emoji 17.0 Complete Dataset

Unicode 17.0 + Emoji 17.0 完整数据集

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg" alt="License"></a>
  <a href="https://github.com/SeekDeeply/unicode-17.0-complete-txt-tsv-dataset-with-emoji/releases"><img src="https://img.shields.io/github/v/release/SeekDeeply/unicode-17.0-complete-txt-tsv-dataset-with-emoji" alt="Release"></a>
  <a href="https://github.com/SeekDeeply/unicode-17.0-complete-txt-tsv-dataset-with-emoji/stargazers"><img src="https://img.shields.io/github/stars/SeekDeeply/unicode-17.0-complete-txt-tsv-dataset-with-emoji?style=social" alt="Stars"></a>
  <img src="https://img.shields.io/badge/Unicode-17.0-green" alt="Unicode 17.0">
  <img src="https://img.shields.io/badge/Emoji-17.0-orange" alt="Emoji 17.0">
  <img src="https://img.shields.io/badge/Data%20Size-16MB-lightgrey" alt="Data Size">
</p>

<p align="center">
  <b>🚀 The most complete, meticulously curated dataset for Unicode 17.0 and Emoji 17.0</b><br>
  <b>🚀 最完整、精心整理的 Unicode 17.0 和 Emoji 17.0 数据集</b>
</p>

---

📖 Overview | 概述

This repository provides the absolute most complete and professionally processed dataset for Unicode 17.0 and Emoji 17.0, directly derived from official UCD and Unihan sources.
It includes every allocated character, all control codes, 66 noncharacters, surrogate/private use boundaries, and the full Emoji 17.0 data (fully-qualified, minimally-qualified, unqualified, component).
Perfect for font developers, linguists, text processing researchers, and anyone who needs the ultimate Unicode reference.

本仓库提供 绝对最完整、专业处理 的 Unicode 17.0 和 Emoji 17.0 数据集，直接源自官方 UCD 和 Unihan 源文件。
包含 每一个已分配字符、所有控制符、66个非字符、代理区/私用区边界 以及 完整的 Emoji 17.0 数据（全限定、最小限定、未限定、组件）。
适用于字体开发者、语言学家、文本处理研究人员以及任何需要终极 Unicode 参考的人。

---

✨ Key Features | 核心特性

🏆 Feature 特点
✅ Absolute Completeness All allocated characters + control chars + 66 noncharacters + surrogate/private use boundaries ✅ 绝对完整 所有已分配字符 + 控制字符 + 66个非字符 + 代理区/私用区边界
✅ Latest Version Based on Unicode 17.0 (September 2025) ✅ 最新版本 基于 Unicode 17.0（2025年9月发布）
✅ Multiple Formats Machine‑readable TSV, human‑readable text, single‑line continuous string, block‑separated versions ✅ 多格式可用 机器可读 TSV、人类可读排版、单行连续字符串、按区块分行版
✅ Exact Classification Every character labeled with official block names (Chinese/English) ✅ 精确分类 每个字符按官方区块名标注（中英双语）
✅ Full Emoji Coverage All statuses: fully‑qualified, minimally‑qualified, unqualified, component ✅ Emoji 全覆盖 所有状态：fully‑qualified、minimally‑qualified、unqualified、component
✅ Pure Original Control characters preserved as‑is, no filtering, no modification ✅ 原汁原味 控制字符原样保留，无过滤，无修改

---

📁 Repository Structure | 仓库结构

```
unicode-17.0-complete-txt-tsv-dataset-with-emoji/
├── 📂 Unicode-17.0-Full-Dataset/           # Complete Unicode 17.0 character data
│   ├── Introduction.txt                     # Detailed documentation (bilingual)
│   ├── unicode_17_machine_raw.tsv           # Machine-readable TSV (142,610 rows)
│   ├── unicode_17_human_raw.txt              # Human-readable version (~570,000 lines)
│   ├── unicode_17_string_raw.txt             # Single-line continuous string (142,706 chars)
│   ├── unicode_17_string_blocked_raw.txt     # Block-separated string version
│   └── Unicode 17.0 Blocks.txt                # Official block list (Chinese/English)
│
├── 📂 Emoji-17.0-Full-Dataset/             # Complete Emoji 17.0 data
│   ├── Introduction.txt                     # Detailed documentation (bilingual)
│   ├── emoji_17_machine.tsv                  # Full dataset TSV (5,228 rows)
│   ├── emoji_17_human.txt                     # Full dataset human-readable
│   ├── emoji_17_single_machine.tsv            # Single-codepoint only TSV (1,400 rows)
│   ├── emoji_17_single_human.txt              # Single-codepoint human-readable
│   ├── emoji_17_single_string.txt             # Single-line string (1,400 chars)
│   └── emoji_17_single_string_annotated.txt   # Annotated single-line string
│
└── README.md                                 # This file
```

---

🚀 Quick Start | 快速开始

You can clone the repository or download the latest release:

你可以 克隆仓库 或 下载最新发布版本：

```bash
# Clone with HTTPS
git clone https://github.com/SeekDeeply/unicode-17.0-complete-txt-tsv-dataset-with-emoji.git

# Or download the latest release from:
https://github.com/SeekDeeply/unicode-17.0-complete-txt-tsv-dataset-with-emoji/releases
```

After obtaining the files, you can immediately start exploring the data using any text editor or programming language.

获取文件后，你可以立即使用任何文本编辑器或编程语言开始探索数据。

---

📊 Unicode 17.0 Dataset | Unicode 17.0 数据集

Located in /Unicode-17.0-Full-Dataset/ | 位于 /Unicode-17.0-Full-Dataset/

Three Versions for Different Needs | 三种版本满足不同需求

File Format Size Lines Best For
unicode_17_machine_raw.tsv TSV 5.2 MB 142,610 Program import / Database
unicode_17_human_raw.txt Text 10 MB ~570,000 Reading / Reference / Sharing
unicode_17_string_raw.txt Raw 512 KB 1 String processing / Testing
unicode_17_string_blocked_raw.txt Text ~512 KB ~330 Block-separated exploration

Sample | 样例

```text
# Machine-readable TSV:
        0000    <control>
一       4E00    CJK UNIFIED IDEOGRAPH-4E00
😀       1F600   grinning face

# Human-readable:
  U+0000
      ⚙️ Control Character
      📝 <control>

  U+4E00
      🈴 CJK Ideograph
      📝 CJK UNIFIED IDEOGRAPH-4E00
```

---

😊 Emoji 17.0 Dataset | Emoji 17.0 数据集

Located in /Emoji-17.0-Full-Dataset/ | 位于 /Emoji-17.0-Full-Dataset/

File Family | 文件家族

File Size Lines Purpose
emoji_17_machine.tsv 428 KB 5,228 Full dataset (machine)
emoji_17_human.txt 621 KB 26,358 Full dataset (human)
emoji_17_single_machine.tsv 61 KB 1,400 Single-codepoint (machine)
emoji_17_single_human.txt 111 KB ~5,600 Single-codepoint (human)
emoji_17_single_string.txt 5.4 KB 1 Single-line string
emoji_17_single_string_annotated.txt 5.6 KB ~20 Annotated string

Status Breakdown | 状态分布

Status Count Description
✅ fully-qualified 3,953 Official RGI Emoji
⚠️ minimally-qualified 174 Incomplete sequences
❓ unqualified 71 Text symbols
🧩 component 25 Modifier components
Total 5,223 All statuses included

---

🔧 Data Integrity | 数据完整性验证

All files include SHA-256 checksums for verification. You can verify with:

所有文件均附带 SHA-256 校验值，可用以下命令验证：

```bash
# Linux / macOS
sha256sum -c checksum_sha256.txt

# Windows (PowerShell)
Get-Content checksum_sha256.txt | ForEach-Object {
    $hash, $file = $_ -split '\s+',2
    if ((Get-FileHash $file -Algorithm SHA256).Hash -eq $hash.ToUpper()) {
        Write-Host "$file OK" -ForegroundColor Green
    } else {
        Write-Host "$file FAILED" -ForegroundColor Red
    }
}
```

---

📜 License | 许可证

This project is licensed under the Apache License 2.0 - see the LICENSE file for details.
The raw data is derived from the Unicode Character Database, which is subject to the Unicode Terms of Use.

本项目采用 Apache License 2.0 许可证 - 详见 LICENSE 文件。
原始数据源自 Unicode 字符数据库，其使用需遵守 Unicode 使用条款。

---

🙏 Acknowledgments | 致谢

· Unicode Consortium for the official UCD and Unihan data.
· All contributors who helped refine and verify this dataset.
· You, for your interest in high-quality Unicode data!
· Unicode 联盟 提供的官方 UCD 和 Unihan 数据。
· 所有帮助完善和验证本数据集的贡献者。
· 你，对高质量 Unicode 数据感兴趣的你！

---

📬 Contact & Contribution | 联系方式与贡献

· Found an issue? Open an issue
· Want to contribute? Fork the repository and submit a pull request.
· Questions? Reach out via GitHub Discussions.
· 发现问题？提交 Issue
· 想要贡献？Fork 仓库 并提交 Pull Request。
· 有疑问？通过 GitHub Discussions 联系。

---

<p align="center">
  <b>⭐ If you find this dataset valuable, please give it a star — it helps others discover it!</b><br>
  <b>⭐ 如果你觉得这个数据集有价值，欢迎给个星标 — 这能帮助更多人发现它！</b>
</p>
