# wcc_analysis

Lichess page documentation: https://lichess.org/page/world-championships

Each WCC has a study, studies are fetched using: https://lichess.org/api#operation/studyAllChaptersPgn

Source PGNs are found in /analysed_pgns

Analysis.py for extracting analysis and exporting as JSON - sample export is found in analysis.json

Analysiscsv.py for extracting analysis and exporting as CSV - sample export is found in analysis.csv

Visualize.py takes in CSV and makes some charts, examples are shown below.

![Barplot](https://github.com/Sebastien32/wcc_analysis/blob/master/barplot.png)
![Boxenplot](https://github.com/Sebastien32/wcc_analysis/blob/master/boxenplot.png)
![Boxplot](https://github.com/Sebastien32/wcc_analysis/blob/master/boxplot.png)
![Stripplot](https://github.com/Sebastien32/wcc_analysis/blob/master/stripplot.png)
![Violinplot](https://github.com/Sebastien32/wcc_analysis/blob/master/violinplot.png)
![Scatterplot](https://github.com/Sebastien32/wcc_analysis/blob/master/scatterplot.png)
![Regplot](https://github.com/Sebastien32/wcc_analysis/blob/master/regplot.png)
![Lmplot](https://github.com/Sebastien32/wcc_analysis/blob/master/lmplot.png)
![Gamelengthplot](https://github.com/Sebastien32/wcc_analysis/blob/master/gamelengthscatterplot.png)
