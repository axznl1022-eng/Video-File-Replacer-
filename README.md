# Video File Replacer
### 视频文件筛选与替换工具

---

## 项目简介 | Introduction

### 简体中文

Video File Replacer 是一款轻量级 Windows 视频文件管理工具，主要用于视频转码后的**文件体积比较、筛选、清理与替换**。

视频经过编码压缩后，并不一定会变得更小。受视频内容复杂程度、画面细节、噪点及编码参数等因素影响，部分转码成品可能无法有效降低文件体积，甚至出现**压缩后的文件比原始视频更大**的情况。

本工具通过**文件名自动匹配**原视频与对应的转码成品，并比较两者的**实际文件大小**，帮助用户筛选真正节省存储空间的文件，清理体积反而增大的转码成品，并将符合条件的较小文件**批量替换原视频**。

无需手动逐个查找文件、核对名称和比较体积，让大量转码文件的整理工作更加简单高效。

### English

Video File Replacer is a lightweight Windows utility designed to **compare, filter, clean up, and replace video files after encoding**.

Video encoding does not always result in smaller files. Depending on video complexity, visual details, noise, and encoding settings, some encoded outputs may fail to reduce file size effectively. In certain cases, an encoded file may even become **larger than the original**.

This tool automatically **matches original videos with their corresponding encoded outputs by filename**, then compares their **actual file sizes**. It helps users identify files that genuinely save storage space, clean up oversized encoded outputs, and **batch-replace original videos with smaller versions**.

It eliminates the need to manually locate files, check filenames, and compare file sizes one by one, making post-encoding file management faster and easier.

---

## 主要功能 | Key Features

### 1. 文件名自动匹配 | Automatic Filename Matching

根据**文件名**自动匹配原视频与对应的转码成品，**无需通过视频内容识别**。

Automatically matches original videos with their corresponding encoded outputs **based on filenames**, without analyzing video content.

### 2. 忽略末尾时间戳 | Ignore Timestamp Suffixes

支持忽略转码文件名末尾自动添加的**时间戳**，方便匹配原视频与转码成品。

Supports ignoring automatically appended **timestamp suffixes** in encoded filenames, making it easier to match original videos with their encoded outputs.

### 3. 文件体积比较 | File Size Comparison

自动比较原视频与转码成品的**实际文件大小**，判断转码后是否真正节省了存储空间。

Automatically compares the **actual file sizes** of original videos and encoded outputs to determine whether encoding has actually saved storage space.

### 4. 较大文件清理 | Oversized Output Cleanup

识别并清理**比原视频更大的转码文件**，避免无效成品继续占用存储空间。

Identifies and cleans up encoded files that are **larger than their original videos**, preventing inefficient outputs from taking up additional storage space.

### 5. 批量替换 | Batch Replacement

使用**体积更小的转码成品**批量替换对应的原视频。

**Batch-replaces original videos with smaller encoded outputs.**

### 6. 原片备份 | Original File Backup

支持在替换原视频前**创建原文件备份**，降低误操作造成素材丢失的风险。

Supports **backing up original videos before replacement** to reduce the risk of losing files due to accidental operations.

### 7. 灵活清理 | Flexible File Cleanup

支持将不需要的转码文件移入 **Windows 回收站**或**永久删除**。

Allows unwanted encoded files to be moved to the **Windows Recycle Bin** or **permanently deleted**.

### 8. 双语界面 | Bilingual Interface

支持在**简体中文与 English**之间切换界面语言。

Supports switching the interface language between **Simplified Chinese and English**.

---

## 文件匹配说明 | File Matching Notice

### 简体中文

文件匹配依赖**文件名**，而不是视频内容识别。请确保原视频与转码文件的命名对应关系正确，避免错误匹配。

工具支持忽略转码文件名末尾自动添加的时间戳，但仍建议在执行批量操作前检查匹配结果。

### English

File matching is based on **filenames**, not video content recognition. Please ensure that original videos and their encoded outputs have corresponding filenames to avoid incorrect matches.

The tool supports ignoring automatically appended timestamp suffixes in encoded filenames. However, it is still recommended to review the matching results before performing batch operations.

---
<img width="704" height="604" alt="Example of encoded video files with different file sizes" src="https://github.com/user-attachments/assets/972b5e56-5896-4799-927b-c8dd646b9b34" />


## 使用场景 | Use Case

### 简体中文

如图所示，视频经过编码压缩后，并不一定会变得更小。

由于视频内容复杂程度、画面细节、噪点以及编码参数等因素的影响，部分转码成品可能无法有效降低文件体积，甚至出现**压缩后的文件比原始视频更大**的情况。

面对大量转码文件，如果依靠人工逐个核对文件名、比较大小，再手动筛选和替换，不仅繁琐，也容易出错。

**Video File Replacer 正是为解决这一问题而设计。**

工具通过**文件名自动匹配**原视频与转码成品，比较双方的实际文件体积，筛选更小的转码文件，并清理体积反而增大的成品。对于符合条件的文件，还可以**批量替换原视频**，并支持备份原文件。

无需手动逐个查找、核对和替换，让转码后的文件整理更加高效。

### English

As shown in the image, video encoding does not always result in smaller files.

Depending on video complexity, visual details, noise, and encoding settings, some encoded outputs may fail to reduce file size effectively. In certain cases, an encoded file may even become **larger than the original**.

When dealing with large numbers of encoded videos, manually checking filenames, comparing file sizes, filtering outputs, and replacing originals can be tedious and error-prone.

**Video File Replacer is designed to solve this problem.**

The tool automatically **matches original videos with their encoded outputs based on filenames**, compares their actual file sizes, identifies smaller outputs, and cleans up files that have become larger. Eligible files can also be used to **batch-replace the corresponding originals**, with optional original-file backups.

No need to manually locate, compare, and replace files one by one. Make post-encoding file management faster and easier.


---
<img
  src="https://github.com/user-attachments/assets/937fa1a0-4ffd-4969-a389-99350b555432"
  alt="Video File Replacer"
  width="320"
/>
## 下载与启动 | Download & Launch

### 简体中文

下载项目文件并解压到任意文件夹，**无需安装，也无需编译 EXE**。

### 🚀 下载并解压后，双击以下文件即可启动：

# 🟨 `Run.bat`

**无需安装，无需编译，双击即可启动！**

程序启动后会直接打开图形化操作界面。按照界面提示选择原视频文件夹和转码输出文件夹，即可开始比较、筛选、清理和替换操作。

### English

Download the project files and extract them to any folder. **No installation or EXE compilation is required.**

### 🚀 Quick Start | Getting Started

# 🟧 `Run.bat`

**No installation required. Simply double-click to launch!**

The graphical interface will open directly. Select the original video folder and the encoded output folder, then follow the on-screen instructions to compare, filter, clean up, and replace files.

<img width="1718" height="1217" alt="Video File Replacer main interface" src="https://github.com/user-attachments/assets/5debff01-7c0d-44c0-b9a3-bed8f3aea1cc" />

---

## 界面语言切换 | Language Switching

### 简体中文

🌐 在**绿色圈出的地方**，可以切换界面语言，选择**简体中文或 English**。

### English

🌐 You can switch the interface language between **Simplified Chinese and English** at the location highlighted with the green circle.

<img width="1718" height="1217" alt="Language selection in Video File Replacer" src="https://github.com/user-attachments/assets/5debff01-7c0d-44c0-b9a3-bed8f3aea1cc" />

---

## 使用提醒 | Usage Notice

### 简体中文

本工具涉及文件清理和原视频替换操作。虽然提供了原文件备份等保护选项，但在实际使用中，仍可能因**文件匹配错误、程序异常或意外中断**等情况导致素材丢失。

建议首次使用时先用少量测试文件熟悉操作流程，执行批量清理或替换前仔细检查文件列表，并根据需要开启原文件备份。

**对于重要视频素材，建议始终保留独立备份。**

### English

This tool performs file cleanup and original video replacement. Although backup options are provided, unexpected issues such as **incorrect file matching, program errors, or interruptions** may still result in data loss.

For first-time use, it is recommended to test the tool with a small number of files, review the file list before batch cleanup or replacement, and enable original file backup when appropriate.

**For important video files, always keep a separate backup.**

---

## 项目特点 | Project Highlights

- 轻量级 Windows 工具，无需安装。
- 基于文件名匹配，不进行视频内容识别。
- 支持忽略转码文件名末尾的时间戳。
- 不依赖特定视频编码器或编码格式。
- 适用于 AV1、HEVC、H.264 等不同编码格式的转码成品。
- 通过文件体积比较，筛选真正更小的转码文件。
- 支持批量清理、批量替换及原文件备份。
- 提供简体中文与英文界面。

- Lightweight Windows utility with no installation required.
- Uses filename-based matching rather than video content recognition.
- Supports ignoring timestamp suffixes in encoded filenames.
- Not tied to any specific video encoder or codec.
- Compatible with encoded outputs from AV1, HEVC, H.264, and other video codecs.
- Identifies smaller encoded files through actual file size comparison.
- Supports batch cleanup, batch replacement, and original file backups.
- Provides Simplified Chinese and English interfaces.

---

## 许可证 | License

本项目的授权方式及使用条件请以仓库中的 `LICENSE` 文件为准。

Please refer to the `LICENSE` file in this repository for the applicable licensing terms and conditions.
