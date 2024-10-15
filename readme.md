# Vietlot data

Data crawling from https://vietlott.vn/, results for products:
- [6/55](https://vietlott.vn/vi/trung-thuong/ket-qua-trung-thuong/655)
- [6/45](https://vietlott.vn/vi/trung-thuong/ket-qua-trung-thuong/645)
- [Keno](https://vietlott.vn/vi/trung-thuong/ket-qua-trung-thuong/winning-number-keno)
- [Max 3D](https://vietlott.vn/vi/trung-thuong/ket-qua-trung-thuong/max-3d)
- [Max 3D Pro](https://vietlott.vn/vi/trung-thuong/ket-qua-trung-thuong/max-3dpro)

- [Vietlot data](#vietlot-data)
  * [Predictions (just for testing, not a financial advice)](#predictions--just-for-testing--not-a-financial-advice-)
    + [random](#random)
  * [raw details 6/55](#raw-details-6-55)
  * [stats 6/55 all time](#stats-6-55-all-time)
  * [stats 6/55 -15d](#stats-6-55--15d)
  * [stats 6/55 -30d](#stats-6-55--30d)
  * [stats 6/55 -60d](#stats-6-55--60d)
  * [stats 6/55 -90d](#stats-6-55--90d)
- [Install](#install)
  * [via pip](#via-pip)
  * [cli](#cli)
    + [crawl](#crawl)
    + [Backfill missing data](#backfill-missing-data)


## Predictions (just for testing, not a financial advice)
These are backtest results for the strategies I have tested (just the abstract method at the moment, you can't predict lotery lol)

### random strategy
predicted: 20 / day (20 tickets perday or 200,000 vnd)
predicted corrected:
|       | date       | result                     | predicted               |
|------:|:-----------|:---------------------------|:------------------------|
| 14105 | 2020-02-11 | [4, 14, 18, 21, 32, 53, 2] | [21, 32, 34, 18, 14, 2] | 

## raw details 6/55 last 10 days
| date       |    id | result                       |   page | process_time               |
|:-----------|------:|:-----------------------------|-------:|:---------------------------|
| 2024-10-12 | 01099 | [29, 34, 35, 38, 50, 51, 37] |      0 | 2024-10-12 14:06:38.873281 |
| 2024-10-10 | 01098 | [4, 5, 6, 29, 32, 44, 53]    |      0 | 2024-10-10 14:08:31.717284 |
| 2024-10-08 | 01097 | [3, 7, 14, 17, 48, 50, 40]   |      0 | 2024-10-08 14:08:48.961350 |
| 2024-10-05 | 01096 | [2, 10, 17, 27, 50, 52, 18]  |      0 | 2024-10-05 14:05:33.835578 |
| 2024-10-03 | 01095 | [18, 21, 34, 40, 42, 53, 25] |      0 | 2024-10-03 14:08:22.354403 |
| 2024-10-01 | 01094 | [3, 18, 22, 41, 43, 44, 12]  |      0 | 2024-10-01 14:08:26.085082 |
| 2024-09-28 | 01093 | [2, 11, 13, 32, 41, 48, 15]  |      0 | 2024-09-28 14:05:31.520053 |
| 2024-09-26 | 01092 | [3, 18, 29, 39, 41, 49, 46]  |      0 | 2024-09-26 14:07:14.797039 |
| 2024-09-24 | 01091 | [1, 6, 11, 17, 24, 31, 43]   |      0 | 2024-09-24 14:07:30.604317 |
| 2024-09-21 | 01090 | [3, 8, 9, 22, 26, 55, 11]    |      0 | 2024-09-21 14:05:36.705265 |
## stats 6/55 all time
|   result |   count |    % | -   |   result |   count |    % | -   | result   | count   | %    |
|---------:|--------:|-----:|:----|---------:|--------:|-----:|:----|:---------|:--------|:-----|
|        1 |     152 | 1.98 |     |       21 |     134 | 1.74 |     | 41       | 158     | 2.05 |
|        2 |     131 | 1.7  |     |       22 |     159 | 2.07 |     | 42       | 137     | 1.78 |
|        3 |     153 | 1.99 |     |       23 |     156 | 2.03 |     | 43       | 154     | 2.0  |
|        4 |     123 | 1.6  |     |       24 |     138 | 1.79 |     | 44       | 148     | 1.92 |
|        5 |     141 | 1.83 |     |       25 |     130 | 1.69 |     | 45       | 136     | 1.77 |
|        6 |     122 | 1.59 |     |       26 |     126 | 1.64 |     | 46       | 150     | 1.95 |
|        7 |     122 | 1.59 |     |       27 |     130 | 1.69 |     | 47       | 139     | 1.81 |
|        8 |     150 | 1.95 |     |       28 |     125 | 1.63 |     | 48       | 148     | 1.92 |
|        9 |     152 | 1.98 |     |       29 |     143 | 1.86 |     | 49       | 147     | 1.91 |
|       10 |     132 | 1.72 |     |       30 |     120 | 1.56 |     | 50       | 141     | 1.83 |
|       11 |     143 | 1.86 |     |       31 |     141 | 1.83 |     | 51       | 154     | 2.0  |
|       12 |     152 | 1.98 |     |       32 |     150 | 1.95 |     | 52       | 146     | 1.9  |
|       13 |     135 | 1.76 |     |       33 |     142 | 1.85 |     | 53       | 148     | 1.92 |
|       14 |     135 | 1.76 |     |       34 |     155 | 2.02 |     | 54       | 134     | 1.74 |
|       15 |     129 | 1.68 |     |       35 |     146 | 1.9  |     | 55       | 141     | 1.83 |
|       16 |     123 | 1.6  |     |       36 |     132 | 1.72 |     |          |         |      |
|       17 |     127 | 1.65 |     |       37 |     123 | 1.6  |     |          |         |      |
|       18 |     144 | 1.87 |     |       38 |     133 | 1.73 |     |          |         |      |
|       19 |     135 | 1.76 |     |       39 |     126 | 1.64 |     |          |         |      |
|       20 |     151 | 1.96 |     |       40 |     150 | 1.95 |     |          |         |      |
## stats 6/55 -15d
|   result |   count |    % | -   |   result |   count |    % | -   | result   | count   | %    |
|---------:|--------:|-----:|:----|---------:|--------:|-----:|:----|:---------|:--------|:-----|
|        1 |       1 | 1.19 |     |       25 |       1 | 1.19 |     | 49       | 1       | 1.19 |
|        2 |       2 | 2.38 |     |       26 |       1 | 1.19 |     | 50       | 3       | 3.57 |
|        3 |       4 | 4.76 |     |       27 |       1 | 1.19 |     | 51       | 1       | 1.19 |
|        4 |       2 | 2.38 |     |       29 |       3 | 3.57 |     | 52       | 1       | 1.19 |
|        5 |       1 | 1.19 |     |       31 |       1 | 1.19 |     | 53       | 2       | 2.38 |
|        6 |       2 | 2.38 |     |       32 |       3 | 3.57 |     | 54       | 2       | 2.38 |
|        7 |       1 | 1.19 |     |       34 |       3 | 3.57 |     | 55       | 1       | 1.19 |
|        8 |       1 | 1.19 |     |       35 |       1 | 1.19 |     |          |         |      |
|        9 |       2 | 2.38 |     |       37 |       1 | 1.19 |     |          |         |      |
|       10 |       1 | 1.19 |     |       38 |       1 | 1.19 |     |          |         |      |
|       11 |       3 | 3.57 |     |       39 |       1 | 1.19 |     |          |         |      |
|       12 |       1 | 1.19 |     |       40 |       2 | 2.38 |     |          |         |      |
|       13 |       1 | 1.19 |     |       41 |       4 | 4.76 |     |          |         |      |
|       14 |       2 | 2.38 |     |       42 |       1 | 1.19 |     |          |         |      |
|       15 |       1 | 1.19 |     |       43 |       2 | 2.38 |     |          |         |      |
|       17 |       3 | 3.57 |     |       44 |       2 | 2.38 |     |          |         |      |
|       18 |       4 | 4.76 |     |       45 |       1 | 1.19 |     |          |         |      |
|       21 |       1 | 1.19 |     |       46 |       1 | 1.19 |     |          |         |      |
|       22 |       3 | 3.57 |     |       47 |       1 | 1.19 |     |          |         |      |
|       24 |       2 | 2.38 |     |       48 |       4 | 4.76 |     |          |         |      |
## stats 6/55 -30d
|   result |   count |    % | -   |   result |   count |    % | -   | result   | count   | %    |
|---------:|--------:|-----:|:----|---------:|--------:|-----:|:----|:---------|:--------|:-----|
|        1 |       1 | 1.19 |     |       25 |       1 | 1.19 |     | 49       | 1       | 1.19 |
|        2 |       2 | 2.38 |     |       26 |       1 | 1.19 |     | 50       | 3       | 3.57 |
|        3 |       4 | 4.76 |     |       27 |       1 | 1.19 |     | 51       | 1       | 1.19 |
|        4 |       2 | 2.38 |     |       29 |       3 | 3.57 |     | 52       | 1       | 1.19 |
|        5 |       1 | 1.19 |     |       31 |       1 | 1.19 |     | 53       | 2       | 2.38 |
|        6 |       2 | 2.38 |     |       32 |       3 | 3.57 |     | 54       | 2       | 2.38 |
|        7 |       1 | 1.19 |     |       34 |       3 | 3.57 |     | 55       | 1       | 1.19 |
|        8 |       1 | 1.19 |     |       35 |       1 | 1.19 |     |          |         |      |
|        9 |       2 | 2.38 |     |       37 |       1 | 1.19 |     |          |         |      |
|       10 |       1 | 1.19 |     |       38 |       1 | 1.19 |     |          |         |      |
|       11 |       3 | 3.57 |     |       39 |       1 | 1.19 |     |          |         |      |
|       12 |       1 | 1.19 |     |       40 |       2 | 2.38 |     |          |         |      |
|       13 |       1 | 1.19 |     |       41 |       4 | 4.76 |     |          |         |      |
|       14 |       2 | 2.38 |     |       42 |       1 | 1.19 |     |          |         |      |
|       15 |       1 | 1.19 |     |       43 |       2 | 2.38 |     |          |         |      |
|       17 |       3 | 3.57 |     |       44 |       2 | 2.38 |     |          |         |      |
|       18 |       4 | 4.76 |     |       45 |       1 | 1.19 |     |          |         |      |
|       21 |       1 | 1.19 |     |       46 |       1 | 1.19 |     |          |         |      |
|       22 |       3 | 3.57 |     |       47 |       1 | 1.19 |     |          |         |      |
|       24 |       2 | 2.38 |     |       48 |       4 | 4.76 |     |          |         |      |
## stats 6/55 -60d
|   result |   count |    % | -   |   result |   count |    % | -   | result   | count   | %    |
|---------:|--------:|-----:|:----|---------:|--------:|-----:|:----|:---------|:--------|:-----|
|        1 |       2 | 1.14 |     |       23 |       3 | 1.71 |     | 43       | 2       | 1.14 |
|        2 |       5 | 2.86 |     |       24 |       4 | 2.29 |     | 44       | 2       | 1.14 |
|        3 |       5 | 2.86 |     |       25 |       2 | 1.14 |     | 45       | 3       | 1.71 |
|        4 |       3 | 1.71 |     |       26 |       2 | 1.14 |     | 46       | 4       | 2.29 |
|        5 |       5 | 2.86 |     |       27 |       2 | 1.14 |     | 47       | 2       | 1.14 |
|        6 |       4 | 2.29 |     |       28 |       2 | 1.14 |     | 48       | 6       | 3.43 |
|        7 |       1 | 0.57 |     |       29 |       7 | 4    |     | 49       | 2       | 1.14 |
|        8 |       4 | 2.29 |     |       30 |       1 | 0.57 |     | 50       | 3       | 1.71 |
|        9 |       2 | 1.14 |     |       31 |       3 | 1.71 |     | 51       | 3       | 1.71 |
|       10 |       2 | 1.14 |     |       32 |       5 | 2.86 |     | 52       | 1       | 0.57 |
|       11 |       7 | 4    |     |       33 |       2 | 1.14 |     | 53       | 3       | 1.71 |
|       12 |       3 | 1.71 |     |       34 |       5 | 2.86 |     | 54       | 4       | 2.29 |
|       13 |       1 | 0.57 |     |       35 |       2 | 1.14 |     | 55       | 2       | 1.14 |
|       14 |       3 | 1.71 |     |       36 |       1 | 0.57 |     |          |         |      |
|       15 |       3 | 1.71 |     |       37 |       4 | 2.29 |     |          |         |      |
|       17 |       4 | 2.29 |     |       38 |       8 | 4.57 |     |          |         |      |
|       18 |       5 | 2.86 |     |       39 |       4 | 2.29 |     |          |         |      |
|       20 |       4 | 2.29 |     |       40 |       3 | 1.71 |     |          |         |      |
|       21 |       3 | 1.71 |     |       41 |       6 | 3.43 |     |          |         |      |
|       22 |       4 | 2.29 |     |       42 |       2 | 1.14 |     |          |         |      |
## stats 6/55 -90d
|   result |   count |    % | -   |   result |   count |    % | -   | result   | count   | %    |
|---------:|--------:|-----:|:----|---------:|--------:|-----:|:----|:---------|:--------|:-----|
|        1 |       3 | 1.13 |     |       22 |       6 | 2.26 |     | 42       | 5       | 1.88 |
|        2 |       7 | 2.63 |     |       23 |       6 | 2.26 |     | 43       | 4       | 1.5  |
|        3 |       5 | 1.88 |     |       24 |       4 | 1.5  |     | 44       | 4       | 1.5  |
|        4 |       3 | 1.13 |     |       25 |       4 | 1.5  |     | 45       | 4       | 1.5  |
|        5 |       5 | 1.88 |     |       26 |       3 | 1.13 |     | 46       | 7       | 2.63 |
|        6 |       5 | 1.88 |     |       27 |       3 | 1.13 |     | 47       | 2       | 0.75 |
|        7 |       3 | 1.13 |     |       28 |       4 | 1.5  |     | 48       | 9       | 3.38 |
|        8 |       5 | 1.88 |     |       29 |       9 | 3.38 |     | 49       | 2       | 0.75 |
|        9 |       4 | 1.5  |     |       30 |       3 | 1.13 |     | 50       | 4       | 1.5  |
|       10 |       4 | 1.5  |     |       31 |       3 | 1.13 |     | 51       | 6       | 2.26 |
|       11 |       7 | 2.63 |     |       32 |       8 | 3.01 |     | 52       | 1       | 0.38 |
|       12 |       5 | 1.88 |     |       33 |       3 | 1.13 |     | 53       | 5       | 1.88 |
|       13 |       2 | 0.75 |     |       34 |       9 | 3.38 |     | 54       | 6       | 2.26 |
|       14 |       5 | 1.88 |     |       35 |       4 | 1.5  |     | 55       | 6       | 2.26 |
|       15 |       3 | 1.13 |     |       36 |       2 | 0.75 |     |          |         |      |
|       16 |       2 | 0.75 |     |       37 |       6 | 2.26 |     |          |         |      |
|       17 |       6 | 2.26 |     |       38 |       9 | 3.38 |     |          |         |      |
|       18 |       7 | 2.63 |     |       39 |       7 | 2.63 |     |          |         |      |
|       20 |       6 | 2.26 |     |       40 |       9 | 3.38 |     |          |         |      |
|       21 |       5 | 1.88 |     |       41 |       7 | 2.63 |     |          |         |      |

# How project works
Since there are many people asked, I write this section.

## Schedule
The project is schedule automatically via Github Actions, run a script, fetch data and auto commit to Github. No server is required, I don't need to do anything.
Details in [workflow file](https://github.com/vietvudanh/vietlott-data/blob/dffb2bcdfa860a0dfc3f2e22e269e6978d478965/.github/workflows/crawl.yaml#L8)

## How crawling works
I just inspected network packages sent between browser and server to find out how data is fetched and replicated that in Python code. 

# Install
 
## via pip

```shell
pip install -i https://test.pypi.org/simple/ vietlott-data==0.1.3
```

## cli
project provides two cli

### crawl
```shell
Usage: vietlott-crawl [OPTIONS] PRODUCT

  crawl a product with a given run date or from/to index page 

Options:
  --run-date TEXT
  --index_from INTEGER  page index from run since we crawl by pagination the
                        pages
  --index_to INTEGER    page index from run since we crawl by pagination the
                        pages
  --help                Show this message and exit.
```

### Backfill missing data

```shell
Usage: vietlott-missing [OPTIONS] PRODUCT

  detect_missing_data and run if needed :param ctx: context :param product:
  product to run :param limit: number of pages to run :return:

Options:
  --limit INTEGER
  --help           Show this message and exit.
```

