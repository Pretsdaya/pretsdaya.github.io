# Electric Aircraft Feasibility Calculation 

## Airplane Energy Calculation

Energy required is Drag x Range:
$$
E = D.R
$$
For a 500km journey:
$$
R = 500000m
$$
For a L/D of 16, and an aircraft mass of 8000kg.
$$
m=8000kg
$$
Therefore:
$$
W = m.g = 8000 \times 10 = 80000N
$$
Lift equals weight:
$$
L = W
$$
Therefore Drag is:
$$
D = \frac{L}{\left(\frac{L}{D}\right)} = \frac{80000}{16} = 5000N
$$
Therefore Energy is:
$$
E = D.R = 5000 \times 500000 = 2500MJ
$$

## Battery Mass Requirement

<https://en.wikipedia.org/wiki/Lithium-ion_battery>

From the above reference for Li-ion batteries, the best specific energy density is:
$$
\frac{E}{m_{battery}} = 0.875 MJ/kg
$$
Therefore:
$$
m_{battery} = \frac{2500}{0.875} = 2857 kg
$$
Of course this is for 100% efficiency, so I would say it would be more like 4000kg.