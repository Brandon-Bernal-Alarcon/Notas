# R Language Notes

This section contains structured notes and practical examples for learning and using the R programming language, from basic concepts to data manipulation, visualization, and statistics.

---

## Index

## [1. Introduction](Notas/R_Language/Introduccion)

### [1.1 First Steps](Notas/R_Language/Introduccion/Primeros_Pasos.ipynb)

- Comments  
- Operations  
- Data types (`numeric`, `logical`)  
- Variables  
- `class()`  
- Creating vectors with `c()`  
- Naming vector elements with `names()`  
- Vector addition  
- `sum()`  
- Vector comparisons (`>`, `<`, `==`, etc.)  
- Indexing vectors with `[i]`

### [1.2 Matrices and Factors](Notas/R_Language/Introduccion/Matrices_y_Factores.ipynb)

- Creating matrices with `matrix()`  
- Naming rows and columns with `colnames()` and `rownames()`  
- Row and column sums: `rowSums()`, `colSums()`  
- Combining matrices with `cbind()` and `rbind()`  
- Matrix indexing  
- Categorical variables with `factor()`  
- Nominal and ordinal factors  
- `summary()`

### [1.3 Data Frames and Lists](Notas/R_Language/Introduccion/Data_Frame_y_Listas.ipynb)

- Creating `data.frame()`  
- `head()` and `tail()`  
- Data frame indexing (`$`, `[]`)  
- `subset()`  
- Creating lists with `list()`  
- Accessing list elements  

---

## [2. Intermediate](Notas/R_Language/Intermedio)

### [2.1 Conditionals and Functions](Notas/R_Language/Intermedio/Condicionales_y_Funciones.ipynb)

- Logical operators: `&`, `|`, `!`  
- `if` / `else` statements  
- Function structure in R  
- Using `help()` and `?`  
- Installing packages and `library()`

### [2.2 Loops and Dates](Notas/R_Language/Intermedio/Ciclos_y_Fechas.ipynb)

- `while` loop  
- `for` loop  
- Date functions: `now()` and `today()`  
- Date formatting and handling  

### [2.3 Pattern Matching and Apply Family](Notas/R_Language/Intermedio/Coincidencias_y_sapply.ipynb)

- Pattern matching with `grepl()` and `grep()`  
- Regular expressions: `^`, `\\.`, `$`  
- Replacement with `sub()` and `gsub()`  
- `lapply()`  
- `sapply()`  
- `vapply()`

---

## [3. Tidyverse – Introduction](Notas/R_Language/Tidyverse)

### [3.1 dplyr Basics](Notas/R_Language/Tidyverse/dplyr_basico.ipynb)

- `install.packages()`  
- `library()`  
- `gapminder()` dataset  
- `str()`  
- `filter()`  
- Pipes `%>%`  
- `arrange()`  
- `mutate()`

### [3.2 Summarize and Group By](Notas/R_Language/Tidyverse/Summarize_y_Group_by.ipynb)

- `summarize()`  
- `group_by()`  
- Introduction to `ggplot2`

### [3.3 Joining Tables with dplyr](Notas/R_Language/Tidyverse/Unir_tablas_con_dplyr.ipynb)

- `inner_join()`  
- `left_join()`  
- `right_join()`  
- `full_join()`  
- `anti_join()`  
- `semi_join()`  
- `replace_na()`  
- `bind_rows()`

---

## [4. Data Manipulation with dplyr and Strings](Notas/R_Language/Manipulacion_Dplyr)

### [4.1 Core dplyr Functions](Notas/R_Language/Manipulacion_Dplyr/Funciones_Dplyr.ipynb)

- `glimpse()`  
- `select()`  
- `arrange()`  
- `filter()` and `%in%`  
- `mutate()`  
- `count()`  
- `summarize()` and `group_by()`  
- `slice()` and variants  
- Column selection helpers (`:`, `contains()`, exclusions, etc.)  
- `rename()`  
- `relocate()`  
- `levels()` and `droplevels()`  
- `table()`

### [4.2 String Manipulation](Notas/R_Language/Manipulacion_Dplyr/Manipular_cadenas.ipynb)

- `str_remove()`  
- `mean()`  
- `replace()`  
- `duplicated()`  
- `distinct()`  
- `str_to_upper()`  
- `str_to_lower()`  
- `str_trim()`  
- `fct_collapse()`  
- `as.*()` functions (`as.numeric()`, `as.character()`, etc.)  
- `is.*()` functions (`is.numeric()`, `is.factor()`, etc.)

---

## [5. ggplot2](Notas/R_Language/ggplot2)

### [5.1 Visualization](Notas/R_Language/ggplot2/Visualización.ipynb)

- `ggplot2` library  
- Grammar of graphics  
- `aes()` mappings  
- Layers with `+`  
- `geom_*()` functions  
- Scatter plots: `geom_point()`  
- Line plots: `geom_line()`  
- Bar plots  
- Histograms  
- Boxplots  
- Titles and labels  
- `labs()`  
- Trend lines: `geom_smooth()`  
- Saving plots: `ggsave()`  
- Vertical and horizontal lines: `geom_vline()`, `geom_hline()`  
- Axis limits: `xlim()`, `ylim()`, `scale_x/y_continuous()`

---

## [6. Statistics](Notas/R_Language/Estadistica)

### [6.1 Basic Statistics](Notas/R_Language/Estadistica/Estadistica_Basica.ipynb)

- `mean()`  
- `median()`  
- `var()`  
- `sd()`  
- `quantile()`  
- `IQR()`  
- Outlier detection  
- Boxplots  
- Probability distributions:
  - Poisson  
  - Exponential  
  - Binomial  
  - Uniform  
  - Normal  
- Sampling  
- `cor()`  
- Linear regression  
