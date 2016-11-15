# IMU-MEMS-Format
Extrapolate the data and convert the $n_{readings} \times 3$ dataframe into $n_{samples} \times \left( 3n_{sensors}+2\right)$ dataframe, where $n_{samples}=ceil \left( f_s . timespan (df_{read}) \right)$
