File Format:
|D|	|W|
0	x_0	y_0
w_j	x_j	y_j	q_j	h_j	s_j
...
d_i	x_i	y_i	e_i	E_i	I_i	u_i	q_i	s_i	f_i
...
where
|D| --- base station number
|W| --- warehouse number
0 --- depot
x_i --- x-coordinates, i \in {0, W, D}
y_i --- y-coordinates, i \in {0, W, D}
w_j --- warehouse index, j \in {1,...,|W|}
q_j --- warehouse stock
h_j --- rental cost
s_j --- service time
d_i --- base station index, i \in {1,...,|D|}
e_i --- recharge rate
E_i --- battery capacity
I_i --- initial SoC
u_i --- power consumption
q_i --- maximal delivery quantity
s_i --- service time
f_i --- outage cost
