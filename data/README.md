# 📦 Project Data

This directory documents the data sources used in the Video Game Market
Analysis Power BI project.

Raw source data is not included in this repository. The original public
dataset can be obtained from its source, while the personal gaming dataset
is documented separately below.

---

## 🎮 Video Game Sales & Engagement Data

**Source:**  
[Video-Game-Sales-and-Engagement-Analysis - Kaggle](https://www.kaggle.com/datasets/bimalkumarsaini/video-game-sales-and-engagement-analysis)

The primary video game market data used in the project came from the
Video Game Sales and Engagement Analysis dataset available on Kaggle.

Data from this source was used to create the `vgsales` and `games` tables
within the Power BI data model.

### Used For

The data supports analysis of:

- Video game sales
- Gaming platforms
- Game genres
- Individual game performance
- Historical trends
- Platform and genre comparisons

The dataset provides the foundation for the Nintendo, Xbox, PlayStation,
PC, and overall market analysis contained within the report.

---

## 👤 Personal Gaming Data

**Source:**  
[My Game Collection - TrueAchievements](https://www.trueachievements.com/gamer/curse1/gamecollection)

The Player One portion of the project uses data from my personal
TrueAchievements game collection.

This dataset provides a player-level perspective that complements the
broader video game market analysis.

### Used For

The personal gaming data supports metrics and analysis including:

- Gamerscore
- TrueAchievement Score
- Achievements earned
- Completion percentage
- Hours played
- Game library size
- Individual game statistics
- Lifetime player statistics

The Player One dashboard uses Power BI's interactive filtering to change
between lifetime and individual-game analysis. Selecting a game changes
the report context and updates the associated metrics for that title.

The **Clear Aggro** control removes the game selection and restores the
lifetime player statistics.

### Data Availability

The raw personal gaming dataset is not distributed as part of this
repository.

The original collection can be viewed through the TrueAchievements source
linked above.

---

## 📅 Date Table

A dedicated Date Table was created within the Power BI model to support
time-based analysis.

The Date Table provides the temporal dimension used by report visuals and
measures for analyzing video game performance over time.

---

## 🔄 Data Preparation

The source data was prepared and modeled within Power BI for use in the
report's calculations and visualizations.

The project combines video game market data, game metadata, personal gaming
statistics, and a dedicated Date Table. Relationships within the Power BI
model support the report's platform, genre, time-based, and player-level
analysis.

The original local source files used during development are not distributed
with this repository. Source provenance and links to the publicly available
data are documented above.

For additional information about the resulting model, see the
[data model diagram](../docs/data-model.png).
---

## 🔒 Data & Repository Policy

Raw copies of the source datasets are intentionally not stored in this
repository.

The public video game dataset can be obtained directly from its original
Kaggle source.

Personal gaming data is referenced for transparency but is not redistributed.

The completed analytical model and report are available in the Power BI
`.pbix` file included with this project.
