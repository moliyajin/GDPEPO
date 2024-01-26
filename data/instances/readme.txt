Each instance file contains four warehouses.
To run instances with m warehouses, read the first m lines which correspond to warehouse parameters.
File Format:
|D|	|W|
0	x_0	y_0
w_1	x_1	y_1	q_1	h_1	s_1
...
w_4	x_4	y_4	q_4	h_4	s_4
d_i	x_i	y_i	e_i	E_i	I_i	u_i	q_i	s_i	f_i
...
where
|D| --- base station number
|W| --- warehouse number
0 --- depot
x_i --- longitude, i \in {0, W, D}
y_i --- latitude, i \in {0, W, D}
w_1 --- warehouse index
q_1 --- warehouse stock
h_1 --- rental cost
s_1 --- service time
d_i --- base station index, i \in {1,...,|D|}
e_i --- recharge rate
E_i --- battery capacity
I_i --- initial SoC
u_i --- power consumption
q_i --- maximal delivery quantity
s_i --- service time
f_i --- outage cost
