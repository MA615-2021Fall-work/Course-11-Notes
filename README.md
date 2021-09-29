# Course-11-Notes

# DPLYR 2-TABLE VERBS

# JOINS
R-CODES:
>inner_join(data1,data2, by = "ID") %>% kable() %>% kable_styling(font_size = 12, position = "left")

inner_join retains only the records that match both data1 and data2.

R-CODES:
>left_join(data1, data2, by = "ID") %>% kable() %>% kable_styling(font_size = 12, postion = "left")

left_join retains all the records from data1 and returns NA if there is no match in data2.

R-CODES:
>right_join(data1, data2, by = "ID") %>% kable() %>% kable_styling(font_size = 12, postion = "left")

right_join retains all the records from data2 and returens NA if there is no match in data1.

R-CODES:
>full_join(data1, data2, by = "ID") %>% kable() %>% kable_styling(font_size = 12, postion = "left")

full_join retains all the records from both data1 and data2 and returns NA where there are no matches.

R-CODES:
>semi_join(data1, data2, by = "ID") %>% kable() %>% kable_styling(font_size = 12, postion = "left")

semi_join retains the rows in data1 that have a match in data2.

R-CODES:
>anti_join(data1, data2, by = "ID") %>% kable() %>% kable_styling(font_size = 12, postion = "left")

anti_join retains only the rows in data1 that DO NOT have a match in data2.



