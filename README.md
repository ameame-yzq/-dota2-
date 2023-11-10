# Genesis: My First Dota 2 Data Analysis Project

## Introduction

The goal of this project is to conduct an in-depth analysis of my Dota 2 gameplay data to identify my strengths and weaknesses. By analyzing various statistical data, I aim to improve my gaming skills.

## Data Collection

The data was obtained from the OpenDota API, covering my personal match records.

## Data Preprocessing

The following preprocessing steps were applied to the data:

1. **Timestamp Conversion**: Converted match start times from Unix timestamps to a readable date format.
2. **Hero ID Mapping**: Converted hero IDs to hero names.
3. **Duration Formatting**: Converted match durations from seconds to "minutes:seconds" format.
4. **Team Tagging**: Tagged players' teams (Radiant or Dire) based on the `player_slot` field.
5. **Descriptive Field Conversion**: Converted `game_mode`, `lobby_type`, `skill`, and `leaver_status` fields to descriptive text.

## File Description

- `dota2_preprocessed.csv`: The preprocessed Dota 2 match data.

## Next Steps

The next steps involve further analysis of the data, such as win rate analysis, personal performance trends, hero selection analysis, etc.

---

# 万物起源：我的第一个 Dota 2 数据分析项目

## 简介

这个项目的目标是对我的 Dota 2 比赛数据进行深入分析，以便发现我的游戏强项和弱点。通过对不同统计数据的分析，我希望能够提升我的游戏技巧。

## 数据收集

数据是从 OpenDota API 获取的，涵盖了我的个人比赛记录。

## 数据预处理

对数据进行了以下预处理步骤：

1. **转换时间戳**：将比赛开始时间从 Unix 时间戳转换为可读的日期格式。
2. **英雄 ID 映射**：将英雄 ID 转换为英雄名称。
3. **持续时间格式化**：将比赛持续时间从秒转换为“分钟:秒”的格式。
4. **队伍标记**：根据 `player_slot` 字段标记玩家所在的队伍（光明方或黑暗方）。
5. **描述性字段转换**：将 `game_mode`、`lobby_type`、`skill` 和 `leaver_status` 字段转换为描述性文本。

## 文件说明

- `dota2_preprocessed.csv`：预处理后的 Dota 2 比赛数据。

## 后续步骤

接下来的步骤包括对数据进行更深入的分析，如胜率分析、个人表现趋势、英雄选择分析等。
