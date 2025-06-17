# Installing-pandas-work-with-series-with-different-datatypes

pip install pandas
import pandas as pd
int_series=pd.Series([3,4,5,6,9,7,8])

print("int series:\n",int_series)

O/P:

int series:

0 3

1 4

2 5

3 6

4 9

5 7

6 8

dtype: int64

****float datatype*****

import pandas as pd

float_series=pd.Series([3.2,4.4,5.6,6.8])

print("float series:\n",float_series)

O/P:

float series:

0 3.2

1 4.4
2 5.6

3 6.8

dtype: float64

****string datatype****

import pandas as pd

string_series=pd.Series(["kiran","kumar"])

print("string series:\n",string_series)

O/P:

string series:

0 kiran

1 kumar

dtype: object

****mixed string datatype****

import pandas as pd

mixed_series=pd.Series(["kiran",5,6,"sola",8,9,"vishnu"])

print("mixed string series:\n",mixed_series)

O/P:

mixed string series:

0 kiran 
1 5

2 6

3 sola

4 8

5 9

6 vishnu

dtype: object
