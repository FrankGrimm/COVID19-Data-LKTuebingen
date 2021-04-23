# COVID data Tuebingen


![plot](https://raw.githubusercontent.com/FrankGrimm/COVID19-Data-LKTuebingen/main/tuebingen_since_02_2021.png)

data: [Landratsamt Tübingen](https://www.kreis-tuebingen.de/17094149.html)

*Disclaimer*: This data is automatically extracted from the PDFs uploaded by the Landratsamt and published as-is. Should you encounter errors please open an issue in the repository.

data range: 2020-10-08 - 2021-04-22

Fields:
- region: Always 'LK Tübingen'
- city: The city or 'LK' for aggregate values
- date: Date according to the report the row was extracted from
- year/week/year_week: calendar information on the date
- infections: Total infections
- new_infections: New infections (not available for LK rows, should consistently refer to the 7 days since the last report)
