# RF_Probe



## Measuring QRP Transmitter Output Power  

The test setup required to perfrom transmitter output power measurement is depicted below:

Depending on RF probe type formulas used to calculate output power differ slightly.

In this section we will consider half-wave rectifier and full-wave rectifier (prototyped) probes.

In case of both designs we start with generic Power equations (we assume dummy load to fully resistive for 
all frequencies measurements are conducted for):

$\P=U*I$
knowing that $\R=U/I$, we can express current as: $I=U/R$, which when plugged into power equation above
gives us:
$\P=U*2/R$

$\sqrt{3x-1}+(1+x)^2$