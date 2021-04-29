#### What is?

[`SuperExactTest shiny app`](https://network.shinyapps.io/SuperExactTest/) is a simple web-based interface to perform multi-set intersection analysis using [R/SuperExactTest](https://github.com/mw201608/SuperExactTest/).

#### Supertest

In the tab "`Supertest`", users can upload sets to perform SuperExactTest analysis and visualize the results. The input data file should be a tab ("\t") delimited text file, which organizes sets either in the columns (Set `Data shape direction` = Column; see [sample file 1](https://raw.githubusercontent.com/mw201608/SuperExactTest.shiny/main/Cancer_Column_Shape.txt)) or in the rows (Set `Data shape direction` = Row; see [sample file 2](https://raw.githubusercontent.com/mw201608/SuperExactTest.shiny/main/Cancer_Row_Shape.txt)). The first row in the "Column" shape direction format or first column in the "Row" shape direction format can be set names. In such cases, check `First element in each row is set name` or `First element in each column is set name`.

#### SET Distribution

In the tab "`SET Distribution`", users can specify set sizes, population size, and intersection size to compute the probability distribution of the intersections at the given setting.


#### Disclaimer

`SuperExactTest shiny app` and R package `SuperExactTest` are made available in the hope that they will be useful, but without any warranty to the extent permitted by applicable law.

#### Donate

If you find the `SuperExactTest` package and this shiny app to be userful, please `Sponsor` at my github page https://github.com/mw201608/SuperExactTest/ to support further development. Thanks!
