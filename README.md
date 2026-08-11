# Global-Olympics-Medal-Analysis
An interactive Tableau Story analyzing global Olympic medal data, covering country performance, gender medal distribution, top individual athletes, sport dominance by nation, and medal composition by sport. Includes a full technical report with a live Tableau Public dashboard and data-backed observations.

The five highest-value athletes in this dataset are separated by a single point of medal value. The two highest-value countries are separated by more than fifty. Medal success does not concentrate the same way at every level, and that gap is what this project set out to explain.

**Overview**

I analyzed global Olympic medal data, tracking country, athlete, gender, sport, medal type, and medal value, then built an interactive Tableau Story around six core visualizations. The result is a dashboard that breaks Olympic success down by country, gender, individual athlete, sport, and geography, rather than treating medal count as one flat number.

**The Problem**

Medal tables usually stop at a country ranking. That leaves out almost everything interesting: which individual athletes are actually driving a country's total, which sports generate the most volume versus the most prestige, and which nations specialize so heavily in one discipline that it defines their entire Olympic identity. This dashboard was built to answer those questions directly, and in the process, it also surfaced two data quality issues worth fixing before the story is considered fully complete.

**What the Dashboard Tracks**

<img width="1292" height="673" alt="Global Olympics Medal Dashboard" src="https://github.com/user-attachments/assets/68963889-dc1e-4164-bceb-d56fc3f6d2ef" />


The dashboard combines six visualizations, country medal performance, gender medal distribution, top athletes by medal value, sport dominance by country on a world map, an Olympic Games year comparison, and medal composition by sport, filterable by medal value, medal type, and sport.

Interactive Version: View the live, interactive dashboard on Tableau Public: https://public.tableau.com/views/GlobalOlympicsMedalOverview/Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

**What I Found**

The United States of America leads every other country by a clear margin, with a total medal value visibly exceeding 200, well ahead of the People's Republic of China's roughly 150. That gap alone places the USA in a performance tier of its own. Japan and ROC followed as a closely matched second tier, both in the 85 to 90 range, a pairing close enough to serve as a natural head-to-head benchmark.

Individual athlete performance told a different kind of story. Caeleb Dressel led all athletes with a medal value of 9, but four other athletes, Alexander Bolshunov, Ariane Titmus, Ailing Eileen Gu, and Marte Olsbu Roeiseland, sat just one point behind at 8 each. At the elite individual level, this dataset shows genuine competition at the top rather than one athlete running away with it.

Sport-level data reinforced how unevenly medal volume is generated. Athletics produced more medal output than the next two sports combined, a reflection of just how many individual events fall under that one category. Geographically, specific countries showed clear sport specializations, Short Track Speed Skating with Korea and Canada, Cross Country Skiing with Sweden, Artistic Gymnastics with Brazil and Italy, though 16 countries remain uncategorized in the current dataset, a gap worth investigating further.

Two things surfaced during this analysis that go beyond straightforward findings. The Gender Medal Distribution chart shows a visually balanced split between Men and Women across medal types, but currently lacks explicit numeric labels to confirm that balance precisely. And the Olympic Games (2020 vs 2022) chart, intended to compare performance across two Games years, currently shows every bubble labeled 2020, a data or filtering issue worth resolving before that comparison can be trusted.

**Why It Matters**

A flat medal count tells you who won. Breaking it down by country, athlete, sport, and geography tells you why, and in this case, it also surfaced two specific data issues that a surface-level look at the dashboard would have missed entirely.

**Tools Used**

Tableau (Story Points, Interactive Dashboard Design, Geographic Mapping, Treemap Visualization)

**Full Details**

The complete technical report and the raw dataset are available here: https://drive.google.com/drive/folders/1mkY6_k5Z9hrfE7tYkgzQbAGn_d8pgJBo?usp=drive_link
